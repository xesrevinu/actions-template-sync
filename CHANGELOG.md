# Changelog

## [3.1.0](https://github.com/xesrevinu/actions-template-sync/compare/v3.0.0...v3.1.0) (2024-10-10)


### Features

* fix input ([9d6fafe](https://github.com/xesrevinu/actions-template-sync/commit/9d6fafeb65e0723124361a041e6ccb502ca973e0))

## [3.0.0](https://github.com/xesrevinu/actions-template-sync/compare/v2.2.3...v3.0.0) (2024-10-10)


### ⚠ BREAKING CHANGES

* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/xesrevinu/actions-template-sync/issues/498))

### Features

* :construction_worker: ([#432](https://github.com/xesrevinu/actions-template-sync/issues/432)) support major/minor tags ([#433](https://github.com/xesrevinu/actions-template-sync/issues/433)) ([eb942cf](https://github.com/xesrevinu/actions-template-sync/commit/eb942cf9366ff4cfbcb6860f9392db555a4e5c11))
* :rocket: ([#328](https://github.com/xesrevinu/actions-template-sync/issues/328) [#316](https://github.com/xesrevinu/actions-template-sync/issues/316)) add params for git user.name, user.email a… ([#330](https://github.com/xesrevinu/actions-template-sync/issues/330)) ([6038fdf](https://github.com/xesrevinu/actions-template-sync/commit/6038fdfeb863b03c9c451ae039347fbeb1b7a3e4))
* :sparkles: ([#204](https://github.com/xesrevinu/actions-template-sync/issues/204)) gpg sign ([#436](https://github.com/xesrevinu/actions-template-sync/issues/436)) ([99aefe5](https://github.com/xesrevinu/actions-template-sync/commit/99aefe5830f9ee249bbfbd90a85108f76e897c33))
* :sparkles: ([#401](https://github.com/xesrevinu/actions-template-sync/issues/401)) add option to force file deletion ([#435](https://github.com/xesrevinu/actions-template-sync/issues/435)) ([e68941f](https://github.com/xesrevinu/actions-template-sync/commit/e68941ff0fc9695be3fe480ab739ebeb318dca0d))
* :sparkles: gpg sign with passphrase ([#460](https://github.com/xesrevinu/actions-template-sync/issues/460)) ([cec582e](https://github.com/xesrevinu/actions-template-sync/commit/cec582ee2fc98db86d2cb5335a33a2fdaa59f418))
* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/xesrevinu/actions-template-sync/issues/498)) ([29d0434](https://github.com/xesrevinu/actions-template-sync/commit/29d04342d0bd6047538dd7f52a7e64a8ca2d4baa))
* :sparkles: Set token to the default provided by GitHub workflow ([#483](https://github.com/xesrevinu/actions-template-sync/issues/483)) ([c1e7561](https://github.com/xesrevinu/actions-template-sync/commit/c1e756148de0343df66fda1a2380382ef06c16d7))
* **#467:** :sparkles: hooks now within action inputs ([#489](https://github.com/xesrevinu/actions-template-sync/issues/489)) ([0e55c08](https://github.com/xesrevinu/actions-template-sync/commit/0e55c08f95f9a83c60f809fa6b49785187ec7623))
* **#468:** :sparkles: enable usage of github env variables within hooks ([#469](https://github.com/xesrevinu/actions-template-sync/issues/469)) ([17d4603](https://github.com/xesrevinu/actions-template-sync/commit/17d4603da56b49e4b72c6531ba6d2db6dbcc3a31))
* **#472:** :sparkles: define output ([#473](https://github.com/xesrevinu/actions-template-sync/issues/473)) ([a19cd8d](https://github.com/xesrevinu/actions-template-sync/commit/a19cd8d7c999cdf9bdc2a08818eb2878d1222cdf))
* **#477:** :sparkles: add input parameter for pr body ([#488](https://github.com/xesrevinu/actions-template-sync/issues/488)) ([481cc21](https://github.com/xesrevinu/actions-template-sync/commit/481cc21550d858dfc12c49f4dfb7605ac744a091))
* **#478:** :sparkles: possible to execute single steps ([#516](https://github.com/xesrevinu/actions-template-sync/issues/516)) ([6b9bd88](https://github.com/xesrevinu/actions-template-sync/commit/6b9bd8844d2a75ecf2f4d2688b7f847fd86cffa3))
* **#482:** :sparkles: add option to force push and pr ([#499](https://github.com/xesrevinu/actions-template-sync/issues/499)) ([cbef7ee](https://github.com/xesrevinu/actions-template-sync/commit/cbef7ee63378db46e59d89a09c055376dccf4817))
* **#523:** :sparkles: delete branches on pr cleanup ([#525](https://github.com/xesrevinu/actions-template-sync/issues/525)) ([d957348](https://github.com/xesrevinu/actions-template-sync/commit/d9573484779def3582a6d442502aaa69eaf674e9))
* ability to add reviewers for pull requests ([#362](https://github.com/xesrevinu/actions-template-sync/issues/362)) ([964b161](https://github.com/xesrevinu/actions-template-sync/commit/964b16174a24d517420640c0e81466c93491c147))
* **action:** add parameter for gh action configuration ([#129](https://github.com/xesrevinu/actions-template-sync/issues/129)) :rocket: ([55484dc](https://github.com/xesrevinu/actions-template-sync/commit/55484dc36dd0cc1313d4d946194463955a2f4be1))
* add configurable PR title and branch prefix ([2d80a8a](https://github.com/xesrevinu/actions-template-sync/commit/2d80a8a1a9f77ac171908181acc909f54554ac6a))
* allow for pruning of older PRs ([#438](https://github.com/xesrevinu/actions-template-sync/issues/438)) ([0e51714](https://github.com/xesrevinu/actions-template-sync/commit/0e51714bd42e4ce8223a641d7435c220a99aad51))
* config files inside .GitHub folder ([#252](https://github.com/xesrevinu/actions-template-sync/issues/252)) ([8aa35f1](https://github.com/xesrevinu/actions-template-sync/commit/8aa35f14a22f32995bb4822c3822dfcd5c03b082))
* **docker:** push image to registries ([7e8787a](https://github.com/xesrevinu/actions-template-sync/commit/7e8787a6f4b693bde965ec9a1a62f62cb430c980))
* **docker:** push image to registries ([93d70a3](https://github.com/xesrevinu/actions-template-sync/commit/93d70a3b9b2c4cdfc11e910e6c3a92b01b294f79))
* **docker:** push image to registries :rocket: ([5bab502](https://github.com/xesrevinu/actions-template-sync/commit/5bab50211ab29a634a5ab96bffb3acc766fbceb6))
* **docker:** push image to registries :rocket: ([8310801](https://github.com/xesrevinu/actions-template-sync/commit/83108019523c1167e23d10086ab2d59835be0fe1))
* **docker:** push image to registries :rocket: ([a54c0ff](https://github.com/xesrevinu/actions-template-sync/commit/a54c0ffc5048ff186e3ee51cc2c97fbb98cb5615))
* **docker:** push image to registries :rocket: ([f88b658](https://github.com/xesrevinu/actions-template-sync/commit/f88b6587706e90e8dbbbe937997db9ad70f34114))
* **docker:** push image to registries :rocket: ([5f162c8](https://github.com/xesrevinu/actions-template-sync/commit/5f162c8c9e194d90828379c5b68a90e22227862f))
* **gh-auth:** add gh auth login and credential helper ([#239](https://github.com/xesrevinu/actions-template-sync/issues/239)) ([7a33121](https://github.com/xesrevinu/actions-template-sync/commit/7a33121add81c181094cdb290a4cc9bf654c918d))
* **hooks:** added precommit hook ([#439](https://github.com/xesrevinu/actions-template-sync/issues/439)) ([4a42410](https://github.com/xesrevinu/actions-template-sync/commit/4a42410a3c63b359844b20860359bc2f8ab4e6fa))
* **hostname:** add hostname :rocket: ([cb89c88](https://github.com/xesrevinu/actions-template-sync/commit/cb89c8896a58539de04d1ba46100e69fc3e08145))
* make commit msg configurable ([#237](https://github.com/xesrevinu/actions-template-sync/issues/237)) ([764e725](https://github.com/xesrevinu/actions-template-sync/commit/764e7250dac337e260c8f28aba63da9da2016b45))
* **self:** add self as action template :rocket: ([80f10a5](https://github.com/xesrevinu/actions-template-sync/commit/80f10a55914de3a35749a783c8d8ef4bb567c4c8))
* Use GITHUB_TOKEN for PR operations ([c2751f4](https://github.com/xesrevinu/actions-template-sync/commit/c2751f4ef4469d53982dbadef996bd2a018b6740))


### Bug Fixes

* :bug: ([#375](https://github.com/xesrevinu/actions-template-sync/issues/375)) fix edge case with .templatesyncignore ([#378](https://github.com/xesrevinu/actions-template-sync/issues/378)) ([1eede30](https://github.com/xesrevinu/actions-template-sync/commit/1eede30772357d6984d1757753a672da4119d356))
* :bug: ([#380](https://github.com/xesrevinu/actions-template-sync/issues/380)) small fix related to remote file mode changes ([#383](https://github.com/xesrevinu/actions-template-sync/issues/383)) ([ff25f8c](https://github.com/xesrevinu/actions-template-sync/commit/ff25f8cbcd237716eeff23dc5616632c7663e99f))
* :bug: fix condition ([5563bf1](https://github.com/xesrevinu/actions-template-sync/commit/5563bf1b748efd19b411f4a8f0ac9dc12693dd41))
* :bug: run of workflows in forked repos ([#312](https://github.com/xesrevinu/actions-template-sync/issues/312)) ([#313](https://github.com/xesrevinu/actions-template-sync/issues/313)) ([53177e2](https://github.com/xesrevinu/actions-template-sync/commit/53177e27db816fcb36efceaf0e1e05956d58cc30))
* :bug: try catch for edge cases ([#465](https://github.com/xesrevinu/actions-template-sync/issues/465)) ([95ce4e4](https://github.com/xesrevinu/actions-template-sync/commit/95ce4e4d5cc72b62970056977256a6592a10547c))
* (lint) fix md lint issue :bug: ([a95853f](https://github.com/xesrevinu/actions-template-sync/commit/a95853fb974d5a41e6268437abb8c549b124a1ba))
* **#461:** :bug: issue with pull request labels with emoji and space ([#462](https://github.com/xesrevinu/actions-template-sync/issues/462)) ([89b8d21](https://github.com/xesrevinu/actions-template-sync/commit/89b8d210b8454957a81dbbf5b81e6977708a25cd))
* **#476:** :bug: output variable edge cases ([#479](https://github.com/xesrevinu/actions-template-sync/issues/479)) ([ab4153b](https://github.com/xesrevinu/actions-template-sync/commit/ab4153bb937a2d7ad996f0693977cb943443e8b3))
* **#507:** :bug: pr title and body internal variable substitution ([#508](https://github.com/xesrevinu/actions-template-sync/issues/508)) ([912b4e0](https://github.com/xesrevinu/actions-template-sync/commit/912b4e01a39729b00a1f928303f864294d6cbede))
* **#510:** :bug: issue with blank lines within .templatesyncignore ([#512](https://github.com/xesrevinu/actions-template-sync/issues/512)) ([814f456](https://github.com/xesrevinu/actions-template-sync/commit/814f4564aa1ce6d354dcf48a34ea5b7a670327a5))
* **#528:** :memo: small docs update ([4eb71ce](https://github.com/xesrevinu/actions-template-sync/commit/4eb71ce2acda4476ed387a8b42cd94846ca8474e))
* **#529:** :bug: edge case with branch cleanup and force push ([#534](https://github.com/xesrevinu/actions-template-sync/issues/534)) ([ab9498f](https://github.com/xesrevinu/actions-template-sync/commit/ab9498f63d0cf03e677228c6a2f6828adf8b4662))
* **#536:** :bug: issue with comments within .templatesyncignore ([#538](https://github.com/xesrevinu/actions-template-sync/issues/538)) ([aba0971](https://github.com/xesrevinu/actions-template-sync/commit/aba0971640d113cd858cfbb6b9eb2f4c2de09049))
* checkout action using a github pat ([#358](https://github.com/xesrevinu/actions-template-sync/issues/358)) ([9e4223d](https://github.com/xesrevinu/actions-template-sync/commit/9e4223d7a38b5c32d29100ad5b59fe5154f9ab2f))
* **ci:** :bug:  ([#388](https://github.com/xesrevinu/actions-template-sync/issues/388)) issues within ci ([8649015](https://github.com/xesrevinu/actions-template-sync/commit/8649015f18ab9855f8d3b93c50d67444438bb14f))
* **ci:** :bug:  ([#388](https://github.com/xesrevinu/actions-template-sync/issues/388)) issues within ci ([dd57314](https://github.com/xesrevinu/actions-template-sync/commit/dd573140ec37a0e41ff179af7d9954a049c9eb93))
* **ci:** :bug:  ([#388](https://github.com/xesrevinu/actions-template-sync/issues/388)) issues within ci ([e063b29](https://github.com/xesrevinu/actions-template-sync/commit/e063b29c03ebb93b4185b752f4d8dc61db3605df))
* **ci:** :bug: ([#387](https://github.com/xesrevinu/actions-template-sync/issues/387)) issue with docker push ([#392](https://github.com/xesrevinu/actions-template-sync/issues/392)) ([a94785c](https://github.com/xesrevinu/actions-template-sync/commit/a94785c1d4150fac0168410757004e83f638caf1))
* **ci:** :bug: issues within ci ([2793a56](https://github.com/xesrevinu/actions-template-sync/commit/2793a56cecdd0000c25e0a81972d78a45fbb4d97))
* **config:** fix pr_labels -&gt; now complete optional ([#207](https://github.com/xesrevinu/actions-template-sync/issues/207)) :rocket: ([f9de1ad](https://github.com/xesrevinu/actions-template-sync/commit/f9de1ad1421d68ac4ec10cd6b9a8963cfa6e81b5))
* **cve:** ([#168](https://github.com/xesrevinu/actions-template-sync/issues/168)) fix bug related to CVE-2022-24765 :lock: ([e231a7b](https://github.com/xesrevinu/actions-template-sync/commit/e231a7b1e54f1fc1ad9244bb83b6983fd76ab919))
* **cve:** fix bug related to CVE-2022-24765 :lock: ([6a6128f](https://github.com/xesrevinu/actions-template-sync/commit/6a6128fd209f833bd6e6c28944d152668a701ac8))
* **divergent_branches:** ([#142](https://github.com/xesrevinu/actions-template-sync/issues/142)) fix issue with divergent branches :bug: ([40d1558](https://github.com/xesrevinu/actions-template-sync/commit/40d1558936bc53edf8e689a20e46e866b135b9ec))
* **docs:** :bug: ([#387](https://github.com/xesrevinu/actions-template-sync/issues/387)) fix missing documentation about .templatesyncignore paths ([3130f5b](https://github.com/xesrevinu/actions-template-sync/commit/3130f5bc62a6f98ece2c209994283520fe3ca811))
* github pat in documentation examples ([#423](https://github.com/xesrevinu/actions-template-sync/issues/423)) ([aea6128](https://github.com/xesrevinu/actions-template-sync/commit/aea6128ca5ae7e21f7ba687ead3f56326cce1b76))
* quote PR title ([bcf13f1](https://github.com/xesrevinu/actions-template-sync/commit/bcf13f16e35f689c001e63d94303189dfabb78a6))
* **sync-template:** fix issue with .templatesyncignore conflicts ([#251](https://github.com/xesrevinu/actions-template-sync/issues/251)) ([dd6bb2c](https://github.com/xesrevinu/actions-template-sync/commit/dd6bb2c1ff98261bbd48933ba3b776b555801953))
* **sync-template:** IF order ([#269](https://github.com/xesrevinu/actions-template-sync/issues/269)) ([00e2f35](https://github.com/xesrevinu/actions-template-sync/commit/00e2f35f579355b6a06d6cc6f2778da5c9a1673e))
* **sync-template:** typo in TEMPLATE_SYNC_IGNORE_FILE_PATH variables ([#268](https://github.com/xesrevinu/actions-template-sync/issues/268)) ([67b630b](https://github.com/xesrevinu/actions-template-sync/commit/67b630b03e20241b950f85a4832d49b7cadf8c18))

## [2.2.3](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.2...v2.2.3) (2024-06-19)


### Bug Fixes

* **#536:** :bug: issue with comments within .templatesyncignore ([#538](https://github.com/AndreasAugustin/actions-template-sync/issues/538)) ([aba0971](https://github.com/AndreasAugustin/actions-template-sync/commit/aba0971640d113cd858cfbb6b9eb2f4c2de09049))

## [2.2.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.1...v2.2.2) (2024-06-16)


### Bug Fixes

* **#529:** :bug: edge case with branch cleanup and force push ([#534](https://github.com/AndreasAugustin/actions-template-sync/issues/534)) ([ab9498f](https://github.com/AndreasAugustin/actions-template-sync/commit/ab9498f63d0cf03e677228c6a2f6828adf8b4662))

## [2.2.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.2.0...v2.2.1) (2024-06-06)


### Bug Fixes

* **#528:** :memo: small docs update ([4eb71ce](https://github.com/AndreasAugustin/actions-template-sync/commit/4eb71ce2acda4476ed387a8b42cd94846ca8474e))

## [2.2.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.1.0...v2.2.0) (2024-05-27)


### Features

* **#523:** :sparkles: delete branches on pr cleanup ([#525](https://github.com/AndreasAugustin/actions-template-sync/issues/525)) ([d957348](https://github.com/AndreasAugustin/actions-template-sync/commit/d9573484779def3582a6d442502aaa69eaf674e9))

## [2.1.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.2...v2.1.0) (2024-04-23)


### Features

* **#478:** :sparkles: possible to execute single steps ([#516](https://github.com/AndreasAugustin/actions-template-sync/issues/516)) ([6b9bd88](https://github.com/AndreasAugustin/actions-template-sync/commit/6b9bd8844d2a75ecf2f4d2688b7f847fd86cffa3))

## [2.0.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.1...v2.0.2) (2024-03-28)


### Bug Fixes

* **#510:** :bug: issue with blank lines within .templatesyncignore ([#512](https://github.com/AndreasAugustin/actions-template-sync/issues/512)) ([814f456](https://github.com/AndreasAugustin/actions-template-sync/commit/814f4564aa1ce6d354dcf48a34ea5b7a670327a5))

## [2.0.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v2.0.0...v2.0.1) (2024-03-18)


### Bug Fixes

* **#507:** :bug: pr title and body internal variable substitution ([#508](https://github.com/AndreasAugustin/actions-template-sync/issues/508)) ([912b4e0](https://github.com/AndreasAugustin/actions-template-sync/commit/912b4e01a39729b00a1f928303f864294d6cbede))

## [2.0.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.12.0...v2.0.0) (2024-03-13)


### ⚠ BREAKING CHANGES

* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/AndreasAugustin/actions-template-sync/issues/498))

### Features

* :sparkles: migrate from docker action to composite action  ([#498](https://github.com/AndreasAugustin/actions-template-sync/issues/498)) ([29d0434](https://github.com/AndreasAugustin/actions-template-sync/commit/29d04342d0bd6047538dd7f52a7e64a8ca2d4baa))

## [1.12.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.11.0...v1.12.0) (2024-03-13)


### Features

* **#482:** :sparkles: add option to force push and pr ([#499](https://github.com/AndreasAugustin/actions-template-sync/issues/499)) ([cbef7ee](https://github.com/AndreasAugustin/actions-template-sync/commit/cbef7ee63378db46e59d89a09c055376dccf4817))

## [1.11.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.10.0...v1.11.0) (2024-03-11)


### Features

* :sparkles: gpg sign with passphrase ([#460](https://github.com/AndreasAugustin/actions-template-sync/issues/460)) ([cec582e](https://github.com/AndreasAugustin/actions-template-sync/commit/cec582ee2fc98db86d2cb5335a33a2fdaa59f418))

## [1.10.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.9.0...v1.10.0) (2024-03-05)


### Features

* **#467:** :sparkles: hooks now within action inputs ([#489](https://github.com/AndreasAugustin/actions-template-sync/issues/489)) ([0e55c08](https://github.com/AndreasAugustin/actions-template-sync/commit/0e55c08f95f9a83c60f809fa6b49785187ec7623))

## [1.9.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.8.1...v1.9.0) (2024-03-05)


### Features

* :sparkles: Set token to the default provided by GitHub workflow ([#483](https://github.com/AndreasAugustin/actions-template-sync/issues/483)) ([c1e7561](https://github.com/AndreasAugustin/actions-template-sync/commit/c1e756148de0343df66fda1a2380382ef06c16d7))
* **#477:** :sparkles: add input parameter for pr body ([#488](https://github.com/AndreasAugustin/actions-template-sync/issues/488)) ([481cc21](https://github.com/AndreasAugustin/actions-template-sync/commit/481cc21550d858dfc12c49f4dfb7605ac744a091))

## [1.8.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.8.0...v1.8.1) (2024-03-02)


### Bug Fixes

* **#476:** :bug: output variable edge cases ([#479](https://github.com/AndreasAugustin/actions-template-sync/issues/479)) ([ab4153b](https://github.com/AndreasAugustin/actions-template-sync/commit/ab4153bb937a2d7ad996f0693977cb943443e8b3))

## [1.8.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.7.0...v1.8.0) (2024-02-29)


### Features

* **#472:** :sparkles: define output ([#473](https://github.com/AndreasAugustin/actions-template-sync/issues/473)) ([a19cd8d](https://github.com/AndreasAugustin/actions-template-sync/commit/a19cd8d7c999cdf9bdc2a08818eb2878d1222cdf))

## [1.7.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.2...v1.7.0) (2024-02-29)


### Features

* **#468:** :sparkles: enable usage of github env variables within hooks ([#469](https://github.com/AndreasAugustin/actions-template-sync/issues/469)) ([17d4603](https://github.com/AndreasAugustin/actions-template-sync/commit/17d4603da56b49e4b72c6531ba6d2db6dbcc3a31))

## [1.6.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.1...v1.6.2) (2024-02-25)


### Bug Fixes

* :bug: try catch for edge cases ([#465](https://github.com/AndreasAugustin/actions-template-sync/issues/465)) ([95ce4e4](https://github.com/AndreasAugustin/actions-template-sync/commit/95ce4e4d5cc72b62970056977256a6592a10547c))

## [1.6.1](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.6.0...v1.6.1) (2024-02-25)


### Bug Fixes

* **#461:** :bug: issue with pull request labels with emoji and space ([#462](https://github.com/AndreasAugustin/actions-template-sync/issues/462)) ([89b8d21](https://github.com/AndreasAugustin/actions-template-sync/commit/89b8d210b8454957a81dbbf5b81e6977708a25cd))

## [1.6.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.5.0...v1.6.0) (2024-02-22)


### Features

* :sparkles: ([#204](https://github.com/AndreasAugustin/actions-template-sync/issues/204)) gpg sign ([#436](https://github.com/AndreasAugustin/actions-template-sync/issues/436)) ([99aefe5](https://github.com/AndreasAugustin/actions-template-sync/commit/99aefe5830f9ee249bbfbd90a85108f76e897c33))

## [1.5.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.4.0...v1.5.0) (2024-02-04)


### Features

* :sparkles: ([#401](https://github.com/AndreasAugustin/actions-template-sync/issues/401)) add option to force file deletion ([#435](https://github.com/AndreasAugustin/actions-template-sync/issues/435)) ([e68941f](https://github.com/AndreasAugustin/actions-template-sync/commit/e68941ff0fc9695be3fe480ab739ebeb318dca0d))

## [1.4.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.3.0...v1.4.0) (2024-01-25)


### Features

* allow for pruning of older PRs ([#438](https://github.com/AndreasAugustin/actions-template-sync/issues/438)) ([0e51714](https://github.com/AndreasAugustin/actions-template-sync/commit/0e51714bd42e4ce8223a641d7435c220a99aad51))

## [1.3.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.2.0...v1.3.0) (2024-01-18)


### Features

* **hooks:** added precommit hook ([#439](https://github.com/AndreasAugustin/actions-template-sync/issues/439)) ([4a42410](https://github.com/AndreasAugustin/actions-template-sync/commit/4a42410a3c63b359844b20860359bc2f8ab4e6fa))

## [1.2.0](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.9...v1.2.0) (2024-01-06)


### Features

* :construction_worker: ([#432](https://github.com/AndreasAugustin/actions-template-sync/issues/432)) support major/minor tags ([#433](https://github.com/AndreasAugustin/actions-template-sync/issues/433)) ([eb942cf](https://github.com/AndreasAugustin/actions-template-sync/commit/eb942cf9366ff4cfbcb6860f9392db555a4e5c11))

## [1.1.9](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.8...v1.1.9) (2023-12-30)


### Bug Fixes

* github pat in documentation examples ([#423](https://github.com/AndreasAugustin/actions-template-sync/issues/423)) ([aea6128](https://github.com/AndreasAugustin/actions-template-sync/commit/aea6128ca5ae7e21f7ba687ead3f56326cce1b76))

## [1.1.8](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.7...v1.1.8) (2023-09-24)


### Bug Fixes

* **ci:** :bug: issues within ci ([2793a56](https://github.com/AndreasAugustin/actions-template-sync/commit/2793a56cecdd0000c25e0a81972d78a45fbb4d97))

## [1.1.7](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.6...v1.1.7) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([8649015](https://github.com/AndreasAugustin/actions-template-sync/commit/8649015f18ab9855f8d3b93c50d67444438bb14f))

## [1.1.6](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.5...v1.1.6) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([dd57314](https://github.com/AndreasAugustin/actions-template-sync/commit/dd573140ec37a0e41ff179af7d9954a049c9eb93))

## [1.1.5](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.4...v1.1.5) (2023-09-24)


### Bug Fixes

* **ci:** :bug:  ([#388](https://github.com/AndreasAugustin/actions-template-sync/issues/388)) issues within ci ([e063b29](https://github.com/AndreasAugustin/actions-template-sync/commit/e063b29c03ebb93b4185b752f4d8dc61db3605df))
* **ci:** :bug: ([#387](https://github.com/AndreasAugustin/actions-template-sync/issues/387)) issue with docker push ([#392](https://github.com/AndreasAugustin/actions-template-sync/issues/392)) ([a94785c](https://github.com/AndreasAugustin/actions-template-sync/commit/a94785c1d4150fac0168410757004e83f638caf1))

## [1.1.4](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.3...v1.1.4) (2023-09-24)


### Bug Fixes

* **docs:** :bug: ([#387](https://github.com/AndreasAugustin/actions-template-sync/issues/387)) fix missing documentation about .templatesyncignore paths ([3130f5b](https://github.com/AndreasAugustin/actions-template-sync/commit/3130f5bc62a6f98ece2c209994283520fe3ca811))

## [1.1.3](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.2...v1.1.3) (2023-09-16)


### Bug Fixes

* :bug: ([#380](https://github.com/AndreasAugustin/actions-template-sync/issues/380)) small fix related to remote file mode changes ([#383](https://github.com/AndreasAugustin/actions-template-sync/issues/383)) ([ff25f8c](https://github.com/AndreasAugustin/actions-template-sync/commit/ff25f8cbcd237716eeff23dc5616632c7663e99f))

## [1.1.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.1...v1.1.2) (2023-09-03)


### Bug Fixes

* :bug: ([#375](https://github.com/AndreasAugustin/actions-template-sync/issues/375)) fix edge case with .templatesyncignore ([#378](https://github.com/AndreasAugustin/actions-template-sync/issues/378)) ([1eede30](https://github.com/AndreasAugustin/actions-template-sync/commit/1eede30772357d6984d1757753a672da4119d356))
