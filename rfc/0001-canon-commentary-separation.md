# RFC 0001: Canon And Commentary Separation

Status: Draft  
RFC: 0001  
Layer: I-II  
Created: 2026-07-04  
Related:

- `canon/Constitution.md`
- `canon/Principles.md`
- `canon/Architecture.md`
- `canon/Governance.md`
- `EDITORIAL-STANDARDS.md`

## Summary

This RFC establishes the separation between canon and commentary as a governing rule of the Knowledge-book repository.

Canon defines stable identity.

Commentary supports living interpretation, research, examples, debates, implementation notes, and evolution.

## Problem

The Brill ecosystem needs to support both stability and movement.

If everything becomes canon, the system becomes rigid and difficult to revise. If nothing becomes canon, the system loses identity and authority.

The repository therefore needs a clear distinction between material that governs the system and material that explores, teaches, applies, or challenges it.

## Proposal

Adopt the following rule:

```text
Canon is stable, minimal, and slow to change.
Commentary is living, expansive, and allowed to evolve quickly.
```

Canon should live primarily in:

```text
canon/
```

Commentary may live in:

```text
books/
patterns/
cases/
rfc/
glossary/
diagrams/
site/
```

## Rationale

The separation protects two values at once:

- coherence
- evolution

Canon gives the ecosystem continuity.

Commentary gives it learning capacity.

The repository should make this separation visible through directory structure, document status, front matter, links, and review process.

## Affected Documents

- `README.md`
- `EDITORIAL-STANDARDS.md`
- all documents in `canon/`
- future book chapters
- future glossary entries
- future RFCs

## Alternatives Considered

One alternative is to treat every polished document as canonical.

This was rejected because polish is not the same as constitutional authority.

Another alternative is to avoid canon entirely and allow the repository to remain fully interpretive.

This was rejected because the Brill ecosystem requires stable identity, especially if it is meant to support books, specifications, educational material, AI systems, and living documentation.

## Migration Notes

Future documents should identify whether they are canon, commentary, RFC, pattern, case, glossary, or implementation material.

Existing documents should be reviewed over time and given explicit status labels.

## Decision

```text
Pending
```

