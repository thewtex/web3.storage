# Changelog

## 1.0.0 (2021-08-16)


### Features

* add PinRequest to track CIDs to replicate ([#118](https://www.github.com/web3-storage/web3.storage/issues/118)) ([8a1aee7](https://www.github.com/web3-storage/web3.storage/commit/8a1aee7c1e03e5be70661e2a253ebe1bf2666aba))
* cron metrics ([#305](https://www.github.com/web3-storage/web3.storage/issues/305)) ([f064afb](https://www.github.com/web3-storage/web3.storage/commit/f064afb83776e14d6a66f1bde5884a9d57013794))
* cron pin sync ([#71](https://www.github.com/web3-storage/web3.storage/issues/71)) ([d40980a](https://www.github.com/web3-storage/web3.storage/commit/d40980aa8c20c68d209f6c1d00f9dbf93d192895))


### Bug Fixes

* clarify pin location in logs ([0b9e4e4](https://www.github.com/web3-storage/web3.storage/commit/0b9e4e400262a7c95b1a0fcf7462d6ec993b8823))
* env var for cluster ipfs proxy auth token ([28b6985](https://www.github.com/web3-storage/web3.storage/commit/28b69853b658c37f5da833c327446d0a50ffa0e7))
* files listing ([#155](https://www.github.com/web3-storage/web3.storage/issues/155)) ([bde495c](https://www.github.com/web3-storage/web3.storage/commit/bde495c334874c742d09f3224854324ebaa24e38))
* incremental metrics ([#349](https://www.github.com/web3-storage/web3.storage/issues/349)) ([8347c20](https://www.github.com/web3-storage/web3.storage/commit/8347c20ed4a34c983d4d815b41c06fb849fff279))
* retry DB requests ([f27896e](https://www.github.com/web3-storage/web3.storage/commit/f27896e7f79470dcc18c10024c9c1cf873d22f21))
* set stream-channels=false for cluster add ([#342](https://www.github.com/web3-storage/web3.storage/issues/342)) ([31f30b2](https://www.github.com/web3-storage/web3.storage/commit/31f30b293071cb6915a04117d004c2a0f7e2fccf))
* small perf improvement to pins cron ([4646fc4](https://www.github.com/web3-storage/web3.storage/commit/4646fc4ca654600de362fb5192c555c0168ea98e))
* switch dagSize type to Long ([#116](https://www.github.com/web3-storage/web3.storage/issues/116)) ([15f85eb](https://www.github.com/web3-storage/web3.storage/commit/15f85eb3bbf090ee4bfce5138eb7b963991956e5))


### Performance Improvements

* faster pin status sync ([#338](https://www.github.com/web3-storage/web3.storage/issues/338)) ([2861e33](https://www.github.com/web3-storage/web3.storage/commit/2861e3346cdff780b6eec6e50f0b365c7dd7f35e))
* parallel DAG size calculations ([2f80af9](https://www.github.com/web3-storage/web3.storage/commit/2f80af980ee6a75aa7dbc6ca92be05bb143bd419))
