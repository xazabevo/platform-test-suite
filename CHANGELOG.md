# [0.17.0](https://github.com/dashevo/plaform-test-suite/compare/v0.16.0...v0.17.0) (2020-12-30)


### Features

* make test works without fallback ([#91](https://github.com/dashevo/plaform-test-suite/issues/91))
* update `dashcore-lib`, `dpp`, `wallet-lib`, `dashjs` ([#81](https://github.com/dashevo/plaform-test-suite/issues/81), [#83](https://github.com/dashevo/plaform-test-suite/issues/83), [#88](https://github.com/dashevo/plaform-test-suite/issues/88))
* identity funding double-spend tests ([#86](https://github.com/dashevo/plaform-test-suite/issues/86))


### Bug Fixes

* fake asset lock must be passed only for regtest ([#90](https://github.com/dashevo/plaform-test-suite/issues/90))
* invalid assertions in `Identity` functional test ([#84](https://github.com/dashevo/plaform-test-suite/issues/84))



# [0.16.0](https://github.com/dashevo/plaform-test-suite/compare/v0.15.0...v0.16.0) (2020-10-28)


### Chore

* update to SDK 0.16 ([#77](https://github.com/dashevo/plaform-test-suite/issues/77))


### BREAKING CHANGES

* Nodes with Dash Platform 0.15 are not supported



# [0.15.0](https://github.com/dashevo/plaform-test-suite/compare/v0.14.0...v0.15.0) (2020-09-04)


### Bug Fixes

* faucet client singleton ([#70](https://github.com/dashevo/plaform-test-suite/issues/70))
* core tests were using `serialize` instead of `toBuffer` ([#66](https://github.com/dashevo/plaform-test-suite/issues/66))
* npm is not running `prepare` script as root ([#63](https://github.com/dashevo/plaform-test-suite/issues/63))


### Features

* `wallet` e2e test ([#59](https://github.com/dashevo/plaform-test-suite/issues/59))
* new test timeout option ([#71](https://github.com/dashevo/plaform-test-suite/issues/71))
* remove pending `subscribeToTransactionsWithProofs` functional tests ([#72](https://github.com/dashevo/plaform-test-suite/issues/72))
* remove getAddressSummary tests ([#67](https://github.com/dashevo/plaform-test-suite/issues/67))
* update Wallet, DPP, DPNS and SDK deps ([#50](https://github.com/dashevo/plaform-test-suite/issues/50), [#64](https://github.com/dashevo/plaform-test-suite/issues/64), [#68](https://github.com/dashevo/plaform-test-suite/issues/68), [#60](https://github.com/dashevo/plaform-test-suite/issues/60))
* support for installation node module from git on docker start ([#55](https://github.com/dashevo/plaform-test-suite/issues/55)) ([adb1e16](https://github.com/dashevo/plaform-test-suite/commit/adb1e1672a0288672b2eaef0bf9effc9212b50ad))
* new topup identity test ([#53](https://github.com/dashevo/plaform-test-suite/issues/53)) ([075f09c](https://github.com/dashevo/plaform-test-suite/commit/075f09cb211fcda45aff2c75a2222e735f9eab49))


### Code Refactoring

* use Wallet lib instead of getUTXO ([#62](https://github.com/dashevo/plaform-test-suite/issues/62))



# 0.14.0 (2020-07-23)


### Features

* use external Travis scripts ([#47](https://github.com/dashevo/plaform-test-suite/issues/47))
* update SDK to 3.14.0 ([#45](https://github.com/dashevo/plaform-test-suite/issues/45))
* update DPP to 0.14.0 ([#42](https://github.com/dashevo/plaform-test-suite/issues/42))
* add document timestamp tests ([#40](https://github.com/dashevo/plaform-test-suite/issues/40))
* define npm test scopes ([#31](https://github.com/dashevo/plaform-test-suite/issues/31))
* dockerize test suite ([#28](https://github.com/dashevo/plaform-test-suite/issues/28))
* functional core tests ([#33](https://github.com/dashevo/plaform-test-suite/issues/33))
* implement functional tests ([#38](https://github.com/dashevo/plaform-test-suite/issues/38))
