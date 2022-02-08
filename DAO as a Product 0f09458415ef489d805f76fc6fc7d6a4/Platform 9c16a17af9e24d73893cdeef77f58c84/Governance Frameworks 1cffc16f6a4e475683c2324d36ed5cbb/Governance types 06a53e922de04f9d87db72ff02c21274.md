# Governance types

DAOs of the future will leverage nuanced governance across three main categories:

- Token Governance — Direct democracy with “Executive Branch” like powers
    - Token Governance should only be used for the most important decisions.
- Optimistic Governance — Representative Democracy with “Legislative Branch” like powers
    - Optimistic Governance should empower key stakeholders to take the reign subject to token holder approval.
- Security Guardian — Conditional Omnipotence with “Judicial Branch” like powers
    - The Security Guardian should maintain conditional omnipotence for fast acting security concerns.

![Untitled](Governance%20types%2006a53e922de04f9d87db72ff02c21274/Untitled.png)

### **Token Governance**

Token Governance means all holders need to vote in order to effect change. This is “positive consent” in the sense that enough stakeholders need to actively approve a new proposal. It functions as an Executive Branch, maintaining full authority over all other components of the system.

Token Governance can have any combination of the following properties:

- Quorum — a minimum amount of approval to pass
- Delegation — appointing a representative to vote on your behalf
- Timelock — A delay after a proposal is passed before taking effect
- Vote-Escrow — locking votes for a time period to earn more votes

Token Governance should ideally only be used on the most important decisions, including but not limited to:

- Minting new tokens (diluting holders)
- Upgrading contracts
- Changing admin control
- Appointing/Vetoing other governance layers

Existing Token Governance contracts:

- [OZ Governor](https://docs.openzeppelin.com/contracts/4.x/api/governance)
- [Governor Bravo](https://medium.com/tally-blog/understanding-governor-bravo-69b06f1875da)
- [Curve VotingEscrow](https://github.com/curvefi/curve-dao-contracts/blob/master/contracts/VotingEscrow.vy).

### **Optimistic Governance**

An Optimistic Governance model allows a core group of elected actors to enact proposals on behalf of the community. 

This form of governance is considered “negative consent” because in the happy path, there is no intervention from token holders to enact a proposal. Enough stakeholders need to actively block a new proposal for it to not take effect. 

It functions as a Legislative Branch, with elected representatives drafting and enacting proposals for the benefit of the community under the watch of Token Governance and the Security Guardian.

It is ideal for nearly all governance applications:

- Parameter changes
- Contributor compensation
- Issuing Incentives
- Minor upgrades/integrations

The Optimistic Governance would use:

- [OpenZeppelin TimelockController](https://docs.openzeppelin.com/contracts/4.x/api/governance#TimelockController) and allow key stakeholders to veto.
- [Optimistic Approval](https://github.com/fei-protocol/fei-protocol-core/blob/develop/contracts/dao/OptimisticTimelock.sol). This concept originated with [Gyroscope](https://docs.gyro.finance/governance/primitives/optimistic-approval).

### **Security Guardian**

The Security Guarding is emergency shutdown mechanics on critical functionality. 

The Security Guardian should have “conditional omnipotence”, in other words it can act immediately but only on pre-defined behaviors. These behaviors should include:

- Pausing contracts
- Vetoing malicious Optimistic or Token Governance proposals
- Force actions that may otherwise be inactive

The best Security Guardian is simply a [Gnosis Safe](https://help.gnosis-safe.io/en/articles/3876461-create-a-safe), which can use [OpenZeppelin Defender](https://defender.openzeppelin.com/#/) to store and streamline security runbooks.

### Links

[Decentralized Governance Structures | by Joey Santoro | Fei Protocol | Dec, 2021 | Medium](https://medium.com/fei-protocol/decentralized-governance-structures-9c4eb8a3e452)