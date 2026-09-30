# Card Shop Feasibility: Michigan City

> Last updated: 2026-09-30
> Status: first pass. Desk research only. No phone calls, no site visits, no
> distributor quotes, no customer counts.

This repo holds research on a trading card store (Pokémon, One Piece, Magic,
Lorcana, sports cards) in Michigan City, Indiana, as a storefront or as an online
store based in Indiana. Seed capital named by the owner: about $50,000.

The deliverable is a go / no-go decision. The research follows the evidence
rules of the [froyo feasibility project](https://github.com/ernieayala/froyo/blob/main/CLAUDE.md):
every number carries a source, a date, and a confidence tier.

| Tier | Means |
|------|-------|
| `fact` | Published by a primary source and specific to this case |
| `sourced` | A credible published figure, used as a proxy for this case |
| `estimate` | Our arithmetic from facts, with the working shown |
| `guess` | No source. A placeholder, never a basis for a conclusion |

## Headline, pessimistic first

1. **$50,000 does not cover the storefront estimate.** Opening costs run
   $64,375 to $198,752, with six months of fixed costs as working capital
   ([storefront costs](research/storefront-costs-and-demand.md), section 8,
   estimate). The low end sits $14,375 above the seed. Before working capital
   the range is $43,896 to $163,547, so $50,000 opens the low-end store with
   about $6,100 left against a six-month cushion of $20,479. Guesses make up 52%
   to 58% of the total; TCG inventory ($20,000 to $50,000) and build-out ($5,000
   to $25,000) are the two largest.
2. **Online-only fits the budget and has no wholesale supply.** Southern Hobby
   and PHD refuse online-only applicants in writing, GTS excludes residences and
   pop-ups from its store-only lines, and every publisher store program found
   requires a public venue with seating
   ([distribution](research/distribution-and-supply.md), sections 1 and 2,
   fact). An online-only seller buys at market and sells at market: a $100
   single nets $78.81 on TCGplayer after fees and zone-4 postage
   ([online and legal](research/online-and-legal.md), section 1.8, estimate).
3. **Sports cards cannot be a main line at opening.** Topps holds MLB, NBA and
   NFL and is not taking new direct accounts: "At this time, there is no
   alternative application process or route available" (fanaticscollectpro.com,
   checked twice on 2026-09-30, fact). Southern Hobby gives new customers no
   new-release sports product. Panini needs 6 months of storefront history and
   sports cards at 70% of sales ([sports cards](research/sports-cards.md),
   fact).
4. **A storefront can open distributor accounts; it cannot get hot product in
   year one.** Accounts need storefront photos, a resale certificate and 3 to 10
   business days. Allocation of hot sets follows purchase history and event
   attendance, and a new store has neither. One hobby store received a single
   Elite Trainer Box of Pokémon's 30th Celebration set (ICv2, 2026-09-28,
   sourced).
5. **The category is at a peak with a speculative share.** Hobby games sales
   rose from $2.84B (2024) to $3.66B (2025) in the US and Canada after two flat
   years. Ravensburger says Lorcana's investment buyers "have since withdrawn";
   30th Celebration singles lost 40% to 80% within a week
   ([category and unit economics](research/category-and-unit-economics.md),
   sourced).

What runs the other way:

- **No publisher-listed card store operates in Michigan City.** The nearest
  three sit 11.0 to 11.5 miles away in Chesterton and La Porte (Wizards and
  Ravensburger locator APIs, fact). Whether that gap means unserved demand or a
  town too small for a store is unresolved
  ([competition](research/competition.md)).
- **Card store demand is resident, not tourist**, so the lakefront winter that
  sank the froyo numbers matters less here. The national proxy shows February
  at 0.72x an average month, against a November and December share of 27%
  (Census retail series, sourced).
- **Small retail rent is cheaper than the froyo work assumed:** $6.50 to
  $12.00/sqft/yr asking for existing inline space on Franklin Street (sourced).

## Buying sealed product on TCGplayer to fill the gap

The owner's example, One Piece OP-16 "The Time of Battle" (list price $4.99 a
pack, $119.76 a box): a case at TCGplayer market price costs $203.48 a box, 70%
above list. Sold in store at market price the gross margin is 9.1%; at 20% over
market, 24.2%; at 50% over, 39.4%. Resold on TCGplayer it loses $10.01 a box
before postage ([distribution](research/distribution-and-supply.md), section
4.3, estimate). Secondary sourcing works as a stopgap for a few SKUs. It does
not work as the supply plan, because a customer can buy the same box on the
same site.

## Storefront against online-only

