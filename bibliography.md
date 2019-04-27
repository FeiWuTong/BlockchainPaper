# 整理

-------------------------------------

## 格式

-------------------------------------

> 作者 / 题目 / 来源 (会议、期刊、网页) / 年份 / 摘要

-------------------------------------

## 检索方式

-------------------------------------

> ### 关键字

>> blockchain, smart contract, distributed consensus, decentralizing, Bitcoin, Ethereum, cryptocurrency

> ### 引用

> ### Website

>> https://www.jianshu.com/p/aec8faa50bd1

>> http://blockchain.whu.edu.cn/blockchainpapers/

>> https://github.com/decrypto-org/blockchain-papers

> ### Forum

>> https://ethresear.ch/

> ### Blog

> ### Github

-------------------------------------

## 会议收录

-------------------------------------

* IEEE International Conference on Blockchain and Cryptocurrency (ICBC)
* USENIX Symposium on Networked Systems Design and Implementation (NSDI)
* Symposium on Operating Systems Principles (SOSP)
* Crypto
* Eurocrypt
* Asiacrypt
* Financial Cryptography and Data Security (FC)
* IEEE Symposium on Security and Privacy (S&P)
* Computer and Communications Security (CCS)
* Security Usenix Security Symposium (USENIX)
* Network and Distributed System Security (NDSS)
* The International Conference on Dependable Systems and Networks (DSN)
* International Conference on Smart Blockchain (SmartBlock)
* International Conference on Blockchain Technology and Applications (ICBTA)
* IEEE International Conference on Blockchain and Cryptocurrency (ICBC)
* IEEE International Workshop on Blockchain, Smart Contracts, and Digital Society (IWBS)
* Symposium on Blockchain Technology and Application (SBTA)
* International Workshop on Blockchain and Data Management (BlockDM)
* International Conference on Blockchain Technology (ICBCT)
* International Conference on Blockchain (ICBC)
* IEEE International Conference on Blockchain

-------------------------------------

# 高引

-------------------------------------
此部分无关时间和会议，是区块链方面的奠基作，其高引用量说明了其影响的深远，许多后续工作都是基于此而开展或改进的。


> 区块链

>> Satoshi Nakamoto, Bitcoin: A Peer-to-Peer Electronic Cash System, https://bitcoin.org/bitcoin.pdf, 2008, 首次提出去中心化的数字货币点对点交易系统（即比特币），区块链的雏形设计与基本原理。

>> Ittay Eyal, Adem Efe Gencer et al, Bitcoin-NG: A Scalable Blockchain Protocol, Proceedings of the 13th USENIX Symposium on Networked Systems Design and Implementation, 2016, 相较于bitcoin提升了数个数量级的tps，提出关键块和微块的概念，且是部分后续研究的比较对象及理论基础。

> 共识机制

>> Miguel Castro and Barbara Liskov, Practical Byzantine Fault Tolerance, Proceedings of the Third Symposium on Operating Systems Design and Implementation, 1999, 实用拜占庭容错算法，相比于BFT能更高效解决拜占庭错误，原用于分布式系统与网络中，后在区块链的委员会投票共识机制方面应用广泛，是很多相关共识机制与区块链的基础（著名的小于1/3作恶节点）。

>> Yossi Gilad, Rotem Hemo, Silvio Micali et al, Algorand: Scaling Byzantine Agreements for Cryptocurrencies, SOSP'17, 2017, 提出新的拜占庭协议，通过委员会（共识组）的轮换机制以及用户权重进行VRFs随机抽签来保证BFT的安全性与活性，并提升了区块链的吞吐量、降低交易延迟、消除分叉。

-------------------------------------

# 区块链

-------------------------------------

> 2019

>> Stefanos Leonardos et al, Weighted Voting on the Blockchain: Improving Consensus in Proof of Stake Protocols, IEEE International Conference on Blockchain and Cryptocurrency, 2019, 提出使用与用户行为相关的用户属性作为权重，在PoS协议中进行权重投票，并采用权重计票方式来保证协议的安全性和稳定性。

>> Jiaping Wang, Hao Wang, Monoxide: Scale out Blockchains with Asynchronous Consensus Zones, Proceedings of the 16th USENIX Symposium on Networked Systems Design and Implementation, 2019, 提出异步共识空间的概念，将区块链系统进行交易和状态的部分分片，分片后保证交易的最终原子性（即前后一致性），并提出连弩挖矿保证分片后系统的安全性不变，在保证安全性的前提下大幅提升区块链的TPS（取决于并行的异步空间数量），可以提升至上万TPS，并大幅降低节点的存储开销。

>> Eduardo Castell´o Ferrer, The Blockchain: A New Framework for Robotic Swarm Systems, Proceedings of the Future Technologies Conference, 2019, 将区块链与机器人集群系统结合在一起，使其更加灵活与安全，并解决了在机器人集群研究领域的四个亟待解决的问题。

