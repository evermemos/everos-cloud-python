# Changelog

## 0.5.0 (2026-07-18)

Full Changelog: [v0.4.1...v0.5.0](https://github.com/evermemos/everos-cloud-python/compare/v0.4.1...v0.5.0)

### Features

* **stlc:** configurable CI runner and private-production-repo support in workflow templates ([9d35f6f](https://github.com/evermemos/everos-cloud-python/commit/9d35f6f71971f4f1ad5757c84a91c7e53e66d65b))


### Bug Fixes

* **internal:** resolve build failures ([491d75e](https://github.com/evermemos/everos-cloud-python/commit/491d75efdf344209258476ff7a21f3454eea90f2))

## 0.4.1 (2026-06-03)

Full Changelog: [v0.4.0...v0.4.1](https://github.com/evermemos/everos-cloud-python/compare/v0.4.0...v0.4.1)

### Features

* **api:** api update ([f0aeb1f](https://github.com/evermemos/everos-cloud-python/commit/f0aeb1f3820928ac8259334770321c5cda3e8165))
* **internal/types:** support eagerly validating pydantic iterators ([1451fbd](https://github.com/evermemos/everos-cloud-python/commit/1451fbd01d833fcb2599a568ee21c9f676202652))
* **lib:** add multimodal auto-upload support (everos_cloud) ([18c684d](https://github.com/evermemos/everos-cloud-python/commit/18c684dcbacec3dd958264eb28c79935ea31df0d))
* support setting headers via env ([46b59a6](https://github.com/evermemos/everos-cloud-python/commit/46b59a6740b55edd90c03397378fcd42ad424688))


### Bug Fixes

* bump version for pypi release ([2ed21af](https://github.com/evermemos/everos-cloud-python/commit/2ed21afdb5cc767630c63da04f5dd1700731f6ab))
* **client:** add missing f-string prefix in file type error message ([6cba326](https://github.com/evermemos/everos-cloud-python/commit/6cba32602459373cfc9fb8b59084def350157c70))
* **client:** preserve hardcoded query params when merging with user params ([3f38e05](https://github.com/evermemos/everos-cloud-python/commit/3f38e05f05eaf4531a2be132ad5db86c7b00fe55))
* ensure file data are only sent as 1 parameter ([7f97423](https://github.com/evermemos/everos-cloud-python/commit/7f9742390013fde1d28ce3c9a1c42b0222bd8122))
* use correct field name format for multipart file arrays ([303537d](https://github.com/evermemos/everos-cloud-python/commit/303537d277358e0a409c536f3d663608e9aa638e))


### Performance Improvements

* **client:** optimize file structure copying in multipart requests ([b7c0131](https://github.com/evermemos/everos-cloud-python/commit/b7c013138f18ebb4da63772a1dbd7ed5a8d52daa))


### Chores

* **internal:** more robust bootstrap script ([7dad341](https://github.com/evermemos/everos-cloud-python/commit/7dad3415471d7207d53d6909826e3a9f6660590d))
* **internal:** reformat pyproject.toml ([f0b5ef6](https://github.com/evermemos/everos-cloud-python/commit/f0b5ef649b2d41029021ab1ff0416d18876f26f7))
* remove custom code ([dda0348](https://github.com/evermemos/everos-cloud-python/commit/dda03486c1d7fe35f09abf51fd808283995bfc8e))
* sync repo ([2a8b508](https://github.com/evermemos/everos-cloud-python/commit/2a8b5087178026f880fa50476616c8992cc6d640))
* update SDK settings ([e6ddf18](https://github.com/evermemos/everos-cloud-python/commit/e6ddf185ee0fcbc1dbb34bdcc91f28e4691100fb))
* update SDK settings ([f2b8801](https://github.com/evermemos/everos-cloud-python/commit/f2b8801fac3560825f15c10080f929f64104749e))
* update SDK settings ([4766c46](https://github.com/evermemos/everos-cloud-python/commit/4766c4676141a1bc9102d40becae7cbf10f650e4))
* update SDK settings ([4ddded1](https://github.com/evermemos/everos-cloud-python/commit/4ddded1484ae5cfa9df090aad003532b1f3ef621))
* update SDK settings ([68703ac](https://github.com/evermemos/everos-cloud-python/commit/68703ac328d743e307d9dfd30bd7b52b8d894dba))
* update SDK settings ([bdb213a](https://github.com/evermemos/everos-cloud-python/commit/bdb213a592f0665a038128b222b6ccdc882a29fd))
* update SDK settings ([5c4bbb3](https://github.com/evermemos/everos-cloud-python/commit/5c4bbb3c610ae5bda82cb23c40861d0071066e4b))

## 0.4.0 (2026-04-09)

Full Changelog: [v0.2.0...v0.4.0](https://github.com/evermemos/everos-python/compare/v0.2.0...v0.4.0)

### Bug Fixes

* bump version for pypi release ([2ed21af](https://github.com/evermemos/everos-python/commit/2ed21afdb5cc767630c63da04f5dd1700731f6ab))

## 0.2.0 (2026-04-08)

Full Changelog: [v0.1.1...v0.2.0](https://github.com/evermemos/everos-python/compare/v0.1.1...v0.2.0)

### Bug Fixes

* **client:** preserve hardcoded query params when merging with user params ([3f38e05](https://github.com/evermemos/everos-python/commit/3f38e05f05eaf4531a2be132ad5db86c7b00fe55))

## 0.1.1 (2026-04-01)

Full Changelog: [v0.0.1...v0.1.1](https://github.com/evermemos/everos-python/compare/v0.0.1...v0.1.1)

### Features

* **api:** api update ([f0aeb1f](https://github.com/evermemos/everos-python/commit/f0aeb1f3820928ac8259334770321c5cda3e8165))


### Chores

* sync repo ([2a8b508](https://github.com/evermemos/everos-python/commit/2a8b5087178026f880fa50476616c8992cc6d640))
* update SDK settings ([68703ac](https://github.com/evermemos/everos-python/commit/68703ac328d743e307d9dfd30bd7b52b8d894dba))
* update SDK settings ([bdb213a](https://github.com/evermemos/everos-python/commit/bdb213a592f0665a038128b222b6ccdc882a29fd))
* update SDK settings ([5c4bbb3](https://github.com/evermemos/everos-python/commit/5c4bbb3c610ae5bda82cb23c40861d0071066e4b))
