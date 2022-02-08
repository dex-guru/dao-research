# DAOStack

DAOstack is a full software stack for building and running decentralized, autonomous organizations: DAOs.

![Untitled](DAOStack%20fa8ff1dd59a94b5aa54b01f068d7dc97/Untitled.png)

**Protocols**

- DXDAO
- necDAO

Key features:

- Holographic consensus

### **Governance Process:**

- **Voting Machines** – A voting machine is a universal contract that operates voting processes. Each voting machine follows its own predefined rules for decision-making. Any set of rules can be implemented, from a simple absolute majority vote to more sophisticated protocols like DAOstack's Genesis protocol.
- **Voting Rights Management** – A voting rights management system is a smart contract that determines how voting rights are distributed. Voting rights management systems must have "balances" that represent the voting power each participant holds. Currently, DAOs on DAOstack use "reputation"-based voting rights. Reputation is a number tracked for each user that can be increased / decreased via proposals or other mechanisms.‌

![Untitled](DAOStack%20fa8ff1dd59a94b5aa54b01f068d7dc97/Untitled%201.png)

## Arc‌

[Arc](https://github.com/daostack/arc) is a Solidity smart contract library for building DAOs. It uses Infra to provide decentralized organizations with voting machines and voting rights management systems. In addition to Infra contracts, DAOs built with Arc have a few basic contract components:

- **Avatar** – The DAO's "account." This contract represents the address of the DAO and holds its assets.
- **Token** – The DAO's native ERC20 token. The DAO can mint and issue this token to members via proposals.
- **Plugins** – Plugins give DAOs superpowers. They can expand the DAO's capabilities in any way: making trades on Uniswap, giving Reputation to agents, upgrading the DAO's contracts, registering new plugins and constraints, and so on.
- **Global Constraints** – Limitations on the actions a DAO can take via plugins. When executing actions, the controller checks the constraints to see if the action violates them and blocks the execution if it does. Constraints might limit how much the DAO can spend on a single proposal, how much Reputation the a single user can have, etc.
- **Controller** – The "access control" of the DAO, managing who can interact with which DAO functions and enforcing the DAO's constraints.

### **Resources:**

[Smart Contracts - v1 (gitbook.io)](https://daostack-1.gitbook.io/v1/introduction/architecture-overview/smart-contracts)