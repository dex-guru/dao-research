# Gearbox Protocol

Gearbox is a generalized leverage protocol: it allows you to take leverage in one place and then use it across various DeFi protocols and platforms in a composable way. The protocol has two sides to it: passive liquidity providers who earn higher APY by [providing liquidity](notion://www.notion.so/liquidity-providers/manage-liquidity); active traders, farmers, or even other protocols who can borrow those assets to [trade or farm with x4+ leverage](notion://www.notion.so/Gearbox-Protocol-70ca73f01f4640a8a47c2f47da5807b3).

## Governance

Gearbox Protocol does not have a core team from day 0, no central authority! Initial members handed over the code to the DAO who then deployed the protocol and even decided the initial pools, assets, collateral types, and so on. The DAO consists of the community multisigs and a few hundred of token holders as per the **DAO-First Launch** strategy. Snapshot + multisigs combination is used. See all the info below.

![Untitled](Gearbox%20Protocol%2070ca73f01f4640a8a47c2f47da5807b3/Untitled.png)

### Governance process:

- Ideation process, usually in Discord.
- **Forum proposal and temperature check: first in Main, then in Proposals.**
- Actual formal proposal on snapshot.
    - A proposer should seek technical help to prepare such a transaction prior to submitting a snapshot proposal
- Multisig execution.

- A minimum of 3 days period must be selected on the snapshot
- Minimum 0.02% of total supply to make a snapshot proposal
- A winning vote must also have > 2% total supply quorum

### Governance features

![Untitled](Gearbox%20Protocol%2070ca73f01f4640a8a47c2f47da5807b3/Untitled%201.png)

Gearbox DAO propose the following ways to solve the early participants larger token percentages during the governance process and even possibilities for all participants to make proposals 

Fixes for the issue:

- Whale portions dominating governance as voters;
    - Fix -> community delegators to unite small holders.
    - Delegation is available to streamline community work. Snapshot page delegation is turned on for delegators from the community to unite and allow smaller holders get their voice
- Whale portions delegating and still dominating;
    - Fix -> limit governance weights of whales completely.
    - Company wallet is not allowed to vote
    

The distribution had a few portions:

1. Community members including Credit Account Mining and other portions: full x1 multiplier.
2. Contributors A meaning initial core members: multiplier of x0.125
3. Contributors B meaning initial contributors: multiplier of x0.25
4. Company wallet: cannot vote on anything before and if the governance model changes.
5. DAO wallet: cannot vote unless it gives grants to people, which then gets x1 multiplier.

![Untitled](Gearbox%20Protocol%2070ca73f01f4640a8a47c2f47da5807b3/Untitled%202.png)

C**ommunity voices are over x2 bigger in its voting power than early contributors and initial core members combined**! According to that, the DAO portion can really be counted as a community portion because of who practically gets to decide what to do with it, whereas neither early group can push anything at their own free will. Avoiding situations of the misuse of power.

Multisig:

Multisig must execute whatever proposal reaches winning quorum. Given that multisig are members previously enacted by token holders, meaning the DAO, and are semi-public people with big reputation - in *extreme* cases they could voice against implementing some proposal. However, that could breach *trust* in the governance model and require immediate action and restructuring. This must be exercised carefully.

Token

GEAR token is an ERC20 utility token, starting off as a governance token for the protocol - and then possibly taking any other new function the DAO could envision for it. GEAR token started as non-transferrable. That can be changed by DAO voting.

Anybody who is not a community member is locked for a minimum of 1 year since launch. All of the vestings can be verified on-chain, no trust required. Community retains the largest portions both in terms of the distribution and in terms of voting weights.

![Untitled](Gearbox%20Protocol%2070ca73f01f4640a8a47c2f47da5807b3/Untitled%203.png)

## Working Groups

### Committees

- **Risk and analytics committee. [Discord channel here](https://discord.gg/cxkj9DBJVV).**
    
    This refers to the math on the assets, and LT, which in turn decides on what adapters are even possible to implement at this point.
    
    - Current LTs, document that.
    - Do research on the protocols in the product&strategy section below.
    - Do research on the current HF of CAs and how it influences liquidations costs. [See example](https://discord.com/channels/841203475606011905/866039241083453450/925305441481805845).
- **Dev one: contracts. [Discord channel here](https://discord.gg/cfHZPwJqxK).**
    - Revamp [dev.gearbox.fi](http://dev.gearbox.fi) and make it polished;
    - Make a list of the architectural pieces (Mikael) and outline who can do what. [See Discord](https://discord.com/channels/841203475606011905/865937984691372072/925063020554633217). This will help other contributors better understand the structure and tech needs.
- **Dev two: frontend & web3. [Discord channel here](https://discord.gg/agg3jCAPqJ).**
    - Make a list of the architectural pieces (Mikael) and outline who can do what. [See Discord](https://discord.com/channels/841203475606011905/865937984691372072/925063020554633217). This will help other contributors better understand the structure and tech needs.
- **Marketing committee. [Discord channel here](https://discord.gg/jbVaRhEeXV).**
    - Weekly newsletter / summary
    - Contributor call minutes like overq4 did here on [forum](https://gov.gearbox.fi/t/2021-12-27-dao-call-meeting-minutes/463).
    - Community calls with other projects, documenting them.
    - Working on the videos and the composable leverage narrative on Twitter / etc.
    - Everybody can be a community manager basically, except the specific people in the regional chats. Those can be maintained by some of the contributors, unless we decide we really need focus and efforts on a specific geo group (to be done ad-hoc).

### Task creation process:

There is a core team and contributors. Core team leading the development process but in terms of DAO it proposes to decrease its role in governance process. DAO has a few contributor calls around mid and end of next week to sit together, chat on what the direction members see for it, how to split roles and work, and so on.

Backlog is open to new tasks and discussions. The backlog is moderated

- If you want to become a contributor, just write a small tldr about yourself and your skills in **🗳general-dao**
- keep the chats on-topic and structured, to make sure conversations follow through in the same channels
- **📊gear-econ** is open for everyone for now, but please make sure to ctrl+f and read back as many-many ideas were already discussed

Every chat can jump on a call & put together an initial list of tasks / backlog that are to be added to the corresponding notion page. Stricter moderation will apply to remove the noise & repeating information from the working chats.

### Links

[Governance Model - Gearbox Protocol](https://docs.gearbox.finance/governance/setup)

[(1) Latest Main topics - Gearbox Governance](https://gov.gearbox.fi/c/main/2)

[Gearbox DAO - Working Sheet (notion.site)](https://www.notion.so/Gearbox-DAO-23966f122ae4421492819242b30a0e7a)