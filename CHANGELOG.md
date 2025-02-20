## [8.5.1](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0...v8.5.1) (2024-05-05)


### Features

* **repo:** load system certs when custom cert specified ([#144](https://github.com/camunda/camunda-8-js-sdk/issues/144)) ([8a47d5e](https://github.com/camunda/camunda-8-js-sdk/commit/8a47d5e9970dd7667d242fb696ca30150b725196)), closes [#131](https://github.com/camunda/camunda-8-js-sdk/issues/131) [#131](https://github.com/camunda/camunda-8-js-sdk/issues/131) [#131](https://github.com/camunda/camunda-8-js-sdk/issues/131) [#135](https://github.com/camunda/camunda-8-js-sdk/issues/135) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#138](https://github.com/camunda/camunda-8-js-sdk/issues/138) [#136](https://github.com/camunda/camunda-8-js-sdk/issues/136) [#136](https://github.com/camunda/camunda-8-js-sdk/issues/136) [#136](https://github.com/camunda/camunda-8-js-sdk/issues/136) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#141](https://github.com/camunda/camunda-8-js-sdk/issues/141) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#141](https://github.com/camunda/camunda-8-js-sdk/issues/141) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#141](https://github.com/camunda/camunda-8-js-sdk/issues/141)

## [8.5.1-alpha.4](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.1-alpha.3...v8.5.1-alpha.4) (2024-05-03)


### Features

* **repo:** load system certs when custom cert specified ([afce0a7](https://github.com/camunda/camunda-8-js-sdk/commit/afce0a78ec81294ab4282ea1cd1e1d80d9244f71)), closes [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#139](https://github.com/camunda/camunda-8-js-sdk/issues/139) [#141](https://github.com/camunda/camunda-8-js-sdk/issues/141)

## [8.5.1-alpha.3](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.1-alpha.2...v8.5.1-alpha.3) (2024-04-29)


### Bug Fixes

* **tasklist:** correct default value of includeVariables parameter in tasklist variables search ([#136](https://github.com/camunda/camunda-8-js-sdk/issues/136)) ([23af921](https://github.com/camunda/camunda-8-js-sdk/commit/23af921769f67e77c68182f3efb2d7509560e514))

## [8.5.1-alpha.2](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.1-alpha.1...v8.5.1-alpha.2) (2024-04-20)


### Features

* **repo:** add status code to HTTPError type ([#135](https://github.com/camunda/camunda-8-js-sdk/issues/135)) ([cfea141](https://github.com/camunda/camunda-8-js-sdk/commit/cfea14173c4ddc005df142cc139db961a235cd53)), closes [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125) [#125](https://github.com/camunda/camunda-8-js-sdk/issues/125)

## [8.5.1-alpha.1](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0...v8.5.1-alpha.1) (2024-04-09)


### Features

* **repo:** add stack traces to async REST errors ([#131](https://github.com/camunda/camunda-8-js-sdk/issues/131)) ([ef8d9c6](https://github.com/camunda/camunda-8-js-sdk/commit/ef8d9c6b58a8864d66b6f8f1b008256cc9acf187))

# [8.5.0](https://github.com/camunda/camunda-8-js-sdk/compare/v8.4.1...v8.5.0) (2024-04-08)


### Bug Fixes

* **issue118:** add smoke test and type surface tests ([fe0c709](https://github.com/camunda/camunda-8-js-sdk/commit/fe0c70925cf3df610b049e776eed5bffe56ef604)), closes [#118](https://github.com/camunda/camunda-8-js-sdk/issues/118)
* **repo:** add note on "supported" ([#107](https://github.com/camunda/camunda-8-js-sdk/issues/107)) ([fc45d61](https://github.com/camunda/camunda-8-js-sdk/commit/fc45d618bc459a06fbf76bd6907511d08e1f583b)), closes [#70](https://github.com/camunda/camunda-8-js-sdk/issues/70)
* **repo:** make fix type commits release a new package ([ded83cf](https://github.com/camunda/camunda-8-js-sdk/commit/ded83cfaf437a2f62a5ef134d7616538facda614))
* **repo:** only git commit on npm publish success ([9012764](https://github.com/camunda/camunda-8-js-sdk/commit/901276451845c5dbd926af0a6563d5564d3e87b9))
* **repo:** use ts-patch to transform module mapping in output ([#112](https://github.com/camunda/camunda-8-js-sdk/issues/112)) ([7efdcf3](https://github.com/camunda/camunda-8-js-sdk/commit/7efdcf3478a0d68b4f1cbc62c1526ba7275008b0)), closes [#110](https://github.com/camunda/camunda-8-js-sdk/issues/110)

## [8.4.1](https://github.com/camunda/camunda-8-js-sdk/compare/v8.4.0...v8.4.1) (2024-04-08)


### Features

* **oauth:** support optional scope in OAuth request ([#25](https://github.com/camunda/camunda-8-js-sdk/issues/25)) ([0451b80](https://github.com/camunda/camunda-8-js-sdk/commit/0451b802594f76518830b9bdff515d67fc0231b9))
* **operate:** add multitenant support and lossless Json parsing ([#82](https://github.com/camunda/camunda-8-js-sdk/issues/82)) ([cf49a71](https://github.com/camunda/camunda-8-js-sdk/commit/cf49a717e2632af845529b3c1fde85ee1b0b347b)), closes [#78](https://github.com/camunda/camunda-8-js-sdk/issues/78) [#67](https://github.com/camunda/camunda-8-js-sdk/issues/67)
* **repo:** add enhanced debug output for http errors ([#88](https://github.com/camunda/camunda-8-js-sdk/issues/88)) ([881b039](https://github.com/camunda/camunda-8-js-sdk/commit/881b03965cc37431885a76291f7c0aa762f26227)), closes [#87](https://github.com/camunda/camunda-8-js-sdk/issues/87)
* **tasklist:** add multitenant support to tasklist ([#85](https://github.com/camunda/camunda-8-js-sdk/issues/85)) ([46bb564](https://github.com/camunda/camunda-8-js-sdk/commit/46bb564365afc3bc6758cd436490a459708128e6))
* **zeebe:** add MigrateProcessInstance ([#97](https://github.com/camunda/camunda-8-js-sdk/issues/97)) ([2a9a123](https://github.com/camunda/camunda-8-js-sdk/commit/2a9a1232b160962f86b9450edd9047a8a933068a)), closes [#49](https://github.com/camunda/camunda-8-js-sdk/issues/49)
* **zeebe:** implement deleteResource ([#73](https://github.com/camunda/camunda-8-js-sdk/issues/73)) ([0cd08b7](https://github.com/camunda/camunda-8-js-sdk/commit/0cd08b7b85d23ab44e42b36b2d9b48c1cfcb8c63))
* **zeebe:** implement lossless parsing of job payload ([#95](https://github.com/camunda/camunda-8-js-sdk/issues/95)) ([57f3ea8](https://github.com/camunda/camunda-8-js-sdk/commit/57f3ea85d4cf86256301f5f2a9bcead09c01a199)), closes [#81](https://github.com/camunda/camunda-8-js-sdk/issues/81)
* **zeebe:** normalise useragent, thread config ([#94](https://github.com/camunda/camunda-8-js-sdk/issues/94)) ([c1c4211](https://github.com/camunda/camunda-8-js-sdk/commit/c1c4211db11173c56d2410f489503ef9acf185f2))
* **zeebe:** remove deployProcess method ([#71](https://github.com/camunda/camunda-8-js-sdk/issues/71)) ([6cb98f0](https://github.com/camunda/camunda-8-js-sdk/commit/6cb98f0ff3baf643015bacfa690f4f119caf6083))


# [8.5.0-alpha.6](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0-alpha.5...v8.5.0-alpha.6) (2024-04-08)


### Bug Fixes

* **issue118:** add smoke test and type surface tests ([fe0c709](https://github.com/camunda/camunda-8-js-sdk/commit/fe0c70925cf3df610b049e776eed5bffe56ef604)), closes [#118](https://github.com/camunda/camunda-8-js-sdk/issues/118)

# [8.5.0-alpha.5](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0-alpha.4...v8.5.0-alpha.5) (2024-04-07)


### Bug Fixes

* **repo:** make fix type commits release a new package ([ded83cf](https://github.com/camunda/camunda-8-js-sdk/commit/ded83cfaf437a2f62a5ef134d7616538facda614))

# [8.5.0-alpha.4](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0-alpha.3...v8.5.0-alpha.4) (2024-04-05)


### Bug Fixes

* **repo:** use ts-patch to transform module mapping in output ([#112](https://github.com/camunda/camunda-8-js-sdk/issues/112)) ([7efdcf3](https://github.com/camunda/camunda-8-js-sdk/commit/7efdcf3478a0d68b4f1cbc62c1526ba7275008b0)), closes [#110](https://github.com/camunda/camunda-8-js-sdk/issues/110)

# [8.5.0-alpha.3](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0-alpha.2...v8.5.0-alpha.3) (2024-04-05)


### Bug Fixes

* **repo:** only git commit on npm publish success ([9012764](https://github.com/camunda/camunda-8-js-sdk/commit/901276451845c5dbd926af0a6563d5564d3e87b9))

# [8.5.0-alpha.2](https://github.com/camunda/camunda-8-js-sdk/compare/v8.5.0-alpha.1...v8.5.0-alpha.2) (2024-04-05)


### Bug Fixes

* **repo:** add note on "supported" ([#107](https://github.com/camunda/camunda-8-js-sdk/issues/107)) ([fc45d61](https://github.com/camunda/camunda-8-js-sdk/commit/fc45d618bc459a06fbf76bd6907511d08e1f583b)), closes [#70](https://github.com/camunda/camunda-8-js-sdk/issues/70)

# [8.5.0-alpha.1](https://github.com/camunda/camunda-8-js-sdk/compare/v8.4.0...v8.5.0-alpha.1) (2024-04-04)


### Features

* **oauth:** support optional scope in OAuth request ([#25](https://github.com/camunda/camunda-8-js-sdk/issues/25)) ([0451b80](https://github.com/camunda/camunda-8-js-sdk/commit/0451b802594f76518830b9bdff515d67fc0231b9))
* **operate:** add multitenant support and lossless Json parsing ([#82](https://github.com/camunda/camunda-8-js-sdk/issues/82)) ([cf49a71](https://github.com/camunda/camunda-8-js-sdk/commit/cf49a717e2632af845529b3c1fde85ee1b0b347b)), closes [#78](https://github.com/camunda/camunda-8-js-sdk/issues/78) [#67](https://github.com/camunda/camunda-8-js-sdk/issues/67)
* **repo:** add enhanced debug output for http errors ([#88](https://github.com/camunda/camunda-8-js-sdk/issues/88)) ([881b039](https://github.com/camunda/camunda-8-js-sdk/commit/881b03965cc37431885a76291f7c0aa762f26227)), closes [#87](https://github.com/camunda/camunda-8-js-sdk/issues/87)
* **tasklist:** add multitenant support to tasklist ([#85](https://github.com/camunda/camunda-8-js-sdk/issues/85)) ([46bb564](https://github.com/camunda/camunda-8-js-sdk/commit/46bb564365afc3bc6758cd436490a459708128e6))
* **zeebe:** add MigrateProcessInstance ([#97](https://github.com/camunda/camunda-8-js-sdk/issues/97)) ([2a9a123](https://github.com/camunda/camunda-8-js-sdk/commit/2a9a1232b160962f86b9450edd9047a8a933068a)), closes [#49](https://github.com/camunda/camunda-8-js-sdk/issues/49)
* **zeebe:** implement deleteResource ([#73](https://github.com/camunda/camunda-8-js-sdk/issues/73)) ([0cd08b7](https://github.com/camunda/camunda-8-js-sdk/commit/0cd08b7b85d23ab44e42b36b2d9b48c1cfcb8c63))
* **zeebe:** implement lossless parsing of job payload ([#95](https://github.com/camunda/camunda-8-js-sdk/issues/95)) ([57f3ea8](https://github.com/camunda/camunda-8-js-sdk/commit/57f3ea85d4cf86256301f5f2a9bcead09c01a199)), closes [#81](https://github.com/camunda/camunda-8-js-sdk/issues/81)
* **zeebe:** normalise useragent, thread config ([#94](https://github.com/camunda/camunda-8-js-sdk/issues/94)) ([c1c4211](https://github.com/camunda/camunda-8-js-sdk/commit/c1c4211db11173c56d2410f489503ef9acf185f2))
* **zeebe:** remove deployProcess method ([#71](https://github.com/camunda/camunda-8-js-sdk/issues/71)) ([6cb98f0](https://github.com/camunda/camunda-8-js-sdk/commit/6cb98f0ff3baf643015bacfa690f4f119caf6083))

# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 8.4.0 (2024-02-01)

### Bug Fixes

- REST getForm returns a flattened shape of the form compared to GraphQL ([58ec6d1](https://github.com/camunda/camunda-8-js-sdk/commit/58ec6d1de08e39cb4699326b67ebbf6a398fb30f))

### Features

- configure specs to import configuration from .env file ([00804d1](https://github.com/camunda/camunda-8-js-sdk/commit/00804d132c0e1840846a5af9eee26351f9580c74))
- **tasklist:** enable multiple clusters via constructor options ([#16](https://github.com/camunda/camunda-8-js-sdk/issues/16)) ([fb12e25](https://github.com/camunda/camunda-8-js-sdk/commit/fb12e258321e6bba03d11d38119c740f0e242773))
