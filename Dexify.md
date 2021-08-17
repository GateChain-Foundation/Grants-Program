**1.1** **Project process** (you need to fill in the following information):

**1.1.1** **Basic information**  
 	Project Name format: Dexify.md  
 	Team name(s): Luke Trotman, Stefan Batalka, Hafeez Sanusi  
	Payment Method: Crypto (GateChain Coin)
	Payment Address: 0x187d75cd00A52B843fEb9CBcF0EdC3619B9cD
	
**1.2** **Project Overview**  

**1.2.1** **Project Introduction**
Dexify is a platform provider supporting cross-chain social trading in a transparent and decentralised manner. It enables individuals and organisations to manage and invest in digital assets based on audited on-chain digital asset management strategies. A smart-contract rules-based protocol enables de-centralised investors to safely allocate their capital to traders based on a provable, verified track-record. The Dexify platforms automated smart mirror contracts (”Dexfunds”) allow investors to seamlessly mirror trades executed by the original Dexfund while leveraging the security of the blockchain to protect against fraud. The Dexify routing layer provides Dexfunds with optimal trade execution and frictionless transactions across multiple blockchains. Utilizing the combined assets across all Dexfunds enables Dexify to minimize the transaction-fees paid by individual investors and provides access to tools normally only available to large volume traders.

The digital asset ecosystem has seen a dramatic rise over the last few years with decentralised financial applications (”defi”) set to capture a significant share of the traditional financial sector. This new asset class is currently largely dominated by retail investors facing a significant challenge in navigating a rapidly changing space with tens of thousands of different projects and associated tokens. The technologically complex and innovative nature of digital assets makes it difficult for the average investor to conduct rigorous fundamental analysis and manage this new asset class effectively. Grandiose claims and complete scams have already cost investors billions of dollars and growing.

These market dynamics have spawned a host of ”crypto influencers” enthusiastically encouraging followers to buy into their ideas in order to generate unparalleled returns. The lack of a common standard and framework for tracking and evaluating these claims has resulted in defi investors being inundated with information that is practically impossible to parse. The Dexify platform aims to provide individual investors with an easy to use interface to evaluate the track-records of traders and portfolio managers as well as deploying capital to their strategies.

**1.3** **Project details**  
Dexfunds:
Dexfunds are smart-contracts that enable Dexify users to automatically follow the actions of the Dexfund creator. Anyone is free to create a Dexfund and specify the modules associated with it. Any investor can join the Dexfund and mirror the original execution and performance. Management and performance fees are calculated automatically and distributed according to the agreed terms once an investor leaves, the Dexfund closes, or a set period is reached.

Security: 
The ability of a Dexfund creator to dictate the execution of trades on behalf of separate parties presents a number of potential security risks. For example, the Dexfund manager could create their own token and list it on one of the decentralised exchanges, after which they could initiate a purchase on behalf of their Dexfund, essentially buying the token from themeselves as well as for anyone mirroring the trade. We have taken a number of steps to mitigate these security risks, and will conduct extensive audits of all deployed code. One such step is to offer separate modules on top of the base Dexfund contract. These modules can be configured in order to offer varying levels of security, permissions and fees.

Modules:
The purpose of the Dexify smart-contract modules is to enable Dexfund creators to have as much freedom as possible in specifying the particular permissions and parameters pertaining to their Dexfund, while also offering transparency to investors as to the level of risk they are being exposed to by mirroring traders. Below are some example modules.

Exchange modules:
Selection of supported exchanges for the Dexfund to execute trades on. Price feeds from these exchanges are automatically included in order to calculate performance, net asset values, various portfolio metrics and fees.

Tokens:
List of tokens that the Dexfund is allowed to trade. Limiting the selection of tokens that could potentially be purchased to more liquid, and well known projects prevents many attacks such as the dummy token creation.

Blockchains:
Specify supported chains that the Dexfund is able to trade across using our cross-chain bridges. Gatechain can be easily intergrated to support all projects launching on the blockchain. 

