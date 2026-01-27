# [2.0.0-alpha.23](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.22...v2.0.0-alpha.23) (2026-01-27)


### Bug Fixes

* clamp thermostat setpoints to valid limits to prevent Matter.js validation errors ([2d190b5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2d190b59d2adcf0e166a3a4ca5f296010642e78c))

# [2.0.0-alpha.22](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.21...v2.0.0-alpha.22) (2026-01-27)


### Features

* add comprehensive REST API with Home Assistant, Logs, and Metrics endpoints ([128a070](https://github.com/RiDDiX/home-assistant-matter-hub/commit/128a070f5627f59918d72169a2059b74c1620d19))

# [2.0.0-alpha.21](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.20...v2.0.0-alpha.21) (2026-01-27)


### Bug Fixes

* set initial RVC state before super.initialize() to satisfy Matter.js validation ([23dcd5e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/23dcd5e71b170ca385d3ef92eb4349e2cd2d7f03))

# [2.0.0-alpha.20](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.19...v2.0.0-alpha.20) (2026-01-27)


### Bug Fixes

* revert thermostat deadband changes - Matter.js enforces constraint on limits ([313e5d6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/313e5d62d3eb11b3401dbe7c7f09ba8a7ec9939c))

# [2.0.0-alpha.19](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.18...v2.0.0-alpha.19) (2026-01-27)


### Bug Fixes

* remove deadband offset from thermostat setpoint limits ([c2a5290](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c2a5290096b4ecfff9d810e896eed6ede298f329))

# [2.0.0-alpha.18](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.17...v2.0.0-alpha.18) (2026-01-27)


### Bug Fixes

* trigger release for Bun import stub fix ([66818ab](https://github.com/RiDDiX/home-assistant-matter-hub/commit/66818abd16018ca8ba417ff84527e748c5617499))

# [2.0.0-alpha.17](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.16...v2.0.0-alpha.17) (2026-01-27)


### Bug Fixes

* bundle Matter.js packages to include access control patch ([2791246](https://github.com/RiDDiX/home-assistant-matter-hub/commit/27912467396382c906b4c3fa5235ad5f9f8eceb4))
* patch Matter.js FabricAccessControl to grant Operate access when cluster undefined ([ca490e2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ca490e29a3d1c49c52af5b44f67931cb2746c6a6))
* stub Bun imports to prevent runtime errors in Node.js ([53db982](https://github.com/RiDDiX/home-assistant-matter-hub/commit/53db982d840b2ff5ca31098f858b99353ec126b2))

# [2.0.0-alpha.16](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.15...v2.0.0-alpha.16) (2026-01-27)


### Bug Fixes

* FanControl step command not calling Home Assistant ([91acf08](https://github.com/RiDDiX/home-assistant-matter-hub/commit/91acf089c0b57e1380fb4ec58faf305879021670))

# [2.0.0-alpha.15](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.14...v2.0.0-alpha.15) (2026-01-26)


### Bug Fixes

* move super.initialize() to beginning in rvc behavior servers ([1fb48f8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1fb48f80904442832f4a00beed8d8a7d316c8795))

# [2.0.0-alpha.14](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.13...v2.0.0-alpha.14) (2026-01-26)


### Bug Fixes

* add missing await to super.initialize() in behavior servers ([#8](https://github.com/RiDDiX/home-assistant-matter-hub/issues/8)) ([803dd35](https://github.com/RiDDiX/home-assistant-matter-hub/commit/803dd3517ba86075c190be2c15a63182b3e72607))

# [2.0.0-alpha.13](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.12...v2.0.0-alpha.13) (2026-01-26)


### Bug Fixes

* round fan percentage to nearest valid step ([#8](https://github.com/RiDDiX/home-assistant-matter-hub/issues/8)) ([292cc91](https://github.com/RiDDiX/home-assistant-matter-hub/commit/292cc91830ee6130f8bad9e2b4855e281d60a67b))

# [2.0.0-alpha.12](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.11...v2.0.0-alpha.12) (2026-01-26)


### Bug Fixes

* separate Smoke and CO alarm types to prevent duplicate sensors ([#7](https://github.com/RiDDiX/home-assistant-matter-hub/issues/7)) ([53e7d03](https://github.com/RiDDiX/home-assistant-matter-hub/commit/53e7d031630701e730fe45717309e77b6f0607c1))

# [2.0.0-alpha.11](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.10...v2.0.0-alpha.11) (2026-01-26)


### Features

* add Add Controller button for multi-fabric re-pairing ([a9a6829](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a9a68293ed86ef022434b5c663bc5aa430901a21))

# [2.0.0-alpha.10](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.9...v2.0.0-alpha.10) (2026-01-26)


### Features

* add Backup/Restore section to Health page ([b4ea8d5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b4ea8d57a4d9fc33031da792c2a15e908c58c2e6))

# [2.0.0-alpha.9](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.8...v2.0.0-alpha.9) (2026-01-26)


### Bug Fixes

* return minimum level instead of null for humidifier controller compatibility ([dfb36a7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dfb36a72afdea48e5c89b8d6781fefbe09d7b553))

# [2.0.0-alpha.8](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.7...v2.0.0-alpha.8) (2026-01-26)


### Bug Fixes

* return minimum level instead of null for Apple Home compatibility ([c3cb384](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c3cb384ba0028d8eb28cea82d41222098c9a47df))

# [2.0.0-alpha.7](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.6...v2.0.0-alpha.7) (2026-01-26)


### Bug Fixes

* move multer to runtime dependencies ([01e46a1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/01e46a1d784621576a9937c9446eb7f87557f4de))

# [2.0.0-alpha.6](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.5...v2.0.0-alpha.6) (2026-01-26)


### Bug Fixes

* pin archiver and unzipper versions and add to app dependencies ([65fd739](https://github.com/RiDDiX/home-assistant-matter-hub/commit/65fd739f26f586dd3da707302dfb3117dd3628e1))


### Features

* add backup/restore system, smoke/CO detector, filter preview, dark mode, sorting, and update docs ([5bcc9a0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5bcc9a0533924e0c0b0dc1a7e7732af548d07878))

# [2.0.0-alpha.5](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.4...v2.0.0-alpha.5) (2026-01-26)


### Features

* add dark mode toggle, device list sorting, and filter preview ([b4fe7e0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b4fe7e0ad94cc136655a511263f799f915a0542e))

# [2.0.0-alpha.4](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.3...v2.0.0-alpha.4) (2026-01-26)


### Bug Fixes

* pass APP_VERSION environment variable to Docker containers ([79bde68](https://github.com/RiDDiX/home-assistant-matter-hub/commit/79bde6896f0f6b90488e09cc960ff254dcf02e76))

# [2.0.0-alpha.3](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.2...v2.0.0-alpha.3) (2026-01-26)


### Bug Fixes

* handle mutex-closed error gracefully during shutdown ([e23bcee](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e23bcee0e97e9a88eac88f2a251fbd0aeafcfe7d))

# [2.0.0-alpha.2](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v2.0.0-alpha.1...v2.0.0-alpha.2) (2026-01-26)


### Features

* improve Fan speed control, add Media Player playback ([0de6198](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0de6198ffb1c4922393e1bb8c190ceffeb613c5c))

# [2.0.0-alpha.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.22...v2.0.0-alpha.1) (2026-01-26)


* fix!: AirQuality sensor conformance - enable all feature flags ([d037659](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d03765929a61ef38809c5af8573cfcc1ce4d0987))


### BREAKING CHANGES

* Alpha version bump to 2.0.0 series. This release includes major new features like Health Monitoring Dashboard, Auto-Recovery, and Bridge Wizard.

# [1.5.0-alpha.22](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.21...v1.5.0-alpha.22) (2026-01-26)


### Features

* health monitoring dashboard, auto-recovery, bridge wizard ([3800813](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3800813f6f740d1ee3a9dd032bc350cfcb7c0f90))

# [1.5.0-alpha.21](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.20...v1.5.0-alpha.21) (2026-01-26)


### Bug Fixes

* cover position comparison, thermostat offline status, valve actions ([4388383](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4388383710f874b1aac9f3f8a7ff3022481c5d81))

# [1.5.0-alpha.20](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.19...v1.5.0-alpha.20) (2026-01-26)


### Bug Fixes

* improve humidity sensor limits, light type detection, and media player power control ([30c94de](https://github.com/RiDDiX/home-assistant-matter-hub/commit/30c94ded8af39c360062ec5fd5293ebb18f0fba7))

# [1.5.0-alpha.19](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.18...v1.5.0-alpha.19) (2026-01-26)


### Bug Fixes

* correct unit mismatch in thermostat deadband (0.1°C vs 0.01°C) ([7b88ee3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7b88ee33d51416c7798c94e515471354511f1fe4))

# [1.5.0-alpha.18](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.17...v1.5.0-alpha.18) (2026-01-26)


### Bug Fixes

* minSetpointDeadBand int8 overflow (250 -> 25) ([3110267](https://github.com/RiDDiX/home-assistant-matter-hub/commit/311026762dfed23ff0df5752ed5b1ede1c26707e))

# [1.5.0-alpha.17](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.16...v1.5.0-alpha.17) (2026-01-26)


### Bug Fixes

* thermostat deadband constraint violation causing boot loop with climate entities ([a680be8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a680be8f59c7a2d16475ea93247db9fea9b099c0))

# [1.5.0-alpha.16](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.15...v1.5.0-alpha.16) (2026-01-26)


### Bug Fixes

* add .nojekyll file and copy to docs build output for GitHub Pages ([cf96b0c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cf96b0cabee98f9f891fd8b2c0ea63f45e455c8a))

# [1.5.0-alpha.15](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.14...v1.5.0-alpha.15) (2026-01-26)


### Bug Fixes

* add environment config for GitHub Pages deployment ([87101a8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/87101a8e0bf775c1561a15a372a3604d2b63cdce))

# [1.5.0-alpha.14](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.13...v1.5.0-alpha.14) (2026-01-26)


### Bug Fixes

* add explicit docs build step with BASE_URL env for GitHub Pages ([259d57b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/259d57bda5fbfea06913d5c5e2bc283d5a253e3a))

# [1.5.0-alpha.13](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.12...v1.5.0-alpha.13) (2026-01-26)


### Features

* integrate structured logging with context and retry utilities into backend ([44bcb9f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/44bcb9f741304d7975408d30eae543e7d0675a35))

# [1.5.0-alpha.12](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.11...v1.5.0-alpha.12) (2026-01-26)


### Features

* add structured logging, retry utilities, and UI improvements ([a0b21ec](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a0b21ec30b717a9604b7d641d5ca3154060465d2))

# [1.5.0-alpha.11](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.10...v1.5.0-alpha.11) (2026-01-26)


### Bug Fixes

* StatusIndicator health API structure mismatch ([5b43fbb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5b43fbb9e3670729e1fff2f853092de54c563442))

# [1.5.0-alpha.10](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.9...v1.5.0-alpha.10) (2026-01-26)


### Features

* add Alarm Control Panel device type ([db96ffb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/db96ffb1e66ffdc7792da0286e05d35ce863f2cd))

# [1.5.0-alpha.9](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.8...v1.5.0-alpha.9) (2026-01-26)


### Features

* add Pressure, Flow, Air Quality sensors and Water Valve ([330d4e3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/330d4e37015b0c31a413b7e86faaa6cd4b0508e3))

# [1.5.0-alpha.8](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.7...v1.5.0-alpha.8) (2026-01-26)


### Bug Fixes

* add null checks in StatusIndicator to prevent crash ([e64b9a6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e64b9a6630b93e70667636b524451ef729abe3b9))

# [1.5.0-alpha.7](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.6...v1.5.0-alpha.7) (2026-01-26)


### Bug Fixes

* add smokeCoAlarm to ClusterId enum ([868558c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/868558ce11a5824c0c57c616bc54d99c1a66f736))
* correct API URLs for Home Assistant ingress support ([8d6a8b5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8d6a8b58d93692918d1cd7b89ed27019fe022001))


### Features

* add Smoke/CO Alarm device type and update entity mappings ([5d405e4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5d405e4112740e9c8ffc6104e43f39e2babc31e6))


### Performance Improvements

* parallelize state updates for faster Alexa/Google Home response ([dea2e62](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dea2e626d6eb812e5290deadaa03104c867f3190))

# [1.5.0-alpha.6](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.5...v1.5.0-alpha.6) (2026-01-26)


### Features

* add WebSocket live updates and status indicator ([227edc8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/227edc804da5e618ccef27a1f2e01796316de437))

# [1.5.0-alpha.5](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.4...v1.5.0-alpha.5) (2026-01-26)


### Features

* add migration support for importing stable exports into alpha ([331f11d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/331f11dd3dc9b545a5c25d3fb59bdba860d544d2))

# [1.5.0-alpha.4](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.3...v1.5.0-alpha.4) (2026-01-26)


### Bug Fixes

* handle missing entity-mappings storage data ([21674ab](https://github.com/RiDDiX/home-assistant-matter-hub/commit/21674ab322306d26f9e6fdcf68bfe27e9229d32e))

# [1.5.0-alpha.3](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.2...v1.5.0-alpha.3) (2026-01-26)


### Features

* complete entity mapping UI integration ([48d0ace](https://github.com/RiDDiX/home-assistant-matter-hub/commit/48d0ace72d6ad63546ec3761ce00babb53614f67))

# [1.5.0-alpha.2](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.5.0-alpha.1...v1.5.0-alpha.2) (2026-01-26)


### Features

* add bridge export/import functionality ([fbd42bd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fbd42bddd3558fc9f491ff8ea6df23c4dd2971b5))

# [1.5.0-alpha.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.4.1-alpha.1...v1.5.0-alpha.1) (2026-01-25)


### Features

* add entity mapping customization ([0e89fd0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0e89fd04245cadacad5007bfc2709623fa850d80))

## [1.4.1-alpha.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.4.0...v1.4.1-alpha.1) (2026-01-25)


### Bug Fixes

* biome formatting for .releaserc.json ([5ca1c4d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ca1c4d93cf1ff19b6833d8f3ce105934f9cfdb3))

# [1.4.0](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.3.1...v1.4.0) (2026-01-25)


### Features

* add health check API and WebSocket live updates ([bbbfd18](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bbbfd189c0325c93b98e3a06659961065341ac96))

## [1.3.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.3.0...v1.3.1) (2026-01-25)


### Bug Fixes

* rebuild frontend with APP_VERSION during release ([34b0bdf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/34b0bdf38cee70309ff1a4c0b2cec004ed6b261c))

# [1.3.0](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.2.0...v1.3.0) (2026-01-25)


### Bug Fixes

* **docs:** add base_url for GitHub Pages deployment ([d4e589e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d4e589e519b7fb97e5a75a91e0ca15ae477f2c15))
* pin Node.js to 22.13.1 for armv7 Docker support ([5be5e97](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5be5e9762375b95b9db0f9c1869d3c20f1183c85))


### Features

* drop armv7 support, upgrade to Node 24 ([0b53cc6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0b53cc67aaadcc1b375e04cf7ed8ae6df5068108))

# [1.2.0](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.1.3...v1.2.0) (2026-01-25)


### Features

* graceful handling of entities with too long IDs ([6580cdd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6580cdd5df4a54557302f26e594f741540a67a72))

## [1.1.3](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.1.2...v1.1.3) (2026-01-25)


### Bug Fixes

* **docker:** add tini for proper signal handling ([244800d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/244800d8d52e80e7760d0f99981b66f20c7a1c13))

## [1.1.2](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.1.1...v1.1.2) (2026-01-25)


### Bug Fixes

* revert to Node 22 - Node 24 has no armv7 Docker support ([2206ae4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2206ae4036ef036e8695384ffede68301b25d2bf))

## [1.1.1](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.1.0...v1.1.1) (2026-01-25)


### Bug Fixes

* disable NPM publish - package owned by original maintainer ([9d65932](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9d65932aa92365e04a98693125d3ea05ce9ce55a))

# [1.1.0](https://github.com/RiDDiX/home-assistant-matter-hub/compare/v1.0.0...v1.1.0) (2026-01-25)


### Features

* add regex and device_name filters, update to riddix ownership, fix Windows compatibility ([2095da4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2095da43bec3078ce450f806d65a266f12b0fc9c))

# 1.0.0 (2026-01-25)


### Bug Fixes

* add additional null-checks to prevent startup failures ([c53c29f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c53c29f09734c5acb84889451286c182fc461363)), closes [#584](https://github.com/RiDDiX/home-assistant-matter-hub/issues/584)
* add configuration option to set Country Code in regulatory config ([f0145ac](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f0145acc1eb8222acb505f8c4784aec52f14b48c)), closes [#541](https://github.com/RiDDiX/home-assistant-matter-hub/issues/541)
* add debug logging when home assistant actions fail ([d77826e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d77826ef95fd7f8de87abffcd7a09326e47ebb5c)), closes [#264](https://github.com/RiDDiX/home-assistant-matter-hub/issues/264)
* add explicit icon for google vendor id ([0afbd42](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0afbd42441e05f4fb0592d724c58b6ee7b695b1e)), closes [#32](https://github.com/RiDDiX/home-assistant-matter-hub/issues/32)
* add extra logging when a device cannot be created ([fc0a2f0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fc0a2f0aef69d44093ee214571868ab01ad23658)), closes [#404](https://github.com/RiDDiX/home-assistant-matter-hub/issues/404)
* add fallback mechanism for empty json files ([035a0bd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/035a0bd174c0cc52ab595f578e5f9cad967da609)), closes [#9](https://github.com/RiDDiX/home-assistant-matter-hub/issues/9)
* add further null checks to prevent bridge from failing ([b8e55c4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b8e55c424ef9c33ea32f738d8e294087972d55d2)), closes [#404](https://github.com/RiDDiX/home-assistant-matter-hub/issues/404) [#412](https://github.com/RiDDiX/home-assistant-matter-hub/issues/412)
* add hash to state subscription to prevent reuses when entity filter is changed ([1162dce](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1162dced1bd9f41d40b526e8a84f010b840cccf4)), closes [#37](https://github.com/RiDDiX/home-assistant-matter-hub/issues/37)
* add missing token to generate github releases ([dd3479f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd3479fec0e5ee021f1f355b71bb30b83a2ebcb3))
* add more configuration details ([7c95b3c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7c95b3c7f24ab6c7da82ec8300eb5ce1910523de))
* add more details when home assistant connection fails ([963d3b2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/963d3b25fd6f0f42e411e30d71491d6ff876a034))
* add silly logs for entity exclusion ([e635f91](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e635f91eb380c2a028924fc91c26093d848284dd)), closes [#40](https://github.com/RiDDiX/home-assistant-matter-hub/issues/40)
* **addon:** revert docker entrypoint setup for the native home assistant addon ([095bd97](https://github.com/RiDDiX/home-assistant-matter-hub/commit/095bd972180e47c181cce9081254778a341fcccf))
* another try to properly react to state events ([04ba690](https://github.com/RiDDiX/home-assistant-matter-hub/commit/04ba6909111108d0982b78d8deaff7d2ea471d99))
* automatically retry home assistant connection on startup ([47979d9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/47979d9dfdaccb3242a9f0b890f610695eda2107)), closes [#347](https://github.com/RiDDiX/home-assistant-matter-hub/issues/347)
* **automation, scene, input_button, button:** add 'lighting' feature to allow onOff to work properly ([2f0bf90](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2f0bf907ac58958de03ddef44b8e898350f1dbd4)), closes [#638](https://github.com/RiDDiX/home-assistant-matter-hub/issues/638) [#636](https://github.com/RiDDiX/home-assistant-matter-hub/issues/636) [#630](https://github.com/RiDDiX/home-assistant-matter-hub/issues/630) [#596](https://github.com/RiDDiX/home-assistant-matter-hub/issues/596)
* avoid transaction locks in applyPatchState by assigning each key ([#869](https://github.com/RiDDiX/home-assistant-matter-hub/issues/869)) ([7c755d2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7c755d2e997c26f5cc576d2d97d4054b542aba9f))
* **basic-information-server:** Use device vendor ([#472](https://github.com/RiDDiX/home-assistant-matter-hub/issues/472)) ([7fd669a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7fd669a6304329183995eb78e2b536cc8292583e))
* **basic-information:** add vendor id and names to all devices ([d3e4703](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d3e4703583eb7bd9545d74faf3434085311bcc34))
* **basic-information:** consider maxLength of device properties ([627aea5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/627aea5149c831a0592f12e7f42618379e4adad3)), closes [#6](https://github.com/RiDDiX/home-assistant-matter-hub/issues/6)
* **basic-information:** ensure variables are actually strings ([dc5f700](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dc5f700d843a57465d4456c502aba264160acd8a)), closes [#400](https://github.com/RiDDiX/home-assistant-matter-hub/issues/400)
* **basic-information:** prevent empty values to fail initialization ([73185d5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/73185d58b5a9e1b67b972af5801fa1d1966a7586)), closes [#393](https://github.com/RiDDiX/home-assistant-matter-hub/issues/393)
* **basic-information:** use proper device information instead of mocked values ([d33c6e8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d33c6e8099a38ce5ed6138d31a6088dc8d2e2336))
* **basicInformation:** reduce the hash for long names to 4 chars ([1212ad3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1212ad3e50cbfc9dec8b748bc4dcf6c800692baa)), closes [#116](https://github.com/RiDDiX/home-assistant-matter-hub/issues/116)
* **basicInformation:** use the entity_id as name, if name is missing ([d4baf5c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d4baf5c14845cc9f446b9eabdfb66c1f346ff030)), closes [#117](https://github.com/RiDDiX/home-assistant-matter-hub/issues/117)
* **binary_sensor:** made config of boolean state cluster optional ([0710d89](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0710d8922faf01077873ba0bd3b28033fe57e64b)), closes [#154](https://github.com/RiDDiX/home-assistant-matter-hub/issues/154)
* **binary_sensor:** revert to invert state for ALL contact sensors ([572fc85](https://github.com/RiDDiX/home-assistant-matter-hub/commit/572fc85f5b4d6f9d293d41d08a57569d3fd0d28b))
* **binary_sensor:** safe access the config from the state ([b703cc7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b703cc7f2d2ee91abe1447335e8ae2b33b691cd3)), closes [#78](https://github.com/RiDDiX/home-assistant-matter-hub/issues/78)
* **bridge:** enable flex wrapping for filter chips in BridgeDetails ([#95](https://github.com/RiDDiX/home-assistant-matter-hub/issues/95)) ([4dcda7a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4dcda7a49a32b0052a15fa4c15d3885d605fc4b2)), closes [#94](https://github.com/RiDDiX/home-assistant-matter-hub/issues/94)
* **bridge:** since matter 1.4 bridge names are limited to 32 characters ([d6bb614](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d6bb614b32d36297ce8555394d41b34c63eb2818)), closes [#623](https://github.com/RiDDiX/home-assistant-matter-hub/issues/623)
* built clean update mechanism to prevent devices to get re-created ([26dc0be](https://github.com/RiDDiX/home-assistant-matter-hub/commit/26dc0bea5b5b625c340569bfb2192d9930330ceb)), closes [#214](https://github.com/RiDDiX/home-assistant-matter-hub/issues/214)
* bumb matter.js to 0.12.3 ([a1266d9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a1266d9f7330334bfb20cc0aec296a2a6c29352e)), closes [#485](https://github.com/RiDDiX/home-assistant-matter-hub/issues/485) [#491](https://github.com/RiDDiX/home-assistant-matter-hub/issues/491)
* change fallthrough matcher after migrating to express@5 ([620eddd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/620eddd0caa9a3e1450eff36b489d22592eb8b34))
* **ci:** add repository to repository_dispatch ([28d34b0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/28d34b06874be5fb5b2b10e40df179d1afd1fe60))
* **ci:** allow multiple docker image tags ([c737066](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c7370662c0f53c99ab9eeabef7f0d3b7ba94f2f2))
* **ci:** automatic releases for the addon repository including changelog ([4559883](https://github.com/RiDDiX/home-assistant-matter-hub/commit/45598834ed446ed7303a0a780ea1accb3aaced8f)), closes [#90](https://github.com/RiDDiX/home-assistant-matter-hub/issues/90)
* **ci:** enable releases on the 'latest' channel ([1b8d02d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1b8d02d3d260a8a6b234189a8b2e7b6bb767a2aa))
* **ci:** properly load changelog for complete release notes ([b85f3d1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b85f3d121ea35041b0be1b884aa65f933cbbb01d))
* **ci:** remove typo which prevented the release workflow ([7330d8d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7330d8d08e15c8aa2c1e176f2e46abd16048eb40))
* cleanup boot sequence and state handling, update all dependencies ([4afb864](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4afb86469268dca6ed4f1103cc316f64c2a182ec))
* **climate & fan:** correctly react to property changes ([08a4d68](https://github.com/RiDDiX/home-assistant-matter-hub/commit/08a4d684205d294ea5d2216c19eaaa55b4b5beac)), closes [#624](https://github.com/RiDDiX/home-assistant-matter-hub/issues/624)
* **climate:** add OnOff cluster to climates, so that they can be turned on and off ([841a192](https://github.com/RiDDiX/home-assistant-matter-hub/commit/841a192fd35b9583098c9c0e324cd20291139a3a))
* **climate:** allow auto-mode only ([7bb1f68](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7bb1f6834893b53cf50fa0ae2bf80ec3d71a706c)), closes [#47](https://github.com/RiDDiX/home-assistant-matter-hub/issues/47)
* **climate:** do not set the target position when device is off ([b828295](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b82829560f460efb22fe9b3debbe57016766cb4d)), closes [#169](https://github.com/RiDDiX/home-assistant-matter-hub/issues/169)
* **climate:** ensure correct temperature conversion between home assistant and matter ([bb33b7b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bb33b7bbbe9ed3473b2ba9c0a28de39b406a9f19)), closes [#411](https://github.com/RiDDiX/home-assistant-matter-hub/issues/411)
* **climate:** ignore unsupported covers and print a warning instead of failing ([317ef5c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/317ef5cac93d92255b339812b3b426298ecf0833)), closes [#561](https://github.com/RiDDiX/home-assistant-matter-hub/issues/561)
* **climate:** map all neccessary properties from climate to thermostat ([72ab81e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/72ab81e59be5823cb64f05cb2b0570e524905a8e)), closes [#73](https://github.com/RiDDiX/home-assistant-matter-hub/issues/73)
* **climate:** only add humidity sensor if available at all ([948a34a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/948a34a3c76151c81f6929e0fc77a9b188470b89)), closes [#168](https://github.com/RiDDiX/home-assistant-matter-hub/issues/168)
* **climate:** remove optional temperature cluster ([#147](https://github.com/RiDDiX/home-assistant-matter-hub/issues/147)) ([a6d9baa](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a6d9baa6cd364e22260ecbfb290cda9177409e80)), closes [#142](https://github.com/RiDDiX/home-assistant-matter-hub/issues/142)
* **climate:** set controlSequenceOfOperation as a required property ([4816273](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4816273b5702bf84ada2dae1149fdd17f9ea9536)), closes [#16](https://github.com/RiDDiX/home-assistant-matter-hub/issues/16)
* **climate:** use 'current_temperature' attribute to get current temperature ([b7475a7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b7475a70de0d2171dba55dbed6c5a112cd6b4e17))
* **climate:** use cooling and heating together with auto mode ([6193a40](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6193a407be100eaa5dc0ec80c8aa41bfa4be5227))
* **climate:** use entity state instead of hvac_mode attribute ([ff20e85](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ff20e852a65c3b35ef0d65a4035bb8b3f309d91c)), closes [#449](https://github.com/RiDDiX/home-assistant-matter-hub/issues/449)
* **climate:** use entity state value as fallback for all status reports ([20483e8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/20483e8da80a56708d472dec3edb6e8ec4ba6dad)), closes [#73](https://github.com/RiDDiX/home-assistant-matter-hub/issues/73)
* **color-control:** Propagate colorMode ([ce5ced4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ce5ced423943421a07d11faff877d9eb7ab47f46)), closes [#225](https://github.com/RiDDiX/home-assistant-matter-hub/issues/225)
* **colorControl:** validate min and max mireds to stay in bounds ([2e10106](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2e10106e06d13273ff7fc9348f4a4212dc2659c7)), closes [#379](https://github.com/RiDDiX/home-assistant-matter-hub/issues/379)
* Cover open state incorrectly syncs as "null" instead of 0% in Matter ([#910](https://github.com/RiDDiX/home-assistant-matter-hub/issues/910)) ([9c4b528](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9c4b528b76dc78e2d55d413e1655b719e630e8b0))
* **cover:** add AbsolutePosition feature to position aware covers and fake PositionAware feature for non position aware covers ([7fb8a01](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7fb8a01931f905fd338723859b0fa690c69100e1)), closes [#144](https://github.com/RiDDiX/home-assistant-matter-hub/issues/144)
* **cover:** allow covers to be not position aware ([7af0298](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7af0298135e24c8f09782833c68fad851a8c0904)), closes [#144](https://github.com/RiDDiX/home-assistant-matter-hub/issues/144)
* **cover:** do not use configStatus to control lift directions ([de7aae8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/de7aae8292526aafedaafe1ad7567d51e233cb71)), closes [#144](https://github.com/RiDDiX/home-assistant-matter-hub/issues/144)
* **cover:** keep current position in bounds ([41f10bf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/41f10bfe32047f65ca17d28eddabb4eda158fc4a))
* **cover:** remove absolute position and add operational status ([5e37273](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5e372735046c79e2e1949f8376d63a9a09b57858))
* **cover:** remove unallowed properties from covers without positions ([241206c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/241206c1f5716b82aca2189614575efc53b844dc))
* **cover:** split feature flag 'mimicHaBehavior' into two features flags for more control ([bd24afd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bd24afd64434665258e9567fce286753dd5cad34))
* **cover:** use compatible cover types for tilt only or both ([a28ee12](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a28ee129da8463f3a9acee6ca629781f882d3ea4)), closes [#393](https://github.com/RiDDiX/home-assistant-matter-hub/issues/393)
* **cover:** use compatible endProductType for tilt and lift ([38c9731](https://github.com/RiDDiX/home-assistant-matter-hub/commit/38c97317c95a75998d427da9010b01733dda418b)), closes [#444](https://github.com/RiDDiX/home-assistant-matter-hub/issues/444)
* debounce HA entity updates to 1 transaction for its attributes ([#870](https://github.com/RiDDiX/home-assistant-matter-hub/issues/870)) ([3608873](https://github.com/RiDDiX/home-assistant-matter-hub/commit/36088738bc710d360c20c6a5689efdfaba3bf358))
* **deps:** update all npm dependencies ([690abbc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/690abbc6346239e6b299126e6dc8b86308bded12))
* **deps:** update dependency ajv to v8 ([e73e5c5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e73e5c5cfb985857c2d632cbdaeb01bd6d285049))
* **deps:** update matter.js to v0.11.8 ([8fe9509](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8fe950993d1ef7715da388de73b7c1a1afbb3c55))
* disable automatic releases ([54f6e50](https://github.com/RiDDiX/home-assistant-matter-hub/commit/54f6e50a692d887740ee53085fdd6b1d8c51b87c))
* disable matter environment parsing ([effe5a4](https://github.com/RiDDiX/home-assistant-matter-hub/commit/effe5a4278e68f658c3035e33ee54da3e55505d3))
* Do not interpret "unknown" boolean states as "true" matter state ([#856](https://github.com/RiDDiX/home-assistant-matter-hub/issues/856)) ([e3bf044](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e3bf0441157464fe661bfca1d32473a3e6ed8440))
* **docker:** ensure the app handles process signals properly ([a8dd37e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a8dd37e62c4509b1ef04771611e104dabd67937a)), closes [#516](https://github.com/RiDDiX/home-assistant-matter-hub/issues/516)
* **docker:** migrate all docker images to node22 ([0af1d92](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0af1d92431c88ac9af0cbbb5e06440cb9010f073))
* **docker:** refactor entrypoint and cmd to allow proper shutdown ([57c01b2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/57c01b28bcaee707e3499ea630dd54605272f6a8)), closes [#516](https://github.com/RiDDiX/home-assistant-matter-hub/issues/516)
* **docker:** remove environment variables from dockerfile ([24adece](https://github.com/RiDDiX/home-assistant-matter-hub/commit/24adece5615e29578ba382dc2acccde37d911672))
* **docs:** add base-url ([7d8e4a0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7d8e4a0187215a053aec3aa83352c718e28e6006))
* **docs:** change the addon repository to be added in home assistant ([4aedf2e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4aedf2ec6f7f30d1e5ea6638c4c6cba6c805baa8))
* enable update of feature flags without restarting the addon ([a5bacab](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a5bacab2ded71d249b92419c60c6fda0442936d9))
* **fan-control:** always set fan mode sequence ([57803ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/57803ca63d9d8250a98c6a07e1db592e1a3cea87)), closes [#274](https://github.com/RiDDiX/home-assistant-matter-hub/issues/274)
* finally fix bigint serialization to be compatible with matter.js ([51f84e1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/51f84e10c11f9031b1e919a46be6cae1005b0320))
* fix OnOffServer after Matter.js 0.13.0-nightly upgrade ([26c3ee7](https://github.com/RiDDiX/home-assistant-matter-hub/commit/26c3ee72ceed48ff5b2086fe49fb95c07459bc95)), closes [#621](https://github.com/RiDDiX/home-assistant-matter-hub/issues/621) [#620](https://github.com/RiDDiX/home-assistant-matter-hub/issues/620)
* frontend version number ([3ca7218](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3ca7218cd5af318779c8d969bc9f694fca34bfe5))
* **frontend:** Add Amazon and Apple vendor IDs ([a244855](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a2448556a61a202b318242bc7a75ccb963a22626))
* **frontend:** add base to index.html ([75137fe](https://github.com/RiDDiX/home-assistant-matter-hub/commit/75137febcab98a7687d50eda0a4e22d70652cb06))
* **frontend:** add copy-to-clipboard action to cluster states ([f79ef69](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f79ef69048294245f571055a81757ab405e41c45))
* **frontend:** add explicit main page to not prevent history-back ([ed13eb8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ed13eb84cbdacefe6b8208de92e0df2684a07351)), closes [#246](https://github.com/RiDDiX/home-assistant-matter-hub/issues/246) [#238](https://github.com/RiDDiX/home-assistant-matter-hub/issues/238)
* **frontend:** add margin to the commissioning qr-code ([#198](https://github.com/RiDDiX/home-assistant-matter-hub/issues/198)) ([9498ae9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9498ae9ebf982b46b84c9cc1707fa1b000c89f4d))
* **frontend:** Add second Samsung vendor ID ([#256](https://github.com/RiDDiX/home-assistant-matter-hub/issues/256)) ([5ce01aa](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ce01aaef12ba09267e72c80996627ce686c6000)), closes [#253](https://github.com/RiDDiX/home-assistant-matter-hub/issues/253)
* **frontend:** adjust base url to prevent broken urls ([370d25b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/370d25b3363fcc09d4a9cbb0627dae8de79713fe))
* ignore entities by their hidden and disabled state ([9e7b641](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9e7b6413e5311cec2e13e05b1d034259615174c4)), closes [#23](https://github.com/RiDDiX/home-assistant-matter-hub/issues/23)
* implement moveToLevelWithOnOff for all levelControls ([93ab431](https://github.com/RiDDiX/home-assistant-matter-hub/commit/93ab431eaf4b6cb7dab67d79ad772938baf8f33d)), closes [#34](https://github.com/RiDDiX/home-assistant-matter-hub/issues/34)
* improve logging to debug inclusion and exclusion ([f055652](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f055652c87be7b887f2a46583e723e971028c582))
* **input_button:** turn the matter device 'on' for a short time ([57465a6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/57465a635f9fffe10156b36ff2d7aacd5a2dcfa3)), closes [#388](https://github.com/RiDDiX/home-assistant-matter-hub/issues/388)
* **input_button:** use correct action to trigger the button ([936ac64](https://github.com/RiDDiX/home-assistant-matter-hub/commit/936ac64b60da28033e79535f468fe508cbf23f5b)), closes [#501](https://github.com/RiDDiX/home-assistant-matter-hub/issues/501)
* introduce an initial start-up delay to make sure home assistant is ready ([0fdb09a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0fdb09aee02220113f25414bcc160485cb663ae6))
* **level-control:** configure minimal transition time ([e754974](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e754974dad037c5c12755acf3b548bd5216a807c)), closes [#4](https://github.com/RiDDiX/home-assistant-matter-hub/issues/4)
* **light:** add fallback-transition time to level- and color-control ([b0ed5a8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b0ed5a8ff7747d471c37d6f866f462eedef92ea4)), closes [#4](https://github.com/RiDDiX/home-assistant-matter-hub/issues/4)
* **light:** allow adjusting min and max level if value is out of bounds ([a95dbda](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a95dbdadeaf17913ca8ea80c1745aadde87cc2f4)), closes [#336](https://github.com/RiDDiX/home-assistant-matter-hub/issues/336)
* **light:** default hue and saturation to 0 when not available ([306bf5a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/306bf5ae88bcb83df00663ce0c235f5db72b0bac)), closes [#134](https://github.com/RiDDiX/home-assistant-matter-hub/issues/134)
* **light:** do not set out-of-bounds color temperatures ([a22ae25](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a22ae25bda441a0c395ce31b2e58243df0632ac5)), closes [#53](https://github.com/RiDDiX/home-assistant-matter-hub/issues/53)
* **light:** ensure color temperature is always within boundaries ([dd47e08](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd47e085b8dd97de8b6612589e5093118372a2ba)), closes [#676](https://github.com/RiDDiX/home-assistant-matter-hub/issues/676)
* **light:** only round min and max values properly ([50394f6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/50394f607ab18cd70eda23edb3f761dde15778ae)), closes [#99](https://github.com/RiDDiX/home-assistant-matter-hub/issues/99)
* **light:** Return 0.0 instead  of null for light brightness to prevent apple home to fail ([7ddbfdd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7ddbfdd74edf02e1a64fe02e8d9920d970daae4f))
* **light:** round values after converting kelvin and mireds ([e4ad137](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e4ad137ba6e52745751619e6c5311b3670d3200a)), closes [#4](https://github.com/RiDDiX/home-assistant-matter-hub/issues/4)
* **lights:** apply rounding to brightness and color calculations ([f72cd9a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f72cd9a66d38d74c75fd85e7eee6ea6fed3cea36))
* **lights:** auto adjust min and max mireds when value is out of bounds ([83a6fa0](https://github.com/RiDDiX/home-assistant-matter-hub/commit/83a6fa03cee49a054c22d12646ac10b71d960bf7))
* **lights:** debounce home assistant actions to prevent race conditions ([#855](https://github.com/RiDDiX/home-assistant-matter-hub/issues/855)) ([bd38e20](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bd38e20dd98b21e2abafd39d514898ac48663b4a))
* **lights:** enable features for on/off and level control ([e89cb67](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e89cb6726b434b788844d09f873821fa29fdcd1f))
* **light:** set previous level when light is turned off ([f761edd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f761edd0e4aaa916d88cb45f030997c325f04672))
* **lights:** preserve last level control state ([6991d9b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6991d9b4403a435887b69d83d04f1dff7e2712a1)), closes [#217](https://github.com/RiDDiX/home-assistant-matter-hub/issues/217)
* **lights:** proper boundaries for color temperature ([784f186](https://github.com/RiDDiX/home-assistant-matter-hub/commit/784f1866dcba40accc383509b6b5ff54ea02f8bf)), closes [#392](https://github.com/RiDDiX/home-assistant-matter-hub/issues/392)
* **lights:** remove old and wrong properties from lights ([0c02a6c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0c02a6c74704cf23a3b2c1d783db33730ddf70da)), closes [#138](https://github.com/RiDDiX/home-assistant-matter-hub/issues/138)
* **light:** swap min and max temperature when mixed up in the entity ([bcd84cd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bcd84cdada63203e91c03f6e56fab2de72778972)), closes [#410](https://github.com/RiDDiX/home-assistant-matter-hub/issues/410)
* **light:** use correct device type for color temp only devices ([4b57edf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4b57edf09beb7af88b1c91b0a633f62505d325b6)), closes [#52](https://github.com/RiDDiX/home-assistant-matter-hub/issues/52)
* log but avoid crash for invalid device errors ([df983ed](https://github.com/RiDDiX/home-assistant-matter-hub/commit/df983ed9119ce7c7edbcbbc7881ff1552cbda704))
* **matter:** finish transaction before calling home assistant services ([f66372c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f66372c3f63445bf113b504daca2338a133e9c94)), closes [#225](https://github.com/RiDDiX/home-assistant-matter-hub/issues/225)
* **media_player:** set default input when no input could be determined ([0830f18](https://github.com/RiDDiX/home-assistant-matter-hub/commit/0830f18af2225ea8a6e053422008457df3d5844f)), closes [#393](https://github.com/RiDDiX/home-assistant-matter-hub/issues/393)
* minor frontend fixes ([97aa72a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/97aa72a360e9bc5b7a81adc858543820490efb9b)), closes [#93](https://github.com/RiDDiX/home-assistant-matter-hub/issues/93)
* minor patch in state management ([cb7607e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cb7607ea80d960ce83f7800b7ac46df4c95791fc))
* **on-off:** allow sending on and off commands, when already on or off ([898ba0d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/898ba0dd8073c5eef85ab5e7ee93e1f5ddc0c080)), closes [#320](https://github.com/RiDDiX/home-assistant-matter-hub/issues/320)
* only hash labels larger than max length ([3e71fb3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3e71fb37a1c77dba038e91dde13261685a4a888f))
* prevent bridge edit screen from automatically changing the port ([415fada](https://github.com/RiDDiX/home-assistant-matter-hub/commit/415fadabbe184decacec3a270d36485bf7a1095e))
* prevent edge cases where storage gets deleted ([3bdc6ee](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3bdc6ee6c66c771ae51297bcc66332c20d40d011))
* prevent race conditions when home assistant responds faster than matter ([#211](https://github.com/RiDDiX/home-assistant-matter-hub/issues/211))  ([5ca0727](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5ca07272656cbd1489ebfbf7edb2b9668d3d84f1)), closes [#208](https://github.com/RiDDiX/home-assistant-matter-hub/issues/208)
* properly handle transactions to prevent cyclic event flows ([afce77c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/afce77c29eebbf966651a43fd1022671a620bfe2)), closes [#763](https://github.com/RiDDiX/home-assistant-matter-hub/issues/763) [#745](https://github.com/RiDDiX/home-assistant-matter-hub/issues/745)
* properly report brightness value when light is off ([#909](https://github.com/RiDDiX/home-assistant-matter-hub/issues/909)) ([a002204](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a00220414606f9d56fc177646727cd406ea4a6de))
* properly trap process signals and shutdown the application ([69c1175](https://github.com/RiDDiX/home-assistant-matter-hub/commit/69c1175c22a7ecd8a9e8dafe2292ff18d074bc84)), closes [#516](https://github.com/RiDDiX/home-assistant-matter-hub/issues/516)
* properly wait for home assistant to boot before starting any bridge ([b8986cc](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b8986cc198a460dca8a1c7a7c3b74c4d38187098)), closes [#574](https://github.com/RiDDiX/home-assistant-matter-hub/issues/574) [#228](https://github.com/RiDDiX/home-assistant-matter-hub/issues/228) [#459](https://github.com/RiDDiX/home-assistant-matter-hub/issues/459)
* properly wait for transactions to begin and to commit ([#877](https://github.com/RiDDiX/home-assistant-matter-hub/issues/877)) ([1f96b41](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1f96b41e6c50b4ae4b51f934b6bce2d18492d266)), closes [#876](https://github.com/RiDDiX/home-assistant-matter-hub/issues/876)
* refactor all clusters to use reactTo and pessimistic state changes ([cd00915](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cd00915c7fe2d0a82d7bc6419294fc4e78286ad8))
* refactor thermostat server to a single behavior with feature flags ([a939600](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a93960071cf46bb60fc9d78e9f0dedbafbdfea22))
* remove all entities which don't have a state ([cb7b76c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cb7b76c10ee55cd018ac8d4d59cf25bba58f3325)), closes [#11](https://github.com/RiDDiX/home-assistant-matter-hub/issues/11)
* remove feature flags ([75b2335](https://github.com/RiDDiX/home-assistant-matter-hub/commit/75b2335e4322c6df2df99cd4909defcd24b5c382))
* remove first-release flag ([3b90bfe](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3b90bfe7323f3100ad833bfb324da55a0c33468c))
* remove funding ([c7eafaa](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c7eafaaa860f1ca0046f6c559ca073c324717620))
* resolve dependabot vulnerability checks ([f2aa5ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f2aa5ca046fa71f93271d42abb328a496e82e69d))
* revert matter.js and cleanup dependencies ([89507ce](https://github.com/RiDDiX/home-assistant-matter-hub/commit/89507ce1a9df3a74426fd294d3755115a2b1eafa))
* revert matter.js to 0.11.5-alpha.0-20241121-c31bc6998 ([a52a66e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a52a66edf2780497a18bfed9df1b4a171df7a1a0))
* revert offline transactions for updates ([9d548ea](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9d548ea994444ab50c8edfffd222da0c2af6afa6)), closes [#887](https://github.com/RiDDiX/home-assistant-matter-hub/issues/887) [#876](https://github.com/RiDDiX/home-assistant-matter-hub/issues/876)
* **scene:** default to off state to be able to turn it on ([1af9513](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1af9513e4eeecbb1833ab15a5e71446a1c37a819)), closes [#199](https://github.com/RiDDiX/home-assistant-matter-hub/issues/199)
* **script, automation, scene:** explicit call the right commands to activate scripts, automations, and scenes ([66f41cd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/66f41cd324711e9d8874efb400c979784ba325a1)), closes [#326](https://github.com/RiDDiX/home-assistant-matter-hub/issues/326)
* **sensor:** fix temperature conversion ([59c17d8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/59c17d89390fd9e9c22e9d7633e75b134f80a7e9)), closes [#64](https://github.com/RiDDiX/home-assistant-matter-hub/issues/64)
* smaller fixes after upgrading to Matter 1.4 ([7472e7f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7472e7f62f03d7da859b67d58a07bcdf0363a25a)), closes [#615](https://github.com/RiDDiX/home-assistant-matter-hub/issues/615)
* **storage:** do not load device states from disk ([1cc51db](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1cc51db653b85defb4c8d94d10098c2c1890f747)), closes [#532](https://github.com/RiDDiX/home-assistant-matter-hub/issues/532)
* **storage:** fixed storage migration of the last release ([8ddb9b5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8ddb9b5be1e51dd57828226f9befc41e977fbe5d)), closes [#523](https://github.com/RiDDiX/home-assistant-matter-hub/issues/523)
* **storage:** use multi-file storage to prevent broken storage files due to race conditions ([98179e6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/98179e6d13e44df32fcb73884c5d960fc0f231cc)), closes [#435](https://github.com/RiDDiX/home-assistant-matter-hub/issues/435)
* support pattern matching ([8107a8b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8107a8b8d66d01e55af8be178f12d6078b68aa4c)), closes [#14](https://github.com/RiDDiX/home-assistant-matter-hub/issues/14) [#30](https://github.com/RiDDiX/home-assistant-matter-hub/issues/30)
* **switch:** show switches as 'off' if they are unavailable ([5b799fb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5b799fb176829d31f2a7253c9cdf6b2b8cf676cb)), closes [#496](https://github.com/RiDDiX/home-assistant-matter-hub/issues/496)
* **thermostat:** add additional logging when unit of measurement changes ([90b625b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/90b625bda5f201a10ffbd1ba8a67b2c1bf1847af)), closes [#411](https://github.com/RiDDiX/home-assistant-matter-hub/issues/411)
* **thermostat:** Check if setting temperature range is supported ([#453](https://github.com/RiDDiX/home-assistant-matter-hub/issues/453)) ([ba3a2f6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ba3a2f6e594639388c874e11dcc3f6a3c51021f2)), closes [#377](https://github.com/RiDDiX/home-assistant-matter-hub/issues/377) [#449](https://github.com/RiDDiX/home-assistant-matter-hub/issues/449)
* **thermostat:** Compare setpoint with target temperature ([#254](https://github.com/RiDDiX/home-assistant-matter-hub/issues/254)) ([b7259ca](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b7259cad4ae50c90e29f5581eeb5812af4274be6))
* **thermostat:** consider the default unit of measurements from home assistant for temperatures ([e9aeb1a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e9aeb1ac06507d1d8d5577a7831a976e03fffc05)), closes [#348](https://github.com/RiDDiX/home-assistant-matter-hub/issues/348)
* **thermostat:** refactor how states are synchronized ([551da69](https://github.com/RiDDiX/home-assistant-matter-hub/commit/551da69cfa7287677337c166e3cde0ce08310a63))
* **thermostat:** set thermostatRunningState more explicit ([8617c88](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8617c8880e93ac06522574170129d58f9a1c7a0e)), closes [#241](https://github.com/RiDDiX/home-assistant-matter-hub/issues/241)
* **thermostat:** Skip temp commands if state is unavailable ([#255](https://github.com/RiDDiX/home-assistant-matter-hub/issues/255)) ([5e68c47](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5e68c470eeddd3da760daccb1e14dee9adcc9bd1)), closes [#216](https://github.com/RiDDiX/home-assistant-matter-hub/issues/216)
* trigger new release ([d00b83f](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d00b83f2715b19c1ad96d88da6d88d1afe345614))
* trying to figure out why serialization works locally but not in docker ([a2c880b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a2c880b386f7f6517cf2979062ec5682f3ac017a))
* update all dependencies including matter.js ([197f01c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/197f01c06724c2d411035680c5ffc3bc510f4da8))
* update dependencies and switch from nx-releases to semantic-release ([a587383](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a5873838adbadfc2b132a9b8d068637242ea83ef))
* upgrade to latest matter.js to fix on-off and connectivity issues ([91d05eb](https://github.com/RiDDiX/home-assistant-matter-hub/commit/91d05eb913102cfbd9162d2859fa55706554b6a0)), closes [#627](https://github.com/RiDDiX/home-assistant-matter-hub/issues/627) [#613](https://github.com/RiDDiX/home-assistant-matter-hub/issues/613) [#594](https://github.com/RiDDiX/home-assistant-matter-hub/issues/594)
* use fallback dirname for node:18 ([bbe0903](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bbe09033cc7fd29c4dab4c231f107490fb49287c))
* use matter internal serialization to be able to serialize additional types (bigint, etc.) ([04e6bc5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/04e6bc5b45f63d1f4e835479c1fb6bc1ff79960e)), closes [#836](https://github.com/RiDDiX/home-assistant-matter-hub/issues/836)
* Use Transaction.act to handle lock acquisition in applyPatchState ([#872](https://github.com/RiDDiX/home-assistant-matter-hub/issues/872)) ([f10c7ed](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f10c7ed22ba51b49b6133e234731663009884776))
* **vacuum:** consider supported features when pausing a vacuum ([70ac3af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/70ac3af2cb4697d6547882bb8fd82b9547b1e536)), closes [#645](https://github.com/RiDDiX/home-assistant-matter-hub/issues/645) [#659](https://github.com/RiDDiX/home-assistant-matter-hub/issues/659)
* **vacuum:** proper implement pause, resume and mode change commands ([c29ed54](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c29ed543ffcb077964185b764fdd6d41d1bbc371)), closes [#616](https://github.com/RiDDiX/home-assistant-matter-hub/issues/616) [#637](https://github.com/RiDDiX/home-assistant-matter-hub/issues/637)
* **vacuum:** return to dock when put into idle mode ([3a8ac4a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3a8ac4a38c14a70f8ea68e64526c78aba9cb0b72))


### chore

* major refactoring due to the growing number of supported device types ([75a1df3](https://github.com/RiDDiX/home-assistant-matter-hub/commit/75a1df3de48347aa51fd01927d601dcadd30f049)), closes [#649](https://github.com/RiDDiX/home-assistant-matter-hub/issues/649) [#644](https://github.com/RiDDiX/home-assistant-matter-hub/issues/644)


### Features

* add a customized app logo ([#202](https://github.com/RiDDiX/home-assistant-matter-hub/issues/202)) ([f01dba6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f01dba6cfbea3a5f1b6555b70e49247e12a2d1aa))
* add base url and proxy detection ([bbce762](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bbce762296b4f5d3b01d541710a57be229419be7))
* add descriptions for docker-compose ([7b304fd](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7b304fd7da2d84bc2d06ee45fcfaaabb767e7009))
* add IP whitelisting to prevent unauthorized access ([916b3ae](https://github.com/RiDDiX/home-assistant-matter-hub/commit/916b3ae5f38f21b0f5f86e2caa1acc338f79c3d5))
* add support for input_boolean, scene, automation, script ([e63a955](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e63a955f22b40a9ecac24a8f4f1003db41b2a169)), closes [#21](https://github.com/RiDDiX/home-assistant-matter-hub/issues/21)
* adjust proxy request handling and update documentation ([f6bdd20](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f6bdd20aa6acb4c8c723d0a926736b37c9b52e49))
* allow configuring the mdns-interface ([441c99b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/441c99bb15b9366ffc32a226041242efc22fc784)), closes [#42](https://github.com/RiDDiX/home-assistant-matter-hub/issues/42)
* allow filtering by entity_category ([fc83505](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fc835056b7f3d9fedb02b52ca3bff567916b5f4e))
* allow include and exclude by area ([a3ef4a6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/a3ef4a6bbbdd565168835af84047b510e4d62a52))
* allow including hidden entities with a feature flag ([03be49d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/03be49d87b47c4e6f01155166d2fd7da07ebca77)), closes [#515](https://github.com/RiDDiX/home-assistant-matter-hub/issues/515)
* allow specifying basic authentication ([4a40caf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4a40caff805ff83fd12c482b42f933c56a804802)), closes [#434](https://github.com/RiDDiX/home-assistant-matter-hub/issues/434)
* **basic-information:** add serial number to devices ([7c37dc1](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7c37dc1d49dcc1a4f1a1187bab0af7812ee70b97)), closes [#266](https://github.com/RiDDiX/home-assistant-matter-hub/issues/266)
* **basicInformation:** add change detection and reachable check to all devices ([d48c9b6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d48c9b63c658c323dd80cb55f724e087369f66de))
* **binary_sensor:** add support for water leak detector ([2f8707a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2f8707af6a5df1212fe143f804361928591fd5e2)), closes [#48](https://github.com/RiDDiX/home-assistant-matter-hub/issues/48)
* **binary_sensor:** allow defaulting unknown device_classes to OnOffSensor (feature flag) ([fffef29](https://github.com/RiDDiX/home-assistant-matter-hub/commit/fffef29d66b0d8525f18a6757bceaa8db3bb48d8)), closes [#525](https://github.com/RiDDiX/home-assistant-matter-hub/issues/525)
* **cli:** added a config-option to provide a configuration file instead of CLI arguments ([b5325d6](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b5325d6c14fd9a1d289b94bd1275d88732387cae)), closes [#115](https://github.com/RiDDiX/home-assistant-matter-hub/issues/115)
* **cli:** allow explicit whitelisting of ip addresses for http ([dee117e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dee117e2bf3a03bd55657eff8aadb7258c04b486))
* **climate:** add temperature measurement and humidity sensor ([3b44979](https://github.com/RiDDiX/home-assistant-matter-hub/commit/3b44979896bc7c3ddb24e98025499f4de7d7d5d7)), closes [#68](https://github.com/RiDDiX/home-assistant-matter-hub/issues/68) [#96](https://github.com/RiDDiX/home-assistant-matter-hub/issues/96)
* **climate:** add thermostatRunningMode only for autoMode ([c928ca5](https://github.com/RiDDiX/home-assistant-matter-hub/commit/c928ca5c29bc7549969d5ac770151f084c23dbb4)), closes [#68](https://github.com/RiDDiX/home-assistant-matter-hub/issues/68)
* **cover:** allow covers to mimic HA behaviors ([5e2907a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/5e2907a8f4780a8e720a9b830a25babc5c22b58b)), closes [#384](https://github.com/RiDDiX/home-assistant-matter-hub/issues/384) [#297](https://github.com/RiDDiX/home-assistant-matter-hub/issues/297) [#291](https://github.com/RiDDiX/home-assistant-matter-hub/issues/291)
* **cover:** allow tilt feature ([9506263](https://github.com/RiDDiX/home-assistant-matter-hub/commit/95062636f6ed8b89e821e79e03e26533fca3dd25)), closes [#349](https://github.com/RiDDiX/home-assistant-matter-hub/issues/349)
* extracted bridge creation to it's own page, allow editing an existing bridge ([38287af](https://github.com/RiDDiX/home-assistant-matter-hub/commit/38287afebb6205160fb058ed26af0059ddff9bd0)), closes [#7](https://github.com/RiDDiX/home-assistant-matter-hub/issues/7) [#10](https://github.com/RiDDiX/home-assistant-matter-hub/issues/10) [#25](https://github.com/RiDDiX/home-assistant-matter-hub/issues/25)
* **fan-control:** Implement fan control cluster ([#258](https://github.com/RiDDiX/home-assistant-matter-hub/issues/258)) ([20cf2bf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/20cf2bf4e305b779347e04d612989243c1a8c8b7)), closes [#43](https://github.com/RiDDiX/home-assistant-matter-hub/issues/43) [#173](https://github.com/RiDDiX/home-assistant-matter-hub/issues/173) [#250](https://github.com/RiDDiX/home-assistant-matter-hub/issues/250)
* **frontend:** add app logo to header ([f9d8021](https://github.com/RiDDiX/home-assistant-matter-hub/commit/f9d80219cd40e3ae234b09da9e89f34f8ef15e47))
* **frontend:** add details how to connect multiple fabrics ([1b717ac](https://github.com/RiDDiX/home-assistant-matter-hub/commit/1b717ac561e04bbff6aef40880404a6eeda4b125))
* **frontend:** New form-based bridge configuration ([#197](https://github.com/RiDDiX/home-assistant-matter-hub/issues/197)) ([d513357](https://github.com/RiDDiX/home-assistant-matter-hub/commit/d5133573444155b60c8a464d8ecf904449eb845a))
* **frontend:** refactored menu structure ([ab40cbf](https://github.com/RiDDiX/home-assistant-matter-hub/commit/ab40cbf8094181814bba41e8279374c2d88c64bb))
* **frontend:** replace brand icons and add samsung ([b3991e2](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b3991e27b37a722d1431790e30cf22bc8ea3d3fc))
* handle button entity the same way as input_button ([#480](https://github.com/RiDDiX/home-assistant-matter-hub/issues/480)) ([573ad24](https://github.com/RiDDiX/home-assistant-matter-hub/commit/573ad2467792fd429d5d52079a033a06f4b65015)), closes [#341](https://github.com/RiDDiX/home-assistant-matter-hub/issues/341)
* **humidifer:** add support for humidifiers mapped to PlugInUnits ([dd7fe69](https://github.com/RiDDiX/home-assistant-matter-hub/commit/dd7fe69576b5efac4ae06c92512b7c01b149b270)), closes [#100](https://github.com/RiDDiX/home-assistant-matter-hub/issues/100)
* **input_button:** add support for input_button entities ([7b38ad9](https://github.com/RiDDiX/home-assistant-matter-hub/commit/7b38ad9be399782201fa0b24a03ade774c02738f)), closes [#195](https://github.com/RiDDiX/home-assistant-matter-hub/issues/195)
* **light:** add support for RGBW and RGBWW lights ([e66a180](https://github.com/RiDDiX/home-assistant-matter-hub/commit/e66a180027b1cc629dcc146a8f2db617fe31f571)), closes [#514](https://github.com/RiDDiX/home-assistant-matter-hub/issues/514)
* **lights:** in general support color control for all lights having hs_color ([91a269d](https://github.com/RiDDiX/home-assistant-matter-hub/commit/91a269d3e4a797adce81bf56c89f18aff93c85eb)), closes [#415](https://github.com/RiDDiX/home-assistant-matter-hub/issues/415)
* link to new documentation ([4419a90](https://github.com/RiDDiX/home-assistant-matter-hub/commit/4419a90f7a39bbdea90c81c714d543ff6ff60d66))
* **media_player:** add support for media_players as OnOffPluginUnits ([59f081c](https://github.com/RiDDiX/home-assistant-matter-hub/commit/59f081c76e252c4a4ff86669e65d2f0807fb680f)), closes [#57](https://github.com/RiDDiX/home-assistant-matter-hub/issues/57)
* **media_player:** expose media_player as speaker device if feature flag is activated ([#156](https://github.com/RiDDiX/home-assistant-matter-hub/issues/156)) ([b2cd50a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/b2cd50a9a86404375eaa46b07f1c744bac33fb9d))
* **media_player:** source selection, mute and volume fixes ([#363](https://github.com/RiDDiX/home-assistant-matter-hub/issues/363)) ([8858c30](https://github.com/RiDDiX/home-assistant-matter-hub/commit/8858c301e687e1688ff4ae7a09f15af275e3bf21))
* **nx-cloud:** setup nx cloud workspace ([2919527](https://github.com/RiDDiX/home-assistant-matter-hub/commit/2919527b09482e15f69b7bbb1546bbd06c974674))
* pre-build the addon docker image to increase installation speed and reduce backup size ([179f266](https://github.com/RiDDiX/home-assistant-matter-hub/commit/179f2660409972f7c4ecc38ad808f1ec4c83cdba)), closes [#323](https://github.com/RiDDiX/home-assistant-matter-hub/issues/323)
* prepare configurations per domainm, entity and compatibility mode ([cb0b599](https://github.com/RiDDiX/home-assistant-matter-hub/commit/cb0b5999c677895bf5799f5f01a13dc70518ddb3))
* project setup and complete migration ([51301ac](https://github.com/RiDDiX/home-assistant-matter-hub/commit/51301ac33e023925ab25fbaf994f7bb1e30e5e3a))
* **sensor:** Add illuminance sensor type ([#758](https://github.com/RiDDiX/home-assistant-matter-hub/issues/758)) ([67ec42b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/67ec42bcd2e2be06d6ced32bbad60e111c147034))
* show version number in app title ([70bdca8](https://github.com/RiDDiX/home-assistant-matter-hub/commit/70bdca89f98b8ab9afac2da7256f98f7772c9390)), closes [#38](https://github.com/RiDDiX/home-assistant-matter-hub/issues/38)
* Taking a Holiday Break – See You in the New Year! ([86bea0a](https://github.com/RiDDiX/home-assistant-matter-hub/commit/86bea0ae57c7bcf747dec24046aa947bc37aa925))
* use custom homeAssistantBehavior for better state management ([6e0f862](https://github.com/RiDDiX/home-assistant-matter-hub/commit/6e0f86246d4393cd77fcb64b3a40dd6af07c79f1))
* Use device area if available for entities that have no area directly set ([#403](https://github.com/RiDDiX/home-assistant-matter-hub/issues/403)) ([bda867e](https://github.com/RiDDiX/home-assistant-matter-hub/commit/bda867e11f53e605d652269af4792f3266b8867e))
* **vacuum:** add basic support for vacuums (RVC) ([9021b7b](https://github.com/RiDDiX/home-assistant-matter-hub/commit/9021b7bc579535cb59f3cc832f2fce438c986f54))


### BREAKING CHANGES

* This could affect some sensors like water leak or occupancy. Make sure to verify your automations in Alexa, Apple Home, Google Home and others.
* MAINTAINER WANTED! This project is currently **looking for a new maintainer**. Due to limited time, I can no longer actively maintain it. If you are interested in taking over or co-maintaining, please reach out via GitHub Discussions (#825).
* Due to the growing code base and its complexity, I've decided to simplify the application by removing non-compliant workarounds.
* Almost every aspect of the device implementations were touched. I've tried to test as much as possible locally until everything was back working. But since there are so many edge cases in different devices, I probably couldn't verify everything.
* **basic-information-server:** It can happen, that your controller (Alexa, Google Home, etc.) doesn't match your existing devices and re-pairs all of them. In that case, you'll need to assign the devices to rooms and automations again.
* As the holiday season approaches and my main job keeps me busy, I haven’t been able to dedicate as much time to this project as I’d like. Over the holidays, I’ll be taking a well-deserved break to recharge. That said, if an opportunity arises, I’ll try to answer a few questions or review a pull request via my phone. I’m looking forward to returning refreshed and motivated in the new year. Thank you for your understanding and continued support! Happy holidays!
* **thermostat:** Auto mode from Home Assistant is no longer supported for climates / thermostats. It just doesn't fit into the Matter specification.
Instead, Heat/Cool from Home Assistant is mapped to AutoMode in Matter.
I tried to test as much as possible, but since I don't have any physical climate I needed to use GenericThermostat and BetterThermostat to make virtual climates.
My testings were therefore limited to simple tests with simple climates. This change could break existing behaviors.
Please provide feedback what is working as expected, and what isn't (https://github.com/t0bst4r/home-assistant-matter-hub/discussions/261).
* The native addon (HAOS) will use Home Assistant ingress from now on. Direct access via the port will no longer be possible.
