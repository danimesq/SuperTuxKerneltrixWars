#🌈 Contribution and Reward Model

##🌈 Current proposal

The project proposes rewarding contributors with governance tokens in proportion to the amount of accepted work they bring to the project. The initial idea specifically emphasizes **lines of code contributed**.

The intended contributor pool is 51% of the governance-token allocation. Gamlr's separate 49% allocation is described in [Governance](GOVERNANCE.md).

This document does not promise tokens. Rewards must not begin until the DAO has approved a complete policy, the relevant contracts or distribution process have been reviewed, and eligibility and appeal procedures are public.

##🌈 Why raw line count is not enough

Raw lines of code (LOC) are easy to count but do not reliably measure value. They can reward unnecessary verbosity, duplicated code, generated boilerplate, or changes that increase maintenance costs. A small security fix or a careful deletion can be more valuable than thousands of new lines.

The project should preserve LOC as a visible input to the proposed model while preventing it from becoming the sole determinant of rewards.

##🌈 Proposed contribution pipeline

1. Contributor submits a pull request or another traceable contribution.
2. Maintainers review correctness, tests, maintainability, security, scope, and licensing.
3. Accepted work is categorized and recorded with its evidence.
4. The contribution registry calculates a provisional score using the published policy.
5. The contributor can inspect the calculation and appeal it.
6. Approved scores are included in a transparent reward epoch.
7. Distribution is executed only after the required governance approval.

##🌈 Inputs to evaluate

Potential inputs requiring policy decisions:

- Accepted added LOC.
- Meaningful deletions and refactors.
- Tests and test coverage improvements.
- Bug fixes and security work.
- Documentation, design, accessibility, localization, and release engineering.
- Asset creation and asset integration.
- Review, mentoring, triage, and maintenance.
- Reproducibility and long-term maintenance impact.

The policy must specify whether non-code work receives an equivalent score, a separate allocation, or another form of recognition.

##🌈 AI-assisted contributions

AI-generated code is eligible for review under the same standards as human-written code. The contributor remains responsible for understanding, testing, licensing, and maintaining the submitted work.

The reward system should not pay simply for raw generated output. It should count only accepted contributions and should include checks for duplication, low-value churn, generated vendored files, formatting-only changes, and other forms of metric gaming.

##🌈 Measurement safeguards

Before choosing a formula, test it against sample histories:

- A large feature implementation.
- A small but critical bug fix.
- A refactor that removes substantial code.
- A test suite or documentation contribution.
- An AI-generated change that requires substantial correction.
- A large duplicated or mechanically generated change.
- A long-running maintenance contribution.

Publish examples showing how each case is scored. Keep the calculation reproducible from version-control history and review records.

##🌈 Open questions

- What counts as a line: added, changed, deleted, or net LOC?
- How are merges, rebases, squashes, and cherry-picks attributed?
- How are shared contributions split?
- How are generated files, vendored dependencies, and code formatting treated?
- What is the reward epoch and total emission schedule?
- Is the contributor pool capped or replenished?
- Can tokens be transferred, delegated, or vested?
- What happens when accepted work is later reverted?
- Who reviews appeals, and how are reviewer conflicts handled?
- How are non-code contributions represented fairly?

No reward formula should be implemented until these questions have clear, published answers.
