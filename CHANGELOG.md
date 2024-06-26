# Change Log

## [Unreleased]

## [4.2.1] - 2024-03-26
### Changed
- PACKAGE IS RETIRED: With Google's retirement of Google Analytics in favour of GA4 this package is no longer useful as it built on top of Magento's core Google Analytics implementation.

## [4.2.0] - 2023-03-08
### Added
- Support for Php 8.2
### Changed
- Minimum Magento version is now 2.3.0 - for earlier versions please use previous releases

## [4.1.1] - 2022-08-05
### Added
- Compatibility with Magento 2.4.5

## [4.1.0] - 2022-04-12
### Added
- Support for Php 8.0/8.1
- Compatibility with Magento 2.4.4

## [4.0.11] - 2021-08-01
### Added
- Compatibility with Magento 2.4.3

## [4.0.10] - 2021-05-03
### Added
- Compatibility with Magento 2.3.7

## [4.0.9] - 2021-02-03
### Added
- Compatibility with Magento 2.4.2

## [4.0.8] - 2020-10-08
### Added
- Compatibility with Magento 2.4.1 and 2.3.6

## [4.0.7] - 2020-07-30
### Added
- Compatibility with Magento 2.4.0
- Support for Php 7.4
- Ability to switch tracked url to be based on requested uri

## [4.0.6] - 2020-04-28
### Added
- Support for Magento 2.3.5

## [4.0.5] - 2020-01-26
### Added
- Support for Magento 2.2.11 and 2.3.4

## [4.0.4] - 2019-10-08
### Added
- Support for Php 7.3
- Support for Magento 2.3.3
### Fixed
- Normalised url was not used

## [4.0.3] - 2019-09-26
### Security
- Fixed potential XSS due to wrong escape method used

## [4.0.2] - 2019-06-26
### Added
- Support for Magento 2.3.2 and 2.2.9

## [4.0.1] - 2019-03-27
### Added
- Compatibility with Magento 2.3.1

## [4.0.0] 2018-12-02
### Changed
- Package changed into a Metapackage - Implementation moved into fooman/googleanalyticsplus-implementation-m2 package
- Semantic versioning will only be applied to the implementation package
### Fixed
- Add currency code on order tracking data
### Added
- Support for Magento 2.3

## [3.0.0] 2017-09-27
### Changed
- Rewrite to support Magento 2.2.0, most of the added logic is now in 
src/view/frontend/web/js/google-analytics.js
### Added
- Support for PHP 7.1

## [2.0.5] 2017-06-05
### Changed
- Specify compatible php versions

## [2.0.4] 2016-12-30
### Fixed
- Update functional tests to work with 2.1.x

## [2.0.3] - 2016-03-13
### Added
- Initial release for Magento 2
