## 1.7.0

 - **FIX**: Exception when having multiple calls to dispose() function of a Svg instance ([#2085](https://github.com/flame-engine/flame/issues/2085)). ([a287904e](https://github.com/flame-engine/flame/commit/a287904eb5dbbe70128207a6f6a56ff98dfbf579))
 - **FIX**: SvgComponent getting blurred and pixelized ([#2084](https://github.com/flame-engine/flame/issues/2084)). ([0911d10b](https://github.com/flame-engine/flame/commit/0911d10b9177c0dbcc6f9ba927f99cb7e04182a5))
 - **FEAT**: Expose paint from svgComponent to set opacity and have opacity effects ([#2092](https://github.com/flame-engine/flame/issues/2092)). ([bedacd0c](https://github.com/flame-engine/flame/commit/bedacd0c8c79f4f060b002eeddaa9d2ef68d316c))

## 1.6.0

 - **FEAT**: Add avoid_final_parameters, depend_on_referenced_packages, unnecessary_to_list_in_spreads ([#1927](https://github.com/flame-engine/flame/issues/1927)). ([deccb434](https://github.com/flame-engine/flame/commit/deccb4349d38b6a91ccf5bdf229980b2a3296ce5))

## 1.5.0

 - **FIX**: Correct flutter constraint ([#1731](https://github.com/flame-engine/flame/issues/1731)). ([c7383843](https://github.com/flame-engine/flame/commit/c738384314a1a5c3695d1c3adaebcb59604df83a))
 - **FEAT**: Move to Flutter 3.0.0 and Dart 2.17.0 ([#1713](https://github.com/flame-engine/flame/issues/1713)). ([2a41d0d6](https://github.com/flame-engine/flame/commit/2a41d0d683391194b7209c47bde91199ab7a663e))

## 1.4.0

 - **FIX**: Correct flutter constraint ([#1731](https://github.com/flame-engine/flame/issues/1731)). ([c7383843](https://github.com/flame-engine/flame/commit/c738384314a1a5c3695d1c3adaebcb59604df83a))
 - **FEAT**: Move to Flutter 3.0.0 and Dart 2.17.0 ([#1713](https://github.com/flame-engine/flame/issues/1713)). ([2a41d0d6](https://github.com/flame-engine/flame/commit/2a41d0d683391194b7209c47bde91199ab7a663e))

## 1.3.0

 - **REFACTOR**: Update and guarantee consistency on mocktail dev dependency version across repo ([#1701](https://github.com/flame-engine/flame/issues/1701)). ([f4a98878](https://github.com/flame-engine/flame/commit/f4a98878062dbd4fe8238a8b014e6be3e528c5d8))
 - **REFACTOR**: Move to package imports ([#1625](https://github.com/flame-engine/flame/issues/1625)). ([843ddc36](https://github.com/flame-engine/flame/commit/843ddc36249272fcb518b44672e1012307dfa1b5))
 - **FEAT**: Add more lint rules ([#1703](https://github.com/flame-engine/flame/issues/1703)). ([49252f8e](https://github.com/flame-engine/flame/commit/49252f8ef29aa6b77144dcb97c24346f2f39380b))
 - **FEAT**: Optional key for Images.load ([#1624](https://github.com/flame-engine/flame/issues/1624)). ([067c34b5](https://github.com/flame-engine/flame/commit/067c34b5f29e1a9bd51861d872092ae5ee0a551f))
 - **FEAT**: Bump to Flutter 2.10.0 ([#1617](https://github.com/flame-engine/flame/issues/1617)). ([beac9013](https://github.com/flame-engine/flame/commit/beac901313456cf0b39b6f4e6459f0feed183614))

## 1.2.0

 - **FEAT**: Added children parameter to Component constructor (#1525). ([f0b31fcf](https://github.com/flame-engine/flame/commit/f0b31fcfc0fc6b0f8f96895ef6a68fd5a30a3159))

## 1.1.0

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 1.1.0-releasecandidate.5

 - Update a dependency to the latest release.

## 1.1.0-releasecandidate.4

 - Update a dependency to the latest release.

## 1.1.0-releasecandidate.3

 - Update a dependency to the latest release.

## 1.1.0-releasecandidate.2

 - Update a dependency to the latest release.

## 1.1.0-releasecandidate.1

> Note: This release has breaking changes.

 - **FIX**: flame svg perfomance (#1373). ([bce24173](https://github.com/flame-engine/flame/commit/bce2417330b5165842f15d0409a213a1c5ad1cd3))
 - **FIX**: preventing svg rendering from affecting other renderings (#1339). ([6e66baa1](https://github.com/flame-engine/flame/commit/6e66baa12fdad7b27f35ca274433acd55165f106))
 - **FEAT**: adding default constructor on SvgComponent (#1334). ([00619f80](https://github.com/flame-engine/flame/commit/00619f80475b1e66802a6d2020ea6d521c84059d))
 - **DOCS**: Fix various dartdoc warnings (#1353). ([9f096053](https://github.com/flame-engine/flame/commit/9f096053fd3c8ebd52d301710625a187db09704f))
 - **BREAKING** **FEAT**: Use a broadphase to make collision detection more efficient (#1252). ([29dd09ca](https://github.com/flame-engine/flame/commit/29dd09ca925e934f3ca4e266a8a0cdb8ad62ef3b))

# CHANGELOG

## [1.0.0]
 - Update to Flame 1.0.0

## [1.0.0-releasecandidate.15]
 - Takes priority as an argument on SvgComponent
 - Simplify implementation of `renderPosition`

## [1.0.0-rc4]
 - Update to flutter_svg 0.22.0

## [1.0.0-rc3]
 - Updated to use flame v1.0.0-releasecandidate.11

## [1.0.0-rc2]
 - Updated to use flame v1.0.0-rc8
 - Migrate to null-safety

## [1.0.0-rc1]
 - Updated to use flame v1.0.0

## [0.0.1]
 - Initial release
