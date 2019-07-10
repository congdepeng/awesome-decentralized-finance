# 超酷的去中心化金融列表  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

经过仔细挑选的非常酷的去中心化金融项目、软件和资源列表。

## 什么是去中心化金融(Decentralized Finance, DeFi)?

去中心化金融 (#defi) 利用开源软件和去中心化网络将传统金融产品转变为无需信任(trustless)和透明的(transparent)协议, 避免了非必须的中间人参与操作(没有中间商赚差价)。

可以想象去中心化金融对金融世界的影响, 将像开源软件改变了软件产品一样。

## 内容索引

- [去中心化交易所协议](#decentralized-exchange-protocols)
- [稳定币/Stablecoins](#stablecoins)
- [借贷协议](#lending-protocols)
- [金融衍生品/预测市场](#derivative-protocols)
- [打包协议(e.g.一篮子货币)](#bundling-protocols)
- [通证化协议](#tokenization-protocols)
- [资金(资产)协议](#fund-protocols)
- [KYC/反洗钱/身份识别](#kyc-aml-identity)
- [应用/工具](#applications-tools)
- [分析](#analytics)
- [杂项](#misc)
- [社区](#community)

<a name="decentralized-exchange-protocols" />

## 去中心化交易所协议

- [BitShares](https://bitshares.org/technology/decentralized-asset-exchange) ([代码](https://github.com/bitshares), [白皮书](https://www.bitshares.foundation/download/articles/BitSharesBlockchain.pdf)) - 基于石墨烯(Graphene)区块链
- Bitcoin
  - [Bisq](https://bisq.network) ([代码](https://github.com/bisq-network/bisq), [白皮书](https://github.com/bisq-network/bisq-docs/blob/master/exchange/whitepaper.adoc)) - 支持点对点交易比特币的协议
- Ethereum
  - [0x](https://0x.org/) ([代码](https://github.com/0xProject), [白皮书](https://0x.org/pdfs/0x_white_paper.pdf)) - 基于中继者(relayers)来提供以太坊资产的去中心化交易功能，当前为第二个版本
  - [Bancor Protocol](https://about.bancor.network/protocol/) ([代码](https://github.com/bancorprotocol/contracts), [白皮书](https://storage.googleapis.com/website-bancor/2018/04/01ba8253-bancor_protocol_whitepaper_en.pdf)) - 使用smart tokens将不同token进行转换的协议，特点是提供更好的流动性
  - [DutchX](https://dutchx.readthedocs.io/en/latest/index.html) ([代码](https://github.com/gnosis/dx-contracts), [docs](https://github.com/gnosis/dx-docs/blob/master/source/_static/docs/DutchX_Documentation.pdf)) - 使用荷兰式拍卖模式来提供更公平的价格的兼容ERC-20s的去中心化交易协议
  - [Hydro Protocol](https://hydroprotocol.io/) ([fork announcement](https://medium.com/hydro-protocol/why-we-are-forking-0x-97dc48ee0426), [代码](https://github.com/HydroProtocol), 原始白皮书已从官网擅长，备份[在此](https://whitepaper.io/document/170/hydro-protocol-whitepaper)) - 从0x分叉的版本，使用新的排序方案、匹配引擎、流动性共享模型
  - [Kyber](https://kyber.network) ([代码](https://github.com/kybernetwork), [白皮书](https://files.kyber.network/Kyber_Protocol_22_April_v0.1.pdf)) - 去中心化链上token交换协议，易于应用集成
  - [Loopring](https://loopring.org) ([代码](https://github.com/loopring), [白皮书](https://loopring.org/resources.html)) - 构建去中心化交易所的协议（中国团队）
  - [Ren](https://renproject.io/) ([代码](https://github.com/renproject), [白皮书](https://renproject.io/litepaper.pdf)) - 用于数字资产的原子交易的去中心化的暗池协议，之前叫做Republic
  - [Swap / AirSwap's Protocol](https://airswap.io) ([代码](https://github.com/airswap), [白皮书](https://swap.tech/whitepaper/)) - 点对点交易ERC-20通证的协议
  - [Uniswap](https://uniswap.io) ([代码](https://github.com/Uniswap), [白皮书](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)) - 用于以太坊上自动token交换的协议，围绕易用性、gas利用效率、审查阻力和零租金提取而设计。

- [Stellar](https://www.stellar.org/developers/guides/concepts/exchange.html) ([代码](https://github.com/stellar), [白皮书](https://www.stellar.org/papers/stellar-consensus-protocol.pdf)) - 金融应用场景的去中心化协议，支持构建去中心化交易所
  - [StellarX](https://www.stellarx.com/) (闭源) - 原生的Stellar交易所界面，开发者[Interstellar](https://interstellar.com/)
  - [Interstellar.exchange](https://interstellar.exchange/) (闭源) - 又是一个原生的Stellar交易所界面，由[Fintech](https://www.fintech.cm/)开发 (和Interstellar公司没有关联)
  - [Stellarport](https://stellarport.io) (闭源) - 一个Stellar交易所界面  - [Stellarterm](https://stellarterm.com/) ([代码](https://github.com/stellarterm/stellarterm)) - 一个开源的Stellar交易所界面

<a name="stablecoins" />

## 稳定币/Stablecoins

- 打白条模式（IOU / 中心化的）
  - Bitcoin / Omni
    - [Tether](https://tether.to) (闭源, [白皮书](https://tether.to/wp-content/uploads/2016/06/TetherWhitePaper.pdf)) - 基于美元质押的稳定币，但是对于是否1：1质押比较有争议，和Bitfinex交易所有较强的关联
  - Ethereum
    - [CENTRE USDC](https://www.centre.io/usdc) ([代码](https://github.com/centrehq), [白皮书](https://www.centre.io/pdfs/centre-whitepaper.pdf)) - ERC-20 格式的稳定币，原本是由[Circle](https://www.circle.com/en/usdc) 发行，现在由[Coinbase](https://blog.coinbase.com/coinbase-and-circle-announce-the-launch-of-usdc-a-digital-dollar-2cd6548d237)控制
    - [Gemini Dollar](https://gemini.com/dollar/) ([代码](https://github.com/gemini/dollar), [白皮书](https://gemini.com/wp-content/themes/gemini/assets/img/dollar/gemini-dollar-whitepaper.pdf)) - ERC-20 格式的稳定币，由Gemini发行
    - [Paxos](https://www.paxos.com/pax/) ([代码](https://github.com/paxosglobal/pax-contracts), [白皮书](https://www.paxos.com/wp-content/uploads/2019/02/PAX_Whitepaper.pdf)) - ERC-20 格式的稳定币，由Paxos Trust Company发行
    - [TrueUSD](https://www.trusttoken.com/trueusd/) ([代码](https://github.com/trusttoken/true-currencies)) - ERC-20 格式的稳定币，支持KYC/AML，由TrustToken发行
    - [DGX Token from Digix](https://digix.global/dgx) ([代码](https://github.com/DigixGlobal), [白皮书](https://github.com/DigixGlobal/digix-press-kit/blob/master/digix-whitepaper.pdf)) - 基于以太坊的和1克黄金挂钩的稳定币
  - Stellar
    - [AnchorUSD](https://www.anchorusd.com/) (闭源) - KYC/AML合规的, 基于美国银行账户
    - [Stronghold](https://stronghold.co/stronghold-usd/) (闭源, [白皮书](https://docsend.com/view/gg3p9ce)) - 基于Stellar的提供KYC/AMC合规的美元稳定币
    - [White Standard](https://thewhitecompanyus.com/white-standard/) ([代码](https://github.com/thewhitecompany/whitestandard#), [白皮书](https://thewhitecompanyus.com/white-paper)) - 基于Stellar的提供多种货币映射的稳定币
- 基于抵押的模式 (Collateralized)
  - [Celo](https://celo.org) ([白皮书](https://storage.googleapis.com/celo_whitepapers/Celo__A_Multi_Asset_Cryptographic_Protocol_for_Decentralized_Social_Payments.pdf)) - Celo 拥有与法定货币(如美元)挂钩的稳定代币,以尽量减少波动性。流通中的代币由多元化、超额担保(overcollateralized)和公开审计的加密资产储备提供支持。
  - Ethereum
    - [Dai Stablecoin from Maker](https://makerdao.com/dai) ([代码](https://github.com/makerdao), [白皮书](https://makerdao.com/whitepaper/)) - 基于智能合约的用于创建债务抵押头寸的稳定币
    - [Synthetix](https://www.synthetix.io/) ([rebranding announcement](https://blog.synthetix.io/havven-is-transforming-into-synthetix/), [代码](https://github.com/Synthetixio/synthetix), [白皮书](https://www.synthetix.io/uploads/synthetix_whitepaper.pdf)) - 以集中闭环支付网络为模型的去中心化稳定币,以前称为 Havven
     - [WBTC](https://www.wbtc.network) ([代码](https://github.com/WrappedBTC/bitcoin-token-smart-contracts), [白皮书](https://www.wbtc.network/assets/wrapped-tokens-whitepaper.pdf)) - ERC-20 格式的1：1抵押比特币
- 基于算法的模式(Algorithmic)
  - Ethereum
    - [Ampleforth](https://www.ampleforth.org/) ([rebranding announcement](https://medium.com/ampleforth/fragments-to-ampleforth-thoughts-behind-the-name-change-e38bf95077b2), [代码](https://github.com/ampleforth), [白皮书](https://www.ampleforth.org/paper/)) -基于货币政策的稳定币协议,以前称为Fragments
    - [Carbon](https://www.carbon.money/) ([白皮书](https://www.carbon.money/static/media/explainer.964136d4.pdf)) - 组合一篮子白名单中的tokens来构建的稳定币
    - [Terra](https://terra.money) ([代码](https://github.com/terra-project), [白皮书](https://s3.ap-northeast-2.amazonaws.com/terra.money.home/static/Terra_White_paper.pdf?fab2019)) - 通过算法扩展和收缩供应来确保价格稳定的协议。

<a name="lending-protocols" />

## 借贷协议 (Lending Protocols)

- Ethereum
  - [Compound](https://compound.finance) ([代码](https://github.com/compound-finance/), [白皮书](https://compound.finance/documents/Compound.Whitepaper.v04-83de48b6622ddd665234b41076d04c8b.pdf?vsn=d)) - 基于算法的货币市场协议（抵押代币来贷款，代币贬值可能被平仓）
  - [Dharma](https://www.dharma.io/) ([代码](https://github.com/dharmaprotocol) [白皮书](https://dharmaprotocol.github.io/developer-docs/#/)) - 使用代币化债务构建贷款产品的协议
  - [Ethlend](https://ethlend.io) ([代码](https://github.com/ETHLend), [白皮书](https://github.com/ETHLend/Documentation/blob/master/ETHLendWhitePaper.md)) - 点对点贷款市场
  - [Lendroid](https://www.lendroid.com) ([代码](https://github.com/lendroidproject), [白皮书](https://lendroid.com/assets/whitepaper-margin-trading.pdf)) - 支持去中心化贷款、保证金交易和卖空的协议
  - [Marble](https://marble.org) ([代码](https://github.com/marbleprotocol)) - 以太坊上的开放金融(Open Finance)
  - [Ripio](https://ripiocredit.network/) ([代码](https://github.com/ripio/rcn-network), [白皮书](https://ripiocredit.network/wp/RCN%20Whitepaper%20ENG.pdf)) - 基于共同签名智能合约的 P2P 全球信贷网络协议

<a name="derivative-protocols" />

## 金融衍生品/预测市场（Derivative Protocols/Prediction Markets）

- Ethereum
  - [Augur](https://www.augur.net) ([代码](https://github.com/AugurProject/augur), [白皮书](https://www.augur.net/whitepaper.pdf)) - 预测市场协议,使任何人"首次以低成本创建和投机衍生品"
  - [bZx](https://b0x.network) ([代码](https://github.com/bZxNetwork), [白皮书](https://b0x.network/pdfs/bZx_white_paper.pdf)) - 基于0x的的去中心化点对点保证金融资和交易协议
   - [CDx](https://cdxproject.com) ([代码](https://github.com/cdx-project), [白皮书](https://cdxproject.com/assets/resources/cdx-whitepaper.pdf)) - 通证化的信用违约互换协议
   - [Daxia](https://www.daxia.us) ([代码](https://github.com/DecentralizedDerivatives), [白皮书](https://github.com/DecentralizedDerivatives/DRCT_standard/blob/master/InDepthOverview.md)) - 通证化衍生工具协议
  - [dYdX](https://dydx.exchange) ([代码](https://github.com/dydxprotocol/protocol_v1), [白皮书](https://whitepaper.dydx.exchange/)) - 保证金交易和期权协议
  - [Gnosis](https://gnosis.io/) ([代码](https://github.com/gnosis), [白皮书](https://gnosis.io/pdf/gnosis-whitepaper.pdf)) -去中心化预测市场协议
  - [Market](https://marketprotocol.io) ([代码](https://github.com/MARKETProtocol), [白皮书](https://marketprotocol.io/assets/MARKET_Protocol-Whitepaper.pdf)) -  构建基于参考资产价格做未来结算的对等协商的协议
  - [UMA](https://umaproject.org) ([代码](https://github.com/umaprotocol), [白皮书](https://umaproject.org/UMA-whitepaper.pdf)) - 允许任何两个交易对手设计和创建自己的金融合同的协议,这些合同仅凭经济激励措施加以担保,使其自我执行并"全球可访问"
  - [Veil](https://veil.co) ([代码](https://github.com/veilco)) - 基于Augur、0x 和以太坊之上的点对点预测市场和衍生品平台

<a name="bundling-protocols" />

## 打包协议 (Bundling Protocols)

- Ethereum
  - [Basket Protocol](https://www.coinalpha.com/projects) ([代码](https://github.com/CoinAlpha/basket-protocol), [wiki](https://github.com/CoinAlpha/basket-protocol/wiki)) - 用于创建包含其他token组合的token协议
  - [BSKT](https://cryptofinlabs.github.io) ([代码](https://github.com/cryptofinlabs/bskt), [白皮书](https://github.com/cryptofinlabs/bskt-whitepaper/blob/master/bskt-whitepaper-v1.0.0.pdf)) - 创建去中心化通证组合的通用智能合约
  - [Set](https://www.setprotocol.com/) ([代码](https://github.com/SetProtocol/set-protocol-contracts), [白皮书](https://www.setprotocol.com/pdf/set_protocol_whitepaper.pdf)) - 用于创建、发行、赎回和再平衡可替代、抵押一篮子代币资产的协议

<a name="fund-protocols" />

## 资金(资产)协议 (Fund Protocols)

(Fund 不太好精准翻译，这里假定数字资产也是一种资金或资产)

- Ethereum
  - [Fund Protocol](https://www.coinalpha.com/projects) ([代码](https://github.com/CoinAlpha/fund-protocol), [wiki](https://github.com/CoinAlpha/fund-protocol/wiki)) - 以太坊上的资金管理协议
  - [Melonport](https://melonport.com) ([代码](https://github.com/melonproject), [绿皮书](https://github.com/melonproject/paper/blob/master/melonprotocol.pdf)) - 数字资产管理协议

<a name="tokenization-protocols" />

## 通证化协议 (Tokenization Protocols)

- Ethereum
  - [ERC-1404](https://erc1404.org/) ([代码](https://github.com/simple-restricted-token/simple-restricted-token), [eip](https://github.com/ethereum/EIPs/issues/1404)) - 发行对转账有限制的通证的开放标准协议（限制是为了更合规，更容易应用到证券化通证中）
  - [Harbor/R-Token](https://harbor.com) ([代码](https://github.com/harborhq), [白皮书](https://harbor.com/rtokenwhitepaper.pdf)) - 合规且标准化的加密证券发行和交易协议
  - [Polymath/ST-20](https://polymath.network) ([代码](https://github.com/PolymathNetwork), 原始白皮书备份在[这里](https://whitepaper.io/document/57/polymath-whitepaper)) - 证券代币化平台
  - [Abacus](https://abacusfi.com/) ([soure code](https://github.com/abacusfi), [白皮书](https://github.com/abacusfi/whitepaper/blob/master/whitepaper.pdf)) - 需要授权的通证协议
- [Stellar](https://www.stellar.org/) ([代码](https://github.com/stellar/stellar-core), [docs](https://www.stellar.org/developers/guides/concepts/assets.html)) - Stellar 原生支持发行任意tokens

<a name="kyc-aml-identity" />

## KYC/反洗钱/身份识别
- Ethereum
  - [Bloom](https://bloom.co) ([代码](https://github.com/hellobloom), [白皮书](https://bloom.co/whitepaper.pdf)) - 身份和信用评分协议
  - [Project Hydro](https://projecthydro.org/) ([代码](https://github.com/HydroBlockchain), [白皮书](https://github.com/HydroBlockchain/hydro-docs)) - 使用前沿加密技术保护用户帐户、身份和交易的分布式生态系统
  - [SelfKey](https://selfkey.org) ([代码](https://github.com/SelfKeyFoundation/Identity-Wallet), [白皮书](https://selfkey.org/selfkey-whitepaper)) - "Self-sovereign" 身份管理系统旨在与各种金融服务相集成
  - [Wyre](https://www.sendwyre.com) ([代码](https://github.com/sendwyre), [Medium post](https://blog.sendwyre.com/announcing-the-wyre-sdk-on-ramps-off-ramps-in-under-10-lines-of-code-f2b127eccb5d)) - Wyre 主要业务重点在跨境支付领域，尤其是中国与美国之间的市场。Wyre 使用比特币、以太坊、莱特币及其他区块链上结算交易，作为两国企业之间的交易媒介。


<a name="applications-tools" />

## 应用和工具
- Ethereum
  - [AMP](https://amp.credit/) - DeFi 软件开发，特别是UX相关的，比如 [EasyCDP](https://easycdp.com/), [SilverWire](https://silverwire.io/), [MultiSupply](https://multi.supply/) 和 [StableWire](https://stablewire.com/)
  - [Bloqboard](https://bloqboard.com) - 基于以太坊的贷款平台，用于抵押贷款的发起，清算和服务，由 Compound 和 Dharma 项目驱动
  - [Fetch](https://hellofetch.co) - 既用于价格发现和交易的去中心化交换聚合器，也是用于发现和管理分散贷款和借款的Dashboard的应用程序
  - [InstaDApp](https://instadapp.io) - "去中心化银行" 基于MakerDAO的用户接口，由[MakerScan](https://makerscan.io)开发
  - [Multis](https://multis.co) ([白皮书](https://multis.co/white-paper.html)) - 多重签名合约的用户界面，定位是"企业的加密资产银行"
  - [Settle](https://settle.finance) - 集成不同的加密工具（包括投资组合跟踪和DeFi协议集成）的Web界面，同时给开发者提供一个类似的“app store”
  - [Zerion](https://zerion.io) ([代码](https://github.com/zeriontech)) - 去中心化金融协议，定位是"无需信任的银行"

<a name="analytics" />

## 分析
- Ethereum
  - [0xTracker](https://0xtracker.com) - 0x protocol trade explorer and decentralised ERC-20 token price index 0x协议交易浏览器，去中心化的ERC-20 token 价格指数
  - [CuriousGiraffe](https://www.curiousgiraffe.io) - 用于分析 [AirSwap](https://www.curiousgiraffe.io/airswap/), [Augur](https://www.curiousgiraffe.io/augur/), [Compound](https://www.curiousgiraffe.io/compound/), 和 [KyberSwap](https://www.curiousgiraffe.io/kyberswap/)
  - [DEX Terminal](https://dexterminal.com) - 分布式金融活动的仪表板，包含交换量以及贷款/借款利率
  - [ETH in DeFi](https://mikemcdonald.github.io/eth-defi/) - Chart of the amount of ETH locked in DeFi products (Maker, Compound, Augur, dYdX, Uniswap)
  - [Loanscan](https://loanscan.io/) - Ethereum 贷款浏览器
  - [MakerScan](https://makerscan.io) - MakerDao 浏览器
  - [MKR Tools](https://mkr.tools/) - MakerDao 浏览器
  - [Uniswap ETH Liquidity](https://mikemcdonald.github.io/uniswap/eth-token-liquidity) - Uniswap的ETH流动性图表，按Token分类
  - [Predictions.Global](https://predictions.global/) - Augur 预测市场的仪表板
- [DeFI Pulse](https://defipulse.com/) - 关于锁定的美元金额信息的仪表板
- [Stablecoin Index](https://stablecoinindex.com/) - 体量比较大的稳定币图表
- [Stable Report](https://stable.report/) - 关于稳定币和常见稳定币列表的每周报道

<a name="misc" />

## 杂项
- Ethereum
  - [8x Protocol](https://8xprotocol.com) ([代码](https://github.com/8xprotocol), [白皮书](https://rawcdn.githack.com/8xprotocol/whitepaper/master/latest.pdf)) - 去中心化的订阅支付协议
  - [AZTEC Protocol](https://www.aztecprotocol.com) ([代码](https://github.com/AztecProtocol/AZTEC), [白皮书](https://github.com/AztecProtocol/AZTEC/blob/master/AZTEC.pdf)) - 支持隐私保护的以太坊网络上的保密交易协议
  - [Centrifuge](https://www.centrifuge.io) ([代码](https://github.com/centrifuge), [白皮书](https://centrifuge.io/centrifuge_os_white_paper.pdf)) - 供应链金融平台, 包括发票、采购订单等的交易。
  - [Groundhog](https://groundhog.network) - 端到端的去中心化定期订阅支付平台

<a name="community" />

## 社区
* [DeFi Reddit](https://www.reddit.com/r/defi/)
* [DeFi Telegram](https://t.me/de_fi)
* ++ [ATA DeFi 研究院](https://www.atatech.org/groups/2828)

<a name="contributions" />

## 参与和贡献

翻译自 [awesome-decentralized-finance](https://github.com/congdepeng/awesome-decentralized-finance)

参与方式详见原始 git repository。


## 后记

- 通篇用的比较多的单词是Protocol，所谓协议就是理论上不绑定具体实现方案，项目发起方基于一个理念创建了项目并做了参考实现，只要符合这个协议，不会将你绑定在具体实现上。
