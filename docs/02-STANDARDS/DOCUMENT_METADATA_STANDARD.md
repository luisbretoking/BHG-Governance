---
title: Document Metadata Standard

document_id: DOCUMENT_METADATA_STANDARD

version: 1.2.0

status: Approved

document_type: Standard

governance_level: Enterprise

owner: BHG Governance Council

approval_authority: BHG Governance Council

created: 2026-07-20

last_updated: 2026-07-22

effective_date: 2026-07-22

classification: Internal

language: en

repository: BHG-GOVERNANCE

governed_by:
  - BHG_CONSTITUTION.md
  - GOVERNANCE_MODEL.md
  - DOCUMENT_POLICY.md
  - VERSIONING_POLICY.md
  - DOCUMENT_STANDARD.md
  - DOCUMENT_SCHEMA_STANDARD.md
  - DOCUMENT_VALIDATION_STANDARD.md

governs:
  - DOCUMENT_IDENTIFIER_STANDARD.md
  - DOCUMENT_RELATIONSHIP_STANDARD.md
  - DOCUMENT_CLASSIFICATION_STANDARD.md
  - DOCUMENT_HISTORY_MODEL.md
  - DOCUMENT_TEMPLATE_ENGINE_STANDARD.md
  - DOCUMENT_COMPILER_STANDARD.md
  - DOCUMENT_LINTING_STANDARD.md
  - DOCUMENT_AUTOMATION_STANDARD.md
  - BASELINE_REGISTRY.md
  - GENESIS_VALIDATION_ENGINE.md
  - All Governance Documents

depends_on:
  - DOCUMENT_STANDARD.md
  - DOCUMENT_SCHEMA_STANDARD.md
  - DOCUMENT_VALIDATION_STANDARD.md

related_to:
  - DOCUMENT_RENDERING_STANDARD.md
  - TRACEABILITY_STANDARD.md
  - REPOSITORY_STANDARD.md
  - NAMING_STANDARD.md
---

# Document Metadata Standard

> Defines the canonical metadata contract for every governance document within the Breto's Holding Group ecosystem.

---

# Purpose

This standard establishes the official metadata architecture required by every governance document within the Breto's Holding Group ecosystem.

Metadata represents the permanent structural identity of institutional knowledge.

Before any document can be governed, validated, audited, versioned, indexed or processed by Artificial Intelligence systems, it shall expose a complete and deterministic metadata contract.

The objective of this standard is to guarantee that every governance artifact is:

- uniquely identifiable;
- machine-readable;
- human-readable;
- traceable;
- auditable;
- relationship-aware;
- compatible with automated governance systems.

---

# Objectives

This standard shall:

- establish the canonical metadata contract;
- define mandatory documentary identity fields;
- enable automated governance validation;
- support Genesis ecosystem engines;
- preserve institutional traceability;
- maintain documentary interoperability;
- enable dependency graph construction;
- support long-term knowledge preservation;
- provide deterministic interpretation for Artificial Intelligence systems.

---

# Metadata as a Governance Contract

Metadata is not descriptive information.

Metadata is a governance contract.

Every official document shall expose enough metadata to allow authorized systems and governance authorities to determine:

- what the document is;
- who owns it;
- who approves it;
- what authority governs it;
- what documents depend on it;
- what documents it governs;
- what lifecycle state it currently has;
- where it belongs within the ecosystem.

A document without valid metadata shall not be considered a complete governance artifact.

---

# Metadata Principles

Document metadata shall be:

## Canonical

Every document shall use the official BHG metadata structure.

---

## Explicit

No critical governance information shall depend on inference.

---

## Deterministic

The same metadata input shall always produce the same interpretation.

---

## Machine-readable

Metadata shall support automated processing.

---

## Human-readable

Metadata shall remain understandable without automation.

---

## Traceable

Every metadata change shall preserve historical evidence.

---

## Version-controlled

Metadata evolution shall follow the corporate versioning model.

---

## Extensible

New fields may be introduced through governance approval without compromising existing documents.

---
# Document Metadata Standard

> Defines the canonical metadata contract for every governance document within the Breto's Holding Group ecosystem.

---

# Metadata Architecture

Metadata is structured into logical governance domains.

Each domain represents a specific dimension of documentary identity, governance authority, lifecycle control and relationship management.