Allocation limits:
Limiting the maximum possible allocation to a single token or blockchain. This not only limits the risk of a significant part of the total portfolio being lost on a minor speculative blockchain, but also limits the potential for order book manipulation on behalf of the Dexfund manager.

Management participation:
Specifications for the required share of the total net asset value that must be owned by the Dexfund creator at any given time. May be a minimum, target or maximum requirement. Value are monitored by the Dexify router and balanced automatically.

Fee modules:
Dexfund managers can select from a range of different fee calculations, such as a set periodic fee, management fees as a percentage of gross asset value under management, performance fees as a percentage of profits generated, or a combination of these.

Module alterations:
Alteration of a Dexfunds active modules can be done in set intervals given adequate notice. Investors that do not approve of the change of Dexfund modules by
Dexify Whitepaper, p. 2 the time changes are set to deploy will be automatically divested from the fund by the execution router.

Notes on modularity:
The separation of the base Dexfund contract and the additional permission modules allows us to easily iterate on the system, adding new modules or editing existing ones as market conditions and consumer demands change. Publishing the Dexfund contract interface parameters encourages anyone to create and submit proposals for additional modules according to their needs. Dexify is a free and open platform enabling traders and their strategies to be paired with investors capital. The dynamics of this transparent free market incentivises traders to construct Dexfunds with a set of modules that provide the optimal trade-off between permissions and risk in a way that is clear to investors, while still enabling the Dexfunds to generate competitive returns.

Execution router:
The Dexify execution router (”router”) is the key layer separating individual investors and Dexfund managers. It serves the dual purpose of providing additional security against market manipulation, as well as enabling efficient order execution and portfolio management. An aggregate liquidity pool and common execution layer enables individual investors to benefit from the scale of the platform, receiving the best available execution and access to cutting edge defi tools.
      
Price feeds and transaction security:
Dexify maintains price feeds from decentralised exchanges across multiple blockchains as well as to their centralised counterparts. These price-feeds are provided to individual Dexfunds according to the permission modules selected. The router leverages our proprietary path-finding algorithm to determine the best possible execution for each order. Routing through the aggregate liquidity pool is is prioritised in order to minimize execution fees and slippage.

Addition and redemption:
The router enables Dexfunds to continuously onboard new investors or redeem existing allocations without requiring set lock-up periods. The router handles the addition of any supported token, or set of tokens by determining the optimal path across avaialable exchanges resulting in a matching allocation distribution to the Dexfund being mirrored. For a given Dexfund: as well as leading transaction obfuscation frameworks such as flash bots as well as any other providers that may emerge in the future, in order to ensure that our trades are executed at the best possible price.

Bridges:
Dexify bridges provide an interface for Dexify traders and router to transfer digital assets across multiple chains. A single bridge consists of two vaults in the form of contracts that freeze assets until they can be redeemed. When a cross-chain transaction is initiated, the original token amount is locked up in the original chains vault and a corresponding amount is released on the target chain. The tokens on the original chain can then be redeemed at any time by repaying the owed tokens on the target chain. These vaults on either end extend the permission modules in the base Dexfund-contract in order to allow for temporary transfers cross-chain. A similar process is executed upon redemption, with the notable difference of distributing fees to the Dexfund manager according to the pre-defined fee modules. The router, in conjunction with the Dexfund contract, keeps track of the entry prices and trade history while participating in the fund and converts all remaining holdings back to the desired token, with fees deducted.

On-chain execution tools:
Recent months have seen an emergence of a multitude of tools used to analyse transactions that are broadcast to blockchains. Due to the distributed, public nature of the technology, malicious actors are able to analyse transactions as they are being broadcast and interfere in a manner that allows them to manipulate prices. Naturally this is at the expense of the originator of the transaction. This manipulation may even extend as far as to the miners themselves re-organising blocks in order to manipulate the prices received upon execution. Solutions to circumvent this manipulation are at the cutting edge of blockchain development and may be too complex for individual traders to implement, however by providing a common execution layer via our router, Dexify is able to socialise the cost of these implementations and share the benefits between all investors. Dexify will work directly with miners,

