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

## Membership Responsibilities and Requirements

### Member

Members are active contributors who can be assigned issues and are expected to remain engaged in the project. Members are given the [Triage GitHub role](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-repository-roles/repository-roles-for-an-organization#repository-access-for-each-permission-level) to requested ksctl repositories, in order to facilitate issue management and moderate discussions.

#### Requirements:

- Two-factor authentication enabled on GitHub.
- Multiple contributions, including code, documentation, or participation in discussions.
- Sponsored by an existing reviewers or maintainers.

#### Responsibilities:

- Moderate GitHub discussions and triage issues.
- Respond to issues and PRs assigned to them.
- Review and contribute to discussions actively.

#### Nomination Process:

To become a member:

1. Open an issue in the `ksctl/community` repository.
2. Ensure your sponsors are `@mentioned` in the issue.
3. Include a list of your contributions that represent your work in the project.
4. Your sponsors must confirm their support by commenting with +1 on the issue.
5. Once the sponsors have responded, the request will be reviewed by project leads. Any missing information will be requested.

### Maintainer

Maintainers are experienced contributors who drive the technical direction of the project and ensure its health and sustainability.

#### Requirements:

- Sustained contributions to the project over time (code, design, or community leadership).
- Demonstrated technical expertise and sound judgment in project discussions.
- Nominated and approved by existing maintainers.

#### Responsibilities:

- Review and merge PRs to maintain project quality.
- Set the technical direction and roadmap for the project.
- Mentor and guide members.
- Participate in governance decisions and resolve conflicts.
- Ensure transparency by documenting decisions publicly.

#### Nomination Process:

To become a maintainer:

1. Open an issue in the `ksctl/community` repository.
2. Ensure your sponsors are `@mentioned` in the issue.
3. Include a summary of your contributions and their impact on the project.
4. Your sponsors must confirm their support by commenting with +1 on the issue.
5. Once the sponsors have responded, the request will be reviewed by project leads. Any missing information will be requested.

## Adding maintainers

Maintainers are first and foremost contributors that have shown they are
committed to the long term success of a project. Contributors wanting to become
maintainers are expected to be deeply involved in contributing code, pull
request review, and triage of issues in the project for more than three months.

Just contributing does not make you a maintainer, it is about building trust
with the current maintainers of the project and being a person that they can
depend on and trust to make decisions in the best interest of the project.

Periodically, the existing maintainers curate a list of contributors that have
shown regular activity on the project over the prior months. From this list,
candidates are selected and proposed as maintainers.

After a candidate has been proposed as maintainer via a Pull Request by any of the existing maintainers, the other maintainers are given five business days to discuss the candidate, raise objections and cast their vote. The Votes take place via the pull request comment. Candidates must be approved by at least 66% of the current maintainers by adding their vote on the PR. Only maintainers of the repository that the candidate is proposed for are allowed to vote. The candidate becomes a maintainer once the pull request is merged.

## Membership Management

### Inactive Members

Members with no significant contributions for 12 months may be removed from the GitHub organization. Reinstatement requires going through the membership process again.

### Removal of inactive maintainers

Similar to the procedure for adding new maintainers, existing maintainers can
be removed from the list if they do not show significant activity on the
project. Periodically, the maintainers review the list of maintainers and their
activity over the last three months.

If a maintainer has shown insufficient activity over this period, a neutral
person will contact the maintainer to ask if they want to continue being
a maintainer. If the maintainer decides to step down as a maintainer, they
open a pull request to be removed from the MAINTAINERS file.


### Stepping down policy

Life priorities, interests, and passions can change. If you're a maintainer but
feel you must remove yourself from the list, inform other maintainers that you
intend to step down, and if possible, help find someone to pick up your work.
At the very least, ensure your work can be continued where you left off.

After you've informed other maintainers, create a pull request to remove
yourself from the MAINTAINERS file.


### Changes in Membership Roles
Role changes are discussed by project leads and approvers and finalized through consensus.


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

