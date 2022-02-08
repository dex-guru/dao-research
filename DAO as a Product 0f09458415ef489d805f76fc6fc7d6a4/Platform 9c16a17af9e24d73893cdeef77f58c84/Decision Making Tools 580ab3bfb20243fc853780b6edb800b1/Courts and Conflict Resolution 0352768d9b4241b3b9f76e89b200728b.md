# Courts and Conflict Resolution

## Kleros

Kleros is a dispute resolution protocol that provides arbitration for the type of subjective conflicts that smart contracts do not address. This is done by having a set of jurors randomly drawn for each dispute and having them vote to ensure a given verdict.

The Kleros court process works in the following way:

- Once a Dapp sends a dispute, the system randomly picks jurors in a court specified for the case in question.
- The case enters the evidence submission period where all interested parties (disputing parties, jurors, challengers, and any external agent) are able to submit their evidence.
- After the evidence period is finished, jurors are able to vote on the case. For now, Kleros jurors can vote 'Yes', 'No' and 'Refuse to Arbitrate'. The third option is available in cases of an invalid submissions, illegal or morally unacceptable content or evidence.

Kleros provides a number of specialized courts by separated by domain:

![Untitled](Courts%20and%20Conflict%20Resolution%200352768d9b4241b3b9f76e89b200728b/Untitled.png)

To become a juror, users should stake their PNK token in specific court / sub-court. Each court has an amount of PNK that will be locked into the case once one’s been drawn as a juror, which is a constant PNK amount per vote and varies from court to court.

Key statistics:

- Disputes total: 1099
- Top 3 courts: Humanity Court, Onboarding, Blockchain
- Active jurors: 762

## Aragon Court

Aragon Court is a dispute resolution protocol that handles subjective disputes that cannot be solved by smart contracts. This is achieved by having a set of guardians drafted for each dispute who will vote to guarantee a certain ruling.

The Aragon Court process works in the following way:

- Guardians sign up to get drafted into the court by activating ANT tokens in Aragon Court's smart contract. The more tokens a guardian has activated, the higher the probability of getting drafted.
- Guardians are expected to perform certain duties and responsibilities, like reviewing arguments for a dispute and casting a vote.
- Failing to cast a vote will result in guardian’s locked tokens getting slashed and redistributed to the winning guardians after the final ruling

Key statistics:

- Active jurors: 102

### Links

[Court - Kleros (gitbook.io)](https://kleros.gitbook.io/docs/products/court)

[yellowpaper.pdf (kleros.io)](https://kleros.io/yellowpaper.pdf)

[Aragon Court - Aragon Help Desk](https://help.aragon.org/article/41-aragon-court)