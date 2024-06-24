# Changelog

## Release (2024-06-24)

ember-cli-fastboot 5.0.0 (major)
fastboot 4.2.0 (minor)
fastboot-app-server 4.1.5 (patch)
foo 0.0.1 (patch)

#### :boom: Breaking Change
* `ember-cli-fastboot`
  * [#904](https://github.com/ember-fastboot/ember-cli-fastboot/pull/904) Remove deprecated implicit-injections ([@mikrostew](https://github.com/mikrostew))
  * [#902](https://github.com/ember-fastboot/ember-cli-fastboot/pull/902) Update CI and drop support for Node 12 ([@mikrostew](https://github.com/mikrostew))

#### :rocket: Enhancement
* `fastboot`
  * [#896](https://github.com/ember-fastboot/ember-cli-fastboot/pull/896) feat: adds a environment variable to opt out of source maps ([@gabrielcsapo](https://github.com/gabrielcsapo))
  * [#903](https://github.com/ember-fastboot/ember-cli-fastboot/pull/903) fix: Provide a more meaningful error when whitelist entry is missing ([@runspired](https://github.com/runspired))

#### :bug: Bug Fix
* `fastboot`
  * [#949](https://github.com/ember-fastboot/ember-cli-fastboot/pull/949) Update url for fastboot-express-middleware in package.json for npm ([@SergeAstapov](https://github.com/SergeAstapov))
  * [#946](https://github.com/ember-fastboot/ember-cli-fastboot/pull/946) Update url for fastboot-app-server in package.json for npm ([@SergeAstapov](https://github.com/SergeAstapov))
  * [#905](https://github.com/ember-fastboot/ember-cli-fastboot/pull/905) remove deprecated implicit injection ([@amiarSlimane](https://github.com/amiarSlimane))
* `ember-cli-fastboot`
  * [#943](https://github.com/ember-fastboot/ember-cli-fastboot/pull/943) fix ember-source peer declaration ([@mansona](https://github.com/mansona))
  * [#939](https://github.com/ember-fastboot/ember-cli-fastboot/pull/939) Fix embroider-optimised ([@mansona](https://github.com/mansona))
  * [#929](https://github.com/ember-fastboot/ember-cli-fastboot/pull/929) fix json stringify in fastboot-config ([@mansona](https://github.com/mansona))

#### :memo: Documentation
* Other
  * [#912](https://github.com/ember-fastboot/ember-cli-fastboot/pull/912) Update readme examples to use native class syntax ([@SergeAstapov](https://github.com/SergeAstapov))
* `fastboot`
  * [#906](https://github.com/ember-fastboot/ember-cli-fastboot/pull/906) chore: updates correct name for variable maxSandboxQueue -> maxSandboxQueueSize ([@gabrielcsapo](https://github.com/gabrielcsapo))

#### :house: Internal
* `ember-cli-fastboot`, `fastboot`
  * [#947](https://github.com/ember-fastboot/ember-cli-fastboot/pull/947) Prepare Release ([@github-actions[bot]](https://github.com/apps/github-actions))
  * [#945](https://github.com/ember-fastboot/ember-cli-fastboot/pull/945) Prepare Release ([@github-actions[bot]](https://github.com/apps/github-actions))
  * [#940](https://github.com/ember-fastboot/ember-cli-fastboot/pull/940) Prepare Release ([@github-actions[bot]](https://github.com/apps/github-actions))
* `fastboot`, `custom-fastboot-app`, `ember-cli-fastboot-testing-app`
  * [#944](https://github.com/ember-fastboot/ember-cli-fastboot/pull/944) always use workspace deps ([@mansona](https://github.com/mansona))
* `fastboot-test-scenarios`
  * [#942](https://github.com/ember-fastboot/ember-cli-fastboot/pull/942) mark fastboot-test-scenarios as private ([@mansona](https://github.com/mansona))
* `fastboot`
  * [#941](https://github.com/ember-fastboot/ember-cli-fastboot/pull/941) add names to private tests packages ([@mansona](https://github.com/mansona))
* Other
  * [#937](https://github.com/ember-fastboot/ember-cli-fastboot/pull/937) start using release-plan ([@mansona](https://github.com/mansona))
  * [#932](https://github.com/ember-fastboot/ember-cli-fastboot/pull/932) update CI action versions ([@mansona](https://github.com/mansona))
  * [#931](https://github.com/ember-fastboot/ember-cli-fastboot/pull/931) update release-it ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`
  * [#935](https://github.com/ember-fastboot/ember-cli-fastboot/pull/935) update to Ember 5.8 using ember-cli-update ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `ember-cli-fastboot-testing-app`, `example-addon`
  * [#934](https://github.com/ember-fastboot/ember-cli-fastboot/pull/934) Update ember-cli-fastboot to 4.12 with ember-cli-update ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `fastboot`, `classic-app-template`, `custom-fastboot-app`, `ember-cli-fastboot-testing-app`, `fastboot-test-scenarios`
  * [#919](https://github.com/ember-fastboot/ember-cli-fastboot/pull/919) Move some failing tests from pre-built fixtures to scenario-tester ([@mansona](https://github.com/mansona))
* `custom-fastboot-app`
  * [#926](https://github.com/ember-fastboot/ember-cli-fastboot/pull/926) make sure that we lint (relevant) test-packages ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `fastboot`, `example-addon`
  * [#920](https://github.com/ember-fastboot/ember-cli-fastboot/pull/920) Add Linting to CI ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `fastboot`, `example-addon`, `foo`
  * [#917](https://github.com/ember-fastboot/ember-cli-fastboot/pull/917) move to pnpm ([@mansona](https://github.com/mansona))

#### Committers: 7
- Chris Manson ([@mansona](https://github.com/mansona))
- Chris Thoburn ([@runspired](https://github.com/runspired))
- Gabriel Csapo ([@gabrielcsapo](https://github.com/gabrielcsapo))
- Michael Stewart ([@mikrostew](https://github.com/mikrostew))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Slimane Amiar ([@amiarSlimane](https://github.com/amiarSlimane))
- [@github-actions[bot]](https://github.com/apps/github-actions)

## Release (2024-05-21)

ember-cli-fastboot 4.1.5 (patch)
fastboot 4.1.5 (patch)
fastboot-app-server 4.1.4 (patch)

#### :bug: Bug Fix
* `fastboot`
  * [#946](https://github.com/ember-fastboot/ember-cli-fastboot/pull/946) Update url for fastboot-app-server in package.json for npm ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 1
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))

## Release (2024-05-02)

ember-cli-fastboot 4.1.4 (patch)
fastboot 4.1.4 (patch)
fastboot-app-server 4.1.3 (patch)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#943](https://github.com/ember-fastboot/ember-cli-fastboot/pull/943) fix ember-source peer declaration ([@mansona](https://github.com/mansona))

#### :house: Internal
* `fastboot`, `custom-fastboot-app`, `ember-cli-fastboot-testing-app`
  * [#944](https://github.com/ember-fastboot/ember-cli-fastboot/pull/944) always use workspace deps ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## Release (2024-05-02)

ember-cli-fastboot 4.1.3 (patch)
fastboot 4.1.3 (patch)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#939](https://github.com/ember-fastboot/ember-cli-fastboot/pull/939) Fix embroider-optimised ([@mansona](https://github.com/mansona))

#### :house: Internal
* `fastboot-test-scenarios`
  * [#942](https://github.com/ember-fastboot/ember-cli-fastboot/pull/942) mark fastboot-test-scenarios as private ([@mansona](https://github.com/mansona))
* `fastboot`
  * [#941](https://github.com/ember-fastboot/ember-cli-fastboot/pull/941) add names to private tests packages ([@mansona](https://github.com/mansona))
* Other
  * [#937](https://github.com/ember-fastboot/ember-cli-fastboot/pull/937) start using release-plan ([@mansona](https://github.com/mansona))
  * [#932](https://github.com/ember-fastboot/ember-cli-fastboot/pull/932) update CI action versions ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`
  * [#935](https://github.com/ember-fastboot/ember-cli-fastboot/pull/935) update to Ember 5.8 using ember-cli-update ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `ember-cli-fastboot-testing-app`, `example-addon`
  * [#934](https://github.com/ember-fastboot/ember-cli-fastboot/pull/934) Update ember-cli-fastboot to 4.12 with ember-cli-update ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `fastboot`, `classic-app-template`, `custom-fastboot-app`, `ember-cli-fastboot-testing-app`, `fastboot-test-scenarios`
  * [#919](https://github.com/ember-fastboot/ember-cli-fastboot/pull/919) Move some failing tests from pre-built fixtures to scenario-tester ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))


## v4.1.2 (2023-11-14)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#929](https://github.com/ember-fastboot/ember-cli-fastboot/pull/929) fix json stringify in fastboot-config ([@mansona](https://github.com/mansona))

#### :house: Internal
* Other
  * [#931](https://github.com/ember-fastboot/ember-cli-fastboot/pull/931) update release-it ([@mansona](https://github.com/mansona))
  * [#926](https://github.com/ember-fastboot/ember-cli-fastboot/pull/926) make sure that we lint (relevant) test-packages ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`, `fastboot-express-middleware`, `fastboot`
  * [#920](https://github.com/ember-fastboot/ember-cli-fastboot/pull/920) Add Linting to CI ([@mansona](https://github.com/mansona))
  * [#917](https://github.com/ember-fastboot/ember-cli-fastboot/pull/917) move to pnpm ([@mansona](https://github.com/mansona))

#### Committers: 1
- Chris Manson ([@mansona](https://github.com/mansona))

## v4.1.1 (2023-05-05)

#### :bug: Bug Fix
* `fastboot`
  * [#905](https://github.com/ember-fastboot/ember-cli-fastboot/pull/905) remove deprecated implicit injection ([@amiarSlimane](https://github.com/amiarSlimane))

#### :memo: Documentation
* Other
  * [#912](https://github.com/ember-fastboot/ember-cli-fastboot/pull/912) Update readme examples to use native class syntax ([@SergeAstapov](https://github.com/SergeAstapov))
* `fastboot`
  * [#906](https://github.com/ember-fastboot/ember-cli-fastboot/pull/906) chore: updates correct name for variable maxSandboxQueue -> maxSandboxQueueSize ([@gabrielcsapo](https://github.com/gabrielcsapo))

#### Committers: 3
- Gabriel Csapo ([@gabrielcsapo](https://github.com/gabrielcsapo))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Slimane Amiar ([@amiarSlimane](https://github.com/amiarSlimane))

## v4.1.0 (2022-12-19)

#### :rocket: Enhancement
* `fastboot`
  * [#896](https://github.com/ember-fastboot/ember-cli-fastboot/pull/896) feat: adds a environment variable to opt out of source maps ([@gabrielcsapo](https://github.com/gabrielcsapo))

#### Committers: 1
- Gabriel Csapo ([@gabrielcsapo](https://github.com/gabrielcsapo))


## v4.0.0 (2022-12-16)

#### :boom: Breaking Change
* `ember-cli-fastboot`
  * [#904](https://github.com/ember-fastboot/ember-cli-fastboot/pull/904) Remove deprecated implicit-injections ([@mikrostew](https://github.com/mikrostew))
  * [#902](https://github.com/ember-fastboot/ember-cli-fastboot/pull/902) Update CI and drop support for Node 12 ([@mikrostew](https://github.com/mikrostew))

#### :rocket: Enhancement
* `fastboot`
  * [#903](https://github.com/ember-fastboot/ember-cli-fastboot/pull/903) fix: Provide a more meaningful error when whitelist entry is missing ([@runspired](https://github.com/runspired))

#### Committers: 2
- Chris Thoburn ([@runspired](https://github.com/runspired))
- Michael Stewart ([@mikrostew](https://github.com/mikrostew))


## v3.3.2 (2022-06-21)

#### :bug: Bug Fix
* `fastboot-app-server`
  * [#892](https://github.com/ember-fastboot/ember-cli-fastboot/pull/892) Pass the log argument to worker in fastboot-app-server ([@Aierie](https://github.com/Aierie))

#### Committers: 1
- [@Aierie](https://github.com/Aierie)

## v3.3.1 (2022-06-15)

#### :bug: Bug Fix
* `fastboot`
  * [#895](https://github.com/ember-fastboot/ember-cli-fastboot/pull/895) fix: removes slow leak by emptying cache for source maps ([@gabrielcsapo](https://github.com/gabrielcsapo))

#### :memo: Documentation
* [#891](https://github.com/ember-fastboot/ember-cli-fastboot/pull/891) chore/remove-outdated-readme-warnings ([@rahulk94](https://github.com/rahulk94))

#### Committers: 2
- Gabriel Csapo ([@gabrielcsapo](https://github.com/gabrielcsapo))
- Rahul Kumar ([@rahulk94](https://github.com/rahulk94))


## v3.3.0 (2022-03-21)

#### :rocket: Enhancement
* `fastboot-app-server`
  * [#890](https://github.com/ember-fastboot/ember-cli-fastboot/pull/890) Allow disabling default logging in fastboot-app-server ([@jurgenwerk](https://github.com/jurgenwerk))

#### Committers: 1
- Matic Jurglič ([@jurgenwerk](https://github.com/jurgenwerk))

## v3.2.0 (2022-02-09)

Version numbering got weird here because several packages were combined into one monorepo with shared version numbers:

 - The previous stable `ember-cli-fastboot` release was 2.2.3, so this is a **semver major**.
 - The previous stable `fastboot` release was 3.1.2, so this is a semver minor.
 - The previous stable `fastboot-app-server` release was 3.0.0, so this is a semver minor.
 - The previous stable `fastboot-express-middleware` release was 3.1.0, so this is a semver minor.

#### :rocket: Enhancement
* Works with Ember 4
* Works with Embroider

#### :boom: Breaking Change
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#834](https://github.com/ember-fastboot/ember-cli-fastboot/pull/834) Update using ember-cli-update and drop support for Node 10 ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`
  * [#825](https://github.com/ember-fastboot/ember-cli-fastboot/pull/825) Drop module unification support ([@xg-wang](https://github.com/xg-wang))
  * [#820](https://github.com/ember-fastboot/ember-cli-fastboot/pull/820) Remove deprecated features for ember-cli-fastboot v3 release ([@xg-wang](https://github.com/xg-wang))


#### :house: Internal
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#886](https://github.com/ember-fastboot/ember-cli-fastboot/pull/886) Update and synchronize dependencies in the monorepo ([@SergeAstapov](https://github.com/SergeAstapov))
* `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#867](https://github.com/ember-fastboot/ember-cli-fastboot/pull/867) Remove unused nested github actions setup ([@SergeAstapov](https://github.com/SergeAstapov))
* `ember-cli-fastboot`
  * [#866](https://github.com/ember-fastboot/ember-cli-fastboot/pull/866) Make edition=octane and update deps for Ember v4 compatibility ([@SergeAstapov](https://github.com/SergeAstapov))
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`
  * [#865](https://github.com/ember-fastboot/ember-cli-fastboot/pull/865) Update .npmignore to ignore .github and test folders ([@SergeAstapov](https://github.com/SergeAstapov))
* Other
  * [#864](https://github.com/ember-fastboot/ember-cli-fastboot/pull/864) Cache dependencies in GitHub Actions CI workflow ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 1
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))

## v3.2.0-beta.5 (2021-11-24)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#862](https://github.com/ember-fastboot/ember-cli-fastboot/pull/862) Ensure rehydration works on Ember < 3.27 ([@rwjblue](https://github.com/rwjblue))
* `fastboot`
  * [#859](https://github.com/ember-fastboot/ember-cli-fastboot/pull/859) Removes call to deprecated OutgoingMessage.prototype._headers ([@SergeAstapov](https://github.com/SergeAstapov))

#### :house: Internal
* `ember-cli-fastboot`
  * [#861](https://github.com/ember-fastboot/ember-cli-fastboot/pull/861) Add tests for Ember 3.24 + 3.28 + 4.0 ([@NullVoxPopuli](https://github.com/NullVoxPopuli))
  * [#858](https://github.com/ember-fastboot/ember-cli-fastboot/pull/858) Add ember-try testing for ember-cli-fastboot ([@mansona](https://github.com/mansona))

#### Committers: 4
- Chris Manson ([@mansona](https://github.com/mansona))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- [@NullVoxPopuli](https://github.com/NullVoxPopuli)

## v3.2.0-beta.4 (2021-09-14)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#857](https://github.com/ember-fastboot/ember-cli-fastboot/pull/857) Avoid implicit injection _fastbootInfo deprecation pt 2 ([@snewcomer](https://github.com/snewcomer))
  * [#849](https://github.com/ember-fastboot/ember-cli-fastboot/pull/849) Fix use of Ember global, breaking Ember 4 ([@simonihmig](https://github.com/simonihmig))
* `fastboot`
  * [#854](https://github.com/ember-fastboot/ember-cli-fastboot/pull/854) Support extracting fastboot specific config from meta tag ([@xg-wang](https://github.com/xg-wang))

#### :memo: Documentation
* [#826](https://github.com/ember-fastboot/ember-cli-fastboot/pull/826) Provide instructions how to debug app via VS Code ([@SergeAstapov](https://github.com/SergeAstapov))

#### Committers: 4
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- Sergey Astapov ([@SergeAstapov](https://github.com/SergeAstapov))
- Simon Ihmig ([@simonihmig](https://github.com/simonihmig))
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))


## v3.2.0-beta.3 (2021-09-10)

#### :boom: Breaking Change
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#834](https://github.com/ember-fastboot/ember-cli-fastboot/pull/834) Update using ember-cli-update and drop support for Node 10 ([@mansona](https://github.com/mansona))
* `ember-cli-fastboot`
  * [#825](https://github.com/ember-fastboot/ember-cli-fastboot/pull/825) Drop module unification support ([@xg-wang](https://github.com/xg-wang))
  * [#820](https://github.com/ember-fastboot/ember-cli-fastboot/pull/820) Remove deprecated features for ember-cli-fastboot v3 release ([@xg-wang](https://github.com/xg-wang))

#### :rocket: Enhancement
* `ember-cli-fastboot`
  * [#814](https://github.com/ember-fastboot/ember-cli-fastboot/pull/814) Throw a helpful error when people use `isFastboot` instead of `isFastBoot` ([@bertdeblock](https://github.com/bertdeblock))
* `fastboot-app-server`
  * [#811](https://github.com/ember-fastboot/ember-cli-fastboot/pull/811) [fastboot-app-server] turn on gzip by default ([@xg-wang](https://github.com/xg-wang))

#### :bug: Bug Fix
* `fastboot`
  * [#853](https://github.com/ember-fastboot/ember-cli-fastboot/pull/853) Fix fastboot-script assets with cutom root url ([@xg-wang](https://github.com/xg-wang))
  * [#840](https://github.com/ember-fastboot/ember-cli-fastboot/pull/840) Add a default state for metadata ([@suchitadoshi1987](https://github.com/suchitadoshi1987))

#### :memo: Documentation
* [#810](https://github.com/ember-fastboot/ember-cli-fastboot/pull/810) doc: update CONTRIBUTING.md for code structure and tests ([@xg-wang](https://github.com/xg-wang))

#### :house: Internal
* `ember-cli-fastboot`
  * [#841](https://github.com/ember-fastboot/ember-cli-fastboot/pull/841) Avoid implicit injection _fastbootInfo deprecation ([@snewcomer](https://github.com/snewcomer))
  * [#836](https://github.com/ember-fastboot/ember-cli-fastboot/pull/836) Restore the legacy tests ([@kiwiupover](https://github.com/kiwiupover))
* Other
  * [#842](https://github.com/ember-fastboot/ember-cli-fastboot/pull/842) Add test scripts ([@xg-wang](https://github.com/xg-wang))
  * [#832](https://github.com/ember-fastboot/ember-cli-fastboot/pull/832) Testing ember-cli-fastboot-testing in new test-package ([@ankushdharkar](https://github.com/ankushdharkar))
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#821](https://github.com/ember-fastboot/ember-cli-fastboot/pull/821) Convert co to async in test; cleanup some configurations ([@xg-wang](https://github.com/xg-wang))

#### Committers: 7
- Ankush Dharkar ([@ankushdharkar](https://github.com/ankushdharkar))
- Bert De Block ([@bertdeblock](https://github.com/bertdeblock))
- Chris Manson ([@mansona](https://github.com/mansona))
- Dave Laird ([@kiwiupover](https://github.com/kiwiupover))
- Scott Newcomer ([@snewcomer](https://github.com/snewcomer))
- Suchita Doshi ([@suchitadoshi1987](https://github.com/suchitadoshi1987))
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))


## v3.2.0-beta.2 (2021-01-29)

#### :bug: Bug Fix
* `ember-cli-fastboot`
  * [#808](https://github.com/ember-fastboot/ember-cli-fastboot/pull/808) Fix treeForFastBoot when project is an addon ([@simonihmig](https://github.com/simonihmig))

#### :house: Internal
* `ember-cli-fastboot`
  * [#803](https://github.com/ember-fastboot/ember-cli-fastboot/pull/803) Dave/custom fastboot app ([@kiwiupover](https://github.com/kiwiupover))

#### Committers: 2
- Dave Laird ([@kiwiupover](https://github.com/kiwiupover))
- Simon Ihmig ([@simonihmig](https://github.com/simonihmig))


## v3.2.0-beta.1 (2021-01-29)

#### :memo: Documentation
* [#800](https://github.com/ember-fastboot/ember-cli-fastboot/pull/800) Update README to match buildSandboxGlobals API ([@bobisjan](https://github.com/bobisjan))

#### :house: Internal
* `ember-cli-fastboot`, `fastboot-app-server`, `fastboot-express-middleware`, `fastboot`
  * [#805](https://github.com/ember-fastboot/ember-cli-fastboot/pull/805) Migrate to a monorepo setup ([@xg-wang](https://github.com/xg-wang))
* `ember-cli-fastboot`
  * [#795](https://github.com/ember-fastboot/ember-cli-fastboot/pull/795) Move response-details-test from legacy-tests to basic-app tests ([@kiwiupover](https://github.com/kiwiupover))

#### Committers: 73
- Jan Bobisud ([@bobisjan](https://github.com/bobisjan))
- Thomas Wang ([@xg-wang](https://github.com/xg-wang))
- Dave Laird ([@kiwiupover](https://github.com/kiwiupover))


## v3.0.0-beta.2 (2020-09-18)

#### :rocket: Enhancement
* `ember-cli-fastboot`
  * [#770](https://github.com/ember-fastboot/ember-cli-fastboot/pull/770) Add 'node: current' to the targets file on install ([@mansona](https://github.com/mansona))

#### :house: Internal
* Other
  * [#787](https://github.com/ember-fastboot/ember-cli-fastboot/pull/787) Don't update the test-package fake addon package versions ([@kiwiupover](https://github.com/kiwiupover))
* `ember-cli-fastboot`
  * [#786](https://github.com/ember-fastboot/ember-cli-fastboot/pull/786) Adding testing libs so we can tests a running ember app. ([@kiwiupover](https://github.com/kiwiupover))

#### Committers: 2
- Chris Manson ([@mansona](https://github.com/mansona))
- Dave Laird ([@kiwiupover](https://github.com/kiwiupover))


## v3.0.0-beta.1 (2020-09-18)

#### :boom: Breaking Change
* [#748](https://github.com/ember-fastboot/ember-cli-fastboot/pull/748) Update fastboot to the latest version 🚀 ([@greenkeeper[bot]](https://github.com/apps/greenkeeper))
* [#695](https://github.com/ember-fastboot/ember-cli-fastboot/pull/695) Drop Node 6, 8, 9, 11, and 13 support. ([@rwjblue](https://github.com/rwjblue))

#### :rocket: Enhancement
* `ember-cli-fastboot`
  * [#780](https://github.com/ember-fastboot/ember-cli-fastboot/pull/780) Update FastBoot to 3.1.0 ([@kiwiupover](https://github.com/kiwiupover))

#### :bug: Bug Fix
* [#772](https://github.com/ember-fastboot/ember-cli-fastboot/pull/772) Remove the second version of broccoli-file-creator from package.json ([@kiwiupover](https://github.com/kiwiupover))

#### :memo: Documentation
* [#771](https://github.com/ember-fastboot/ember-cli-fastboot/pull/771) Update README.md ([@jad359](https://github.com/jad359))

#### :house: Internal
* `ember-cli-fastboot`
  * [#783](https://github.com/ember-fastboot/ember-cli-fastboot/pull/783) Add automated release setup. ([@rwjblue](https://github.com/rwjblue))
  * [#778](https://github.com/ember-fastboot/ember-cli-fastboot/pull/778) Move package-json test to the basic-app ([@kiwiupover](https://github.com/kiwiupover))
  * [#776](https://github.com/ember-fastboot/ember-cli-fastboot/pull/776) Move asset rewriting test to test-packages/basic-app ([@kiwiupover](https://github.com/kiwiupover))
  * [#775](https://github.com/ember-fastboot/ember-cli-fastboot/pull/775) Adding basic test app ([@kiwiupover](https://github.com/kiwiupover))
  * [#767](https://github.com/ember-fastboot/ember-cli-fastboot/pull/767) Migrate to monorepo structure (to easily add test apps) ([@kiwiupover](https://github.com/kiwiupover))
* Other
  * [#774](https://github.com/ember-fastboot/ember-cli-fastboot/pull/774) Move `.gitignore` into root ([@rwjblue](https://github.com/rwjblue))
  * [#773](https://github.com/ember-fastboot/ember-cli-fastboot/pull/773) Remove travis in-favor of GitHub actions ([@kiwiupover](https://github.com/kiwiupover))
  * [#769](https://github.com/ember-fastboot/ember-cli-fastboot/pull/769) Adding github action tests ([@kiwiupover](https://github.com/kiwiupover))

#### Committers: 3
- Dave Laird ([@kiwiupover](https://github.com/kiwiupover))
- Jennifer ([@jad359](https://github.com/jad359))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v2.2.3 (2020-06-10)

#### :bug: Bug Fix
* [#763](https://github.com/ember-fastboot/ember-cli-fastboot/pull/763) Prevent errors when `fastboot-body-end` is not present. ([@rwjblue](https://github.com/rwjblue))

#### :memo: Documentation
* [#762](https://github.com/ember-fastboot/ember-cli-fastboot/pull/762) Update documentation on shoebox. ([@burritoIand](https://github.com/burritoIand))

#### Committers: 2
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- [@burritoIand](https://github.com/burritoIand)

## v2.2.2 (2020-04-09)

#### :rocket: Enhancement
* [#752](https://github.com/ember-fastboot/ember-cli-fastboot/pull/752) Add support for custom configuration ([@bobisjan](https://github.com/bobisjan))

#### :bug: Bug Fix
* [#737](https://github.com/ember-fastboot/ember-cli-fastboot/pull/737) Fix custom app build issue #730 ([@dnalagatla](https://github.com/dnalagatla))

#### :memo: Documentation
* [#728](https://github.com/ember-fastboot/ember-cli-fastboot/pull/728) fix typo in property name isFastboot -> isFastBoot ([@jelhan](https://github.com/jelhan))

#### :house: Internal
* [#760](https://github.com/ember-fastboot/ember-cli-fastboot/pull/760) Re-roll yarn.lock ([@kratiahuja](https://github.com/kratiahuja))
* [#738](https://github.com/ember-fastboot/ember-cli-fastboot/pull/738) Re-roll yarn.lock. ([@rwjblue](https://github.com/rwjblue))

#### Committers: 5
- Dinesh Nalagatla ([@dnalagatla](https://github.com/dnalagatla))
- Jan Bobisud ([@bobisjan](https://github.com/bobisjan))
- Jeldrik Hanschke ([@jelhan](https://github.com/jelhan))
- Krati Ahuja ([@kratiahuja](https://github.com/kratiahuja))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))


## v2.2.1 (2019-09-11)

#### :bug: Bug Fix
* [#725](https://github.com/ember-fastboot/ember-cli-fastboot/pull/725) cheerio is used outside of tests so must be a dependency ([@stefanpenner](https://github.com/stefanpenner))

## v2.2.0 (2019-09-10)

* use volta to pin node to ease development
* Added support to update manifest app files from index.html
 Embroider Support: Moved app factory module out of fastboot-app-module (#714)
* Point to ember-data-storefront instead of ember-cached-shoe (#718)
* Dev server forwards out of scope requests

## v2.1.1 (2019-06-03)

#### :bug: Bug Fix
* [#699](https://github.com/ember-fastboot/ember-cli-fastboot/pull/699) Ensure FastBoot rendered content is cleared even if the server rendered application contains malformed HTML. ([@noslouch](https://github.com/noslouch))

#### Committers: 1
- Brian Whitton ([@noslouch](https://github.com/noslouch))

## v2.1.0 (2019-05-28)

#### :rocket: Enhancement
* [#666](https://github.com/ember-fastboot/ember-cli-fastboot/pull/666) memoize existsSync calls on the fastboot instance itself ([@stefanpenner](https://github.com/stefanpenner))

#### :bug: Bug Fix
* [#692](https://github.com/ember-fastboot/ember-cli-fastboot/pull/692) Fix deprecation warning for Ember.Logger usage ([@rileyhilliard](https://github.com/rileyhilliard))
* [#690](https://github.com/ember-fastboot/ember-cli-fastboot/pull/690) Moved building fastboot config tree from postProcessTree to treeForPublic ([@dnalagatla](https://github.com/dnalagatla))

#### :memo: Documentation
* [#694](https://github.com/ember-fastboot/ember-cli-fastboot/pull/694) Add automated release setup. ([@rwjblue](https://github.com/rwjblue))

#### :house: Internal
* [#694](https://github.com/ember-fastboot/ember-cli-fastboot/pull/694) Add automated release setup. ([@rwjblue](https://github.com/rwjblue))
* [#679](https://github.com/ember-fastboot/ember-cli-fastboot/pull/679) Get tests passing again by testing against ember-data@3.8.0 instead of master ([@kiwiupover](https://github.com/kiwiupover))

#### Committers: 5
- David Laird ([@kiwiupover](https://github.com/kiwiupover))
- Dinesh Nalagatla ([@dnalagatla](https://github.com/dnalagatla))
- Riley Hilliard ([@rileyhilliard](https://github.com/rileyhilliard))
- Robert Jackson ([@rwjblue](https://github.com/rwjblue))
- Stefan Penner ([@stefanpenner](https://github.com/stefanpenner))

## 2.0.4

* Fix issue in IE11 when using `Array.from`

## 2.0.1
* Fixes issue where shoebox data was being cleared when clearing the server side content.

## 2.0.0

* Drop Node 4 support.
* Disentangle from broccoli-asset-rev (requires broccoli-asset-rev@3.0.0).

## 1.1.3

Support without rootElement

## 1.1.2

* Make FastBoot addon compatible with Ember CLI 3.0.0

## 1.1.1

* Make manifest in package.json respect outputPaths configuration in EmberApp (PR # 539) (@SergeAstapov)
* Register fastboot transform for apps to wrap non compatible asserts (PR#470) (@kratiahuja)
* Move fastboot-transform and fs-extra to depedencies in package.json (@SergeAstapov)

## 1.1.0

* Bumping `fastboot-express-middleware` to 1.1.0
