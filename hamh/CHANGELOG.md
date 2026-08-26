## [2.0.56](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.55...v2.0.56) (2026-08-26)


### Bug Fixes

* **#450:** keep late endpoint flushes and test teardown off the update chain ([ef7b5cd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ef7b5cde3e3bdd4f2385f6c9fe050132f9dfd677)), closes [#450](https://github.com/RiDDiX/home-assistant-matter-hub/issues/450)
* **#450:** retry battery auto-mapping and report honest charge state ([a15466e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a15466e5d116145baa02470e0d6b0577f1addc4e)), closes [#450](https://github.com/RiDDiX/home-assistant-matter-hub/issues/450)
* **#452:** advertise the full mandatory color feature set ([9182a71](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9182a71dbcf0b81975d19c61dce0b4bef6626f8c)), closes [#452](https://github.com/RiDDiX/home-assistant-matter-hub/issues/452)
* cover type and end product stay consistent with the feature map ([b75b7bc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b75b7bc12a257a62fca75ba67cb6ce82e50bc2e2)), closes [#304](https://github.com/RiDDiX/home-assistant-matter-hub/issues/304)
* preserve explicit actions during debounce ([f66b771](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f66b771c5e921e3a0f7d01e67f12d84683fee63e))


### Features

* **#449:** flag to accept the terms and conditions commissioning commands ([56db6af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/56db6afdcc9253e44d53ed636b74953f19a6b18c)), closes [#449](https://github.com/RiDDiX/home-assistant-matter-hub/issues/449)
* **#449:** flag to enable matter over tcp ([6c636a6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6c636a6eb3a129c34ceaed96bb859de797002809)), closes [#449](https://github.com/RiDDiX/home-assistant-matter-hub/issues/449)
* **#449:** flag to mask the Matter version identifiers as 1.5.1 ([035afc0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/035afc07c5649a4e3423c27dca56bb90c51ee167)), closes [#449](https://github.com/RiDDiX/home-assistant-matter-hub/issues/449)
* **i18n:** add Korean (ko) translation ([12c0bcd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/12c0bcde8432254537a5abfaff432669bcd49fc3))
* pm2.5, pm10 and co2 sensor overrides ([31d89c2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/31d89c29304ed1f11e9476cf0f3570c4eb588609))

## [2.0.55](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.54...v2.0.55) (2026-08-13)


### Bug Fixes

* **#155:** plugin devices mount with bridged basic information ([b25e422](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b25e4223293a5026e2271801fe4f5f2e973c6bd8)), closes [#155](https://github.com/RiDDiX/home-assistant-matter-hub/issues/155)
* **#438:** a disabled device keeps its Matter number to itself ([ae599d1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ae599d1b50ddd0fe0f7a419afb8c9be8ac5e4948)), closes [#438](https://github.com/RiDDiX/home-assistant-matter-hub/issues/438)
* **#438:** devices keep their Matter numbers across HA restarts ([031655e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/031655e6fc5c0b7d3c8cb582d90b09eb23be28f1)), closes [#438](https://github.com/RiDDiX/home-assistant-matter-hub/issues/438)
* **#438:** keep devices when HA briefly reports no entities ([fff546e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fff546e7bb3ff2ec85bce072cbc36cf7ecc4f8b9)), closes [#438](https://github.com/RiDDiX/home-assistant-matter-hub/issues/438)
* **#441:** power on reaches the climate when the cache lags ([4a2a3b1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4a2a3b191551db892daa9d271d3fc7300e07c006)), closes [#441](https://github.com/RiDDiX/home-assistant-matter-hub/issues/441)
* **#442:** fan speed zero clamps to the slowest real mode ([0313e6e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0313e6ec5c19f2f57feb24b3669eb40014dc60c0)), closes [#442](https://github.com/RiDDiX/home-assistant-matter-hub/issues/442)
* **#445:** plugin endpoints no longer stall or vanish from entity updates ([a03a7a9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a03a7a9d818e5ec70728836b3cd66bcedeee2d76)), closes [#445](https://github.com/RiDDiX/home-assistant-matter-hub/issues/445)
* **#446:** a command that cannot reach Home Assistant fails instead of lying ([ed67bf4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ed67bf4145be67ec3fd1c5264fd7942d0c831505)), closes [#446](https://github.com/RiDDiX/home-assistant-matter-hub/issues/446)
* **#447:** identify presses the identify button of the device ([2d6be4c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2d6be4c965398d7a0ff4b80d45950dd3406411ac)), closes [#447](https://github.com/RiDDiX/home-assistant-matter-hub/issues/447)
* stop closing a controller session while it is still priming ([4a7faa1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4a7faa1e01260b81924bb58dd92c50e7470717ff))


### Features

* **#443:** fan slider debounce, and number flags render as numbers ([ff5ae1d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ff5ae1d509bea13f34cc87e1dbf724e420a964e0)), closes [#443](https://github.com/RiDDiX/home-assistant-matter-hub/issues/443)

## [2.0.54](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.53...v2.0.54) (2026-08-09)


### Bug Fixes

* **#439:** plugin disable sticks and unconfigured plugins expose nothing ([5ad6d28](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ad6d289d8740e699cbb2211d5cfc63e6f2e590d)), closes [#439](https://github.com/RiDDiX/home-assistant-matter-hub/issues/439)
* camera cleanup scoped per bridge, plugin state rides backups ([e7d0b61](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e7d0b61db032b2904e6929b5811062dc5267e7ef))

## [2.0.53](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.52...v2.0.53) (2026-08-09)


### Bug Fixes

* **#423:** surface rejected invokes and endpoint removals in the log ([809728d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/809728ddb2648a95486f133d766c605c43c143d7)), closes [#423](https://github.com/RiDDiX/home-assistant-matter-hub/issues/423)
* **#429:** close the remaining stuck-moving paths and log resolved cover flags ([f737de1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f737de172dea252436d9074dbce46c8b35d62dfb))
* **#431:** scope power measurements to the endpoint, not the whole node ([1d7a851](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1d7a85162e51557f5770c322897fce258ca6a27d)), closes [#431](https://github.com/RiDDiX/home-assistant-matter-hub/issues/431)
* **#432:** plugin config survives restarts and tokens stay out of the api ([19e0428](https://github.com/RiDDiX/home-assistant-matter-hub/commit/19e042801562a2e4731ece0313b44d0fb754250c)), closes [#432](https://github.com/RiDDiX/home-assistant-matter-hub/issues/432)
* **#432:** plugins page explains server mode instead of hinting at installs ([9c619b4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9c619b44e5b29e262f3de92a0f6da7b27b853f36)), closes [#432](https://github.com/RiDDiX/home-assistant-matter-hub/issues/432)
* **#432:** reject built-in plugin names on every install path ([5c7ba4b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5c7ba4bdfc437b2d391d71d4080b0154da2c8f36)), closes [#432](https://github.com/RiDDiX/home-assistant-matter-hub/issues/432)
* **#433:** clear the stale sendPinOverTheAir a 2.0.16 store still carries ([58fc150](https://github.com/RiDDiX/home-assistant-matter-hub/commit/58fc150ee82b213a1ee5e9a293c97dd1e4fc465b)), closes [#433](https://github.com/RiDDiX/home-assistant-matter-hub/issues/433)
* **#434:** store the level google sends after a room off instead of relighting ([43b4432](https://github.com/RiDDiX/home-assistant-matter-hub/commit/43b4432d71ff17365fa89531f187a54ace12308d)), closes [#434](https://github.com/RiDDiX/home-assistant-matter-hub/issues/434)
* **#435:** always zero the thermostat deadband on auto mode ([8aa4089](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8aa408997b68e6323eab354e37f2ab5ef5e78bbd)), closes [#435](https://github.com/RiDDiX/home-assistant-matter-hub/issues/435)
* **#435:** contain aggregator construction failures instead of exiting ([785c19a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/785c19a467cfe99aafbd1350d48c64383da9aec8)), closes [#435](https://github.com/RiDDiX/home-assistant-matter-hub/issues/435)
* **#435:** ignore the parked range when deriving single-mode setpoints ([fd771ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fd771ca3ed428667f86655a2218324319d4ffc65)), closes [#435](https://github.com/RiDDiX/home-assistant-matter-hub/issues/435)
* boost survives echoes, restarts and rejected retries ([3e6600b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3e6600b0392556453cb7be20ccffe1cdb571765a))
* **fan:** advertise only the fan modes the HA entity actually has ([b609b86](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b609b861eec0d9b1f990dd101844f4276d9abdd0))
* one auto predicate for every fan feature gate ([28015e3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/28015e30b808dedc7eb81baa45c310f68fc9427b))
* plugin devices actually receive controller writes ([0e481e9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0e481e9828549ea53735c9509604060a2bd47beb))
* vacuum keeps its auto-resolved rooms after state updates ([b06bce9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b06bce93066aca155410d97188ee4ce86ae52261))


### Features

* **#355:** per-area switches routines can flip ([6203d72](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6203d724db67a271860484787cbef06fd771eb24)), closes [#355](https://github.com/RiDDiX/home-assistant-matter-hub/issues/355)
* **#365:** shadow rule spots the wedge cycle the watchdog misses ([3f388d4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3f388d4d2ba67d8afc758f2c7c3a50238fb56fdd)), closes [#365](https://github.com/RiDDiX/home-assistant-matter-hub/issues/365)
* **#368:** opt-in ascending room order for batch vacuums ([6a2d536](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6a2d536572bd8a5d72a93d8ad8539cd4ad0cbcea)), closes [#368](https://github.com/RiDDiX/home-assistant-matter-hub/issues/368)
* **#432:** plugin settings dialog on the plugins page ([d1015cc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d1015cc784b34d1a781cb99da65419d4f9b960c7)), closes [#432](https://github.com/RiDDiX/home-assistant-matter-hub/issues/432)
* doorbell and electrical utility meter overrides ([9556c5e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9556c5ef41c23ae9a5c1f2ed70a4c40f29a47b2e))
* security plugin arms the house from any controller ([583cf16](https://github.com/RiDDiX/home-assistant-matter-hub/commit/583cf1647aa931addf85c47bde195b897f536abb))
* **water-heater:** add the Matter 1.4 WaterHeaterManagement device type ([58c810d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/58c810ddefe14159a8c954b6ded0ad5b1ce3eb79))

## [2.0.52](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.51...v2.0.52) (2026-07-31)


### Bug Fixes

* **#430:** plugins page tolerates server mode bridges ([eecb71d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/eecb71d9ef22abc733f1eed04aff69fb1bc94524)), closes [#430](https://github.com/RiDDiX/home-assistant-matter-hub/issues/430)

## [2.0.51](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.50...v2.0.51) (2026-07-31)


### Bug Fixes

* **#428:** vacuum onoff derives from the entity, not the sibling run mode class ([9e2bb53](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9e2bb531d5d95c0e62c7579ee52df2fad0cfa5b8)), closes [#428](https://github.com/RiDDiX/home-assistant-matter-hub/issues/428)
* **#429:** cover completion works in every position space ([2fb033f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2fb033f4597931278a49a7896e4f61c70fdb203e)), closes [#429](https://github.com/RiDDiX/home-assistant-matter-hub/issues/429)
* camera webrtc path logs, signaling hardening and media fixes ([a99eb3c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a99eb3c2cac5823d6d1d1d4e190e69aabe791d50))
* ship @matter/protocol with the app package ([595baf1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/595baf11020d6da35d406f9a27e5ea8fc9062fc1))


### Features

* **#287:** opt-in watchdog rotates sessions gone silent at the interaction layer ([931d3a4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/931d3a4255581aea60ccde2d103946d409eaba65)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* camera live view delivers the webrtc answer over the requestor cluster ([aef509e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/aef509e81d0fdfcf5ae1a4e70b7965cb03964a06))
* ev charger support on the energy evse device type ([1164da6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1164da6ec6091a55e246eed798507726cb09e7bc))
* manual cleanup of orphaned identity and mapping records ([a33e863](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a33e8637d0409e36357ee7b96bf625bf43357631))
* subscription scope per fabric on the health card ([40ed41a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/40ed41af24002ee629c07aa2b77860b5b684e31f))

## [2.0.50](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.49...v2.0.50) (2026-07-29)


### Bug Fixes

* **#408:** composed devices carry the device battery and room label ([4d39b22](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4d39b221bf02200a5def689046d68ef5f7771137)), closes [#408](https://github.com/RiDDiX/home-assistant-matter-hub/issues/408)
* **#408:** show composed device battery in the web ui ([c9b171b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c9b171bca6ca28654808917f7d4a803a7edc5ba9)), closes [#408](https://github.com/RiDDiX/home-assistant-matter-hub/issues/408)
* **#411:** discrete cover commands cancel the pending slider action ([eb56997](https://github.com/RiDDiX/home-assistant-matter-hub/commit/eb5699743cd73b76b343ffdc4b5d9b20debb2a8d)), closes [#411](https://github.com/RiDDiX/home-assistant-matter-hub/issues/411)
* **#411:** share cover debounce across matter transactions ([1348e36](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1348e36ce7ab9949206866341167e48d71060e04)), closes [#411](https://github.com/RiDDiX/home-assistant-matter-hub/issues/411)
* **#412:** step base accumulates and rapid color undo works ([7ad113a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7ad113a091f3764be59cbb1c188c23d6a76e7704)), closes [#412](https://github.com/RiDDiX/home-assistant-matter-hub/issues/412)
* **#415:** refresh mdns records when interface addresses change ([83e40a9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/83e40a9f94274f524a5f8952e5181443245440b7)), closes [#415](https://github.com/RiDDiX/home-assistant-matter-hub/issues/415)
* **#417:** diagnostics reflect the mdns ipv4 setting ([a7922e7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a7922e76f84d9aa746b8c2e16d154f015c1bc0ff)), closes [#417](https://github.com/RiDDiX/home-assistant-matter-hub/issues/417)
* **#419:** camera endpoints set the mandatory av stream attributes ([f3477ee](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f3477ee9ccecd444fc7b0eef5a20592a8755d1ab)), closes [#419](https://github.com/RiDDiX/home-assistant-matter-hub/issues/419)
* **#423:** session max age reloads into the edit form ([d2e7c55](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d2e7c5575a47bd8608b95c1c41e8b9e17a4c4daa)), closes [#423](https://github.com/RiDDiX/home-assistant-matter-hub/issues/423)
* **#426:** composed sensors read sub-entities past the bridge filter ([291921a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/291921a311e127b41661fe01d8ec8bfab2bf3fca)), closes [#426](https://github.com/RiDDiX/home-assistant-matter-hub/issues/426) [#408](https://github.com/RiDDiX/home-assistant-matter-hub/issues/408)
* **#428:** server mode shares the dead session timeout and session diagnostics ([2f07259](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2f07259ab02167683c6802501c35f296eda438c9)), closes [#428](https://github.com/RiDDiX/home-assistant-matter-hub/issues/428)
* **#429:** emit the moving-to-stopped edge for covers without transitional states ([2fefd46](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2fefd4611c260a470ca3a35b5bfcb25998a7854b)), closes [#429](https://github.com/RiDDiX/home-assistant-matter-hub/issues/429)
* **#65:** valve and cover overrides route onoff to their services ([3d336ae](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3d336ae4559fb821648bea6ed64bd17b638c2218)), closes [#65](https://github.com/RiDDiX/home-assistant-matter-hub/issues/65)
* get_states shares the registry query timeout ([3cbc207](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3cbc2074fb2c0a84725502864ed16864553da999)), closes [#422](https://github.com/RiDDiX/home-assistant-matter-hub/issues/422)


### Features

* **#404:** stable device identity keyed on the ha unique id ([d382bfd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d382bfd61c631573e9155fc2eb7a074b7f38a184)), closes [#404](https://github.com/RiDDiX/home-assistant-matter-hub/issues/404)
* **#408:** smoke alarms report battery, fault and expressed state ([84ec994](https://github.com/RiDDiX/home-assistant-matter-hub/commit/84ec9944d45bf36991a6bb6c6ec044ada29dc257)), closes [#408](https://github.com/RiDDiX/home-assistant-matter-hub/issues/408)
* **#418:** opt-in passthrough programs the physical lock usercode ([961cd3c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/961cd3cf3b922f2bda87a75a1145d53caf98d81d)), closes [#418](https://github.com/RiDDiX/home-assistant-matter-hub/issues/418)
* **#418:** per-lock pin length overrides ([7f62df3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7f62df3146d3dfbebb99b330351104e113402e77)), closes [#418](https://github.com/RiDDiX/home-assistant-matter-hub/issues/418)
* **#419:** enable matter-over-tcp on bridges with cameras ([30ba6ff](https://github.com/RiDDiX/home-assistant-matter-hub/commit/30ba6ff99c8e3e9111455574a41e4f02ef344468)), closes [#419](https://github.com/RiDDiX/home-assistant-matter-hub/issues/419)
* **#423:** opt-in to suppress the momentary on/off flip ([ca9251e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ca9251e1b8a878c0052868b03420a7011024471b)), closes [#423](https://github.com/RiDDiX/home-assistant-matter-hub/issues/423)
* **#427:** per-entity switch to disable battery mapping ([5846df6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5846df634ee3e3d0e41554fcb4dd00d1ca47ea98)), closes [#427](https://github.com/RiDDiX/home-assistant-matter-hub/issues/427)
* commissioning preflight and label guard in the wizard ([2a3046c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2a3046cb78c110e3244b49a793e67f5a9b87fffb))
* energy stage 1, electrical meter, home battery and grouped measurements ([7fc8806](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7fc88061b7cc12058ff619e120ccc62e80cc036d))
* light level and color temperature step control ([#412](https://github.com/RiDDiX/home-assistant-matter-hub/issues/412)) ([cbf99d9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cbf99d91b5da62213f821b828f92298192261515))
* mdns option to disable ipv4 ([#417](https://github.com/RiDDiX/home-assistant-matter-hub/issues/417)) ([de6025b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/de6025b084ab870e02eba8de5a3baacfa02747c6))

## [2.0.49](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.48...v2.0.49) (2026-07-11)


### Bug Fixes

* **#182:** drop Lighting on button ([9b5c328](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9b5c3285b9d834545aafd9e64e8c31daad0b2035)), closes [#182](https://github.com/RiDDiX/home-assistant-matter-hub/issues/182)
* **#214:** composed sensors list all device types ([c90b786](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c90b78689310a3307a25b80fc880b56fde26b8ad)), closes [#214](https://github.com/RiDDiX/home-assistant-matter-hub/issues/214)
* **#287:** drop keepalive for closed own session ([4bfeaaa](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4bfeaaa3fc448135ba7a961d638fe66af2104524))
* **#287:** keep active 0-sub sessions for recovery ([6798099](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6798099426f45442bc325522b36a92b558a7df61)), closes [#287](https://github.com/RiDDiX/home-assistant-matter-hub/issues/287)
* **#350:** cover-as-light tilt-only covers use tilt ([5399ca9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5399ca93192bbe562c48bfde57ff1abe14726371)), closes [#350](https://github.com/RiDDiX/home-assistant-matter-hub/issues/350)
* **#373:** camera reuses bridge HA connection ([2f55498](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2f55498f9ffbbdeedcf9671a47cdcf067e5ecb54)), closes [#373](https://github.com/RiDDiX/home-assistant-matter-hub/issues/373)
* **#373:** scope plugin config per bridge and clarify camera setup ([e9f3a23](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e9f3a23373137bdaf70d306b5b3874721467a3ed)), closes [#373](https://github.com/RiDDiX/home-assistant-matter-hub/issues/373)
* **#378:** reassign clashing bridge port on load ([6722932](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6722932ae5c27c7c9f2c5302283146b15cd8141f)), closes [#378](https://github.com/RiDDiX/home-assistant-matter-hub/issues/378)
* **#380:** make mounted on/off control spec conformant ([d136790](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d136790d95986640c285515ff29ec40bac0902c5)), closes [#380](https://github.com/RiDDiX/home-assistant-matter-hub/issues/380)
* **#384:** clear stale cooling and auto state ([9b27774](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9b277744d47999921c9a8ad65970b7278164a90d)), closes [#384](https://github.com/RiDDiX/home-assistant-matter-hub/issues/384)
* **#385:** neutralize basic info domain leak ([4475538](https://github.com/RiDDiX/home-assistant-matter-hub/commit/447553883855482a201c693c875267e48ffb1ee2)), closes [#385](https://github.com/RiDDiX/home-assistant-matter-hub/issues/385)
* **#386:** drop subscription jitter for Google ([8285f98](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8285f98305007f0c4c49d243157ee874aaae24ed)), closes [#386](https://github.com/RiDDiX/home-assistant-matter-hub/issues/386)
* **#386:** drop subscription jitter for server mode too ([d659605](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d659605d06f818319504dc7afdeba3b0e822ec7f)), closes [#386](https://github.com/RiDDiX/home-assistant-matter-hub/issues/386)
* **#387:** gate fan Auto on a real auto preset ([2042e7f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2042e7f429d6dba191372099193ffaac92a77c7b)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** only treat 100% as the power-on default ([0b7eb29](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0b7eb290317ced7fc2bedabd522e61e3b79b19f3)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** remember fan speed across transactions and restarts ([a9d6bb0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a9d6bb0a41838c4b8f926ccb6827375d6da28e34)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** remember speed from controller writes too ([e4dfc6d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e4dfc6d0199c114c5ddde3693dbdc576684f50f9)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** restore speed patches matter state ([002cb2a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/002cb2a034e0fdec5766114cf12a535330ec8331)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** restore survives onOff race ([2f842c3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2f842c3211cdc26086eee208259c988e98fbe171)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#397:** unbolt maps to lock.unlock not open ([f10dc6b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f10dc6b7c9f449002ec609efc41f5b2a4de89e8d)), closes [#397](https://github.com/RiDDiX/home-assistant-matter-hub/issues/397)
* **#398:** close stale sessions only after real quiet period ([8d4b25f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8d4b25f3773035ad813603224fbd97fcec55760f))
* **#400:** sweep superseded sessions of a reconnecting peer ([0c762ae](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0c762ae553551c700c61b588db02f2f2a7ea934f)), closes [#400](https://github.com/RiDDiX/home-assistant-matter-hub/issues/400)
* **#402:** level to brightness conversion uses one scale ([49afc7e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/49afc7ed3b13c967c526d2b311fe0abeed98f07a)), closes [#402](https://github.com/RiDDiX/home-assistant-matter-hub/issues/402)
* **#404:** keep endpoint number on mapping change to avoid alexa re-add ([09a2cd3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/09a2cd391cba5c330779ac2bed6180c92a576b46)), closes [#404](https://github.com/RiDDiX/home-assistant-matter-hub/issues/404)
* **#405:** expose tilt for covers reporting only set_tilt_position ([11fc402](https://github.com/RiDDiX/home-assistant-matter-hub/commit/11fc402b9d36705b08b848d6eeb39c11c8695ae0)), closes [#405](https://github.com/RiDDiX/home-assistant-matter-hub/issues/405)
* **#408:** compose sub-entities outside the bridge filter ([83c9427](https://github.com/RiDDiX/home-assistant-matter-hub/commit/83c94276c69bd17b89290e24d9379e0a5728ea96)), closes [#408](https://github.com/RiDDiX/home-assistant-matter-hub/issues/408)
* fabric stale threshold to 2 keepalive cycles ([9bd6b49](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9bd6b49794f500cc09dad1f988a4c68bc0ae8cdf))
* server mode session info reports fabric ([0c2f801](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0c2f8012321870b1c07ba0287b64a6fd11eca7ed))


### Features

* **#356:** expose select as on/off switch option ([9ac1359](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9ac1359baac6cb3bddf93d5fbdd8d818bdda4632)), closes [#356](https://github.com/RiDDiX/home-assistant-matter-hub/issues/356)
* **#380:** experimental mounted on/off control type ([1908d20](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1908d208464ea7bd142a24ae4688bc7f0edee17f)), closes [#380](https://github.com/RiDDiX/home-assistant-matter-hub/issues/380)
* **#385:** unique id suffix to shed stale controller records ([064354b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/064354bd9727bbd19b330323190a29a14090c659))
* **#386:** opt-in fast session recovery ([8d50a29](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8d50a2955a6eaef546b540591e7233da15408628)), closes [#386](https://github.com/RiDDiX/home-assistant-matter-hub/issues/386)
* **#387:** log fan power-on restore decision ([529f603](https://github.com/RiDDiX/home-assistant-matter-hub/commit/529f603001fe9feaf2a630b1dbb032cdcc0cadd7)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** map localized fan wind presets ([8b7ae5d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8b7ae5d61af5087335317f10734970c9e5af3b5d)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#387:** opt-in restore fan speed on power-on ([1fae3ba](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1fae3baa866c79ee93684793813c34b6f36276b7)), closes [#387](https://github.com/RiDDiX/home-assistant-matter-hub/issues/387)
* **#388:** warn on otbr thread mdns interface ([3581aa9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3581aa95036ac76be7dbdc7be8ff8bb17c61617b)), closes [#388](https://github.com/RiDDiX/home-assistant-matter-hub/issues/388)
* **#401:** warn when alexa pairs a non-5540 bridge ([7453423](https://github.com/RiDDiX/home-assistant-matter-hub/commit/74534233896a891806cee2d2504059453baed097)), closes [#401](https://github.com/RiDDiX/home-assistant-matter-hub/issues/401)
* per-fabric controller health card ([6e3e43b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6e3e43b3d5a41b1684d2224f0dce95f0cb2a9ad6))

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
