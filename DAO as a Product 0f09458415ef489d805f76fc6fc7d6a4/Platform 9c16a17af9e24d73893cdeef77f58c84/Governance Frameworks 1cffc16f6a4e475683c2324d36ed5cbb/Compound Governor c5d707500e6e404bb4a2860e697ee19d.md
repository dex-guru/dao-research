# Compound Governor

Compound Governor was originally developed by Compound Labs for use with COMP voting and proposals. Compound Governor is currently one of the most prominent and widely adopted governance frameworks.

### Protocols

- Uniswap
- Compound

### **Key Facts**

- [On chain voting](https://tally.document360.io/docs/en/on-chain-vs-off-chain-voting)
- [Vote delegation](https://tally.document360.io/docs/en/vote-delegation) is supported

### **Governance Process**

- Voting power is determined based on the number of tokens delegated to each address. This means users *must* submit a delegation transaction before their tokens will be included in governance votes. Users may either delegate to a third party, or self-delegate if they would like to participate in voting directly.
- Only users whose voting power exceeds the **proposal submission threshold** are able to submit proposals.
- Optional **proposal delay** parameter allows protocols to delay the start of voting for a specified length of time after a proposal is submitted, giving time for users to update their vote delegation
- Voting takes place over a predefined *voting period* determined by the underlying protocol (e.g. Compound has a ~2.5 day voting period, while Uniswap uses a 7 day period).
- When the voting period ends, the system first checks if the number of yes votes exceed the protocol's *quorum threshold* (e.g. Compound currently requires 4% of total tokens to vote in support to meet quorum).
- If the *quorum threshold* has been met and the vote gains majority support, the passed proposal is then placed into a *timelock* queue which delays code execution (this is currently set to 2 days for most governance systems).
- Once the time-lock period has elapsed, the proposal can be executed and relevant code or parameter changes are implemented in the protocol.

![Untitled](Compound%20Governor%20c5d707500e6e404bb4a2860e697ee19d/Untitled.png)

### **Autonomous Proposals:**

While submitting proposals directly requires a large share of voting power, participants can submit an *autonomous proposal* with a lower vote requirement. The proposal contract address can then accept vote delegations from users, and will be submitted for a full vote once total delegations have surpassed the *proposal submission* threshold.

### **Governor Alpha and Bravo**

[Understanding Governor Bravo. A review of key changes versus… | by monetsupply | Tally | Medium](https://medium.com/tally-blog/understanding-governor-bravo-69b06f1875da)

Governor Alpha, was set up as an immutable contract. This means any changes to governance parameters (eg. quorum, voting period, etc) require deploying a new governance contract and transferring ownership of the governance timelock. 

Governor Bravo is an upgraded version of the contract allowing for upgrades and changes to the governance parameters without migrating.

![Untitled](Compound%20Governor%20c5d707500e6e404bb4a2860e697ee19d/Untitled%201.png)

### Links

[Compound Governance](https://wiki.withtally.com/docs/compound-governor)

[https://compound.finance/docs/governance](https://compound.finance/docs/governance)

[**OpenZeppelin Governor**](Compound%20Governor%20c5d707500e6e404bb4a2860e697ee19d/OpenZeppelin%20Governor%20c5d27feeaacb47fea4fbf1ea28af045f.md)