**1.1** **Project process** (you need to fill in the following information):  

**1.1.1** **Basic information**  
 	Project Name format: Rlink_Phase1.md  
 	Team name(s): Rlink  
	Payment Method: 2000 GT token  
	Payment Address: gt11475rwxzgu6wt8xe7qrdksrluze6srk3k7ud6w73rxckcc4c0qguxad82acnqvupwe03e6f  
	
**1.2** **Project Overview**  

Rlink is the world's first oracle that completely realizes decentralized recommendation relationship and rebate. Rlink want to realized the whole process of recording the reference relationship on the smart contract and making chain rebates according to the reference relationship. 

**1.2.1** **Project Introduction**

In the phase1,we need to develop this oracle and test this oracle in the test chain  We also will launch this oracle in the Gate chain which is compatible with EVM to serve those dapp developers.

BP of this project: https://docs.qq.com/pdf/DUktkcW9iemZ0TERo

**1.3** **Project details**  
Invitation relationship: This module records the invitation relationship between all addresses using a Hash map, and provides the function of querying and writing the associated address of any address.  Realize infinite level address associated record.  
Distribution: This module provides the function of distributing tokens for DAPP. By calling this module, DAPP can easily realize the distribution of tokens to a specified address and its associated address at a specified rate.  Supports multi-level associated address distribution  
![architecture](https://raw.githubusercontent.com/Rlinknetwork/rlink/main/docs/architecture.png)


**1.3.1** **Technology Stack Used**  

Technology 1: Etheruem/GateChain/Solidity/Web3 

Technology 2: Javascript

 **1.4** **Team**  
 - Steven，Team leader
 - Peter，Project Product Director
 - And other 24 members

 **1.4.1** **Team Profile:**  

 **Steven**

 Graduated from the Chinese University of Hong Kong with a double bachelor's degree in mathematics and information engineering, and a master of mathematics from the University of California, Berkeley
Worked in the fixed investment department of Bank of America Merrill Lynch
AItrade, a quantitative trading project, was founded in 2015 to provide data, analysis, and direct transaction services for Quanke
Created in 2018, the Dapp project AllBet has long been in the top three of the Tron rankings
Created TopDapp media and sold it to overseas community teams
FilWorld community technical partner, providing Fil-based mining pool and operation development.XZ Blasting Rock Fund Technical Verifier, providing technical verification for decentralized projects

**Peter**
 
 Project Product Director, Master of User Experience at Kingston University, London, senior blockchain player, bought the first Bitcoin in April 2013, designed and participated in the development of multiple blockchain applications, and has a profound understanding of decentralization and defi applications opinion.

**1.4.2** **Information of Project Leader:**  
Name: Peter

Mailbox: wangmingping@dooge.io / 744032924@qq.com

**1.5**   **Legal structure:**  
Legal Representative: Daoji technology company

Registered Address:  2402G, Block A, Tianan Digital Times Square, Che Gong Miao, Shenzhen, Guangdong Province, China

**1.6** **Team Code Warehouse**  
Source Code Repository:  https://github.com/Rlinknetwork/rlink

**1.7**

Project Direction:Development of Rlink - MVP - Phase 1 

Iteration Cycle:   2 months

Iteration Content:  milestone 1 ; milestone 2

Cost: 2000 GT token

**Milestone 1 —completed the core code development**
- **Estimated Duration:** 1 month
- **FTE:** 3
- **Costs:** 10,00 GT

In the milestone, our team will completed core code development to realize one-level rebates on the smart contract

| Number | Deliverable | Specification |
| ----- | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | Documentation includes contract interface description documentation, invocation examples. |
| 0c. | Testing Guide | Core functions will have test demo coverage (min. 50%) to ensure functionality and robustness. In the guide we will describe how to use test demo. |
| 1. | Address relation | We will coding relation module for record one-level address relaitons by a hash map and query address relation functions |  
| 2. | Distribute | We will coding distribute module for distribute token by one-level address relations |  

**Milestone 2 —Implement more features**
- **Estimated Duration:** 1 month
- **FTE:** 3
- **Costs:** 10,00 GT

In the milestone, our team will realize two-level rebates on the smart contract. We will test this project in the parallel chain which is compatible with EVM

| Number | Deliverable | Specification |
| ----- | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | Documentation includes contract interface description documentation, invocation examples. |
| 0c. | Testing Guide | Core functions will have test demo coverage (min. 50%) to ensure functionality and robustness. In the guide we will describe how to use test demo. |
| 1. | Address relation | We will upgrade relation module for record two-level address relaitons by hash map and query address relation functions |  
| 2. | Distribute | We will upgrade distribute module for distribute token by two-level address relations | 