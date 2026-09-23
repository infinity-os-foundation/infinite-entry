# Infinite Entry

**A record system for businesses operated by AI.**

Infinite Entry specifies the primitives a business keeps records in, the relationships between
those primitives, and the invariants those records must satisfy. It covers what was observed, what
it means, what is being done about it, who authorised it, and what followed.

It extends the accounting tradition in two directions at once: across all data, not only financial
transactions, and across action, not only past fact.

**[Read the specification](IE-SPEC.md)**

---

## Status: draft. Not a standard yet.

> **Version 2.0-draft is not normative, and you should not cite it as a standard.**
>
> Its primitives and invariants are derived from **a single implementation**. A specification
> derived from one implementation is a description of that implementation until a second,
> independent implementation exists.
>
> Under the Foundation's two-implementation rule, this becomes normative when at least two
> independent interoperating implementations exist and at least one is not by the Foundation's
> sponsor. Until then it is published as a draft so the work is visible while it waits.

We would rather publish a serious draft and tell you why it is not a standard than declare a
standard nobody else has built against.

## What is in here

| | |
|---|---|
| `IE-SPEC.md` | The specification, version 2.0-draft |
| `CHANGELOG.md` | What changed from version 1.0 and why |

## The short version

Double entry is not a conservation law. Double entry is a **record system**: a journal, a ledger, a
chart of accounts, and a trial balance that checks it. Debits equalling credits is the invariant,
not the system.

Infinite Entry is the same four things over a wider domain, plus one group double entry never
needed. A ledger clerk could not act without a human instructing them, and the instruction lived
outside the books. **An agent can act.** So a business operated by AI has to record authority,
intent and effect, or nobody can reconstruct who permitted an action after the fact.

The metric layer carries a conservation law, driver contributions equal total change. It is the
direct analogue of the trial balance, and it is one of seven invariants rather than the whole
system.

## Conformance

Section 10 of the specification says what conformance means, which version 1.0 did not. In short, an
implementation conforms when it provides the primitives or documents its substitutes, its records
are sufficient to detect a violation of each invariant **from the records alone**, and it publishes
which invariants it checks automatically and which it does not.

**An implementation that checks none of them automatically may still conform, provided it says so.**
What does not conform is a conformance claim a reader cannot check, including one made by the
Foundation or its sponsor.

## Who maintains this

The Infinity OS Foundation. The Foundation is funded and staffed by StarMynd, which builds
commercial products on this standard and benefits when it is adopted. That is stated here rather
than in a footer because you would find it anyway, and where you find it changes how you read the
rest.

The Foundation publishes. It does not operate systems for individual businesses.

## Contributing

A second independent implementation is the most useful contribution anyone can make, because it is
the thing standing between this document and being a standard at all.

Issues and proposals are welcome. Objections are more welcome, and published in full.

## Licence

This specification is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.
See `LICENSE` for the full legal code.

You may copy, modify and redistribute it, including commercially, provided you credit the source and **indicate whether you made changes**. That second requirement is the point: it is what stops a
modified copy circulating as though it were the original, which is the one failure a citable
reference cannot survive.

The Foundation's software, including Infinity OS, is licensed separately under MIT. A specification
and an implementation are different things and are licensed differently on purpose.

### Implementing it needs no permission

**You do not need permission from the Foundation to build something to this specification.** The
operative wording is in [`GRANT.md`](GRANT.md), which sits beside `LICENSE` rather than inside it,
because `LICENSE` is the unmodified official CC BY 4.0 legal code and adding sentences to it would
create a non-standard licence no tool could recognise.

`GRANT.md` is the single canonical copy of that wording. This paragraph summarises it and
deliberately does not restate it, so the two cannot drift apart.

