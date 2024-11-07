# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [19.5.0](https://github.com/nholuongut/commitlint/compare/v19.4.1...v19.5.0) (2024-09-11)

**Note:** Version bump only for package @commitlint/read





# [19.4.0](https://github.com/nholuongut/commitlint/compare/v19.3.1...v19.4.0) (2024-08-07)


### Features

* support linting from the last tag ([#4110](https://github.com/nholuongut/commitlint/issues/4110)) ([4b204ec](https://github.com/nholuongut/commitlint/commit/4b204ecfb43dd6a00e24b51111aadbd78f9d58e1))





## [19.2.1](https://github.com/nholuongut/commitlint/compare/v19.2.0...v19.2.1) (2024-03-19)

**Note:** Version bump only for package @commitlint/read





# [19.2.0](https://github.com/nholuongut/commitlint/compare/v19.1.0...v19.2.0) (2024-03-15)


### Features

* **cli:** introduce new --last flag, to stop recommending HEAD~1 ([#3916](https://github.com/nholuongut/commitlint/issues/3916)) ([99f4f3f](https://github.com/nholuongut/commitlint/commit/99f4f3f4839190a2758083df7ba20b988e7b68a6))





## [19.0.3](https://github.com/nholuongut/commitlint/compare/v19.0.2...v19.0.3) (2024-02-28)

**Note:** Version bump only for package @commitlint/read





# [19.0.0](https://github.com/nholuongut/commitlint/compare/v18.6.2...v19.0.0) (2024-02-27)


* feat!: migrate to pure ESM (#3850) ([3423735](https://github.com/nholuongut/commitlint/commit/342373559bdf7c783c4ef37ff05dc38a5f681159)), closes [#3850](https://github.com/nholuongut/commitlint/issues/3850)


### Reverts

* Revert "chore!: minimum node version v20" ([2816783](https://github.com/nholuongut/commitlint/commit/2816783d00e7eb967de3ac9347c2fc43dc8b94fa))


### BREAKING CHANGES

* migrate to pure ESM

* feat: migrate to pure ESM

* chore: update snapshot

* fix: load `parserPreset` with another `await`

* test: migrate to vitest

* test: remove no replacement `--runInBand` test-ci script

* chore: fix code reviews

* refactor(load): rewrite resolve logic

* fix(config-nx-scopes): fix syntax error

* feat(resolve-extends): add resolveFrom and loadParserPreset

* feat(load): use resolveFrom and loadParserPreset from resolve-extends

* test: include only @commitlint/* packages src in coverage

* test: explicit import vitest utilities

* test: remove @jest/globals from dependencies

* fix(resolve-extends): `resolveFrom` output should be platform aware

* test: restore NO_COLOR to test script

* chore: fix linting issues

* fix: should use fileURLToPath instead of pathname for Windows compatibility

* Apply suggestions from code review

* fix: should reuse `cli` instead call `yargs()`

* feat(cli): set terminalWidth as wrap to avoid work break on help

* Update .eslintrc.cjs

* feat: migrate @commitlint/config-conventional to pure ESM





## [18.6.1](https://github.com/nholuongut/commitlint/compare/v18.6.0...v18.6.1) (2024-02-13)

**Note:** Version bump only for package @commitlint/read





# [18.6.0](https://github.com/nholuongut/commitlint/compare/v18.5.1...v18.6.0) (2024-01-25)

**Note:** Version bump only for package @commitlint/read





## [18.4.4](https://github.com/nholuongut/commitlint/compare/v18.4.3...v18.4.4) (2024-01-04)


### Bug Fixes

* **read:** remove fs-extra usage and use fs/promises ([#3803](https://github.com/nholuongut/commitlint/issues/3803)) ([714be66](https://github.com/nholuongut/commitlint/commit/714be668c104c554c66e866e53addd04944544f6))





## [18.4.3](https://github.com/nholuongut/commitlint/compare/v18.4.2...v18.4.3) (2023-11-21)

**Note:** Version bump only for package @commitlint/read





# [18.4.0](https://github.com/nholuongut/commitlint/compare/v18.3.0...v18.4.0) (2023-11-10)

**Note:** Version bump only for package @commitlint/read





# [18.1.0](https://github.com/nholuongut/commitlint/compare/v18.0.0...v18.1.0) (2023-10-25)

**Note:** Version bump only for package @commitlint/read





# [18.0.0](https://github.com/nholuongut/commitlint/compare/v17.8.1...v18.0.0) (2023-10-20)


* chore!: minimum node version v18 (#3644) ([5b4aeaf](https://github.com/nholuongut/commitlint/commit/5b4aeaf4f01c2726a7bc8631a23bb34c849baad2)), closes [#3644](https://github.com/nholuongut/commitlint/issues/3644)


### BREAKING CHANGES

* drop node v14 and v16 support

* chore: remove unused types

* docs: prepare node update and new release

* chore!: minimum TS version v5
* drop TS v4 support

* ci: remove node v14/16 checks

* chore: adjust node types to minimal supported version

* chore!: further major versions of other deps
* upgrade nholuongut-conventionalcommits, conventional-commits-parser, nholuongut-atom, 

* docs: simplify releases and remove roadmap





## [17.8.1](https://github.com/nholuongut/commitlint/compare/v17.8.0...v17.8.1) (2023-10-20)

**Note:** Version bump only for package @commitlint/read





## [17.5.1](https://github.com/nholuongut/commitlint/compare/v17.5.0...v17.5.1) (2023-03-28)

**Note:** Version bump only for package @commitlint/read





## [17.4.4](https://github.com/nholuongut/commitlint/compare/v17.4.3...v17.4.4) (2023-02-17)

**Note:** Version bump only for package @commitlint/read





## [17.4.2](https://github.com/nholuongut/commitlint/compare/v17.4.1...v17.4.2) (2023-01-12)


### Bug Fixes

* update dependency @types/fs-extra to v11 ([#3494](https://github.com/nholuongut/commitlint/issues/3494)) ([8f553c7](https://github.com/nholuongut/commitlint/commit/8f553c7603e3ee0f435d878e396eec899a213de8))





# [17.4.0](https://github.com/nholuongut/commitlint/compare/v17.3.0...v17.4.0) (2023-01-04)

### Bug Fixes

- update dependency fs-extra to v11 ([#3460](https://github.com/nholuongut/commitlint/issues/3460)) ([a437923](https://github.com/nholuongut/commitlint/commit/a43792388e0d9707da770b26592c5e31553384a1))

# [17.2.0](https://github.com/nholuongut/commitlint/compare/v17.1.2...v17.2.0) (2022-10-31)

**Note:** Version bump only for package @commitlint/read

# [17.1.0](https://github.com/nholuongut/commitlint/compare/v17.0.3...v17.1.0) (2022-08-27)

### Features

- **commitlint:** add additional git log args ([#3334](https://github.com/nholuongut/commitlint/issues/3334)) ([229c65b](https://github.com/nholuongut/commitlint/commit/229c65b60f15c15da5f5b11deb555d1f557c673a))

# [17.0.0](https://github.com/nholuongut/commitlint/compare/v16.3.0...v17.0.0) (2022-05-16)

- chore!: minimum node version v14 (#3128) ([ac5f9b4](https://github.com/nholuongut/commitlint/commit/ac5f9b47a9e3cd5c9d58b14da0feb426f06b1ef9)), closes [#3128](https://github.com/nholuongut/commitlint/issues/3128)

### BREAKING CHANGES

- drop node v12 support

- chore: rename circleci windows job

node version is not defned by the name anyways (i think)

## [16.2.1](https://github.com/nholuongut/commitlint/compare/v16.2.0...v16.2.1) (2022-02-13)

**Note:** Version bump only for package @commitlint/read

# [16.0.0](https://github.com/nholuongut/commitlint/compare/v15.0.0...v16.0.0) (2021-12-26)

**Note:** Version bump only for package @commitlint/read

# [15.0.0](https://github.com/nholuongut/commitlint/compare/v14.2.0...v15.0.0) (2021-11-17)

**Note:** Version bump only for package @commitlint/read

# [14.0.0](https://github.com/nholuongut/commitlint/compare/v13.2.1...v14.0.0) (2021-10-26)

**Note:** Version bump only for package @commitlint/read

# [13.2.0](https://github.com/nholuongut/commitlint/compare/v13.1.0...v13.2.0) (2021-09-28)

**Note:** Version bump only for package @commitlint/read

# [13.1.0](https://github.com/nholuongut/commitlint/compare/v13.0.0...v13.1.0) (2021-07-24)

**Note:** Version bump only for package @commitlint/read

# [13.0.0](https://github.com/nholuongut/commitlint/compare/v12.1.4...v13.0.0) (2021-05-24)

- chore!: remove node 10 support (#2596) ([4db4ba1](https://github.com/nholuongut/commitlint/commit/4db4ba1b0b312410a0f62100a93a80c246a6c410)), closes [#2596](https://github.com/nholuongut/commitlint/issues/2596)

### BREAKING CHANGES

- minimum node version is 12

## [12.1.3](https://github.com/nholuongut/commitlint/compare/v12.1.2...v12.1.3) (2021-05-12)

### Bug Fixes

- update dependency fs-extra to v10 ([#2575](https://github.com/nholuongut/commitlint/issues/2575)) ([d47d2b5](https://github.com/nholuongut/commitlint/commit/d47d2b595b980adadd4fb8ff198c1914caeff18f))

## [12.1.2](https://github.com/nholuongut/commitlint/compare/v12.1.1...v12.1.2) (2021-04-29)

**Note:** Version bump only for package @commitlint/read

## [12.1.1](https://github.com/nholuongut/commitlint/compare/v12.1.0...v12.1.1) (2021-04-02)

**Note:** Version bump only for package @commitlint/read

# [12.1.0](https://github.com/nholuongut/commitlint/compare/v12.0.1...v12.1.0) (2021-03-06)

**Note:** Version bump only for package @commitlint/read

## [12.0.1](https://github.com/nholuongut/commitlint/compare/v12.0.0...v12.0.1) (2021-02-23)

**Note:** Version bump only for package @commitlint/read

# [12.0.0](https://github.com/nholuongut/commitlint/compare/v11.0.0...v12.0.0) (2021-01-18)

**Note:** Version bump only for package @commitlint/read

# [11.0.0](https://github.com/nholuongut/commitlint/compare/v10.0.0...v11.0.0) (2020-09-05)

### Bug Fixes

- update dependency @types/fs-extra to ^9.0.1 ([#2088](https://github.com/nholuongut/commitlint/issues/2088)) ([cb1028e](https://github.com/nholuongut/commitlint/commit/cb1028ef2700d86991c69a1e2ad391bc1bdc9d90))

# [10.0.0](https://github.com/nholuongut/commitlint/compare/v9.1.2...v10.0.0) (2020-08-16)

### Bug Fixes

- update dependency fs-extra to v9 ([#1018](https://github.com/nholuongut/commitlint/issues/1018)) ([2df49fa](https://github.com/nholuongut/commitlint/commit/2df49fac907993ae78199a1012e918b0e2ff5621))

- refactor!: drop support for node 8 (#1999) ([751f39f](https://github.com/nholuongut/commitlint/commit/751f39f284ef232574a176c3c11b1982ee544166)), closes [#1999](https://github.com/nholuongut/commitlint/issues/1999)

### BREAKING CHANGES

- remove node 8 from circle-ci checks

also remove node 13 because we do not support experimental versions

- docs: update node v10 to latest LTS 10 version

Co-authored-by: Cedric van Putten <me@bycedric.com>

Co-authored-by: Cedric van Putten <me@bycedric.com>

## [9.1.2](https://github.com/nholuongut/commitlint/compare/v9.1.1...v9.1.2) (2020-07-13)

**Note:** Version bump only for package @commitlint/read

## [9.1.1](https://github.com/nholuongut/commitlint/compare/v9.1.0...v9.1.1) (2020-06-30)

**Note:** Version bump only for package @commitlint/read

# [9.1.0](https://github.com/nholuongut/commitlint/compare/v9.0.1...v9.1.0) (2020-06-21)

**Note:** Version bump only for package @commitlint/read

## [9.0.1](https://github.com/nholuongut/commitlint/compare/v9.0.0...v9.0.1) (2020-05-26)

**Note:** Version bump only for package @commitlint/read

# [9.0.0](https://github.com/nholuongut/commitlint/compare/v8.3.5...v9.0.0) (2020-05-21)

**Note:** Version bump only for package @commitlint/read

## [8.3.4](https://github.com/nholuongut/commitlint/compare/v8.3.3...v8.3.4) (2020-01-03)

**Note:** Version bump only for package @commitlint/read

# [8.3.0](https://github.com/nholuongut/commitlint/compare/v8.2.0...v8.3.0) (2019-10-16)

**Note:** Version bump only for package @commitlint/read

# [8.2.0](https://github.com/nholuongut/commitlint/compare/v8.1.0...v8.2.0) (2019-09-16)

**Note:** Version bump only for package @commitlint/read

# [8.1.0](https://github.com/nholuongut/commitlint/compare/v8.0.0...v8.1.0) (2019-07-15)

**Note:** Version bump only for package @commitlint/read

# [7.6.0](https://github.com/nholuongut/commitlint/compare/v7.5.2...v7.6.0) (2019-05-06)

### Bug Fixes

- use sander.readFile correctly ([#448](https://github.com/nholuongut/commitlint/issues/448)) ([#630](https://github.com/nholuongut/commitlint/issues/630)) ([8e47985](https://github.com/nholuongut/commitlint/commit/8e47985))

<a name="7.5.0"></a>

# [7.5.0](https://github.com/nholuongut/commitlint/compare/v7.4.0...v7.5.0) (2019-01-31)

### Bug Fixes

- all broken website references ([#564](https://github.com/nholuongut/commitlint/issues/564)) ([82eeb5a](https://github.com/nholuongut/commitlint/commit/82eeb5a))
- replace all repository references with conventional changelog ([#561](https://github.com/nholuongut/commitlint/issues/561)) ([6c3afcd](https://github.com/nholuongut/commitlint/commit/6c3afcd))
- replace all website references with conventional changelog ([#563](https://github.com/nholuongut/commitlint/issues/563)) ([6b86fb1](https://github.com/nholuongut/commitlint/commit/6b86fb1))
- resolve path to commit message for git submodules ([83b1a47](https://github.com/nholuongut/commitlint/commit/83b1a47))

### Features

- add support for git submodules ([cc575fa](https://github.com/nholuongut/commitlint/commit/cc575fa))

<a name="7.3.1"></a>

## [7.3.1](https://github.com/nholuongut/commitlint/compare/v7.3.0...v7.3.1) (2019-01-11)

**Note:** Version bump only for package @commitlint/read

<a name="7.3.0"></a>

# [7.3.0](https://github.com/nholuongut/commitlint/compare/v7.2.1...v7.3.0) (2019-01-11)

**Note:** Version bump only for package @commitlint/read

<a name="7.1.2"></a>

## [7.1.2](https://github.com/nholuongut/commitlint/compare/v7.1.1...v7.1.2) (2018-09-04)

**Note:** Version bump only for package @commitlint/read

<a name="6.1.1"></a>

## [6.1.1](https://github.com/nholuongut/commitlint/compare/v6.1.0...v6.1.1) (2018-02-22)

**Note:** Version bump only for package @commitlint/read