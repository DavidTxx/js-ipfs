# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.6.3](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.6.2...ipfs-grpc-client@0.6.3) (2021-09-02)


### Bug Fixes

* declare types in .ts files ([#3840](https://github.com/ipfs/js-ipfs/issues/3840)) ([eba5fe6](https://github.com/ipfs/js-ipfs/commit/eba5fe6832858107b3e1ae02c99de674622f12b4))
* remove use of instanceof for CID class ([#3847](https://github.com/ipfs/js-ipfs/issues/3847)) ([ebbb12d](https://github.com/ipfs/js-ipfs/commit/ebbb12db523c53ce8e4ddae5266cd9acb3504431))





## [0.6.2](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.6.1...ipfs-grpc-client@0.6.2) (2021-08-25)

**Note:** Version bump only for package ipfs-grpc-client





## [0.6.1](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.6.0...ipfs-grpc-client@0.6.1) (2021-08-17)

**Note:** Version bump only for package ipfs-grpc-client





# [0.6.0](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.5.0...ipfs-grpc-client@0.6.0) (2021-08-17)


### Features

* pubsub over gRPC ([#3813](https://github.com/ipfs/js-ipfs/issues/3813)) ([e7d5509](https://github.com/ipfs/js-ipfs/commit/e7d5509c87e87aed6be3c1d0b2a01ab74cdc1ed9)), closes [#3741](https://github.com/ipfs/js-ipfs/issues/3741)





# [0.5.0](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.4.1...ipfs-grpc-client@0.5.0) (2021-08-11)


### Features

* make ipfs.get output tarballs ([#3785](https://github.com/ipfs/js-ipfs/issues/3785)) ([1ad6001](https://github.com/ipfs/js-ipfs/commit/1ad60018d39d5b46c484756631e30e1989fd8eba))


### BREAKING CHANGES

* the output type of `ipfs.get` has changed and the `recursive` option has been removed from `ipfs.ls` since it was not supported everywhere





## [0.4.1](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.4.0...ipfs-grpc-client@0.4.1) (2021-07-30)

**Note:** Version bump only for package ipfs-grpc-client





# [0.4.0](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.3.3...ipfs-grpc-client@0.4.0) (2021-07-27)


### Features

* implement dag import/export ([#3728](https://github.com/ipfs/js-ipfs/issues/3728)) ([700765b](https://github.com/ipfs/js-ipfs/commit/700765be2634fa5d2d71d8b87cf68c9cd328d2c4)), closes [#2953](https://github.com/ipfs/js-ipfs/issues/2953) [#2745](https://github.com/ipfs/js-ipfs/issues/2745)
* upgrade to the new multiformats ([#3556](https://github.com/ipfs/js-ipfs/issues/3556)) ([d13d15f](https://github.com/ipfs/js-ipfs/commit/d13d15f022a87d04a35f0f7822142f9cb898479c))


### BREAKING CHANGES

* ipld-formats no longer supported, use multiformat BlockCodecs instead

Co-authored-by: Rod Vagg <rod@vagg.org>
Co-authored-by: achingbrain <alex@achingbrain.net>





## [0.3.3](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.3.2...ipfs-grpc-client@0.3.3) (2021-06-18)

**Note:** Version bump only for package ipfs-grpc-client





## [0.3.2](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.3.1...ipfs-grpc-client@0.3.2) (2021-06-05)

**Note:** Version bump only for package ipfs-grpc-client





## [0.3.1](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.3.0...ipfs-grpc-client@0.3.1) (2021-05-26)

**Note:** Version bump only for package ipfs-grpc-client





# [0.3.0](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.2.4...ipfs-grpc-client@0.3.0) (2021-05-10)


### Bug Fixes

* ignore the ts error caused by the recent protobufjs type change ([#3656](https://github.com/ipfs/js-ipfs/issues/3656)) ([084589c](https://github.com/ipfs/js-ipfs/commit/084589c0116d8f27ce1462424fb93b6037b776a9))


### chore

* upgrade deps with new typedefs ([#3550](https://github.com/ipfs/js-ipfs/issues/3550)) ([a418a52](https://github.com/ipfs/js-ipfs/commit/a418a521574c878d7aabd0ad2fd8d516908a3756))


### BREAKING CHANGES

* all core api methods now have types, some method signatures have changed, named exports are now used by the http, grpc and ipfs client modules





## [0.2.4](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.2.3...ipfs-grpc-client@0.2.4) (2021-03-10)

**Note:** Version bump only for package ipfs-grpc-client





## [0.2.3](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.2.2...ipfs-grpc-client@0.2.3) (2021-03-09)


### Bug Fixes

* update to new aegir ([#3528](https://github.com/ipfs/js-ipfs/issues/3528)) ([49f7880](https://github.com/ipfs/js-ipfs/commit/49f78807d7e26483bd926b45cc7e0f797d77e41b))





## [0.2.2](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.2.1...ipfs-grpc-client@0.2.2) (2021-02-08)

**Note:** Version bump only for package ipfs-grpc-client





## [0.2.1](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.2.0...ipfs-grpc-client@0.2.1) (2021-02-02)

**Note:** Version bump only for package ipfs-grpc-client





# [0.2.0](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.1.2...ipfs-grpc-client@0.2.0) (2021-02-01)


### chore

* update deps ([#3514](https://github.com/ipfs/js-ipfs/issues/3514)) ([061d77c](https://github.com/ipfs/js-ipfs/commit/061d77cc03f40af5a3bc3590481e1e5836e7f0d8))


### BREAKING CHANGES

* ipfs-repo upgrade requires repo migration to v10





## [0.1.2](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.1.1...ipfs-grpc-client@0.1.2) (2021-01-22)


### Bug Fixes

* issue with isolateModules flag ([#3495](https://github.com/ipfs/js-ipfs/issues/3495)) ([839e190](https://github.com/ipfs/js-ipfs/commit/839e1908f3c050b45af176883a7e450fb339bef0)), closes [#3494](https://github.com/ipfs/js-ipfs/issues/3494) [#3498](https://github.com/ipfs/js-ipfs/issues/3498) [/github.com/ipfs-shipyard/ipfs-webui/pull/1655#issuecomment-763846124](https://github.com//github.com/ipfs-shipyard/ipfs-webui/pull/1655/issues/issuecomment-763846124)





## [0.1.1](https://github.com/ipfs/js-ipfs/compare/ipfs-grpc-client@0.1.0...ipfs-grpc-client@0.1.1) (2021-01-20)


### Bug Fixes

* use https agent for https requests ([#3490](https://github.com/ipfs/js-ipfs/issues/3490)) ([ac4bb48](https://github.com/ipfs/js-ipfs/commit/ac4bb4841ce7c191408e1b2bb906284ae0dbd975)), closes [#3474](https://github.com/ipfs/js-ipfs/issues/3474)





# 0.1.0 (2021-01-15)


### Features

* add grpc server and client ([#3403](https://github.com/ipfs/js-ipfs/issues/3403)) ([a9027e0](https://github.com/ipfs/js-ipfs/commit/a9027e0ec0cea9a4f34b4f2f52e09abb35237384)), closes [#2519](https://github.com/ipfs/js-ipfs/issues/2519) [#2838](https://github.com/ipfs/js-ipfs/issues/2838) [#2943](https://github.com/ipfs/js-ipfs/issues/2943) [#2854](https://github.com/ipfs/js-ipfs/issues/2854) [#2864](https://github.com/ipfs/js-ipfs/issues/2864)
* allow passing a http.Agent to the grpc client ([#3477](https://github.com/ipfs/js-ipfs/issues/3477)) ([c5f0bc5](https://github.com/ipfs/js-ipfs/commit/c5f0bc5eeee15369b7d02901035b04184a8608d2)), closes [#3474](https://github.com/ipfs/js-ipfs/issues/3474)