>> Vitalik Buterin et al, Incentives in Ethereum’s Hybrid Casper Protocol, IEEE International Conference on Blockchain and Cryptocurrency, 2019, 文章对Hybrid Casper FFG协议概括总结，该协议为覆盖以太坊PoW区块链的一种PoS Checkpoint协议，其激励机制保证了区块链的活性并提供了高于标准PoW协议的安全性。另外通过在区块链上部署该协议的智能合约，作者还分析了其存在的一些问题和潜在的缺陷。

> 2018

>> Jiangshan Yu, David Kozhaya et al, RepuCoin: Your Reputation is Your Power, ResearchGate, 2018, 提出PoR声望证明的概念，将用户的声望与其挖矿能力相结合以抵御51%攻击，并结合Bitcoin-NG与Byzcoin微块关键块的概念大幅提升区块链系统的TPS。

>> Hirotsugu Seike, Takeo Hamada et al, Blockchain-Based Ubiquitous Code Ownership Management System without Hierarchical Structure, IEEE, 2018, 将泛在码（泛在ID）的管理系统与区块链结合在一起，而非DNS的层次结构型，从而减少分配与处理过程中的负担并提升效率。

>> Don Tapscott, Blockchain Revolution: The Internet of Value, Blockchain Revolution, 2018, 介绍区块链，并说明了区块链目前的发展潜力与主要安全问题、相关解决方案，和在实际中的潜在影响（即应用）。

>> Kokoris-Kogias, Eleftherios et al, OmniLedger: A Secure, Scale-Out, Decentralized Ledger via Sharding, IEEE Symposium on Security and Privacy, 2018, 通过对区块链进行安全、合理的随机分片来扩展区块链，并且在保持交易的原子性下正确并行地处理交易，其指出了Elastico的几个未解决的问题并在其基础上进行改进，克服其问题。

>> Mahdi Zamani et al, RapidChain: Scaling Blockchain via Full Sharding, CCS'18, 2018, 指出现有的基于分片的区块链仍需要高额的通信代价，无法充分发挥分片的优势，其提出的RapidChain则在对区块链进行完全分片的情况下，保证拜占庭容错的占比为1/3，在保障安全的条件下进一步提高区块链的吞吐量。

>> Dejan Vujičić et al, Blockchain Technology, Bitcoin, and Ethereum: A Brief Overview, 17th International Symposium INFOTEH-JAHORINA, 2018, 对区块链技术、比特币、以太坊等作了一个简明扼要的介绍。

>> Rafael Pass and Elaine Shi, Thunderella: Blockchains with Optimistic Instant Confirmation, Proceedings of Eurocrypt, 2018, 提出算法Thunderella使状态机可以实现快速且异步地处理共识，并在异常时能同步回滚。其与同步协议的稳定性一致但具有更快的响应，能瞬间确认交易。前提是不出现拜占庭错误（即大部分节点是诚实的）。

>> Christian Badertscher et al, But Why Does it Work? A Rational Protocol Design Treatment of Bitcoin, Proceedings of Eurocrypt, 2018, 作者通过部署RPD（Rational Protocol Design）框架来分析比特币并证明了其分析的合理性，除了将RPD机器扩展至了加密货币领域外，还解释了为什么大部分节点（算力）是诚实的这一难证问题。

>> Bernardo David et al, Ouroboros Praos: An adaptively-secure, semi-synchronous proof-of-stake blockchain, Proceedings of Eurocrypt, 2018, 提出了一个新的PoS协议——Ouroboros Praos，该协议是首个提供了针对在半同步状态下“完全自适应腐蚀”的安全保障的算法，其中包括新形式的安全数字签名以及一种新的可验证随机函数。

>> Joel Alwen et al, Sustained Space Complexity, Proceedings of Eurocrypt, 2018, 文章引入了持续内存机制，即内存困难型函数（MHF），使评估成本受内存成本控制，在专业硬件设备（如FPGAs、ASICs）上运行的成本与一般机器上的成本相当，可应用于区块链上避免垄断和中心化。

>> Bram Cohen and Krzysztof Pietrzak, Simple Proofs of Sequential Work, Proceedings of Eurocrypt, 2018, 文章提出了一种更简单且更有效率的连续工作证明，用空间证明取代PoW来保证加密货币（区块链）的安全，且其空间复杂度最低可降至log(N)级别。

>> Ben Fisch et al, Scaling Proof-of-Replication for Filecoin Mining, https://web.stanford.edu/~bfisch/porep_short.pdf, 2018, 解释了PoR的细节原理以及各类相关技术、算法与协议，并提出可扩展至大文件的块链连续编码算法对PoR进行扩展。

>> Yonatan Sompolinsky and Aviv Zohar, PHANTOM, GHOSTDAG: Two Scalable BlockDAG protocols, https://eprint.iacr.org/2018/104.pdf, 2018, 文章提出了基于PoW的共识协议Phantom，其可以将中本聪型区块链转化为DAG型区块，在保证安全的情况下适应区块链的高吞吐量、达到扩展区块链的效果。其通过一种贪心算法来分辨区块的有效性，进而保证DAG区块顺序的稳定，诚实节点最终能达成一致共识。

> 2017

>> Marco Iansiti and Karim R. Lakhani, The Truth About Blockchain, Harvard Business Review, 2017, 对区块链的发展进行正反两面的分析，说明其虽具备极大的发展潜力与市场，但仍需要很长的时间去适应、发展并成熟化。

