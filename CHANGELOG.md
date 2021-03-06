# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [0.3.4] - 2018-10-09
### Fixed
- Issue while calling soft deletes macros staticly.

## [0.3.3] - 2018-10-09
### Adds
- Support for Soft Deletes

## [0.3.2] - 2018-10-05
### Adds
- Support to return type of `redirect` & `view` helpers ([#157](https://github.com/nunomaduro/larastan/pull/157))

## [0.3.1] - 2018-10-04
### Fixes
- Usage with Laravel 5.6 ([2d13d9a](https://github.com/nunomaduro/larastan/commit/2d13d9a3ae0f2a50739ecc25e3b5860199486d7e))

## [0.3.0] - 2018-10-04
### Adds
- Support for static analysis in Laravel Packages

## [0.2.12] - 2018-09-27
### Adds
- Support to return type of `request` helper ([#145](https://github.com/nunomaduro/larastan/pull/145))

## [0.2.11] - 2018-09-21
### Adds
- Support to return type of `response` helper
- Support to return type of `\Illuminate\Http\Response::input` method

### Fixes
- False positives when performing long Eloquent queries
- Issue when there is recursive mixins
- When container got used twice using the `ArrayAccess` interface

## [0.2.10] - 2018-09-12
### Fixes
- Issue while using invalid mixins ([#137](https://github.com/nunomaduro/larastan/pull/137))

## [0.2.9] - 2018-09-01
### Fixes
- Usage of spaces with the option `--paths`

## [0.2.8] - 2018-09-01
### Fixes
- Issue while resolving implementations from container

## [0.2.7] - 2018-08-27
### Fixes
- Issue on Windows with the default path param ([#128](https://github.com/nunomaduro/larastan/pull/128))
- Issue with exit code ([#115](https://github.com/nunomaduro/larastan/pull/115))
- While running Larastan on CI envs ([#113](https://github.com/nunomaduro/larastan/pull/113))

## [0.2.6] - 2018-08-27
### Added
- Support to Laravel 5.7

## [0.2.5] - 2018-08-17
### Fixes
- Issue with option `errorFormat` ([#121](https://github.com/nunomaduro/larastan/pull/121))

## [0.2.4] - 2018-07-24
### Fixes
- Issue while resolving implementations that don't exist on the container

## [0.2.3] - 2018-07-23
### Fixes
- Common laravel false positives on trusted proxies and app exception handler

## [0.2.2] - 2018-07-23
### Fixes
- Resolved null type from container

## [0.2.1] - 2018-07-23
### Fixes
- Error - "internal error: * product does not exist"

## [0.2.0] - 2018-07-22
### Fixes
- Issues while using Lumen

## [0.1.9] - 2018-07-22
### Adds
- Support to Lumen and Laravel Zero

## [0.1.8] - 2018-07-22
### Adds
- Support to builder dynamic wheres

## [0.1.7] - 2018-07-22
### Adds
- Support to "object" return type

### Fixes
- Bug on macro extension

## [0.1.6] - 2018-07-22
### Adds
- Allows array access on objects that respects container's contract

## [0.1.5] - 2018-07-22
### Fixes
- Removes unused `dd`

## [0.1.4] - 2018-07-22
### Fixes
- Issue when `static` is missing was return type hint on Illuminate Model mixins

## [0.1.3] - 2018-07-20
### Fixes
- Usage on Windows + Laravel Homestead ([#55](https://github.com/nunomaduro/larastan/pull/55))

## [0.1.2] - 2018-07-20
### Adds
- `Illuminate\Contracts` property extension

## [0.1.1] - 2018-07-18
### Fixes
- Infinite recursion in mixins middleware ([b5a4317](https://github.com/nunomaduro/larastan/commit/b5a4317ef7c19b9008e4efff7ef50d2649b00151))

## [0.1.0] - 2018-07-17
### Added
- Adds first alpha version
