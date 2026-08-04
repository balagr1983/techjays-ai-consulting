# Techjays AI Consulting Practice - Working Context

> Living context anchor for the AI Consulting wing initiative. Maintained by Claude Code and
> updated as new transcripts, research, and drafts arrive. Everything in this repo is tracked
> and pushed to GitHub as backup.
> Last updated 17 Jul 2026 after the market research sweep: research documents live in
> `Research/`, roadmap draft v0.1 in `Offering/roadmap.md`. Prior milestone, 16 Jul 2026
> call: **decision aligned to launch an AI consulting practice inside Techjays**, offering
> pre-study and operational-readiness services.

---

## 1. What this project is

An initiative by **Philip Samuelraj** (Techjays leadership) and **Bala (Balasubramanian GR)**
to stand up a dedicated **AI Consulting practice inside Techjays**. The practice sells paid
pre-study, opportunity-identification, and AI-readiness engagements to clients who want to
know "where we are and what we should do" before committing to an AI build.

## 2. Story so far

- **Early Jul 2026 (first call, exact date not captured):** Philip proposed the AI consulting
  wing idea. Bala's top-of-mind suggestion: package it as an **Audit report**. Philip's market
  signal: many customers he spoke to wanted someone to tell them what to do and where they
  stand before acting. The two ideas fit together. Left off at the "AI audit" concept.
- **Between calls:** Bala analyzed the market and found the Big Four and large consulting
  firms have already made AI advisory a focus and have consulted on many such projects. This
  raised the differentiation question: what is different about a Techjays offering?
- **16 Jul 2026 call:** Most of the differentiation doubts answered (see section 4). Aligned
  on launching the practice. Transcript in `Transcripts/`.
- **17 Jul 2026:** Deep market research sweep completed (107-agent verified web research).
  Key results: the fixed-fee 4 to 8 week assessment is an established, purchasable market
  format; a named scoring framework is table stakes at every tier; PwC is the most
  productized big-firm example (12 domains, 0-100 score); West Monroe already markets the
  builder-advisor combination; the only verified public price is a boutique at USD 15,000
  to USD 25,000 for 4 weeks, leaving the mid-market fee band undocumented (peer interviews
  to fill it). Full findings in `Research/`; roadmap draft v0.1 in `Offering/roadmap.md`.
