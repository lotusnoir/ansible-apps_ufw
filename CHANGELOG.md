# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/3.1.0...3.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`94bcd23`](https://github.com/lotusnoir/ansible-apps_ufw/commit/94bcd23daa8ba143ad37531204447e367fa964f4)

## [3.1.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/3.0.0...3.1.0) - 2025-11-17

### Commits

- update core and molecule [`e8e82fd`](https://github.com/lotusnoir/ansible-apps_ufw/commit/e8e82fd691ba42e4a1f39783eb2da2e7ac17a15f)
- add oraclelinux10 support + lint and core fixes [`6d68af4`](https://github.com/lotusnoir/ansible-apps_ufw/commit/6d68af4c707fd88c1fec7d2f7ac519d12b5b54c6)

## [3.0.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/2.1.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`8c65363`](https://github.com/lotusnoir/ansible-apps_ufw/commit/8c6536360ae50148fd99a533f8eae66f2ec866a9)
- update core, molecule + gitlab-ci [`727d0b4`](https://github.com/lotusnoir/ansible-apps_ufw/commit/727d0b4b0c68039fc4f8470697d44c1eab824577)
- add support for ubuntu24 [`835651f`](https://github.com/lotusnoir/ansible-apps_ufw/commit/835651fa49f00dcac81b9c7991deed7f966f2084)
- changes on molecule [`c2998a9`](https://github.com/lotusnoir/ansible-apps_ufw/commit/c2998a9cff01998afc79971bd6241391088703b9)
- change start order &gt; to the end [`fdf574e`](https://github.com/lotusnoir/ansible-apps_ufw/commit/fdf574e114a5b4b1126bbd17bb8a1e7c69cb8ed1)
- customize before and after rules [`726d5c2`](https://github.com/lotusnoir/ansible-apps_ufw/commit/726d5c2ffc1afac9b90a7c85bdd8fb10814031e6)
- fix molecule paralelism and little updates [`1ae6e4a`](https://github.com/lotusnoir/ansible-apps_ufw/commit/1ae6e4ac46eb064a3a4bede83d1e35df3f55a73c)

## [2.1.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/2.0.0...2.1.0) - 2025-01-15

### Commits

- add support for ubuntu24 [`cd6fbbb`](https://github.com/lotusnoir/ansible-apps_ufw/commit/cd6fbbb9a95185c993006db8fec20f35fc938d37)
- add version on molecule play image to maintain support on old release [`a287d04`](https://github.com/lotusnoir/ansible-apps_ufw/commit/a287d044b5d2f3445f664cc0644050a87c4c4cbb)
- remove support for debian10 / ubuntu18 / redhat8 [`ea4d589`](https://github.com/lotusnoir/ansible-apps_ufw/commit/ea4d589be0b490a5ee7547c6e20a83ce4f91edb2)
- remove molecule test [`0b7543d`](https://github.com/lotusnoir/ansible-apps_ufw/commit/0b7543d0df1717d6795c47ee14270355dcfd68a5)
- add restart on start command as no change on fore-reload [`fb6074b`](https://github.com/lotusnoir/ansible-apps_ufw/commit/fb6074ba96091a93f6a5fb29274bab297c2a527e)
- revert starting task and add force-reload on redhat distrib [`12426ab`](https://github.com/lotusnoir/ansible-apps_ufw/commit/12426abb9ff05bee0af0b10595a99cc07a427ce0)
- change started task to ansible.builtin.service [`d400248`](https://github.com/lotusnoir/ansible-apps_ufw/commit/d400248f5655f3a8ae2285339646cc7ac7dc08bf)
- add redhat 9 to default supported distrib [`decacc3`](https://github.com/lotusnoir/ansible-apps_ufw/commit/decacc3cfa8674b1ad2ab49346e077b12c454808)
- remove redhat molecule checks [`90d2aba`](https://github.com/lotusnoir/ansible-apps_ufw/commit/90d2abac6d555302171e40ef3e6722d1fb9b46e3)
- sort testing distrib to avoid random changes [`84e631f`](https://github.com/lotusnoir/ansible-apps_ufw/commit/84e631f64ceaeb2c7659b2c7576fb6c9d6964924)

## [2.0.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`a8db140`](https://github.com/lotusnoir/ansible-apps_ufw/commit/a8db14055f71fde10bd9c2a742d8f1d232b06514)
- update readme + precommit + include vars [`84a61b0`](https://github.com/lotusnoir/ansible-apps_ufw/commit/84a61b077de32575f331f1c99862406443182ec2)
- add ansible comment on template files [`605220d`](https://github.com/lotusnoir/ansible-apps_ufw/commit/605220d8b4e19a0df05438667076be70b9dba483)
- update molecule playbook order and main include vars [`bacf71a`](https://github.com/lotusnoir/ansible-apps_ufw/commit/bacf71a85fea29800e5eb96f2800c6f46fdea0e1)
- add option to disable icmp pings check [`c83c626`](https://github.com/lotusnoir/ansible-apps_ufw/commit/c83c62692487a3e6b4292e65171c718b76afd0c4)

## [1.1.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`beb28db`](https://github.com/lotusnoir/ansible-apps_ufw/commit/beb28db2928d326d19df8815fc427bf59c128715)

## [1.0.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`106526a`](https://github.com/lotusnoir/ansible-apps_ufw/commit/106526a2bdbf1860b6d6b0d00c31afc18bbab918)
- add precommit for lint [`6b043fd`](https://github.com/lotusnoir/ansible-apps_ufw/commit/6b043fd783b32e7d857ecff78509ca662cf9061a)
- fix checks [`3089fb7`](https://github.com/lotusnoir/ansible-apps_ufw/commit/3089fb7c9db28589aedcaaabdc0a9f599159e059)
- add new molecule all scenario [`c665978`](https://github.com/lotusnoir/ansible-apps_ufw/commit/c665978f2af2509401ed082fbeda6f21235170a0)
- split distro for molecule tests on ci [`c2bc35e`](https://github.com/lotusnoir/ansible-apps_ufw/commit/c2bc35e1089ba72f0596eda33f9fd43c5b647a4a)
- update checks and Readme [`b3f7605`](https://github.com/lotusnoir/ansible-apps_ufw/commit/b3f76050b0ca6db578905facba4cb053d4bb9187)
- add molecule fix for ora9 [`d28f6a5`](https://github.com/lotusnoir/ansible-apps_ufw/commit/d28f6a573f3d1b788957d9ba6840e6da1001c6d6)
- add ora9 support [`ab73bd6`](https://github.com/lotusnoir/ansible-apps_ufw/commit/ab73bd61930451d30401e11ba59c8ac6f33f918d)
- update install option [`c7c4fa9`](https://github.com/lotusnoir/ansible-apps_ufw/commit/c7c4fa9b793a2d0046c8a63fa4ae27deba3f112a)
- add condition to check redhat epel release [`0cf33f2`](https://github.com/lotusnoir/ansible-apps_ufw/commit/0cf33f21daf5a615cbc84e24a98bcec9d9bc8dac)

## [0.3.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`22b2298`](https://github.com/lotusnoir/ansible-apps_ufw/commit/22b22987d88ca02feb1ee2270394524dba13d3a8)
- minor: add oracleLinux support + little fixes [`d351f47`](https://github.com/lotusnoir/ansible-apps_ufw/commit/d351f47a93c62f6689bb09ffe4b839d0e3232274)

## [0.2.0](https://github.com/lotusnoir/ansible-apps_ufw/compare/0.1.1...0.2.0) - 2022-06-07

### Commits

- fix: molecule tests on ubuntu 18&20 [`2aea29e`](https://github.com/lotusnoir/ansible-apps_ufw/commit/2aea29ef009852b5cad2bf9e7cb1a82d64ab632f)
- fix: remove molecule centos8 [`9c93cd4`](https://github.com/lotusnoir/ansible-apps_ufw/commit/9c93cd426707082ce102aa3a0de9ce5ffe1c7014)
- fix: remove unsupported centos8 + minor fixes [`cbf8027`](https://github.com/lotusnoir/ansible-apps_ufw/commit/cbf802798e701043961b96ab38e231c2a843333d)

## [0.1.1](https://github.com/lotusnoir/ansible-apps_ufw/compare/0.1.0...0.1.1) - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`2b4c583`](https://github.com/lotusnoir/ansible-apps_ufw/commit/2b4c5830c0a14f43b738c88ee4391b9ebc271da3)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`5e625b2`](https://github.com/lotusnoir/ansible-apps_ufw/commit/5e625b2a9943b5d18de08ae62a73e433867d62b1)
- minor: add changelog + automatic files checks [`57d84c9`](https://github.com/lotusnoir/ansible-apps_ufw/commit/57d84c9bed8ab96d678303b16fa2eeac585c439b)
- update after.rules [`75bee06`](https://github.com/lotusnoir/ansible-apps_ufw/commit/75bee06fc33b83ebb5561009e21e7306ffba3044)

## 0.1.0 - 2021-11-08

### Commits

- initial commit [`a067692`](https://github.com/lotusnoir/ansible-apps_ufw/commit/a0676929a650dd37483293db6c96c54acfef294e)
