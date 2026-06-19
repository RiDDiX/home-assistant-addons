## [2.0.48](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.47...v2.0.48) (2026-06-19)


### Bug Fixes

* **#381:** clear inactive setpoint limits ([ee99d04](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ee99d04db204c5432a868d9a5a10e0c17157a421)), closes [#381](https://github.com/RiDDiX/home-assistant-matter-hub/issues/381)
* show full release notes in updates card ([bd471ae](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bd471ae089af312721800364608b2b5904e0f59e))

## [2.0.47](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.46...v2.0.47) (2026-06-19)


### Bug Fixes

* **#287:** remove no-op keepalive, lower interval ([6831e8d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6831e8d2b76845f80cfc5e4dbf979e718c36e500)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** route keepalive to own session ([6713f73](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6713f73997ec7bc5f1c4cd366762e3ac53595ea6)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#309:** companion fan off stops the AC ([5b30524](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5b305249c24179bf81b49c0fba2aa3fcd843febe)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#365:** 1.3-safe type for leak/freeze/rain ([c32ab9c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c32ab9c18de0f8483e3ca76050ad108b7b330cdf)), closes [#365](https://github.com/RiDDiX/home-assistant-matter-hub/issues/365)
* **#367:** clear currentArea on new selection ([414ea16](https://github.com/RiDDiX/home-assistant-matter-hub/commit/414ea16d60b4293e43afbe49b8e2ca5ded165760)), closes [#367](https://github.com/RiDDiX/home-assistant-matter-hub/issues/367)
* **#367:** don't drop rooms in batch area merge ([678ef2c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/678ef2c82108e98983e7a2f101b6deca18783c7b)), closes [#367](https://github.com/RiDDiX/home-assistant-matter-hub/issues/367)
* **#367:** skip unreached rooms on early stop ([3bbb2ce](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3bbb2cee3b7d8d1ec7196590827db86eaeaef7d5)), closes [#367](https://github.com/RiDDiX/home-assistant-matter-hub/issues/367)
* **#368:** wake on m2 sensor, map in clean order ([cfddbe9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cfddbe91a0f07d85cd7be17cb25e62b8be5ad72f)), closes [#368](https://github.com/RiDDiX/home-assistant-matter-hub/issues/368)
* **#369:** map fan speed to the matching preset ([97e2cfe](https://github.com/RiDDiX/home-assistant-matter-hub/commit/97e2cfeefe9ca7f4c5e79061bf8de4010db2cf9b)), closes [#369](https://github.com/RiDDiX/home-assistant-matter-hub/issues/369)
* **#370:** clear stale hue on color-temp lights ([bcf2239](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bcf22394f1f56f15de8961e2539b3f74a4f3dd14)), closes [#370](https://github.com/RiDDiX/home-assistant-matter-hub/issues/370)
* **#370:** type test vendorId so build passes ([cefb55c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cefb55cfec66bf5a02c4b3ae1c119a9a10a54934)), closes [#370](https://github.com/RiDDiX/home-assistant-matter-hub/issues/370)
* **#374:** don't auto-map power/energy to lights ([13845ee](https://github.com/RiDDiX/home-assistant-matter-hub/commit/13845eed2557d3d37787f172bd817be94de54571)), closes [#374](https://github.com/RiDDiX/home-assistant-matter-hub/issues/374)
* **#375:** order thermostat setpoint limits so init never fails ([6c800bd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6c800bdba0580302c65bdf8e8adb387d730d081d)), closes [#375](https://github.com/RiDDiX/home-assistant-matter-hub/issues/375)
* **#375:** repair drifted thermostat limits ([4995a7f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4995a7f5974d0e840f670cf4e4fbe40c891a6f40)), closes [#375](https://github.com/RiDDiX/home-assistant-matter-hub/issues/375)
* **#377:** show Charging for docked vacuums ([84ed472](https://github.com/RiDDiX/home-assistant-matter-hub/commit/84ed472e1ed172879d5f42368a839f198ce14368)), closes [#377](https://github.com/RiDDiX/home-assistant-matter-hub/issues/377)
* **#380:** on/off switch override is now a switch ([ad5b958](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ad5b958958a2b6dd25300d3d310538695d27e645)), closes [#380](https://github.com/RiDDiX/home-assistant-matter-hub/issues/380)
* **#381:** clamp systemMode, clear cover tilt ([960f1a7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/960f1a70480ef535c1284793b7a38fbfedc05c46)), closes [#381](https://github.com/RiDDiX/home-assistant-matter-hub/issues/381)
* add werift and @matter/types to app dependencies (match backend) ([e7eacd4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e7eacd45e5bb69e20846363e88b16b601f055259))
* cap the controller-warnings list height ([072b95d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/072b95d6a4a8bac6b48cf97e7112efabb396024c))
* close matter sessions cleanly on shutdown ([6678088](https://github.com/RiDDiX/home-assistant-matter-hub/commit/667808869241234dcd948acb1cb890bb1c21e6b9))
* drop Lighting on automation and input button ([a1cab28](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a1cab2860d7215b4f90311e5fa47c00fc5f173aa)), closes [#182](https://github.com/RiDDiX/home-assistant-matter-hub/issues/182) [#364](https://github.com/RiDDiX/home-assistant-matter-hub/issues/364)
* harden standalone devices page and api ([a6a00d1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a6a00d1c8320dad3497b817800e5d294df859e62))
* patch LevelControl transitionTime schema ([#383](https://github.com/RiDDiX/home-assistant-matter-hub/issues/383)) ([661cb56](https://github.com/RiDDiX/home-assistant-matter-hub/commit/661cb561d0bdd3ee64b80f050020f5cba666d334))
* set door lock alwaysSet per matter spec ([6301305](https://github.com/RiDDiX/home-assistant-matter-hub/commit/63013050e95de4d240ea8f740c3e5ae3ff8ed097))
* show the full update changelog ([2a72cec](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2a72cec0e1e3355dd2a916e9f2f8ad37a1338450))
* stabilize HA auto climate direction ([ff05551](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ff055517811b2ce9027ba0f38ae22b29b4cebd42))


### Features

* **#301:** multi-entity standalone devices ([22dd9a4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/22dd9a4bd8856e3aed99a3a0a3eaea2e84d46a4f)), closes [#301](https://github.com/RiDDiX/home-assistant-matter-hub/issues/301)
* **#301:** wire lawn_mower as a robotic vacuum ([681b3ee](https://github.com/RiDDiX/home-assistant-matter-hub/commit/681b3ee4f8953a1bc2972485f574c238fe91b6fb)), closes [#301](https://github.com/RiDDiX/home-assistant-matter-hub/issues/301)
* **#351:** per-entity update throttle ([4bc8177](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4bc8177efc3dbdf6de0c29d0d8187cfef8f9bf2b)), closes [#351](https://github.com/RiDDiX/home-assistant-matter-hub/issues/351)
* **#365:** add per-session liveness to health ([afeb667](https://github.com/RiDDiX/home-assistant-matter-hub/commit/afeb667d0e4904d5acdeab4d487a5e5c8e3bbc9a)), closes [#365](https://github.com/RiDDiX/home-assistant-matter-hub/issues/365)
* **#367:** opt-in to drop custom-area room modes ([9dcd6b4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9dcd6b4f55dbcceca3c22c9d97104b06dfa24bb2)), closes [#367](https://github.com/RiDDiX/home-assistant-matter-hub/issues/367)
* **#368:** track current room by cleaned area ([41265b7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/41265b7a5aaefdfbd02cbbb28404e1079c964923)), closes [#368](https://github.com/RiDDiX/home-assistant-matter-hub/issues/368)
* **#372:** cover as dimmable light for Alexa ([d269420](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d269420f1b2f903a62ed4e52ad1cd44b0b58f184)), closes [#372](https://github.com/RiDDiX/home-assistant-matter-hub/issues/372)
* **#377:** charging-state sensor mapping ([0ea3657](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0ea3657def67f45ad9574cbb9f58d609b6064909)), closes [#377](https://github.com/RiDDiX/home-assistant-matter-hub/issues/377)
* **#382:** filter entities by manufacturer ([a394fe5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a394fe5ce2be24d154b27e632cdfa183c697c5c5)), closes [#382](https://github.com/RiDDiX/home-assistant-matter-hub/issues/382)
* add Aqara controller support ([6ca90de](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6ca90de6c96d599ed0ff59ae76e758e189167a18))
* controller support badges in device-type picker ([ad7ce2d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ad7ce2d27f8c048ffb4d1e6f27250134ec60a07e))
* experimental WebRTC camera plugin (SmartThings-only, untested media path) ([fab2316](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fab23160ef6103ff3598b0fa177de87604416230))
* failure times and configurable auto recovery ([ae7d6db](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ae7d6dbad5e0bb4f69bd333ba91295528d892bd3))
* per-entity device health diagnostics ([b27607a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b27607adaa207ef42c45903f9a0196ebac79ec68))
* **plugins:** let plugins contribute custom matter.js endpoints ([251440f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/251440fd20a4a9428d9cde803304778573048a7b))
* show controller warnings on bridge page ([985eda6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/985eda61925d2f0a4752872f8c76b640945c44c4))
* warn when a bridge exposes types its controller does not support ([1ea00db](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1ea00db0665af82019f04d0a31cc2d6771dfae6d))

## [2.0.46](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.45...v2.0.46) (2026-06-03)


### Bug Fixes

* **#287:** refresh rvc sessions safely ([78d156d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/78d156dab03252438ad923fd3113c783cf33d3b3)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#309:** add companion fan toggle and persist ([e7fa03c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e7fa03c680df9d777884d28ed6168fd664b25780)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#309:** order fan speed presets ascending ([a2cd14a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a2cd14a350a9338a642fb863810fa82dc5c31af5)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#313:** cast lock fabric index ([e6f7f68](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e6f7f68fc8781f6fb784c015603e3d9346e50237)), closes [#313](https://github.com/RiDDiX/home-assistant-matter-hub/issues/313)
* **#313:** handle lock access code ([4b534c6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4b534c6da4044d65b22bd40ee9447a63db635306)), closes [#313](https://github.com/RiDDiX/home-assistant-matter-hub/issues/313)
* **#313:** harden lock credentials ([c5e957c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c5e957ce900eb2ff23d4c1602d01ee2001790a52)), closes [#313](https://github.com/RiDDiX/home-assistant-matter-hub/issues/313)
* **#350:** tilt-only covers use tilt for lift cmds ([9191ff7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9191ff7464a397e5b19f851db62c77751b77a40a)), closes [#350](https://github.com/RiDDiX/home-assistant-matter-hub/issues/350)
* **#351:** skip unchanged endpoints on HA updates ([57c1593](https://github.com/RiDDiX/home-assistant-matter-hub/commit/57c15931d396e4a4f1aee5c14e7b5deb78339275)), closes [#351](https://github.com/RiDDiX/home-assistant-matter-hub/issues/351)
* **#352:** keep registry resilient to ha connection drops ([7723c22](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7723c22e3642121d42bca4705fdc2861d648615c)), closes [#352](https://github.com/RiDDiX/home-assistant-matter-hub/issues/352)
* **#358:** keep addon heap flag ([c3a8d22](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c3a8d2234023c815e5b6fcce4121bdf249e9d433)), closes [#358](https://github.com/RiDDiX/home-assistant-matter-hub/issues/358)
* **#359:** narrow battery auto-mapping ([ab6a2ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ab6a2ea67a6495bbb323e7b1589cc639eddcaa5a)), closes [#359](https://github.com/RiDDiX/home-assistant-matter-hub/issues/359)
* format battery tests ([a793703](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a793703124a225fd4028830102f25b73b8dc3397))
* make automation momentary ([#364](https://github.com/RiDDiX/home-assistant-matter-hub/issues/364)) ([0d46cff](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0d46cff9d1ab143c10cfc3448ac2ca715b25eb5d))
* point empty-state docs link to own site ([ee01a35](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ee01a352302c1fcbdb14c0cad347a3dbd6e27e4d))
* resolve dependency vulnerabilities ([e536288](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e5362883dc0eb42f63ea0d357e99184de50e711f))
* stub bun:sqlite constants export for esbuild bundle ([f7d591c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f7d591cdeae5a12d8a6d1c79ae5652b0c5b2f52b))
* support enum battery states ([fa65a69](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fa65a691bbe6ccf7279a4626e2dbf3dd4437837f))


### Features

* **#291:** edit vacuum area data and batch ([a9bfb25](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a9bfb252a7e9414260a76168c2e3eb5a446115e1)), closes [#291](https://github.com/RiDDiX/home-assistant-matter-hub/issues/291)
* **#309:** opt-in companion fan for climate ac ([89b9866](https://github.com/RiDDiX/home-assistant-matter-hub/commit/89b9866bbc626675a4e1436c922f92b787e53508)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* add weather domain as matter sensor ([01176a9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/01176a92ed9947639cfb2bada97435b54101a512))
* warn on non-5540 port for alexa bridge ([55247a0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/55247a059444bf8771e7776947ee5a4418203be2))

## [2.0.45](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.44...v2.0.45) (2026-05-16)


### Bug Fixes

* **#348:** bind typed text in entity autocomplete ([5e6ef44](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5e6ef44647ae00b36b166e7ce91fd8872aad06cc)), closes [#348](https://github.com/RiDDiX/home-assistant-matter-hub/issues/348)

## [2.0.44](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.43...v2.0.44) (2026-05-16)


### Bug Fixes

* **#287:** guard pushKeepalive on construction ([c3c69e4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c3c69e45275394b4fef20e939eb7a6fe02f9af90)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** make rvc clean mode reactor offline ([9d6bf93](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9d6bf9395ac1ebb7ac06cb5a03fdff79e30ba05a)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** rotate aged matter sessions ([6272875](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6272875f802d3df4e99797c3a036b78214019f6f)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#312:** drop EndProductType.Unknown for window class ([1839037](https://github.com/RiDDiX/home-assistant-matter-hub/commit/18390377242fc17d3a83f76067a5bb561040a864)), closes [#312](https://github.com/RiDDiX/home-assistant-matter-hub/issues/312)
* **#328:** align cover cluster profile with certified Eve ([6d569d5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6d569d5f4872b4b990701b5a3c9c55f40a4e042f)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** dedup deferred cover target writes ([6b3a020](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6b3a02079956f9303eeb3fb4c7e7d870cc700941)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** drop deferred cover target split ([b53ba8a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b53ba8a283fdfc8451df08410ecd2fbc9bb40461)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** drop legacy cover position attrs from updates ([6fd2935](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6fd2935a7366e18398de2cdeb18f913c9ed16368)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** hold cover current update on motion start ([07d6095](https://github.com/RiDDiX/home-assistant-matter-hub/commit/07d609554b05f49f141b0a9449a49969befc4faf)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** split cover state/target/current matter reports ([30fac32](https://github.com/RiDDiX/home-assistant-matter-hub/commit/30fac3259922852aafe7344e8669eccbdbf28625)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** write cover target before state in patch ([4af65f6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4af65f659edfab6737cad05eb48eae64bfeda27d)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#328:** write target before current in cover updates ([28626a1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/28626a1460110483c1fb3990405d97f2aa925e3a)), closes [#328](https://github.com/RiDDiX/home-assistant-matter-hub/issues/328)
* **#330:** load serialNumberSuffix when editing bridge ([bfe068c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bfe068cffc0ff81e16e76fa310dfc6af8b834a96))
* **#330:** preserve serialNumberSuffix when trimming to 32 chars ([705ce07](https://github.com/RiDDiX/home-assistant-matter-hub/commit/705ce075f38758bf8def469101c877ed74148dd2))
* **#331:** widen cover slider debounce window to 300ms ([71795e7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/71795e7a9ae1360e9623cc914ad805c3cde667bf)), closes [#331](https://github.com/RiDDiX/home-assistant-matter-hub/issues/331)
* **#334:** stop reporting charging once docked vacuum is full ([0b8b87f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0b8b87f96a1f9c82d349721973043c66eb25e565)), closes [#334](https://github.com/RiDDiX/home-assistant-matter-hub/issues/334)
* **#335:** clear currentArea when vacuum returns to dock ([50e251d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/50e251d27bdec70cbcbec1f3cb1f83df6b2750b9)), closes [#335](https://github.com/RiDDiX/home-assistant-matter-hub/issues/335)
* **#335:** clear stale currentArea inherited across restarts ([a29d5ab](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a29d5ab3bcafab86ce1ac61416f98588f4efdf9b)), closes [#335](https://github.com/RiDDiX/home-assistant-matter-hub/issues/335)
* **#335:** dispatch custom service areas sequentially ([75b6a5f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/75b6a5f23ea35dc6536a781bd4e6beaf9cb51f66)), closes [#335](https://github.com/RiDDiX/home-assistant-matter-hub/issues/335)
* **#335:** preserve customServiceAreas in dynamic RvcRunMode supportedModes ([5c7b926](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5c7b926b8e21cb1f9583076a1d606e7af423735e)), closes [#335](https://github.com/RiDDiX/home-assistant-matter-hub/issues/335)
* **#335:** set observedCleaning on every cleaning event ([f9883b4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f9883b41c13024c68189edef3da49e3612333c81)), closes [#335](https://github.com/RiDDiX/home-assistant-matter-hub/issues/335)
* **#336:** swap bridge-icon HEAD probe for /exists ([2ab3877](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2ab387787fe2ec17e7a3ec48026640de6ff8d3b6)), closes [#336](https://github.com/RiDDiX/home-assistant-matter-hub/issues/336)
* **#340:** freeze immediately on off transition, clear on action=off ([4c80854](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4c808543898a63afe76aac56bbaa23fea42eb251)), closes [#340](https://github.com/RiDDiX/home-assistant-matter-hub/issues/340)
* **#340:** keep mode through cool to off+idle ([8c2adf3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8c2adf3df72f9959293e87d3454b959290d07c2d)), closes [#340](https://github.com/RiDDiX/home-assistant-matter-hub/issues/340)
* **#341:** make HA WS message timeout configurable, raise default to 60s ([b71cbfd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b71cbfd006313ce0650fe0f9f0f7d90323d67c10)), closes [#341](https://github.com/RiDDiX/home-assistant-matter-hub/issues/341)
* **#343:** add PowerTopology + cumulativeEnergyImported default ([e860165](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e860165643d9b07674ba9587f5a577e875450987)), closes [#343](https://github.com/RiDDiX/home-assistant-matter-hub/issues/343)
* **#343:** default activePower=0 on energy sensor endpoint ([8704cd6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8704cd6c62fb80913d33717f49745946e54e31f1)), closes [#343](https://github.com/RiDDiX/home-assistant-matter-hub/issues/343)
* **#345:** dedupe @codemirror/state for json editor ([086b74f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/086b74f15a9d8e6b64bdebfc83f84a357a70145f)), closes [#345](https://github.com/RiDDiX/home-assistant-matter-hub/issues/345)
* **#347:** heap headroom and force-sync pressure guard ([eefa259](https://github.com/RiDDiX/home-assistant-matter-hub/commit/eefa259b9cedbf9467e0a82f24b56775428dc640)), closes [#347](https://github.com/RiDDiX/home-assistant-matter-hub/issues/347)


### Features

* **#287:** bridge setting for session rotation ([2c595ad](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2c595adfa69c98ba355d5468a9903bcd3dd938de)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#290:** add per-entity customVendorId and HA-registry serial fallback ([8f252f6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8f252f6e3ff2c21fed408f3243dd28891e4bdb83)), closes [#290](https://github.com/RiDDiX/home-assistant-matter-hub/issues/290)
* **#331:** per-bridge and per-entity cover slider debounce ([b61670e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b61670e45a6195b395190f89dcaccd22f53d4c2f)), closes [#331](https://github.com/RiDDiX/home-assistant-matter-hub/issues/331)
* **#337:** any_field_regex matcher for grouped AND/OR filters ([0169ecf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0169ecf671fe605c853079f66256fa36e3e9bac1)), closes [#337](https://github.com/RiDDiX/home-assistant-matter-hub/issues/337)
* **#337:** regex filters for entity and device labels ([8138a07](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8138a07081380143f058c85db1df560ce218db00)), closes [#337](https://github.com/RiDDiX/home-assistant-matter-hub/issues/337)
* **#338:** entity-id autocomplete in filter rules ([183588a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/183588a0a3e20c5ea4539ec646a04edb5485ebdd)), closes [#338](https://github.com/RiDDiX/home-assistant-matter-hub/issues/338)
* **#340:** per-entity climateKeepModeOnIdle for off+idle ACs ([847120e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/847120ee44f9dea94682ddd63ad3f01e388baed5)), closes [#340](https://github.com/RiDDiX/home-assistant-matter-hub/issues/340)

## [2.0.43](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.42...v2.0.43) (2026-04-29)


### Bug Fixes

* **#281:** set currentArea on externally-started cleaning ([62b371a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/62b371a445aeb9c403891e237311641b925b97fb)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* **#309:** drop matter automode for ha-auto-only ac ([66abbfc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/66abbfcae6d3f357f30a89a2959d57dac27a382f)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#309:** keep ha-auto ac systemMode stable when hvac_action goes idle ([e35a052](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e35a05286c2d813c707f292b64c851d329457611)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#312:** map cover device_class=window to Rollershade ([adbddbd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/adbddbd602e6339f3cefb5672f4e7d8724d8ddde)), closes [#312](https://github.com/RiDDiX/home-assistant-matter-hub/issues/312)
* **#320:** use sibling identify button when vacuum.locate unsupported ([f722ece](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f722ecec15b8f8b45a15be15e8f20681fde89a72)), closes [#320](https://github.com/RiDDiX/home-assistant-matter-hub/issues/320) [#208](https://github.com/RiDDiX/home-assistant-matter-hub/issues/208)
* **#322:** recognize UWANT/Xiaomi sweep/mop labels ([050c45d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/050c45d2e2a1a7808e27cec10ed07c5ee37bea4a)), closes [#322](https://github.com/RiDDiX/home-assistant-matter-hub/issues/322)
* **#323:** pick valid Type for lift+tilt window coverings ([2ed05af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2ed05afa16b70d2f0a5ba5eb1e0e16a3887d4e3a)), closes [#323](https://github.com/RiDDiX/home-assistant-matter-hub/issues/323)
* **#327:** make sensor reactors offline so updates reach controllers ([ef65ff6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ef65ff64cc49c67eb238c0ed81581d871232cf81)), closes [#327](https://github.com/RiDDiX/home-assistant-matter-hub/issues/327)


### Features

* **#321:** snap climate setpoints to entity step ([e507c0d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e507c0d6be409f149d88a60abf529df36878aac2)), closes [#321](https://github.com/RiDDiX/home-assistant-matter-hub/issues/321)
* **#325:** add japanese translation from [@kimera257](https://github.com/kimera257) ([5934f4e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5934f4e910e5b01284d55068e35831d09756a8df)), closes [#325](https://github.com/RiDDiX/home-assistant-matter-hub/issues/325)
* capture matter.js controller traffic in /api/logs ([d8d28a2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d8d28a2d69b3aac64097c733253f202d79c0f028))

## [2.0.42](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.41...v2.0.42) (2026-04-26)


### Bug Fixes

* **#316:** align root softwareVersionString with version ([ae4b33d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ae4b33d7c60064cfe9b02e3c579f4d1416358d87)), closes [#316](https://github.com/RiDDiX/home-assistant-matter-hub/issues/316)
* **#319:** clamp climate auto to heat/cool on non-AutoMode bases ([6dd4ded](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6dd4ded1a001eb7e18808cb78c908fb1187a7ad9)), closes [#319](https://github.com/RiDDiX/home-assistant-matter-hub/issues/319)

## [2.0.41](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.40...v2.0.41) (2026-04-23)


### Bug Fixes

* **#302:** use DeadFrontBehavior for climate OnOff cluster ([a64fb9b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a64fb9b4fffa32955bca2fec2db03a72fc1ff8f6)), closes [#302](https://github.com/RiDDiX/home-assistant-matter-hub/issues/302)
* **#305:** patch matter.js to accept long operational cert serials ([2a08033](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2a08033206cbc45e8f2eb0a3e26e47d99c0a761a)), closes [#305](https://github.com/RiDDiX/home-assistant-matter-hub/issues/305)
* **#306:** put alexa brightness-reset workaround behind feature flag ([6e3329d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6e3329d29e47375374e5eb67fce34985797e7ff0)), closes [#306](https://github.com/RiDDiX/home-assistant-matter-hub/issues/306)
* **#308:** use fan.set_percentage so already-on fans accept speed changes ([9b27bbc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9b27bbc16e0b90c08f40a5d573cfc1578d66acdc)), closes [#308](https://github.com/RiDDiX/home-assistant-matter-hub/issues/308)
* **#309:** expose matter auto mode for climate devices with ha auto ([55e7ef6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/55e7ef6df16b3db2d9b5f11f47d1805f5c73a037)), closes [#309](https://github.com/RiDDiX/home-assistant-matter-hub/issues/309)
* **#311:** apply server-mode root identity via transactional set ([4ed4dfd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4ed4dfd17269f0d91000f004ea8c9d78bc398d3a)), closes [#311](https://github.com/RiDDiX/home-assistant-matter-hub/issues/311)
* **#312:** avoid TiltBlindTiltOnly for lift-only blinds ([01e778f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/01e778f92ae439bff70c11fc98ea89b73325f69b)), closes [#312](https://github.com/RiDDiX/home-assistant-matter-hub/issues/312)
* add 30s timeout to ha sendMessagePromise calls ([a66f150](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a66f1506078235f2aa6b240284eb3add072c1e6f))
* clear pending debouncers on unregisterAll ([2be9c22](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2be9c22d0a4e69e90832629817292591a30e9205))
* compare entity attributes with deep-equal not json round-trip ([4ff6d94](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4ff6d94532cdef44472e4f0d981e5f61b66b8ca7))
* correct thermostat running state for unknown modes and drying ([b88ec13](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b88ec13736ad61fc46025ba67f793b982cbaf3de))
* dispose AppEnvironment on graceful shutdown ([dc94c77](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dc94c779d52fff65e20bfef279bf59d692ff0ee2))
* graceful shutdown on api/backup/restart ([01349ad](https://github.com/RiDDiX/home-assistant-matter-hub/commit/01349adc9b35a103c7b1022005e1061368eabe9f))
* guard auto-refresh against overlapping reloads ([22254a3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/22254a3dc6742e5612cccb71756f94d4e98c99db))
* guard mireds conversion and align colorMode publishing ([b858694](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b858694a5d03f416f2c974a55aa439b89fa11c7b))
* log and surface bridge import errors ([cba6296](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cba6296052e0d726412eb76be22c2e6d7345129d))
* parallelize home assistant registry fetches ([6c30827](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6c3082721a8617325cec6afedcc0a11f35a1470a))
* reject web-api start on port conflict ([757348d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/757348de16385a60da3c6a4571c5a0082da80bb5))
* retry transient network errors on ha connect ([a3e2504](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a3e25041aec32229b95827c8bbdc6fae62441350))
* serialize bridge start and stop lifecycle calls ([d4a0367](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d4a03678c5acd8c9569707801fd05754e7e30ff5))
* serialize updateStates and detach plugin listeners ([7839ef2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7839ef2f11d21ec76560a088a92b66953f403a47))
* stop bridges in parallel during stopAll and restartAll ([c89101a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c89101a982755ff31ae4ddb30f7af89794e4ae3b))
* sweep stale optimistic state entries on set ([af22805](https://github.com/RiDDiX/home-assistant-matter-hub/commit/af228056864dfc48c2c14c00df12ad1721aec0d2))


### Features

* add boolean state configuration cluster on leak freeze rain contact ([67da2b7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/67da2b7d1a1afb1758bc23af0298a62852aa35d5))
* wire groups and scenes management on light plug and fan endpoints ([220373d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/220373ddf07ada84564ee65b138a20c6183fa7e4))

## [2.0.40](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.39...v2.0.40) (2026-04-12)


### HOTFIX (from v2.0.39)

* **#297, #299:** fix crash loop on startup — Node 22 native WebSocket drops connections on both aarch64 (RPi) and amd64; now forces `ws` library ([d5b07c7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d5b07c7c))
* **#297:** fix service initialization errors being silently swallowed, causing the process to hang instead of exiting
* **#297:** registry fetch now waits for WebSocket reconnect between retries with increased retry tolerance


### Bug Fixes

* **#298:** add select, input_select, siren to filter preview domain map ([4804c22](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4804c2258db8c82ce83a236ddbe908e8b25d753c)), closes [#298](https://github.com/RiDDiX/home-assistant-matter-hub/issues/298)


### Features

* add support link in footer and docs page ([4185c4e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4185c4e340033ab830fc8f12e69720a489511b79))

## [2.0.38](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.37...v2.0.38) (2026-04-11)


### Bug Fixes

* **#273:** auto-map HA moisture sensors to HumiditySensor ([924fe4c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/924fe4cd24d2e2f5e245f08e4d2755b362d82e78)), closes [#273](https://github.com/RiDDiX/home-assistant-matter-hub/issues/273)
* **#275:** restore fan speed on turn-on and guard speed rounding ([1895fb2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1895fb20e5fce01b3033f392cb4bdcc82b965d94)), closes [#275](https://github.com/RiDDiX/home-assistant-matter-hub/issues/275) [#219](https://github.com/RiDDiX/home-assistant-matter-hub/issues/219)
* **#281:** persist cleaning session state across behavior proxy calls ([fac2330](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fac2330cf872ae72c43b77bb7538bb4f7e688daa)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281) [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* **#281:** preserve progress across mid-session idle in multi-phase cleans ([9a64cf5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9a64cf50142fd10185d32ae9219ba2cfab705ee7)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* **#281:** push operationalState and currentMode in keepalive ([9d9fdec](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9d9fdec1430ff3d723814926027589c9e39be17d)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281) [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* **#281:** use endpoint instead of agent as WeakMap key for cleaning session ([65c2ed7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/65c2ed7a7806085a35b8dfeeca88e447a6729676)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281) [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* **#286:** guard all behavior update() methods against missing attributes ([47f58ae](https://github.com/RiDDiX/home-assistant-matter-hub/commit/47f58aee50e9b6f9180c88a51bf4e480d3a88661)), closes [#286](https://github.com/RiDDiX/home-assistant-matter-hub/issues/286)
* **#286:** guard endpoint-specific sensor update() against missing attributes ([d5a6cfc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d5a6cfc046130285909f37dab46e2f827a87ddc3)), closes [#286](https://github.com/RiDDiX/home-assistant-matter-hub/issues/286)
* **#287:** keepalive writes directly to RvcOperationalState cluster ([cc60f50](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cc60f50bfcc07a858052ebf6dd41b4c115a2fe26)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287) [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** make rvc reactors offline to produce subscription reports ([bd9857f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bd9857f8647fd5823609179d6589d1a0ef3b45b8)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** use counter-based nonce and add keepalive diagnostics ([01a781a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/01a781ab468afe61753136ad0b6303ec91b7a037)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** use Date.now() instead of instance nonce for keepalive diff ([5e8970b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5e8970b85bb7ba42c3e9f58a8cb738a73cccb853)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287) [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287) [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** use errorStateDetails instead of errorStateLabel for keepalive ([10d33c9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/10d33c92f0de1ffe8c6756760739fd1b0540eab3)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#287:** use setStateOf for keepalive instead of act() ([87e2062](https://github.com/RiDDiX/home-assistant-matter-hub/commit/87e20622c4a2b7f2f96733f7e1b28fcb5108a78c)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#289:** derive multiPressMax at endpoint creation time ([671543b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/671543b545d240a017a59872f93806f50415a55d)), closes [#289](https://github.com/RiDDiX/home-assistant-matter-hub/issues/289)
* **#289:** fix GenericSwitch event handling for Apple Home buttons ([af66db3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/af66db3f7840122779a04aa3fe6c75508f3433b5))
* **#289:** resolve expired-reference error and lost long press events ([77a4b7a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/77a4b7ac2d73181381748cc756199b23bb5df873))
* **#289:** split GenericSwitch into single/multi variants ([941b7d2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/941b7d294d8e393684e8f41852e62eaa5d253f31)), closes [#289](https://github.com/RiDDiX/home-assistant-matter-hub/issues/289)
* **#290:** biome formatter compliance for serialNumber line ([243865e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/243865e0e1ce0d06379f2d9c3d5d02c3aaf8598c)), closes [#290](https://github.com/RiDDiX/home-assistant-matter-hub/issues/290)
* **#290:** populate server-mode root BasicInformation from entity data ([a1b7174](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a1b7174e7208630e416fb6325c0a54a88af7aa4b)), closes [#290](https://github.com/RiDDiX/home-assistant-matter-hub/issues/290)
* **#293:** honor speaker override for tv media_player entities ([255143b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/255143b73fef0fb4aec49eff95e97f7275456019)), closes [#293](https://github.com/RiDDiX/home-assistant-matter-hub/issues/293)
* add startup force sync to server-mode-bridge ([#282](https://github.com/RiDDiX/home-assistant-matter-hub/issues/282)) ([bf59ee2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bf59ee2a5308f6b7f44690cc55f62e2bbf2d6856))
* **alpha:** correct vacuum spec-violating state combinations ([#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)) ([22aaa0d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/22aaa0d3aba20bcca36417b5d8afd0356bcaa895))
* **alpha:** force structural diff in operationalError to trigger subscription reports ([#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)) ([d731f71](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d731f711e911674130c9d648e55c3e79e9422b0e))
* **alpha:** improve currentRoom sensor matching and add INFO logging ([#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)) ([6e42c9e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6e42c9ec3b8218667a444ff0ff389332848f893c))
* **alpha:** preserve activeAreas during brief state transitions and fix Dreame room_id matching ([#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)) ([f8dcf77](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f8dcf77878f760f579db9bdffa7b8335b34c9436))
* **alpha:** surface silent currentRoom short-circuits and log legacy vacuum auto-assignments at INFO ([#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)) ([3390e42](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3390e422611a6c054f6864164b51a3493a00895e))
* auto-map radon sensors to RadonSensorDevice ([4718b70](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4718b704ee99fe4d7cf401e85cd287bdb2e0dfca))
* auto-map rain binary sensors to RainSensorDevice ([f0abbf8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f0abbf8f473e0ad314f8ee6b6fdf32201c6a8742))
* avoid infinite recursion in ServiceArea progress update ([3a92134](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3a9213401d42d1ac6f080856c0afc1ad33f8d800)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* biome formatting for activeAreas guard condition ([edd1da2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/edd1da2d43cad0bf3bdf259666270539115cd8c8))
* biome formatting in create-legacy-endpoint-type ([9c43060](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9c430605cfe2899ed06d8e81447d279bf1cb97fb))
* biome formatting in sidebars.ts ([cfb0413](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cfb04136a19b00a30d4edcb23638a86618d64ed6))
* bounded HA connection retries and memory leak cleanup on dispose ([bc43ebe](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bc43ebee7506d4c148dc908313696b173a163381))
* correct broken README links to docs-site URLs ([8b69473](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b69473e776155b0ee969c571470ee2f0a1b8bd1))
* correct logo path and lint trailing whitespace ([#282](https://github.com/RiDDiX/home-assistant-matter-hub/issues/282), [#285](https://github.com/RiDDiX/home-assistant-matter-hub/issues/285)) ([514338a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/514338a57c60e74e2eb8df3bf60ba94800c87fe8))
* enable ServiceArea ProgressReporting for room cleaning status display ([64fbebd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/64fbebdd6e6102a57eaadcb8c2b06a9b58de8c15))
* guard against missing attributes during HA restart ([#286](https://github.com/RiDDiX/home-assistant-matter-hub/issues/286)) ([02d10ba](https://github.com/RiDDiX/home-assistant-matter-hub/commit/02d10baa814a1e1b79cc9ea97390c7aed1ed14ab))
* periodic keepalive to prevent Apple Home "Updating..." ([#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)) ([c20b03b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c20b03bd5ec047edb5b9a4943ccaca83be4eafc2))
* persist currentRoomEntity in entity mapping API and storage ([04089b4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/04089b4c52dfad0caa8384d00520a9e9043e26bd))
* persist custom product/vendor/serial in entity mapping api ([933b3c7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/933b3c792b8e7319d58c065502868342a8946e7f))
* persist plugin config to registry on API update ([bd6f40b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bd6f40b7b74fda0a261320c1b8ae6c1c037e7be3))
* push new log entries to SSE stream subscribers ([5ab1444](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ab1444233f5b97574406b88bb6f1cac7233e436))
* remove HEALTHCHECK from addon Dockerfile ([932b8aa](https://github.com/RiDDiX/home-assistant-matter-hub/commit/932b8aab28351af63860f5b1606dc47cdf5888ba))
* restore missing mapping fields in backup restore paths ([8ee73bf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8ee73bf4534b1364fe275d6419671f02c50f4536))
* retain active areas for progress tracking during cleaning session ([28aa0be](https://github.com/RiDDiX/home-assistant-matter-hub/commit/28aa0be030845770e79da4e726d0e2dfcfee37fe)), closes [#281](https://github.com/RiDDiX/home-assistant-matter-hub/issues/281)
* send area_id from area-based bridge wizard ([6c02cde](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6c02cde891e6cd57e8ffa1d05c883e14111ca3f1))
* set currentMode in changeToMode and restore currentArea on cleaning transition ([7eb8798](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7eb87983b831917b7bc9e2f5ae93ea6785f7437e))
* strip BasicInformationServer from composed sub-endpoints ([29db91b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/29db91b357146290516ac229728afcc80ce359f7))
* update ServiceArea currentArea during vacuum cleaning for Apple Home status display ([05e82d4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/05e82d477720123ab3d9fd30554dfb4ec05e75a9))
* use interval timer for vacuum keepalive instead of in-update check ([5952b8e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5952b8e40b8312fd1409aa4e15e0848e5eb98aae))


### Features

* **#290:** add customSerialNumber per-entity override ([5ec2573](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ec25734f9499ddcfc692988373819e456e75b91)), closes [#290](https://github.com/RiDDiX/home-assistant-matter-hub/issues/290)
* **#55:** discrete Open/Close mode for garage and gate covers ([30c4b5b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/30c4b5b77a72b59127dad0db4e94be43e6149465))
* add customProductName and customVendorName entity mapping overrides ([0cca498](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0cca498fc4619202c60c4e5bfb886ccacfdd662b)), closes [#277](https://github.com/RiDDiX/home-assistant-matter-hub/issues/277)
* add dishwasher device type override for switch entities ([5f41e3b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5f41e3b3d86099dec07ca8f5624cecc704d9eebf))
* add Docker HEALTHCHECK to standalone and addon images ([12ced3b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/12ced3b7ec6ad5e8ab5dcf537a76e8000a726e3b))
* add Polish (pl) i18n locale ([#288](https://github.com/RiDDiX/home-assistant-matter-hub/issues/288)) ([3a9aa79](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3a9aa79da56c27c40b5a8e400cbc9f80d65ff548))
* add productNameFromNodeLabel bridge flag for aqara ([32c49d3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/32c49d34d1ef71d42a7180d13612a5614ed36716))
* add siren domain support as OnOff Plug-in Unit ([ad0e024](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ad0e024f3ea5fdb0eab5fbf677cb02ac662fffc7))
* dynamic room progress tracking via currentRoomEntity sensor ([b95d0c1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b95d0c194f8dae83324be4ab8b2c5bca2a80ebb0))
* emit diagnostic events for commands, sessions, and errors ([ddb66d4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ddb66d44daf682b76e6bc3af84ba03715506128f))
* emit diagnostic warning for unsupported sensor device_class ([cc40bd2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cc40bd2b202b8f2b93424250a0f68dfbb9897b0d))
* energy/power measurement support on composed devices ([977cf34](https://github.com/RiDDiX/home-assistant-matter-hub/commit/977cf34f65209936132324fc0d5bd983d0fac994))
* immediate force sync on startup ([#282](https://github.com/RiDDiX/home-assistant-matter-hub/issues/282)) ([2404f4b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2404f4bb422532ceb778c431236577a92c3846f8))
* latency instrumentation in state update path ([a380d74](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a380d74877e65b0a71af56f395b1493692730eae))
* mDNS/network diagnostic API endpoint and frontend card ([198a222](https://github.com/RiDDiX/home-assistant-matter-hub/commit/198a2228498524f3086da0745128799ea6c69553))
* multi-admin fabric diagnostics in session info and health API ([59e7ef9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/59e7ef9627fedac8fe6cc61871016b16113ec4be))
* startup memory guard, reduced log buffer, and low-resource docs ([aee5638](https://github.com/RiDDiX/home-assistant-matter-hub/commit/aee56387b1fc8ceb285e63dcf3ffd1278c2d2b2c))