Fees and insurance pool:
A percentage fee corresponding to the relative counter-party risk posed by the secondary chain is set aside in an insurance pool. Should the secondary chain protocol be compromised somehow, the insurance pool will cover investors losses to the extent of the liquidity available at the time. The ethereum mainnet is considered to be the chain against which all other chains are being bridged for the purpose of this insurance pool.

Portfolio re-balancing:
Portfolio re-balancing is the act of realigning assets in a portfolio back to their target allocations. This can be a target percentage weighting of each asset as a part of a whole portfolio of assets. During re-balancing assets are traded such that the value held in each asset shifts toward the target allocation. This process is executed by the router at pre-determined intervals.

Passive vs active management:
Dexfund creators can create both actively and passively managed Dexfunds, where ”actively” refers to the manual trading of a set of assets while ”passive” sets specifies target allocations to a set of assets as a percentage of the net asset value. Dexfunds can be either wholly or partially actively or passively managed. Managers can chose when, or how frequently to rebalance their portfolio. The complexity of portfolio management and re-balancing is abstracted away and executed by the router in the most efficient manner, the only thing managers have to do is specify the target percentages and re-balancing periods.

Permitted periods:
During the initial stages of platform growth, the portfolio re-balancing periods will be limited to predefined intervals of 1/2/3/4/12 and 24 hours. This is in order to maximise the utilization of the aggregate liquidity pool and ensure best execution on behalf of investors. Dexfund managers can manually request to rebalance the portfolio at any given time, in which case this will be executed at the next possible interval.

Dexify indexes:
The Dexify platform can support a broad range of strategies trading not just across multiple assets but also across multiple chains. As such these Dexfunds provide significant diversification potential across decentralised assets. Taking this further, Dexify will provide custom indexes allocating to subsets of existing Dexfunds based on various metrics such as crossfund correlation, volatility, counter-party risk and security metrics. This allocation will be made on behalf on the index fund in the same manner that an individual would mirror a given Dexfund, with the index effectively acting as an intermediary layer.

**1.3.1** **Technology Stack Used**  

Technology 1: PHP

Technology 2: Solidity

 **1.4** **Team**  
 
 **1.4.1** **Team Profile:**  
 ceo/Founder - Luke Trotman: A second time founder, he formerly founded a 7 figure social media marketing business whilst at one of the UK's best universities studying banking, finance and management. He has a cross-platform social following of over 3 million people and has amassed over 500 million views and impressions since he started 2 years ago. He is an avid crypto investor and his aim is to make Defi a safer and more guided place for investors in the space. We want to be able to allow anyone in the world with a digital wallet to have access to the best asset management on the planet. 
 
cto - Stefan Batalka: Has been into computers for as long as he can remember. He has several years of experience with solidity and bitcoin core. He has managed 7&8 figure portfolios for some very large hedge fuinds in london. Former profesional poker player. Founded a crypto-advisory company in 2018 (Ranvier AI) Coded many trading bots using AI/ML, and hundreds of iterations of strategies. Worked on implementations for permissionless decentralised sports betting. Coded algortihms for cancer prevention. 

Co-founder - Hafeez Sanusi: A deep understanding of DeFi and the crypto space, Hafeez is an expert within the data analytics field. He is one of englands leading consultants in the data anyltics field and has deep expertise within Tableau, Alteryx, and Python. This allows us to execute the dexify vision to the highest quality.
 
**1.4.2** **Information of Project Leader:**  
Name:  Luke Trotman
Mailbox: Luke@dexify.io  

**1.5**   **Legal structure:**  
Legal Representative: Tom Grant
Registered Address:  Suite 1, Warrant House, Altrincham, Cheshire, WA14 4PZ

**1.6** **Team Code Warehouse**  
Source Code Repository:  www.dexify.io

**1.7**  
	Project Direction: Currently developing our MVP  
	Iteration Cycle: Implementation - UI/UX front end all designed (Please see our website www.dexify.io), backend being developed.   
	Iteration Content: Full back-end development 
	Cost: $90,000-$150,000
