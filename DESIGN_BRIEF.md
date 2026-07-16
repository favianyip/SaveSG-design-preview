# SaveSG High-Fidelity Redesign Prototype

## Assignment
Redesign the entire consumer-facing SaveSG experience as a responsive, high-fidelity interactive prototype for phone and desktop. This will be published as a temporary public GitHub Pages preview for the owner to inspect overseas on a phone.

## Surface commitment
Primary surface: **Monitor** — a calm household command centre where state and one meaningful action are glanceable.
Secondary surfaces: **Decide / Inspect** for recommendation detail and **Configure** for bill review/onboarding.
Do not use a marketing hero or a generic SaaS KPI/card grid as the main product screen.

## Product law
- Analyze many variables; show one decision.
- SWITCH, WAIT, NO ACTION, and VERIFY INFORMATION are equally legitimate outcomes.
- Unknown is better than wrong; action requires JIT revalidation.
- No comparison marketplace as the primary UI.
- No government affiliation, provider bias, fintech hype, gamification, AI sparkles, coins, gradients, Merlion/flag imagery, or invented production claims.
- This preview uses clearly labeled synthetic data only.
- Consumer web and native app share the same information architecture.

## Selected visual direction
Use **Quiet Ledger** as the base, importing only Civic Relay's confidence/evidence trail and JIT unavailable state. The existing implementation is too raw; do not simply reskin its bordered cards.

Create a more editorial, premium, calm utility-management product:
- warm paper-like neutral background, ink-black typography, restrained deep green action color, amber only for waiting, blue for evidence;
- exceptional numeric/date typography with tabular figures;
- precise dividers and hierarchy instead of excessive cards, pills, shadows, or rounded rectangles;
- original ledger/check mark that works as favicon and app mark;
- mobile bottom navigation and desktop left rail, using the same content model;
- 44px minimum touch targets, strong focus styles, WCAG-conscious contrast, reduced-motion support;
- no remote dependencies, web fonts, image APIs, or icon libraries.

## Required interactive product surfaces
Build one self-contained `index.html` with embedded CSS and JavaScript. It must include:
1. **Overview/Monitor** — household annual avoidable spend, one priority decision, service ledger rows for mobile/broadband/electricity, monitoring status.
2. **Service detail / recommendation** — current arrangement, one recommendation, net annual economics, material differences, evidence trail, source time, confidence, JIT unavailable blocking state.
3. **Bill intake and material review** — choose service, simulated processing state, review only provider/current recurring cost/contract end/account mask, confirm success. Never imply a real upload occurs.
4. **Activity** — scheduled reviews and evidence/status timeline, no fake analytics.
5. **Household/settings** — members, services, privacy/deletion controls as a believable preview.
6. **Onboarding preview** — promise, interruption policy, choose first service; accessible as a restart/demo action, not the default main screen.

Interactions:
- navigation works without page reload;
- evidence disclosure expands;
- priority recommendation opens detail;
- JIT verification button visibly runs, then fails closed as unavailable with plain-language copy;
- bill review progresses through real named states, then material confirmation and success;
- desktop/mobile layouts are genuinely recomposed, not merely shrunk;
- persist current surface with URL hash and prototype state with localStorage where helpful;
- provide a small unobtrusive “Preview controls” menu to restart onboarding/reset demo.

## Content
Use only synthetic examples:
- Mobile: Demo Mobile, S$45/month, potential S$216/year, JIT unavailable and handoff blocked.
- Broadband: WAIT until 1 Oct 2026 because termination economics are material.
- Electricity: NO ACTION, already on a strong plan.
- Household: “Tan household” is synthetic and must be labeled as such.
- Source timestamp: 15 Jul 2026, 12:00 PM SGT.

## Deliverables
- `index.html` — complete self-contained prototype.
- `README.md` — temporary public preview disclaimer and interaction map.
- No build step.

## Quality bar
Run the Claude Design slop diagnostic before finishing. Compositional tells 3, 8, and 10 must be absent. Target score 0–1/10. Verify HTML structure and key interaction selectors. Do not modify `/home/favianyip/SaveSG`; write only in this preview directory.
