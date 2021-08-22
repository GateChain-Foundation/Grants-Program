**1.1** **Project process** (you need to fill in the following information):  

**1.1.1** **Basic information**  
 	Project Name format: DEXPro.md  
 	Team name(s): Defilabs  
	Payment Method:  GT (ERC20) / ETH / USDT (ERC20)  
	Payment Address: 0xcbBdcCf29C287D0Fa2b29820c704ffae6D377Ad4  
	
**1.2** **Project Overview**  
DexPro intends to establish a more professional decentralized trading platform, the existing mainstream AMM DEX such as uniswap, pancakeswap, user experience has a worse using-experience than CEX, we focus on the development of better trading supporting experience such as providing rich K line, capital analysis, optional trading, limited price trading, etc., further develop innovation Defi function such as support LP, NFT staking lending, etc.  
In addition, when we provide development support for other blockchain projects, we found that many enterprises, project parties themselves do not have blockchain technical team, but have a very strong demand for blockchain Defi function and high pay intention, so we also plan to turn blockchain Defi function gradually into a SaaS service, such as we will start from allowing users to build all kinds of farms and pools staking pool, etc.  
We will support as many more mainstream blockchain as Ethereum, BSC, HECO, gatechain, etc.

Project Phase:  
● has been completed:  
Technical accumulation and market research of the project are completed  
Some functional demo development was completed  
Accumulated intention customers and community  

● is in progress:  
Seeking seed round financing  
Improve the project design  
Improve the project prototype and UI design  
Design the project Token model  
Improve the development architecture design  


**1.2.1** **Project Introduction**  
Since the emergence of uniswap in 2018, it has greatly changed the Defi industry. Based on AMM trading mechanism and innovative LP mining and single-currency staking mining, and with the development of various blockchain lending applications to further have expanded the application surface of Defi. 

**The Vision**  

This project is based on the existing mainstream AMM DEX tech to build a more professional and powerful exchange, and develop innovative Defi functions and SaaS Defi capabilities.  

**The Mission**  

Further lowering the threshold of Defi use, making it easier for more common people to use Defi, and allow more companies and groups to participate in the promotion of Defi and cryptocurrency, making cryptocurrency and blockchain technology more popular.  

The project features are described as follows:  

DEX:  

1, displays transaction K line, transaction volume, transaction records and other information  

2, supports self-selected currency, the introduction of transaction currency data display area, etc  

3, supports exchange rate conversion,sort by price, etc  

4, allows users to make limited price orders  

5, supports using the platform token to pay the deduction fees  


Defi:  

1, supports LP pledge lending  

2, NFT pledge mining and lending (quotation model)  

3, adds a reward algorithm based on the change in the staking time  

4, Defi features SaaS development, allowing users to create a LP staking reward pool and a single currency staking reward pool by themself  

**1.3** **Project details**  

**1.3.1** **Technology Stack Used**  

Technology 1:   Solidity/Go

Technology 2:   JS/TS

Framework:  React/Gin/Truffle

**1.3.2** **Project Design Introduction**   
The project is based on the existing AMM mechanism to create a lower use threshold, easier to use, more powerful DEX and Defi system.  

Here is a prototype conceptual design of its featured features:  

**DEX direction:**  

1、Show users K transaction line, transaction volume, transaction records and other information  

Nowadays, mainstream AMM DEX is relatively simple compared with CEX function. We will provide DEX with various transaction information such as price in Fiat money, transaction K line, transaction volume, amount of the liquidity pool, transaction record, project information.  

![K transaction line Picture](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/K_transaction_line_picture.png)

2、Support the self-currency selection display, the introduction of trading currency data display area, etc  

The general AMM exchange only supports the selection of the transaction currency by searching for names or contracts, and cannot view the currency price easily. We introduce the self-selected transaction pair function to facilitate users to view the real-time pricing of their favorite currency directly in the DEX.

![self-currency selection display](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/self-currency_selection_display.png)
![trading currency data display](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/trading_currency_data_display.png)

3、Support for exchange rate conversion, rise and fall ranking, etc  

Support display Fiat currency pricing, such as USD, CNY pricing  


<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/exchange.png width=333 height=622 />

4、Allow users to make limited price orders  

Ordinary AMM exchanges only support instant transactions, and we introduce the development of automatic limited price orders into DEX to automatically meet eligible transactions.  


<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/limit_price_orders.png width=333 height=622 />

5、supports using the platform token to pay the deduction fees  

![supports using the platform token to pay the deduction fees](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/deduction_fees.png)  

**Defi direction:**  

1、Support for LP pledge lending  

In addition to the general LP staking mining function, DEX Pro will also develop the LP pledge lending function,it support the pledge LP using for borrowing. In addition to supporting the LP pledge of our platform, we also plans to support the LP pledge of other mainstream AMM exchanges, such as uniswap, pancakeswap, etc.  

