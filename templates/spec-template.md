# Specifications

> This file is the single source of truth for this project.
> All tests and implementation derive from these specifications.
> Changes flow: Principles → Spec → Tests → Implementation

## Metadata

- **Project:** [Project Name]
- **Created:** [DATE]
- **Test Framework:** [FRAMEWORK]
- **Last Updated:** [DATE]
- **SDD Version:** 1.1

## Governing Principles

This specification is governed by the following principle documents:

- [Architecture Principles](./principles-architecture.md) — Module boundaries, data flow, structural patterns
- [Development Principles](./principles-development.md) — Code style, testing approach, required patterns
- [Security Principles](./principles-security.md) — Secrets handling, validation, audit requirements

All specifications must comply with these principles. Non-compliance requires explicit justification or principle update.

---

## Feature: [Feature Name]

> [Brief description of what this feature does and why it exists]

### REQ-001: [Requirement Title]

[Clear description of the expected behavior. Focus on WHAT, not HOW.
Describe the behavior from the user's perspective.]

**Preconditions:**
- [What must be true before this behavior can occur]
- [Required state, data, or context]

**Trigger:**
- [What action or event initiates this behavior]

**Expected Behavior:**
- [Step-by-step what should happen]
- [Be specific about outputs, state changes, side effects]

**Acceptance Criteria:**
- [ ] [Testable criterion 1 - specific, measurable]
- [ ] [Testable criterion 2 - can be verified by code]

**Edge Cases:**
- [Edge case 1]: [Expected behavior for this case]
- [Edge case 2]: [Expected behavior for this case]

**Constraints:**
- [Performance requirements]
- [Security considerations]
- [Technical limitations]

**Principles Compliance:**
- Architecture: [Which architecture principles apply and how this spec honors them]
- Development: [Which development principles apply and how this spec honors them]
- Security: [Which security principles apply and how this spec honors them]

---

<!--
=== TEMPLATE FOR NEW REQUIREMENTS ===

### REQ-XXX: [Title]

[Description of behavior]

**Preconditions:**
- [Precondition]

**Trigger:**
- [What initiates this]

**Expected Behavior:**
- [What happens]

**Acceptance Criteria:**
- [ ] [Criterion]

**Edge Cases:**
- [Case]: [Behavior]

**Constraints:**
- [Constraint]

**Principles Compliance:**
- Architecture: [Applicable principles and compliance]
- Development: [Applicable principles and compliance]
- Security: [Applicable principles and compliance]

=== END TEMPLATE ===
-->

---

## Specification Quality Checklist

Before finalizing any spec, verify:

- [ ] **Observable:** Describes external behavior, not internal implementation
- [ ] **Testable:** Each criterion can be verified by automated test
- [ ] **Unambiguous:** Only one way to interpret the requirement
- [ ] **Complete:** Covers happy path AND failure cases
- [ ] **Independent:** Minimal coupling to other specifications
- [ ] **Traceable:** Clear ID for linking to tests (REQ-XXX)
- [ ] **Principle-Compliant:** Explicitly addresses relevant architecture, development, and security principles
