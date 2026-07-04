# Pattern: Document Identity

Status: Draft  
Layer: III - Implementation  
Type: Pattern  
Provenance: Editorial Phase II, derived from repository principles and Chapter 1.  
Related:

- `../canon/Principles.md`
- `../EDITORIAL-STANDARDS.md`
- `../glossary/identity.md`

## Problem

Knowledge artifacts need to evolve without losing their identity.

Without stable identity, readers and systems cannot reliably tell whether a document is the same artifact, a revision, a replacement, a fork, or a different kind of material.

## Context

Knowledge-book contains many kinds of artifacts:

- canon
- chapters
- glossary entries
- RFCs
- patterns
- cases
- diagrams
- site content

The same idea may appear in several forms. Each form needs enough identity to be referenced, revised, related, and trusted.

## Structure

A document identity should include:

- stable path
- clear title
- document type
- status
- layer
- provenance
- related documents
- revision notes when appropriate

Recommended opening block:

```text
# Title

Status:
Layer:
Type:
Version:
Provenance:
Related:
```

## Canonical Relationship

This pattern implements:

- `../canon/Principles.md`: Principle 1, Knowledge Has Identity
- `../canon/Principles.md`: Principle 7, Version History Is Part Of Meaning

## Examples

Good document identity:

```text
glossary/provenance.md
Status: Draft
Type: Glossary Entry
Provenance: Editorial Phase II, derived from repository principles and editorial standards.
Related: ../canon/Principles.md, ../EDITORIAL-STANDARDS.md
```

Weak document identity:

```text
notes.md
```

The weak example may contain valuable writing, but it does not yet tell the system what it is.

## Review Questions

- Can the document be referenced by path?
- Does the title match the purpose?
- Is the document type clear?
- Is the current status clear?
- Is provenance visible?
- Are important relationships named?

