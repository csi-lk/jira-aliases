# Changelog

## [2.3.0](https://github.com/csi-lk/jira-aliases/compare/v2.2.1...v2.3.0) (2023-08-21)


### Features

* add 'my' command to get all my tickets ([e2819d8](https://github.com/csi-lk/jira-aliases/commit/e2819d88ce97c652cef4be5ac534b2d697cd0d0e))

## [2.2.1](https://github.com/csi-lk/jira-aliases/compare/v2.2.0...v2.2.1) (2023-08-15)


### Bug Fixes

* colors can not be included before installed ([03ff301](https://github.com/csi-lk/jira-aliases/commit/03ff30169cc9dc762b19efe83d0ec5eca466b1dd))
* config path incorrect and echo creating file missing ([f97a9c2](https://github.com/csi-lk/jira-aliases/commit/f97a9c201cd5f1ecba0b040866595882be96b975))
* don't exit during config setup ([a2a327e](https://github.com/csi-lk/jira-aliases/commit/a2a327ea7d0bd98bfeb19a442cf6d3e7b9581980))
* don't run setup as part of installation as script pauses ([37a36f2](https://github.com/csi-lk/jira-aliases/commit/37a36f26814d23349b149a0ef225f47f644113cb))
* installation path was incorrect, should be home dir based ([ac73af0](https://github.com/csi-lk/jira-aliases/commit/ac73af003138a9ae9170202b461e3cb262fd5950))
* installation script still pointing at incorrect path ([05c8962](https://github.com/csi-lk/jira-aliases/commit/05c8962250c2dd8064023b77eebafb5526bacb5d))
* only get latest release if the config has a version set ([7b4b725](https://github.com/csi-lk/jira-aliases/commit/7b4b7250b86d4b29b6cabed545cadac01071cbb2))

## [2.2.0](https://github.com/csi-lk/jira-aliases/compare/v2.1.0...v2.2.0) (2023-08-14)


### Features

* add 'info' command for getting info about focused or x ticket ([fdabfbd](https://github.com/csi-lk/jira-aliases/commit/fdabfbdc26fb342604ce65a19621e1d83e2aed2d))

## [2.1.0](https://github.com/csi-lk/jira-aliases/compare/v2.0.0...v2.1.0) (2023-08-14)


### Features

* assign ticket to me ([4bc2206](https://github.com/csi-lk/jira-aliases/commit/4bc22066860188dd769dba2f15ac09ead43d8dc5))

## [2.0.0](https://github.com/csi-lk/jira-aliases/compare/v1.5.0...v2.0.0) (2023-08-14)


### ⚠ BREAKING CHANGES

* add jq requirement

### Documentation

* add jq requirement ([8cc4719](https://github.com/csi-lk/jira-aliases/commit/8cc4719f4054b8d4d6b6fc158378c692a996a8dd))

## [1.5.0](https://github.com/csi-lk/jira-aliases/compare/v1.4.1...v1.5.0) (2023-08-14)


### Features

* get transitions based on names from API ([28e2935](https://github.com/csi-lk/jira-aliases/commit/28e2935cf039c9cff5ad1804c28ba89794068877))

## [1.4.1](https://github.com/csi-lk/jira-aliases/compare/v1.4.0...v1.4.1) (2023-07-26)


### Bug Fixes

* installation script pulling from branch dir not main ([f770572](https://github.com/csi-lk/jira-aliases/commit/f770572a1ac5baa4770954039628724089df7dd1))

## [1.4.0](https://github.com/csi-lk/jira-aliases/compare/v1.3.0...v1.4.0) (2023-07-26)


### Features

* upgrade install script, split files for sourcing ([26c5a99](https://github.com/csi-lk/jira-aliases/commit/26c5a99ede00a1004c714941be39e94456df4f2a))

## [1.3.0](https://github.com/csi-lk/jira-aliases/compare/v1.2.0...v1.3.0) (2023-07-25)


### Features

* update version function to now list remote version ([ab7699f](https://github.com/csi-lk/jira-aliases/commit/ab7699f8158823b86f7bc9c1362b7a9b418d1c1e))

## [1.2.0](https://github.com/csi-lk/jira-aliases/compare/v1.1.0...v1.2.0) (2023-07-25)


### Features

* check git for new versions ([6d13ccb](https://github.com/csi-lk/jira-aliases/commit/6d13ccbdaca6ac06e3095e45260e8da34cbbef55))

## [1.1.0](https://github.com/csi-lk/jira-aliases/compare/v1.0.0...v1.1.0) (2023-07-25)


### Features

* add ability to transition ticket to in progress ([384661e](https://github.com/csi-lk/jira-aliases/commit/384661ea8ae2e9ff247918457b09088526f6e061))
* add comboing for commands, update readme ([28bd900](https://github.com/csi-lk/jira-aliases/commit/28bd900ad49da4c82187f2d6c06ce4e122861fe9))
* add initial jira alias bash script ([e84c87c](https://github.com/csi-lk/jira-aliases/commit/e84c87cb218babc7820cbd935c3adc00ba85f963))
* add installation script, windows counterpart, version fn ([80ec95a](https://github.com/csi-lk/jira-aliases/commit/80ec95a3eec93539cee817fbfabe12341645d689))
* add more movement targets, todo and done ([6271f13](https://github.com/csi-lk/jira-aliases/commit/6271f13ffc85a7868e6eb9ca0d10e46dc7f0c2d1))
* add open ticket in browser function that remebers last created ([3972075](https://github.com/csi-lk/jira-aliases/commit/3972075656134439875d071595354c8afed885c7))
* add shortcut to move tickets to 'review' ([c2484b5](https://github.com/csi-lk/jira-aliases/commit/c2484b5993031f69fca219dd1719cb7f71a1500f))
* copy ticket to clipboard on mac ([6973195](https://github.com/csi-lk/jira-aliases/commit/697319584f90042a785c4aa5c7846a4ab30b1200))