The metadata architecture shall preserve separation between:

- documentary identity;
- governance authority;
- lifecycle management;
- classification;
- repository ownership;
- documentary relationships;
- validation state.

---

# Domain 1 — Documentary Identity

This domain defines the permanent identity of a governance artifact.

Mandatory fields:

- title
- document_id
- document_type
- version

## Title

Defines the official human-readable name of the document.

Requirements:

- shall represent the official purpose of the document;
- shall remain consistent throughout the document lifecycle;
- shall not create ambiguity with existing documents.

---

## Document Identifier

Defines the permanent machine-readable identity of the document.

Requirements:

- shall be unique;
- shall never be reused;
- shall remain stable across document versions;
- shall comply with DOCUMENT_IDENTIFIER_STANDARD.md.

The document identifier represents the identity of the artifact and not the current version.

---

## Document Type

Defines the normative category of the document.

Allowed categories include:

- Constitution
- Model
- Policy
- Standard
- Procedure
- Guide
- Record

---

## Version

Defines the current evolution state of the document.

Requirements:

- shall follow VERSIONING_POLICY.md;
- shall represent the impact of changes;
- shall preserve historical continuity.

---

# Domain 2 — Governance Authority

This domain defines institutional ownership and approval responsibility.

Mandatory fields:

- governance_level
- owner
- approval_authority

---

## Governance Level

Defines the normative position of the document inside the BHG governance hierarchy.

The governance level determines:

- authority scope;
- review requirements;
- approval requirements;
- inheritance rules.

---

## Owner

Defines the organizational authority responsible for maintaining the document.

The owner shall ensure:

- accuracy;
- lifecycle management;
- periodic review;
- governance compliance.

---

## Approval Authority

Defines the authority responsible for formal approval.

Approval authority shall be determined according to:

- BHG_CONSTITUTION.md;
- GOVERNANCE_MODEL.md;
- AUTHORITY_MODEL.md;
- AUTHORITY_MATRIX.md.

---

# Domain 3 — Lifecycle Management

This domain defines the evolution state of the document.

Mandatory fields:

- status
- created
- last_updated
- effective_date

---

## Status

Defines the official lifecycle state.

Allowed values:

- Concept
- Draft
- Review
- Approved
- Active
- Deprecated
- Archived

---

## Created

Defines the original creation date.

This field represents historical origin and shall not be modified.

---

## Last Updated

Defines the latest approved modification date.

Every approved modification shall update this value.

---

## Effective Date

Defines the date from which the current version becomes applicable.

Approval and effectiveness may occur on different dates.

---

# Domain 4 — Classification and Language

This domain defines information handling and interpretation requirements.

Mandatory fields:

- classification
- language

---

## Classification

Defines the information handling category.

Classification shall follow:

DOCUMENT_CLASSIFICATION_STANDARD.md

Examples:

- Public
- Internal
- Confidential
- Restricted

---

## Language

Defines the canonical interpretation language.

Language shall:

- be explicitly declared;
- follow LANGUAGE_POLICY.md;
- never be inferred by automated systems.

---

# Domain 5 — Repository Identity

This domain defines the official source location.

Mandatory field:

- repository

---

## Repository

Defines the authorized repository containing the canonical document.

Requirements:

- shall identify the official source of truth;
- shall support auditability;
- shall remain consistent with repository governance.

---

# Domain 6 — Documentary Relationships

This domain defines how the document connects with the governance ecosystem.

Mandatory fields:

- governed_by
- governs
- depends_on
- related_to

---

## Governed By

Defines superior documents that provide authority.

Examples:

- Constitution;
- Governance Models;
- Policies.

---

## Governs

Defines documents that derive authority from this document.

---

## Depends On

Defines documents required for correct interpretation, implementation or validation.

Examples:

- schemas;
- standards;
- templates;
- procedures.

---

## Related To

Defines associated documents without direct authority inheritance.

Examples:

- complementary documents;
- historical references;
- supporting documentation.

---

# Documentary Relationship Graph

Metadata relationships shall allow authorized systems to reconstruct the governance knowledge graph.

The graph shall support:

- authority resolution;
- dependency analysis;
- impact assessment;
- change propagation;
- baseline validation.

---

# Metadata Immutability Rules

The following fields represent permanent identity:

- document_id;
- created;
- repository.

