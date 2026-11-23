# Status freshness — how to read this shared reference

**Published 23 November 2026. This is a dated, curated public team reference, not a live feed.**

The operational evidence and current-state register are maintained in an **internal private** OBJECTS repository. This public documentation is a reviewed, non-sensitive projection. No Gmail, phonebook, telemetry, finance, internal map or confidential plant data is synced into this site.

## Interpret a statement with three separate questions

1. **What was actually evidenced?** Example: the supplier confirmed in writing that a delivery is agreed.
2. **What has not yet been evidenced?** Example: a confirmed delivery appointment is *not* physical handover, a paid invoice, a usable tank, a commissioned cooling circuit or two-press production.
3. **When must it be rechecked?** Example: after an expected arrival window ends, a site handover check is needed. Old text must not be treated as live fact.

A source-backed **seller confirmation** can be valid historical evidence forever, while the **current delivery status** becomes stale quickly. Those are different things.

## Current time-sensitive example: three incoming 1,000 L IBC containers

| Field | State at last verification |
| --- | --- |
| Evidence observed | Seller confirmed the agreed delivery in writing on **23 Nov 2026, 14:53 CET** |
| Promised arrival window | **Tue 24 Nov, 11:00–12:00 CET** |
| Supplier handling | Delivery and unloading agreed |
| Physical receipt | **NOT VERIFIED** (as of 23 Nov) |
| Condition, outlets, cleaning, filling, coolant compatibility | **NOT YET VERIFIED / NOT QUALIFIED** |
| Required freshness check | **Tue 24 Nov, by 12:30 CET** (site handover evidence) |

**After 24 Nov 12:30 CET:** unless a newer verified site report has been incorporated, treat the statement above as a **historical delivery promise requiring recheck**. Do not tell colleagues the containers were delivered or missed; neither is proven from this file alone.

## Rules for colleagues, contractors and AI assistants

- Read [equipment status](EQUIPMENT-STATUS.md), check the evidence date and state the *as-of* time. If a statement is past its review time, mark it **NEEDS CURRENT VERIFICATION**.
- Distinguish **ordered → seller confirmed → dispatched → received → inspected → filled → approved for use**. Do not skip statuses.
- Do not treat a Markdown document, AI-generated diagram, successful purchase, shipping window or nominal pump flow as authority for technical commissioning.
- Corrections should be dated and include the primary evidence or onsite observer. Follow [feedback instructions](../FEEDBACK.md).
- Sensitive supplier references, internal wayfinding, personnel phone numbers, site/security details and original engineering images must remain in approved private channels.

This publication is intentionally conservative: an unknown or overdue fact should be **visibly unknown**, not replaced with an unsupported guess.
