# Aragon Govern

Aragon Govern is framework for frictionless DAO governance with on-chain execution and plug-in dispute resolution.

### **Key Facts**

- On chain voting
- Optimistic governance

### **Governance Process**

![Untitled](Aragon%20Govern%20c3fec09707e7457ea9c3ac206a8c9426/Untitled.png)

- Optimistic Governance assumes that all actions are legitimate unless proven otherwise.
- In practice, this means that governance becomes a perpetual-motion machine of proposals that are scheduled as on-chain transactions to execute by default *unless* they are specifically challenged in Aragon Court during a Dispute Time Delay set by the DAO.
- DAO transactions cannot be executed immediately. Instead, these are delayed by a period of time set by the DAO. This assumes 'optimistically' that all transactions are legitimate but gives any DAO member the opportunity to challenge the transaction in our decentralized dispute resolution system, Aragon Court. A successful challenge will cancel the transaction.
- A collateral deposit set by the DAO is required to schedule a transfer of DAO funds. This is refunded at the close of the execution window unless someone has successfully challenged the transaction in Aragon Court, in which case it will be forfeited to the Court Guardians.

### Links:

- [Getting started - Aragon Govern](https://docs.aragon.org/govern/docs/developers/getting-started)
- [Aragon](https://aragon.org/)