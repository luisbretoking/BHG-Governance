---
title: Document Linting Standard
version: 1.1.0
status: Approved
document-type: Standard
governance-level: Enterprise
owner: BHG Governance Council
approval-authority: BHG Governance Council
language: en
classification: Internal

applies-to:
  - Entire BHG Ecosystem

governed-by:
  - BHG_CONSTITUTION.md
  - GOVERNANCE_MODEL.md
  - DOCUMENT_STANDARD.md
  - DOCUMENT_SCHEMA_STANDARD.md
  - DOCUMENT_VALIDATION_STANDARD.md
  - DOCUMENT_AUTOMATION_STANDARD.md

governs:
  - Genesis Lint Engine
  - Documentation CI/CD
  - AI Review Engine
  - Repository Validation Engine
  - Continuous Compliance Engine
  - Documentation IDE Extensions
---

# Document Linting Standard

> Defines the official static analysis framework used to detect documentation quality issues before governance validation and compilation.

---

# Purpose

Linting identifies documentation issues as early as possible.

Its purpose is preventive.

Linting improves documentation quality before formal validation.

---

# Objectives

The linting framework shall:

- detect documentation defects;
- enforce institutional standards;
- improve consistency;
- reduce governance errors;
- support continuous quality assurance;
- enable Governance as Code.

---

# Linting Principles

Linting shall be:

- Automatic
- Deterministic
- Repeatable
- Non-destructive
- Machine Verifiable
- Traceable

Linting shall never modify institutional content automatically.

---

# Linting Scope

Linting may analyze:

- metadata;
- headings;
- structure;
- document hierarchy;
- grammar compliance;
- schema compliance;
- references;
- dependencies;
- naming conventions;
- version consistency;
- governance metadata.

---

# Rule Categories

Lint rules are organized into:

## Metadata Rules

Verify:

- required fields;
- metadata consistency;
- identifier uniqueness;
- version formatting.

---

## Structural Rules

Verify:

- heading hierarchy;
- section ordering;
- mandatory sections;
- document organization.

---

## Governance Rules

Verify:

- governed-by references;
- governs references;
- authority consistency;
- governance level.

---

## Dependency Rules

Verify:

- missing references;
- circular dependencies;
- invalid dependencies;
- orphan documents.

---

## Naming Rules

Verify:

- filenames;
- identifiers;
- document titles;
- repository conventions.

---

## Version Rules

Verify:

- semantic versioning;
- version synchronization;
- deprecated references;
- incompatible versions.

---

## Traceability Rules

Verify:

- identifiers;
- audit references;
- governance links;
- certification references.

---

# Severity Levels

Every lint finding shall be classified as:

- Info
- Warning
- Error
- Critical

Critical findings shall block governance progression.

---

# Lint Report

Every execution shall generate:

- Rule Identifier
- Severity
- Location
- Description
- Recommendation
- Detection Timestamp

Reports shall be machine-readable.

---

# IDE Integration

Linting engines should support:

- Visual Studio Code
- Cursor
- GitHub Copilot
- Claude Code
- Codex
- BEiA

Real-time feedback is recommended.

---

# Continuous Linting

Repositories shall execute linting:

- before commits;
- before pull requests;
- during CI;
- before publication;
- during scheduled audits.

---

# AI Compatibility

Artificial Intelligence systems may:

- execute lint rules;
- classify findings;
- recommend corrections;
- prioritize remediation.

AI systems shall not automatically approve governance compliance.

---

# Governance as Code

Lint rules shall be executable by software without human interpretation.

Rule definitions shall remain version-controlled.

---

# Extensibility

Additional lint rules may be introduced while preserving backward compatibility.

The lint engine shall support plug-in based rule extensions.

---

# Institutional Principle

> Prevention is more efficient than correction.

Institutional quality begins before governance approval.
