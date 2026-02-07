## [2.0.15](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.14...v2.0.15) (2026-02-07)


### Bug Fixes

* **#110:** restore reactive cleaning mode sync from vacuum entity ([f64ad8e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f64ad8eccb1fc24d10c7a419e10f759b14ae016a)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#124:** auto-reset momentary devices (scenes/automations) after activation in Alexa ([a60e66b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a60e66b335e8487552002ec61a419253732ed935)), closes [#124](https://github.com/RiDDiX/home-assistant-matter-hub/issues/124)
* **#41:** patch LevelControl TLV schema to accept omitted transitionTime from Google Home ([733135b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/733135b4106d7f33f3c54598b901cd04ca32ce88)), closes [#41](https://github.com/RiDDiX/home-assistant-matter-hub/issues/41)
* add missing autoForceSync to ServerModeBridge ([4b92464](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4b924640dd6b06e2f012f140849d2f41ff430cfb)), closes [#103](https://github.com/RiDDiX/home-assistant-matter-hub/issues/103)
* add missing disableLockPin to entity-mapping API handler ([ba288ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ba288caa91085d909ba8e983828ed50cf04e5524))
* add missing Math.round() to humidity measurement ([ab2d196](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ab2d1965e0daa570528ab998a3ee953f76f0af8c))
* detect Matter controllers by rootVendorId instead of fabric label ([db84672](https://github.com/RiDDiX/home-assistant-matter-hub/commit/db846720c19e8505a4a457aa58334f3cccf62c8a))
* route ordering for bridge priorities endpoint ([812ffd9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/812ffd9cd383b5542c3d81ec4b0e1126b76fc237))


### Features

* **ui:** add device limit warning for Matter controllers ([b73fc8b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b73fc8bdcda353c3e3512aeb73f92ce2805681d3)), closes [#129](https://github.com/RiDDiX/home-assistant-matter-hub/issues/129)

## [2.0.14](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.13...v2.0.14) (2026-02-07)


### Bug Fixes

* **#130:** support ventilation-only climate devices (fan_only/dry) ([18d9a31](https://github.com/RiDDiX/home-assistant-matter-hub/commit/18d9a31d1c1340d67a4b336cd8025435e5cdb99e)), closes [#130](https://github.com/RiDDiX/home-assistant-matter-hub/issues/130) [#130](https://github.com/RiDDiX/home-assistant-matter-hub/issues/130)

## [2.0.13](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.12...v2.0.13) (2026-02-07)


### Bug Fixes

* **sensors:** correct CO2 thresholds and add ExtremelyPoor for CO2/PM10 ([35b41ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/35b41eaac4cddf47de050e04ae9cada59b0438a1))

## [2.0.12](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.11...v2.0.12) (2026-02-07)


### Bug Fixes

* **tvoc:** use correct measurement unit and thresholds per device_class ([ff1d706](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ff1d7067fb31648679d45d60611bcc52504165af))

## [2.0.11](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.10...v2.0.11) (2026-02-07)


### Bug Fixes

* **#71:** cooling setpoint now updates temperature in auto mode for single-temp thermostats ([786c233](https://github.com/RiDDiX/home-assistant-matter-hub/commit/786c23312fcfcba21fe91b4e512c49c1b55b387d)), closes [#71](https://github.com/RiDDiX/home-assistant-matter-hub/issues/71)
* **#78:** translate position commands to open/close for binary covers ([7021b2d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7021b2d0272d4ca790f4ea4d94c049a5e7edaa2e))
* **#92:** clamp colorTemperatureMireds to device range before updating boundaries ([e866f0d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e866f0da80d8160be4f31b4b55d3a2b8b71a3834)), closes [#92](https://github.com/RiDDiX/home-assistant-matter-hub/issues/92) [#92](https://github.com/RiDDiX/home-assistant-matter-hub/issues/92)

## [2.0.10](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.9...v2.0.10) (2026-02-07)


### Bug Fixes

* **#124:** scenes always showing as on - use same pattern as automation ([563536c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/563536c9cd885d8f100ff090d647a8f20319c647)), closes [#124](https://github.com/RiDDiX/home-assistant-matter-hub/issues/124)
* **#78:** add PositionAwareLift back for all covers - Apple Home requires it ([ad347eb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ad347ebf4319d27dffb3d6d990109b9b5c7df72f)), closes [#78](https://github.com/RiDDiX/home-assistant-matter-hub/issues/78)

## [2.0.9](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.8...v2.0.9) (2026-02-06)


### Bug Fixes

* **#105:** update Auto Force Sync to include Alexa workaround ([8b010c5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b010c5822a87624371e794086bda7c2340a1f0a)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* **#110:** enable RvcCleanMode for vacuums with cleaningModeEntity mapping ([40ebe9d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/40ebe9d9d6ce7521095ca8993203992f3f6aeb13)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** read cleaning mode from select entity instead of vacuum entity ([8357949](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8357949cd6b1d7e48ed60f45ec68c112dee31130)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#114:** correct storage detection and add IPv6 network interfaces ([11ab9f8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/11ab9f8efff2e262f8b7ed1f98a448de7c704e8d)), closes [#114](https://github.com/RiDDiX/home-assistant-matter-hub/issues/114)
* **#115:** add forceSync method to ServerModeBridge ([b476c2a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b476c2a54baf7afdfbf40455c3eaddb511e55fa9)), closes [#115](https://github.com/RiDDiX/home-assistant-matter-hub/issues/115)
* **#117:** add debug logging for cover open/close commands ([79b5947](https://github.com/RiDDiX/home-assistant-matter-hub/commit/79b5947021bcbb427bd65eb1be9361bee3722a46))
* **#117:** coverSwapOpenClose now also inverts position commands ([90a3876](https://github.com/RiDDiX/home-assistant-matter-hub/commit/90a3876aa899f7a56cf33b901a3352bd6aa274a3))
* **#123:** reduce vacuum log spam by changing repeated state logs to DEBUG level ([d791470](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d791470348e1c102f3252dbab2b27b138d4341f4)), closes [#123](https://github.com/RiDDiX/home-assistant-matter-hub/issues/123)
* **#95:** add debug logging for lock/unlock PIN operations ([fe0eb5a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fe0eb5a8bac7ce470900dde92a086cab5425b6d0)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** add required defaults for lock PinCredential feature ([b90fda0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b90fda01b092489d076be2ade346b49a1abcff1e)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** add required PinCredential defaults before initialize to prevent Behaviors have errors ([a9e7a0b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a9e7a0b64398d5e597329c596007662469830afd)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#99,#112:** add batteryEntity mapping support for fan, climate, and temperature sensors ([bf69f81](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bf69f81768e550481b338632e6e9ebac71db41f3)), closes [#99](https://github.com/RiDDiX/home-assistant-matter-hub/issues/99) [#112](https://github.com/RiDDiX/home-assistant-matter-hub/issues/112)
* **#99:** add battery support for Smoke and CO alarm devices ([a7e7ae2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a7e7ae298b1fec6b8d73ea2ba6c4e06277b2a9cd)), closes [#99](https://github.com/RiDDiX/home-assistant-matter-hub/issues/99)
* **#99:** initialize endpointList in PowerSource cluster for Google Home compatibility ([cdefd96](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cdefd9670ee83a490f8c99c3d35690e8d233a8ef)), closes [#99](https://github.com/RiDDiX/home-assistant-matter-hub/issues/99)
* auto-reset scenes and buttons to OFF after activation ([b5096e8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5096e895ace07f41f9b221e14149eda1c8fc61a))
* format the files ([2173e08](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2173e08399907168abaef624ba386d6260778287))
* use lodash for formatting ([851a9c0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/851a9c0c44e944101321a2958ba94f06372b5e66))
* use notes-file for GitHub release to avoid shell syntax errors ([4d17e3b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4d17e3b6ab087d52d358412b46a40fea8e91a0b7))


### Features

* **#108:** add oscillation (Rocking) and wind mode support for fans ([867fe55](https://github.com/RiDDiX/home-assistant-matter-hub/commit/867fe558a2b1034f9172cb64c70da31cbee85c05)), closes [#108](https://github.com/RiDDiX/home-assistant-matter-hub/issues/108)
* **#112:** add batteryEntity mapping support for vacuums ([990f3ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/990f3ea1519f3b412cc5aa9d16c7d9c4f025e107)), closes [#112](https://github.com/RiDDiX/home-assistant-matter-hub/issues/112)
* **#117:** add coverSwapOpenClose feature flag for Alexa ([d45142e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d45142e64337735787941b1c1f70328d8e0f70ec))
* **#121:** add copy endpoint data to clipboard button ([3f7cbe0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3f7cbe030fdaa6fbf007f695f0a8a76ef9a3f3dd)), closes [#121](https://github.com/RiDDiX/home-assistant-matter-hub/issues/121)
* **#95:** add per-lock PIN disable option in entity mapping UI ([4e818f9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4e818f912a97a0193a8269b9b9932d223972d21c)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** allow lock without PIN, only unlock requires PIN ([401f2d3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/401f2d396d9097a7ae27894550dcd37e7ddabf2f)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* implement ecovacs room handling ([0cb733b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0cb733b47279c29d7f8f942a09456f0bb7a31069))

## [2.0.8](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.7...v2.0.8) (2026-02-06)


### Bug Fixes

* **#95:** add required defaults for lock PinCredential feature ([8c175a2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8c175a218610637e0873676016da099171b3e919)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** add required PinCredential defaults before initialize to prevent Behaviors have errors ([8fd1688](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8fd1688d879c920c636b5c8692850226d7ed4fb8)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)

## [2.0.7](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.6...v2.0.7) (2026-02-05)


### Bug Fixes

* **#93:** make forceSync actually push device states to controllers ([255e0b0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/255e0b01f73b5b8654d92b566864fb6b32d8599e)), closes [#93](https://github.com/RiDDiX/home-assistant-matter-hub/issues/93)
* allow SystemMode.Auto to be displayed without AutoMode feature ([#71](https://github.com/RiDDiX/home-assistant-matter-hub/issues/71)) ([22a3d3f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/22a3d3f57f96cb9576bfbde6a7d58dbcc372307f))
* dehumidifier now correctly shows target humidity instead of scaled value ([#96](https://github.com/RiDDiX/home-assistant-matter-hub/issues/96)) ([ecf6ed8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ecf6ed81bdda3f87e506ddcdfb9fc2075ecb168e))
* ensure humidity is assigned before battery for correct T+H+B grouping ([e2e616c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e2e616c90c2c6b90d00ed843c0d6d5a61162eeca))
* factory reset API call uses POST instead of GET ([c793bbd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c793bbdacdfd5bdb39db09a1987b665ea3fff67a))
* force-set thermostat values unconditionally before super.initialize() ([de672e9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/de672e94d7f15f914e587885bd7c83f4ab2e1252))
* **frontend:** reorder Sort By dropdown options to match filter order ([#100](https://github.com/RiDDiX/home-assistant-matter-hub/issues/100)) ([340f30c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/340f30c3d868ae3dd48ab726f2023d61a095c45e))
* move env() to command builder for proper environment variable parsing ([b39ba29](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b39ba29f7178940ea61cf7856993d42b07074ac9))
* pre-calculate auto-assignments to ensure correct entity skipping order ([bac1562](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bac1562aa95e573786b37ff97f3f7b4e732fec1b))
* prioritize explicit direction over target position for cover open/close commands ([b5ed651](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5ed651259e1e342013d5b7235a2594d39f0e8b4))
* remove State class override properties - rely only on .set() for defaults ([74d9935](https://github.com/RiDDiX/home-assistant-matter-hub/commit/74d9935a2fbb3cb2e5dc12f13404b64bc560ef57))
* set APP_VERSION env var during alpha build ([f754a15](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f754a155d5129b728a7db3c78bbf054f63969da0))
* set minSetpointDeadBand to 0 for heat_cool thermostats with single setpoint ([2b3e5af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2b3e5afcaa22d57d9e3ef718f61084cd93b6f55a))
* set thermostat state at endpoint level with AutoMode feature for minSetpointDeadBand ([0889a8a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0889a8ac8d81a8fe8a76cf5cfce775de21d8f1cb))
* sync cover target position with current when stopped ([#93](https://github.com/RiDDiX/home-assistant-matter-hub/issues/93)) ([95f66c5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/95f66c5c87401e0134f2b6c0fb8243deaf768293))
* use ThermostatBehavior instead of ThermostatServer to bypass validation issues ([7693058](https://github.com/RiDDiX/home-assistant-matter-hub/commit/76930584fac9272ba71d00fa395d97ecee08f63b))
* water heater support for high temperatures (kettles/boilers 70-100°C) ([acd3c63](https://github.com/RiDDiX/home-assistant-matter-hub/commit/acd3c63fb81e4bb96589a914993fa274dec827f8))
* **water-heater:** remove .with() call that was losing initial state values ([#97](https://github.com/RiDDiX/home-assistant-matter-hub/issues/97)) ([edd709a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/edd709a707a73941def44a56f89b725f9b67244a))


### Features

* **#93:** add Auto Force Sync option for Google Home workaround ([d002eec](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d002eec9afa9b5b4f6318f682038bf165338b753)), closes [#93](https://github.com/RiDDiX/home-assistant-matter-hub/issues/93)
* **#95:** add RequirePINforRemoteOperation for Matter locks ([f008ceb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f008ceb6d03e2c5df73bb35d0b6222e52900af4a)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* **#95:** hash PIN codes with PBKDF2 for secure storage ([2b48d01](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2b48d01f7512dd8605daaeed8ea627bd75fb5e59)), closes [#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)
* add /api/matter/labels endpoint and improve label filter documentation ([ed7e249](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ed7e249d17fbca023c2cce100bebeec4f9aeb1f3))
* add auto battery mapping feature flag for bridges ([1024c29](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1024c29ebd43e544ce9550fa126f9f1f31122deb))
* add auto humidity mapping to temperature sensors ([5fb8ed5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5fb8ed56972734982945b4c2a7e39a13295151fd))
* add Force Sync button to push device states to controllers ([2c45e79](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2c45e796a4e4fca868fc1aa17f5b35e855863bbc))
* add Roborock room selection support via button entities mapping ([8faf111](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8faf1117d1749b4d1cf20fd2d52ec06961f07b8f))
* add roomEntities UI with auto-discovery for Roborock vacuum room selection ([00c2879](https://github.com/RiDDiX/home-assistant-matter-hub/commit/00c28795518cc99c3643db45681e8a2baa85aabc))
* add separate autoHumidityMapping feature flag (default: enabled) ([cd07654](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd076541e4e1dfc5613d858afa3dc65788a7fb6b))
* add sorting with direction toggle to All Devices view ([#100](https://github.com/RiDDiX/home-assistant-matter-hub/issues/100)) ([eb48e10](https://github.com/RiDDiX/home-assistant-matter-hub/commit/eb48e101149a830dd48f18c392544ebc495463ab))
* sort bridge list alphabetically in All Devices view ([06c2618](https://github.com/RiDDiX/home-assistant-matter-hub/commit/06c2618cb79648803069d97e00b935bba92ae6d3))
* **ui:** add Force Sync button to bridge menu ([949748f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/949748f524d748312fc64e5c9640c131dd3686af)), closes [#93](https://github.com/RiDDiX/home-assistant-matter-hub/issues/93)


### Reverts

* use ThermostatServer instead of ThermostatBehavior (fixes atomicRequest) ([bc7abad](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bc7abadf94f8be6c57df01dd6e34b3af022e56b9))

## [2.0.6](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.5...v2.0.6) (2026-02-04)


### Features

* add Server Mode option to Bridge Wizard for Robot Vacuums ([5ba7dc8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ba7dc8ef3fc0cd19481b148c097654a81d54105))

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
