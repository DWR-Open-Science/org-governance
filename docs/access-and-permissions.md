# Access and Permissions

**Status:** Draft — current organization configuration  
**Last reviewed:** 08/20/2026

This document explains how the DWR Open Science GitHub organization implements its access and decision-making model. It supplements the [organization charter](charter.md); it does not replace DWR or State of California policy.

## Purpose and principle

The organization is intended to be self-organizing for ordinary work while retaining a clear boundary around sensitive and destructive administrative actions:

> Creation and collaboration are decentralized; exposure and destruction are centrally controlled.

Members can start and organize work. Teams are the normal way to grant repository access. Organization owners retain authority over actions that can expose, remove, transfer, or materially affect organizational assets.

## How repository access is granted

The organization’s base repository permission is **No permission**. Becoming an organization member does not automatically grant access to private repositories or write access to public repositories.

Repository access must be granted explicitly, preferably through a team. Direct per-person access is an exception and should be used only when a team is not a practical fit.

| Repository type | Normal access pattern |
|---|---|
| Shared public repository | `Contributors` team → `Write`, where direct member contribution is appropriate |
| Project or functional repository | Project or functional team → the least privileged role needed |
| Private repository | Project or functional team → explicit `Read`, `Write`, `Maintain`, or `Admin` access |
| Individual exception | Direct access → documented reason and periodic review |

Public repositories are visible and forkable by everyone, and anyone can submit a pull request from a fork back to a repository. Private repositories are visible only to the people and teams explicitly granted access. Forking private repositories is disabled.

## Roles and decision rights

| Role | Responsibilities and boundaries |
|---|---|
| **Organization owners** | Administer organization-wide membership, policy, and settings; control repository visibility changes, deletion, transfer, and issue deletion; steward this governance. Keep this group small. |
| **Teams** | Represent shared project or functional access boundaries. They are the default mechanism for access management and may be created by members. |
| **Repository maintainers** | Maintain their repositories; review and merge changes; keep repository documentation current; arrange orderly handoff and continuity. |
| **Repository administrators** | Administer only the repositories for which they have been intentionally granted Admin. They may install eligible GitHub Apps and rename branches protected by organization rules, subject to GitHub restrictions. They cannot change visibility, delete or transfer repositories, or delete issues. |
| **Members** | May create public and private repositories, create teams, organize project work, and administer repositories when explicitly granted the relevant role. |
| **Outside collaborators** | Cannot create organization repositories, teams, or organization app-access requests. Their invitation and access pathway is still to be defined. |

## Team conventions

- Use teams, rather than direct individual grants, whenever practical.
- Give teams descriptive names and a clear project or functional purpose.
- A person may belong to more than one team.
- Grant the least privileged repository role that enables the work. In particular, grant `Admin` only when repository settings access is needed.
- The `Contributors` team is the broad member group for selected shared public repositories; it does not control who may create repositories.

## New repository access checklist

When creating a repository, the creator and its intended maintainers should:

1. Confirm that the repository belongs in this organization and decide whether it should be public or private.
2. Identify the team responsible for the repository and its maintenance.
3. Grant that team the appropriate repository role.
4. Name repository maintainers and document ownership and handoff expectations.
5. Use direct individual access only when necessary, and record why it is an exception.

Because base permissions are `No permission`, new repositories do not automatically become writable by all organization members.

## Related organization settings

The following settings support this model:

- Members may create public and private repositories, public GitHub Pages sites, and teams.
- Users with `Read` access may create repository Discussions.
- GitHub Projects have an organization-wide base permission of `Read`; edit access is granted where needed.
- Organization app access requests are limited to members.
- Repository administrators may install GitHub Apps only when the app does not request broader organization or repository-administration permissions.
- Only organization owners may change repository visibility, delete or transfer repositories, or delete issues.

## Membership and collaborator requests

This document describes the permissions model, not an intake process. The organization does not yet have a designated point of contact, request process, or joining criteria for new members or outside collaborators. Those pathways remain to be decided under the charter’s membership governance work.

Until that work is complete, this document should not be read as an invitation pathway or authorization to add members or collaborators.

## Review and changes

GitHub’s live organization settings are the technical source of truth. This document records the intended governance model and should be reviewed whenever a material organization setting changes, and periodically as governance matures.

Propose changes through an issue or pull request in this repository, following the charter’s [amendment process](charter.md#8-amending-this-charter). Changes to DWR or State policy supersede this document.
