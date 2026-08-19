# Public release model

## Released artifacts and sources of truth

The I·V·O ecosystem maintains distinct, explicitly versioned artifacts. Internal/private kernels and public Lens Prompt releases are different version lines and must not be renumbered or presented as competing copies of one artifact.

For the public prompt line, the frozen prompt file identified in the release manifest is the source of truth for that release. This repository must not independently invent or silently modify definitions, operator rules, prompt modules, naming conventions, or research-status claims after release.

```text
approved frozen public prompt
        ↓ checked release commit
public GitHub release and tag
        ↓ distribution and citation
website · Zenodo · users · reviewers · pilots
```

## Why internal and public artifacts are separated

An internal environment may contain:

- exploratory mutations;
- contradictory drafts;
- unpublished external correspondence;
- raw observations;
- commercial domain packs;
- sensitive or identifiable case material;
- abandoned experiments;
- internal release and licensing decisions.

Publishing that whole environment would confuse active truth with historical development and could expose material that was never intended for release.

The public repository therefore functions as a curated research object rather than a mirrored workshop. An internal kernel version such as v2.0.0 does not compete with or determine the public prompt version number v4.0; each artifact follows its own declared governance and lineage.

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

The website explains relevance, applications, and routes to collaboration:

- `https://design-by-authenticity.com/ivo-lens` is the accessible public introduction and download page.
- `https://design-by-authenticity.com/ivo-lens-canonical` is the readable web representation of the current canonical prompt.
- GitHub is the source, versioning, provenance, and research layer.
- Zenodo is the permanent release archive and DOI layer.

The website representation must remain traceable to the exact GitHub canonical artifact and checksum; it does not replace that release artifact as the technical source of truth.
