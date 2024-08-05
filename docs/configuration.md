# Configuration

Postgres Operator is configured through the upstream [Zalando Postgres Operator chart](https://github.com/zalando/postgres-operator/tree/master/charts/postgres-operator) as well as a UDS configuration chart. It implements a database for many [applications within UDS Software Factory](https://github.com/defenseunicorns/uds-software-factory/blob/main/docs/database.md#uds-postgres-operator-package) when one is not available in your cloud provider.

## Networking

Network policies are controlled via the `uds-postgres-config` chart in accordance with the [common patterns for networking within UDS Software Factory](https://github.com/defenseunicorns/uds-software-factory/blob/main/docs/networking.md).  Because Postgres does not interact with external resources like object storage it only implements `custom` networking for the `postgres-operator` namespace:

- `custom`: sets custom network policies for the `postgres-operator` namespace (as a break glass in case you deploy your own postgres cluster custom resources - see below)

## Postgres Clusters

Postgres Operator is configured through [`acid.zalan.do/v1` `Postgresql` custom resources](https://github.com/zalando/postgres-operator/blob/master/docs/reference/cluster_manifest.md#cluster-manifest-reference).  The `uds-postgres-config` chart creates one of these by default which is configurable through the following:

- `postgresql.enabled`: whether to create the default `Postgresql` custom resource (if disabled you will need to apply your own CRs to the cluster)
- `postgresql.teamId`: the name of the team the cluster belongs to (i.e. `uds`)
- `postgresql.volume.size`: the size of the database on disk (i.e. `1Gi`)
- `postgresql.numberOfInstances`: The number of cluster Pods to run in the cluster (i.e. `2`)
- `postgresql.users`: The users to create for the database in the form `{namespace}.{username}` (i.e. `gitlab.gitlab: []`)
- `postgresql.databases`: The database names to create and the users they map to (i.e. `gitlabdb: gitlab.gitlab`)
- `postgresql.version`: The version of Postgres to run (i.e. `14`)
- `postgresql.ingress`: A list of ingress entries to create for this cluster (follows the [custom networking definition](https://github.com/defenseunicorns/uds-software-factory/blob/main/docs/networking.md) except for `direction` which is always `Ingress` and `selector` which is always `cluster-name: pg-cluster`)