These fields shall not change after document approval.

Controlled fields may change through approved governance modification:

- title;
- owner;
- approval_authority;
- governance_level;
- relationships.

Every controlled modification shall preserve:

- version history;
- justification;
- approval evidence.

---

# Metadata Validation Framework

Every document shall pass metadata validation before:

- approval;
- publication;
- baseline inclusion;
- repository certification.

Validation shall verify:

- required fields;
- metadata schema;
- identifier uniqueness;
- authority relationships;
- dependency integrity;
- lifecycle consistency;
- version compliance.

---

# Genesis Compatibility

Genesis systems shall use metadata as the primary structural layer for:

- repository discovery;
- document classification;
- dependency mapping;
- governance validation;
- baseline certification;
- compliance analysis.

Metadata failures shall generate governance findings and prevent certification when required.

# Advanced Metadata Governance

Metadata evolution shall be controlled through governance procedures.

Metadata changes shall not occur independently from the documentary governance model.

Any modification to the metadata contract shall evaluate:

- backward compatibility;
- validation impact;
- automation impact;
- dependency impact;
- baseline impact.

---

# Metadata Schema Evolution

The metadata schema may evolve through controlled governance changes.

New metadata fields:

- shall require governance approval;
- shall include documentation;
- shall define validation rules;
- shall preserve compatibility whenever possible.

Breaking changes to metadata interpretation require:

- major version increment;
- migration strategy;
- impact assessment;
- governance approval.

---

# Metadata Validation States

Documents processed by governance automation may contain validation states.

Supported validation states include:

- Pending Validation
- Validated
- Validation Warning
- Validation Failed
- Certified

Validation state information shall never replace the official document status.

Document status represents governance lifecycle.

Validation state represents technical compliance verification.

---

# Artificial Intelligence Compatibility

Artificial Intelligence systems shall use metadata as the primary structural reference for document interpretation.

AI systems may use metadata to:

- identify authoritative documents;
- reconstruct governance chains;
- detect missing relationships;
- analyze dependencies;
- evaluate documentary consistency;
- support compliance analysis.

AI systems shall never:

- modify governance authority;
- change document ownership;
- approve documents;
- override metadata rules.

---

# BKOs Compatibility

BKOs shall use metadata to maintain the institutional knowledge graph.

BKOs capabilities include:

- document indexing;
- relationship discovery;
- dependency mapping;
- historical reconstruction;
- governance context retrieval;
- impact analysis.

BKOs shall consider metadata as the structural identity layer of institutional knowledge.

---

# BEiA Compatibility

BEiA shall use metadata to:

- explain document authority;
- identify applicable governance rules;
- analyze documentary evolution;
- prepare governance reports;
- detect inconsistencies.

BEiA recommendations shall remain advisory.

Human governance authorities retain final decision authority.

---

# Corporate Compliance Engine Compatibility

The Corporate Compliance Engine shall validate metadata before:

- document approval;
- repository publication;
- Genesis Baseline certification;
- governance audits.

Validation shall verify:

- mandatory metadata fields;
- schema compliance;
- relationship integrity;
- lifecycle consistency;
- version alignment;
- governance authority.

Documents failing validation shall generate compliance findings.

---

# Repository Integration

Every repository containing BHG governance documents shall ensure:

- metadata availability;
- metadata consistency;
- identifier uniqueness;
- relationship preservation;
- version traceability.

Repository automation may use metadata for:

- indexing;
- validation;
- documentation generation;
- compliance monitoring.

---

# Audit Requirements

Every metadata modification shall preserve evidence.

Audit records shall allow reconstruction of:

- previous metadata state;
- modified fields;
- modification reason;
- approving authority;
- effective date;
- affected documents.

---

# Long-Term Preservation

Metadata shall preserve institutional continuity across technological generations.

Document formats may evolve.

Storage systems may change.

Automation platforms may be replaced.

The canonical metadata model shall preserve the identity and governance meaning of every institutional document.

---

# Compliance

All governance documents within the Breto's Holding Group ecosystem shall comply with this standard.

Documents without valid metadata shall not be considered complete governance artifacts.

Non-compliant documents shall enter the appropriate remediation process.

---

# Institutional Principle

> Metadata transforms documents into governed institutional assets.

> A consistent metadata model enables deterministic governance, automation and institutional continuity across generations.
