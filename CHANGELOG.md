# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [3.0.0](https://github.com/tetsuwanadam/capacitor-mixpanel/compare/capacitor-mixpanel-v2.1.1...capacitor-mixpanel-v3.0.0) (2024-12-26)


### ⚠ BREAKING CHANGES

* **config:** deprecate `iosToken` and `androidToken`, use config `token` ([#40](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/40))

### Features

* add hasOptedOutTracking, ios ip collection settings and fix missing ios methods ([#60](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/60)) ([863f425](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/863f4257b8c4e75c96ee9bcfc848500a4f16aefa))
* add some SDK functions and fix SDK versions ([#8](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/8)) ([563c9b1](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/563c9b17a37c201764526fb3f16b9357af881954))
* mixpanel for capacitor ([b6eda10](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/b6eda108eee9fef47b6e59704ad6d973b75826d7))
* option for opt in/out by default and deleteProfile() ([#43](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/43)) ([df09f7e](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/df09f7ed37a399dd1d8cadc47bf8721ce4e620a2))
* trackCharge and setProfile ([b5aca09](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/b5aca0952c6a8dade564fd731e2e8d6bf9b2560d))
* update mixpanel libraries to ios=4.0.0 android=7.0.0 web=2.45.0 ([#15](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/15)) ([c89f545](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/c89f5458b0059722a10af572aff0bd58dd15789e))


### Bug Fixes

* **config:** deprecate `iosToken` and `androidToken`, use config `token` ([#40](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/40)) ([f64b757](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/f64b757e46ed55d05a7ff76c0a3c1bf1dc7fd506))
* ios ([09da486](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/09da486223cde026239a55cdd223b8a7216fad6f))
* ios ([491db51](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/491db51786dc0453f92f29cfaa83920bff29c080))
* **ios:** crashing on non-string property values ([#4](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/4)) ([5507a4d](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/5507a4d08581a303e23d58a4209403cc67c56f6f))
* **ios:** invalid unwrapping ([baa5e50](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/baa5e50c3097b6d59e97c346d373d1e9f5c9a03a))
* remove deprecated web config object call ([#3](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/3)) ([9c05cc1](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/9c05cc1658de6a3d366c59517e557e5eb89b1307))
* **types:** make token optional in typescript ([#105](https://github.com/tetsuwanadam/capacitor-mixpanel/issues/105)) ([73b183a](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/73b183a12ed6e1c78ea976b6c2090dc0fc491df0))
* typo on android ([fac6561](https://github.com/tetsuwanadam/capacitor-mixpanel/commit/fac65612a5ff2a9359f2b537aeba28f54e63dcf0))

## [2.1.1](https://github.com/houseninjadojo/capacitor-mixpanel/compare/capacitor-mixpanel-v2.1.0...capacitor-mixpanel-v2.1.1) (2023-03-04)


### Bug Fixes

* **types:** make token optional in typescript ([#105](https://github.com/houseninjadojo/capacitor-mixpanel/issues/105)) ([73b183a](https://github.com/houseninjadojo/capacitor-mixpanel/commit/73b183a12ed6e1c78ea976b6c2090dc0fc491df0))

## [2.1.0](https://github.com/houseninjadojo/capacitor-mixpanel/compare/capacitor-mixpanel-v2.0.0...capacitor-mixpanel-v2.1.0) (2023-01-19)


### Features

* add hasOptedOutTracking, ios ip collection settings and fix missing ios methods ([#60](https://github.com/houseninjadojo/capacitor-mixpanel/issues/60)) ([863f425](https://github.com/houseninjadojo/capacitor-mixpanel/commit/863f4257b8c4e75c96ee9bcfc848500a4f16aefa))

## [2.0.0](https://github.com/houseninjadojo/capacitor-mixpanel/compare/capacitor-mixpanel-v1.1.0...capacitor-mixpanel-v2.0.0) (2022-12-01)


### ⚠ BREAKING CHANGES

* **config:** deprecate `iosToken` and `androidToken`, use config `token` ([#40](https://github.com/houseninjadojo/capacitor-mixpanel/issues/40))

### Bug Fixes

* **config:** deprecate `iosToken` and `androidToken`, use config `token` ([#40](https://github.com/houseninjadojo/capacitor-mixpanel/issues/40)) ([f64b757](https://github.com/houseninjadojo/capacitor-mixpanel/commit/f64b757e46ed55d05a7ff76c0a3c1bf1dc7fd506))

## [1.1.0](https://github.com/houseninjadojo/capacitor-mixpanel/compare/capacitor-mixpanel-v1.0.1...capacitor-mixpanel-v1.1.0) (2022-12-01)


### Features

* option for opt in/out by default and deleteProfile() ([#43](https://github.com/houseninjadojo/capacitor-mixpanel/issues/43)) ([df09f7e](https://github.com/houseninjadojo/capacitor-mixpanel/commit/df09f7ed37a399dd1d8cadc47bf8721ce4e620a2))

## 1.0.1 (2022-12-01)

### Release

* Update dependencies

## 1.0.0-beta.2 (2022-09-13)

### Bugfixes

* Set peer dependency for capacitor/core to v4

## 1.0.0-beta.1 (2022-08-29)

### Release

* Upgrade plugin for Capacitor 4 compatibility

## 0.2.0 (2022-08-29)

### Features

* update mixpanel libraries to ios=4.0.0 android=7.0.0 web=2.45.0 (#15) ([c89f545](https://github.com/houseninjadojo/capacitor-mixpanel/commit/c89f545))
  * this adds new configuration option `trackAutomaticEvents` with default value `true`

### 0.1.0 (2022-05-03)

### Features

* add some SDK functions and fix SDK versions ([#8](https://github.com/houseninjadojo/capacitor-mixpanel/issues/8)) ([563c9b1](https://github.com/houseninjadojo/capacitor-mixpanel/commit/563c9b17a37c201764526fb3f16b9357af881954))
