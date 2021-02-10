# Change Log

### Fixed

## [1.1.8] - 2021-02-10
 
### Added

### Changed

Updated CONTRIBUTING.md
   
### Fixed

## [1.1.7] - 2021-01-29
 
### Added

### Changed

**!!!Breaking changes!!!**

New certificate is added to the project and implemented directly to the library. Now the same Root CA certificate can be 
used both for MQTTS and OTA Updates. 

In order to use previous version of IoTaaP HAPI Library you can select it using platformio.ini file by adding:
> lib_deps=
    iotaap/IoTaaP HAPI @ 1.1.6

Please be aware that this library is deprecated and we have introduced IoTaaP OS from 2021-01-29, and for any new project
we recommend using IoTaaP OS, although IoTaaP HAPI will still be available.
[**IoTaaP OS is on GitHub**](https://github.com/iotaap/iotaap-os)
   
### Fixed

## [1.1.6] - 2021-01-27
 
### Added

### Changed

License
   
### Fixed

Temporary fix in example for: https://community.platformio.org/t/adafruit-gfx-lib-will-not-build-any-more-pio-5/15776

## [1.1.5] - 2020-04-04
 
### Added

Added functions to enable or disable updates
 
### Changed

Made checkUpdate() public
   
### Fixed

## [1.1.4] - 2020-03-30
 
### Added

Added travis testing and basic example
 
### Changed

Updated IoTaaP Core version dependency
   
### Fixed

Fixed wrong certificate path

## [1.1.3] - 2020-03-30
 
### Added

Added detection if device is standalone or in a group
 
### Changed

Updated IoTaaP Core version dependency
   
### Fixed

Fixed buggy fw version variable
Fixed device publish function with missing topic

## [0.1.3] - 2020-03-30
 
### Added

OTA Upgrade
 
### Changed
   
### Fixed

## [0.1.0] - 2020-03-08
 
### Added

First stable version. Status publishing, publish and device publish working.
Added new IoTaaP Cloud certificate.
Added some future functions templates.
 
### Changed
   
### Fixed
     
## [0.0.1] - 2019-09-15
  
Initial version
 
### Added

Initial documentation
 
### Changed
   
### Fixed