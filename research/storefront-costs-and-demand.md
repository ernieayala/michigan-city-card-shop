# Storefront Costs and Local Demand: TCG and Sports Card Store

> Last updated: 2026-10-01
> Scope: who buys, how much space, what it costs to open and run. Sports-card
> distribution and the card market itself sit in [sports-cards.md](sports-cards.md)
> and [category-and-unit-economics.md](category-and-unit-economics.md), not here.

**Headline, pessimistic first.** Opening costs run $64,200 to $198,800
(estimate, table below), and guesses make up $33,600 to $118,900 of that. A
Michigan City card store would not open into an empty market: a comic and game
shop (Heroes Haven, 296-A E US Hwy 20) and a video game store (Game Changers,
4303 Franklin St) already trade in town, and a card show with 100+ tables runs
monthly at the FOP lodge. Neither store appears on a publisher store locator
([competition.md](competition.md)). The resident youth base in the core trade
area comes to about 5,500 children aged 8 to 17 (estimate). Rent is the one line
that came in cheaper than the earlier frozen-yogurt study feared: existing small
inline space asks $6.50 to $10.00/sqft/yr on available listings; a $12.00 ask
went under contract in 2025.

---

## 1. How large is the resident demand base?

**Finding:** The core trade area (ZCTAs 46360 Michigan City, 49117 New Buffalo,
49128 Three Oaks) holds 50,625 residents, about 5,481 aged 8 to 17, 13,649 aged
18 to 39, and 4,905 households with children under 18.

**Confidence:** fact for each ACS cell; estimate for the 8-17 band and the
trade-area sums (arithmetic shown below)
**Source:** US Census Bureau, American Community Survey 2020-2024 5-year
estimates (release `acs2024_5yr`), tables B01001 (sex by age), B11005
(households with people under 18), B19013 (median household income), B26001
(group quarters). Retrieved through the Census Reporter API, which republishes
ACS tables cell for cell:
<https://api.censusreporter.org/1.0/data/show/acs2024_5yr?table_ids=B01001,B19013,B11005,B01003&geo_ids=16000US1848798,05000US18091,05000US26021>
and
<https://api.censusreporter.org/1.0/data/show/acs2024_5yr?table_ids=B01001,B19013,B11005&geo_ids=86000US46360,86000US49117,86000US49128,86000US46350,16000US2657220>
; group quarters:
<https://api.censusreporter.org/1.0/data/show/acs2024_5yr?table_ids=B26001&geo_ids=16000US1848798,05000US18091,86000US46360>
(Michigan City 2,843; LaPorte County 6,878; ZCTA 46360 2,854). The data.census.gov API (api.census.gov) refused the request without an API
key, so the figures did not come from census.gov directly.
**Retrieved:** 2026-09-30

| Geography | Population | Age 8-17 (est.) | Age 18-39 | Households with children | Share of households | Median household income |
|-----------|-----------:|----------------:|----------:|-------------------------:|--------------------:|------------------------:|
| Michigan City (place) | 31,814 | 3,468 | 10,108 | 3,227 | 24.8% | $53,089 (MOE ±$4,337) |
| ZCTA 46360 (Michigan City and Michiana Shores) | 43,817 | 4,859 | 12,481 | 4,321 | 23.7% | $59,266 (±$3,586) |
| ZCTA 49117 (New Buffalo area, MI) | 3,358 | 283 | 464 | 236 | 13.3% | $75,114 (±$14,923) |
| ZCTA 49128 (Three Oaks area, MI) | 3,450 | 339 | 704 | 348 | 22.9% | $67,398 (±$10,641) |
| **Core trade area (three ZCTAs)** | **50,625** | **5,481** | **13,649** | **4,905** | | |
| ZCTA 46350 (La Porte) | 44,763 | 6,160 | 11,273 | 5,579 | 31.6% | $74,307 (±$2,613) |
| LaPorte County, IN | 111,917 | 13,690 | 30,581 | 12,207 | 28.0% | $71,055 (±$2,241) |
| Berrien County, MI | 153,288 | 19,055 | 38,531 | 16,467 | 25.7% | $65,425 (±$1,108) |
| New Buffalo city, MI | 1,338 | 116 | 217 | 91 | 12.1% | $64,702 (±$24,988) |

**How the 8-17 band is built.** ACS reports ages 5-9, 10-14 and 15-17. The
8-17 figure is 10-17 in full and two-fifths of 5-9, which assumes ages 5 through
9 are evenly spread. Michigan City: 2,663 + 0.4 x 2,012 = 3,468. The 18-39 band
sums ACS brackets 18-19 through 35-39; ACS has no 40 cut, so "18-40" here means
18-39.

