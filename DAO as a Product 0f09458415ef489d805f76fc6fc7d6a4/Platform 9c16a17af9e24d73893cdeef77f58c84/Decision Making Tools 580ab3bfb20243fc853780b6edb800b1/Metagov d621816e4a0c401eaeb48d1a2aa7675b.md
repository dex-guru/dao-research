# Metagov

Metagov is an API wrapper and architecture for digital governance services. We think of it as v0.1 of a "governance layer" for the internet. See [docs.metagov.org](http://docs.metagov.org/).

Metagov is a unified API gateway for digital governance services. It’s designed to support rapid prototyping of governance systems, decision-making processes, and social workflows across a range of platforms, from forums to chat services to blockchains. To help people prototype, Metagov ships with a powerful driver for authoring governance policies over multiple platforms.

Metagov is a Django backend service with a plugin architecture. Metagov is meant to be deployed alongside a governance [Driver](https://docs.metagov.org/en/latest/design.html#driver), where the specific governance decisions are made. Drivers written in Django can import the Metagov Django app directly. Drivers written with other frameworks or using other languages will need to communicate with Metagov via HTTP. Both kinds of drivers use Metagov to communicate with zero or more third party services.

![Untitled](Metagov%20d621816e4a0c401eaeb48d1a2aa7675b/Untitled.png)

![Untitled](Metagov%20d621816e4a0c401eaeb48d1a2aa7675b/Untitled%201.png)

### Governance framework

![Untitled](Metagov%20d621816e4a0c401eaeb48d1a2aa7675b/Untitled%202.png)

> For the field of online governance, we believe the best strategy is to focus on *a common publishing standard for community constitutions*.
> 

### Links

- [Metagov Gateway](https://gateway.metagov.org/), a unified API gateway for digital governance services
- [Modular Politics](https://www.metagov.org/modpol), a working paper outlining a governance layer for the internet
- [Govbase](https://www.metagov.org/govbase), an open database of projects and tools in online governance
- [Agreement Engine](https://metagov.org/agreements), a tool for building contract systems on the internet
- [DAOstar One](https://daostar.one/), a roundtable working towards an ERC standard for DAOs
- Metaeth, a Discord bot for ethical, responsive digital ethnography
- [Cryptopolitics](https://metagov.org/cryptopolitics), a political typology quiz for crypto
- [Composing games into complex institutions](https://arxiv.org/abs/2108.05318), a research paper
- [The Metagovernance Seminar](https://metagov.org/seminar/), a weekly seminar