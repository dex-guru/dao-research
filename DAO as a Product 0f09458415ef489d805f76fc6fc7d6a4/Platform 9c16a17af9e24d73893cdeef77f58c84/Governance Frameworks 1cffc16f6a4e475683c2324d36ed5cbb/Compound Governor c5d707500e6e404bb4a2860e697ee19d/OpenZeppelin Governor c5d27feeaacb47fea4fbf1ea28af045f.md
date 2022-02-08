# OpenZeppelin Governor

OpenZeppelin's new Governor framework shares many similarities in design with Compound Governer, with some architectural changes and improved standardization that may bring benefits to supported protocols.

### Protocols

- ENS
- PoolTogether

### **Key Facts**

- [On chain voting](https://tally.document360.io/docs/en/on-chain-vs-off-chain-voting)
- [Vote delegation](https://tally.document360.io/docs/en/vote-delegation) is supported
- Optional compatibility with [Compound Governor](https://wiki.withtally.com/docs/compound-governor) components

### [Governance Process](../Compound%20Governor%20c5d707500e6e404bb4a2860e697ee19d.md)

### **Key Changes Versus Compound Governor**

- Modular design and architecture to minimize protocols' need to fork components
- Ability to meet protocol specific requirements with addition of small modules using solidity inheritence
- Minimized use of storage improves gas efficiency
- Two versions of many components: one optimized for efficiency, with another designed for optional compatibility with Compound Governor contracts
- Use of a timelock contract is recommended in most cases, but no longer required (as it is with the Compound Governor framework)

### Links

[OpenZeppelin Governor](https://wiki.withtally.com/docs/openzeppelin-governor)

[https://docs.openzeppelin.com/contracts/4.x/api/governance](https://docs.openzeppelin.com/contracts/4.x/api/governance)

[https://www.youtube.com/watch?v=Lltt6j6Hmww&t=2821s](https://www.youtube.com/watch?v=Lltt6j6Hmww&t=2821s)

[Build Your DAO with OpenZeppelin Governor ft. ENS - YouTube](https://www.youtube.com/watch?v=Lltt6j6Hmww&ab_channel=OpenZeppelin)