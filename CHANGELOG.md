# Change Log

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
