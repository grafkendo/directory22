# Directory22 — Launch Plan

AI-native local services directory, built to replicate across regions.
Region #1 is the pilot; the playbook gets cloned. Research behind this plan:
[research-brief.md](research-brief.md).

## 1. The concept

A directory of local home-service pros (plumbers, HVAC, electricians, roofers)
with two things the incumbents don't have: **exclusive leads** (no shared-lead
auction like Angi/Thumbtack) and **AI-native intake** ("my water heater is
leaking and it's Sunday" → matched pro, not a category browse).

One brand, one domain, city subdirectories from day one
(`yoursite.com/plumbers-austin/`). Every new region launches on the authority
the previous regions built — no separate domains per city.

**Positioning:** the anti-Angi. Verified pros, transparent pricing, no
pay-to-play reviews, pro-friendly economics reported as cost-per-booked-job.

## 2. Why now

- Angi is declining (1.96/5 BBB, 2,300+ complaints in 3 years, falling revenue).
  Thumbtack grows but pros hate unqualified leads and no-refund charges.
- Google lead costs rose up to 69% YoY in some trades — owned/ranked assets are
  comparatively more attractive every quarter.
- AI Overviews now appear on ~35–68% of local queries and cut clicks up to 58%
  — but AI-cited businesses convert at 6.24% vs 3.29% organic. Become the cited
  source and you get the highest-quality leads on the page.
- No AI-native home-services directory exists yet. Conversational matching +
  AI review summaries + instant booking is unowned territory.

## 3. Business model

**Primary — rank-and-rent:**
- Flat monthly rental: ~$750/mo per site/trade to one exclusive local business,
  or
- Pay-per-lead (exclusive): $75–300 depending on trade (roofing top, plumbing
  mid). Pay-per-call medians: plumbing $33, HVAC $38.50, roofing $42.

**Later layers:** featured listings, premium "AI-optimized profile" tiers
(businesses need AI-readable profiles to appear in ChatGPT/Gemini answers —
sellable), display ads at scale.

**Pricing principle:** sell on *cost per booked job*, not cost per lead.
That's the number owners decide by. Track it, report it — it's the retention
weapon. Reference points: exclusive $100 lead closing 1 in 4 → ~$400/booked
job; shared marketplace leads close ~1 in 10 → ~$600/booked job.

## 4. Tech stack

**Pilot (region #1): WordPress + GeoDirectory.**
Fastest path ($1k–5k upfront, weeks not months). GeoDirectory uses custom DB
tables so it stays fast at scale. Risk to manage: plugin sprawl and abandoned
plugins — keep the plugin count ruthless.

**By region 3–5: custom rebuild (Next.js or similar).**
$15k–50k+, total control, faster pages, and far better for the AI-native
features (conversational intake, review summarization). Spec it in parallel
with the pilot so plugin debt never compounds.

**URL structure:** subdirectories, never subdomains or per-city domains.
`yoursite.com/{service}/{city}/`. One CMS, one analytics property, one Search
Console property, all link equity compounding in one domain.

## 5. The replication playbook (the actual product)

This is what makes region #2 cheap. Non-negotiable rules per region:

1. **60%+ unique local content per page.** No city-name swaps. The Sept 2025
   spam update (SpamBrain) crushed mass-produced near-identical pages; one
   practitioner with 33,620 templated pages got only ~18% indexed.
2. **First-party proof elements:** local stats, real photos, landmarks, named
   businesses, local FAQs with specific data points.
3. **10–15 pages max at launch** (up to 35–40 only if fully proofed). Start
   with the count you can prove.
4. Self-referencing canonicals, sitemaps grouped by page type, noindex anything
   below the quality bar.
5. **Gate:** clone to the next region only after the current one has indexed
   pages AND one paying pro.

Each region ships as: niche pages (service × city) + review/UGC engine +
conversational intake + booking.

## 6. AI differentiators (ship one at launch)

1. **Conversational intake** (highest leverage): "describe your problem in
   everyday language" → AI translates to trade criteria → matched pro.
   Redfin/Realtor.com set the pattern; no home-services directory does it.
2. **AI review summaries:** pull reviews from across the web, summarize
   ("shows up on time, fair pricing, 4.6★ from 200 reviews"). Becoming table
   stakes — BestProsInTown shipped AI profiles Oct 2026.
3. **Instant booking + smart escalation:** AI chatbot books the job, escalates
   to human on uncertainty.

## 7. SEO strategy (2026 rules)

- Play the **organic** game, not the local pack (directories compete in
  localized organic: on-page + links + topical depth).
- Target **commercial-intent queries** — AI Overviews appear less there.
- Become the **cited source inside AI Overviews**: FAQ content with specific
  data points, schema markup, review velocity (80+/yr), consistent footprint
  across 15–30 sources, GBP completeness for listed pros.
- Thin service pages are dying. Topical depth + local context wins.
- Never fake addresses, never keyword-stuff business names, never fake
  reviews — Google is actively cracking down in 2026.

## 8. Brand (open decisions)

The consumer-facing brand name is TBD ("Directory22" is the repo, not the
brand). It needs: a name, palette, wordmark, and a visual system that works
at favicon size and on a billboard. Trustworthy + modern — this brand sells
trust to homeowners and ROI to pros. (Protograph's build sequence applies:
research → lock palette/type/logo → style guide → assets → site.)

## 9. Pilot: region #1

- **One metro + one trade.** Recommendation: HVAC or plumbing — high urgency,
  high lead value, year-round demand, customers call or fill forms.
- 10–15 pages, each with genuine local proof content.
- 1–3 pros signed on pay-per-lead or flat monthly.
- Report cost-per-booked-job from week one.

## 10. Timeline

| Phase | Window | Milestones |
|---|---|---|
| 0 — Foundations | Weeks 1–2 | Brand name + identity; pilot metro + trade locked; domain + hosting; WP + GeoDirectory scaffold |
| 1 — Build | Weeks 3–8 | 10–15 local-proofed pages; conversational intake v1; review pipeline; schema + speed |
| 2 — Launch | Weeks 8–12 | Indexation push; sign 1–3 pros; first leads; cost-per-booked-job reporting live |
| 3 — Replicate | Month 4+ | Region #2 only after the gate (indexed + paying pro); begin custom-rebuild spec |

## 11. Costs (rough, pilot)

Domain + hosting + WP stack: a few hundred dollars. Content (the real cost —
local-proofed pages aren't cheap to write well): budget per page. GeoDirectory
add-ons ~$229/yr. Total pilot: low single-digit thousands if content is
AI-assisted + human-proofed.

## 12. Risks

- **Google spam updates** — mitigated by the replication playbook (real local
  content, no doorway pages, no private blog networks; old rank-and-rent died
  on PBNs).
- **AI Overviews eating clicks** — mitigated by targeting commercial intent
  and becoming the cited source.
- **Proving ROI** — you only track calls/forms; mitigate with
  cost-per-booked-job reporting and call tracking from day one.
- **Chicken-and-egg** (no pros without traffic, no trust without pros) —
  mitigated by launching with free/exclusive listings for the first pros.

## 13. How it connects to the stack

- Directory **generates** the lead →
- After-hours AI agent **captures** the call →
- Protograph content engine **feeds** the SEO.
- Lead-gen factory fills gaps with outbound.

One "AI department for hire" for SMBs, four legs.
