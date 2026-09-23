# Changelog

## 2.0-draft, 2026-09-23

**Status: draft, not normative.** Derived from a single implementation. See the notice at the top of
`IE-SPEC.md`.

### The change in one sentence

Version 1.0 named the framework after its invariant. Version 2.0 names the system.

### Why

Double entry is not a conservation law. Double entry is a **record system**: a journal, a ledger, a
chart of accounts, and a trial balance that checks it. Debits equalling credits is the invariant,
not the system.

Version 1.0 defined Infinite Entry as "a conservation law for business metrics", which is the
parallel to the trial balance rather than to double entry itself. Version 2.0 defines it as the
record system, and the conservation law becomes one of its invariants.

### What changed

| | |
|---|---|
| **Title** | "A Framework for Structured Business Intelligence" becomes "A Record System for Businesses Operated by AI" |
| **Abstract** | Rewritten to the record-system framing |
| **4.1 Core Axioms** | Adds **Axiom 2**: a business operated by non-deterministic agents must record not only what happened, but what was permitted, by whom, and what followed. This is the axiom double entry never needed, because a ledger clerk could not act without a human instruction that lived outside the books. An agent can act |
| **4.2** (new) | What a record system is, and the mapping from double entry's four parts |
| **4.3** (new) | **The primitives.** Six groups: observation, meaning, intent, authority, identity, attention. Every row measured from a working implementation |
| **4.4 to 4.7** | The Infinite Ledger, the metric registry, the dimension registry and the two consumption modes. **Unchanged prose**, renumbered from 4.2 to 4.5, and now presented as Group 2 of the primitive set rather than as the whole framework |
| **4.8 The invariants** | The conservation law, unchanged, becomes **invariant I1** and gains six siblings: no effect without a prior reservation, no effect without a named authority, no action without a held lease, an approval is spent once, every row a human touches names that human, and outcome and completeness are two questions |
| **4.9** | Shared context. Unchanged, renumbered from 4.7 |
| **9.5** (new) | A second endurance argument: a record system outlives its records because its primitives describe what a business must remember, not how it happens to be written down |
| **10 Conformance** (new) | Version 1.0 asserted that any implementation could be validated against the framework and never said what validation means. Section 10 states it |
| **Appendix A** | The glossary entry defining Infinite Entry as a conservation law is corrected. Entries added for the new primitives and for "invariant" |

### Unchanged

Sections 1, 2, 3, 5, 6, 7, 8 and 9.1 to 9.4, and Appendices B and C, are carried over from version
1.0 without modification. Version 2.0 was assembled by splicing into the version 1.0 text rather
than by rewriting it, so unchanged sections are preserved exactly.

### Known limitations of this draft

1. **The primitive set is derived from one implementation.** That is a strength for accuracy and a
   weakness for neutrality. A specification derived from one implementation describes that
   implementation until a second exists.
2. **Invariants I6 and I7 are policy, not mathematics.** I1 is arithmetic and cannot be argued
   with. I6 and I7 are design positions on accountability that a reasonable implementer might
   contest. They are marked as such in the text.
3. **Section 8 has not been extended.** It should state which primitive groups each implementation
   layer is responsible for, so an implementation can be checked group by group. Not done.
4. **Section 9.1 to 9.4 still argues endurance from the single axiom.** 9.5 adds the systemic
   argument beside it rather than rewriting the original prose.

## 1.0, 2026-03-27

Initial specification. Infinite Entry as a framework for structured business intelligence, built on
a conservation law for business metrics.
