## [2.0.26](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.25...v2.0.26) (2026-02-23)


### Bug Fixes

* **#105:** add non-destructive session lifecycle logging for diagnostic visibility ([3044f89](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3044f893ef65809cec02b97bbacfc28216fe17d0)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* **#110:** add diagnostic logging for vacuum clean mode changes ([d4990b7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d4990b7de03525fb54095d2e8767f962b0ba7df5)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** dispatch cleaning mode before intensity and remove stale state check ([c56b9c7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c56b9c757693157daa657c4ab1aa60118b0c295a)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** positional fallback for vacuum suction/mop intensity matching ([f93626d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f93626de97c1e1e9e216ce532bb06689284b3916)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** switch cleaning mode entity when Apple Home sends intensity mode ([a393aa1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a393aa18bb5fcd21dac5e6a01d1ff96a9d5a37b5)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** use target entity for action debounce key ([4ca1590](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4ca15905df9a28128d5aa0ba691f9f374209e6db)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#148:** coverUseHomeAssistantPercentage takes precedence over coverSwapOpenClose for position ([8bb457b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8bb457b166da88fdf8fd6fea0d7d0c98de19379f))
* **#165:** restore Auto tag for mid-range fan speeds, add tag dedup logic ([b5f5d72](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5f5d72506b5df1c52adf3c1fc68112cd1b991b3)), closes [#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)
* **#176:** preserve setpoint nudge while device is Off ([d95b37c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d95b37c51f53cd83bf26b7ed83b85bf04abf0926)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#176:** replace unreliable setpoint nudge with property setter interceptor ([b5d01e7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5d01e7f767a91568c1087dfad11623dca84fc52)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#189:** fallback 'Vacuum Then Mop' to 'Vacuum & Mop' when entity lacks dedicated option ([fbf9d95](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fbf9d95df6ee82f0e149624920f30746c4cd73c9)), closes [#189](https://github.com/RiDDiX/home-assistant-matter-hub/issues/189)
* **#190:** cgroup-aware heap sizing for Docker/HA OS containers ([0dc84c7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0dc84c7bebd611f3e50d54321246b2a862ca7e0a)), closes [#190](https://github.com/RiDDiX/home-assistant-matter-hub/issues/190)
* **#191:** restore subscription persistence disabled to prevent Apple Home Updating status ([f9588df](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f9588df66faa9eec9fb77f7a95133dd3a2e076d4)), closes [#191](https://github.com/RiDDiX/home-assistant-matter-hub/issues/191)
* **#198:** dispatch all button presses for multi-room ServiceArea selection ([91a8c44](https://github.com/RiDDiX/home-assistant-matter-hub/commit/91a8c449e540f90c738cf6f827148ffb75882ff1)), closes [#198](https://github.com/RiDDiX/home-assistant-matter-hub/issues/198)
* **#199:** use directional commands for cover open/close instead of position path ([176d840](https://github.com/RiDDiX/home-assistant-matter-hub/commit/176d84063931d95420b3e6d01844bd67482b3a77))
* **#200:** pin Docker runtime to Node 22 to fix ERR_INVALID_PACKAGE_CONFIG ([49fa22c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/49fa22c632eb95fbff84f00d5c979bbf18c0be02))
* **#202:** allow editing entity filter for server mode templates in wizard ([fcb3909](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fcb39098af57a4ff6ac75042546e1abd39fa89e3)), closes [#202](https://github.com/RiDDiX/home-assistant-matter-hub/issues/202)
* **#202:** entity filter change on server-mode bridge now updates the endpoint ([cd24810](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd24810c6fc3c2e025239b316679486031af9ef8)), closes [#202](https://github.com/RiDDiX/home-assistant-matter-hub/issues/202)
* **#203:** show start/stop/restart buttons with single bridge ([f5abfff](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f5abfff4d84b8c3a90a2dedca6494f21817d8dcc)), closes [#203](https://github.com/RiDDiX/home-assistant-matter-hub/issues/203)
* add missing pressureEntity to entity-mapping API, harden API error handling, use proper Logger in lock/water-heater, prune stale sync state, add cover inversion tests ([9565655](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9565655aa6457241def40a5224287e5373fa9eda))
* add setpoint nudge for same-value auto-resume while thermostat is Off ([5fafd17](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5fafd17d2b3015b41d6c414ff1603c7f8c78733a)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* always auto-detect battery entity for server-mode vacuums ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([16e42ed](https://github.com/RiDDiX/home-assistant-matter-hub/commit/16e42edcfd051fb6bb55965141d4c44472e3fe1b))
* assign intensity tags to all matching fan speeds for Apple Home visibility ([e8d2378](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e8d23784d7423e258f72e65856f88b2736dfe0f4))
* clarify that Alexa requires OnOff cluster for robotic vacuums ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([a50314b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a50314be4079836bc2cfb433ae0aa0b732a906e6))
* coverSwapOpenClose now also inverts position reporting ([b5653ff](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5653ff42ed77fc21d5b1bf3e5c78f50ec062481)), closes [#195](https://github.com/RiDDiX/home-assistant-matter-hub/issues/195)
* implement KeypadInputServer for BasicVideoPlayer media endpoint ([dc0c8ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dc0c8ca853418363b2613b0b217dfb56c64c25c9))
* live diagnostics text overflow and sync sorting with bridge status ([44837ac](https://github.com/RiDDiX/home-assistant-matter-hub/commit/44837ac83024ee70a586a4d83ded06bd6d611e4f))
* prevent frontend crash when serializing disposed Matter.js containers ([#193](https://github.com/RiDDiX/home-assistant-matter-hub/issues/193)) ([5ce8c7d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ce8c7d5a37b36d5706ece0711381717b4ec03f9))
* reduce WindowCoveringServer log noise by moving position updates to DEBUG ([8b0381b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b0381b64b7b35ba64b9d8140e5a467f2eda3fec))
* remove auto-added PowerSource device type from descriptor ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([31550cf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/31550cf07b84a155a03ebcd89dd1bb6d728ba6a5))
* remove PowerSource cluster from server-mode vacuum endpoint ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([45be591](https://github.com/RiDDiX/home-assistant-matter-hub/commit/45be591e8c814861e004f5d5b980e719c401443e))
* remove thermostat setpoint write interceptor causing 'Cannot redefine property' crash ([93d7ce6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/93d7ce603ad77c827301f154cea683cbf97db1fc)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* restore PowerSource device type on vacuum endpoint to match Matterbridge ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([1789c73](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1789c73c9dac4e53e2531a1d8fd45ffcd038aca6))
* use 1-based mode IDs for RVC clusters and restore PowerSource ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([6a452a9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6a452a94bed5720dd5526dab95396448ff896a8b))
* vacuum OnOff turnOff sends return_to_base instead of stop ([046d6cf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/046d6cf389b8fcf0e347fc0d77fcd9ec35cda15b))
* validate mode in changeToMode overrides (Matter spec compliance) ([400002d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/400002d0f13d839e6882ef0dc9bdf3181b65b6dc))


### Features

* **#197:** add authentication configuration from UI ([c84cf89](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c84cf89341a37a27ecf49be94cfd51db411c4e29)), closes [#197](https://github.com/RiDDiX/home-assistant-matter-hub/issues/197)
* dynamic compatibility warnings in bridge config editor ([304d93c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/304d93cc9f5fd930f4d6eeb9de08d0cbfe58820b))
* expandable cluster diagnostics in device cards ([0cdee8c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0cdee8c6ee85743425636196abff45679e01e72a))
* support select and input_select entities via ModeSelectDevice ([396b663](https://github.com/RiDDiX/home-assistant-matter-hub/commit/396b663a544b117892793ff916323d1c8db24bd6))
* update matter.js packages from 0.16.8 to 0.16.10 ([675713f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/675713f8ee8645454a0a5727ba2c662d38a031ad))
* webhook event bridge  fire hamh_action HA events for controller commands ([08ebcb2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/08ebcb26c29d34a969a666bdb2bc198d99825939))

## [2.0.25](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.24...v2.0.25) (2026-02-21)


### Bug Fixes

* **#110:** restructure RvcCleanMode to flat modes for Apple Home extra features ([905bf24](https://github.com/RiDDiX/home-assistant-matter-hub/commit/905bf24076a5b866af262b3f974e88837f1d6ebb)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#176:** deferred setpoint nudge for reliable auto-resume ([5ab4fe6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ab4fe6a8aae4eca8a5fbd90db707a028573e033)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#189:** unwrap response.response from roborock.get_maps service call ([075df6a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/075df6a35fec9a96e51f95fd0a160eda75d2ebc1)), closes [#189](https://github.com/RiDDiX/home-assistant-matter-hub/issues/189)
* **#190:** dynamic Node.js heap sizing based on available system RAM ([a619c0d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a619c0dbec01fecfa87bdb72e14a5483b6bdb566)), closes [#190](https://github.com/RiDDiX/home-assistant-matter-hub/issues/190)
* **#192:** recreate endpoints when entity mapping changes ([a9c23d1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a9c23d1694c77f710ce9e6dd587eb786d5a29d24)), closes [#192](https://github.com/RiDDiX/home-assistant-matter-hub/issues/192)
* limit RvcOperationalState to well-known states and update OOM FAQ ([130460d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/130460d90da16a94fed340719a775428aedb14ef))
* **oom:** increase heap limit to 768MB, add memory pressure guard and startup logging ([#180](https://github.com/RiDDiX/home-assistant-matter-hub/issues/180)) ([1cd4201](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1cd4201b0578b9908ae14a61a0398051e60dad54))
* prevent Apple Home from renaming fan speed 'normal' to 'Automatic' ([8a5bba9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8a5bba9ca0a0db5973a80f65d2a99618ee8f5c8a))
* responsive mobile layout for dashboard stat cards ([157d9c4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/157d9c481b4148ea76e5b67a61824c54eb182f51))
* update label filter descriptions and value hint in bridge config schema ([53c2c31](https://github.com/RiDDiX/home-assistant-matter-hub/commit/53c2c314cf98cec495e2d468e5a929930798278e))
* **vacuum:** expose fan speed modes for Roborock without cleaning mode entity ([7ed5a78](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7ed5a788e5c9b594a765581719031b9cede1fd34))
* **vacuum:** use exact match for fan speed tags to prevent deduplication ([77be697](https://github.com/RiDDiX/home-assistant-matter-hub/commit/77be697e8a112fbcc9683f0b6e5dbaaefef754ad))


### Features

* **#188:** show decoded vendor name next to fabric icons in FabricList ([86f8aff](https://github.com/RiDDiX/home-assistant-matter-hub/commit/86f8aff0ab0cb7b33a2728f32c7b0da12d8c37a3)), closes [#188](https://github.com/RiDDiX/home-assistant-matter-hub/issues/188)
* dynamic vacuum fan speed modes + vacuumOnOff feature flag ([6cfff16](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6cfff16307c4c8fcbf000a00fda4e8b7ee4a6d91))
* open commissioning window for multi-fabric pairing ([ec808b7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ec808b781e18028146ae2ee7ea218e9785dab0b7))
* show fabric icons with vendor names in bridge details and health dashboard ([3205bd1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3205bd12cb0d8e6c9b65b0743981eadfe874bb5c))
* **vacuum:** add mop intensity modes for Apple Home extra features ([0f5948d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0f5948dac752910969bf2db84d97dee7910dd5af))
* **vacuum:** auto-detect cleaning mode, suction level and mop intensity entities ([d83f83c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d83f83c892ea7cd9a5490ffb38825b29478de527))
* **vacuum:** auto-detect Roborock rooms via roborock.get_maps service ([9679bc1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9679bc185626a83e41b9743108fedd1013772252))

## [2.0.24](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.23...v2.0.24) (2026-02-20)


### Bug Fixes

* **#110:** add Vacuum+Mop tags to combination clean modes for Apple Home ([b21b8ef](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b21b8ef3c4319c9a7375337750529411d22d9421)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#110:** prevent cleaning mode revert by tracking pending mode from controller commands ([036c4d8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/036c4d851772c8eed1591ef7801ba2bdc317b33d)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* **#176:** auto-resume climate even when setpoint value unchanged ([ee80dfc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ee80dfc77d25c75d6418e679b852fbdcb53237c0)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#176:** auto-resume climate on same-value setpoint write via class setters ([a66e77c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a66e77c37e3e5921a35d8db43c222f443cf86169)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#176:** nudge setpoint when off to defeat matter.js same-value dedup ([d4e1a60](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d4e1a6036697204e9939ccc94873dfcb113b80f9)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#176:** safe auto-resume respecting controlSequenceOfOperation and preventing dual-fire ([aabb6ac](https://github.com/RiDDiX/home-assistant-matter-hub/commit/aabb6ac36fe66010d3278e1791e61ec03f6a9ea9)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#176:** skip setpoint nudge during Off transition to fix Google voice confirmation ([93cc045](https://github.com/RiDDiX/home-assistant-matter-hub/commit/93cc04553e54fce7e9c6af388f494476244e87fc))
* **#182:** remove Lighting feature from OnOff for non-light device types ([09b341c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/09b341c431dac1b666600aa42b9d6e31d9787c7d)), closes [#182](https://github.com/RiDDiX/home-assistant-matter-hub/issues/182)
* add warm-start state push and diagnostic events to ServerModeBridge ([#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)) ([9294b39](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9294b3966c6064ac8cb06cd683375b68f01dfb7e))
* additional minMeasuredValue fixes for humidity and flow measurement clusters ([8f501d8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8f501d8eeb6c2a8cdb5782b01fd98858411c8303))
* alpha changelog empty due to HEAD^ excluding latest commit ([4190ecc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4190ecc3b9899e38e03943176ff8dcaed561b3a4))
* always include PowerSource and ServiceArea on vacuum endpoints ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([052dd08](https://github.com/RiDDiX/home-assistant-matter-hub/commit/052dd088376964033668c458f922521dbbec723a))
* always include RvcCleanMode on vacuum endpoints ([#183](https://github.com/RiDDiX/home-assistant-matter-hub/issues/183)) ([7510001](https://github.com/RiDDiX/home-assistant-matter-hub/commit/751000182e7c03ec0b1f96c9cfec405ea34e08b6))
* automation turnOff now disables instead of being null ([cd67a2e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd67a2ed2edfbf4e124c7e651a86f51885462927))
* change minMeasuredValue from 0 to 1 in electrical measurement clusters ([3bb26fb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3bb26fb19527f54ed8d584c231313771aae62321))
* correct Config Backup icon in Health Dashboard (cloud arrow up) ([0f5f762](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0f5f76252f80651dc0810d3f3a097e3d4244e168))
* correct DoorLock supportedOperatingModes inverted semantics, add ElectricalEnergyMeasurement event emission, fix thermostat setpointRaiseLower divisor ([0da15a4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0da15a4f9cbf901111f6b8f6c48e89d128b8741e))
* handle HA WebSocket connection-lost errors gracefully ([#180](https://github.com/RiDDiX/home-assistant-matter-hub/issues/180)) ([d0cb755](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d0cb7559231ec9d1b2c15d72d38c82eee159c66b))
* **logging:** add cache to battery lookup and remove spam ([b07cc92](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b07cc9287e73ddc53c319ad305c79165260e2e01))
* **logging:** reduce bridge-registry battery warning spam ([6dec983](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6dec983ddcc962cb5fcc063ed3fd52d4c8511fcc))
* **oom:** delete endpoints in dispose() to prevent memory leak ([#180](https://github.com/RiDDiX/home-assistant-matter-hub/issues/180)) ([765e185](https://github.com/RiDDiX/home-assistant-matter-hub/commit/765e185b41b9e2889c39e2ef102978c770d3768d))
* remove custom subscription monitoring, use matter.js defaults ([d044fa2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d044fa2da27c341f65889056559f30481eaed373))
* revert flow minMeasuredValue to 0 (0 is a valid uint16 value, not null) ([debf759](https://github.com/RiDDiX/home-assistant-matter-hub/commit/debf759403f7b7e6384d8cbdd1d5d950b56702b7))
* set humidity minMeasuredValue to 0 (uint16 cannot be negative) ([4fbc9d8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4fbc9d85a81431fe66ac6723763284312758cd4b))
* swap import/export icons in bridge overview ([c73bfe9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c73bfe9e125d0eb9add035ff076e53427c14ad68))
* **thermostat:** add defensive checks to setpoint interceptor to prevent initialization errors ([2c7a9b9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2c7a9b9cada3426b4cf80765a23d122909569448))
* **thermostat:** make setpoint interceptor idempotent to prevent redefine error ([40c1946](https://github.com/RiDDiX/home-assistant-matter-hub/commit/40c1946d7ae38237bc6aae598c4e01f4c78a4647))
* **thermostat:** remove broken proxy code causing initialization errors ([2ce4f78](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2ce4f782c91cefe085890222a83c232e0beabaa9))
* **thermostat:** use Proxy instead of property override for setpoint interception ([aa753f9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/aa753f99d4f11ea4ccbac494c8f10eb3cfc5edcc))
* use negative minMeasuredValue to allow 0 readings in measurement clusters ([4cb07d4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4cb07d4bd7f9bb5d546705fadd29f2417b6cdf19))
* **vacuum:** show docked instead of paused when idle and charging ([#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)) ([91ae4fc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/91ae4fca32b33b162b661fb3ad899889e1bd5c3a))


### Features

* add tooltips to filter type dropdown with descriptions for each option ([9627843](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9627843cf0b54eed97b7977828cfa00ab5776ca0))
* add WaterFreezeDetector device type for binary_sensor.cold ([e075de9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e075de95474087ec577da5dce587421f28ae4ec3))
* **frontend:** improve Dashboard UX - alphabetically sort bridges, add navigation guide, remove duplicate buttons, mobile responsiveness ([96964d3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/96964d3be8ed5bfcf87efbcc149e1a269489378f))
* implement real Matter Composed Devices for sensor endpoints ([#179](https://github.com/RiDDiX/home-assistant-matter-hub/issues/179)) ([bca0b28](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bca0b28610b548086c3305ad4e861198d94685be))
* live diagnostics dashboard with WebSocket event streaming ([aed990e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/aed990ed212e9925b0e86371bd400cbbbbcdd80b))
* **vacuum:** add suction level entity mapping for Apple Home extra features ([c70c2c2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c70c2c251354cac8928598accd246c2f87accd42)), closes [#110](https://github.com/RiDDiX/home-assistant-matter-hub/issues/110)
* wire autoComposedDevices master flag to enable all auto-mapping sub-flags ([ffc4487](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ffc4487ea96d1cfe0d680abe35c5d40c17a80bf5))


### Reverts

* downgrade matter.js to 0.16.8 due to constraint parsing bug in 0.16.9 ([35acfad](https://github.com/RiDDiX/home-assistant-matter-hub/commit/35acfad24aafcae9cea78aa49cc8c2a51175da84))

## [2.0.23](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.22...v2.0.23) (2026-02-19)


### Bug Fixes

* **oom:** delete endpoints in dispose() to prevent memory leak ([#180](https://github.com/RiDDiX/home-assistant-matter-hub/issues/180)) ([e75902b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e75902bec9a8a64b3e435574697af86d1a124a15))

## [2.0.22](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.21...v2.0.22) (2026-02-18)


### Bug Fixes

* **#176:** restore auto-resume heating/cooling when setpoint written while off ([754f102](https://github.com/RiDDiX/home-assistant-matter-hub/commit/754f102e08c52a27757051bad868aa1876c17411)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)

## [2.0.21](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.20...v2.0.21) (2026-02-18)


### Bug Fixes

* **#176:** auto-resume heating/cooling when setpoint is written while device is off ([c3a661b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c3a661ba8f96cf622916dbfd451c7a80d4a0af7f)), closes [#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)
* **#178:** correct vendor ID mappings in Network Map and Health Dashboard ([b477148](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b4771481917649c26a8f2bd2ea72c18f49d9a217)), closes [#178](https://github.com/RiDDiX/home-assistant-matter-hub/issues/178)
* revert thermostat auto-resume logic ([#176](https://github.com/RiDDiX/home-assistant-matter-hub/issues/176)) - caused mode cycling ([cf580c1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cf580c1b691ec16c1ad633126634fba85ced6f86))

## [2.0.20](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.19...v2.0.20) (2026-02-18)


### Bug Fixes

* **#105:** enable orphan detection for commissioned bridges without active sessions ([dfd2c6e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dfd2c6eb018c08cb9900bb9770992a8baf271d3b)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* **#105:** faster session recovery and bridge restart escalation for Alexa ([c4f9613](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c4f96131710ba3d4a1e4ed41d43460b397ca6a6b)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* **#105:** session stability improvements — reduce MRP traffic and clean shutdown ([085e723](https://github.com/RiDDiX/home-assistant-matter-hub/commit/085e723d8a5f430708dbfa0cbab9be49c6e69f1b)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* **#106:** resolve Roborock room names showing entity IDs instead of friendly names ([c3035a2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c3035a2e5068f02b0073955d00260a06c8408e6e))
* **#112:** add diagnostic logging for battery auto-mapping in server mode ([5126b13](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5126b13dfdd94bf0e76bedc86825b49ddd17f2ac)), closes [#112](https://github.com/RiDDiX/home-assistant-matter-hub/issues/112)
* **#117:** restore coverSwapOpenClose to force inversion (regression from b88d9a1) ([0d46309](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0d46309c9b8bd8ebdc10a65b090aa183070d144e))
* **#162:** auto-detect TV device_class for media_player on/off support ([e977a74](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e977a746bf4aa66ddf32e1fa3765c38c5faa9ab6)), closes [#162](https://github.com/RiDDiX/home-assistant-matter-hub/issues/162)
* **#166:** add unit conversion for auto-mapped pressure entities and validate pressure range ([6af3cc7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6af3cc77772b4990ea0520d07d9b74629bbee0c7)), closes [#166](https://github.com/RiDDiX/home-assistant-matter-hub/issues/166)
* **#174:** add debug logging for cover position flags ([efbd592](https://github.com/RiDDiX/home-assistant-matter-hub/commit/efbd5924bc82dbcdb8c696a083cb1180fa823d81)), closes [#174](https://github.com/RiDDiX/home-assistant-matter-hub/issues/174)
* add native Ecovacs/Deebot room cleaning support via spot_area ([#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)) ([97a890f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/97a890f8e765526b1a25f0754dc8c78aa2a2950a))
* add subscription keepalive for ALL bridged devices to prevent Offline/Updating ([38f2ed3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/38f2ed32e67c1e568b56ce8102680d92c11334e0))
* add subscription keepalive to prevent Apple Home 'Updating' for vacuums ([#103](https://github.com/RiDDiX/home-assistant-matter-hub/issues/103)) ([8b66fcd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b66fcd0b45f70cec64297439c1ea4767ec0d531))
* delete subscription persistence before start to prevent premature re-establishment ([3b55c49](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3b55c499c6425e52c3b05778dce9da8469eefa5e)), closes [CommissioningServer.#enterOnlineMode](https://github.com/CommissioningServer./issues/enterOnlineMode)
* disable AutoMode for climate devices without heat_cool (dual setpoint) ([9376165](https://github.com/RiDDiX/home-assistant-matter-hub/commit/93761655c950c3ce5193f1942f35ad25f3f2519e))
* disable subscription persistence to prevent stale re-establishment causing Updating/Offline ([#103](https://github.com/RiDDiX/home-assistant-matter-hub/issues/103)) ([8174d34](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8174d34a95d2f195bb8bf09529c16141baab2625))
* increase bridge restart delay and handle port-in-use errors ([e2225ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e2225ea490988ffe9b9929c43f108b058e7ff038))
* make subscription keepalive + health checks unconditional (not gated by autoForceSync) ([c95d694](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c95d694ec34e198899a6ee5db337ed27ef252f31))
* stop health check from sabotaging controller reconnection ([f40f010](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f40f0103ce9181f89f0fb031e4befd5a8a4a2494))
* stop sabotaging matter.js subscription recovery (the REAL offline/updating fix) ([a68d7be](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a68d7be9a91cd2ea6db486fb01401e1444ebfdec))


### Features

* **#163:** add Server Mode recommendation for vacuum bridges in Apple Home ([2722d8a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2722d8a0c205209f74a346820a47c81ae91aca3f)), closes [#163](https://github.com/RiDDiX/home-assistant-matter-hub/issues/163)
* **#165:** auto-detect Ecovacs cleaning mode support (vacuum/mop/both) ([b729565](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b7295652b67466bc468959234f497b3c7144e085)), closes [#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)
* add diagnostic export API and graceful entity unavailability guards ([be00eed](https://github.com/RiDDiX/home-assistant-matter-hub/commit/be00eedf765a66a959fab7f76a6870bac729279a))
* add entity health indicators with unavailable filter in endpoint list ([bbe1ea8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bbe1ea8f03c2c43f7e73fcff10dfc8a12cf806e4))
* add session/subscription connectivity info to health dashboard ([ac948fb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ac948fbe5ac12dfdd5ad35249a407dfa4b1deb6a))
* bridge templates, live filter preview, entity diagnostics, wizard enhancement, bulk operations ([68a301c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/68a301c37dbc985e2f5e2b4001db526fe0e59ecc))

## [2.0.19](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.18...v2.0.19) (2026-02-14)


### Bug Fixes

* **#112:** add auto-battery-mapping and batteryEntity support to server mode vacuum ([a80c5b7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a80c5b79559ad761b47e48983ab04241175e9314)), closes [#112](https://github.com/RiDDiX/home-assistant-matter-hub/issues/112)
* **#164:** split label filter into EntityLabel and DeviceLabel types ([4a9f4fc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4a9f4fc742d38cc55873fe74fd5bfef00743e877)), closes [#164](https://github.com/RiDDiX/home-assistant-matter-hub/issues/164) [#164](https://github.com/RiDDiX/home-assistant-matter-hub/issues/164)
* broadcast bridge 'starting' status via WebSocket for all bridges ([#160](https://github.com/RiDDiX/home-assistant-matter-hub/issues/160)) ([cd6f594](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd6f594f4526ab53e2e8ec71597a4282cd6b9cd7))
* broadcast bridge status changes via WebSocket during startup ([#160](https://github.com/RiDDiX/home-assistant-matter-hub/issues/160)) ([064de02](https://github.com/RiDDiX/home-assistant-matter-hub/commit/064de02447e763e4728f653562afd152ed717f9c))
* detect orphaned bridge state and clear resumption records for controller reconnection ([f7cda0f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f7cda0fec2320b4f32b448ea3f0271889f68434f)), closes [#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)
* pass entityState to filter-preview for device_class support and update label docs with display name resolution ([88aea83](https://github.com/RiDDiX/home-assistant-matter-hub/commit/88aea83cb1c3571520b23d2c05c5048744d29ccf))
* prevent vacuum.send_command crash for Ecovacs/Deebot vacuums ([#165](https://github.com/RiDDiX/home-assistant-matter-hub/issues/165)) ([47adc83](https://github.com/RiDDiX/home-assistant-matter-hub/commit/47adc83d8e233f113561c8cb849cd229663c1cb0))
* reduce MRP traffic and improve session recovery for Alexa ([#105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/105)) ([76aa5f6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/76aa5f6083837183aed76e58b98b59aa7baae1d3))
* resolve version 0.0.0-dev shown in UI for manual and workflow_dispatch builds ([32e8f65](https://github.com/RiDDiX/home-assistant-matter-hub/commit/32e8f65b07ad5156ef73750e277704d19904cbd1))


### Features

* add device_class filter type for entity filtering by HA device class attribute ([395410f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/395410f00496c7a36ad99d9441d4e1cad249c8b6))
* add diagnostics dashboard with entity health indicators, battery levels, and auto-mapping info ([11fbaa2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/11fbaa2a35bbb9dee48632159b67e6c11a536fcd))
* add edit/add filters button to bridge details FiltersCard ([4de35e2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4de35e2f0a66897b3e9a5fe8e74ce3889672f384))
* add ElectricalPowerMeasurement and ElectricalEnergyMeasurement clusters for switch/plug entities with auto-mapping ([3e92cb6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3e92cb6292f1ca436abedb076f63543e10979742))
* add energy measurement clusters to light devices with auto-mapping support ([cc42d56](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cc42d5610e93ba27023af6685f83207476b06bb0))
* add event domain support with GenericSwitch device for HA event.* entities (doorbells, buttons) ([4c48365](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4c4836572f7fd8606268bc8a9166217620132855))
* add power/energy entity fields to EntityMappingDialog for manual configuration ([c218f77](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c218f771f98d00d2c4cd86e049cd4d2c7efdf579))
* expand Filter Reference page with all filter types ([7ec818b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7ec818b791d8cb0707873ffdbaf96f0bfae75da4))
* resolve label display names to slugs in filter matching ([0656494](https://github.com/RiDDiX/home-assistant-matter-hub/commit/06564944a7783b888a2cbf5f4d7f0a48420abe5e))

## [2.0.18](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.17...v2.0.18) (2026-02-12)


### Bug Fixes

* resolve version 0.0.0-dev shown in UI for manual and workflow_dispatch builds ([63fa12f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/63fa12f544a878737571fb60941ab31e0d4f4eb1))

## [2.0.17](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.16...v2.0.17) (2026-02-12)


### Bug Fixes

* **#103:** remove OnOff from bridged vacuum to fix Apple Home Updating status ([9fd7968](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9fd796808c61b8c8dfab28ac2c4795c1dba61f04))
* **#105:** use initiateForceClose for dead session cleanup instead of initiateClose ([6394bf0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6394bf0c8e2318499dce2aeecac17fa99761914a))
* **#108:** move rockSupport/windSupport to .set() defaults - fixes Behaviors have errors ([c0b547e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c0b547e82d2283cb39b25e6e633c7c79f6e96645))
* **#108:** set rockSupport/windSupport so controllers allow enabling oscillation and wind modes ([d2235e4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d2235e4ea447a3daa49bdded4a91cd608487ee1a)), closes [#108](https://github.com/RiDDiX/home-assistant-matter-hub/issues/108)
* **#112:** search full HA registry for battery/humidity entities, not filtered bridge entities ([925b29a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/925b29af791f31cc9b47a10f447d35dc17cd6a7b)), closes [#112](https://github.com/RiDDiX/home-assistant-matter-hub/issues/112)
* **#124:** ensure onOff true->false transition for momentary scene/automation reset ([3bf2c9c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3bf2c9c2533d2948f9d74a7879979e2f2867b408)), closes [#124](https://github.com/RiDDiX/home-assistant-matter-hub/issues/124)
* **#136:** fix critical super binding bug in thermostat feature variants ([1b86030](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1b860302eaad655ae32b1e7e066c57134e83573a))
* **#136:** use feature-specific thermostat bases for Alexa compatibility ([59c1fca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/59c1fcaf6cf371c7f2dc2b6fa13dca9d76ae4c9d)), closes [#136](https://github.com/RiDDiX/home-assistant-matter-hub/issues/136)
* **#137:** add debug logging to HumidityMeasurementServer for Alexa humidity diagnosis ([2db6106](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2db610635605be22d166167405e66901b6a20e75)), closes [#137](https://github.com/RiDDiX/home-assistant-matter-hub/issues/137)
* **#137:** set thermostat limits before setpoints to support negative temperatures ([dd95a97](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd95a97201b7984f63c316727567a6161565766a)), closes [#137](https://github.com/RiDDiX/home-assistant-matter-hub/issues/137)
* **#141:** limit Node.js heap to 512MB to prevent OOM kills on low-resource devices ([0544a0a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0544a0ac38795033d3f3687f9fd0a1668acf2f56)), closes [#141](https://github.com/RiDDiX/home-assistant-matter-hub/issues/141)
* **#142:** make Alexa brightness-reset workaround always active, no longer behind feature flag ([21423e9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/21423e946374f3f92ddec3bcb2c180867b31d249)), closes [#142](https://github.com/RiDDiX/home-assistant-matter-hub/issues/142)
* **#143:** map auto mode to heat/cool for single-capability thermostats ([f9bf7e2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f9bf7e2a0a6a14e1699b0c0a0679cfffaa07e94c)), closes [#143](https://github.com/RiDDiX/home-assistant-matter-hub/issues/143)
* **#144:** responsive mobile navigation with hamburger menu drawer ([f17654a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f17654adbadbd2ac56488f2fccce75a52f861a34)), closes [#144](https://github.com/RiDDiX/home-assistant-matter-hub/issues/144)
* **#144:** wrap action buttons on Bridges page for mobile screens ([e068985](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e068985bcb1d6d393d30e41aac638e1e8ed22f73)), closes [#144](https://github.com/RiDDiX/home-assistant-matter-hub/issues/144)
* **#145:** pass water heater min/max limits at endpoint level to prevent 50°C cap regression ([cd48638](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd48638ebcd4e7e1904109d7f42d29a8628e5960)), closes [#145](https://github.com/RiDDiX/home-assistant-matter-hub/issues/145)
* **#146:** fall back to setpoint when current_temperature unavailable ([bad3338](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bad333863e254bf3c6911813aa77acb32bc46bd4)), closes [#146](https://github.com/RiDDiX/home-assistant-matter-hub/issues/146)
* **#146:** re-enable AutoMode for full HVAC thermostats to fix Apple Home active display ([889010b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/889010b8291ab1399827eb56c0fbb20a156ee20b))
* **#146:** set localTemperature to null when current_temperature unavailable - fixes Apple Home display ([fe77f88](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fe77f8839d23f2fb43a11c0989fed9a459b274ae))
* **#146:** set thermostatRunningMode for Auto mode only - reactor skips Auto ([da04b2e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/da04b2e58b0ee53a5cb51caccbef0cc10d7dab74)), closes [#146](https://github.com/RiDDiX/home-assistant-matter-hub/issues/146)
* **#146:** stop manually setting thermostatRunningMode - let Matter.js reactor handle it to fix Auto mode ([0678d35](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0678d35e124f31866322bab459035eb5caa25041))
* **#148:** fix coverSwapOpenClose not affecting position display - was doing same inversion as default ([b88d9a1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b88d9a1178548b3a18c72305bf56a757f99f6d5b))
* **#154:** map running/plug/power binary sensors to OnOffSensor instead of ContactSensor ([e3ca4ba](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e3ca4babc5f0ee3afa53f8bd81e524d77a307172)), closes [#154](https://github.com/RiDDiX/home-assistant-matter-hub/issues/154)
* **#52:** per-property error handling in applyPatchState, fix thermostatRunningState ([0491822](https://github.com/RiDDiX/home-assistant-matter-hub/commit/049182244ec17d1435da161ecd5a5b310e82e481))
* **#52:** revert thermostatRunningState to systemMode-based logic for correct mode coloring ([d96ffd7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d96ffd7aff50b7766c86628327dc7d0d7ddf2c94)), closes [#52](https://github.com/RiDDiX/home-assistant-matter-hub/issues/52)
* **#52:** set thermostatRunningMode and controlSequenceOfOperation from HA entity ([cd18e1c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd18e1cc4918c3d578ec3f08401a15f294de4e04)), closes [#52](https://github.com/RiDDiX/home-assistant-matter-hub/issues/52)
* **#52:** use HA min/max limits for all thermostat modes, fix local temperature fallback ([ec865a4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ec865a4601a329cde781b38b8f5984e7b03da3c5))
* add OperationCompletion event, GoHome command, remove OnOff from server-mode RVC ([121c62e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/121c62e422388df016a7e0c29d9f6bbb46e01e5b)), closes [#103](https://github.com/RiDDiX/home-assistant-matter-hub/issues/103)
* add state deduplication and debouncing to ServerModeVacuumEndpoint ([f51b19a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f51b19ad6f0cdf3b3238207cde8f423fe2dabbeb))
* add User feature to DoorLock for Apple Home compatibility ([df6b860](https://github.com/RiDDiX/home-assistant-matter-hub/commit/df6b860ffe388b6ee5cf56b0aec5005bdcc58052))
* consistent property ordering in endpoint .set() for negative temperature support ([307945e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/307945e807a51f0565d22719e0cc5c74122b52a5))
* detect and close dead sessions to recover from Alexa subscription loss ([684e6e0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/684e6e0da2fd53529327c1b2f66be7dd0c24d17f))
* dreame vacuum multi-floor room ID collision causing auto-grouping in Apple Home ([0e43473](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0e43473469f846a0e6fb8f49e0ffd004013bfd57))
* improve behavior error logging to extract AggregateError details per behavior ([d972762](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d972762ed61c619a020a2bd8c666db3bceeda6f6))
* improve crash resilience across bridge lifecycle ([6f0daad](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6f0daad553ec218c97731928cfded06c7303feac))
* initialize thermostatRunningState in defaults so controllers subscribe from start ([746cc4e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/746cc4ebd140e39eb533f12ccd08af889d2d02c7))
* label filter now also matches device-level labels ([dc92455](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dc92455701fb694bab7759508084a4faaa9947e6))
* remove AutoMode feature to fix Apple Home active heating/cooling display ([ef0c1c9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ef0c1c9ad3550a603d34368c96272a4d60630286)), closes [#3105](https://github.com/RiDDiX/home-assistant-matter-hub/issues/3105)
* remove stale minSetpointDeadBand and add NaN guards for thermostat initialization ([9bc9859](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9bc9859b50168b9870809e7c7e7f999a289a3609))
* remove unverified device limit warnings from bridge UI ([725b41d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/725b41d15b733ef4fe65b7531623c89f10400fa9))
* replace confusing API endpoint hint with clear label_id instructions ([182eb80](https://github.com/RiDDiX/home-assistant-matter-hub/commit/182eb8070a2d33f64b060c24122950a736905845))
* **sensor:** don't skip humidity entities auto-assigned to temperature sensors ([#133](https://github.com/RiDDiX/home-assistant-matter-hub/issues/133)) ([e76b253](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e76b253e3028f66a946ae6078e47ba76d51277fe))
* **speaker:** prevent base LevelControlServer from overwriting volume ([#79](https://github.com/RiDDiX/home-assistant-matter-hub/issues/79)) ([32f67ab](https://github.com/RiDDiX/home-assistant-matter-hub/commit/32f67ab9dbd7b8c615da838fb3292b8d4f5626a0))
* truncate FixedLabel area name to 16 chars and add detailed behavior error logging ([cc09c4b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cc09c4b2df7b727c848235cd277aced893534e23))
* **ui:** match Startup Order icons to Bridge page style and reduce card padding ([7c840e0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7c840e0f48fa6950fd462e5ab5d437cb2a34e538))
* **ui:** network map dark mode for bridge/failed nodes, status chip readability, position persistence with undo/reset ([12ee128](https://github.com/RiDDiX/home-assistant-matter-hub/commit/12ee1284f50164b115eaf262e274ab26a4d65c90))
* **ui:** network map grid layout for many devices and dark mode support for controls/minimap ([f4d1b1e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f4d1b1e907d42372c2649210a97eed30bf25e6e6))
* use hvac_action for thermostatRunningState to show active heating/cooling in Apple Home ([771cabd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/771cabd4fd8c1b3f5205902d357c6ba60a9494a9))
* use MutableEndpoint.with() API for FixedLabel instead of manual spreading ([55afbd2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/55afbd207960438c9bdec2a5b8db6efca4ca0dab))
* use unlatch action for unlockDoor on locks with Unbolting feature ([18912f2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/18912f22dfb713931bd302f849dcd345092071b5))


### Features

* add auto pressure mapping for combined temperature+pressure sensors ([35f2ab1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/35f2ab19f03f28005e034dadd3d8990f3b7966dc))
* add community tip about device limits to bridge config editor ([48d048a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/48d048ae8ee7334e7dcafa8b491a70c729c66cbb))
* add Labels & Areas reference page to frontend UI ([6fae7af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6fae7af9d0484e03189ed950ec96857d2046f699))
* add lock unlatch/unbolt support for locks with OPEN feature ([b924c11](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b924c11b57b223ec8f4577fc6a7d4362223682cc))
* automatic room assignment via HA areas using FixedLabel cluster ([#77](https://github.com/RiDDiX/home-assistant-matter-hub/issues/77)) ([bfb11c7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bfb11c7cc792d490cedd8437cd84d6d31c039548))
* enhanced device state display in EndpointCard with sensor values, light color/brightness, lock state, and more ([1c0f47f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1c0f47f3d2aaf377e7df44cdb0df269f91da0d08))
* expose HA temperature unit via ThermostatUserInterfaceConfiguration cluster ([8718708](https://github.com/RiDDiX/home-assistant-matter-hub/commit/871870864b59dbb339f6cda3791bc44ce1e70701))
* **frontend:** add Network Map page with React Flow visualization ([78927ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/78927ead936223041094bdfce0b295350329d59a))
* **sensor:** add tvoc_sensor to entity mapping options ([#134](https://github.com/RiDDiX/home-assistant-matter-hub/issues/134)) ([c142ac3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c142ac34bac0eaf7a873e33424021e0282183692))
* **ui:** add configurable page size selector to All Devices page ([266a038](https://github.com/RiDDiX/home-assistant-matter-hub/commit/266a038f6865d4432605b3ababef798aee9d081b))
