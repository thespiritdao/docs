# ⚖ SpiritDAO Governance

The purpose of the SpiritDAO Governance Proposal Process ("the SDGP process") is to provide a structured process for making changes to the shared resources of the SpiritDAO Network. For these shared resources, governance processes are needed to grant or deny access and approve or reject proposed changes.

<details>

<summary>Governance Bodies</summary>

The following bodies will form part of the SDGP process and are collectively called the SpiritDAO Network, composed of a Primary DAO and Pods. \
\
Pods are customizable coordination structures where we can encode specific governance rules into the smart contracts enabling them. We leverage [<mark style="color:yellow;">Hats Protocol</mark>](membership/tech-stack.md) to support the formation of Pods. For more details on how to organize pods, see [<mark style="color:yellow;">this documentation.</mark>](https://docs.metropolis.space/docs/pod-basics/pod-configurations)

#### **Primary DAO**&#x20;

Votes to validate the community’s sentiment and then schedule for on-chain execution, enabling SpiritDAO Members to exercise direct democracy (directly propose and approve proposals of any kind) and elect members to new or existing Pods.

Primary DAO votes are considered community-wide proposals and will typically involve the strategic direction of our DAO/non-profit efforts, major financial decisions, and meta-governance proposals.&#x20;

For Primary DAO votes, the Executive Pod holds the right to organize proposals as Optimistic, meaning that any individual not voting is counted as a "Yes" vote.&#x20;

#### Pods

Pods are controlled by the Primary DAO but may operate within custom frameworks of governance.  See [<mark style="color:yellow;">Pod Agreements</mark>](pod-agreements.md) for more details about existing Pods.

</details>

<details>

<summary>Separation of Powers </summary>

Members may not be elected to leadership positions in multiple pods simultaneously.&#x20;

</details>

<details>

<summary>Formation of new Pods </summary>

The Primary DAO can deploy a new Pods, be given control over an already deployed Pod, dissolve an existing Pod, or spin off a Pod as an independent DAO at any point in time.&#x20;

Each Pod shall have its own operating agreement outlining, at a minimum, the responsibilities of its members, which shall be listed as an Appendix to the [<mark style="color:yellow;">SpiritDAO Network Charter</mark>](membership/network-agreement.md).&#x20;

In case of conflict between agreements, the [<mark style="color:yellow;">SpiritDAO Network Agreement</mark>](membership/network-agreement.md) shall prevail over any Pod operating agreement.

Pod Proposal Templates may be found within our [<mark style="color:yellow;">Collaboration Hub</mark>](https://app.charmverse.io/join?domain=spiritdao).

</details>

<details>

<summary>Treasuries &#x26; Permissions </summary>

**Community Vault:** The reserve treasury of SpiritDAO. Used to fund Pods and/or to obtain yield.&#x20;

* Any SpiritDAO Token Holder can make proposals for Financial Proposals as described in the Financial Proposals section of this SDGP process document.
* The Executive Pod is responsible for the responsible delegation of Community Vault funds to other Pods. A Primary DAO vote must approve any yield/vesting arrangements.
* Community Vault: [<mark style="color:yellow;">0xF3c47077C406FeA33daD4BE498fDf03Cb5d4537f</mark>](https://etherscan.io/address/0xF3c47077C406FeA33daD4BE498fDf03Cb5d4537f)

**Operations Vault:** A central treasury of the SpiritDAO Network. Used to fund general operations and make strategic funding.&#x20;

* Any SpiritDAO Token Holder can make proposals for Financial Proposals as described in the Financial Proposals section of this SDGP process document.&#x20;
* And any wallet with permissions for the Executive Pod (i.e., any member of the Executive Pod) can program and delete Financial Actions in the Executive Pod as per the Executive Pod operating agreement.

**Additional Treasuries:**&#x20;

* Pods create additional treasuries under the exclusive control of the Pod (but not entirely outside the control of the Primary DAO). Pods use a lightweight permissions layer around a [<mark style="color:yellow;">Gnosis Safe</mark>](https://gnosis-safe.io/) multi-sig wallet to create more flexible and composable working units.&#x20;
* Both the Primary DAO and Pods may create additional treasuries through a majority vote of SpiritDAO Token Holders (Primary) or Pod Members (Pods)
  * Example: SpiritDAO will provide virtual and physical utility for holders, and therefore, the operations vault may require sub-vaults in future moments.

</details>

<details>

<summary>Proposals</summary>

_Note: For a abridged visual representation of the Proposal Process see_ [_<mark style="color:yellow;">How to Contribute</mark>_](membership/how-to-contribute.md)_._

Any Verified SpiritDAO Member can create a Proposal in the Primary DAO. \
Members may visit our [<mark style="color:yellow;">Collaboration Center</mark> ](https://collab.spiritdao.org)to view our available proposal templates and guides.

Any Pod may remove a scheduled proposal at any time (e.g., Veto right) should they have the power to do so as per their operating agreement and this Charter.&#x20;

All proposals must comply with the Requirements for Proposals & the specific format and process for the type of proposal as follows:

**The Requirements for Proposals:**&#x20;

1. Public deliberation: all proposals must be shared during the public deliberation phase in the SpiritDAO Forum located in our Collaboration Center and linked in the [<mark style="color:yellow;">SpiritDAO Discord Server</mark>](https://discord.gg/Dg94YJxAEm) unless these services are unavailable.&#x20;
2. Voting period: the vote must be at least 7 days.&#x20;
3. Scheduling: once approved, proposals are executed by the Executive Pod.

**Types of Proposals:**

1. _<mark style="color:green;">Charter Improvement Proposals</mark>:_ proposals focusing on the amendment or enhancement of the SpiritDAO charter.
2. _<mark style="color:green;">Funding Proposals:</mark>_ proposals that require the transfer of funds, typically to compensate for work completed/committed to be completed.&#x20;
3. _<mark style="color:green;">Meta Governance Proposals</mark>_<mark style="color:green;">:</mark> proposals that change the governance processes, parameters, or tooling of SpiritDAO.
4. _<mark style="color:green;">Elections Proposals:</mark>_ proposals where an election has already been agreed by the community (in the SpiritDAO Charter or in a previous proposal), and the proposal aims to source the candidates/options and then launch a vote to decide between them.
5. _<mark style="color:green;">Pod Proposals:</mark>_ proposals to fund new/existing pod operations and efforts.
6. _<mark style="color:green;">Text Improvement Proposals:</mark>_ proposals to add new, remove, or edit content within _Self-Actualization in the Age of Crisis._&#x20;
7. _<mark style="color:green;">Other Proposals:</mark>_ any other type of proposal.

**Process for Financial Proposals and/or Other Proposals (sequential order):**

_Public deliberation phase_: A post with the draft of the proposal is posted in the SpiritDAO Forum for a minimum of 7 days and a maximum of 14 days and must follow the appropriate format. Proposals must follow the appropriate format depending on the type.

_Voting_: the proposal (or a revised version incorporating the community’s feedback) is posted for a vote.

1. For calculating voting power:&#x20;
   1. Primary DAO: 1 Membership Token = 1 Vote
   2. Pod Voting: Voting power per membership token may in relation to merit earned.

_Approval_: a proposal is deemed approved and scheduled for execution if the following conditions are reached:&#x20;

1. Support: The vote shall be deemed as “passed,” with a simple majority (>50%) of the participating SpiritDAO Token holders having voted in favor.
   * Primary DAO proposals intend to leverage **Optimistic Governance** to overcome voter apathy and organizational impasse. Any vote not cast in a specific direction (yes/no) out of the total possible votes is considered a "Yes" vote. The scope of total votes may vary for specific pods, but the Primary DAO always considers all possible votes.&#x20;
   * Pods may also choose to leverage Optimistic Governance or require specific quorums (minimum vote amounts) for votes to pass.

* When a proposal includes a code submission, the Dev Pod has up to 14 days to decide and communicate via a post in SpiritDAO Forum whether a proposal will be:&#x20;
  1. Accepted and incorporated.&#x20;
  2. Submitted to a 3rd party audit to determine its safety (conditional on the Operations Vault having the necessary funds).
  3. Rejected as malicious, technically infeasible, or economically infeasible (if an audit is required and the Operations Vault lacks the necessary funds to cover the costs of the audit).

**Process for Elections (sequential order):**

_Public deliberation phase:_ A post with the draft of the proposal is posted in the SpiritDAO forum for a minimum of 10 days and a maximum of 30 days with the format:

1. Title of Proposal (in the format “Election Gov Proposal: \[Proposal Title]”)
2. Description of the Action (including what permissions will be given/removed for which Pod and/or Primary DAO)
3. If the election is proposed before the stipulated in the agreements of the Pod, add a description of why an advanced election is needed
4. Optional but ideal: ETH Wallet address of the author(s) and/or other identifiers.

_Sourcing Candidates:_ Candidates can be proposed (and/or propose themselves) by replying to the Forum post (only one candidate per post reply) in the following format:

1. Identifier: ETH wallet address, name, discord handle, and optional twitter handle / other identifiers
2. Rationale: description of why they are an ideal candidate for the position

_Voting_: top 10 candidates with the highest number of upvotes in the SpiritDAO Forum will be put forward to a vote.

1. If the election is proposed before the frequency stipulated in the operating agreement of a specific Pod (if any), the vote must also include the option to keep the current permissions even if the current wallets were not amongst the top 10 candidates.&#x20;

_Approval & Execution:_

1. In the exceptional case that two proposed users gain the same number of votes, the winner will be the candidate who reaches the tied number of votes first.&#x20;
   * Example: Candidate A and B both tied at 7 votes, Candidate A wins because it reached 7 votes a day before Candidate B. If votes are submitted in the same block, repeat the vote.

</details>

<details>

<summary>Disputes</summary>

Disputes between members that can not be addressed through facilitation or mediation, shall be resolved by the Executive Pod.&#x20;

In the future SpiritDAO may develop an internal court to separate the function from the Executive Pod.

</details>
