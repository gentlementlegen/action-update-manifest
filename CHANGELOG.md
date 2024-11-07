# Changelog

## [1.2.0](https://github.com/gentlementlegen/action-update-manifest/compare/v1.1.2...v1.2.0) (2024-11-07)


### Features

* add CODEOWNERS and enhance README.md ([24a312d](https://github.com/gentlementlegen/action-update-manifest/commit/24a312dc56c4b27fb22d88d75f21d2c9f570358a))
* add GitHub packages to action setup ([5eb45f9](https://github.com/gentlementlegen/action-update-manifest/commit/5eb45f9a0a4b14b9ce79f135b56e7679f1392c1c))
* switched bundling to `bun` ([970c018](https://github.com/gentlementlegen/action-update-manifest/commit/970c0185775b9ccfd7ae0cfb07b52ff62d78f5b7))


### Bug Fixes

* **action:** refactor manifest update to use async/await ([90e7386](https://github.com/gentlementlegen/action-update-manifest/commit/90e7386d82f05a6f3f6575ca862a76507fefd352))
* add ESM support by replacing __dirname ([b722932](https://github.com/gentlementlegen/action-update-manifest/commit/b7229322141033319fd4a872e56f2cfa7cfc59b4))
* adding all generated files ([f11d086](https://github.com/gentlementlegen/action-update-manifest/commit/f11d08692dbc7939f796383fa09fdd26ac7b87ce))
* adding sourcemap option ([4bf048d](https://github.com/gentlementlegen/action-update-manifest/commit/4bf048d6f4307c9f45ddbf1efbd7403ff49c538b))
* call updateManifest function in action.yml ([5fac319](https://github.com/gentlementlegen/action-update-manifest/commit/5fac3191264c7f374d594adf0dd38eb40393d4d2))
* command should run on linux env ([0bcd69a](https://github.com/gentlementlegen/action-update-manifest/commit/0bcd69aadb7150f82eb59d3310d5b216aa3a6b68))
* correct file addition logic in action.yml ([9690d25](https://github.com/gentlementlegen/action-update-manifest/commit/9690d25cf6f581b02f9b4ada6e76da993b8f2c3f))
* correct order of ncc build command options ([0bf5f26](https://github.com/gentlementlegen/action-update-manifest/commit/0bf5f26061de4aaca91924fc4d5b2a7fa0387a5b))
* correct path for dist file in git tree ([789e396](https://github.com/gentlementlegen/action-update-manifest/commit/789e39659da2824c177131f0181b87083270b1fd))
* handle ESM and CJS module loading in action script ([33147cc](https://github.com/gentlementlegen/action-update-manifest/commit/33147cc8721f94c42a1ecb3834217a61cbf75f3a))
* handle schema defaults and required fields correctly ([dc46486](https://github.com/gentlementlegen/action-update-manifest/commit/dc46486a0922f243c34a827b6db36556b1bc0a87))
* minify option ([2d41331](https://github.com/gentlementlegen/action-update-manifest/commit/2d413310d0779ec724a0e13d3b45ac9a5a962313))
* properly adding map files ([5d00ef5](https://github.com/gentlementlegen/action-update-manifest/commit/5d00ef5dafcc1b50dae6dd02ff0973ff17c65c9a))
* properly retrieve js file list ([ec553da](https://github.com/gentlementlegen/action-update-manifest/commit/ec553daba7f70fc61befc10069523134d3c12a7f))
* remove rebase option during git pull ([ca46e9d](https://github.com/gentlementlegen/action-update-manifest/commit/ca46e9d8a785d6edc250a7f48c6974617bf6bee6))
* rename output file to use .cjs extension ([4860686](https://github.com/gentlementlegen/action-update-manifest/commit/4860686466a97f6d514fa6d88714ca22586c0d07))
* replace async file operations with sync methods ([8e99285](https://github.com/gentlementlegen/action-update-manifest/commit/8e992851f2586567bf2180ae5f5a59f3266b8dc2))
* switch to bash script for pushing changes ([876b39b](https://github.com/gentlementlegen/action-update-manifest/commit/876b39b76dbfdb68dd27f773c1ab7d4a5c7e029c))
* switch to Octokit for commit and push ([45f54ee](https://github.com/gentlementlegen/action-update-manifest/commit/45f54eecb4ebda5eb8b0695e7e3d5b1b774e82d1))
* update bot email to use GitHub noreply address ([2c48b0c](https://github.com/gentlementlegen/action-update-manifest/commit/2c48b0ccb66cd14d8e22e3072e868ae4390e737e))
* update default schema path to use .cjs extension ([d650040](https://github.com/gentlementlegen/action-update-manifest/commit/d650040c3cfd7178c69ac48e5bc9a0a548cde791))
* update schema and plugin path extensions, remove ts compilation ([086a914](https://github.com/gentlementlegen/action-update-manifest/commit/086a9147e9b8ca942e8467ee6a02a1ab52a4cf8f))
* update schema and plugin path extensions, remove ts compilation ([6c4202b](https://github.com/gentlementlegen/action-update-manifest/commit/6c4202beb4cf0adce32ae8732b2566e5444648a2))

## [1.1.2](https://github.com/ubiquity-os/action-deploy-plugin/compare/v1.1.1...v1.1.2) (2024-10-22)


### Bug Fixes

* **action:** refactor manifest update to use async/await ([90e7386](https://github.com/ubiquity-os/action-deploy-plugin/commit/90e7386d82f05a6f3f6575ca862a76507fefd352))
* call updateManifest function in action.yml ([5fac319](https://github.com/ubiquity-os/action-deploy-plugin/commit/5fac3191264c7f374d594adf0dd38eb40393d4d2))
* handle ESM and CJS module loading in action script ([33147cc](https://github.com/ubiquity-os/action-deploy-plugin/commit/33147cc8721f94c42a1ecb3834217a61cbf75f3a))
* rename output file to use .cjs extension ([4860686](https://github.com/ubiquity-os/action-deploy-plugin/commit/4860686466a97f6d514fa6d88714ca22586c0d07))
* replace async file operations with sync methods ([8e99285](https://github.com/ubiquity-os/action-deploy-plugin/commit/8e992851f2586567bf2180ae5f5a59f3266b8dc2))
* switch to bash script for pushing changes ([876b39b](https://github.com/ubiquity-os/action-deploy-plugin/commit/876b39b76dbfdb68dd27f773c1ab7d4a5c7e029c))
* update schema and plugin path extensions, remove ts compilation ([086a914](https://github.com/ubiquity-os/action-deploy-plugin/commit/086a9147e9b8ca942e8467ee6a02a1ab52a4cf8f))
* update schema and plugin path extensions, remove ts compilation ([6c4202b](https://github.com/ubiquity-os/action-deploy-plugin/commit/6c4202beb4cf0adce32ae8732b2566e5444648a2))

## [1.1.1](https://github.com/ubiquity-os/action-deploy-plugin/compare/v1.1.0...v1.1.1) (2024-10-15)


### Bug Fixes

* handle schema defaults and required fields correctly ([dc46486](https://github.com/ubiquity-os/action-deploy-plugin/commit/dc46486a0922f243c34a827b6db36556b1bc0a87))

## [1.1.0](https://github.com/ubiquity-os/action-deploy-plugin/compare/v1.0.0...v1.1.0) (2024-10-15)


### Features

* add GitHub packages to action setup ([5eb45f9](https://github.com/ubiquity-os/action-deploy-plugin/commit/5eb45f9a0a4b14b9ce79f135b56e7679f1392c1c))


### Bug Fixes

* switch to Octokit for commit and push ([45f54ee](https://github.com/ubiquity-os/action-deploy-plugin/commit/45f54eecb4ebda5eb8b0695e7e3d5b1b774e82d1))
* update default schema path to use .cjs extension ([d650040](https://github.com/ubiquity-os/action-deploy-plugin/commit/d650040c3cfd7178c69ac48e5bc9a0a548cde791))

## 1.0.0 (2024-10-10)


### Features

* add CODEOWNERS and enhance README.md ([24a312d](https://github.com/ubiquity-os/action-deploy-plugin/commit/24a312dc56c4b27fb22d88d75f21d2c9f570358a))


### Bug Fixes

* correct order of ncc build command options ([0bf5f26](https://github.com/ubiquity-os/action-deploy-plugin/commit/0bf5f26061de4aaca91924fc4d5b2a7fa0387a5b))
* remove rebase option during git pull ([ca46e9d](https://github.com/ubiquity-os/action-deploy-plugin/commit/ca46e9d8a785d6edc250a7f48c6974617bf6bee6))
* update bot email to use GitHub noreply address ([2c48b0c](https://github.com/ubiquity-os/action-deploy-plugin/commit/2c48b0ccb66cd14d8e22e3072e868ae4390e737e))
