# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0](https://github.com/pavlokomarov/roach-php-core/compare/1.1.1...v2.0.0) (2023-04-04)


### ⚠ BREAKING CHANGES

* add namespace to run and scheduler ([#105](https://github.com/pavlokomarov/roach-php-core/issues/105))

### Features

* add namespace to run and scheduler ([#105](https://github.com/pavlokomarov/roach-php-core/issues/105)) ([167e824](https://github.com/pavlokomarov/roach-php-core/commit/167e824362a9507caa3cc03200eb546d51e35437))
* add ResponseReceiving and ResponseReceived events ([96c9332](https://github.com/pavlokomarov/roach-php-core/commit/96c9332c796cf8c64ca8bd15885580b49354a78c))
* allow request middleware to set a response to bypass downloader ([#106](https://github.com/pavlokomarov/roach-php-core/issues/106)) ([d8ae43e](https://github.com/pavlokomarov/roach-php-core/commit/d8ae43ea5efb7f1cd729fc6dab19756beddb4702))


### Bug Fixes

* rename integration tests so they actually get run ([33eb25e](https://github.com/pavlokomarov/roach-php-core/commit/33eb25e31769d1d3080174341efeac06cd89ee45))


### Miscellaneous Chores

* (deps): bump symfony/console from 6.2.5 to 6.2.7 ([#93](https://github.com/pavlokomarov/roach-php-core/issues/93)) ([4f535da](https://github.com/pavlokomarov/roach-php-core/commit/4f535da0d95f6e5a88bea4c1e5d9c7f3219388c6))
* (deps): bump symfony/css-selector from 6.2.5 to 6.2.7 ([20fc15b](https://github.com/pavlokomarov/roach-php-core/commit/20fc15b708c6c486b49a2c766630b42512df25c6))
* (deps): bump symfony/dom-crawler from 6.2.5 to 6.2.7 ([#92](https://github.com/pavlokomarov/roach-php-core/issues/92)) ([25e4831](https://github.com/pavlokomarov/roach-php-core/commit/25e48316e49408ad2ce120e76d56fa70be8864dc))
* add code of conduct ([ed80fbe](https://github.com/pavlokomarov/roach-php-core/commit/ed80fbe7919d0a518d54a4ba48b8cefb0565f6cc))
* add CODEOWNERS file ([9efec92](https://github.com/pavlokomarov/roach-php-core/commit/9efec92ce1ba244cbd205037e8c3463d6986f054))
* add commitlint step to pipeline ([64e785a](https://github.com/pavlokomarov/roach-php-core/commit/64e785a0a04c5697ec91f17905190cbc062512ce))
* add contribution guide ([bdb57e0](https://github.com/pavlokomarov/roach-php-core/commit/bdb57e0824cb4c883be3d9109696c74d88586644))
* add issue templates ([5c4fd81](https://github.com/pavlokomarov/roach-php-core/commit/5c4fd81a3a3caa7ee6b3ab42d69f85d0e02dbfbe))
* **deps-dev:** bump ergebnis/composer-normalize from 2.29.0 to 2.30.2 ([980b920](https://github.com/pavlokomarov/roach-php-core/commit/980b92040b6f6ea38907a49d296f69f9a91ab606))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.3.1 to 5.3.2 ([44d81c9](https://github.com/pavlokomarov/roach-php-core/commit/44d81c9855542fec1f8f1c342d666e1ca6680350))
* **deps-dev:** bump ergebnis/php-cs-fixer-config from 5.3.2 to 5.3.3 ([7b6f59f](https://github.com/pavlokomarov/roach-php-core/commit/7b6f59fab7bb75efcbacc848122ed23b840b560f))
* **deps-dev:** bump phpunit/phpunit from 10.0.15 to 10.0.16 ([57b4d03](https://github.com/pavlokomarov/roach-php-core/commit/57b4d03bd6ca00c5b17af81ac8ebbc8382c91677))
* **deps-dev:** bump phpunit/phpunit from 10.0.16 to 10.0.18 ([a5fe27a](https://github.com/pavlokomarov/roach-php-core/commit/a5fe27ad0cadb3f74da4916f7b1a97d27abe144c))
* **deps-dev:** bump vimeo/psalm from 5.6.0 to 5.8.0 ([b60588a](https://github.com/pavlokomarov/roach-php-core/commit/b60588ad6e60bd6eb8146466202bd8baf12ad8f0))
* **deps:** bump psy/psysh from 0.11.12 to 0.11.13 ([4542cbf](https://github.com/pavlokomarov/roach-php-core/commit/4542cbf00fe2b02a86d5b2048a97556706adf44f))
* **deps:** bump symfony/event-dispatcher from 6.2.5 to 6.2.7 ([3a19510](https://github.com/pavlokomarov/roach-php-core/commit/3a19510e0457867f0a307c8511e2cb0ef85a8e6b))
* **deps:** bump symfony/options-resolver from 6.2.5 to 6.2.7 ([#89](https://github.com/pavlokomarov/roach-php-core/issues/89)) ([fe24ee3](https://github.com/pavlokomarov/roach-php-core/commit/fe24ee3241546c3dc968537b344040dd9bb3c483))
* set up dependabot ([29fb85e](https://github.com/pavlokomarov/roach-php-core/commit/29fb85ee3e7db67b855a2999b1af592253043e1a))
* set up release please action ([5a7df32](https://github.com/pavlokomarov/roach-php-core/commit/5a7df32ca5fc8816fd4e7b6273eb5071f1203e00))
* upgrade to phpunit 10 ([fd83095](https://github.com/pavlokomarov/roach-php-core/commit/fd830953f85f3ad7a06c04988ca39a24718c5e46))

## [2.0.1] – 2023-02-17

### Fixed

- Fixed version incompatibility with `sebastian/version` depenency

## [2.0.0] – 2023-02-06

### Added

- Added `userAgent` option to `ExecuteJavascriptMiddleware` (#82)
- Added `delay` option to `ExecuteJavascriptMiddleware` (#72)

### Changed

- Dropped PHP 8.0 support
- Updated various dependencies

## [1.1.1] — 2022-09-09

### Changed

- `ExecuteJavascriptMiddleware` now uses `waitUntilNetworkIdle` before returning the response body (#56)

## [1.1.0] — 2022-06-22

### Added

- Added a way to define custom item classes as well as item processors which only process certain
  types of items (#47)

### Changed

- Fixed deprecation warning in console commands for `symfony/console:^6.1` (#44)

## [1.0.0] — 2022-04-19

### Added

- Added `Roach::collectSpider` method to start a spider run and return all scraped items.
- Added `array $context` parameter to `Roach::startSpider` and `Roach::collectSpider` to pass arbitrary
  context data to a spider when starting a run.
- Added `roach:run <spider>` command to start a spider through the CLI.
- Added `Roach::fake()` method to test that a run for a given spider was started

### Changed

- Requests dropped by downloader middleware are no longer affected by `requestDelay` (fixes #27)
- Move `spatie/browsershot` from a `require` to `suggest` as it's only necessary if the `ExecuteJavascriptMiddleware` is used.
  Remove `ext-exif` as a dependency for the same reason.

### Removed

- Removed default command from CLI. To start the REPL, you now need to explicitly invoke the `roach:shell <url>` command, instead.

## [0.2.0] - 2021-12-28

### Added

- Added `ExecuteJavascriptMiddleware` to retrieve a page’s body after executing Javascript (#7)

## [0.1.0] - 2021-12-27

### Added

- Initial release

[2.0.0]: https://github.com/roach-php/core/compare/1.1.1...2.0.0
[1.1.1]: https://github.com/roach-php/core/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/roach-php/core/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/roach-php/core/compare/0.2.0...1.0.0
[0.2.0]: https://github.com/roach-php/core/compare/0.1.0...0.2.0
