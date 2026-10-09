# Directory Listing Site — Research Brief (Oct 2026)

Replicable multi-region directory for local service businesses (plumbers, HVAC, electricians, etc.). Region #1 is the pilot; the playbook gets cloned.

---

## 1. Rank-and-Rent / Directory Lead-Gen Models

**How it works:** build a site targeting "[service] + [city]", rank it with SEO, then monetize the inbound calls/form fills — either a flat monthly "rental" to one local business or pay-per-lead. You own the digital asset; the client rents the lead flow. (https://ippei.com/local-lead-generation-guide/)

**2026 economics (mid-year data):**
- Shared marketplace leads run ~$60 but close ~1 in 10 → ~$600 per booked job. Google Local Services Ads leads ~$53 with ~44% booking → $120–230 per booked job. Exclusive leads $75–$300; a $100 exclusive lead closing 1 in 4 → ~$400 per booked job. (https://www.youtube.com/watch?v=PjWykbvtiog)
- HomeAdvisor-style shared leads by trade: general contracting $40–90, HVAC $20–70, plumbing $25–80, roofing $50–100+, landscaping $15–50. A contractor spending $1,500/mo at 25% close pays $150–200 per booked job before labor/materials. (https://www.biondocreative.com/2026/09/angi-vs-homeadvisor-vs-thumbtack-which-lead-platform-is-worth-it-for-home-service-pros/)
- Affiliate/payout side (Lead Smart, Aug–Sep 2026, 408k leads): median payouts per qualified call — water damage $201–213, roofing CPL $130, plumbing CPL $44.50–48, HVAC pay-per-call $38.50, plumbing pay-per-call $33.25, electrical ~$23–24.50. These are what publishers get paid — a floor reference for pricing your own leads. (https://markets.financialcontent.com/newsok/article/prunderground-2026-8-20-lead-smart-publishes-payout-data-on-408398-home-service-leads-as-google-reshapes-local-ads)
- Google lead costs rose up to 69% year-over-year in some trades (appliance repair) — rising paid-lead costs make owned/ranked assets more attractive by comparison. (https://www.wdfxfox34.com/online_features/press_releases/lead-smart-inc-google-lead-costs-rose-up-to-69-in-a-year-what-the/article_9fb8a834-24a0-5fd9-809b-d4daf03087b0.html)
- Classic rank-and-rent example: one flat monthly fee (~$750/mo cited) for all exclusive leads a site generates; practitioners report portfolios of 50+ sites producing ~$52k/mo. Treat guru income claims with skepticism, but the unit economics are real. (https://ippei.com/local-lead-generation-vs-dropshipping/)

**Niche selection matters:** home services (plumbing, HVAC, roofing) are ideal because customers call or fill forms. Weigh service frequency, average ticket, seasonality, and licensing requirements. (https://ippei.com/local-lead-generation-guide/)

**Risks:** rank-and-rent traditionally relied on private blog networks (PBNs) for backlinks — if Google flags the network, income can vanish overnight. Also, you only track calls/forms, so proving the client's true ROI takes work. (https://ippei.com/rank-and-rent-club/)

---

## 2. Local SEO in 2026

**Google's core triad is unchanged:** relevance, distance, prominence. (https://cited.so/blog/google-maps-ranking-for-service-businesses)

**What carries weight (Whitespark Local Search Ranking Factors, Nov 2025, ~130 practitioners):** for the local pack — Google Business Profile signals 32%, reviews 20%, on-page 15%, behavioral 9%, links 8%, citations 6%. For localized *organic* results (where directory pages compete), on-page signals and links carry substantially more weight: dedicated service pages, geographic relevance, inbound links, internal linking, title/heading optimization. (https://valveandmeter.com/blog/local-seo/local-seo-ranking-factors/ · https://cubecreative.design/blog/small-business-marketing/seo-vs-geo-local-search-home-service)

**Key rules:**
- GBP primary category is the single most impactful field; complete profiles + review quantity *and* velocity dominate. Never fake an address — suspension risk, and it doesn't durably work. (https://cited.so/blog/google-maps-ranking-for-service-businesses · https://github.com/ahmedzarif-ops/cut/blob/HEAD/.claude/skills/local-seo/SKILL.md)
- Local pack and organic are *different competitions* — an HVAC company can own Maps near its shop but need organic pages to cover the metro. A directory plays the organic game. (https://valveandmeter.com/blog/local-seo/local-seo-ranking-factors/)

**AI Overviews / AI search — the big 2026 shift:**
- AI Overviews appear on roughly 35–68% of local queries (estimates vary by study); top-ranking pages lose up to 58% of clicks when one appears (Ahrefs, Feb 2026); Seer measured CTR falling 1.76% → 0.61%. (https://www.einpresswire.com/article_pdf/899690993/dallas-seo-expert-why-local-businesses-are-losing-up-to-58-of-their-search-traffic-to-ai-results)
- The flip side: AI citations convert at 6.24% vs 3.29% for traditional organic — AI-referred visitors are the highest-quality leads available. Overviews surface only ~32% as many businesses as the old 3-pack, and proximity no longer correlates with AI visibility — trust signals do. (https://pushleads.com/google-ai-overviews-local-contractors-why-your-google-ranking-is-a-vanity-metric/)
- Control signals for AI inclusion: GBP completeness, review velocity (80+/year cited), schema markup, consistent footprint across 15–30 sources, FAQ content with specific data points and clear structure. (https://pushleads.com/google-ai-overviews-local-contractors-why-your-google-ranking-is-a-vanity-metric/ · https://growthproai.com/blog/google-ai-overviews-local-business-guide-2026)
- Strategy: target commercial-intent queries (Overviews appear less often there) and make your pages the *cited source* inside the Overview. Thin service pages are dying; topical depth + local context wins. (https://growthproai.com/blog/google-ai-overviews-local-business-guide-2026 · https://www.linkedin.com/pulse/local-seo-2026-strategies-make-you-unstoppable-google-toheed-bscyf)
- Google is also cracking down on keyword-stuffed business names and fake reviews in 2026 — clean profiles are the baseline. (https://ad-hoc-news.de — via search results)

---

## 3. Multi-Region Architecture

**URL structure — use subdirectories.** 2026 consensus is clear: `yoursite.com/plumbers-austin/` consolidates all link equity into one domain; Google treats subdomains as semi-separate sites that must build authority independently. Subdirectories = one CMS, one analytics property, one Search Console property, cheapest to operate. (https://seomator.com/blog/subdomain-vs-subdirectory · https://theguidex.com/insights/subdomain-vs-subdirectory · https://github.com/craftos-dev/craftbot-agent-bundles/blob/HEAD/agents/l10n/skills/locale-routing-subdomain-subdirectory/SKILL.md)

Note: classic rank-and-rent used separate exact-match domains per city (e.g. napervillecommercialroofing.com). That still works for single-asset plays, but for a *branded, replicable directory*, one domain with city subdirectories compounds authority across every region you add — each new region launches on the back of the last one's links.

**CMS / tech stack:**
- **WordPress + GeoDirectory** (free core, 10k+ installs, 4.8/5; stores listings in custom DB tables so it stays fast at scale; $229/yr for add-on bundle): fastest pilot launch, $1k–5k upfront, cheap hosting. Risk: plugin sprawl slows the site and each abandoned plugin is a security hole. (https://athemes.com/reviews/geodirectory-plugin-review/ · https://weetechsolution.com — via search results)
- **Custom (Next.js etc.):** $15k–50k+, months of dev, total control, faster pages, no plugin maintenance — and far better for AI-native features (conversational matching, instant booking). (https://medium.com/@samshtechtechnologies/custom-website-vs-wordpress-which-is-better-2026-guide-21eabeced55a)
- **Recommendation:** WordPress + GeoDirectory for the region-1 pilot (speed to market), plan the custom rebuild once the template is proven — ideally by region 3–5, before plugin debt compounds.

**Avoiding duplicate-content / doorway problems:**
- There is no literal "duplicate content penalty" — the risk is classification as *doorway pages* or *scaled content abuse*. Google's Sept 2025 spam update (SpamBrain upgrade) specifically targeted mass-produced near-identical pages; cookie-cutter city pages saw sharp visibility drops. (https://www.hostpapa.com/blog/marketing/does-duplicate-content-hurt-seo/)
- Practitioner data: a 33,620-page templated programmatic site got only ~18% of pages indexed. Hand-writing 80–120 words of genuinely region-specific content for top pages lifted indexation 15% in six weeks. (https://github.com/automatable-skool/seo-blueprint-day1/blob/HEAD/references/doorway-pages.md)
- Playbook per region page: 60%+ unique local content; first-party proof elements (local stats, real photos, landmarks, named businesses); self-referencing canonicals; sitemap grouped by page type; noindex anything below the quality bar. Whitespark guidance: 10–15 city pages max if lightly differentiated, up to 35–40 if fully proofed — start with the count you can prove. (https://workhacker.com/blog/multi-location-seo · https://github.com/efraijo/operator-seo-skill/blob/HEAD/skills/technical/seo-programmatic/SKILL.md)

---

## 4. Monetization

| Stream | Typical price points (2026) |
|---|---|
| Monthly rental (rank-and-rent) | ~$750/mo per site/trade to one exclusive business |
| Pay-per-lead (exclusive) | $75–300/lead depending on trade (roofing top end) |
| Pay-per-call | $23–42/call median by trade (plumbing $33, HVAC $38.50, roofing $42) |
| Shared-lead marketplaces (comp) | $15–85/lead (Angi), $3–30+ credits (Thumbtack), $200–550/mo ad tiers (Angi) |
| Featured listings / tiers | Standard directory fare — price against local ad spend |
| Display ads | Remnant revenue; don't lead with it |

Sources: https://ippei.com/local-lead-generation-vs-dropshipping/ · https://www.biondocreative.com/2026/09/angi-vs-homeadvisor-vs-thumbtack-which-lead-platform-is-worth-it-for-home-service-pros/ · https://markets.financialcontent.com/newsok/article/prunderground-2026-8-20-lead-smart-publishes-payout-data-on-408398-home-service-leads-as-google-reshapes-local-ads · https://adaptdigitalsolutions.com/articles/homeadvisor-vs-angieslist-vs-houzz-vs-porch-vs-thumbtack-vs-yelp-vs-bark/

**Pricing principle:** sell on *cost per booked job*, not cost per lead — that's the number that decides the channel for the business owner. Track it and report it; it's your retention weapon. (https://www.youtube.com/watch?v=PjWykbvtiog)

---

## 5. AI-Native Directory Features

- **Conversational matching:** Redfin launched Conversational Search (Nov 2025) and Realtor.com added natural-language property search — buyers describe wants in everyday language, AI translates to criteria. Same pattern applies to "my water heater is leaking and it's Sunday" → matched pro. No major home-services directory does this yet. (https://www.biz4group.com/blog/ai-residential-property-marketplace-development)
- **AI review summarization & trust:** BestProsInTown (1M+ businesses, 10M reviews) launched AI search-optimized business profiles in Oct 2026 and has run AI fake-review detection since 2020. Review summarization is becoming table stakes. (https://www.einpresswire.com/article/947991049/bestprosintown-launches-ai-search-optimized-profiles-for-home-service-businesses)
- **Smart matching + booking:** NLP matching of poorly-written requests to pro specialties, AI chatbots handling booking/rescheduling/FAQs with intelligent escalation to humans. (https://medium.com/@tysonpaul001/how-ai-is-shaping-the-future-of-home-service-apps-smarter-scheduling-smarter-homes-0149750494f8)
- **AI visibility as an upsell:** businesses now need AI-optimized profiles to appear in ChatGPT/Gemini answers — a directory could sell "AI-search optimization" of listings as a premium tier. (https://www.novaadvertising.com/ai-search-home-service-businesses/)

**Bottom line:** the AI-native home-services directory doesn't exist yet. Conversational intake + AI review summaries + instant booking is a genuine differentiator, not a gimmick.

---

## 6. Competitive Gaps

| Platform | Standing (2026) | Core complaints |
|---|---|---|
| Angi | BBB 1.96/5; 2,300+ complaints/3 yrs; declining revenue | False/outdated leads, unexpected fees, poor-quality pros, $1,400+ effective cost per booked job reported |
| Thumbtack | Growing 33% YoY; Trustpilot 3.0, Sitejabber 1.8 | Unqualified leads, charges for inquiries that never book, near-impossible refunds — pros feel "same playbook" as HomeAdvisor |
| Yelp | Trustpilot 1.3/5; flat growth | $2–20 CPC, $150+/mo minimums; review-filter distrust; historically adversarial business relationships |
| Google LSA | Dominant, expanding | $25–162/lead by trade; works but not infinitely scalable; you rent, never own |

Sources: https://adaptdigitalsolutions.com/articles/homeadvisor-vs-angieslist-vs-houzz-vs-porch-vs-thumbtack-vs-yelp-vs-bark/ · https://www.topconsumerreviews.com/best-contractors/reviews/angi · https://www.consumeraffairs.com/homeowners/thumbtack.html?page=2

**Where homeowners actually come from:** word-of-mouth 73–79%, Google search 39–62%, home-services sites ~34%. 91% check reviews before hiring; referrals convert 50%+. (https://adaptdigitalsolutions.com/articles/homeadvisor-vs-angieslist-vs-houzz-vs-porch-vs-thumbtack-vs-yelp-vs-bark/)

**The openings:**
1. **Trust:** verified pros, no pay-to-play review manipulation, transparent pricing — the anti-Angi position.
2. **Exclusive leads:** every shared-lead complaint is a selling point for a directory that gives a lead to *one* pro.
3. **Pro-friendly economics:** the incumbents extract; a directory that proves cost-per-booked-job wins loyalty.
4. **AI matching:** nobody owns conversational intake in home services yet.
5. **Own the asset story:** "stop renting leads from Angi; rent a cheaper, exclusive stream from us — or buy the playbook." (Meets owners where they are.)

---

## Pilot Recommendations (Region #1)

1. One metro + one trade (HVAC or plumbing — high urgency, high lead value, year-round demand).
2. Branded domain, `/{service}/{city}/` subdirectories from day one.
3. WordPress + GeoDirectory for the pilot; spec the custom rebuild in parallel.
4. 10–15 pages max at launch, each with genuine local proof content — no city-name swaps.
5. Monetize with 1–3 pros on pay-per-lead or flat monthly; report cost-per-booked-job.
6. Ship one AI differentiator at launch (conversational intake is the highest-leverage pick).
7. Clone the template to region #2 only after region #1 has indexed pages and a paying pro.
