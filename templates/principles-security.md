# Security Principles

> Non-negotiable security requirements for protecting user data and system integrity.

## Philosophy

[One-sentence security philosophy for this project]

---

## Core Principles

### 1. [Principle Name]

[Description and rationale]

**Implementation:**
- [Specific requirement]
- [Specific requirement]

### 2. [Principle Name]

[Description and rationale]

**Implementation:**
- [Specific requirement]
- [Specific requirement]

### 3. [Principle Name]

[Description and rationale]

---

## Secrets Management

### What Constitutes a Secret

- [Item]
- [Item]

### Handling Requirements

| Action | Requirement |
|--------|-------------|
| Storage | [Requirement] |
| Logging | [Requirement] |
| Transit | [Requirement] |

---

## Input Validation

### Validation Strategy

[Describe the approach to input validation]

### Required at Boundaries

- [ ] [Validation type]
- [ ] [Validation type]

### Dangerous Patterns to Reject

- [Pattern]
- [Pattern]

---

## Error Handling Security

### What Errors Should Reveal

To users:
- [What's safe to reveal]

To logs:
- [What should be logged]

### What Errors Must Never Reveal

- [Forbidden information]
- [Forbidden information]

---

## Audit Requirements

### Events That Must Be Logged

| Event | Log Level | Required Fields |
|-------|-----------|-----------------|
| [Event] | [Level] | [Fields] |

### Log Sanitization

[Rules for sanitizing logs]

---

## Security Checklist for Code Review

Every change should verify:

- [ ] No secrets in code or commits
- [ ] All external input validated
- [ ] Error messages reveal no sensitive details
- [ ] Logging contains no secrets
- [ ] [Project-specific check]

---

## See Also

- [Constitution](./constitution.md) - Core principles and mission
- [Architecture Principles](./principles-architecture.md) - Structural guidance
- [Development Principles](./principles-development.md) - Code-level guidance
