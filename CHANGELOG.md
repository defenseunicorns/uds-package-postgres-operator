# Changelog

All notable changes to this project will be documented in this file.

## [1.13.0-uds.2](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.13.0-uds.1...v1.13.0-uds.2) (2024-09-25)


### ⚠ BREAKING CHANGES

* add additional config options and update default pasword encryption for fips ([#65](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/65))

### Features

* add additional config options and update default pasword encryption for fips ([#65](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/65)) ([a3e23b4](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/a3e23b4d75f67832d1d2452c068e0155805d12f0))

## [1.13.0-uds.1](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.13.0-uds.0...v1.13.0-uds.1) (2024-09-19)


### Features

* expose resources and additionalVolumes for HugePages ([#63](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/63)) ([49152b3](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/49152b36cee10c7314f04811a7a9e2341f122ccb))

## [1.13.0-uds.0](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.12.2-uds.2...v1.13.0-uds.0) (2024-08-27)


### Miscellaneous

* **deps:** update postgres package dependencies ([#59](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/59)) ([cae5ab8](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/cae5ab894e7b203b73ef3b7d3f57d5f04be93caf))

## [1.12.2-uds.2](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.12.2-uds.1...v1.12.2-uds.2) (2024-07-31)


### Features

* **metrics:** building blocks for postgres exporter ([#53](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/53)) ([c2a47bc](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/c2a47bc77ccf3fda6f302a11968d879337ff4957))


### Miscellaneous

* add `Made for UDS` badge ([#57](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/57)) ([2aa0328](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/2aa032862718c462f51032a2951f26249e344f98))
* **deps:** update postgres support dependencies ([#50](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/50)) ([18c6c03](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/18c6c03b5dc1fdc583277f40b1233779ac43ec9a))
* **deps:** update postgres support dependencies ([#56](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/56)) ([a79c9c6](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/a79c9c68e18fdf0b7d97852b9a2af3615f911428))
* **deps:** update support-deps to v3.25.15 ([#55](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/55)) ([84d4c33](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/84d4c33818eaefa72b241d733b937620b627762c))

## [1.12.2-uds.1](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.12.2-uds.0...v1.12.2-uds.1) (2024-07-09)


### Bug Fixes

* netpol selector correction for ingress to pg-cluster ([#48](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/48)) ([8c28aea](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/8c28aea517b087093b509636c0e47ef37ad7141d))


### Miscellaneous

* **deps:** update support-deps to v4.3.4 ([#47](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/47)) ([54c533b](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/54c533b3befbd7330abec4c84e2644e18beb7eb0))
* fix arm runner name ([#45](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/45)) ([298ef55](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/298ef5519d24eca3b13550b966db7eb6dbe3c6f1))

## [1.12.2-uds.0](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.11.0-uds.2...v1.12.2-uds.0) (2024-07-03)


### Miscellaneous

* add architecture to publish job name ([#42](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/42)) ([5a6d73f](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/5a6d73f5d7731d919493e6d29614c1bf3739fc9b))
* add pre release testing ([#40](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/40)) ([ac40af4](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/ac40af4a8b24885f2cb8dac81d45a8e8caae0f50))
* **deps:** update postgres package dependencies ([#30](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/30)) ([034910c](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/034910cb2ff1fb13cf8a711931204aa5fc0dcd49))
* **deps:** update postgres support dependencies ([#39](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/39)) ([597c22e](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/597c22e8e4b06187ed77d77d4ad94c60c0ae5fab))
* normalize the repository README and remove `.vscode` ([#43](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/43)) ([aa54ab8](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/aa54ab8882e317bc53092d3c1ef44a44bd72f7ad))
* update license ([#38](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/38)) ([a8180ac](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/a8180ac5c54e6733c3bbc715a04ad588e8864bbe))

## [1.11.0-uds.2](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.11.0-uds.1...v1.11.0-uds.2) (2024-06-12)


### ⚠ BREAKING CHANGES

* enable istio and netpols for everything ([#37](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/37))

### Features

* enable istio and netpols for everything ([#37](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/37)) ([642a38d](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/642a38d91f07e5564e9c74742c8a8f0be2a860cf))


### Miscellaneous

* cleanup the repo ([#34](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/34)) ([6fa6840](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/6fa6840f61b3fca289fd0e2b8a4a42f807bd850e))
* **deps:** update postgres support dependencies ([#29](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/29)) ([1c55b70](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/1c55b7010c9efc5f2c3e8a18d7d63a82b61e27e8))
* **deps:** update postgres support dependencies ([#36](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/36)) ([87c07ab](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/87c07ab27de9703cb6bd8cb15cc076dbdb870956))

## [1.11.0-uds.1](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.11.0-uds.0...v1.11.0-uds.1) (2024-06-07)


### Features

* add wait for PGO package CR readiness ([#32](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/32)) ([1d8056a](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/1d8056ab7ca35f15a7870055829f6ad28998a2d2))


### Miscellaneous

* change image refs to support multi arch ([#33](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/33)) ([963a962](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/963a9629fb5392b549544fdd5340fbca0a3f1d2c))
* **deps:** update postgres support dependencies ([#24](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/24)) ([e08e679](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/e08e67942f8c502a3819c15be5eb35407b53c7de))
* **deps:** update postgres support dependencies ([#26](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/26)) ([7d02d31](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/7d02d3171cb02b69e515f56199de9ae12a43eb0f))
* fix the allowed versions of postgres ([#28](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/28)) ([4839d50](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/4839d5080189428a4b8d977fb718c3b9f6ba3638))

## [1.11.0-uds.0](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.5...v1.11.0-uds.0) (2024-04-05)


### Miscellaneous

* add formatting to make the warning stand out more ([#23](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/23)) ([42fca2f](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/42fca2fbb0aa58bfc895215cbeee94721ac2b6b1))
* **deps:** update postgres package dependencies ([#16](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/16)) ([b91ec33](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/b91ec332e0f73973b98c0b31af0915e0900b85a8))
* **deps:** update postgres support dependencies ([#22](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/22)) ([a7fefa8](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/a7fefa8f321b9898e5754a2ccba916991ddd9b18))
* fix missing import in publish task ([#20](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/20)) ([ff35f91](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/ff35f9183f3eb3757e339f6e2c0472eb5f1fc971))

## [1.10.1-uds.5](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.4...v1.10.1-uds.5) (2024-03-29)


### Miscellaneous

* **deps:** update postgres support dependencies ([#17](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/17)) ([0a37841](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/0a3784196133d7495b4f38b4a4edea7e4c5dc632))
* hotfix renovate config registries ([6238f93](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/6238f9367ebb3d0a42b20722eb4a8186c6705137))
* update to uds-common v0.3.9 and add upgrade-tests ([5a581ca](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/5a581ca1914eb185312905ad2dbe057dd382b370))

## [1.10.1-uds.4](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.3...v1.10.1-uds.4) (2024-03-05)


### ci

* fix oci publish issue ([#11](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/11)) ([6ab7735](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/6ab7735dce5b61de9f4589f51ad5c7a14397e8d4))

## [1.10.1-uds.3](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.2...v1.10.1-uds.3) (2024-03-04)


### ci

* update remote publish task to latest ([#9](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/9)) ([046d961](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/046d96157bc22dfc1164685eb9d6f2c84fde2302))

## [1.10.1-uds.2](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.1...v1.10.1-uds.2) (2024-03-04)


### ci

* fix publish create task ([#7](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/7)) ([567301f](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/567301f92b6be6f705532fd332087422521a82dc))

## [1.10.1-uds.1](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.0...v1.10.1-uds.1) (2024-03-04)


### Miscellaneous

* release 1.10.1-uds.1 ([#5](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/5)) ([5ebac86](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/5ebac865bd256ec9a3e5dc9518acf5843b707abe))

## [1.10.1-uds.0](https://github.com/defenseunicorns/uds-package-postgres-operator/compare/v1.10.1-uds.0...v1.10.1-uds.0) (2024-03-02)


### Features

* initial uds postgres operator with optional database deployment chart ([#2](https://github.com/defenseunicorns/uds-package-postgres-operator/issues/2)) ([344b8ea](https://github.com/defenseunicorns/uds-package-postgres-operator/commit/344b8eaf412c864344411de0d6a62ef01e6f7485))

## [0.0.0] - YYYY-MM-DD
PRE RELEASE

### Added
- Initial CHANGELOG.md
- CODEOWNERS
- CONTRIBUTING.md
- DEVELOPMENT_MAINTENANCE.md
- LICENSE
- READEME.md
- zarf.yaml
