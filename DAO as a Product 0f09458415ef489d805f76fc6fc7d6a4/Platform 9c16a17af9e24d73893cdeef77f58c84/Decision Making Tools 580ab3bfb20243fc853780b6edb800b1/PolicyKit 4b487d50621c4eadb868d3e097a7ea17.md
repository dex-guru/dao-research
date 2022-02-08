# PolicyKit

PolicyKit is a software infrastructure that empowers online communities to create a broad range of
governance approaches by writing a small amount of code. PolicyKit empowers online community members to **concisely author a wide range of governance procedures and automatically carry out those procedures** on their home platforms

The IAD framework developed by researchers at the Ostrom Workshop broadly describes complex governance arrangements and centers around actors engaging in an “action situation” where they perform actions in light of an existing structure of rules.

The two main abstractions within PolicyKit are *actions* and *policies*. An action is a one-time event that can occur within a community and is typically first proposed by a community member. In contrast, a policy is a declaration that must always be true and that governs some user capability. For instance, a policy for joining a community might be: “To join the community, a user must be approved by at least one existing member of the community.”

### Layers

In the IAD framework, researchers separate out a “constitutional choice” layer for participatory change in a government’s overall design

Platform actions are one-time events that correspond to a user capability on the platform. This can include posting a message, joining a channel, or editing a wiki, depending on the platform in question.

![Untitled](PolicyKit%204b487d50621c4eadb868d3e097a7ea17/Untitled.png)

### Software Infrastructure:

- A software library for concisely authoring policies in the Python programming language,
- A policy engine, or a continually-running server process that waits for proposed actions and checks them against policies to see whether they can pass,
- A platform integration to a community’s platform where members can attempt platform actions as well as vote on actions while going about their regular activities, and where passed platform actions can execute, and,
- A web interface where members can install PolicyKit to their platform, propose constitution actions, and author policies in a code editor.

### Supported platforms:

- Reddit
- Slack
- Discord
- Loomio
- GitHub
- SourceCred
- Discourse
- Metagov

![Untitled](PolicyKit%204b487d50621c4eadb868d3e097a7ea17/Untitled%201.png)

![Untitled](PolicyKit%204b487d50621c4eadb868d3e097a7ea17/Untitled%202.png)

### Links

Whitepaper: [https://policykit.org/static/policyengine/pdf/policykit_uist2020.pdf](https://policykit.org/static/policyengine/pdf/policykit_uist2020.pdf)

[PolicyKit](https://policykit.org/)

[Welcome to the Docs for PolicyKit! — PolicyKit documentation](https://policykit.readthedocs.io/en/latest/index.html)

[https://github.com/amyxzhang/policykit](https://github.com/amyxzhang/policykit)