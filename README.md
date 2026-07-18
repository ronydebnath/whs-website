# TechNova Solutions — Staff WHS Hub

A single-file, offline staff Work Health & Safety (WHS) website for **TechNova Solutions**,
a fictional NSW tech company with a hybrid (office + work-from-home) workforce.

Built as a consulting-pitch deliverable by **Group 2** — Rony, Anmol, Ankit, Zizhen, Yuwei.

## How to open

Just open **`index.html`** in any modern browser (Chrome, Edge, Firefox, Safari).
No server, no internet and no build step are required — everything (styles, scripts
and the three.js hero animation) is inlined in the one file.

## What's inside (six pages, client-side routed)

1. **Home** — plain-English WHS policy statement, the PCBU statement, and three quick-link cards.
2. **Hazards & Reporting** — a filterable/searchable register of 12 hazards (Office / Remote / Both)
   with reporting steps, plus a validating hazard-report form (no backend; shows a confirmation state).
3. **Rights & Duties** — PCBU and worker duties/rights in plain English, each with its real legal
   source cited inline, plus a sources table.
4. **Risk Assessment** — the top 3 risks (L×C rating, level, reasonably practicable control) and a
   colour-coded 5×5 risk matrix.
5. **Emergency & Contacts** — distinct office vs remote/lone-worker procedures, key contacts, and
   emergency numbers (000 prominent).
6. **Resources** — links to SafeWork NSW, NSW Legislation, Safe Work Australia and Comcare.

## Legal grounding

All citations are to real instruments — the **Work Health and Safety Act 2011 (NSW)**
(s 19 primary duty of care, s 27 officers' due diligence, s 28 worker duties, s 29 other persons,
ss 47–49 consultation, s 84 cease unsafe work, Part 6 discrimination) and the
**Work Health and Safety Regulation 2017 (NSW)**, with **SafeWork NSW** as the regulator.

Psychosocial duties cite the WHS Regulation 2017 (NSW) Part 3.2 Div 11 (reg 55A–55D, in force
1 Oct 2022) and electrical safety cites Ch 4 Part 4.7. The 5×5 risk matrix is an *illustrative*
qualitative tool, not a statutory one — this is stated on the page.

## Illustrative data

TechNova Solutions is a fictional company created for this pitch. Staff names, phone extensions,
the office address and ABN are **illustrative examples** to make the demo feel complete — swap in
real details before any actual deployment. Emergency numbers (000, 106, 13 11 26, 13 11 14,
1800 022 222, 13 10 50) are the real Australian services.

## Accessibility & design

Semantic HTML, keyboard-navigable, WCAG AA colour contrast, a skip link, ARIA live regions on the
form/filters, `prefers-reduced-motion` support, and a responsive mobile-first layout. Colour is used
to carry meaning (risk levels, emergency), not for decoration.
