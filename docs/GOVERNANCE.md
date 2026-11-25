#🌈 Governance Proposal

##🌈 Purpose

The proposed DAO would govern selected project-level decisions, including whether to offer an official commercial edition, how project revenue is allocated, and how the community's development priorities are set.

The DAO is a design proposal only. No token, DAO contract, treasury, legal entity, or voting process is represented as deployed.

##🌈 Proposed allocation

The current project direction reserves the governance-token allocation as follows:

| Allocation | Share | Intended role |
|---|---:|---|
| Gamlr | 49% | Permanent organizational allocation |
| Contributors | 51% | Contributor community allocation |
| **Total** | **100%** | |

The 49% Gamlr allocation is intended to remain reserved to Gamlr. The remaining 51% is intended for contributors under a transparent contribution policy.

Before implementation, the project must define what “permanent” means technically and legally: whether the allocation is non-dilutable, whether tokens can be transferred, how lost keys are handled, whether the allocation can delegate votes, and what happens during a legal or organizational restructuring. These details are not yet decided.

##🌈 Governance scope

Potential DAO responsibilities:

- Approving or rejecting an official commercial release.
- Setting monetization principles and revenue-allocation policies.
- Approving major project funding and treasury expenditures.
- Prioritizing major roadmap proposals.
- Approving changes to governance rules, subject to protected commitments.

Routine engineering decisions should remain with maintainers and technical reviewers. Token voting on every code-level choice would slow development and create unnecessary governance overhead.

##🌈 Free-edition guarantee

A free edition is a mandatory and enduring project commitment.

A commercial release must not remove, replace, or make the free edition unavailable. The governance system should not permit an ordinary monetization proposal to repeal this guarantee.

The following implementation details still need a formal decision:

- What “free” means: no purchase price, no mandatory subscription, and whether optional donations are allowed.
- Whether the free edition must be feature-equivalent to the commercial edition.
- Supported platforms and minimum system requirements.
- Where the free edition must be hosted and how mirrors or archival copies are maintained.
- Whether the free edition includes source code and under which license.

The preferred direction is to preserve open-source access to the project's own code and to use licenses that make independent forks possible. This preference is not a finalized license decision.

##🌈 Voting design questions

Before deployment, specify:

- Proposal creation thresholds and eligibility.
- Quorum and approval thresholds.
- Voting period and execution delay.
- Delegation and conflict-of-interest rules.
- Sybil resistance and contributor identity/eligibility.
- Emergency pause and recovery procedures.
- Treasury controls and spending limits.
- Upgradeability, admin powers, and contract ownership.
- Dispute resolution and appeals.
- How protected principles, especially the free-edition guarantee, are enforced.

A 49% allocation does not automatically define veto power or guarantee a particular outcome. Those effects depend on the voting thresholds and proposal rules. The final governance specification must model these outcomes explicitly.

##🌈 Separation of powers

Recommended conceptual separation:

1. **Contribution registry:** records reviewed contribution events and evidence.
2. **Reward distributor:** calculates and distributes the contributor allocation under approved rules.
3. **Governance token:** represents voting weight, if token-based voting is selected.
4. **Governor:** handles proposals, voting, timelocks, and execution.
5. **Treasury:** holds project funds and executes approved spending.

These components may eventually be smart contracts, but no chain, token standard, upgrade model, or deployment plan has been selected.

##🌈 Legal and operational review

Before accepting funds or issuing transferable governance tokens, obtain appropriate legal and tax advice for the jurisdictions and participants involved. Token design can create regulatory, tax, consumer-protection, and governance obligations.

The DAO should publish its rules, treasury movements, voting records, and conflict disclosures in an accessible format.
