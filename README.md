# SaveSG Design Preview

Temporary public, static prototype for reviewing SaveSG's redesigned consumer experience on phone and desktop.

## Important

- All names, prices, decisions, dates, documents, and household details are synthetic.
- This prototype does not upload, transmit, or process files.
- It is not connected to SaveSG production services and must not be used with private data.
- It demonstrates product direction, information architecture, responsive behavior, and interaction states—not production readiness.

## Interaction map

- **Overview:** household monitor, priority decision, mobile/broadband/electricity service ledger.
- **Mobile decision:** current vs. recommended economics, evidence, assumptions, and fail-closed JIT verification.
- **Bills:** simulated named processing states and material-field confirmation.
- **Activity:** scheduled reviews and evidence/status history.
- **Household:** members, services, interruption policy, privacy, and reset controls.
- **Preview controls:** restart onboarding or reset local prototype state.

No build step or external dependencies are required. GitHub Pages serves `index.html` directly.

## Design posture

Primary surface: **Monitor**. Secondary surfaces: **Decide / Inspect** and **Configure**.

Visual base: Claude-authored **Quiet Ledger**, with Civic Relay's evidence trail, confidence disclosure, and JIT unavailable state. Composition prioritizes one decision, numeric trust, precise dividers, and mobile resilience over generic dashboard cards.
