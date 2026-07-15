# Public release model

## One source of truth

The I·V·O ecosystem uses a private canonical repository as its durable source of truth.

This public repository is downstream from that source. It must not independently invent or silently modify definitions, operator rules, prompt modules, naming conventions, visual parameters, or research-status claims.

```text
private canonical source
        ↓ approved extraction
public GitHub release
        ↓ distribution and citation
website · Zenodo · users · reviewers · pilots
```

## Why the repositories are separated

The private environment may contain:

- exploratory mutations;
- contradictory drafts;
- unpublished external correspondence;
- raw observations;
- commercial domain packs;
- sensitive or identifiable case material;
- abandoned experiments;
- internal release and licensing decisions.

Publishing that whole environment would confuse active truth with historical development and could expose material that was never intended for release.

The public repository therefore functions as a curated research object rather than a mirrored workshop.

## Release criteria

Material can move into this repository when it is:

1. traceable to a canonical source;
2. assigned a version or status;
3. checked for superseded terminology;
4. free of secrets and personal data;
5. accompanied by licensing and attribution information;
6. clear about whether it is stable, experimental, frozen, or archived;
7. consistent with the corresponding Zenodo and website statements.

## Public file statuses

Files should use one of these labels where relevant:

- **Stable** — recommended public version.
- **Frozen** — fixed for research comparison; not necessarily validated.
- **Experimental** — open for testing and likely to change.
- **Draft** — incomplete and not suitable for operational use.
- **Archived** — retained for provenance but superseded.

## Version changes

A public version change should include:

- the version identifier;
- a concise changelog;
- the reason for the change;
- whether previous results remain comparable;
- any migration or incompatibility note;
- updated citation metadata where required.

## Zenodo and GitHub

GitHub is the navigable, evolving release layer. Zenodo is the durable, citable archive layer.

A GitHub state should be archived to Zenodo when it represents a meaningful release that should remain independently retrievable and citeable. Minor wording changes do not necessarily require a new Zenodo version; methodological or canonical changes generally do.

## Website

The website explains relevance, applications, and routes to collaboration. It should link to GitHub for current public structure and to Zenodo for archival citation.

The website is not the canonical source of technical truth.