<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/LP_pledge_lending_1.png width=333 height=622 />
<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/LP_pledge_lending_2.png width=333 height=622 />

2、NFT pledge mining and lending (quotation model)  

Support NFT pledge mining, pledge and lending, pledge and lending will use the quotation mechanism to determine the amount of lending.  

 
<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/NFT_pledge_mining_and_lending_1.png width=333 height=622 />
<img src=https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/NFT_pledge_mining_and_lending_2.png width=333 height=622 />

3、Add the reward algorithm based on the change of the pledge time  

Innovate the pledge reward calculation method, and introduce the influence of time factor, which can set the reward rate to increase the reward rate with the increase of pledge time, this can help stay more user for the project party.  

![Add the reward algorithm based on the change of the pledge time](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/reward.png) 

4、Allow users to create a LP pledge reward pool and a single-currency pledge reward pool by themselves  

This function is inspired by our development and application for other blockchain projects, many enterprises are very interested in blockchain and Defi, eager to integrate blockchain technology into its business, including financing, marketing, fans, feedback, etc., but now Defi functions still need to complex development can be adopted, and we will start from developing a highly available SaaS pledge pool for users, gradually SaaS more Defi functions, to provide more companies without technical team and want to use blockchain technology.  

Users create the LP pledge reward pool and the single-currency pledge reward pool by themselves:  

Self-service upper a pool in the form of voting + auction:  

For example:  

1: Fill in the fixed form, submit project data, pool funds, display information, audit report, etc. (consider preliminary review, screening by contracts or DAO in the later stage)  

2: Project sorting voting, voting using the platform native token voting, charging a small fee for voting  

3: The top 30 voting items will automatically enter the bidding ranking procedure, conduct bidding through the preset bidding address, and the project will pay the DEXPro token for bidding   

4: The top 10 bidding players pass automatically. The project party can set up a pool that support 30d for free, and charge additional fee for the time over 30d  

Submit the Form:  

![Submit the Form](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/form_submit.png) 

Application Home page:

![Application Home page](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/application_home_page.png) 

Bidding page:

