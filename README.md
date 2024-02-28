# uds-package-postgres-operator

> [!WARNING]  
> uds-package-postgres-operator is in early alpha and is not ready for general consumption.

[Short description]

## Prerequisites

- [K3D](https://k3d.io/) for dev & test environments or any [CNCF Certified Kubernetes Cluster](https://www.cncf.io/training/certification/software-conformance/#logos) for production environments.
<!-- renovate: datasource=github-tags depName=defenseunicorns/uds-cli versioning=semver -->
- [UDS CLI](https://github.com/defenseunicorns/uds-cli?tab=readme-ov-file#install) v0.9.2 or later

## Flavors

| Flavor | Description | Example Creation |
| ------ | ----------- | ---------------- |
| upstream | Uses upstream images within the package. | `uds zarf package create . -f upstream` |
| registry1 | Uses images from registry1.dso.mil within the package. | `uds zarf package create . -f registry1` |

## Releases

The released packages can be found in [ghcr](https://github.com/defenseunicorns/uds-package-postgres-operator/pkgs/container/packages%2Fuds%2Fpostgres-operator).

## UDS Tasks (for local dev and CI)

*For local dev, this requires installing [uds-cli](https://github.com/defenseunicorns/uds-cli?tab=readme-ov-file#install)

| Task | Description | Example |
| ---- | ----------- | ------- |
| setup-cluster | Uses the `k3d-core-istio` bundle to create a cluster for testing against | `uds run setup-cluster` |
| create-package | Creates just the Postgres Operator package | `uds run create-package --set FLAVOR=<flavor>` |
| create-test-bundle | Creates Postgres Operator and Postgres Operator test packages and then bundles them | `uds run create-test-bundle` |
| deploy-package | Deploy Postgres Operator package only | `uds run deploy-package` |
| deploy-test-bundle | Deploy Postgres Operator and Postgres Operator dependency bundle | `uds run deploy-test-bundle` |
| test-package | Run checks against a deployed package or bundle | `uds run test-package` |
| cleanup | Teardown the cluster | `uds run cleanup` |

## Contributing

Please see the [CONTRIBUTING.md](./CONTRIBUTING.md)