**Cross-check against the earlier frozen-yogurt study ([market-demographics.md](https://github.com/ernieayala/froyo/blob/main/research/market-demographics.md)).** That file carried
31,814 residents and $53,089 median income as `sourced` from aggregators
(retrieved 2026-08-04). ACS 2024 5-year returns the same 31,814 and $53,089, so the two figures
now trace to the primary table.

**Michigan City skews poorer and less family-heavy than La Porte.** 23.7% of
46360 households have children, against 31.6% in 46350 (La Porte) and 28.0%
county-wide. Median income in 46360 runs $15,041 below 46350. A store in Michigan
City sits in the thinner half of its own county for the youth segment.

**The New Buffalo side adds little.** ZCTAs 49117 and 49128 add 6,808 residents
and 622 children aged 8-17. Median age in New Buffalo city is 54.5 (Census
Reporter profile, <https://censusreporter.org/profiles/16000US2657220-new-buffalo-mi/>,
retrieved 2026-09-30). This is a retiree and second-home area, not a youth
market.

**Disconfirming check: prisons inflate the adult count.** Michigan City
has 2,843 residents in group quarters (B26001), 8.9% of the city. LaPorte County
has 6,878. Men aged 25-44 outnumber women 25-44 by 962 in the city (5,225 vs
4,263) and by 3,387 county-wide (16,096 vs 12,709). Berrien County, with no
comparable facility count in this pull, is balanced (17,864 vs 17,828). The
likely cause is the Indiana State Prison in Michigan City and the Westville
Correctional Facility in the county. That attribution is a `guess`: B26001 does
not split correctional from other group quarters, and table B26101 or the 2020
Census group quarters count would confirm it. Until then, treat the 18-39 count
for Michigan City as 7,265 to 10,108 (subtracting all group quarters as the
lower bound), and the adult male count as overstated by up to 2,854 in 46360.

---

## 2. Who buys sports cards, as distinct from TCG players?

**Finding:** No current, primary, demographically split survey of sports card
buyers was found. The two sources with methodology point to young adult men,
and both are older than 18 months.

**Confidence:** sourced, stale
**Source:** CivicScience, "Are Sports Cards Making a Comeback?", 2021-05-11,
<https://civicscience.com/are-sports-cards-making-a-comeback/> ; The Setonian
(Seton Hall student paper) reporting the Seton Hall Sports Poll, 2024-05-02,
<https://www.thesetonian.com/article/2024/05/sports-memorabilia-and-collecting>
**Retrieved:** 2026-09-30

- CivicScience: "those ages 18 to 24 are much more likely than people 25 and
  older to have bought trading cards in the last week or month," and 43% of US
  adults "has or used to have at least some trading cards." No sample size on
  the page. Dated 2021, inside the pandemic card boom.
- Seton Hall Sports Poll via The Setonian: 28% of US households "actively
  collect sports memorabilia," and 54% of collectors own cards. The fetched page
  gives no age or gender split. A search-result summary attributed an 18-34
  figure to the same poll; the fetched article did not contain it, so it is not
  used.

Pages that report "65% of collectors are 18-35" and "62% male" trace to market
research resellers and blog aggregators with no methodology. Excluded under
the evidence rules on the overview page.

**Local adult male base (the proxy we can count):** men aged 18-24 and 25-54 in
the core trade area are 2,272 and 9,997 (ACS B01001, 46360 + 49117 + 49128).
Subtract up to 2,854 group-quarters residents in 46360 from the adult figure.

**Disconfirming check:** A sports card buyer drives to a card show or orders
online. The Michigan City Card and Pokemon Show at FOP Lodge #75, 416 US-20,
lists "100+ tables" for its 2026-10-17 date and another on 2026-12-12, with
"vendor tables featuring Pokemon and sports cards"
(<https://www.treasurehunter.show/show/the-michigan-city-card-and-pokemon-show-michigan-city-in-2026-12-12>,
retrieved 2026-09-30, `sourced`). That shows local buyers exist. It also shows
they already have a recurring channel where 100 dealers compete on price, which
caps what a store can charge for boxes and singles on show weekends.

---

## 3. Is the customer base resident or tourist?

**Finding:** Resident. Weekly organized play (league nights, Friday Night Magic,
prereleases) needs the same players every week, which a July day-tripper cannot
supply. Summer tourism may lift impulse sealed-product sales and does nothing for
events.

**Confidence:** guess. No survey of card store customers by residence was
found. The reasoning is structural, not measured.
**Source:** Structure of event play as described by the operators themselves:
NWI Cards lists "weekly locals, tournaments, prereleases"
(<https://www.nwicards.com/pages/visit>, retrieved 2026-09-30). Tourism context:
the earlier frozen-yogurt study ([tourism-seasonality.md](https://github.com/ernieayala/froyo/blob/main/research/tourism-seasonality.md)) (NPS annual visits, 2,629,497 in CY 2025,
retrieved 2026-08-04, `fact`).
**Retrieved:** 2026-09-30

A frozen-yogurt shop fears February because tourists leave. A card store's
demand base stays in town all year, so its seasonality risk is smaller, and its
ceiling is set by 50,625 residents (46360's median household income is $59,266)
rather than by 2.6 million park visits.

**Disconfirming check:** What would make tourism matter? Family visitors buying
packs as a rainy-day activity, and second-home owners in 49117 buying
sports-card boxes on summer weekends. Neither has a number. A store could test
it by logging customer ZIP codes at checkout for one summer. Card releases, not
weather, set a card store's calendar, and nobody in this repo has modeled that.

---

## 4. Purdue Northwest as a demand source

**Finding:** PNW reports 6,103 undergraduate, graduate and online students
system-wide for fall 2026, down from 6,522 in fall 2025. No Westville campus
figure was found for any year after 2016.

**Confidence:** sourced
**Source:** WBIW, "Purdue reports enrollment growth, higher graduation and
retention rates," 2026-09-28,
<https://www.wbiw.com/2026/09/28/purdue-reports-enrollment-growth-higher-graduation-and-retention-rates/>
(6,103); fall 2025 figure of 6,522 via Northwest Indiana Business Magazine,
<https://nwindianabusiness.com/community/education/purdue-northwest-reports-strong-enrollment-numbers/67275/>
(search result summary, page not fetched)
**Retrieved:** 2026-09-30

Two campuses (Hammond, Westville) share the 6,103, and online students are in
it. The only campus split found, 6,092 at Westville against 9,194 at Hammond,
dates to the 2016 merger and is stale. A 2024 HomeTownNewsNow article reported
9,051 total (<https://hometownnewsnow.com/local-news/761065/pnw-reports-higher-fall-semester-enrollment>,
2024-09-20), which likely counts dual-credit high school students; the two
series are not comparable.

**Distance:** Westville campus to downtown Michigan City is roughly 12 to 15
miles by US-421. `guess`, not measured; a map check replaces it.

**Disconfirming check:** A commuter campus 12+ miles away with a falling
system-wide headcount does not supply a weekly event crowd. Weight PNW near zero
until the registrar gives a Westville headcount and a count of students living
in 46360.

---

## 5. How much floor space does a card store with play space need?

**Finding:** 1,000 to 1,500 sq ft covers a sales floor and seating for 20 to 40
players. Keep the play area under 750 sq ft so it stays classified as part of
the retail occupancy rather than as a separate assembly occupancy.

**Confidence:** estimate, built on code minimums (`fact`) and two trade
benchmarks (`sourced`, stale)
**Source:** Indiana Building Code 2014 (2012 IBC with Indiana amendments, 675
IAC 13-2.6, effective 2014-12-01, still the current adopted edition per Indiana
DHS, <https://www.in.gov/dhs/boards-and-commissions/fpbsc-rules>); Table 1004.1.2
via <https://up.codes/viewer/indiana/ibc-2012/chapter/10/means-of-egress> ;
Section 303.1.2 via
<https://up.codes/viewer/indiana/ibc-2012/chapter/3/use-and-occupancy-classification>
(search-result summary; section text not fetched); ICv2, "Ins and Outs of
In-Store Gaming, Part II," 2002-05-21,
<https://icv2.com/articles/games/view/1433/ins-outs-in-store-gaming-part-ii>
**Retrieved:** 2026-09-30

**Code facts:**
- Assembly, unconcentrated (tables and chairs): 15 net sq ft per occupant.
- Mercantile, grade-floor sales area: 30 gross sq ft per occupant. Storage and
  stock: 300 gross.
- Section 303.1.2: an assembly room with an occupant load under 50, or under
  750 sq ft, that is accessory to another occupancy is classified with that
  occupancy.
- Table 1015.1: a space with an occupant load over 49 in groups A, B, E, F, M
  or U needs two exits or exit access doorways (search-result summary of the
  2012 IBC table; not fetched from the code text).

**Arithmetic:**
- Play area: 20 players x 15 = 300 sq ft; 40 players x 15 = 600 sq ft.
- Tables: a 72 x 30 in folding table seats six card players at three per side
  (24 in each, `guess` on comfort). 20 players need 4 tables, 40 need 7.
- Sales floor and counter: 400-600 sq ft (`guess`). Stock room, restroom,
  office: 150-250 sq ft (`guess`). Total: 850-1,450 sq ft, rounded to
  1,000-1,500.
- Occupant load at 1,400 sq ft: 600/15 + 600/30 + 200/300 = 40 + 20 + 1 = 61.
  That exceeds 49, so the unit likely needs a second exit. Many older inline
  bays have a rear service door; confirm before signing.

**Trade benchmarks (stale, 24 years old):** New World Manga ran an "1100 square
foot store with gaming space for 32 players"; Dr. Bob's Game Shop had "2400
square feet with 1200 feet of gaming space" (ICv2, 2002). The 1,100 sq ft / 32
seat case sits inside our range. No GAMA publication with a square-footage
benchmark was found.

**Disconfirming check:** What would make 1,000-1,500 too small? Pokémon
prereleases and One Piece or Lorcana launch events can exceed 40 players. The
cap then comes from code, not tables: past 49 occupants in the play room, it
becomes an A-3 assembly space with its own egress and fire requirements. Heroes
Haven runs two rooms, one for comics and one for tabletop play (Yelp description
via search summary, not fetched), which suggests the same 1,000-2,000 sq ft
class. A larger event hall is a different building and a different rent.

---

## 6. What does that space rent for in Michigan City?

**Finding:** Existing small inline retail asks $6.50 to $10.00/sqft/yr on
available listings (a $12.00 ask went under contract in 2025); new or
large Franklin Street south-end space asks $19 to $21. For 1,200-1,500 sq ft
the all-in estimate is $1,000 to $2,125 per month.

**Confidence:** sourced for each listing; estimate for the monthly band; guess
for the NNN add-on
**Source:** see table
**Retrieved:** 2026-09-30

**LoopNet and Crexi returned HTTP 403 to every automated request** (search
pages and individual listings). CityFeet, Showcase and Realmo did the same. The
listings below come from the Northwest Indiana Forum's property database
(ZoomProspector), CommercialSearch/PropertyShark, and a Berkshire Hathaway
listing page, each fetched directly.

| Address | Space | Asking | Monthly base | Terms | Source (retrieved 2026-09-30) |
|---------|------:|-------:|-------------:|-------|-------------------------------|
| 1601 Franklin St, Unit C | 858 sf | $6.50/sf/yr | $465 | 3-5 yr; lease type not stated | <https://properties.zoomprospector.com/northwestin/property/1601-Franklin-St-Michigan-City-Indiana/FC96A191-E96A-42F9-964F-3A48A97E9E80> (updated 2026-06-25) |
| 1601 Franklin St, Suite 1603 | 1,370 sf | $7.00/sf/yr | $799 | negotiable term | same |
| 3200 Franklin St (Park and Shop), Suite 3231-B | 3,000 sf | $10.00/sf/yr | $2,500 | NNN, 3-5 yr; Bradley Co. 219-508-0554 | <https://properties.zoomprospector.com/wvpa/property/3200-Franklin-St-Michigan-City-Indiana/9E861EE5-D2E4-4CE8-88FD-B8BADE6A1C3E> (updated 2026-06-25) |
| 3200 Franklin St, Suite 3221 | 5,756 sf | $9.75/sf/yr | $4,677 | NNN, 3-5 yr | same |
| 720 Franklin St (Uptown Arts District) | 2,800 sf | $12.00/sf/yr | $2,800 | tenant pays electric and gas; **pending under contract since 2025-10-01, off market** | <https://www.bhhsnorthernindianarealestate.com/commercial/gni/824208/720-franklin-street-michigan-city-in-46360> |
| 5510 Franklin St | 12,000 sf | $19.00/sf/yr | $19,000 | not stated | <https://www.commercialsearch.com/commercial-real-estate/us/in/michigan-city/retail/> |
| 5172 Franklin St | 8,000 sf | $14,000/mo ($21.00/sf/yr) | $14,000 | not stated | same |
| 4301 Franklin St (Lake Park Plaza) | 1,400-15,000 sf | price on request | | EDC contact Clarence Hulse 219-873-1211 | <https://properties.zoomprospector.com/northwestin/property/4301-Franklin-St--Michigan-City-Indiana/DECD70DF-62B4-45EA-9E83-5C3A436420BA> (updated 2026-01-02) |
| 5330 Franklin St | 1,360 sf | price on request | | | CommercialSearch, as above |

**Comparison with the earlier frozen-yogurt study ([operating-costs.md](https://github.com/ernieayala/froyo/blob/main/research/operating-costs.md)).** That file recorded LoopNet's
$9.67/sqft average for Michigan City retail (retrieved 2026-08-04) as a `guess`,
on the grounds that a pool dominated by large boxes misstates small-space rent.
The direct listings show older small inline space asking $6.50 to $12.00, which
brackets $9.67. The suspicion that small space rents far above the average does
not hold for existing stock on these listings. It does hold for new or
south-end Franklin Street space at $19-21, and for The Franklin at 11th Street
Station, still price on request.

**Monthly band arithmetic:**
- Low: 1,200 sq ft x ($7 base + $3 NNN) / 12 = $1,000.
- High: 1,500 sq ft x ($12 base + $5 NNN) / 12 = $2,125.
- NNN charges (taxes, insurance, CAM) of $3-5/sqft/yr are a `guess`. None of the
  listings publish them.

**Disconfirming check:** Asking is not achieved rent, and one listing in the
set went under contract a year ago at an unknown final rate. The Park and Shop
NNN charges could exceed the base. A call to Bradley Company and to the EDC
(which lists several of these spaces) replaces the NNN guess.

**Heroes Haven sits in Michigan City Center, 290-298 E US Hwy 20.** A LoopNet
search-result summary listed 1,260-2,700 sq ft available in that center (page
not fetched, 403). A second card store in the same strip as the incumbent is a
siting question to decide on purpose, not by default.

---

## 7. Which cost lines from a food business drop out?

**Finding:** A card store is mercantile (group M) retail with no food service.
It removes the food-specific lines from the earlier frozen-yogurt study's cost
checklist and adds security and inventory-insurance lines a food shop does not
need.

**Confidence:** estimate (classification reasoning), with the dropped lines
taken from the frozen-yogurt study's [regulatory-and-tax.md](https://github.com/ernieayala/froyo/blob/main/research/regulatory-and-tax.md) and its [cost checklist](https://github.com/ernieayala/froyo/blob/main/CLAUDE.md)
**Source:** frozen-yogurt study, [regulatory-and-tax.md](https://github.com/ernieayala/froyo/blob/main/research/regulatory-and-tax.md) (retrieved 2026-08-04);
[transit-and-development.md](https://github.com/ernieayala/froyo/blob/main/research/transit-and-development.md)
**Retrieved:** 2026-09-30

| Frozen-yogurt study line | Card store |
|------------|-----------|
| LaPorte County Food Service License and health plan review | Drops out. No food served |
| Grease interceptor, floor drains | Drops out |
| Hood and ventilation | Drops out |
| Three-compartment warewash sink, NSF equipment | Drops out |
| Certified food protection manager | Drops out |
| Soft-serve machines, compressor failure, spoilage | Drops out |
| Mop sink | May remain. Plumbing fixture tables can require a service sink in mercantile space; ask the building department |
| ADA restroom, building permit, sign permit, CAM, POS, processing, insurance, workers comp | All remain |
| Prepared-food tax question (county food and beverage tax) | Drops out. Card sales carry Indiana's 7% state sales tax only |
| Personal property tax on equipment | Exempt: Indiana exempts business personal property under $2,000,000 acquisition cost per county from the 2026 assessment date (DLGF memo, 2025-05-23, <https://www.in.gov/dlgf/files/2025-memos/250523-Cockerill-Memo-Legislation-Affecting-Assessment-Matters.pdf>, `fact`) |
| New: burglary-rated security, inventory insurance limits | Added. See section 10 |

---

## 8. Startup cost

**Finding:** $64,200 to $198,800 to open, including six months of fixed
operating costs as working capital. Guess-tier lines account for $33,600 to
$118,900 of it.

**Confidence:** estimate; individual lines tiered in the table
**Source:** see table
**Retrieved:** 2026-09-30

| Line item | Low | High | Source | Confidence |
|-----------|----:|-----:|--------|-----------|
| Security deposit and first month rent (2 months all-in) | $2,000 | $4,250 | Rent band, section 6 | estimate |
| Build-out: paint, lighting, flooring, electrical for play area, ADA restroom fixes | $5,000 | $25,000 | None. A contractor walk-through of a chosen bay replaces it. ADA restroom retrofit drives the high end | guess |
| Locking display counters (4 low, 8 high) and locking wall cases (2 low, 4 high) | $3,776 | $8,312 | Counter: ShopPOP 70 x 20 x 38 in full-vision counter with locks, $623.69 (1-3), $589.04 (4+), <https://www.shoppopdisplays.com/18592/full-vision-glass-display-counter-black-70l-x-20w-x-38h.html> . Wall case: Uline H-2805 Clear-View cabinet, 3-point lock, $710 unassembled, $900 assembled, <https://www.uline.com/BL_3939/Clear-View-Cabinets> . Freight excluded | estimate |
| Play tables, 72 x 30 in (4 low, 7 high) | $1,120 | $1,960 | Uline H-2229A deluxe folding table, $280 each, <https://www.uline.com/BL_3988/Deluxe-Folding-Tables> | estimate |
| Chairs (20 at $30, 40 at $60) | $600 | $2,400 | No chair price retrieved | guess |
| Shelving, slatwall, checkout counter, supplies wall | $2,000 | $6,000 | None | guess |
| POS hardware (terminal, tablet, printer, scanner, cash drawer) | $800 | $2,000 | None retrieved. A Square or Shopify hardware quote replaces it | guess |
| Security: camera system, monitored alarm install, safe, window protection | $1,300 | $11,500 | None. Two alarm-company quotes replace it. Roll-down grille or security film drives the high end | guess |
| Exterior sign | $1,500 | $8,000 | None. A sign shop quote replaces it | guess |
| Indiana LLC Articles of Organization and Registered Retail Merchant Certificate | $125 | $125 | $100 filing fee, State Form 49459 (R12/01-26), <https://forms.in.gov/Download.aspx?id=16989> ; $25 per location RRMC, valid two years, IN DOR New and Small Business Owners guide, <https://www.in.gov/dor/files/new-small-business-handbook.pdf> | fact |
| Michigan City building, occupancy and sign permits, business registration | $200 | $1,500 | Fee schedule not published on the city site; Municode Chapter 50 did not render. Building dept 219-873-1417 | guess |
| Insurance, first-year premium (BOP with inventory, liability) | $1,136 | $4,000 | Low: Insureon median retail BOP $95/mo, $1,136/yr ($94.67/mo; $95 x 12 = $1,140), updated 2025-01-03, <https://www.insureon.com/retail-business-insurance/cost> . High: guess for inventory limits of $50k+ in a theft-targeted category | sourced (low), guess (high) |
| Utility deposits | $200 | $1,000 | None | guess |
| Opening TCG inventory: sealed Pokémon, Magic, One Piece, Lorcana, singles, sleeves and supplies | $20,000 | $50,000 | None in this file. Distribution terms sit in [distribution-and-supply.md](distribution-and-supply.md) | guess |
| Opening sports-card inventory: 10 SKUs x 2 boxes x $100 low; 25 SKUs x 4 boxes x $300 high | $2,000 | $30,000 | Unit prices below are Topps consumer presale prices; a store without a Topps account buys at secondary prices, e.g. $209.95 for a $99.99 hobby box ([sports-cards.md](sports-cards.md)). SKU and depth counts are guesses | estimate |
| Pre-opening payroll and training | $1,000 | $3,000 | None | guess |
| Accountant and lease review | $500 | $2,500 | None | guess |
| Opening marketing | $500 | $2,000 | None | guess |
| Working capital: 6 months of fixed operating cost | $20,479 | $35,205 | Monthly fixed cost below x 6 | estimate |
| **Total** | **$64,236** | **$198,752** | | estimate |
| Of which guess-tier lines | $33,600 | $118,900 | | |
| Total before working capital | $43,757 | $163,547 | | |

**Guess lines:** build-out, chairs, shelving and fixtures, POS hardware,
security, signage, city permits, utility deposits, TCG inventory, pre-opening
payroll, professional fees, marketing, and the high end of insurance. Guesses
make up 52% of the low total and 60% of the high total. The two largest are TCG
inventory and build-out.

**Sports-card box prices (unit inputs to the inventory line):**
- 2026 Topps Series 1 Baseball, Topps presale 2026-01-13: hobby $99.99, jumbo
  $199.99, mega $49.99, value blaster $24.99. Source: Checklist Insider,
  <https://www.checklistinsider.com/2026-topps-series-1-baseball> . `sourced`.
  A search-result summary showed Blowout Cards at $209.95 and Best Buy at
  $279.99 for the same hobby box after release (pages not fetched); another
  summary attributed $209.95 to DA Card World ([sports-cards.md](sports-cards.md)).
- 2025 Bowman Chrome Baseball hobby box, Topps presale 2025-08-11: $289.99;
  12-box case $3,359.99. Source: Baseball America, 2025-08-08, updated
  2025-08-28, <https://www.baseballamerica.com/stories/2025-bowman-chrome-preorder-begins-monday-aug-11/> .
  `sourced`.
- These are consumer presale prices from Topps. A store's wholesale cost through
  a distributor is a separate figure, covered in [sports-cards.md](sports-cards.md).
  Hobby boxes that sell out trade above MSRP, so replacement cost floats with
  the secondary market.

**Monthly fixed operating cost (basis for working capital):**

| Line | Low | High | Source | Confidence |
|------|----:|-----:|--------|-----------|
| Rent, all-in | $1,000 | $2,125 | Section 6 | estimate |
| Electric, gas, water | $250 | $600 | None. A NIPSCO bill history from the landlord replaces it | guess |
| Internet | $80 | $200 | None | guess |
| POS software | $49 | $189 | Low: Square Plus $49/mo per location. High: BinderPOS Pro $150 + Shopify Basic $39 | fact (pricing pages) |
| Insurance | $95 | $333 | $1,136 to $4,000 / 12 | sourced / guess |
| Alarm monitoring | $30 | $60 | None | guess |
| Accounting and payroll service | $150 | $400 | None | guess |
| One part-time employee, 25 hr/wk, wage and employer FICA | $1,674 | $1,874 | 25 x 52 x $14.35 / 12 x 1.0765; same at $16.07. BLS OEWS, section 11 | estimate |
| Workers comp | $86 | $86 | Insureon retail median $86/mo, as above | sourced |
| **Total** | **$3,413** | **$5,867** | | estimate |

Totals use unrounded rows ($3,413.18 low, $5,867.43 high).

Owner pay and owner health insurance are excluded. Neither is optional for
the owner; they are left out because no figure exists yet.

**Disconfirming check: what line is missing?** Against the frozen-yogurt study's
cost checklist: merchant processing (2.4% to 2.6% + 15¢ on Square, 2.5% to 2.6% +
10¢ on Shopify) is a variable cost and belongs in the P&L, not here. Loan
interest is absent because financing is undecided. Organized-play kits and
prerelease product are inventory purchases tied to each release and are not in
the opening inventory line. Event prizes and promo support are unknown.
Replacement of stolen inventory after a burglary is the tail risk, covered by
insurance only up to its stated limit and after the deductible.

---

## 9. POS options with published pricing

**Finding:** Card-specific systems cost $99 to $150/mo; general retail POS
costs $0 to $149/mo. BinderPOS has paused new sign-ups.

**Confidence:** fact (vendor pricing pages)
**Source:** each vendor page below
**Retrieved:** 2026-09-30

| System | Monthly | Setup | Transaction fees | Status | Source |
|--------|--------:|------:|------------------|--------|--------|
| BinderPOS (TCGplayer) | $100 (Binder), $150 (Binder Pro) | 2-4 week onboarding | 2% on own-website sales; 2.5% on TCGplayer integration sales; requires Shopify | **"we are pausing new seller onboarding and sign-ups"** (waitlist) | <https://seller.tcgplayer.com/point-of-sale> (binderpos.com redirects here) |
| CrystalCommerce Professional | $99 | $599 list, "$0.99 option" shown | 2.5% online; 0% POS and buylist | open | <https://www.crystalcommerce.com/pricing/> |
| Square for Retail | $0 Free, $49 Plus, $149 Premium, per location | | in person 2.6% + 15¢ (Free), 2.5% + 15¢ (Plus), 2.4% + 15¢ (Premium) | open | <https://squareup.com/us/en/pricing> (price table read from page source) |
| Shopify POS Pro | $89 per location, billed yearly, on top of Basic $39 or Grow $105 | | in person 2.6% + 10¢ (Basic), 2.5% + 10¢ (Grow) | open | <https://www.shopify.com/pos/pricing> |
| TCGplayer Pro | $0: "no contract, no monthly payment, and no startup cost" | none | Shipped Pro website sale: 2.5% Pro fee and 2.5% + $0.30 transaction fee | Requires Level 4 | [online-and-legal.md](online-and-legal.md), section 1.1 (help center read through its JSON endpoint) |

**Disconfirming check:** The card-specific systems earn their fee through
singles pricing and marketplace sync. A store that sells mostly sealed product
and sports boxes may not need them, and Square's free tier would do. A store
that relies on singles needs one, and the best-known option is closed to new
stores today.

---

## 10. Security: is theft a real cost here?

**Finding:** Yes. Card stores in Indiana and the region are burglary and
distraction-theft targets, with losses from $5,000 to $340,000 per incident. The
nearest documented case is in Chesterton, 11.0 miles straight-line
([competition.md](competition.md), estimate).

**Confidence:** sourced (local news)
**Source:** see list
**Retrieved:** 2026-09-30

- **Chesterton, IN, Reliquary Gaming, 1500 block S Calumet Rd.** Three people
  asked to browse a Magic: The Gathering binder; two distracted staff while the
  third bagged it. Value about $5,000. Date reported as 2023-11-29. WGN,
  <https://wgntv.com/northwest-indiana/police-search-for-group-spotted-stealing-5k-worth-of-trading-cards-from-chesterton-game-shop/>
  returned 403; details come from the search-result summary of that article.
  The Chesterton Tribune copy now redirects to an unrelated site.
- **Indianapolis, Grandmaster Games, 4200 S East St, 2026-05-08, about 5:45am.**
  Break-in; the masked suspect went for display cases, skipped the registers,
  and took graded slabs worth $10,000 to $15,000. WRTV,
  <https://www.wrtv.com/news/local-news/crime/thieves-steal-15k-in-pokemon-trading-cards-from-south-side-indianapolis-shop>
- **Twin Lakes, WI (Kenosha County), Goldenrod City Collectibles, 2026-08-10.**
  Window smashed at about 2am; four people took at least $340,000 in under five
  minutes. FOX6,
  <https://www.fox6now.com/news/twin-lakes-card-store-burglary-pokemon-cards-among-340k-stolen> .
  This is about 90 miles from Michigan City, not in Michiana; it is here for the
  loss size.

No card store break-in in Michigan City or LaPorte County was found. The
search covered NW Indiana town names and Michiana, and absence from search
results does not establish absence of incidents.

**What this implies for cost:** entry in both burglaries came through glass.
Locking cases slow a thief but do not stop a smash, so high-value stock (graded
slabs, hobby boxes, chase singles) goes into a safe or back room overnight. That
routine costs 20-40 minutes of labor per day (`guess`). The insurance question
that matters is the inventory limit and the theft sublimit for collectibles, and
whether the carrier excludes "valuable papers" or collectibles held for sale.
The Insureon medians in section 8 are for all retail and do not answer it.

**Disconfirming check:** A store could hold low sealed inventory and keep
singles online-only to cap exposure. That also caps what the display case
sells. A quote for a BOP with $50,000 and $100,000 inventory limits, burglary
coverage included, settles the insurance line.

---

## 11. What does staff cost, and what does the owner work?

**Finding:** Retail salespersons in the Michigan City-La Porte MSA earned a
median $14.35/hr and a mean $16.07/hr in May 2025. The owner covers 45 to 60
hours a week in a one-employee store that runs evening events.

**Confidence:** fact (wages); estimate (owner hours)
**Source:** BLS Occupational Employment and Wage Statistics, May 2025,
Michigan City-La Porte MSA (area 33140), via the BLS Public Data API, series
OEUM003314000000041203101 (employment), ...03 (mean hourly), ...08 (median
hourly), ...06 (10th pct), ...07 (25th pct), and 41201101/41201103/41201108
for cashiers; <https://api.bls.gov/publicAPI/v2/timeseries/data/> . Release:
BLS Midwest Information Office, "Occupational Employment and Wages in Michigan
City-La Porte, May 2025," released Friday 2026-07-10,
<https://www.bls.gov/regions/midwest/news-release/occupationalemploymentandwages_michigancity.htm>
**Retrieved:** 2026-09-30

| Occupation, May 2025 | Employment | 10th pct | 25th pct | Median | Mean |
|----------------------|-----------:|---------:|---------:|-------:|-----:|
| Retail salespersons (41-2031) | 1,460 | $10.98 | $13.17 | $14.35 | $16.07 |
| Cashiers (41-2011) | 1,040 | | | $13.71 | $13.82 |
| First-line supervisors, retail (41-1011) | | | | $21.75 | |
| All occupations, mean | | | | | $26.16 |

This release supersedes the May 2024 food-service figure in
the earlier frozen-yogurt study ([operating-costs.md](https://github.com/ernieayala/froyo/blob/main/research/operating-costs.md)), which was 27 months old. The regional release
reports sales and related occupations at $20.87/hr mean; that group includes
higher-paid sales roles and overstates a counter wage.

**Owner hours, estimate.** Hours posted by nearby stores, retrieved 2026-09-30:
Game Changers, 58 hr/wk (Mon-Thu 10-6, Fri-Sat 10-8, Sun 11-5;
<https://www.lgsfinder.org/indiana/michigan-city/game-changers-michigan-city>);
NWI Cards, Merrillville, 36.5 hr/wk, closed Mon-Tue
(<https://www.nwicards.com/pages/visit>). A store open 48 hr/wk (Tue-Fri 12-8,
Sat 10-8, Sun 12-6) with one 25 hr/wk employee leaves 23 hr of floor time for
the owner. Friday Night Magic and league nights run past close. Buying,
singles pricing, online listing and event reporting add 10-15 hr/wk (`guess`).
Evening events need two people on the floor for theft reasons (section 10).
Result: 45-60 owner hours a week, most of them evenings and weekends.

**Disconfirming check:** If the owner does not draw pay, the store looks
profitable while it consumes a full-time job. A financial model must price owner
labor at the BLS supervisor median, $21.75/hr, or state that it does not.

---

## 12. Events and existing play: demand signal and competition

**Finding:** Michigan City has tabletop play but no publisher-sanctioned card
play. Heroes Haven runs a tabletop room; Game Changers sells video games and,
per one aggregator, some TCG; a card show with 100+ tables runs monthly.
Neither public library runs a trading card club.

**Confidence:** sourced
**Source:** see list
**Retrieved:** 2026-09-30

- **Heroes Haven Comics & Games, 296-A E US Hwy 20.** A third-party directory,
  MyStore411, lists it as a "Wizards Play Network Store"
  (<https://www.mystore411.com/store/view/24378007/Wizards-of-the-Coast-Michigan-City>).
  The Wizards locator's own API, queried the same day, does not list it
  ([competition.md](competition.md)); the primary source wins, so treat it as not
  a WPN store until Heroes Haven says otherwise.
  Search summaries describe Magic, HeroClix and Warhammer play and a separate
  tabletop room (Yelp and Facebook pages returned 403). Whether it runs Pokémon,
  One Piece or Lorcana events is unknown.
- **Game Changers, 4303 Franklin St** (inside Lake Park Plaza). 4.7 stars, 446
  reviews; carries "other trading card games" and board games, video games.
  LGS Finder, <https://www.lgsfinder.org/indiana/michigan-city/game-changers-michigan-city> .
  LGS Finder lists it as "the sole game store currently listed in Michigan City
  proper" and nine more within 25 miles.
- **The Michigan City Card and Pokemon Show**, FOP Lodge #75, 416 US-20: dates
  2026-10-17 (100+ tables) and 2026-12-12. Section 2.
- **Pokémon league leads, all from search-result summaries:** Reliquary
  Gaming, Chesterton, 11.0 mi (pokemon.com league page 6238436, per
  [competition.md](competition.md)); Porter County Pokemon League at Galactic
  Greg's, 1407 E Lincolnway, Valparaiso, 19.5 mi (league page 4479). Both pages
  returned a bot check. No league in Michigan City appeared. High Heat Cards &
  Collectibles in La Porte appeared in the second summary as a lead, unverified.
- **Michigan City Public Library**, October 2026 calendar
  (<https://www.mclib.org/events>): D&D for Kids (Oct 7), Board Game Night for
  Adults (Oct 13), Ultimate Werewolf (Oct 26). No Pokémon, Magic or trading card
  program.
- **La Porte County Public Library** upcoming events
  (<https://www.laportelibrary.org/events/upcoming>): no card or tabletop game
  program.
- **Schools:** no card game club was found for Michigan City Area Schools or
  Marquette Catholic. Searches returned nothing either way.

**What it means.** The gap in Michigan City looks like Pokémon and the newer
games (One Piece, Lorcana) with youth events, since the incumbents lean
toward Magic, miniatures, comics and video games. That reading rests on
directory text, not on their event calendars. The library's D&D and board game
nights show it programs for tabletop audiences, so a library partnership for a
learn-to-play Pokémon night is a cheap demand test.

**Disconfirming check:** If Heroes Haven already runs a Pokémon league or One
Piece nights, the gap closes and a new store splits a small player base. Call
Heroes Haven (219-809-9191) and Game Changers (219-879-7930), or attend one
event night at each, and count players. The Pokémon locator blocked automated
retrieval; the Wizards locator was read through its API
([competition.md](competition.md)). A browser check of events.pokemon.com for
46360 settles which Pokémon events run where.

---

## Still unknown

- **Player counts at existing events.** Attend an event night at Heroes
  Haven and any Game Changers event; count heads. This is the single best
  demand measurement available.
- **Which games Heroes Haven and Game Changers sanction.** Wizards and Pokémon
  locators in a browser, or a phone call.
- **NNN charges on Park and Shop and Lake Park Plaza.** Call Bradley Company
  (219-508-0554) and EDC Michigan City (219-873-1211).
- **Whether a second exit exists in any candidate bay**, and whether Michigan
  City's zoning treats sanctioned tournaments with entry fees as retail or as
  indoor recreation. Planning and Zoning, 219-873-1419.
- **City permit and sign fees, and whether "business registration" carries a
  fee.** Building dept 219-873-1417 or the Cloudpermit portal.
- **Insurance quote** for a BOP with $50,000-$100,000 inventory limits and
  burglary coverage for collectibles.
- **Fees for Wizards Play Network and Play! Pokémon store membership.** The
  venue requirements are in [distribution-and-supply.md](distribution-and-supply.md),
  sections 1.1 and 1.2.
- **PNW Westville headcount** and students living in 46360. PNW registrar.
- **Share of group quarters in Michigan City that is correctional.** ACS table
  B26101 or 2020 Census group quarters counts.
- **Sports-card buyer demographics** from a survey with published methodology
  and an age-by-gender split. YouGov's tracker exists
  (<https://yougov.com/en-us/trackers/fame-and-popularity-sports-card-collecting>)
  but its numbers did not render.
- **Whether summer tourists buy cards.** Log customer ZIP codes for one summer,
  or ask Game Changers what July does against February.

## Re-check schedule

| Figure | Re-check by | Why |
|--------|-------------|-----|
| ACS 2020-2024 5-year demographics | 2026-12-31 | ACS 2021-2025 5-year releases in December |
| Listing rents (1601 Franklin, 3200 Franklin, 5510, 5172) | 2026-12-25 | Rent quotes go stale in 6 months; listings updated 2026-06-25 |
| BLS OEWS May 2025 wages | 2027-07-15 | May 2026 estimates expected mid-2027 |
| POS pricing and BinderPOS onboarding pause | 2027-03-30 | Vendor pricing moves; the pause may lift |
| Insureon medians (updated 2025-01-03) | Now | 21 months old, past the 18-month threshold, and proxy data only |
| Topps presale box prices | Per release | Each product line prices separately |
| CivicScience (2021) and Seton Hall (2024) collector data | Now | Both past 18 months; replace with a current survey |
| PNW enrollment | 2027-09-30 | Fall census date |
| Heroes Haven and Game Changers event programs | 2027-01-15 | Competitor programs change with each game release |
| Indiana building code edition (2012 IBC base) | Before any lease | A newer adopted edition would change the occupant load and assembly thresholds |
