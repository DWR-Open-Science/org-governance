<!--
  ANCHOR CONVENTION — please read before editing headings.

  Each section carries an explicit <a id="..."></a> anchor so that links from
  issues and other documents survive renumbering or rewording of headings.

  When linking to a section, GitHub prefixes custom IDs with "user-content-".
  So the anchor <a id="roles"></a> is linked as:
      README.md#user-content-roles

  Do not remove these anchors. If you add a section, add an anchor with it.
-->

# Charter of the DWR Open Science GitHub Organization

**Status:** Draft — v0.1
**Last updated:** [07/30/2026]
**Maintained by:** [To be decided](https://github.com/DWR-Open-Science/org-governance/issues/2)

> This charter is a living document. It describes what the DWR Open Science GitHub organization is for, what belongs in it, and how it is run. It is directional rather than binding: it records the shared commitments of the people participating in the organization today, and it is expected to change as the organization grows. See [Amending this Charter](#user-content-amendments).
>
> Open decisions are tracked as issues in this repository and recorded in the [Decision Log](#user-content-decision-log) once resolved.

---

<a id="purpose"></a>

## 1. Purpose

The California Department of Water Resources (DWR) produces a large volume of scientific and technical work; models, analyses, data-processing pipelines, and the documentation that surrounds them. Much of this work has historically lived on individual workstations, in shared drives, or in personal accounts, where it is difficult to find, difficult to reproduce, and difficult to hand off.

The DWR Open Science GitHub organization exists to give that work a durable, shared, and public home. Specifically, it aims to:

- **Make DWR science reproducible.** Analyses and models should be traceable from raw input to published result.
- **Make DWR science findable and reusable.** Work products should be discoverable by other DWR programs, partner agencies, and the public.
- **Reduce single-person dependency.** Code that supports Department decisions should not be recoverable only from one person's laptop.
- **Support collaboration.** Provide a common ground for working with academic institutions, sister agencies, consultants, and the broader water-science community.
- **Advance open government.** Support DWR's commitments under the Open and Transparent Water Data Act (AB 1755) and the State's broader open-data direction.

<a id="principles"></a>

## 2. Guiding Principles

1. **Open by default.** Repositories are public unless there is a specific reason they should not be. Where a repository must start private, the reason is recorded and revisited.
2. **Reproducibility over polish.** A rough but runnable analysis is more valuable than a tidy one nobody can execute.
3. **Credit is given.** Contributors are named. Code and data are citable products of DWR science.
4. **Documentation is part of the work.** A repository without a README is unfinished.
5. **Sensitive information stays out.** Openness never overrides DWR's obligations to protect personal, confidential, or security-sensitive information.
6. **Low barrier to entry.** Participants come from a wide range of technical backgrounds. Norms and tooling should welcome newcomers rather than filter them out.

<a id="scope"></a>

## 3. Scope

### In scope

- Scientific and technical analysis code (R, Python, MATLAB, and similar)
- Models, model configurations, and model post-processing tools
- Data-processing, QA/QC, and ETL pipelines for DWR scientific data
- Reproducible reports, notebooks, and analysis products
- Documentation, training material, and templates supporting the above
- Small reference or example datasets required for code to run

### Out of scope

- Any material containing personally identifiable information (PII)
- Security-sensitive information, including detailed State Water Project facility, operational, or infrastructure data
- Confidential, privileged, or pre-decisional material not cleared for public release
- Large primary datasets, which belong in DWR's [designated data repositories](https://github.com/DWR-Open-Science/org-governance/issues/8) and should be referenced from here, not stored here

Repositories that fall outside this scope belong elsewhere in the DWR GitHub enterprise or in DWR's other systems. When scope is unclear, ask the organization owners before creating the repository.

<a id="membership"></a>

## 4. Membership

**Today:** membership is open to DWR staff whose work involves scientific or technical code, and to those directly supporting that work.

**Going forward:** the organization intends to extend participation to external collaborators: academic partners, sister agencies, contractors, and community contributors working with DWR. [Membership pathways for those groups](https://github.com/DWR-Open-Science/org-governance/issues/12) will be defined as the need arises and added to this charter.

Note that anyone may already contribute to public repositories in this organization by opening issues and pull requests. Formal membership governs permissions within the organization, not the ability to participate in its work.

### Joining

[To be decided](https://github.com/DWR-Open-Science/org-governance/issues/4)

### Leaving

Membership ends when a participant leaves DWR or their role no longer involves the organization's work. Before departure, members are responsible for ensuring that repositories they maintain have another named maintainer and that no work of ongoing value exists only in a personal account. A [departure checklist](https://github.com/DWR-Open-Science/org-governance/issues/13) supports this.

<a id="roles"></a>

## 5. Roles

| Role | Who | Responsibilities |
|---|---|---|
| **Organization Owners** | [To be decided](https://github.com/DWR-Open-Science/org-governance/issues/2) | Administer the organization; create and archive repositories; manage membership and permissions; steward this charter |
| **Maintainers** | Named per repository | Own a repository's direction and quality; review and merge changes; keep documentation current; ensure a successor is identified |
| **Members** | DWR staff in the organization | Contribute code, review changes, open issues, uphold the principles in this charter |
| **Contributors** | Anyone | Open issues and pull requests on public repositories |

Every repository should have at least two people with maintainer access. This is the organization's main safeguard against orphaned work.

<a id="repository-expectations"></a>

## 6. Repository Expectations

Each repository in the organization should include, at minimum:

- A `README.md` describing what the repository does, who maintains it, and how to run it
- A `LICENSE` file — the organization default is [to be decided](https://github.com/DWR-Open-Science/org-governance/issues/3)
- A clear statement of its status: active, maintained, or archived

Detailed conventions branching, commit style, review practice, testing, environment management; are deliberately not specified here. They belong in `CONTRIBUTING.md` and in the organization's repository templates, which can evolve without amending this charter.

<a id="dwr-policy"></a>

## 7. Relationship to DWR Policy

This charter operates within existing DWR and State of California policy, it does not replace or supersede it. Participants remain subject to DWR information security, records management, data governance, and public communication requirements.

Two implications deserve emphasis, because they are easy to overlook:

- **Public repositories are public records.** This includes commit messages, issue threads, and code comments — not just the code itself. Write accordingly.
- **Publication is not reversible.** Content pushed to a public repository should be assumed to be permanently public, even if later deleted, because forks and mirrors persist.

Where this charter and DWR policy appear to conflict, DWR policy governs, and the conflict should be raised with the organization owners so this document can be corrected.

<a id="amendments"></a>

## 8. Amending this Charter

This charter is maintained in this repository and changes through the same process as any other work here: open an issue to propose a change, or open a pull request with the proposed language. Organization owners review proposed changes and adopt them by consensus.

Substantive changes — to purpose, scope, or membership — should be announced to the organization's members before adoption and given a reasonable comment period.

Every resolved decision is recorded in the [Decision Log](#user-content-decision-log) with a link to the issue where it was discussed, so that the reasoning behind the charter's current text remains recoverable.

As the organization matures, this charter is expected to become more specific and more binding. Its current form is intended to be a starting point that people can react to, not a finished framework.

<a id="contact"></a>

## 9. Contact

Questions about this charter, the organization, or whether a project belongs here: [to be decided](https://github.com/DWR-Open-Science/org-governance/issues/5).

<a id="decision-log"></a>

## 10. Decision Log

Decisions that shaped this charter, and those still open. Each links to the issue where the discussion happened. When an issue closes, replace the placeholder text in the relevant section with the decision, and update the row below.

| Section | Decision | Status | Issue | Resolved |
|---|---|---|---|---|
| [Roles](#user-content-roles) | Who holds organization owner permissions | Open | [#2](https://github.com/DWR-Open-Science/org-governance/issues/2) | — |
| [Repository Expectations](#user-content-repository-expectations) | Default license for organization repositories | Open | [#3](https://github.com/DWR-Open-Science/org-governance/issues/3) | — |
| [Membership](#user-content-membership) | How a DWR staff member joins the organization | Open | [#4](https://github.com/DWR-Open-Science/org-governance/issues/4) | — |
| [Contact](#user-content-contact) | Durable contact point for the organization | Open | [#5](https://github.com/DWR-Open-Science/org-governance/issues/5) | — |
| [Scope](#user-content-scope) | Repository creation and request process | Open | [#6](https://github.com/DWR-Open-Science/org-governance/issues/6) | — |
| [Repository Expectations](#user-content-repository-expectations) | Archiving and deprecation process | Open | [#7](https://github.com/DWR-Open-Science/org-governance/issues/7) | — |
| [Scope](#user-content-scope) | Designated homes for primary datasets | Open | [#8](https://github.com/DWR-Open-Science/org-governance/issues/8) | — |
| [Principles](#user-content-principles) | Private repository exception process | Open | [#9](https://github.com/DWR-Open-Science/org-governance/issues/9) | — |
| [Membership](#user-content-membership) | Code of conduct adoption | Open | [#10](https://github.com/DWR-Open-Science/org-governance/issues/10) | — |
| [Membership](#user-content-membership) | External collaborator pathways | Deferred | [#12](https://github.com/DWR-Open-Science/org-governance/issues/12) | — |
| [Membership](#user-content-membership) | Member departure checklist | Open | [#13](https://github.com/DWR-Open-Science/org-governance/issues/13) | — |