| Factor | Storefront with play space | Online-only |
|--------|---------------------------|-------------|
| Distributor accounts | Eligible | Refused (Southern Hobby, PHD) or limited (GTS) |
| Publisher store programs and event support | Eligible once seating and signage exist | Not eligible |
| Hot-product allocation | Starts near zero, grows with history | No path |
| Sports hobby accounts | Topps closed; Panini after 6 months at 70% sports; Upper Deck program open but Southern Hobby will not supply | None |
| Pricing power | Events, same-day purchase, local trust | Price taker: 198 to 263 competing listings on sampled popular cards |
| Opening cost | $64,375 to $198,752 (estimate) | Low; inventory is the cost |
| Local rules | Second exit likely needed above 49 occupants | City home-occupation zoning bars "retail sales activities" at a home |

## Plan

The [storefront plan](storefront-plan.md) fits a singles-first store with a
20-seat play area into the $50,000, at the low end of every cost line and with
five gates to pass before any lease is signed.

## Research files

| File | Covers | Strongest finding |
|------|--------|-------------------|
| [Distribution and supply](research/distribution-and-supply.md) | Publisher programs, distributor terms, allocation, secondary sourcing | Account access is routine for a storefront and closed to online-only; allocation is the hard part |
| [Competition](research/competition.md) | Every card, comic and game seller within 45 minutes, big-box, closures, the owner's pricing claims | No publisher-listed store in Michigan City; a 100-table card show runs monthly in town |
| [Storefront costs and demand](research/storefront-costs-and-demand.md) | Demographics, space, rent, startup costs, staffing, security | Startup $64,375 to $198,752; theft losses at regional card stores ran $5,000 to $340,000 per incident |
| [Online and legal](research/online-and-legal.md) | Marketplace fees, shipping, Indiana tax, city code, card shows | New TCGplayer sellers start capped at 100 items and $1,000 listed |
| [Category and unit economics](research/category-and-unit-economics.md) | Market size, bust signals, margins, seasonality, failure rate | Anecdotal margins: sealed 27% to 35%, singles 45% to 50% |
| [Sports cards](research/sports-cards.md) | Licenses, direct programs, formats, breaks, grading | Topps closed to new shops; box breaks face lottery claims in California |

## The owner's four observations, checked

| Observation | Result |
|-------------|--------|
| A Michigan City comic shop carries a few boxes of Pokémon and One Piece | Consistent. Heroes Haven Comics & Games is the only comic shop found; no publisher locator lists it. Stock depth unchecked |
| A sports card shop near New Buffalo prices 50% to 80% above market | Not verified. A sports-first shop exists there; its site blocks automated retrieval, so no prices were read |
| La Porte shops price about 20% above market | Not verified. Neither publishes prices. A shop without allocation has to charge about this much to earn 24% on secondary-sourced product, so the markup may reflect cost rather than extra margin (estimate) |
| La Porte is the next nearest option | Contradicted in part. Reliquary Gaming in Chesterton is the same distance and runs the most posted events |

## Open questions, ranked by how much they move the answer

| # | Question | How to answer | Decides |
|---|----------|---------------|---------|
| 1 | What does a new account pay as a percent of list price, and what does it receive on a hot release in its first 6 months? | Call GTS (800-890-5456), Southern Hobby and PHD. Ask about each game, and whether buying slow product is a condition of hot allocation | Every sealed margin, and whether $50,000 stocks a store |
| 2 | Will Michigan City players play and buy in town, or do they already drive to Chesterton and La Porte? | Attend one event at Reliquary and one at High Heat; count players and ask their home town | Whether a local event space has demand |
| 3 | What does the monthly card show sell, at what prices, and who tried a card store here before? | Attend the FOP Lodge show on 2026-10-17; ask the organizer (219-229-0411) about past shops | Whether the show already absorbs local demand |
| 4 | What do local shops charge against TCGplayer and list price? | The 10-SKU same-day price survey in [competition](research/competition.md) | The pricing gap the entry case rests on |
| 5 | Which stores run Pokémon and One Piece events within 25 miles? | Pokémon Event Locator and Bandai TCG+ in a browser (both blocked automated access) | Whether the youth-event gap exists |
| 6 | What does inventory insurance with burglary coverage cost at $50,000 to $100,000 limits? | Two broker quotes | The largest tail risk |
| 7 | What are triple-net charges on candidate bays, and does a bay have a second exit? | Bradley Company (219-508-0554), EDC Michigan City (219-873-1211), city planning (219-873-1419) | The rent line and the event cap |

## What this pass did not do

- No distributor, landlord, insurer or shop owner was contacted.
- No store's monthly sales were obtained. There is no revenue estimate yet, so
  no monthly cash model and no three-scenario run.
- No financial model exists for the card shop. The froyo project's model engine
  has no card-store assumptions.
- Indiana statutes on secondhand and pawn dealers could not be retrieved.
- Several figures are past the 18-month limit or rest on search snippets; each
  file's re-check schedule names them.

## Re-check schedule

Each research file carries its own. The two that could change the headline:
the Topps application freeze (re-check 2026-12-31) and Southern Hobby's
new-customer sports rule (re-check 2027-03-30).
