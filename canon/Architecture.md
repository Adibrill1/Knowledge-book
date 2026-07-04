# Architecture

Status: Draft Canon  
Layer: II - Architecture  
Scope: Repository and knowledge-system architecture

## Purpose

The Architecture defines how the Brill ecosystem organizes knowledge into durable, navigable, and evolvable structures.

## Architectural Model

The repository is organized as a layered knowledge architecture:

```text
Layer I    Constitution
Layer II   Architecture
Layer III  Implementation
Layer IV   Examples
```

Each layer has a different rate of change and a different responsibility.

## Layer I: Constitution

Constitutional documents define enduring commitments.

They should be concise, stable, and rarely amended.

Primary location:

```text
canon/
```

## Layer II: Architecture

Architectural documents define how the system is organized.

They describe structures, relationships, symbolic language, editorial models, governance mechanisms, and publication logic.

Primary locations:

```text
canon/
diagrams/
glossary/
```

## Layer III: Implementation

Implementation documents and systems turn the architecture into working artifacts.

They include templates, site code, metadata conventions, workflows, and publication standards.

Primary locations:

```text
site/
patterns/
rfc/
books/
```

## Layer IV: Examples

Examples demonstrate how the system works in context.

They include cases, applied patterns, educational material, diagrams, chapter commentary, and implementation notes.

Primary locations:

```text
cases/
patterns/
books/
assets/
```

## Repository As System

The repository should make the following properties visible:

- identity
- status
- provenance
- relationships
- version history
- evolution

These properties may be expressed through front matter, directory structure, links, diagrams, RFCs, or site behavior.

## Change Flow

New ideas should normally move through this path:

```text
note or draft -> commentary -> pattern/case/RFC -> reviewed proposal -> canon
```

Canonization should be deliberate, not automatic.

