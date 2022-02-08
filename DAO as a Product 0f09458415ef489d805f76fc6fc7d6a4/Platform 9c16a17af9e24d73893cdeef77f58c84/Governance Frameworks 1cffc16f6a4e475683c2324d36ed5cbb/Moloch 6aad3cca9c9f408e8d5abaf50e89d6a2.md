# Moloch

Moloch is the simplistic framework

### **Protocols**

- [MetaCartel](https://twitter.com/meta_cartel)
- [Raid Guild](https://raidguild.org/)
- [Rocket](https://twitter.com/RocketNFT)
- [Orochi](https://twitter.com/OrochiDAO)

### **Key Facts**

- On chain voting
- Ragequit mechanism
- Membership is Permissioned, Membership Resignation/Reduction is Permissionless

### **Governance Process (v2):**

*With Moloch V1:*

[https://miro.medium.com/max/875/0*-80DQF0Eaa9mx_EC](https://miro.medium.com/max/875/0*-80DQF0Eaa9mx_EC)

*With Moloch V2:*

[https://miro.medium.com/max/875/0*sxSXvYHevOToXtJ6](https://miro.medium.com/max/875/0*sxSXvYHevOToXtJ6)

**States**

- **Queue**
    
    The Proposal is submitted and waiting for Voting Period. Once a proposal is submitted, it is marked as an ‘Unsponsored Proposal’. 
    
- Sponsored
    
    Any member of the DAO can choose to ‘Sponsor’ that proposal, effectively moving it from the Unsponsored queue into the Voting Period. 
    
- **Voting**
    
    The Proposal can be voted on by Members.
    
- **Grace**
    
    The Proposal can no longer be voted on. Any Members who voted ‘No’ and do not have an existing ‘Yes’ vote on other Proposals can ragequit before the Proposal is processed.
    
- **Ready for Processing**
    
    After the Grace Period, proposals move here where they can be processed by any Member, executing their purpose (Ex. distribute Shares, accept Tribute).
    
- **Completed**
    
    After being processed, all Proposals end up here as a record for the DAO of all the final states of all proposals.
    

**No Quorum needed**

It doesn’t matter how many votes are cast, they are literally just counted against each other, and unless more than 50% vote yes, the proposal will fail.

### Changes v2 vs v1

**Multi-Token Support**

Moloch v2 DAOs can now hold up to 200 different assets, as opposed to just one. This means DAOs can hold assets other than ETH, including stablecoins like DAI, time tokens like [$MAGIC](https://etherscan.io/address/0x51876a15Aff97A68ED7DF051cE11fade0b91b384) and even project tokens like Kyber Network Crystals (KNC).

**Funding Proposals**

Instead of receiving shares for proposals, those wishing to receive funding can do so in any of the DAOs assets — such as ETH or DAI — without having to ragequit shares. This means a proposal can request 1000 DAI to completely mitigate volatility that arose throughout the two week processing period.

**GuildKick**

Getting sick of someone who’s clearly going against the DAOs best interest? GuildKick allows members to force a ragequit upon someone else through a unique type of proposal. The kicked member’s shares get burned, and they receive their pro-rata share over the DAOs underlying assets.

**Open Submissions**

Anyone, including those who are not members of the DAO, can now submit proposals on their own, as opposed to relying on a DAO member to submit it for them.

**Trade Proposals**

Hoping to have effective treasury management within a DAO? With trade proposals, DAOs can swap their underlying collateral, for example turning Dai into a transferrable, interest-earning asset like [Chai](https://chai.money/).

**Voting Updates**

Once a proposal is submitted, it is marked as an ‘Unsponsored Proposal’. Any member of the DAO can choose to ‘Sponsor’ that proposal, effectively moving it from the Unsponsored queue into the Voting Period. From there it follows the same process as in V1.

### **Resources:**

- [Moloch Evolved: V2 Primer. Everything you need to know about… | by Cooper Turley | Raid Guild | Medium](https://medium.com/raid-guild/moloch-evolved-v2-primer-25c9cdeab455)
- [Moloch Primer for Humans. WTF is a Moloch DAO and why are they so… | by Ven Gist | Odyssy | Medium](https://medium.com/odyssy/moloch-primer-for-humans-9e6a4f258f78)
- [Whitepaper/Whitepaper.pdf at master · MolochVentures/Whitepaper · GitHub](https://github.com/MolochVentures/Whitepaper/blob/master/Whitepaper.pdf)