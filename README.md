# 🏭 UDS Postgres Operator Package

[![Latest Release](https://img.shields.io/github/v/release/defenseunicorns/uds-package-postgres-operator)](https://github.com/defenseunicorns/uds-package-postgres-operator/releases)
[![Build Status](https://img.shields.io/github/actions/workflow/status/defenseunicorns/uds-package-postgres-operator/tag-and-release.yaml)](https://github.com/defenseunicorns/uds-package-postgres-operator/actions/workflows/tag-and-release.yaml)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/defenseunicorns/uds-package-postgres-operator/badge)](https://api.securityscorecards.dev/projects/github.com/defenseunicorns/uds-package-postgres-operator)

This package is designed for use as part of a [UDS Software Factory](https://github.com/defenseunicorns/uds-software-factory) bundle deployed on [UDS Core](https://github.com/defenseunicorns/uds-core).

## Prerequisites

- [K3D](https://k3d.io/) for dev & test environments or any [CNCF Certified Kubernetes Cluster](https://www.cncf.io/training/certification/software-conformance/#logos) for production environments.

- [UDS CLI](https://github.com/defenseunicorns/uds-cli?tab=readme-ov-file#install) v0.9.2 or later

## Flavors

| Flavor | Description | Example Creation |
| ------ | ----------- | ---------------- |
| upstream | Uses upstream images within the package. | `uds zarf package create . -f upstream` |
| registry1 | Uses images from registry1.dso.mil within the package. | `uds zarf package create . -f registry1` |

Note: the registry1 flavor uses `ghcr.io/zalando/spilo-15:3.0-p1` published from GHCR as there is not a spilo image in Iron Bank

## Releases

The released packages can be found in [ghcr](https://github.com/defenseunicorns/uds-package-postgres-operator/pkgs/container/packages%2Fuds%2Fpostgres-operator).

## UDS Tasks (for local dev and CI)

*For local dev, this requires installing [uds-cli](https://github.com/defenseunicorns/uds-cli?tab=readme-ov-file#install)

After installing uds-cli, for a list of available tasks that can be run in this repository execute the following command:

`uds run --list`

## Contributing

Please see the [CONTRIBUTING.md](./CONTRIBUTING.md)