- **28 Jul to 4 Aug 2026:** **Sales packaging cycle completed.** Gerry called the
  approach doc "a great first pass", took it to the Waites COO as a direction test, and
  asked how we describe/sell the service and why clients should choose us. Built the
  service packaging (one-liner, pitch, seller toolkit, why-us; `Offering/service-packaging.md`),
  verified the MIT NANDA and McKinsey stats against sources (deck-safe), and produced
  the deck through three format iterations (HTML, NotebookLM, then the Techjays house
  style per Dharma's design system, which shipped in the updated doc plugin 0.2.0).
  Philip approved direction and rate on the way through; format approved by Philip and
  Dharma; content verified before send. **Deck sent to Gerry 4 Aug
  (`Offering/Service_Packaging_Deck_V2.pptx`). Now waiting on Gerry: deck feedback and
  the COO-discussion update.** Tooling unblocked along the way: Node + pptxgenjs and
  Python 3.12 + PDF/Office libraries now installed; /doc:deck pipeline functional.
- **22 Jul 2026:** **First inbound opportunity, scoped in principle on the Gerry Perkel
  call.** Waites (waites.net; ~200 people, ~USD 50 million revenue, predictive
  maintenance): ~6-week onsite process re-architecting study of sales, BD, marketing,
  and customer service (software dev excluded), prioritized agentic-AI roadmap as the
  deliverable, USD 40,000 to 50,000, likely ~Sep start (end-September decision deadline;
  Gerry + COO chartered to deliver a roadmap by end of year to double revenue per
  white-collar employee). Gerry coaches Techjays, Northstar, AND Waites - he is the
  16 Jul transcript's "Jerry", and says many of his clients need the same thing: this is
  the pilot for the practice AND the test of the CEO-coach channel. Bala owes Gerry a
  proposal + questionnaire and a follow-up call by end of week / early next week.
  Full detail: `Prospects/Waites/waites-brief.md`.
- **21 Jul 2026:** Second research pass done. Closed the packaging picture for Deloitte
  (agentic readiness assessment, digital-channels scoped), EY (free 15-minute EY.ai
  Maturity Model, 7 dimensions, lead-gen play), Bain (AI Deployment Matrix 2x2
  diagnostic opening strategy engagements, buy/build/partner framing), and IBM
  (week-sized fixed-scope Advise SKUs on AWS Marketplace, retired self-serve quiz,
  four-tier ICA4CT engagement ladder). BCG still dark after two passes. No disclosed
  dollar fees found anywhere (all marketplace SKUs price via private offer), and the six
  buyer-survey statistics remain unverified - not deck-safe yet. Strawman package
  (framework, SKU one-pagers, report ToC) and Philip update draft also completed today.
- **17 Jul 2026:** Received IIT Madras Walmart Center for Tech Excellence brochure (via
  Bala's friend at the CoE) - MSME manufacturing analytics: productized platforms +
  subsidized channel (FaMe TN) + skilling. Different segment, but reinforces three
  patterns: reusable delivery assets, ecosystem co-funding of the client's cost, and
  training as a packaged line. Summary in `Research/iitm-wcte-summary.md`.

## 3. Why clients would buy (demand signals from Philip)

Clients fall into two buckets:
1. **Come with a defined problem or PoC** (e.g. a client team arrived with a deck and proof
   of concept). Techjays already monetizes this via a **paid 6-week, USD 60,000 discovery
   phase** that captures requirements and produces the cost.
2. **Know AI matters but do not know where to start.** Boards push CEOs toward the big
   management-consulting firms; some CEOs explicitly do not want that route because they
   would pay a huge price for abstract strategy with no execution behind it.

Every engagement ties to three client goals:
1. **Increase revenue**
2. **Increase margin** through cost savings
3. **Improve client experience**

Market anecdotes (from Philip, 16 Jul):
- A client paying around USD 250,000 per year for an application that is effectively the
  nervous system of a USD 400 million company; the follow-on enterprise-readiness
  opportunity could be worth around USD 500,000.
- CEOs have told Philip: "if I work with you, you will find me something valuable and help
  me build it, because you have skin in the game." Even an ex-strategy-consultant CEO in his
  network sees this.

## 4. Positioning and differentiation (the answer to the Big Four question)

The big firms do offer similar AI studies, but Techjays differentiates on:
1. **Cost:** the big firms charge roughly 4 to 5 times what Techjays would charge for the
   same study; quality of work is comparable in our view.
2. **Skin in the game:** Techjays not only advises on strategy but can execute and build the
   recommended solutions. Pure strategy consultants cannot.
3. **Actionable over abstract:** high-ROI, low-cost, actionable implementation plans rather
   than high-fee abstract strategy decks.

**Risk to manage (raised by Bala):** because Techjays can also build, clients may perceive a
bias in the advice ("you will recommend building because you build"). This line has to be
tread carefully in positioning and in the reports themselves.

## 5. Offering shape (initial thinking, 16 Jul)

1. **AI opportunity identification study:** work with the client team for about 8 weeks
   (roughly USD 100,000 to USD 150,000). Identify AI opportunities across the business, plot
   them on a **2x2 matrix of ROI vs cost**, stack-rank them, and hand over a prioritized,
   actionable plan. Techjays can then optionally deliver the top items.
2. **AI pre-readiness study:** map the client's entire business process and operations to the
   tiniest detail as a standalone service, about 8 weeks, around USD 150,000.
3. **Existing foundation:** Techjays **Design and Discovery (DND)** engagements are already
   quasi-consulting (study current systems, reimagine, AI-enable, automate). Re-narrate and
   re-present DND as the pre-study consulting engagement rather than inventing a new
   delivery motion from scratch.

Open packaging questions: naming/terminology (what do the big firms call these studies and
how does the market react), sales positioning, cross-selling into delivery, team/hiring plan.

## 6. Decisions log

| Date | Decision |
|------|----------|
| 16 Jul 2026 | Establish an AI consulting practice within Techjays offering pre-study and operational-readiness services. Aligned by Philip and Bala. |
| 16 Jul 2026 | Build on the DND motion (rebrand/re-narrate) rather than inventing a separate delivery model. |

## 7. Action items

| # | Owner | Item | Status |
|---|-------|------|--------|
| 1 | Bala | Research AI consultancies through leadership network: what consulting engagements they ran, what reports/studies they received before implementing AI, and the methodologies used. Report back to Philip in a few days. Question set ready in `Research/peer-interview-questions.md`; prioritize real fees (Q7) and builder-bias perception (Q8). | Open |
| 2 | Bala | Identify potential hires from personal network interested in the AI consulting practice. | Open |
| 3 | Bala + Philip | Schedule a follow-up call to develop the practice strategy (positioning, terminology, selling motion, team). Roadmap draft v0.1 ready as the agenda backbone. | Open |
| 4 | Bala | Study how the big firms sell these engagements: terminology, packaging, market reaction. | Done 17 Jul 2026 - see `Research/competitive-teardown.md` |
| 5 | Claude | Second research pass: BCG X, Bain, Deloitte, EY, IBM Consulting packaging + targeted procurement-records hunt for real assessment fees + verify the buyer-survey figures before client-facing use. | Done 21 Jul 2026 - 4 of 5 firms closed (BCG still dark); no disclosed fees found; buyer stats still unverified |
| 6 | Bala | Send the Philip update (draft in COMMUNICATIONS.md) and book the working session. | Open |
| 7 | Claude | Dedicated verification pass on the six buyer-survey statistics before any client-facing deck (Phase 2 gate). | Open |
| 8 | Bala + Claude | Waites proposal for Gerry: discovery process, 6-week plan, deliverables, projected gains, pilot-priced at USD 40,000 to 50,000 (framed as founding-client pricing to protect the list-price anchor). Due before the follow-up call (end of week / early next week). | Open |
| 9 | Bala + Claude | Waites assessment questionnaire for sales, BD, marketing, customer service (pre-sendable). | Open |
| 10 | Bala | Brief Philip on the Waites opportunity and Gerry call; align pricing framing. | Done - approach doc and packaging deck both approved (23 and 31 Jul) |
| 12 | Bala + Claude | Packaging deck rebuilt to the Techjays Proposal Style Guide per Philip's 31 Jul feedback (bigger type, traditional deck format, Google Sans). Review with Dharma, then send to Gerry with the drafted email. | Open |
| 11 | Bala | Get the staff list from Susan or Mency for team screening; extend to US network for a stateside delivery resource (Gerry's hint). | Open |

## 8. People

- **Philip Samuelraj** - Techjays leadership; originator of the practice idea; owns client and
  CEO-network relationships.
- **Bala (Balasubramanian GR)** - PM at Techjays; drives research, packaging, and hiring
  intelligence for the practice.

## 9. Repo map

```
Consulting_Stuff/
  CONTEXT.md            <- this file, the living context anchor
  COMMUNICATIONS.md     <- log of key messages/emails once outreach starts
  README.md             <- repo purpose and structure
  Transcripts/          <- call transcripts (PDF originals + extracted text)
  Research/             <- research-plan, competitive-teardown, pricing-benchmarks,
                           frameworks-and-methodologies, buyer-demand-signals,
                           peer-interview-questions
  Offering/             <- roadmap.md + roadmap-deck.html, framework-strawman,
                           sku-one-pagers, report-template-toc, team-plan
  Prospects/            <- one folder per live opportunity (first: Waites, via Gerry
                           Perkel / CEO Coaching)
  Notes/                <- working notes that do not fit elsewhere
```

## 10. House style (applies to all documents here)

- No em dashes or en dashes in any document.
- Money always as USD 150,000 style, never "150K".
- Company name is **Techjays** (transcripts may garble it as "TechJS").
- Client-facing times in EST.
