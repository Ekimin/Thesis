# 摘要

>This paper examines information leakage in distributed ledgers. We show how the lack of time priority in the period between the publication of a transaction and its validation by miners or designated participants can expose a transaction’s “footprint” to the market, resulting in potential front-running and manipulation.

这篇文章研究了分布式账本技术中的信息泄露问题。我们演示了在交易的公布到比特币矿机或者特定参与者证实交易有效这段时间中，缺乏时序是怎样揭示出交易走向市场的“脚印”，从而导致潜在的非法预先交易和操作。

>We propose a cryptology-based approach for solving information leakage problems in distributed ledgers that relies on using a “hash” (or mathematical identifier) to secure time-priority followed by a second communication revealing more features of the underlying market transaction. Solving the information leakage problem greatly expands the potential applications of private distributed ledger technology.

为了解决分布式账本技术中信息泄露问题，我们提出了一个基于密码学的方法。该方法通过“哈希”（或者其他数学标识符）和紧随其后的可以显示更多潜在市场交易信息的二次通讯信息来确保交易时序。解决信息泄露问题可以增加个人分布式账本技术的潜在应用。

# Introduction

Advocates of the blockchain, the distributed ledger technology that underlies Bitcoin,see an almost limitless future for the innovation. Apart from its role in cryptocurrencies,distributed ledger technologies are being developed to handle stock trades, clear and settle leveraged loans, handle catastrophe reinsurance, keep track of land titles and transactions,track the ownership of intellectual properties, facilitate peer-to-peer marketplaces – the list goes on and on. Much of the appeal of the blockchain lies in its use of a decentralizeddistributed ledger technology in which an immutable single record emerges of the varioustransactions encased in the blocks. The ability to trade assets in such a setting, along with theemergence of new “smart contracts” that can automatically trigger additional steps such asrecording ownership changes or authorizing payments, can have, in the words of the Bank ofEngland, “far-reaching implications for the financial industry”.

用于比特币中的分布式账本技术——区块链技术的先驱者，见证了它在技术革命中的广泛应用前景。除了在加密货币中的应用，分布式账本技术还广泛应用于股票交易， 解决杠杆贷款问题，处理巨灾再保险，跟踪解决土地所有权相关事务，知识产权的所有权鉴定，促进P2P市场发展等等。