![Bidding page](https://raw.githubusercontent.com/Defilaboratory/Grants-Program/main/applications/assets/images/bidding_page.png) 

**1.3.3** **user portrait** 

1, cryptocurrency trader  

2, Defi users  

3, Companies and groups that want to use defi  

**1.3.4** **TOKEN model design**  

The project has not issued tokens in the seed financing stage, and will improve the design of the token mechanism and economic model during the development stage;  

The use of the project platform token is now known as follows:  
1、Give the LP staking rewards  
2、Reward the single currency mine pool  
3、As a handling fee deduction for various platform functions  
4、The fee paid as the application staking pool  
5、Used for pledge lending, casting NFT, etc  

 **1.4** **Team**  
 
 **1.4.1** **Team Profile:**  

 The main members of the project team are me (ZHOU KANG) (Founder of Guangzhou Firefly Network Co., Ltd, started entrepreneurship during university), and one graduate student with a master's degree in computer science from Jinan University, and three engineers currently working in well-known Internet companies.  

I founded a software development company in 2017 to develop digital systems for various companies, government, enterprises, and universities.Our customers included Tencent, China Southern Power Grid, NetEase, etc. Our team started contacting blockchain development in 2018. In 2018, we developed a blockchain wallet, Tokenfactory, a software system for automatically issuing tokens, and developed smart contracts and main chain coins. In 2020, we started to develop Defi applications. In 2021,we developed a number of overseas blockchain projects including AMM DEX, NFT mint/Market, etc., and accumulated a lot of Defi/NFT development experience, as well as potential customers to provide basic support for creating innovative applications. Below are some projects we have developed and stored on the test server. Some of the projects have already been run overseas and have many users and TVL.  

124.70.69.10   
8.134.34.147  
120.79.1.122  

The development of these projects is based on the learing of uniswap, pancakeswap, and bakeryswap, allowing us to accumulate a large amount of DEX and Defi development experience. Now we are also further developing NFT mining and other functions for our overseas projects. We are confident and capable of innovating in the Defi industry.  

**Team members:**

Project Leader & Product Design: ZHOU KANG(Founder of Guangzhou Firefly Network Software Company, started geting in touch with blockchain projects in 2017,graduated from GUANGZHOU University)  

UI:Camille(3 years working experience)  

CTO& Contract Engineer: LI WEI FENG(Master of Computer Department of Jinan University, started to develop blockchain project in 2018)

Front-end developer: 2 members are engineers of Tencent subsidiary (part-time), LI ZHI QIANG (4 years of working experience) (full-time developer in our company)
Back-end developer: 1 engineer working for TOP1 express e-commerce  company(part-time), WU WEI YE (3 years of working experience) (full-time developer in our company)  

Test Engineer: HUANG YONG FENG(Our full-time test Engineer）  


**1.4.2** **Information of Project Leader:**  
Name:  Zhou kang  
Email: Defilabs@126.com    
Telegram:+86 13104936960  

**1.5**   **Legal structure:**  
Legal Representative:Guangzhou Firefly Network Co.,Ltd.  
Registered Address:  Innoangel Space,Guangzhou Higher Education Mega Center, Panyu District, Guangzhou City, Guangdong Province, China  

**1.6** **Team Code Warehouse**  
Source Code Repository:  

https://github.com/Defilaboratory

**1.7**  
	Project Direction:Defi/DEX   
	Iteration Cycle:each month   
	Iteration Content:  

Phase 1: Complete the prototype design of the AMM exchange, with the most basic add liquidity, exchange, staking farms, and staking pools (estimated time spent: 2~3 weeks)  

Phase 2: DEX function optimization, support for display of self-selected currencies, introduction of transaction currency data display area; support for exchange rate conversion, ups and downs sorting; support for displaying currency pricing for legal currencies, such as USD, CNY pricing, etc.; add innovative pledge reward calculation methods , The time factor is introduced, and the reward rate can be increased as the pledge time increases (estimated time spent: 8~10 weeks)  

Phase 3: Price limit transaction, support DEX limited price pending order transaction (estimated time spent: 12~15 weeks)  

Phase 4: Support LP pledge lending. In addition to supporting LP pledge on its own platform, it also plans to support LP pledge on other mainstream AMM exchanges, such as uniswap, pancakeswap, etc. (estimated time spent: 8~10 weeks)  

Stage 5: Complete the design of the Dex Pro platform Token mechanism and economic model (estimated time spent: 2~3 weeks)  

Stage 6: Support NFT pledge mining, pledge lending, pledge lending will use the quotation mechanism to determine the loan amount. (estimated time spent: 8~10 weeks)  

Stage 7: Support users to apply for the creation of LP and single currency pledge reward pools by themselves, and create a reward pool for a certain period of time through voting and bidding. (estimated time spent: 12-15 weeks)  


Deliverables:  
- front-end and back-end code, contract code  
- design document  
- Phase System demo, Available version system  

Cost:$200,000

Raising funds costs are expected to be used for: 

●Improve project design  

Including perfect project direction, technology, business model, perfect project token model, writing project white paper, etc.  

●Development  

The software system was developed according to the project plan.  

●Promotion  

The promotion and operation of the project is not limited to the operation of telegram, Twitter and other communities, and prepares for the subsequent financing and development of the project. 

●Recruitment  

Recruit more talents to join our team.  

**Write at the end:**

I have been exposed to blockchain in 2017 and after experiencing the Market turmoil of 2017 ~ 19, I have used to thought that blockchain industry is just make for a pure speculative market. But in 2019 and 2020,the development of Defi really made me realize that I was thinking wrong and corrected my idea completely. In 2018, I used to thought about what if we using the decentralized blockchain tech into some application of P2P, then may the collective thunder incident of P2P will not happen. However, due to the unmature situation at that time, the low market quotes made me have a relatively pessimistic mood about the development of blockchain at that time.  
But now, I doubt no more, and firmly believe that blockchain technology will be one of the most promising technologies in the next 10 years. First of all, the reform that now gradually permeates the financial field, I believe that decentralized finance will gradually revolutionize the traditional centralized system, to all kinds of P2P, finance, lending, integral systems,even to the IPO,  will be gradually changed by the decentralized mechanism, making financial services more transparent, universal, fair, and can benefit everyone. And this is just the beginning, DAO has the power to make a different in all industries.  
For example, in 2017,the founder of KUAIDI has proposed to use blockchain technology to build a decentralized Didi/UBER, but limited to the development of blockchain technology and industry, as well as people's acceptance of the concept of decentralization, or proposed that the founder himself did not implement it consistently, this conception did not continue. But it doesn't mean that these ideas are wrong. It's just like the first tablet-PC was invented by Microsoft, but it is Apple making it popular, just the reason of the right time.  
And we are now determined to join the construction of a decentralized system, hoping that we can think big,but start small, and can eventually make a different.  
We will start from the Defi decentralized finance into the field of blockchain technology development, base on the existing Defi achievements to learn and make innovation, constantly promote the application and popularization of blockchain and decentralized technology, and can eventually penetrate into other industries, establish many other kinds of DAO organization system, promote blockchain decentralization, producing audit free, reliability innovation solutions that the traditional industry workflow cannot achieve.  
We will use all means to finance the project,we heartily expect the support of gateio, and we will humbly accept any suggestions in any respect.   
Finally, thanks again for reading!  
