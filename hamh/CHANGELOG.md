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
