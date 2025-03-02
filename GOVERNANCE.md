### ksctl Governance

## Overview

**ksctl** is committed to building an open, inclusive, productive and self-governing open source community focused on building a high-quality Developmer-Friendly Kubernetes environment. The community is governed by this document with the goal of defining how community should work together to achieve this goal.

## Code Repositories

The following code repositories are governed by ksctl community and maintained under the `ksctl` namespace.

* **[community](https://github.com/ksctl/community):** Used to store community-related material–e.g., proposals, presentation slides, governance documents, community meeting minutes, etc.

## Community Roles

### Maintainers
- Maintainers have write access to the ksctl organization.
- They review and merge pull requests, resolve issues, and guide the project roadmap.
- Maintainers are responsible for upholding the project's quality, security, and sustainability.

### Contributors
- Anyone who contributes to ksctl through code, documentation, or discussions is considered a contributor.
- Contributors may be nominated to become maintainers based on consistent and high-quality contributions.

### Technical Steering Committee (TSC)
- The TSC consists of core maintainers who oversee the project's technical direction.
- They make final decisions on architectural changes, security policies, and long-term goals.
- TSC members are selected based on their expertise and contributions.


> [!IMPORTANT]
> **New maintainers** must be nominated by existing maintainers via a PR 
> and must be elected by 2/3 of existing maintainers. Likewise, maintainers
> can be removed by 2/3 of the existing maintainers or can resign by notifying one of the maintainers.
> 
> Voting on decisions can happen on the mailing list, **GitHub**, **Discord**, **email**, 
> or via a voting service, when appropriate. Maintainers can either 
> vote "agree, yes, +1", "disagree, no, -1", or "abstain". 
> A vote passes when supermajority is met. An abstain vote equals not voting at all.


## Decision-Making Process

### Technical Decisions
- Most decisions are made through discussions in GitHub Issues, Pull Requests, and community meetings.
- If consensus is not reached, maintainers vote, with a simple majority deciding the outcome.
- Major technical changes require approval from the TSC.

### New Features & Roadmap
- The community can propose new features via GitHub Discussions or RFCs.
- The TSC reviews proposals and prioritizes them based on project needs.
- Roadmap updates are shared publicly for transparency.

### Dispute Resolution
- In case of disagreements, a neutral vote among maintainers will be held.
- If a dispute remains unresolved, the TSC has the final authority.

## Proposal Process

Proposals should cover the high-level objectives, use cases, and technical
recommendations on how to implement. In general, the community member(s)
interested in implementing the proposal should be either deeply engaged in the
proposal process or be an author of the proposal.

**Lifecycle**

The proposal Issue/PR can be marked with different status labels to represent the
status of the proposal:

* **New**: Proposal is just created.
* **Reviewing**: Proposal is under review and discussion.
* **Accepted**: Proposal is reviewed and accepted (either by consensus or vote).
* **Rejected**: Proposal is reviewed and rejected (either by consensus or vote).

## Lazy Consensus

To maintain velocity in a project as busy as ksctl, the concept of [Lazy
Consensus](https://www.apache.org/foundation/glossary.html#LazyConsensus) is practiced. Ideas
and / or proposals should be shared by maintainers via
GitHub with the appropriate maintainer groups tagged. Out of respect for other contributors,
major changes should also be accompanied by a ping on Discord or a note on the
ksctl mailing list as appropriate. Author(s) of proposal, Pull Requests,
issues, etc.  will give a time period of no less than five (5) working days for
comment and remain cognizant of popular observed world holidays.

Other maintainers may chime in and request additional time for review, but
should remain cognizant of blocking progress and abstain from delaying
progress unless absolutely needed. The expectation is that blocking progress
is accompanied by a guarantee to review and respond to the relevant action(s)
(proposals, PRs, issues, etc.) in short order.

Lazy Consensus is practiced for all projects in the `ksctl` org, including
the main project repository, community-driven sub-projects, and the community
repo that includes proposals and governing documents.

Lazy consensus does _not_ apply to the process of:

* Removal of maintainers from ksctl

## Updating Governance

All substantive changes in Governance require a supermajority agreement by all maintainers.

