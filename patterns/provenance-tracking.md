# Pattern: Provenance Tracking

Status: Draft  
Layer: III - Implementation  
Type: Pattern  
Provenance: Editorial Phase II, derived from repository principles, editorial standards, and glossary work.  
Related:

- `../canon/Principles.md`
- `../EDITORIAL-STANDARDS.md`
- `../glossary/provenance.md`

## Problem

Knowledge loses trust when its origin and evolution become invisible.

Without provenance, future readers cannot tell whether an artifact came from a manuscript, a conversation, an RFC, a design decision, a prior version, or an external source.

## Context

The Brill ecosystem is meant to support long-term evolution.

That means documents will be rewritten, moved, expanded, deprecated, superseded, canonized, interpreted, and implemented in different media.

Provenance keeps those changes intelligible.

## Structure

Every substantial document should include a provenance statement.

The statement may be short, but it should answer at least one of these questions:

- Where did this artifact come from?
- What prior material does it derive from?
- What decision created it?
- What does it replace or refine?
- What conversation, RFC, manuscript, or implementation produced it?

Recommended field:

```text
Provenance:
```

For longer documents, add revision notes:

```text
## Revision Notes

0.1.0 - Initial draft.
```

## Canonical Relationship

This pattern implements:

- `../canon/Principles.md`: Principle 3, Provenance Builds Trust
- `../canon/Principles.md`: Principle 7, Version History Is Part Of Meaning

## Examples

Simple provenance:

```text
Provenance: Editorial Phase II, derived from repository principles and Chapter 1.
```

RFC provenance:

```text
Provenance: Proposed in RFC 0001 and accepted during Editorial Phase II review.
```

Migration provenance:

```text
Provenance: Migrated from manuscript notes into structured chapter format.
```

## Review Questions

- Can a future reader understand why this document exists?
- Does the provenance identify a source, decision, or phase?
- Does the document explain major changes?
- Would canonization require a stronger provenance note?

