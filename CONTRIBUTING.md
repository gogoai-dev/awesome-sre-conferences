# Contributing

Thanks for helping keep this list accurate. Conference lists rot fast, so the bar here is about verifiability rather than volume.

## What belongs here

An event belongs in this list if its primary audience is **SRE, DevOps, Platform Engineering, cloud native, or observability** practitioners.

In scope: SRE and reliability conferences, DevOps and DevSecOps events, KubeCon and its co-located days, Kubernetes Community Days, platform engineering and internal developer platform events, observability and monitoring conferences, cloud-native and FinOps-for-engineers events, and incident-management events.

Out of scope: kernel and embedded Linux conferences, general software engineering conferences, vendor user-group meetings for a single product, legal or governance summits, anything without a public agenda, and one-off webinars.

## Adding an event

Add a row to the correct region table, keeping rows in **date order**. Every row needs:

1. **A date.** Real dates only. `2026`, `Q3 2026` or `TBA 2026` are acceptable only when the organizer has genuinely not announced one. No entry without a date field.
2. **A link to the organizer's own page**, not to an aggregator, a LinkedIn post, or a ticketing partner.
3. **A location**, or `Online`.

Use the same formats already in the file: `22 Aug 2026` for single days, `9–12 Nov 2026` (en dash) for ranges.

## Adding a CFP

Add a row to the CFP table in **deadline order**. It needs the CFP close date, the conference name, the event date and location, and a direct link to the submission page (Sessionize, PaperCall, Conference Hall, or the organizer's own form).

If a conference has announced a CFP but not a deadline, add it to the "announced, deadline not yet published" line instead of the table.

## Removing things

Past events and closed CFPs are **deleted**, not struck through or moved to an archive section. The value of this list is that everything in it is still actionable.

If you spot something past its date, a PR that just deletes it is a perfectly good PR.

## Fixing a date

Dates drift. If an organizer moves an event, open a PR with the corrected date and link to the announcement in the PR description.

## Checks before you open a PR

- The link resolves and is the organizer's own page.
- The event is not already listed under a different name (co-located days and their parent conference are both allowed; exact duplicates are not).
- The row is in date order within its table.
- Markdown tables still render.

## Adding a whole category

If you want to propose a new region table or a new section, open an issue first so we can agree on scope before you do the work.
