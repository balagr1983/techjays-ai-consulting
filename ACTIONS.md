# AI Consulting Practice — Action Register

Per-project action register per the cross-project discipline (see `action-registers` memory). Automated sweeps land under "Proposed (unreviewed)"; only Bala's confirmation moves an item into an Open table.

> **Machine-readable contract** (read by `action-digest.py`, do not break it):
> `Status` is one of `open` | `waiting` | `blocked` | `done` | `dropped`.
> `Due` is `YYYY-MM-DD` or `-`. IDs are stable and are never reused.
> Roll-forward calendar events are keyed off the ID, so do not renumber rows.
> Close a row by setting Status and moving it to Done / closed.

Seeded 14 Aug 2026 from the Gerry Perkel call transcript (22 Jul), the Philip and Gerry email threads, and in-session commitments. Normalized to the machine-readable format 24 Aug 2026.

## Open — mine

| ID | Action | Owner | Priority | Due | Status | Source | Notes |
|---|---|---|---|---|---|---|---|

## Waiting on others (standing)

| ID | Action | Owner | Priority | Due | Status | Source | Notes |
|---|---|---|---|---|---|---|---|

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
| CON-B1 | Chase Gerry: deck feedback + Waites COO outcome | Bala | 2026-08-25 | Chased in one line inside the 25 Aug check-in mail ("NSR Ops AI Status and Consulting Updates"); catch-up proposed Tue/Thu. The wait continued as CON-W1/W2, both parked 28 Aug; CON-B5 was gated on his answer. |
| CON-B8 | Confirm Gerry's proposed catch-up slot (Fri 28 Aug, 8:30 AM PT / 11:30 AM EST) and send the invite | Bala | 2026-08-28 | Closed via board 28 Aug evening. Was the last live CON item; the register is now fully parked. The call's outcome decides what reopens from the Parked block. |

### Parked 28 Aug 2026 — reopen after the Gerry call

**Bala's ruling, 28 Aug:** everything on the consulting practice is downstream of tonight's Gerry catch-up (CON-B8) and of what happens with Waites. Nothing here is delivered or abandoned — it is all parked so it stops nagging, and re-seeds off the call outcome. **CON-B8 is the only CON item left open.** When the call lands, reopen from this list rather than re-deriving it.

**Call outcome (28 Aug, per Bala):** the register stays parked — no new CON action items. (1) NSR side: Bala connects with Caitlin on justifying the project's success to the board; Rajesh's ROI deck goes to Gerry and Caitlin once ready — tracked as OPS-B4-B6 in the Ops AI register, not here. (2) Waites: a quick 2-week mini project will be proposed; Bala is sending Gerry the updated costing himself (based on the initial costing), deliberately not tracked as an item. CON-W1 (deck feedback) and CON-W2 (Waites COO outcome) are effectively answered by this call; the mini-project proposal is the new thread the register re-seeds from if it lands.

| ID | Action | Owner | Closed | Note |
|---|---|---|---|---|
| CON-B2 | Get the staff list from Susan or Mency and screen internally for the offsite solution-designer role | Bala | 2026-08-28 | PARKED, not done. Was already parked 25 Aug. Reopen with the "holds a valid US visa" filter captured alongside the six consulting-trait criteria. |
| CON-B3 | Network outreach for Philip's two asks: peer intel on prior AI consulting engagements (fees actually paid; whether an advisor who also builds reads as a plus or a bias risk) plus potential hires | Bala | 2026-08-28 | PARKED, not done. Bala 28 Aug: "ignore for now, will re-open it later." PARTIAL as of 25 Aug — one candidate applied on the hires side; the peer-intel half is untouched. Question set is ready in `Research/peer-interview-questions.md`. |
| CON-B4 | Build the anonymized sample assessment report from real Techjays engagements (NSR DND artifacts, the logistics redesign) | Bala | 2026-08-28 | PARKED, not done. Bala first said move to the week of 7 Sep, then parked all CON — the park supersedes. NOTE: this one was committed to Gerry in writing as the "Next" step on the packaging deck, so it carries an external promise; raise it at the call if he asks. Claude to draft when reopened. |
| CON-B5 | Draft the four Waites department questionnaires (sales, business development, marketing, customer service), pre-sendable, answerable in under an hour each | Bala | 2026-08-28 | PARKED, not done. Was already blocked on Gerry confirming the engagement is moving — exactly what the call decides. Claude to draft when reopened. |
| CON-B6 | Practice-setup working session with Philip: the six open decisions (framework and offering names, pilot client and pricing, whether SKU 0 stays, who fronts the practice, marketplace channel timing, org placement) | Bala | 2026-08-28 | PARKED, not done. Parked since the Waites opportunity took over. |
| CON-B7 | Raise practice org placement and Dharma's sponsorship at the next Bala-Dharma 1-1 | Bala | 2026-08-28 | PARKED, not done. Was due 7 Sep. The practice overlaps the Chief AI Officer's domain and early blessing turns a turf risk into air cover, so reopen this one as soon as the practice is live again. |
| CON-W1 | Feedback on the service-packaging deck (how we describe/sell the service, why us) | Gerry Perkel | 2026-08-28 | PARKED, not received. Tonight's call is the venue for this answer. |
| CON-W2 | Outcome of Gerry's discussion with the Waites COO: does she want to proceed in this direction? | Gerry Perkel / Waites COO | 2026-08-28 | PARKED, not received. Tonight's call is the venue for this answer, and it is the fork the whole register hangs on. |
| CON-W3 | Staff list for internal team screening | Susan / Mency | 2026-08-28 | PARKED. Rides with CON-B2. |
