# Editorial Standards

Status: Draft  
Layer: III - Implementation  
Scope: Writing, review, publication, and maintenance

## Purpose

These standards define how material should be written, reviewed, linked, and maintained inside Knowledge-book.

## Document Front Matter

Every substantial document should begin with a short metadata block in plain text or YAML.

Recommended fields:

```yaml
title:
status:
layer:
type:
version:
created:
updated:
provenance:
related:
```

## Status

Use clear status labels:

```text
Draft
Review
Stable
Canonical
Deprecated
Superseded
```

## Provenance

Provenance should explain the origin of a document or concept.

It may include:

- source manuscript
- originating conversation
- prior document
- RFC
- contributor
- date

## Relationships

Documents should link to related material when the relationship helps interpretation.

Common relationship types:

- depends on
- expands
- refines
- contradicts
- implements
- illustrates
- supersedes

## Canon Rules

Canon should be:

- short
- stable
- carefully reviewed
- minimally interpretive
- linked to living commentary where more explanation is needed

## Commentary Rules

Commentary may be:

- exploratory
- example-rich
- provisional
- research-driven
- updated frequently

Commentary should still remain traceable to the canon it interprets.

## Chapter Rules

Each chapter should be an independent Markdown document.

Chapters should include:

- title
- editorial status
- abstract
- relationship to canon
- chapter body
- key concepts
- related documents
- revision notes

## Review Checklist

Before publication, check whether the document:

- has a clear purpose
- identifies its status
- preserves provenance
- links related concepts
- avoids unnecessary canon expansion
- uses consistent terms
- can be read independently

