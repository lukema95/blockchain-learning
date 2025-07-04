# Blockchain Learning
个人区块链学习笔记📒，包括共识算法、密码学、虚拟机、智能合约、零知识证明等，大部分参考资料来源于网上🕸️，加上个人的一些加工和总结🏭。

## 目录
- [Blockchain Learning](#blockchain-learning)
  - [目录](#目录)
  - [🚀共识算法](#共识算法)
    - [导论](#导论)
    - [PBFT算法](#pbft算法)
    - [Raft算法](#raft算法)
    - [Tendermint算法](#tendermint算法)
  - [🔑密码学](#密码学)
  - [🤖️虚拟机](#️虚拟机)
  - [📒智能合约](#智能合约)
    - [📒学习笔记](#学习笔记)
      - [🔥DeFi](#defi)
    - [🕸️学习资料](#️学习资料)
      - [🔥Solidity](#solidity)
    - [🔐安全](#安全)
    - [🔧工具](#工具)
    - [🔌插件](#插件)
    - [📜博客](#博客)
  - [🧀零知识证明](#零知识证明)
    - [💾学习资料](#学习资料)
    - [🔧开源工具](#开源工具)
    - [🔥相关项目](#相关项目)
    - [📜文章博客](#文章博客)
  - [📚区块链书籍](#区块链书籍)
    - [Bitcoin](#bitcoin)
    - [Ethereum](#ethereum)


## 🚀共识算法
### [导论](/consensus/Guide.md)
### [PBFT算法](/consensus/PBFT.md)
### [Raft算法](/consensus/Raft.md)
### [Tendermint算法](/consensus/Tendermint.md)

## 🔑密码学
- [SM2国密算法](/cryptography/SM2.md)
- [RSA算法](/cryptography/RSA.md)

## 🤖️虚拟机
- TODO

## 📒智能合约

### 📒学习笔记
#### 🔥DeFi
- [dydx-v2 合约源码解读](/defi/dydx/README.md)

### 🕸️学习资料
#### 🔥Solidity
- [Solidity中文文档](https://solidity-cn.readthedocs.io/)
- [OpenZeppeline](https://docs.openzeppelin.com/) - OpenZeppeline 文档
- [Solidity by Example](https://solidity-by-example.org/) - Solidity 例子
- [WTF-Solidity](https://github.com/AmazingAng/WTF-Solidity) - Solidity 中文系列课程
- [gas-puzzles](https://github.com/RareSkills/gas-puzzles) - 一系列用于实践 Gas 优化的智能合约。
- [WTF-gas-optimization](https://github.com/WTFAcademy/WTF-gas-optimization) - Gas优化技术，经 Foundry 验证。
- [learning-solidity](https://github.com/willitscale/learning-solidity) - Solidity 文档和 YouTube 教程
- [awesome-solidity](https://github.com/bkrem/awesome-solidity) - 精选的 Solidity 资源、库、工具等列表
- [smart-contract-best-practices](https://github.com/ConsenSys/smart-contract-best-practices) - ConsenSys 关于合约的最佳实践仓库
- [Dapp-Learning](https://github.com/Dapp-Learning-DAO/Dapp-Learning) - 适合各个阶段开发者的Dapp学习项目
- [solidity-expert](https://github.com/dukedaily/solidity-expert) - 以太坊开发教程
- [Smart Contract Weakness Classification (SWC) ](https://swcregistry.io/) - 智能合约弱点分类
- [Capture the Ether](https://capturetheether.com/) - 以太坊智能合约安全游戏
- [CryptoZombies](https://cryptozombies.io/) - CryptoZombies是一个互动学校，教你所有关于区块链的技术知识。通过制作自己的加密收藏品游戏来学习编写智能合约。
- [DeFi-Developer-Road-Map](https://github.com/OffcierCia/DeFi-Developer-Road-Map) - 以太坊智能合约开发路线图
- [solmate](https://github.com/transmissions11/solmate) - 现代、有主见的、gas优化的智能合约
- [solady](https://github.com/Vectorized/solady) - Gas优化的Solidity库

### 🔐安全
- [Alchemy Security Tools](https://www.alchemy.com/dapps/top/security-tools) - Alchemy 安全工具合集，包括173个最佳的Web3安全工具
- [DeFiHackLabs](https://github.com/SunWeb3Sec/DeFiHackLabs) - 使用Foundry重现DeFi被黑事件
- [DeFiVulnLabs](https://github.com/SunWeb3Sec/DeFiVulnLabs) - 使用 Foundry 了解常见的智能合约漏洞
- [solidity-security-blog](https://github.com/sigp/solidity-security-blog) - Solidity 安全，已知攻击媒介和常见反模式的综合列表
- [awesome-ethereum-security](https://github.com/crytic/awesome-ethereum-security) - 精彩的以太坊安全参考精选列表
- [WTF-solcurity](https://github.com/WTFAcademy/WTF-solcurity) - Solidity 智能合约的公认安全和代码质量标准
- [solsec](https://github.com/sannykim/solsec) - 研究Solana智能合约安全性，审核和利用的资源集合
- [web3-security-resources](https://github.com/Raiders0786/web3-security-resources) - 区块链安全资源
- [public-audits](https://github.com/Frankcastleauditor/public-audits) - Frankcastle 私有/公开的个人智能合约审计报告
- [PublicReports](https://github.com/HalbornSecurity/PublicReports) - Halborn 公开的智能合约审计报告
- [security-and-auditing-full-course-s23](https://github.com/Cyfrin/security-and-auditing-full-course-s23) - 安全审计全栈课程
- [Blockchain-Attack-Vectors](https://github.com/ImmuneBytes-Security-Audit/Blockchain-Attack-Vectors) - 引用，分类和减轻区块链攻击向量的框架
- [awesome-solana-security](https://github.com/0xMacro/awesome-solana-security) - Solana 安全资源
- [50-days-of-crushing-audits](https://github.com/0xaudron/50-days-of-crushing-audits) - 50天破解智能合约
- [Cryptocurrency-Security-Audit-Guide](https://github.com/slowmist/Cryptocurrency-Security-Audit-Guide/tree/main) - 慢雾加密货币安全审计导论
- [Blockchain Security Audit List](https://github.com/0xNazgul/Blockchain-Security-Audit-List) - 区块链安全审计公司、独立审计师和公共审计地点列表

### 🔧工具
- [slither](https://github.com/crytic/slither) - Solidity 静态分析工具
- [mythx](https://mythx.io/) - Mythril 是一个基于符号执行的以太坊虚拟机字节码安全分析工具，用于检测以太坊和其他 EVM 兼容区块链构建的智能合约中的安全漏洞。
- [echidna](https://github.com/crytic/echidna) - Echidna 是一个基于符号执行的智能合约模糊测试工具，用于检测智能合约中的安全漏洞。
- [Remix](https://remix.ethereum.org/) - Solidity IDE
- [Hardhat](https://hardhat.org/) - 以太坊专业开发环境。它由用于编辑、编译、调试和部署智能合约和 dApp 的不同组件组成，所有这些组件共同创建一个完整的开发环境。
- [Foundry](https://github.com/foundry-rs/foundry) - Foundry 是一个使用 Rust 编写的用于以太坊应用程序开发的速度极快、可移植且模块化的工具包。
- [Pinata](https://www.pinata.cloud/) - IPFS存储，合约图片存储
- [evm.code](https://www.evm.codes/) - 在线以太坊虚拟机操作码文档及交互
- [mythril](https://github.com/ConsenSys/mythril) - EVM字节码的安全分析工具。支持为以太坊、Hedera、Quorum、Vechain、Roostock、Tron 和其他 EVM 兼容区块链构建的智能合约
- [tenderly](https://tenderly.co/) - 使 Web3 开发人员能够构建、测试、监控和操作智能合约，从智能合约的诞生到大规模采用。
- [Phalcon](https://phalcon.xyz/) - Phalcon 是一款面向加密项目和开发人员的安全开发套件
- [ABI to interface](https://gnidan.github.io/abi-to-sol/) - 从 ABI JSON 生成 Solidity 接口
- [ETH Calldata Decode](https://calldata-decoder.apoorv.xyz/) - 解码以太坊 calldata
- [Get ABI for unverified contracts](https://abi.w1nt3r.xyz/) - 猜测任何以太坊合约的 ABI，即使它没有在 Etherscan 上验证。
- [Dedaub](https://library.dedaub.com/decompile) - Dedaub 反编译器采用以太坊虚拟机 (EVM) 字节码并生成更具可读性的类似 Solidity 的代码，从而可以更好地理解未经验证的智能合约

### 🔌插件
- [Solidity Debugger Pro](https://marketplace.visualstudio.com/items?itemName=robertaachenw.solidity-debugger-pro): VSCode 插件，Solidity 的独立调试器
- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor): VSCode 插件，提供可视化安全审计、以安全为中心的语法和语义突出显示、详细的类大纲、UML图生成器，以及许多其他特性。
- [Ethlink](https://github.com/duaraghav8/Ethlint): Solidity 代码风格检查
- [hardhat-solhint](https://hardhat.org/hardhat-runner/plugins/nomiclabs-hardhat-solhint): Hardhat插件, 代码风格检查
- [hardhat-gas-reporter](https://www.npmjs.com/package/hardhat-gas-reporter): Hardhat插件, 生成Gas消耗报告

### 📜博客
- [Solidity 可升级合约](https://mousy-butter-cb8.notion.site/Solidity-66247ec460764824b31a85e16a39aa3a?pvs=4)
- [如何使用 Hardhat 在 Etherscan 上验证智能合约](https://blog.chain.link/how-to-verify-smart-contract-on-etherscan-hardhat/)
- [如何创建 NFT 像素艺术收藏系列文章](https://dev.to/balt1794/series/17526)
- [默克尔树在NFT白名单中的应用](https://mirror.xyz/clearlove.eth/wgDFvBx1ER-UyweTQoLFvO3ghRtLg6NPkTtKvCab-EE)
- [减少智能合约 Gas 消耗的 8 种方法](https://medium.com/coinmonks/8-ways-of-reducing-the-gas-consumption-of-your-smart-contracts-9a506b339c0a)
- [如何部署和使用可升级的智能合约](https://mp.weixin.qq.com/s/jiA20s8ImXM-H18XCIqzpw)
- [了解以太坊智能合约存储](https://programtheblockchain.com/posts/2018/03/09/understanding-ethereum-smart-contract-storage/)
- [Solidity 中编写内联汇编(assembly)的那些事](https://learnblockchain.cn/article/675)
- [How to become a smart contract auditor](https://cmichel.io/how-to-become-a-smart-contract-auditor/)
- [Capture The Ether Solutions](https://cmichel.io/capture-the-ether-solutions/)
- [Ethernaut Solutions](https://cmichel.io/ethernaut-solutions/)
- [Damn Vulnerable DeFi Solutions](https://cmichel.io/damn-vulnerable-de-fi-solutions/)
- [Paradigm CTF 2021 Solutions](https://cmichel.io/paradigm-ctf-2021-solutions/)
- [How Diamond Storage Works](https://dev.to/mudgen/how-diamond-storage-works-90e)


## 🧀零知识证明
### 💾学习资料
- [learn.0xparc.org](https://learn.0xparc.org/) - 0xPARC的应用ZK学习小组，包含ZK及电路系列课程
- [Zero Knowledge Proofs](https://zk-learning.org/) - 斯坦福大学ZKP MOOC
- [[MIT IAP 2023] Modern Zero Knowledge Cryptography](https://zkiap.com/) - MIT零知识证明系列课程
- [ABCDE ZK Hacker Camp Curriculum Schedule](https://abcdelabs.github.io/zkcamp) - ABCDE ZK 课程
- [awesome-zero-knowledge-proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs) - Matter Lab 的 ZKP 资源汇总
- [Zero-Knowledge Proofs Starter Pack](https://ethresear.ch/t/zero-knowledge-proofs-starter-pack/4519) - 以太坊社区有关ZKP的教程资源
- [Demystifying Zero Knowledge Proofs [FINAL]](https://docs.google.com/presentation/d/1gfB6WZMvM9mmDKofFibIgsyYShdf0RV_Y8TLz3k1Ls0/edit#slide=id.g443f641f0b_1_89) - ZKP 学习PPT
- [ZKP Science](https://zkp.science/) - 权威ZKP学术研究
- [ZKSpace](https://zks.org/) - ZKP 学习社区
- [ZK Hack](https://zkhack.dev/) - ZK 学习和构建的中心。
- [zk-SNARKs: A Gentle Introduction](https://www.di.ens.fr/~nitulesc/files/Survey-SNARKs.pdf) - ZK SNARKs 论文
- [ZKP 系列学习文章](https://airtable.com/shrErOf7fj5aPZONr/tblKK5oXs9qpjnVKh) - 循序渐进的ZKP学习资料
- [moonmath-manual](https://github.com/LeastAuthority/moonmath-manual) - 为任何有兴趣了解和释放 zk-SNARK 潜力的人（从初学者到专家）提供的资源。
- [Baby SNARK](https://github.com/initc3/babySNARK) - SNARK教程
- [ZK Shanghai 2023](https://zkshanghai.xyz/) - 一套中文 ZKP 学习课程
- [zkp-co-learn](https://learn.z2o-k7e.world/) - 中文零知识证明系列课程
- [Awesome ZKP](https://awesomezkp.notion.site/) - 一个零知识证明Notion知识库
- [Halo2 Book](https://zcash.github.io/halo2/index.html) - zcash的Halo2教程
- [Halo2 Book(中文)](https://trapdoor-tech.github.io/halo2-book-chinese/index.html) - zcash的Halo2教程
- [ZKVM book](https://hackmd.io/@liangcc/zkvmbook/https%3A%2F%2Fhackmd.io%2FHfCsKWfWRT-B_k5j3LjIVw) - ZKVM 知识介绍

### 🔧开源工具
- [circom](https://github.com/iden3/circom) - zkSnark 电路编译器
- [zcash/halo2](https://github.com/zcash/halo2) - Halo2零知识证明系统
- [libsnark](https://github.com/scipr-lab/libsnark) - C++ library for zkSNARKs
- [libsnark-tutorial](https://github.com/howardwu/libsnark-tutorial) - zkSNARK 教程和开发环境
- [plonkathon](https://github.com/0xPARC/plonkathon) - 教育版本的python plonk实现
- [zkrepl](https://zkrepl.dev/) - 在线网页版电路IDE
- [ZK-Garage/plonk](https://github.com/ZK-Garage/plonk) - 一个使用arkworks作为后端的纯Rust PLONK实现
- [privacy-scaling-explorations/zkevm-circuits](https://github.com/privacy-scaling-explorations/zkevm-circuits) - zkevm 电路实现
- [zkemail/zk-email-verify](https://github.com/zkemail/zk-email-verify) - 验证具有与电子邮件域相同的信任假设的电子邮件
- [zkp-application/circom-rsa-verify](https://github.com/zkp-application/circom-rsa-verify) - Zero Knowledge Proof for RSA

### 🔥相关项目
- [zkMove Project](https://www.zkmove.net/) - A zero-knowledge proof friendly Move language runtime environment.
- [DelphinusLab/zkWasm](https://github.com/DelphinusLab/zkWasm) - zkWasm
- [Scroll](https://scroll.io/) - The native zkEVM
- [Aztec](https://aztec.network/) - The programmable privacy layer for web3
- [Zecrey Protocol](https://www.zecrey.com/) - zkRollup based Layer 2 protocol featuring privacy and scalability.
- [zkSync](https://zksync.io/) - zkRollup
- [StarkNet](https://www.starknet.io/en) - zkRollup
- [zkemail/halo2-zk-email](https://github.com/zkemail/halo2-zk-email) - Email verification circuit in halo2
- [mina](https://github.com/MinaProtocol/mina) - Mina is a cryptocurrency protocol with a constant size blockchain, improving scaling while maintaining decentralization and security.
- [zcash](https://github.com/zcash/zcash) - Anonymous coin
- [risc0](https://github.com/risc0/risc0) - RISC Zero is a zero-knowledge verifiable general computing platform based on zk-STARKs and the RISC-V microarchitecture.


### 📜文章博客
- [零知识证明学习资源汇总](https://secbit.io/blog/2019/11/07/zkp-learning-resources/)
- [L2汇总的汇总](https://h0m83hhc6r.feishu.cn/docs/doccnp6vxEcdn6CYT9725nEldfb#)
- [关于零知识应用安全性的几点思考](https://mirror.xyz/bubb1es.eth/V9pqaI7l5U08yq-kRhL6kYcrpCALMYuxJQ3TP-Pa0iA)
- [零知识证明 - 从理论到实践（视频）](https://mp.weixin.qq.com/s/XWKiakLxpvJUm5WURT7tQw)
- [深入理解zk-STARK证明系统](https://trapdoor-tech.github.io/zkstark-book/)
- [0xScope Labs 首期Tech Studio，讲述zk的过去和未来](https://mirror.xyz/0xB134928B00c6c76b939D8715a6dc1e1dAe5B5b6e/D2_U2JQTZy10dSke1u5SjoIEXOVOy-uRkZ80NSsQlb8)
- [zkMesh: April 2022 recap](https://zkmesh.substack.com/p/zkmesh-april-2022-recap?s=r)
- [Why and How zk-SNARK Works 1: Introduction & the Medium of a Proof-Maksym](https://medium.com/@imolfar/why-and-how-zk-snark-works-1-introduction-the-medium-of-a-proof-d946e931160)
- [The ultimate guide to L2s on Ethereum](https://dcbuilder.mirror.xyz/QX_ELJBQBm1Iq45ktPsz8pWLZN1C52DmEtH09boZuo0)
- [An Incomplete Guide to Rollups-vitalik](https://vitalik.ca/general/2021/01/05/rollup.html)
- [Hardware Acceleration for Zero Knowledge Proofs-Paradigm](https://www.paradigm.xyz/2022/04/zk-hardware)
- [Decentralized Speed: Advances in Zero Knowledge Proofs-a16z](https://a16z.com/2022/04/15/zero-knowledge-proofs-hardware-decentralization-innovation/)
- [Incomplete Guide to ZK: Why ZK Matters？-fundamental labs](https://mirror.xyz/fundamentalabs.eth/24i98adRylhjdcqV1TnsT8ZbkIXCulCrDTIrsrziQmY)
- [ZERO-KNOWLEDGE ROLLUPS-ethereum.org](https://ethereum.org/en/developers/docs/scaling/zk-rollups/)
- [PLONK by Hand (Part 1: Setup)](https://research.metastate.dev/plonk-by-hand-part-1/)
- [Quadratic Arithmetic Programs: from Zero to Hero - Vitalik Buterin](https://medium.com/@VitalikButerin/quadratic-arithmetic-programs-from-zero-to-hero-f6d558cea649)
- [Exploring Elliptic Curve Pairings - Vitalik Buterin](https://medium.com/@VitalikButerin/exploring-elliptic-curve-pairings-c73c1864e627)
- [Zk-SNARKs: Under the Hood - Vitalik Buterin](https://medium.com/@VitalikButerin/zk-snarks-under-the-hood-b33151a013f6)
- [Understanding PLONK - Vitalik Buterin](https://vitalik.ca/general/2019/09/22/plonk.html)
- [ZkVM: fast, private, flexible blockchain contracts](https://github.com/stellar/slingshot/blob/main/zkvm/docs/zkvm-design.md)
- [How to build modern SNARKs systems](https://joseandro.github.io/posts/snarks_constructions/)

## 📚区块链书籍
### Bitcoin
- [Mastering Bitcoin 2nd Edition - Programming the Open Blockchain](https://github.com/bitcoinbook/bitcoinbook)
- [Mastering the Lightning Network (LN)](https://github.com/lnbook/lnbook)
- [Grokking Bitcoin](https://github.com/kallerosenbaum/grokkingbitcoin)
- [Programming Bitcoin](https://github.com/jimmysong/programmingbitcoin)
- [Bitcoin development philosophy](https://bitcoindevphilosophy.com/)
- [Onboarding to Bitcoin Core](https://github.com/chaincodelabs/onboarding-to-bitcoin-core)

### Ethereum
- [Understanding Ethereum: Go-Ethereum Code Analysis](https://github.com/ABCDELabs/Understanding-Ethereum-Go-version)
