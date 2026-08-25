# AI Consulting Practice — Action Register

Per-project action register per the cross-project discipline (see `action-registers` memory). Automated sweeps land under "Proposed (unreviewed)"; only Bala's confirmation moves an item into an Open table.

> **Machine-readable contract** (read by `action-digest.py`, do not break it):
> `Status` is one of `open` | `waiting` | `blocked` | `done` | `dropped`.
> `Due` is `YYYY-MM-DD` or `-`. IDs are stable and are never reused.
> Roll-forward calendar events are keyed off the ID, so do not renumber rows.
> Close a row by setting Status and moving it to Done / closed.

Seeded 14 Aug 2026 from the Gerry Perkel call transcript (22 Jul), the Philip and Gerry email threads, and in-session commitments. Normalized to the machine-readable format 24 Aug 2026.

## Open — mine

| ID | Action | Owner | Due | Status | Source | Notes |
|---|---|---|---|---|---|---|
| CON-B1 | Chase Gerry: feedback on the service-packaging deck AND the outcome of his discussion with the Waites COO | Bala | 2026-08-17 | open | Gerry email 28 Jul + deck send 4 Aug | Deck sent 4 Aug, no reply. His own "later this week with more info" (28 Jul) also lapsed. Gates CON-B5. Soft chase SENT 25 Aug (check-in mail: consulting + Caitlin readout + catch-up proposed Tue/Thu, Wed 26 Aug India holiday; see COMMUNICATIONS.md 25 Aug entry). Hold further chasing until he answers or the catch-up happens. |
| CON-B2 | Get the staff list from Susan or Mency and screen internally for the offsite solution-designer role | Bala | 2026-08-18 | open | Bala, 28 Jul session; `Offering/team-plan.md` | Capture "holds a valid US visa" as an explicit filter alongside the six consulting-trait criteria. |
| CON-B3 | Network outreach for Philip's two asks: peer intel on prior AI consulting engagements (priority: fees actually paid, and whether an advisor who also builds reads as a plus or a bias risk) plus potential hires | Bala | 2026-08-19 | open | Philip call 16 Jul (promised "in a few days") | Question set ready in `Research/peer-interview-questions.md`. |
| CON-B7 | Raise practice org placement and Dharma's sponsorship at the Bala–Dharma 1-1 | Bala | 2026-08-21 | open | `Offering/team-plan.md` politics note | The practice overlaps the Chief AI Officer's domain; early blessing turns a turf risk into air cover. The 21 Aug 1-1 did happen — confirm whether this was raised. |
| CON-B4 | Build the anonymized sample assessment report from real Techjays engagements (NSR DND artifacts, the logistics redesign) | Bala | 2026-08-24 | open | Packaging deck slide 7, sent to Gerry 4 Aug | Claude to draft. Committed to Gerry in writing as the "Next" step on the deck. |
| CON-B5 | Draft the four Waites department questionnaires (sales, business development, marketing, customer service), pre-sendable, answerable in under an hour each | Bala | - | blocked | Waites approach document | Claude to draft. Promised "once scope is confirmed" — trigger when Gerry confirms the engagement is moving (CON-B1). |
| CON-B6 | Practice-setup working session with Philip: the six open decisions (framework and offering names, pilot client and pricing, whether SKU 0 stays, who fronts the practice, marketplace channel timing, org placement) | Bala | - | blocked | `Offering/roadmap.md` | Parked since the Waites opportunity took over. Schedule once Gerry's direction is clear. |

## Waiting on others (standing)

| ID | Action | Owner | Due | Status | Source | Notes |
|---|---|---|---|---|---|---|
| CON-W1 | Feedback on the service-packaging deck (how we describe/sell the service, why us) | Gerry Perkel | - | waiting | 4 Aug | Active chase is CON-B1. |
| CON-W2 | Outcome of Gerry's discussion with the Waites COO: does she want to proceed in this direction? | Gerry Perkel / Waites COO | - | waiting | 28 Jul | Active chase is CON-B1. |
| CON-W3 | Staff list for internal team screening | Susan / Mency | - | waiting | 28 Jul | Bala to request — CON-B2. |

## Proposed (unreviewed)

*(Sweeps append here; nothing below is confirmed.)*

## Done / closed

| ID | Action | Owner | Closed | Note |
|---|---|---|---|---|
| CON-D1 | Market research on how big firms package AI pre-study offerings | Bala | 2026-07-21 | Two verified passes; `Research/competitive-teardown.md` |
| CON-D2 | Waites engagement-approach document, reviewed by Philip, sent to Gerry | Bala | 2026-07-24 | Gerry: "a great first pass" |
| CON-D3 | Service packaging (description, seller toolkit, why-us) built, approved by Philip and Dharma, sent to Gerry | Bala | 2026-08-04 | `Offering/Service_Packaging_Deck_V2.pptx` |
| CON-D4 | Pre-pitch research on Waites and the competitive AI landscape | Bala | 2026-07-28 | `Prospects/Waites/waites-market-research.md`; offered to Gerry as enrichment |
| CON-D5 | BCG CEO-board AI knowledge gap added to the knowledge base | Bala | 2026-08-05 | `Research/bcg-ceo-board-ai-gap.md` |
