---
id: nsdai
title: nsDai Strategy
sidebar_position: 1
sidebar_class_name: hidden
---

**This strategy allows users to leverage their DAI holdings** by depositing them into an sDai vault, which is a specialized financial vehicle. This depositing action allows their DAI to be put to work, generating potential profits over time. The approach combines the security of DAI, a stablecoin, with the revenue-generating power of DeFi strategies. This mechanism is designed to provide users with a more effective way to maximize the potential return on their DAI investments.


This strategy is straightforward as the logic is very simple: it consists of depositing tokens into DSR to acquire sDai.

![alt](/content/sdai.png)


### Source of yields
    - Maker Protocol fees coming from DAI borrow and treasury earning.


### What is sDAI

    - sDAI is a special version of the DAI cryptocurrency that lets you earn extra money (yield) through the Maker protocol, while still being able to use your DAI as usual.

    - You can easily convert your DAI to sDAI and back without needing to use a cryptocurrency exchange, by simply depositing or withdrawing from a specific feature called the Dai Savings Rate (DSR) module.

    - With sDAI, you can do all the things you normally do with DAI, like transferring it to others, staking it to earn rewards, lending it, and more.

    - To use sDAI and take advantage of its benefits, you can go to the SparkLend website and interact with it directly from there.

    - More about [sDAI](https://docs.spark.fi/defi-infrastructure/sdai-overview/dsr-and-sdai#what-is-sdai):

### What is DSR

    - The Dai Savings Rate (DSR) is a feature within the Maker Protocol that enables Dai holders to earn savings by actively engaging with the DSR contract.

    - To earn savings, users must manually transfer Dai from their wallet to the Maker Protocol, with the assurance that Dai can be instantly redeemed without liquidity constraints, but only back to the original depositing account.

    - Integration of DSR functionality by custodians, decentralized exchanges, wallets, or dapps is advantageous as it allows any user to earn savings on their Dai holdings.

    - More about [DSR](https://docs.spark.fi/defi-infrastructure/sdai-overview/dsr-and-sdai#what-is-dsr):

### What is Spark

    - Spark aims to enhance the DAI ecosystem as part of the MakerDAO community, positioning itself as a next-generation DeFi infrastructure.

    - It introduces SparkLend, a DAI-focused money market protocol that integrates liquidity from Maker and other top DeFi protocols.

    - sDAI, a yield-bearing stablecoin within Spark, represents DAI in the Dai Savings Rate (DSR) module, funneling revenue from the Maker protocol back to DAI holders.

    - Spark features SparkConduits, enabling direct liquidity transfer from Maker to various protocols. It operates under the governance of SparkDAO, a subDAO of Maker Allocator, scheduled to launch its governance in May 2024.

    - More about Spark:
      - [Website](https://spark.fi/)
      - [Docs](https://docs.spark.fi/)
      - [Analytics](https://dune.com/facundol2/spark-protocol)
      - [Spark on Twitter](https://twitter.com/sparkdotfi)

### What is MakerDAO

    - MakerDAO aims to stabilize the crypto economy using a dual-token system: Dai for stability and MKR token for governance, emphasizing the necessity of a decentralized stablecoin for digital financial benefits.

    - It champions decentralized finance (DeFi) accessibility, striving for economic empowerment and equal access to the global financial market for all.

    - The Multi Collateral Dai (MCD) update expands collateral options to include various Ethereum-based assets, contingent on approval by MKR holders.

    - This enhancement introduces new features to the protocol, promoting broader asset acceptance and flexibility. 

    - More about Maker:
      - [Website](https://makerdao.com/en/)
      - [Docs](https://docs.makerdao.com/)
      - [MakerDAO on Twitter](https://twitter.com/MakerDAO)



### Understanding Risks Associated with SDAI

1. **Smart Contract Risk**:
    - sDAI, like other DeFi protocols, is susceptible to exploits, including smart contract vulnerabilities and malicious attacks.

2. **Regulatory Risks**:
    - MakerDAO's shift towards RWA-based collateral introduces regulatory uncertainty due to its decentralized nature.
    - Increased reliance on RWAs may lead to compliance challenges and potential regulatory gaps.

3. **Collateral Risks**:
    - RWAs' default risks may result in collateral shortfalls, jeopardizing the 1:1 USD peg of sDAI.
    - Fluctuations in the DAI Savings Rate (DSR) could strain liquidity buffers if significant amounts of sDAI are minted or burned abruptly.
    - RWAs' sensitivity to interest rate fluctuations may lead to losses if redemptions are required before maturity.

4. **Collateral Risks**:
    - MakerDAO's engagement with multiple counterparties exposes it to credit risks such as liquidity, reputation, and settlement challenges.

5. **Centralization and Transparency Risks**:
    - Pursuing additional returns through RWAs may increase centralization within MakerDAO. 
    - Onboarding RWAs reduces transparency compared to on-chain crypto assets, posing transparency  risks.

