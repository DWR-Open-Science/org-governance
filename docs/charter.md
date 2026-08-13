# Charter of the DWR Open Science GitHub Organization

**Status:** Draft — v0.1
**Last updated:** [08/13/2026]
**Maintained by:** [To be decided](https://github.com/DWR-Open-Science/org-governance/issues/2)

> This charter is a living document. It describes what the DWR Open Science GitHub organization is for, what belongs in it, and how it is run. It is directional rather than binding: it records the shared commitments of the people developing the organization today, and it is expected to change as the organization grows. See [Amending this Charter](#8-amending-this-charter).
>
> Open decisions are tracked as issues in this repository and recorded in the [Decision Log](#10-decision-log) once resolved.

---

## 1. Purpose

The DWR Open Science GitHub organization is being established as part of the 2026 work for DWR Strategic Plan Action 1.2.2, *Development of Open Science Guidance and Resources* (SP 1.2.2). It is one part of DWR's work to develop guidance and resources that strengthen the Department's ability to conduct open science: a shared home for resources that help staff develop, publish, and steward reproducible, open-source scientific analyses and software.

The organization aims to:

- **Make open-source practice actionable.** Provide practical standards, templates, guides, training, and examples that staff can apply in day-to-day work.
- **Strengthen reproducibility and accessibility.** Support scientific work that is understandable, reusable, and maintainable over time.
- **Support collaboration.** Make it easier for technical and non-technical staff to participate in open-science practice and for DWR to collaborate with others appropriately.
- **Build sustainable stewardship.** Promote clear ownership, maintenance, contribution, attribution, and support practices for shared resources.
- **Complement existing DWR work.** Support—not replace—the GitHub organizations and repositories already maintained by DWR programs and teams.

## 2. Guiding Principles

1. **Openness is applied responsibly.** Open-source practice does not mean that every project, dataset, or product should be public. Access and reuse must account for legal requirements, security, privacy, Tribal data and Indigenous data sovereignty, community-held knowledge, and other appropriate limits. Publication, access, and reuse decisions should be documented and revisited when circumstances change.
2. **Reproducibility and usability matter.** Open-source resources should be accompanied by the documentation, licensing, environment information, and development practices needed for others to understand and use them.
3. **Credit and labor are recognized.** Sustainable practice acknowledges the people who design, document, review, maintain, and support code, with clear pathways for contribution and attribution.
4. **Shared stewardship is part of the work.** Open-source resources should have defined governance, ownership, maintenance, and support expectations so that they remain trustworthy and useful over time.
5. **Accessibility and inclusion matter.** Norms, tools, and feedback processes should welcome staff with different technical backgrounds and should not require GitHub experience to participate in review.
6. **Build on what works.** The organization will use effective existing DWR and external resources where helpful rather than reinventing them.

## 3. Scope

### In scope

During the initial 2026 phase of SP 1.2.2, this organization is a shared home for resources that help DWR staff develop, publish, and steward reproducible, open-source scientific work. It includes:

- Governance, standards, and practical guidance for open-source scientific work at DWR
- Reusable repository templates, project scaffolding, and implementation guides
- Training, onboarding, demonstrations, and websites that support open-science practice
- Exemplar repositories that demonstrate recommended practices
- Tools and code that directly support these resources or the practice of open science at DWR, when they fit the organization’s purpose and can be maintained responsibly
- Small reference or example datasets required for an included resource to run

This organization complements, rather than replaces, GitHub organizations and repositories already maintained by DWR programs and teams.

### Out of scope

- Program- or team-specific scientific code, models, analyses, and data pipelines that are best owned and maintained by the responsible program or team
- Any material containing personally identifiable information (PII)
- Information requiring restricted access or community governance, including sensitive ecological information, Tribal data and Indigenous data sovereignty, and community-held knowledge
- Security-sensitive information, including detailed State Water Project facility, operational, or infrastructure data
- Confidential or privileged material not cleared for public release
- Large primary datasets, which belong in DWR's [designated data repositories](https://github.com/DWR-Open-Science/org-governance/issues/8) and should be referenced from here, not stored here

This organization is not the default destination for every DWR repository. Repositories that fall outside this scope belong in the DWR GitHub organization or other system best positioned to own, maintain, and support them. When scope is unclear, follow the [publication, access, and reuse decision process](https://github.com/DWR-Open-Science/org-governance/issues/9) or ask the organization owners before creating a repository.

## 4. Membership

Membership and permission pathways are being developed as part of the organization's governance. They will define appropriate access, contribution, and maintenance roles for DWR staff and, where appropriate, collaborators.

A code of conduct and reporting pathway will be established before external contribution pathways are opened.

Participation in the development and review of these resources is not limited to GitHub. Materials may be shared through accessible DWR communication channels, such as SharePoint, briefings, working-group meetings, and targeted review sessions, so that staff and managers can provide feedback without GitHub experience.

### Joining

Joining criteria and procedures are [to be decided](https://github.com/DWR-Open-Science/org-governance/issues/4) as part of the governance structure.

### Leaving

Departure, transition, and handoff procedures will be defined with the organization's maintenance and ownership structure. A [departure checklist](https://github.com/DWR-Open-Science/org-governance/issues/13) is an open governance item.

## 5. Roles

| Role | Who | Responsibilities |
|---|---|---|
| **Organization Owners** | [To be decided](https://github.com/DWR-Open-Science/org-governance/issues/2) | Administer the organization; create and archive repositories; manage membership and permissions; steward this charter |
| **Maintainers** | To be named per repository | Maintain resources; review and merge changes; keep documentation current; and support orderly handoff and continuity |
| **Members** | To be defined | Contribute to resources, review changes, and uphold this charter's principles |
| **Contributors** | To be defined | Contribute through the pathways established for each resource |

This is a proposed role model. The organization will define the final structure for ownership, maintenance, support, and permissions as part of its governance work.

## 6. Repository Expectations

Minimum standards for open-source scientific repositories are being defined as part of SP 1.2.2. The standards are expected to address licensing, documentation, reproducibility, maintenance, and project status, with testing, environment and dependency management, security, and review practices applied as appropriate to the resource.

Initial work will focus on a small set of reusable repository templates, task-oriented implementation guides, lightweight onboarding and training materials, and baseline security and risk guidance. More advanced materials—such as comprehensive testing guidance, CI/CD patterns, containerization, pipeline orchestration, expanded exemplar repositories, and detailed maintenance frameworks—will be developed in later phases as capacity allows.

The default license for organization repositories is [to be decided](https://github.com/DWR-Open-Science/org-governance/issues/3).

## 7. Relationship to DWR Policy

This charter operates within existing DWR and State of California policy, not replacing or superseding it. Participants remain subject to DWR information security, records management, data governance, and public communication requirements.

Two implications deserve emphasis, because they are easy to overlook:

- **Public repositories are public records.** This includes commit messages, issue threads, and code comments, not just the code itself. Write accordingly.
- **Publication is not reversible.** Content pushed to a public repository should be assumed to be permanently public, even if later deleted or access is restricted, because forks and mirrors persist. Review publication decisions carefully before release.

Where this charter and DWR policy appear to conflict, DWR policy governs, and the conflict should be raised with the organization owners or current stewards so this document can be corrected.

GitHub is the primary public development and hosting environment for these resources, but feedback and policy review may be gathered through accessible DWR communication channels. Designated maintainers will incorporate that input into the GitHub-hosted materials.

## 8. Amending this Charter

This charter is maintained in this repository and changes through the same process as any other work here: open an issue to propose a change, or open a pull request with the proposed language. Until the formal governance structure is adopted, proposed changes are reviewed by the SP 1.2.2 working group or designated maintainers.

Substantive changes (e.g., to purpose, scope, or membership) should be announced to the organization's members before adoption and given a reasonable comment period.

Every resolved decision is recorded in the [Decision Log](#10-decision-log) with a link to the issue where it was discussed, so that the reasoning behind the charter's current text remains recoverable.

As the organization matures, this charter is expected to become more specific and more binding. Its current form is intended to be a starting point that people can react to, not a finished framework.

## 9. Contact

Questions about this charter, the organization, or whether a project belongs here: [to be decided](https://github.com/DWR-Open-Science/org-governance/issues/5).

## 10. Decision Log

Below is a list of decisions that shaped this charter and those that are still open. Each links to the issue where the discussion happened. When an issue closes, replace the placeholder text in the relevant section with the decision, and update the row below.

| Section | Decision | Status | Issue | Resolved |
|---|---|---|---|---|
| [Roles](#5-roles) | Who holds organization owner permissions | Open | [#2](https://github.com/DWR-Open-Science/org-governance/issues/2) | — |
| [Repository Expectations](#6-repository-expectations) | Default license for organization repositories | Open | [#3](https://github.com/DWR-Open-Science/org-governance/issues/3) | — |
| [Membership](#4-membership) | How a DWR staff member joins the organization | Open | [#4](https://github.com/DWR-Open-Science/org-governance/issues/4) | — |
| [Contact](#9-contact) | Durable contact point for the organization | Open | [#5](https://github.com/DWR-Open-Science/org-governance/issues/5) | — |
| [Scope](#3-scope) | Repository creation and request process | Open | [#6](https://github.com/DWR-Open-Science/org-governance/issues/6) | — |
| [Repository Expectations](#6-repository-expectations) | Archiving and deprecation process | Open | [#7](https://github.com/DWR-Open-Science/org-governance/issues/7) | — |
| [Scope](#3-scope) | Designated homes for primary datasets | Open | [#8](https://github.com/DWR-Open-Science/org-governance/issues/8) | — |
| [Principles](#2-guiding-principles) | Process for publication, access, and reuse decisions | Open | [#9](https://github.com/DWR-Open-Science/org-governance/issues/9) | — |
| [Membership](#4-membership) | Code of conduct adoption | Open | [#10](https://github.com/DWR-Open-Science/org-governance/issues/10) | — |
| [Membership](#4-membership) | External collaborator pathways | Deferred | [#12](https://github.com/DWR-Open-Science/org-governance/issues/12) | — |
| [Membership](#4-membership) | Member departure checklist | Open | [#13](https://github.com/DWR-Open-Science/org-governance/issues/13) | — |
