# Decision Log

This file records important project decisions, their rationale, alternatives considered, and expected impact.

Use this log for decisions that materially affect project scope, architecture, methodology, licensing, public release boundaries, data handling, or security posture.

## How to use this log

Add a new entry when a decision:

- changes the project direction;
- accepts an important trade-off;
- defines scope or out-of-scope boundaries;
- selects a standard, framework, model, technology, or license;
- affects public release readiness;
- affects clean-room / IP boundaries;
- affects security, privacy, evidence, or assurance logic.

Keep entries short enough to be readable, but specific enough that a future reader can understand why the decision was made.

## Status values

- `Proposed` — under discussion, not yet accepted.
- `Accepted` — current project position.
- `Superseded` — replaced by a later decision.
- `Rejected` — considered but not adopted.
- `Deprecated` — previously used, but should no longer guide new work.

## Decision entries

### DEC-0001 — Decision title

**Date:** YYYY-MM-DD  
**Status:** Proposed / Accepted / Superseded / Rejected / Deprecated  
**Owner:** Name or role  
**Related files:** `README.md`, `docs/example.md`, `schemas/example.schema.json`

#### Context

What problem, uncertainty, constraint, or opportunity led to this decision?

Include only relevant background. Avoid private, employer-specific, customer-specific, or confidential details.

#### Decision

What was decided?

State the decision directly and clearly.

#### Rationale

Why was this option selected?

Explain the reasoning, assumptions, and intended benefits.

#### Alternatives considered

- **Option A:** Brief description and why it was not selected.
- **Option B:** Brief description and why it was not selected.
- **Option C:** Brief description and why it was not selected.

#### Trade-offs

What are the accepted costs, limitations, or risks?

Examples:

- simpler now, but less flexible later;
- more structured, but higher initial documentation burden;
- more open, but requires stronger clean-room discipline;
- more automation, but requires human validation.

#### Impact

What changes because of this decision?

Consider:

- documentation;
- code;
- schemas;
- examples;
- tests;
- licensing;
- release model;
- future work.

#### Review trigger

When should this decision be revisited?

Examples:

- when the project becomes public;
- when the first schema is stable;
- when real users or reviewers appear;
- when a better standard or model is selected;
- before production use;
- before external publication.

---

### DEC-0002 — Decision title

**Date:** YYYY-MM-DD  
**Status:** Proposed / Accepted / Superseded / Rejected / Deprecated  
**Owner:** Name or role  
**Related files:** `path/to/file.md`

#### Context


#### Decision


#### Rationale


#### Alternatives considered


#### Trade-offs


#### Impact


#### Review trigger


---

## Lightweight entry format

Use this shorter format for smaller decisions that do not need a full explanation.

### DEC-XXXX — Decision title

**Date:** YYYY-MM-DD  
**Status:** Accepted  
**Decision:** Short statement of what was decided.  
**Reason:** Short reason.  
**Review trigger:** When to revisit.
