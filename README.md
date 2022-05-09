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
- [合约开发](#合约开发)
- [国库管理](#国库管理)
- [DAO 产生器](#DAO-产生器)
- [DAO 工具](#DAO-工具)
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
- [Snapshot](https://snapshot.org/) - 完全开源的链下治理投票平台

## 反女巫攻击

- :open_file_folder: [BrightId AntiSybil package](https://github.com/BrightID/BrightID-AntiSybil) - 提供了多种反女巫算法的 Python 分析框架
- :open_file_folder: [Uniswap sybil interface](https://github.com/Uniswap/sybil-interface) - 用于挖掘潜在投票代理的治理工具，并面对可能的女巫攻击
    - :open_file_folder: [Uniswap/sybil-list](https://github.com/Uniswap/sybil-list) - 列出了与 Uniswap 治理相关的 ETH 地址链结到的 Twitter 帐户
- [sybil.org](https://sybil.org/) 几个知名的 DAO 治理相关 ETH 地址投票代理信息
- :open_file_folder: [sybil verifier worker](https://github.com/Uniswap/sybil-verifier-worker) - Uniswap 治理 ETH 地址与 Twitter 帐户验证器 (nodejs)
- :open_file_folder: [Pando](https://github.com/pandonetwork/pando) - 基于 IPFS、ethereum 和 aragonOS 的 git 分布式远程协议

## 合约开发

- :open_file_folder: [CodeforDAO/contracts](https://github.com/CodeforDAO/contracts) - 适用于小型新创团队的 DAO 合约框架


## 国库管理

- :open_file_folder: [LDO purchase executor](https://github.com/lidofinance/ldo-purchase-executor) -负责购买 LDO 代币回国库的合约
- :open_file_folder: [Conviction Voting (Aragon App)](https://github.com/1Hive/conviction-voting-app) - 对信念投票结果进行资金拨款的合约

## DAO 产生器

- [daohaus.club](https://daohaus.club) - 由社区赞助，采用 [CCO](https://daohaus.substack.com/p/-what-is-a-community-contribution?s=r) 方式建立与管理 DAO 的平台
- :open_file_folder: [daostack/DAOstack-Hackers-Kit](https://github.com/daostack/DAOstack-Hackers-Kit) - DAOstack 提供建立 DAO 的完整工具包
- :open_file_folder: [JoinColony/colonySDK](https://github.com/JoinColony/colonySDK) - DAO 基础设施平台 Colony 开源 SDK
- :open_file_folder: [aidenlab/juicebox](https://github.com/aidenlab/juicebox/wiki/Download) - DAO 金库管理与募资平台 Juicebox 下载页面

## DAO 工具

- :open_file_folder: [sourcecred/sourcecred](https://github.com/sourcecred/sourcecred) - 开放式协作的信誉协议


## 仪表板

- [Dune analytics](https://dune.com/browse/dashboards) - 链上分析数据平台 Dune analytics 可看到 DAO NFT, 代币发放等信息


## :wave: Contribute

GitHub 上有许多以 "Awesome-XXX" 命名的项目，主要是为了发扬 [Awesome 清单](https://github.com/sindresorhus/awesome/blob/master/awesome.md) 的开源精神，欢迎加入一起编写与修改此条目。

## License

[Unlicense](https://unlicense.org)

