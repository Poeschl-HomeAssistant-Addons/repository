Note: this is the full changelog of the versions deployed via the [previous mono-repository](https://github.com/Poeschl-HomeAssistant-Addons/repository/tree/41c02f85a6fffb328c21df76ace4e54ad0ee3466).

## 1.12.0 - 2024-01-13

* 🔼 Update Valetudo-Mapper to commit `54aba35` (thanks @gerard33 #442)
* 🔼 Update git to `2.36.6-r0`

## 1.11.0 - 2022-08-03

* 🔼 Update Valetudo-Mapper to commit `bd97779`
* 🔼 Update alpine to `3.16`
* 🔼 Update git to `2.36.2-r0`
* 🔼 Update npm to `8.10.0-r0`
* 🔨 Migrated to S6-Overlay `V3`
* 📝 Updated to new repository structure + Yaml config


## 1.10.1 - 2022-04-10

* 📝 Updated Readme

## 1.10.0 - 2021-07-27

* 🔧 Add port of mqtt broker to schema validaton
* 🔼 Update Valetudo-Mapper to commit `8500701`
* 🔼 Update alpine to `3.14`
* 🔼 Update git to `2.32.0-r0`
* 🔼 Update npm to `7.17.0-r0`

## 1.9.0 - 2021-04-02

* 🔨 Use ghcr.io/home-assistant for base images


## 1.8.1 - 2021-03-17

* 🐛 Specifiy own S6 entrypoint, don't rely on the base image.
* 🔨 Use Multi-Stage Build to reduce download size
* 🔼 Updated git to `2.30.2-r0`
* 🔼 Updated npm to `14.16.0-r0`


## 1.8.0 - 2021-02-15

* 🔨 Allow also anonymous access in mqtt broker url


## 1.7.1 - 2021-02-10

* 🔼 Updated git to `2.30.1-r0`


## 1.7.0 - 2021-01-30

* 🔨 Use Jemalloc for better memory handling
* 🔼 Update alpine to `3.13`
* 🔼 Update git to `2.30.0-r0`
* 🔼 Update npm to `14.15.4-r0`

## 1.6.1 - 2020-11-27

* 🐛 fix rotation config
* 🔨 Modernise Readme

## 1.6.0 - 2020-11-27

* 🔼 Update Valetudo-Mapper to commit `1ae822c`
* 🔼 Update alpine to `3.12`
* 🔼 Update git to `2.26.2-r0`
* 🔼 Update npm to `12.18.4-r0`
* ➕ Add rotation setting


## 1.5.0 - 2020-10-22

* 🔨 Use S6-Overlay for execution
* 🔨 Start as `application` startup type


## 1.4.0 - 2020-05-29

* 🔼 Updated Valetudo-Mapper to commit `8e23ac2`
* ➕ Added all missing settings until now

### ⚠️ Breaks existing config

More: see [#82](https://github.com/Poeschl/Hassio-Addons/pull/82)


## 1.3.2 - 2020-05-22

* 🔨 Updated Changelog to new format


## 1.3.1 - 2020-04-29

* 🔼 Updated git to `2.24.3-r0`


## 1.3.0 - 2020-04-16

* 🔼 Updated Valetudo-Mapper to commit `4bd62e2`


## 1.2.1 - 2020-04-16

* 🔼 Updated git to `2.24.2-r0`


## 1.2.0 - 2020-02-09

* ➕ Added new config settings (thanks @thundergreen)
  * `drawForbiddenZones`
  * `drawVirtualWalls`
  * `gradientBackground`


## 1.1.1 - 2020-02-07

* 🔼 Updated dependencies:
  * alpine `3.11`
  * git `2.24.1-r0`
  * npm `12.15.0-r1`


## 1.1.0 - 2020-02-04

* 🐛 fix compatibility with 2008 firmware for S50/55


## 1.0.0 - 2019-12-09

* ➕ Add Valetudo-Mapper in its basic form (master commit)
