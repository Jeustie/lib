# [@shapeshiftoss/caip-v2.1.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v2.0.2...@shapeshiftoss/caip-v2.1.0) (2022-03-16)


### Features

* add gem adapter ([#433](https://github.com/shapeshift/lib/issues/433)) ([78a8f14](https://github.com/shapeshift/lib/commit/78a8f14b82330239555ad544121ea956dd6ca8be))

# [@shapeshiftoss/caip-v2.0.2](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v2.0.1...@shapeshiftoss/caip-v2.0.2) (2022-03-16)


### Bug Fixes

* update json rpc ([#442](https://github.com/shapeshift/lib/issues/442)) ([abfb16c](https://github.com/shapeshift/lib/commit/abfb16c3d28fa40bbb20e9834d95dca9d13e008a))

# [@shapeshiftoss/caip-v2.0.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v2.0.0...@shapeshiftoss/caip-v2.0.1) (2022-03-03)

# [@shapeshiftoss/caip-v2.0.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.13.0...@shapeshiftoss/caip-v2.0.0) (2022-03-03)


### Code Refactoring

* remove contract types and  make assetnamespace and assetreference required fields ([#410](https://github.com/shapeshift/lib/issues/410)) ([b12bbf3](https://github.com/shapeshift/lib/commit/b12bbf39f55e5d87775def96c2ca7ce05abff2ee))


### BREAKING CHANGES

* remove ContractTypes

For CAIP19 we will use AssetNamespace instead

* refactor(swapper): use AssetNamespace instead of ContractTypes

* feat(caip): caip19 requires assetNamespace and assetReference
* removed contractType and tokenId

assetNamespace and assetReference are used instead and are required

* refactor(asset-service): use AssetNamespace instead of ContractTypes

* refactor(chain-adapters): use assetNamespace and assetReference

For CAIP19, stop relying on default assets

* refactor(swapper): use assetReference instead of tokenId

* refactor(market-data): use assetReference instead of tokenId

* Update packages/caip/README.md

Co-authored-by: 0xdef1cafe <88504456+0xdef1cafe@users.noreply.github.com>

* refactor(asset-service): updated ERC20 strings to lowercase

Co-authored-by: Chris Thompson <chris@thompson-web.org>
Co-authored-by: 0xdef1cafe <88504456+0xdef1cafe@users.noreply.github.com>

# [@shapeshiftoss/caip-v1.13.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.12.1...@shapeshiftoss/caip-v1.13.0) (2022-03-03)


### Features

* osmosis market service ([#394](https://github.com/shapeshift/lib/issues/394)) ([cd613e1](https://github.com/shapeshift/lib/commit/cd613e133f76c00324b5d35fe75ba1ee164f82d7))

# [@shapeshiftoss/caip-v1.12.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.12.0...@shapeshiftoss/caip-v1.12.1) (2022-03-01)


### Bug Fixes

* support slip44 for Cosmos in toCAIP2 ([#409](https://github.com/shapeshift/lib/issues/409)) ([370a8d6](https://github.com/shapeshift/lib/commit/370a8d6530262d78c74cf490fba8061d2fd1331b))

# [@shapeshiftoss/caip-v1.12.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.11.4...@shapeshiftoss/caip-v1.12.0) (2022-02-28)


### Features

* add Cosmos based chain adapters ([#397](https://github.com/shapeshift/lib/issues/397)) ([a0690d7](https://github.com/shapeshift/lib/commit/a0690d700f924d5ff095cfeae072d204e4016708)), closes [#291](https://github.com/shapeshift/lib/issues/291)

# [@shapeshiftoss/caip-v1.11.4](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.11.3...@shapeshiftoss/caip-v1.11.4) (2022-02-25)


### Bug Fixes

* caip support for Osmosis ([#398](https://github.com/shapeshift/lib/issues/398)) ([e0edc67](https://github.com/shapeshift/lib/commit/e0edc673732df2810dae32c5a49014cd174bad5a))

# [@shapeshiftoss/caip-v1.11.3](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.11.2...@shapeshiftoss/caip-v1.11.3) (2022-02-18)


### Bug Fixes

* update fromCaip19 ([#389](https://github.com/shapeshift/lib/issues/389)) ([5ee728f](https://github.com/shapeshift/lib/commit/5ee728fe69c09d8a2d0459ebd020aa4d4f871929))

# [@shapeshiftoss/caip-v1.11.2](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.11.1...@shapeshiftoss/caip-v1.11.2) (2022-02-18)

# [@shapeshiftoss/caip-v1.11.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.11.0...@shapeshiftoss/caip-v1.11.1) (2022-02-17)

# [@shapeshiftoss/caip-v1.11.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.10.2...@shapeshiftoss/caip-v1.11.0) (2022-02-16)


### Features

* caip2/caip19 for Cosmos SDK ([#371](https://github.com/shapeshift/lib/issues/371)) ([24d8f03](https://github.com/shapeshift/lib/commit/24d8f034348e4e6f11da7bdba035312924a0fe9d))

# [@shapeshiftoss/caip-v1.10.2](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.10.1...@shapeshiftoss/caip-v1.10.2) (2022-02-16)

# [@shapeshiftoss/caip-v1.10.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.10.0...@shapeshiftoss/caip-v1.10.1) (2022-02-09)

# [@shapeshiftoss/caip-v1.10.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.9.0...@shapeshiftoss/caip-v1.10.0) (2022-01-31)


### Features

* 821 extend yearn vaults ([#335](https://github.com/shapeshift/lib/issues/335)) ([ef7f591](https://github.com/shapeshift/lib/commit/ef7f5919f27a9e5db1b2c064fda741f6566c672d))

# [@shapeshiftoss/caip-v1.9.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.8.0...@shapeshiftoss/caip-v1.9.0) (2022-01-27)


### Features

* extend market service for pricing data on new tokens ([#327](https://github.com/shapeshift/lib/issues/327)) ([d506d99](https://github.com/shapeshift/lib/commit/d506d99c8e35f92c111bccc09a4a73e12430acb5))

# [@shapeshiftoss/caip-v1.8.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.7.0...@shapeshiftoss/caip-v1.8.0) (2022-01-03)


### Features

* short circuit market data calls to providers that don't support that asset ([#292](https://github.com/shapeshift/lib/issues/292)) ([861fc19](https://github.com/shapeshift/lib/commit/861fc19e8bf92a7e84a37a9b61e33a1a10f02d2d))

# [@shapeshiftoss/caip-v1.7.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.6.1...@shapeshiftoss/caip-v1.7.0) (2021-12-17)


### Features

* implement coincap market service (fixes [#281](https://github.com/shapeshift/lib/issues/281)) ([#286](https://github.com/shapeshift/lib/issues/286)) ([2159a00](https://github.com/shapeshift/lib/commit/2159a005754a8234b87abb648796ea63c69452b3))

# [@shapeshiftoss/caip-v1.6.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.6.0...@shapeshiftoss/caip-v1.6.1) (2021-12-09)


### Bug Fixes

* normalize case for caip contract identifiers (eth). remove chainSpecific from subscribeTxs (eth) ([#277](https://github.com/shapeshift/lib/issues/277)) ([6da16c2](https://github.com/shapeshift/lib/commit/6da16c203b86d19983c8c66f45e25d363d482df5))

# [@shapeshiftoss/caip-v1.6.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.5.1...@shapeshiftoss/caip-v1.6.0) (2021-12-09)


### Features

* caip10 account spec ([#269](https://github.com/shapeshift/lib/issues/269)) ([a794818](https://github.com/shapeshift/lib/commit/a794818ac31ac426c1c3500dfa3b63c69ac7fb53))

# [@shapeshiftoss/caip-v1.5.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.5.0...@shapeshiftoss/caip-v1.5.1) (2021-12-08)

# [@shapeshiftoss/caip-v1.5.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.4.2...@shapeshiftoss/caip-v1.5.0) (2021-11-30)


### Features

* use sibling packages as peerDependencies ([#229](https://github.com/shapeshift/lib/issues/229)) ([7de039e](https://github.com/shapeshift/lib/commit/7de039e89907d98048fe6b1e39b4a1e64377cb50))

# [@shapeshiftoss/caip-v1.4.2](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.4.1...@shapeshiftoss/caip-v1.4.2) (2021-11-29)


### Bug Fixes

* speed up invert of generated caip info ([#256](https://github.com/shapeshift/lib/issues/256)) ([b7d58e4](https://github.com/shapeshift/lib/commit/b7d58e4d69015066b2fe3b800178e2c76a57972f))

# [@shapeshiftoss/caip-v1.4.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.4.0...@shapeshiftoss/caip-v1.4.1) (2021-11-12)


### Bug Fixes

* bump types ([#224](https://github.com/shapeshift/lib/issues/224)) ([fc6ca1c](https://github.com/shapeshift/lib/commit/fc6ca1c5940701131f8421ddbe35f5f8e2d851d3))

# [@shapeshiftoss/caip-v1.4.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.3.0...@shapeshiftoss/caip-v1.4.0) (2021-11-12)


### Features

* export CAIP2 and CAIP19 as string alias ([#215](https://github.com/shapeshift/lib/issues/215)) ([4dacb75](https://github.com/shapeshift/lib/commit/4dacb7546a49c3d722442d89a8c1262907d34915))

# [@shapeshiftoss/caip-v1.3.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.2.2...@shapeshiftoss/caip-v1.3.0) (2021-11-10)


### Features

* add getSendMaxAmount to swapper ([#200](https://github.com/shapeshift/lib/issues/200)) ([1788f5f](https://github.com/shapeshift/lib/commit/1788f5f0aa94334f87452633d572eed4b4feee5d))

# [@shapeshiftoss/caip-v1.2.2](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.2.1...@shapeshiftoss/caip-v1.2.2) (2021-11-10)

# [@shapeshiftoss/caip-v1.2.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.2.0...@shapeshiftoss/caip-v1.2.1) (2021-11-09)


### Bug Fixes

* bump package versions ([#198](https://github.com/shapeshift/lib/issues/198)) ([da6c8f1](https://github.com/shapeshift/lib/commit/da6c8f13eb361aa520f2f1e9fc3e16a3785ed287))

# [@shapeshiftoss/caip-v1.2.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.1.0...@shapeshiftoss/caip-v1.2.0) (2021-11-02)


### Features

* market service market cap functionality ([#153](https://github.com/shapeshift/lib/issues/153)) ([cce22b9](https://github.com/shapeshift/lib/commit/cce22b9398e26ee90c50633941f293e13512a65c))

# [@shapeshiftoss/caip-v1.1.0](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.0.1...@shapeshiftoss/caip-v1.1.0) (2021-10-28)


### Features

* coingecko caip19 adapter ([#172](https://github.com/shapeshift/lib/issues/172)) ([082a52a](https://github.com/shapeshift/lib/commit/082a52a2fe46b1e4d16128800e75b6ed184aec1d))

# [@shapeshiftoss/caip-v1.0.1](https://github.com/shapeshift/lib/compare/@shapeshiftoss/caip-v1.0.0...@shapeshiftoss/caip-v1.0.1) (2021-10-27)

# @shapeshiftoss/caip-v1.0.0 (2021-10-26)


### Features

* caip ids ([#166](https://github.com/shapeshift/lib/issues/166)) ([faa954a](https://github.com/shapeshift/lib/commit/faa954a3f0bd6bb710d7dc1221be73ec1a8bd87d))