>> Marc Pilkington, Blockchain technology: principles and applications, Research handbook on digital transformations, 2017, 对区块链技术的主要原理进行阐述并举例一些重要的、前沿的区块链的应用。

> 2016

>> Jesse Yli-Huumo et al, Where Is Current Research on Blockchain Technology?—A Systematic Review, PLOS ONE, 2016, 对截止至2016年部分关于区块链的研究作了系统性地分析，包括研究的主题、挑战和未来的方向。

>> Michael Crosby, Nachiappan et al, BlockChain Technology: Beyond Bitcoin, Applied Innovation Review, 2016, 解释了区块链技术并说明其在经济/非经济领域的热门应用，并展望了区块链方面的挑战及商业机会。

>> Asaph Azaria et al, MedRec: Using Blockchain for Medical Data Access and Permission Management, 2nd International Conference on Open and Big Data, 2016, 将区块链应用于医学数据的管理（即电子病历）。

>> Konstantinos Christidis et al, Blockchains and Smart Contracts for the Internet of Things, IEEE, 2016, 提出将区块链与物联网结合在一起，并指出其优势与潜力，以及一些潜在的问题。

>> Loi Luu et al, A Secure Sharding Protocol For Open Blockchains, CCS'16, 2016, 项目名为Elastico，最早提出在存在拜占庭错误的情况下将区块链安全地进行分片的论文，通过分片的方式提高区块链的tps。

>> Joseph Poon and Thaddeus Dryja, The Bitcoin Lightning Network: Scalable Off-Chain Instant Payments, https://lightning.network/lightning-network-paper.pdf, 2016, 闪电网络的白皮书，通过开启微支付通道，在不影响去中心化的特性下，实现在链下的转账与跨链交易，从而在一定程度上解决Bitcoin的扩展性问题，大幅提升tps。

>> Yonatan Sompolinsky et al, Spectre: Serialization of proof-of-work events: Confirming transactions via recursive elections, https://eprint.iacr.org/2016/1159.pdf, 2016, 提出序列化PoW事件并通过递归选举确认交易，是对区块链的一种扩展方案，其可在任意出块速率下正常运作，即可大幅提高tps。其解决分叉的方案是在DAG结构中采用对拥有最多子区块的区块进行不同分支的归并，成为有效的主区块加入账本。

> 2015

>> Guy Zyskind et al, Decentralizing Privacy: Using Blockchain to Protect Personal Data, IEEE CS Security and Privacy Workshops, 2015, 提出通过区块链来保护与管理用户的个人数据，交易用来携带查询、存储或分享数据的指令。

>> Yonatan Sompolinsky and Aviv Zohar, Secure High-Rate Transaction Processing in Bitcoin, International Financial Cryptography Association, 2015, 指出比特币（区块链）在高吞吐量（tps）下分叉双花的安全问题，并提出GHOST协议，通过选择最重分支为主链来降低区块链分叉带来的风险，提升安全性，已经应用于以太坊。

> 2014

>> Andrew Poelstra, Distributed Consensus from Proof of Stake is Impossible, https://download.wpsoftware.net/bitcoin/alts.pdf, 2014, 解释PoS的原理及应用方式，并指出其机制存在的问题和作为分布式协议的不合理性。

>> Shawn Wilkinson and Jim Lowry, Metadisk: Blockchain-Based Decentralized File Storage Application, https://storj.io/metadisk.pdf, 2014, storj的前身，早期提出并证明云存储和区块链可结合在一起的白皮书，并提供平台的原型以及应用与扩展所需的底层API。

-------------------------------------

# 合约

-------------------------------------

> 2019

>> Martin Westerkamp, Verifiable Smart Contract Portability, IEEE International Conference on Blockchain and Cryptocurrency, 2019, 提出并实现了无需信任机构执行移植过程即可移植不同区块链上智能合约的状态与功能，前提是合约的运作都是EVM，且第三方库的引用需要维护额外一张映射表。

>> Krishnendu Chatterjee et al, Probabilistic Smart Contracts: Secure Randomness on the Blockchain, IEEE International Conference on Blockchain and Cryptocurrency, 2019, 对于受限于非概率性的智能合约，文章提出了一种新的博弈论方法用于在区块链中产生可证明的、不可操纵的伪随机数，其可使智能合约获取该可信的随机性，以适应需要完全依赖随机性的应用与合约。

> 2018

>> 

> 2017

>> 

> 2016

>> Ahmed Kosba, Andrew Miller et al, Hawk: The Blockchain Model of Cryptography and Privacy-Preserving Smart Contracts, IEEE Symposium on Security and Privacy, 2016, 指出现有的区块链系统缺乏交易隐私，并提出用隐私保护智能合约来使区块链上的交易隐私信息隐藏起来，其中的加密基础为零知识证明。

> 2014

>> David Vorick, Luke Champine, Sia: Simple Decentralized Storage, Sia White Paper, 2014, 去中心化的区块链分布式存储，通过对等节点之间的存储合约来决定存储的数据与对应的价格。
