# Contributing to the BNL Genesis Mission Portfolio

The **BNL Genesis Mission Portfolio** publishes public project descriptions.
Portfolio content is prepared, reviewed, and approved in a controlled workflow
before it is published.

## Portfolio Repositories

The Portfolio uses two repositories:

- [`portfolio-docs`](https://github.com/BNL-Genesis/portfolio-docs) — the
  **controlled source repository** for Portfolio content. Project teams and
  authorized contributors propose new project descriptions and updates here
  through pull requests, which go through review and approval before
  publication.

- [`bnl-genesis.github.io`](https://github.com/BNL-Genesis/bnl-genesis.github.io)
  — the **public repository of the Portfolio website**. Approved content is
  published here by an automated workflow. **Do not submit project-content
  pull requests directly to this repository.**

## Portfolio Content Flow

```text
Project Team / Contributor
          │
          ▼
    portfolio-docs
  (controlled source)
          │
          ▼
     Pull Request
          │
          ▼
  Review and Approval
          │
          ▼
        Merge
          │
          ▼
 Automated Publication
          │
          ▼
 bnl-genesis.github.io
  (public Portfolio)
```

A proposed change does not modify the public website until its pull request in
`portfolio-docs` has been reviewed, approved, and merged.

## Ways to Contribute

### Option A — Contribute through GitHub

This is the preferred workflow for project teams that expect to maintain their
Portfolio project information directly. It requires:

1. GitHub account;
2. BNL GitHub Enterprise license (see
   [Obtaining BNL GitHub Enterprise Access](bnl-github-enterprise-access.md));
3. membership in the `BNL-Genesis` organization and access to
   `portfolio-docs` (see
   [BNL-Genesis GitHub Workspace](bnl-genesis-workspace.md)).

Once you have access, follow the contribution workflow documented in
`portfolio-docs`.

### Option B — Submit Content to the BNL Genesis Mission Team

You do **not** need GitHub access to have a project represented in the Portfolio. Download and fill in the [project content template](https://github.com/BNL-Genesis/bnl-genesis.github.io/blob/main/docs/portfolio/_project_template.md), then send it to [@mikhail](https://www.bnl.gov/staff/mtitov).

A member of the team will prepare the corresponding change in `portfolio-docs`
on your behalf. It then goes through the same review and approval process as
changes submitted directly through GitHub.
