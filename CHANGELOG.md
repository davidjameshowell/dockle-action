## [1.4.0](https://github.com/erzz/dockle-action/compare/v1.3.2...v1.4.0) (2023-08-15)


### :sparkles: New Features

* default to exit code 1 unless overridden should be the default behaviour ([3ab4b31](https://github.com/erzz/dockle-action/commit/3ab4b31cd91327509e65ea67a4660cb0b0c55873))

## [1.3.2](https://github.com/erzz/dockle-action/compare/v1.3.1...v1.3.2) (2022-12-28)


### :bug: Bug Fixes

* Run authenticated requests against the GitHub API ([1dd541c](https://github.com/erzz/dockle-action/commit/1dd541c2bb36b89e3d5f80d0557876135109f536))

## [1.3.1](https://github.com/erzz/dockle-action/compare/v1.3.0...v1.3.1) (2022-07-05)


### :bug: Bug Fixes

* set default DOCKLE_HOST ([2d6a807](https://github.com/erzz/dockle-action/commit/2d6a807cbcfd09b528b193e7acc5f1f2e6b3f763)), closes [/github.com/goodwithtech/dockle/issues/188#issuecomment-1173841064](https://github.com/erzz//github.com/goodwithtech/dockle/issues/188/issues/issuecomment-1173841064)

## [1.3.0](https://github.com/erzz/dockle-action/compare/v1.2.0...v1.3.0) (2022-05-25)


### :package: Maintenance

* **deps:** update github/codeql-action action to v2 ([341faaf](https://github.com/erzz/dockle-action/commit/341faaffa4eca286313101ab5455ad757a6b94bf))


### :sparkles: New Features

* add floating releases for loosely pinning version ([644bc8c](https://github.com/erzz/dockle-action/commit/644bc8c9ec5ec5d23531d56025f35820e98d3b26)), closes [#13](https://github.com/erzz/dockle-action/issues/13)

# [1.2.0](https://github.com/erzz/dockle-action/compare/v1.1.1...v1.2.0) (2022-03-21)


### Bug Fixes

* add a sane default value for new timeout input ([059e164](https://github.com/erzz/dockle-action/commit/059e164d658da4837e7de28e9958c576a3dc5c0e))


### Features

* add option for image pull input ([d8d87c4](https://github.com/erzz/dockle-action/commit/d8d87c4b8b11acf20a8be40d5ee5f86227c49453))

## [1.1.1](https://github.com/erzz/dockle-action/compare/v1.1.0...v1.1.1) (2021-09-20)


### Bug Fixes

* stdout report not being produced when breaking build ([43bd850](https://github.com/erzz/dockle-action/commit/43bd850348b04556ba9e4557ae67666c84099e49))

# [1.1.0](https://github.com/erzz/dockle-action/compare/v1.0.0...v1.1.0) (2021-09-13)


### Features

* add allow rules for credential checks ([38c400a](https://github.com/erzz/dockle-action/commit/38c400ab5ec7844a78af3da010feac3732dcfcbd))

# 1.0.0 (2021-09-01)


### Bug Fixes

* re-run the scan to produce a stdout version of the report too ([5896be3](https://github.com/erzz/dockle-action/commit/5896be3f32f3db6bbbaa05313bd69359aa064a8c))
* upload sarif report with correct action ([7b7bb04](https://github.com/erzz/dockle-action/commit/7b7bb04a12f1f7eedecff6bd39fbc84c5ce6b8a4))


### Features

* add initial composite action ([975b7d5](https://github.com/erzz/dockle-action/commit/975b7d508d233173eea00577e98daa37debef6ec))
