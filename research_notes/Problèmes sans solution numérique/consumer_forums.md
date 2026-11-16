# Recurring everyday consumer problems with "no good app yet": evidence from forums and app markets

> **Method caveat (read first):** In this session, reddit.com was blocked for the search tool ("domain not accessible to our user agent"), and fetching news.ycombinator.com and its mirrors (hn.svelte.dev, hn.nuxt.dev) failed with DNS errors. So **no Reddit thread could be opened, and no upvote or comment counts could be verified**. The evidence below comes from search-engine summaries of HN thread titles, app-store listings and reviews, community forums (CHOICE Community, Beancount forum), news coverage, and comparison blogs. Many of those blogs are **written by competing vendors**; they are flagged as such. The report writer should not present any item as "N upvotes on r/X". Where demand evidence is weak, the gap is stated explicitly.

## Which "is there an app for…" requests recur, and what is the evidence of demand?

### Takeaway
Many classic "somebody make this" ideas are already crowded with apps: home inventory and warranties, lent-item trackers, personal CRMs, chore apps, and group-trip planners. They are not unsolved. The stronger cases are problems where a **good incumbent was killed, crippled or paywalled** (Mint, Stocard, Splitwise's free tier, Facebook Events/Local, the Komae babysitting co-op). Also strong are problems that need **cross-silo aggregation**: local events across Luma, Partiful, Eventbrite and Meetup; grocery prices across chains; a group-trip workflow spanning decide, plan and pay; and parents' school and club email overload.

### Cited Findings
**Meta-evidence on "wish there was an app" threads**
- Idea-mining guides list "Is there an app for", "Why doesn't X exist" and "I wish I could" as the standard pain-point phrases on Reddit. One guide cites an unverified r/personalfinance example about splitting roommate expenses ("Living with roommates and splitting expenses is a nightmare") — [generateideas.app](https://www.generateideas.app/blog/find-app-ideas-reddit) (secondary; original post not verified)
- A wiki-style page says one analysis covered over 9,300 "I wish there was an app for this" Reddit posts, with most posted on Mondays and Tuesdays. Treat this figure as low-reliability — [Grokipedia](https://grokipedia.com/page/Reddit_posts_wishing_for_websites_or_web_apps)
- HN thread "Ask HN: What do you wish existed? (October 2025)" exists. The visible comments in the search summary were mostly tech-oriented (a Genode OS daily driver, phone and Android emulation), not consumer life. Points and comment count are unverified — [HN mirror](https://hn.svelte.dev/item/45500937)
- HN thread "Ask HN: What do you still do manually in 2026 that should be automated?" (about May 2026). Consumer-relevant reply: still sorting the photo gallery by hand, especially screenshots and downloads. Most other replies were work tasks — [HN](https://news.ycombinator.com/item?id=48045237)
- Older (2024) consumer wish lists on MetaFilter include a good adding-machine app and a "conspiracy wall" infinite-canvas app — [Ask MetaFilter](https://ask.metafilter.com/382602/What-desktop-app-phone-app-or-website-do-you-wish-existed)
- Cautionary data point from Indie Hackers: a receipt and warranty app for "sharing receipts with family" drew about 6,000 views and 30+ comments, mostly negative ("This is just emotional marketing for your app"). Stated demand does not equal willingness to pay — [Indie Hackers search summary](https://www.indiehackers.com/post/i-wasted-months-building-things-nobody-wanted-66eec1cc5b) (the exact post URL is uncertain; it came via a search summary)

**Candidate 1: Loyalty-card wallet after Stocard was absorbed into Klarna (strong, recent "killed incumbent" signal)**
- Klarna acquired Stocard (2021) and folded it into the Klarna app. Sources disagree on the timeline: migration notices from about Oct–Nov 2024, the app gone from stores by mid-2025, and a final shutdown about March 2026 with a two-week migration window — [CHOICE Community thread (p.3)](https://choice.community/t/stocard-being-replaced-by-klarna-app/33022?page=3); [Vamers, 20 Mar 2026](https://vamers.com/2026/03/20/klarna-stocard-barcodes-loyalty/); [ScanKeeper (vendor)](https://scankeeper.app/klarna-stocard-loyalty-cards/)
- User complaints:
  - Klarna requires a full account where Stocard was optional, so being locked out of Klarna means losing your cards.
  - No Apple Watch support.
  - Cards no longer work offline.
  - Custom sorting and location-based suggestions are gone.
  - No data export.
  - Some migrations failed and lost card data.

  Sources: [CHOICE Community](https://choice.community/t/stocard-being-replaced-by-klarna-app/33022?page=3); [CardWarden founder post (vendor)](https://cardwarden.app/blog/why-i-built-cardwarden); [RCards (vendor)](https://rcards.net/blog/stocard-alternatives/)
- Alternatives already exist:
  - SuperCards (reportedly from the original Stocard team; free, no account).
  - Catima (free and open source).
  - Apple Wallet plus converters (Pass2U, NeatPass, MakePass).
  - Several new indie apps: CardWarden, PerkPocket, ScanKeeper.

  Sources: [AlternativeTo](https://alternativeto.net/software/stocard); [NeatPass (vendor)](https://neatpass.app/learn/stocard-alternative); [PerkPocket guide (vendor)](https://cohesionbrew.com/apps/perkpocket/guides/stocard-alternative.html)

**Candidate 2: Mint replacement: free, all-in-one budgeting (strong demand, solved only by paid apps)**
- Intuit shut down Mint (2024). The direct paid replacements are Monarch (about $99.99/yr) and YNAB (about $109/yr). Free options are narrower: Empower (investments, basic budgeting) and the Rocket Money free tier — [financialaha](https://www.financialaha.com/articles/mint-alternatives-after-shutdown/); [financeapps.guide](https://www.financeapps.guide/guides/mint-shutdown-best-alternatives-2026/); [Beancount forum "Life After Mint"](https://beancount.io/forum/t/life-after-mint-finding-the-right-alternative-for-your-financial-style/99)
- Regional limits: Monarch's bank linking is North America only; YNAB covers North America, the UK and much of Europe — [spendandinvest](https://spendandinvest.com/blog/mint-alternative-2026)
- A niche of "own your data / no bank login" tools has emerged (statement upload instead of aggregation) — [bankstatementgenie (vendor)](https://bankstatementgenie.com/blog/best-mint-alternatives)

**Candidate 3: Expense splitting without the Splitwise free-tier cap (strong complaint, but many alternatives)**
- Splitwise's free tier caps new expenses per day. The number is unpublished; users report 3–5, with 3–4 the most common. Pro features include receipt scanning, currency conversion and charts. Pro price is reported as $4.99/mo, about $40/yr, or $59.99/yr; sources conflict — [hipposplit "what Reddit says" (vendor)](https://hipposplit.com/blog/splitwise-review/); [splitwin (vendor)](https://splitwin.app/blog/splitwise-daily-expense-limit/); [getfinny (vendor)](https://getfinny.app/blog/best-splitwise-alternatives-2026)
- Free alternatives without a cap: Tricount (now owned by bunq), Splid, Spliit (open source). Settle Up has some caps and ads — [splitfast (vendor)](https://splitfast.io/blog/splitwise-alternatives); [criaplanner](https://criaplanner.com/guides/splitwise-alternatives)
- At least 8 competing vendors publish "Splitwise alternative" SEO pages. That is evidence of demand, and also evidence that the market is already saturated.

**Candidate 4: Local events / "what's on this weekend" discovery (recurring, structurally unsolved)**
- Facebook Events became Facebook Local (2017), which was deprecated in early 2021 — [AlternativeTo](https://alternativeto.net/software/events-from-facebook/about). Even in 2016 the standalone Events app ranked only about #250–500 in US social apps — [TechCrunch](https://techcrunch.com/?p=1427049)
- Events are now split across silos: Luma (tech/founders), Partiful (social invites, US-centric), Eventbrite (ticketed), Meetup (interest groups). Third parties sell scrapers (Apify actors) that merge these into one deduplicated city feed, which implies no consumer aggregator fills the gap — [Apify event scraper](https://apify.com/avinashchby/event-scraper); [Apify city finder](https://apify.com/northloop-labs/tech-events-finder)
- A vendor built on Luma claims Luma discovery is weak outside hub cities and that most Luma events never appear on its featured page. This is self-interested and the figure is unverified — [Hidden Events (vendor)](https://hiddenevents.online/blog/luma-vs-meetup-vs-eventbrite-vs-partiful/)
- Older academic framing (2017): "sites exist to assist us in choosing venues and services, [but] there is a lack of similar resources to help us find local social activities and events" — [Berkeley MIDS capstone](https://www.ischool.berkeley.edu/projects/2017/eventdilly-lets-get-out-there) (old evidence)

**Candidate 5: Group trip planning, a single flow for decide → plan → pay (crowded but fragmented)**
- Wanderlog has itineraries but no voting or way to resolve disagreement, and only basic expenses. Troupe "handles group voting but stops at the decision phase". Splitwise is money-only. Newer entrants each miss one leg: TripRelay (voting + itinerary, no expenses), Limbo (voting with deadlines, no cost splitting), TripRiot (votes + plan lock) — [tripriot comparison, Nov 2026 (vendor)](https://tripriot.com/compare/group-trip-planner-apps/); [triprelay (vendor)](https://triprelay.app/blog/best-group-trip-planning-apps); [getlimbo (vendor)](https://www.getlimbo.app/best-group-trip-planner-apps); [bangertrip (vendor)](https://www.bangertrip.com/en/blog/best-group-trip-planner-apps-2026)
- Reviews say groups end up deciding back in the group chat, and that participants drop off if the first vote is hard to find (onboarding friction) — [tripprof](https://tripprof.com/en/blog/best-group-travel-planning-apps/); [weplanify (vendor)](https://www.weplanify.com/en/alternatives/best-group-trip-planner-apps)
- Note: at least 10 vendors published "best group trip planner 2026" comparisons. The category is a crowded red ocean; the problem is persistent fragmentation, not missing apps.

**Candidate 6: Parents drowning in school, club and sports emails (active, many new AI entrants, unproven)**
- 2025–2026 entrants that parse school and club emails into a family calendar: Honeycomb (AI extracts dates from school/club emails), Sense (forward emails; also chores and allowance), Sync School Events (pushes to Google Calendar), Parentr (polls, RSVPs, volunteer sign-ups). Most have few or no ratings — [Honeycomb](https://apps.apple.com/app/id1507430402); [Sense](https://apps.apple.com/app/id6739470108); [Sync School Events](https://apps.apple.com/us/app/sync-school-events/id6757267528); [Parentr](https://apps.apple.com/us/app/parentr-family-organizer/id6503667022)
- School-run portals (Sentral, ParentMail, eClass) depend on the school subscribing and add yet another login — [Sentral flyer](https://bossleypk-h.schools.nsw.gov.au/content/dam/doe/sws/schools/b/bossleypk-h/download-box/A5_Sentral-for-Parents-App_Flyer_FNL.pdf); [iris ParentMail](https://apps.apple.com/ie/app/iris-parentmail/id937274547)

**Candidate 7: Babysitting co-ops / childcare swaps between trusted parents (repeated failure of businesses)**
- Komae (points-based babysitting exchange) reached about 19,000 accounts but announced a shutdown in 2019 because "the business wasn't working out". It was rescued by Wana Family Network and made free. The latest Facebook notice says it is retiring and points users to Carefully (undated) — [Working Woman Report](https://workingwomanreport.com/komae-babysitting-app-saved-new-parent/); [Komae Facebook](https://www.facebook.com/mykomae/mentions/); [JHU Hub, 2020](https://hub.jhu.edu/at-work/2020/09/11/komae-cooperative-care-app/)
- Local news shows parents still starting informal co-ops by hand — [10News San Diego](https://www.10news.com/news/making-it-in-san-diego/making-it-in-san-diego-mom-starts-co-op-for-free-babysitting-between-friends)

**Candidate 8: Cross-store grocery price comparison (US) (hard data problem; services close)**
- Flipp (weekly flyers), Basket and Grocery Dealz exist. Chain apps are deep on one store and useless across stores — [groceriestracker (vendor)](https://groceriestracker.com/blog/best-grocery-price-comparison-apps-2026); [grocerychop (vendor)](https://grocerychop.com/blog/best-app-to-compare-grocery-prices)
- PriceSnap says it stopped grocery product search, receipt scanning and basket pricing in November 2026 — [PriceSnap](https://www.pricesnap.ai/grocery-price-comparison)
- Unit pricing is not mandatory everywhere (Canada example), so apps have to compute it — [CBC](https://www.cbc.ca/lite/story/1.6580728)

**Candidate 9 (borderline): Organizing screenshots and the camera roll**
- Raised in the 2026 HN "still do manually" thread (sorting gallery screenshots and downloads) — [HN](https://news.ycombinator.com/item?id=48045237). No additional demand evidence was gathered; existing tools such as Google Photos and Apple Photos search were not checked in this session.

**Checked and found NOT unsolved (keep out of the "no solution" list)**
- **Home inventory / warranty / receipts:** many apps — Itemtopia (free, ad-free), Stowly (free web, insurance PDF), Manifest (AI extraction from photo or forwarded receipt), Warranty Shelf, OwnThis, Habitalog. Most have few reviews, so no dominant player, but the category is not empty — [Itemtopia](https://apps.apple.com/ca/app/itemtopia/id952405279); [Stowly](https://alternativeto.net/software/get-stowly/about/); [Manifest](https://alternativeto.net/software/manifest-home-inventory-app/about/); [Warranty Shelf](https://apps.apple.com/app/id6502906534)
- **Tracking items lent to friends:** Borrow, LendPal (4.1★, 645 ratings), Kashikalist, BorrowHub, The Give-Back Log (June 2026), LendingLogTracker — [LendPal](https://apps.apple.com/app/id894350470); [Borrow](https://apps.apple.com/us/app/borrow/id885644065?uo=4); [Give-Back Log](https://apps.apple.com/app/id6767269640)
- **Personal CRM for friends and family:** Monica (open source, self-host, no dedicated mobile app), Dex ($144/yr, professional focus, no free tier), Queue, Keep My Friends, Hippo, Garden, Moments, UpHabit, Covve, Mesh (no Android) — [AlternativeTo Monica](https://alternativeto.net/software/monica); [AlternativeTo Dex](https://alternativeto.net/software/dex); [onepagecrm](https://www.onepagecrm.com/blog/best-personal-crm/)
- **"Which friends are free" social calendar:** Howbout claims 10M users and is still active (developer replies to reviews in Oct 2025). Some reviews say "none of my friends use this anymore", which points to network-effect decay — [Google Play](https://play.google.com/store/apps/details?id=app.zyng.app&hl=en_US); [App Store reviews](https://apps.apple.com/us/app/howbout-shared-calendar/id1477248221?see-all=reviews)

### Inferences
- The best opportunities are in "abandoned or enshittified incumbent" categories (Stocard, Mint, Splitwise free tier), where the user need has been validated for years. These categories fill up fast with clones, though; the loyalty-card and Splitwise spaces had 5–10 new indie entrants within about a year. Differentiation would come from privacy (no account, offline, export), cross-platform support (Android plus Watch), and non-US coverage.
- The structurally unsolved problems are **aggregation** problems: events, grocery prices, school emails. They are hard because the data sits in silos with anti-scraping defenses, product matching is hard, and the supply side has no incentive to share.
- The trust-network problems (babysitting co-ops, "who's free") fail because of **chicken-and-egg network effects** and weak monetization, not technology. Komae is a documented case.

### Gaps
- No Reddit thread (r/SomebodyMakeThis, r/AppIdeas, r/lifehacks, etc.) could be opened or quoted. Upvote and comment counts are entirely missing. A follow-up with Reddit access should confirm which candidates recur most.
- HN thread scores and comment counts could not be read. The Oct 2025 "What do you wish existed?" thread's consumer content is unknown beyond the summary.
- Product Hunt comments and 1–3★ app-store reviews were not read in full; only listing summaries were available.

## For each candidate, which existing apps come closest, and what precisely is missing?

### Takeaway
Close solutions exist for almost every candidate. The gaps are specific: they are about account requirements, paywalls, region coverage, missing workflow steps, or missing network density, not the absence of any app.

### Cited Findings
| Problem | Closest today | What's missing (per sources) |
|---|---|---|
| Loyalty-card wallet | Klarna (former Stocard), SuperCards, Catima, Apple Wallet + Pass2U | Klarna: forced account, no Watch, no offline mode, no export, lost cards on migration ([CHOICE](https://choice.community/t/stocard-being-replaced-by-klarna-app/33022?page=3); [CardWarden](https://cardwarden.app/blog/why-i-built-cardwarden)) |
| Mint-style free budgeting | Monarch, YNAB, Empower, Rocket Money | Full features are paid only (about $100/yr); Monarch is North America only; free tools are basic ([financialaha](https://www.financialaha.com/articles/mint-alternatives-after-shutdown/); [spendandinvest](https://spendandinvest.com/blog/mint-alternative-2026)) |
| Expense splitting | Splitwise, Tricount, Splid, Spliit, Settle Up | Splitwise: daily cap of about 3–5, ads, receipt scanning and FX behind paywall ([hipposplit](https://hipposplit.com/blog/splitwise-review/)) |
| Local events | Luma, Partiful, Eventbrite, Meetup; Facebook Local is dead | No cross-platform consumer aggregator; weak discovery outside hub cities ([Apify](https://apify.com/northloop-labs/tech-events-finder); [Hidden Events](https://hiddenevents.online/blog/luma-vs-meetup-vs-eventbrite-vs-partiful/)) |
| Group trips | Wanderlog, Troupe, Splitwise, TripRelay, Limbo | No app combines voting, itinerary and expenses; decisions slide back to the group chat ([tripriot](https://tripriot.com/compare/group-trip-planner-apps/)) |
| School/club email overload | Honeycomb, Sense, Sync School Events, school portals | Unproven new apps with few ratings; portals depend on the school ([Honeycomb](https://apps.apple.com/app/id1507430402)) |
| Babysitting co-op | Komae → Wana → Carefully | Repeated business failure and retirement ([Working Woman Report](https://workingwomanreport.com/komae-babysitting-app-saved-new-parent/)) |
| US grocery prices | Flipp, Basket, Grocery Dealz | Flyer-only or partial coverage; PriceSnap stopped its grocery features in Nov 2026 ([PriceSnap](https://www.pricesnap.ai/grocery-price-comparison)) |

### Inferences
- In 1–3 (loyalty cards, budgeting, splitting), the missing piece is a business model or a trust stance, not features. In 4, 5 and 8 (events, group trips, groceries), it is data integration. In 6 it is reliability of AI parsing and adoption. In 7 it is network density.

### Gaps
- Pricing and feature claims come largely from vendor comparison pages and were not checked against official sites.
- Non-English markets (e.g., Tricount and bunq in Europe, local event apps) were not examined.

## Why has nobody solved them well?

### Takeaway
There are five recurring causes: (1) acquirers absorb good free apps into their own products (Klarna/Stocard, Intuit/Mint); (2) free utilities can't sustain themselves, which leads to caps and paywalls (Splitwise); (3) data sits in hostile silos (events, grocery prices); (4) chicken-and-egg network effects (babysitting co-ops, Howbout); and (5) stated demand doesn't turn into payment.

### Cited Findings
- Acquisition and absorption: Stocard was folded into Klarna to drive Klarna accounts — [Vamers](https://vamers.com/2026/03/20/klarna-stocard-barcodes-loyalty/)
- Unsustainable free model: Komae had about 19k accounts but "the business wasn't working out" — [Working Woman Report](https://workingwomanreport.com/komae-babysitting-app-saved-new-parent/)
- Data cost and anti-bot defenses: a developer case study cites freshness vs. cost, anti-bot measures, frequent site changes, and UPC matching across chains — [webdatascraping.us](https://www.webdatascraping.us/store-level-pricing-us-price-comparison-app.php)
- Network decay: Howbout reviews say "none of my friends use this anymore" — [App Store reviews](https://apps.apple.com/us/app/howbout-shared-calendar/id1477248221?see-all=reviews)
- Low willingness to pay: Indie Hackers feedback on the family receipt and warranty app, and a founder noting the gap between "people want this" and "worth building a business around" — [Indie Hackers](https://www.indiehackers.com/post/i-wasted-months-building-things-nobody-wanted-66eec1cc5b)
- Facebook's own Events app never got popular (about #250–500 in US social apps) — [TechCrunch](https://techcrunch.com/?p=1427049)

### Inferences
- A solo developer should avoid categories that need two-sided network density (co-ops, social calendars) unless the app works for a single user first. An example would be a personal events feed that becomes social later.

### Gaps
- No market-size data per category was found.

## What would a feasible MVP look like for a solo developer or small team?

### Takeaway
The most feasible MVPs are single-player, privacy-first utilities that replace a crippled incumbent. A loyalty-card wallet and a no-cap expense splitter are the easiest, but already contested. An "events in my city" aggregator built from a few scraped or API sources, and an AI school-email-to-calendar tool, carry more risk but leave more room.

### Cited Findings (feasibility anchors)
- Open-source proof that a loyalty wallet can be built small: Catima (FOSS) — [AlternativeTo](https://alternativeto.net/software/stocard)
- Open-source proof for expense splitting: Spliit — [splitfast](https://splitfast.io/blog/splitwise-alternatives)
- The event-merging technique already exists as scrapers (Luma, Eventbrite, Meetup, Partiful), so a consumer UI could sit on top — [Apify](https://apify.com/avinashchby/event-scraper)
- An email-forwarding plus AI-extraction pattern is already used by Honeycomb and Sense, and by Manifest for receipts — [Sense](https://apps.apple.com/app/id6739470108); [Manifest](https://alternativeto.net/software/manifest-home-inventory-app/about/)

### Inferences (MVP sketches, not sourced facts)
- **Loyalty wallet:** no account; offline; import from a Stocard/Klarna export or a photo; Android plus Apple Watch / Wear OS; open export format; one-time payment. Differentiation is narrow given SuperCards and Catima.
- **Free budgeting "Mint-lite":** CSV/statement import plus LLM categorization; no bank login; strong in regions Monarch doesn't cover. Revenue from a modest one-time or low annual price.
- **Splitter:** unlimited free entries, multi-currency, a link-join web app with no install. Already saturated, so only viable as a feature inside a broader group-trip product.
- **Group trip "decide → plan → pay":** a link-based web app with polls and deadlines that turns a locked plan into an itinerary, with a simple expense ledger. Low install friction addresses the onboarding drop-off.
- **City events feed:** start with one city; merge Luma, Eventbrite, Meetup and venue calendars; filter by interest; send a weekly digest email. The risks are scraping terms of service and source fragility.
- **School-email parser:** a forwarding address that turns emails into ICS calendar entries plus a to-do digest. Accuracy and trust are the key metrics, and there is competition from 2025–2026 entrants.

### Gaps
- None of these MVPs were validated against real user interviews or paid-conversion data.
- Legal and terms-of-service constraints on scraping event or grocery sites were not researched.
