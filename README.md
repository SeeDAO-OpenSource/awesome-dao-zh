# :open_book: DAO 相关开源工具精选中文版 :open_book:

<p align="left">
    <a href="https://github.com/sindresorhus/awesome">
        <img src="https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
    </a>
    <a href="https://github.com/SeeDAO-OpenSource/awesome-dao-zh/network">
        <img src="https://img.shields.io/github/forks/SeeDAO-OpenSource/awesome-dao-zh.svg"
             alt="forks">
    </a>
    <a href="https://github.com/SeeDAO-OpenSource/awesome-dao-zh/stargazers">
        <img src="https://img.shields.io/github/stars/SeeDAO-OpenSource/awesome-dao-zh.svg"
             alt="stars">
    </a>
    <a href="https://unlicense.org">
        <img src="https://img.shields.io/badge/license-unlicense-blue"
             alt="license">
    </a>
</p>

本列表主要搜集各种与 DAO 的经营、运作相关的开源工具与学习资源，欢迎提出 PR 与相关建议，更多请阅读 [贡献指南](CONTRIBUTING.md)，本文件以 [Unlicense](https://unlicense.org) 释出。如果是开源项目，会在条目前面加上 :open_file_folder:　`:open_file_folder:` 标示。

[什么是 DAO?](https://zh.m.wikipedia.org/zh-cn/分布式自治组织)

### :balance_scale:	收录标准

:warning: 主要请聚焦在 DAO 有关之工具、代码方面的开发资源，请勿张贴关于 DAO 研究与行业调研资讯

## :sunglasses: 其他 Awesome

本文件会不定期从国际上 DAO 相关 Awesome 清单中更新资料过来，例如：
- [DAOresearch/awesome-daos](https://github.com/DAOresearch/awesome-daos) (已停止更新)
- [castle-finance/awesome-dao-treasury-mgmt](https://github.com/castle-finance/awesome-dao-treasury-mgmt)
- [windranger-io/awesome-dao](https://github.com/windranger-io/awesome-dao)
- [deltaDAO/awesome-dao](https://github.com/deltaDAO/awesome-dao)

其他中文相关 Web3 的 Awesome 清单：
- [dily3825002/awesome-ethereum-cn](https://github.com/dily3825002/awesome-ethereum-cn) - 以太坊开发资源汇总
- [houbb/awesome-metaverse-zh](https://github.com/houbb/awesome-metaverse-zh) - 关于 Metaverse 的精彩项目和信息资源列表

## 目录

- [DAO 列表](#dao-列表)
- [投票工具](#投票工具)
- [反女巫攻击](#反女巫攻击)
- [教育学习](#教育学习)
- [合约开发](#合约开发)
- [国库管理](#国库管理)
- [DAO 产生器](#DAO-产生器)
- [DAO 工具](#DAO-工具)
- [社群经营](#社群经营)
- [仪表板](#仪表板)

## DAO 列表

能列出所有 DAO ，或是某一类的 DAO 与相关信息资讯

- [deepdao.io](http://deepdao.io/organizations) - 去中心化信息分析平台 DeepDAO
- [coinmarketcap.com/view/dao/](https://coinmarketcap.com/view/dao/) - 由市值 (Market Cap) 大小排序的 DAO 排行榜
- [defirate.com](https://defirate.com) - DeFi DAO 的讯息平台
- [DAOs list - DAO Incubator](https://ecosystem.daoincubator.org/wiki/dao) - 由一群Web3 Builder, Designer 和专家组成的平台，致力于使当前 DAO 更具功能性
- [OpenOrgs.info](https://openorgs.info/) - OpenOrgs.info 提供了知名 DAOs 详细的金库数据信息

## 投票工具

- [Tally](https://www.tally.xyz) - 提供 DAO 治理基础设施的平台
- :open_file_folder:　[Snapshot](https://github.com/snapshot-labs/snapshot) - 完全开源的链下治理投票平台

## 反女巫攻击

- :open_file_folder: [BrightId AntiSybil package](https://github.com/BrightID/BrightID-AntiSybil) - 提供了多种反女巫算法的 Python 分析框架
- :open_file_folder: [Uniswap sybil interface](https://github.com/Uniswap/sybil-interface) - 用于挖掘潜在投票代理的治理工具，并面对可能的女巫攻击
    - :open_file_folder: [Uniswap/sybil-list](https://github.com/Uniswap/sybil-list) - 列出了与 Uniswap 治理相关的 ETH 地址链结到的 Twitter 帐户
- [sybil.org](https://sybil.org/) 几个知名的 DAO 治理相关 ETH 地址投票代理信息
- :open_file_folder: [sybil verifier worker](https://github.com/Uniswap/sybil-verifier-worker) - Uniswap 治理 ETH 地址与 Twitter 帐户验证器 (nodejs)
- :open_file_folder: [Pando](https://github.com/pandonetwork/pando) - 基于 IPFS、ethereum 和 aragonOS 的 git 分布式远程协议
- :open_file_folder: [Minimal Anti-Collusion Infrastructure (MACI)](https://github.com/appliedzkp/maci) - 最小化反共谋基础设施 ([中文介绍](https://medium.com/taipei-ethereum-meetup/zkp-%E8%AE%80%E6%9B%B8%E6%9C%83-maci-1faa658a026))

## 教育学习

- :open_file_folder: [DAO的研究和探索计划 (Dapp Learning DAO)](https://github.com/Dapp-Learning-DAO/Dapp-Learning/tree/main/dao) - DApp 学习指南中有关 DAO 的学习任务

## 合约开发

- :open_file_folder: [CodeforDAO/contracts](https://github.com/CodeforDAO/contracts) - 适用于小型新创团队的 DAO 合约框架
- :open_file_folder: [Nemesis DAO](https://github.com/NemesisDao/Contracts) - Nemesis DAO (Defi DAO) 使用的合约
- :open_file_folder: [Bonding Curve aka．Automatic Market Maker Contract](https://github.com/relevant-community/bonding-curve) - 联合曲线 AMM 合约
- :open_file_folder: [Bonds Module](https://github.com/relevant-community/bonding-curve) - 使用 Cosmos SDK 实现联合曲线功能
- :open_file_folder: [Moloch V1](https://github.com/MolochVentures/moloch/tree/minimal-revenue/v1_contracts) - 协调与管理财库为主的 DAO 合约框架
- :open_file_folder: [Moloch V2](https://github.com/MolochVentures/moloch) - 从 V1 版本简化了许多机制，并解决安全性问题
- :open_file_folder: [Moloch V3](https://github.com/Moloch-Mystics/moloch-v3) - 实现 Moloch 模块化，方便与其他 DAO 合约整合使用
- :open_file_folder: [TrojanDAO V2](https://github.com/TROJANFOUNDATION/Trojan-DAO-Token-Engineering) - 募资与协调和管理才库的 DAO 合约框架, 整合 Moloch DAO 与联合曲线功能
- :open_file_folder: [daohaus-contracts](https://github.com/DAOhaus/daohaus-contracts) - DAOHaus 治理合约
- :open_file_folder: [Moloch Minion](https://github.com/raid-guild/moloch-minion) - 由 Moloch DAO 投票通过后可呼叫执行的合约框架
- :open_file_folder: [Open Grants](https://github.com/raid-guild/open-grants) - Raid Guild 开发的 EVM 公共物品筹资合约与网站框架
- :open_file_folder: [token-request-app](https://github.com/1Hive/token-request-app) - 1Hive 代幣購買 App 合約
- :open_file_folder: [redemptions-app](https://github.com/1Hive/redemptions-app) - 1Hive 代幣賣回退款 App 合約
- :open_file_folder: [Limited Liability DAOs](https://github.com/dOrgTech/LL-DAO) - dOrg 發起匹配美國LLC公司結構的 DAO 框架
- :open_file_folder: [Limited Liability DAOs](https://github.com/dOrgTech/LL-DAO) - dOrg 發起匹配美國LLC公司結構的 DAO 框架


## 国库管理

- :open_file_folder: [LDO purchase executor](https://github.com/lidofinance/ldo-purchase-executor) -负责购买 LDO 代币回国库的合约
- :open_file_folder: [Conviction Voting (Aragon App)](https://github.com/1Hive/conviction-voting-app) - 对信念投票结果进行资金拨款的合约
- :open_file_folder: [gnosis/zodiac](https://github.com/gnosis/zodiac) - 在 Gnosis Safe 上的 DAO 扩展工具
- :open_file_folder: [safe-global/safe-react](https://github.com/safe-global/safe-react/releases) - Gnosis Safe 桌面版应用下载页面

## DAO 产生器

- [daohaus.club](https://daohaus.club) - 由社区赞助，采用 [CCO](https://daohaus.substack.com/p/-what-is-a-community-contribution?s=r) 方式建立与管理 DAO 的平台
- :open_file_folder: [daostack/DAOstack-Hackers-Kit](https://github.com/daostack/DAOstack-Hackers-Kit) - DAOstack 提供建立 DAO 的完整工具包
- :open_file_folder: [JoinColony/colonySDK](https://github.com/JoinColony/colonySDK) - DAO 基础设施平台 Colony 开源 SDK
- :open_file_folder: [aidenlab/juicebox](https://github.com/aidenlab/juicebox/wiki/Download) - DAO 金库管理与募资平台 Juicebox 下载页面
- :open_file_folder: [AmbassaDAOs](https://github.com/Multi-DAO/ambassadaos) - 让多个 DAO 一起透过 MultiDAO 发起联盟大使 DAO (Near)
- :open_file_folder: [aragon/dao-templates](https://github.com/aragon/dao-templates/) - Aragon DAO 模板框架


## DAO 工具

- :open_file_folder: [sourcecred/sourcecred](https://github.com/sourcecred/sourcecred) - 开放式协作的信誉协议
- :open_file_folder: [AraCred](https://github.com/aragon/Aracred) - Aragon 客制化且自动化执行的 SourceCred
- :open_file_folder: [TokenSPICE](https://github.com/tokenspice/tokenspice) - EVM 代理人为主的代币经济模型模拟器
- :open_file_folder: [solsim](https://github.com/tokenspice/tokenspice) - Solana 复杂系统模拟器 (模拟 Defi 协议, DAO 治理)
- :open_file_folder: [Commons Simulator](https://github.com/commons-stack/commons-simulator) - 代币经济的简易模拟器
- :open_file_folder: [Zksync Gitcoin Tax Helper](https://github.com/zcstarr/zksync-tax-helper#pico-dao) - 产生在 zksync 上的交易列表以供报税
- :open_file_folder: [OpenRaise](https://github.com/dOrgTech/OpenRaise) - dOrg 發起便于以联合曲线和 [DAICO](https://coinmarketcap.com/alexandria/glossary/decentralized-autonomous-initial-coin-offerings-daico) 进行募资的合约框架
- :open_file_folder: [DiscordSay](https://github.com/Ysail/DiscordSay) - 使用 Python 的 Discord 水群机器人 (自动发言灌水)
- :open_file_folder: [IdentDeFi](https://github.com/Identdefi/contracts) - ERC721合约建立不可转让NFT达到KYC的零知识证明 [[ETHDenver 2022 获奖项目](https://mirror.xyz/foresightnews.eth/sJVgzId93eD_LgM-th7sYOlF2Nz9MgDWp9tTP_3pMkw)]
- :open_file_folder: [Deus Ex Securitas](https://github.com/DicksonWu654/ethdenverhack) - 使用机器学习自动审计合约 (目前只能判斷重入攻擊) [[ETHDenver 2022 获奖项目](https://mirror.xyz/foresightnews.eth/sJVgzId93eD_LgM-th7sYOlF2Nz9MgDWp9tTP_3pMkw)]
- :open_file_folder: [Blocksnap](https://github.com/jaydenwindle/blocksnap) - 对链上数据快照生成工具 (python) [[ETHDenver 2022 获奖项目](https://mirror.xyz/foresightnews.eth/sJVgzId93eD_LgM-th7sYOlF2Nz9MgDWp9tTP_3pMkw)]
- :open_file_folder: [DeFi and DAO tokenomics](https://github.com/dgeorgiev06/awesome-ethereum-diagrams#defi-and-dao-tokenomics) - awesome-ethereum-diagrams 中 DAO 代币经济流程图
- :open_file_folder: [AraGraph](https://github.com/ConsenSys/aragraph) - Aragon DAO 權限關係視覺化
- :open_file_folder: [DAOcreator](https://github.com/dOrgTech/DAOcreator) - dOrg 提供快速建立 DAO 的工具 (nodejs)

## 法律会计

- :open_file_folder: [LAO Templates](https://github.com/DAOresearch/lao-templates) - 提供建立一个与当前法律兼容的 DAO 模板
- :open_file_folder: [SCoDA – Simple Code Deference Agreement](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-/) - 以 SCoDA 精神设计的具法律约束力合约框架
-:open_file_folder: [Crypto Comix Hackathon Pitch ](https://github.com/JurisProject/crypto-comix) - 符合美国非营利合作社规范的 DAO 模板 ([章程](https://github.com/DAOresearch/crypto-comix/blob/master/docs/doc5.md))
- :open_file_folder: [LexDAO Constitution Information](https://github.com/lexDAO/LexDAO-Constitution) - LexDAO 符合美国怀俄明州非法人合作社规定的 DAO 章程模板 ([章程](https://github.com/lex-node/SCoDA-Simple-Code-Deference-Agreement-/blob/master/DAO%20Charter%20with%20Qualified%20Code%20Deference.md))
- :open_file_folder: [The Grimoire Operating Agreement](https://github.com/metacartel/MCV/wiki/The-Grimoire---Operating-Agreement) - 将 DAO 作为投资俱乐部的 DAO 章程协议
- :open_file_folder: [Digital Organization Designs](https://github.com/open-esq/Digital-Organization-Designs) - 透过 js,solidity 定义的公司结构与相关协作法则
- :open_file_folder: [SCoDAO – Simple Code Deference Agreement for DAO](https://github.com/open-esq/SCoDAO-Simple-Code-Deference-Agreement-for-DAO) - 以 SCoDA 精神规定的 DAO 的运作规定
- :open_file_folder: [TermSheets.me](https://github.com/open-esq/termsheet) - 以 [YC 标准](https://www.ycombinator.com/series_a_term_sheet/) 制定的 Term Sheet 工具协助 DAO 募资
- :open_file_folder: [MetaCartel Venture DAO Wiki](https://github.com/metacartel/MCV/wiki) - 以 Moloch V2 为基础的 Venture DAO 合约与法律文件
- :open_file_folder: [AIT](https://github.com/lexDAO/AIT) - 符合美国法律 [D 506(c)](https://www.investor.gov/introduction-investing/investing-basics/glossary/rule-506-regulation-d) 保护投资人隐私的合格投资人注册表 (ERC721)
- []()


## 社群经营

- [DAO Canvas (PDF)](https://drive.google.com/uc?export=download&id=1vJeo4PCGTj1G17n6es9g4Pn0cmCgSG_F) - DAOstack 发行的 DAO 思维画布图 ([备份](files/DAOcanvas%20v0.3%20Nippon.pdf))
- :open_file_folder: [Orbit Model](https://github.com/orbit-love/orbit-model) - 一个社群经营框架 (可集成 Slack, Discord, Discourse...)
- :open_file_folder: [Giveaway bot on Twitter with Twitter API V2](https://github.com/June911/twitter_giveway_bot) - Twitter 自动抽奖脚本
- :open_file_folder: [Conviction Voting (Aragon App)](https://github.com/1Hive/conviction-voting-app) - 对信念投票结果进行资金拨款的合约
- :open_file_folder: [ArgoDisco](https://github.com/acolytec3/ArgoDisco) - Aragon DAO Discord 机器人
- :open_file_folder: [Web 3 Revenue Primitives](https://github.com/FEMBusinessModelsRing/web3_revenue_primitives) - Web3 商业模式分析框架
- :open_file_folder: [Gitcoin DAO OKRs Example](https://github.com/dex-guru/dao-research/blob/main/DAO%20as%20a%20Product%200f09458415ef489d805f76fc6fc7d6a4/Metrics%20a1525449914f49e7bb83fbf3c4b3d13a/Gitcoin%20DAO%20OKRs%20Example%2006548e00ff1a4e24b064fc4d278ab740.md) - Gitcoin DAO 采用 OKRs 范例
- :open_file_folder: [Onboarding & Working Groups &　Decision Making Process](https://github.com/dex-guru/dao-research/blob/main/DAO%20as%20a%20Product%200f09458415ef489d805f76fc6fc7d6a4/Metrics%20a1525449914f49e7bb83fbf3c4b3d13a/Gitcoin%20DAO%20OKRs%20Example%2006548e00ff1a4e24b064fc4d278ab740.md) - Index Coop Onboarding 与工作小组处理流程
- :open_file_folder: [DAO Metrics](https://github.com/dex-guru/dao-research/blob/main/DAO%20as%20a%20Product%200f09458415ef489d805f76fc6fc7d6a4/Metrics%20a1525449914f49e7bb83fbf3c4b3d13a/DAO%20Metrics%207c04a1bd65584e368113602cfef09c58.md) - DexGuru 整理出基于社会学与经济学理论的 DAO 衡量指标
- :open_file_folder: [SubDAO Mechanics](https://github.com/dex-guru/dao-research/blob/main/DAO%20as%20a%20Product%200f09458415ef489d805f76fc6fc7d6a4/SubDAO%20Mechanics%209ada5f159625471b94ed9b05e188180b.md) - DexGuru 整理 SubDAO 的运作机制流程图

## 仪表板

- [Dune analytics](https://dune.com/browse/dashboards) - 链上分析数据平台 Dune analytics 可看到 DAO NFT, 代币发放等信息


## :wave: Contribute

GitHub 上有许多以 "Awesome-XXX" 命名的项目，主要是为了发扬 [Awesome 清单](https://github.com/sindresorhus/awesome/blob/master/awesome.md) 的开源精神，欢迎加入一起编写与修改此条目。

## License

[Unlicense](https://unlicense.org)

