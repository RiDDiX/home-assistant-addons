## [2.0.5](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.4...v2.0.5) (2026-02-04)


### Bug Fixes

* **#101:** set includesIcons before writing backup.json to archive ([5c564c1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5c564c19d0ac4341e5bb52de0997432ec0ee9aa4)), closes [#101](https://github.com/RiDDiX/home-assistant-matter-hub/issues/101)
* **#49:** make addDevice idempotent and mark excess entities as failed ([f5b53e3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f5b53e3b15927d718c83e72acdb5ec2ffe6963f8)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)
* **#49:** prevent double ServerNode creation in Server Mode ([d0a2b59](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d0a2b59e2f51c476d4d988dd425137a4b5a32b16)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)
* **#82:** use homeassistant.turn_on/off for lights to support entity type overrides ([03da0fb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/03da0fb926c591b6089fb56105588e141a37f11a)), closes [#82](https://github.com/RiDDiX/home-assistant-matter-hub/issues/82)
* add CHANGELOG.md assets to alpha releases for HA addon compatibility ([837613c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/837613cd89f9e0cbe7d6f63ec8b53a46b2f81b41))
* **ci:** add range constraint to alpha branch for correct version calculation ([670c19e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/670c19edb747dc39d452c1dd289c8a28219be969))
* **ci:** format releaserc.json to pass biome lint ([6b85647](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6b85647e6805ecaa955e1ec40b194099a0563e84))
* **ci:** revert to manual alpha versioning - only increment alpha.X number ([7d2ad64](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7d2ad6447d9a99d467b79e0b552f20c8018de96c))
* **ci:** use semantic-release for alpha releases instead of manual versioning ([9d638e4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9d638e417dcefa34831a1059373183776c03594a))
* correct changelogUrl to download CHANGELOG_FULL.md instead of HTML page ([34cf39c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/34cf39c1313f4d9231f8120da094d675b7da1d28))
* use separate ServerModeEnvironment to prevent storage conflicts ([f73c10b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f73c10bf1c4796ab57c4170f2006582e9bccf2a2))


### Features

* **#49:** add server mode for Robot Vacuums to enable Siri voice commands ([eb51e2d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/eb51e2d1015f3838655de95e64805eeb35579c5d)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)
* **#49:** implement proper Server Mode with non-bridged vacuum endpoints ([1d05d8c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1d05d8cb5fd28f186cb4eb54893643cbbf6b5575)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)
* **#49:** improve Dreame vacuum cleaning mode aliases ([cb285ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cb285ea2c16340a7882b61cfc37beed11e25f252)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)
* **#95:** add lock credential management UI and API for Matter DoorLock PIN support ([08189a9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/08189a941ca45cbaac65139b70cd5f9253cd8a04)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** integrate PIN code support into LockServer for lock/unlock commands ([b5861db](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5861dbe224a1f3ed0c3bd368bf54d0a2fec2209)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* add separate alpha release workflow with manual versioning ([550201b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/550201bbf7486be80f2349967747ffc57d013afb))

## [2.0.4](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.3...v2.0.4) (2026-02-04)


### Bug Fixes

* **#49:** add mopping_after_sweeping alias for Dreame lowercase format ([af2e0f2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/af2e0f264a0f388ca168e5badf1b364d3cb6c274)), closes [#49](https://github.com/RiDDiX/home-assistant-matter-hub/issues/49)

## [2.0.3](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.2...v2.0.3) (2026-02-04)


### Bug Fixes

* **#49:** fix cleaning mode partial match selecting wrong option ([97f6743](https://github.com/RiDDiX/home-assistant-matter-hub/commit/97f67437135cca648e029da95d587523e951c63d))

## [2.0.2](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.1...v2.0.2) (2026-02-04)


* feat!: start v2.1.0-alpha development cycle ([d47b804](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d47b8049379b08cc4b8d5662d96beedce2209b1b))


### Features

* add battery sensor support for sensor entities with device_class battery ([#60](https://github.com/RiDDiX/home-assistant-matter-hub/issues/60)) ([ddfe6c1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ddfe6c18b640be9e55327c7032718d11e425cbf7))
* add combined Temperature+Humidity sensor support with humidityEntity and batteryEntity mapping ([2a8e651](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2a8e6514954b9ee613c05cd91d50ee872a50c757))
* add PowerSource cluster to Lock and Cover devices with battery ([20dc78e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/20dc78ed5d8d071eddbabf663e6d14709b4a3a9a))
* add PowerSource cluster to Switch, BinarySensor, Light, Fan, Climate devices with battery ([8b5e977](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b5e9771c4700872937a80ae7ac2e889305c23b0))


### BREAKING CHANGES

* Reset alpha versioning to v2.1.0-alpha series after cleanup of old releases.

## [2.0.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0...v2.0.1) (2026-02-04)


### Bug Fixes

* add water_heater to entity mapping dropdown and backend factories ([ccdda2b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ccdda2bc465aaa251e48a98d0f8d3ef89143f772))
* remove AutoMode feature from ClimateDevice to fix Behaviors have errors ([#82](https://github.com/RiDDiX/home-assistant-matter-hub/issues/82)) ([0a4af9e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0a4af9e473d0873a30306712762c9a710531d266))
* revert getSystemMode to v1.10.6 behavior - map Auto to Heat/Cool without AutoMode feature ([dd4fda3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd4fda3198c5d573374e66b78cad58e2cd2986aa))
* suppress Invalid intervalMs errors to prevent FATAL crashes ([#74](https://github.com/RiDDiX/home-assistant-matter-hub/issues/74), [#76](https://github.com/RiDDiX/home-assistant-matter-hub/issues/76), [#79](https://github.com/RiDDiX/home-assistant-matter-hub/issues/79), [#80](https://github.com/RiDDiX/home-assistant-matter-hub/issues/80), [#82](https://github.com/RiDDiX/home-assistant-matter-hub/issues/82)) ([e171d0e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e171d0e04eabceb1689508f693251986811ebeb8))
* thermostat auto mode now correctly displays on Matter controllers ([#71](https://github.com/RiDDiX/home-assistant-matter-hub/issues/71)) ([d348265](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d348265202541f3a61f4120af5e2b848d0b92615))


### Features

* add EntityIsolationService to isolate problematic entities at runtime ([8d81fd2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8d81fd24d8b014274d8288cbcb5e02e5715fbfaf))
* merge alpha fixes and update README for v1.10.5 stable release ([6ea28a3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6ea28a3a2a49712f03e33a0a801d8f53f75439c4))
* merge alpha into main for v2.0.0 release ([3f94d6d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3f94d6d9b13b54bd574dcfc7829629540550b052))
