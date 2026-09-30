# Local and Regional Competition for TCG and Sports Card Product

> Last updated: 2026-09-30

Scope: stores selling Pokémon, One Piece, Magic: The Gathering, Lorcana, Yu-Gi-Oh!, and sports cards
within roughly 45 minutes of Michigan City, IN 46360. Distances are straight-line miles from
41.7075, -86.8950 (central Michigan City), computed by us with the haversine formula from coordinates
the publisher locators return. Drive distance runs longer. Treat every distance as `estimate`.

## What the principal reported

**Finding:** The repo owner reports four things about local competition, recorded here as testimony before any check.
**Confidence:** guess
**Source:** Repo owner, verbal, relayed through the project coordinator
**Retrieved:** 2026-09-30

1. A comic book shop in Michigan City carries a small TCG selection: some Pokémon, some One Piece, a few boxes at most.
2. A sports card shop near New Buffalo (Michigan side) deals in sports cards first, with some Pokémon, and prices 50-80% above market.
3. Shops in La Porte price about 20% above market.
4. The next nearest options after those are the La Porte shops.

Results of the checks below:

| Claim | Status | Basis |
|-------|--------|-------|
| 1. Michigan City comic shop, small TCG selection | Consistent, not verified | The only comic shop found is Heroes Haven Comics & Games. Its own site and listings describe comics, Magic, HeroClix, Warhammer. No publisher locator lists it. Pokémon and One Piece stock depth not checkable online |
| 2. New Buffalo sports shop, some Pokémon, 50-80% over market | Shop exists and is sports-first; price claim not verified | The Sports Card Shop, 18853 US Hwy 12, New Buffalo, MI. Its site blocks automated retrieval, so no prices were read |
| 3. La Porte shops about 20% over market | Not verified | Neither La Porte card shop publishes a price list found online |
| 4. La Porte shops are the next nearest | Contradicted in part | Reliquary Gaming in Chesterton is 11.0 mi, the same distance as High Heat in La Porte (11.0 mi), and runs more organized play than either La Porte shop |

## Which authorized stores do the publisher locators show near 46360?

**Finding:** The Wizards locator lists zero WPN stores in Michigan City; the nearest three are 11.0 to 11.5 mi away (Reliquary Gaming, Chesterton; High Heat Cards & Collectibles and Goblin Cards & Collectibles, La Porte).
**Confidence:** fact
**Source:** Wizards Store & Event Locator backend, `https://api.tabletop.wizards.com/silverbeak-griffin-service/graphql`, query `storesByLocation` at lat 41.7075, lon -86.8950, radius 80,467 m (50 mi). Store pages: https://locator.wizards.com/store/14726 , https://locator.wizards.com/store/23837 , https://locator.wizards.com/store/15353
**Retrieved:** 2026-09-30

The query returned 55 stores within 50 mi, sorted by distance. The web front end at
https://locator.wizards.com renders results client-side, and a plain fetch of the search URL showed
"No results found", so the list came from the API the page itself calls. Nearest WPN stores:

| Store | Address | Miles |
|-------|---------|-------|
| Reliquary Gaming | 1585 S Calumet Rd, Chesterton, IN 46304 | 11.0 |
| High Heat Cards & Collectibles | 103 J St, La Porte, IN 46350 | 11.0 |
| Goblin Cards & Collectibles | 603 E Lincolnway, La Porte, IN 46350 | 11.5 |
| HB Cards | 1703 Calumet Ave, Valparaiso, IN 46383 | 17.4 |
| GameStop 5052 | 2710 Laporte Ave, Valparaiso, IN 46383 | 17.9 |
| Dragon's Lair Cards and Comics | 3369 Willowcreek Rd, Portage, IN 46368 | 18.2 |
| GameStop 6958 | 6133 US-6, Portage, IN 46368 | 18.2 |
| Galactic Gregs, Inc | 1407 E Lincoln Way, Valparaiso, IN 46383 | 19.5 |
| The Shop Collectibles LLC | 10971 4 Seasons Pl, Crown Point, IN 46307 | 26.6 |
| Schmoley's Games and More | 1946 N Main St, Crown Point, IN 46307 | 30.4 |
| Slice and Dice Game Cafe | 20950 W Ireland Rd, South Bend, IN 46614 | 32.6 |
| Fantasy Games | 52025 State Rd 933, South Bend, IN 46637 | 33.3 |
| Reddhill Electronics and Games | 105 E Main St, Niles, MI 49120 | 33.9 |
| Topps Trade Center | 1609 Mall Dr, Benton Harbor, MI 49022 | 35.5 |
| Rivals Gaming | 102 N Center St, Mishawaka, IN 46544 | 36.6 |

Posted Magic events on 2026-09-30 (locator store pages):

| Store | Posted events |
|-------|---------------|
| Reliquary Gaming | Reality Fracture Draft Fri Oct 2, $35; free play Sun Oct 4; Commander Party Fri Oct 9, $10; Star Trek prerelease Fri Nov 6, $40 |
| Dragon's Lair (Portage) | Friday Night Magic Commander every Friday Oct 2 to Dec 4, 4:00 PM, 40-player cap |
| HB Cards (Valparaiso) | Commander open play every Tuesday Oct 6 to Nov 24, 12:00 PM |
| High Heat (La Porte) | "No upcoming events at this store" |
| Goblin (La Porte) | "No upcoming events at this store" |

**Disconfirming check:** A third-party page (https://www.mystore411.com/store/view/24378007/Wizards-of-the-Coast-Michigan-City, retrieved 2026-09-30) lists Heroes Haven Comics & Games as a "Wizards Play Network Store". The Wizards API, the primary source, does not list it. Heroes Haven either left WPN or the mirror is stale. An unposted event is not proof of no event: La Porte shops may run Magic nights they do not post. A phone call to each settles it.

---

**Finding:** The Ravensburger play platform lists no Lorcana store in Michigan City; the nearest Lorcana organized-play stores are Reliquary Gaming (11.0 mi) and High Heat (11.0 mi). Goblin is not listed for Lorcana.
**Confidence:** fact
**Source:** `https://api.ravensburgerplay.com/api/v2/game-stores/?latitude=41.7075&longitude=-86.895&num_miles=50` (71 store-game rows, 2 pages)
**Retrieved:** 2026-09-30

Lorcana stores within 25 mi: Reliquary Gaming (Chesterton, 11.0), High Heat (La Porte, 11.0), HB Cards
(Valparaiso, 17.4), Dragon's Lair (Portage, 18.2), Underground Case Breaks (Hobart, 22.2). The same feed
lists Riftbound (Riot's TCG, distributed through the same platform) at Reliquary, HB Cards, Dragon's Lair,
Nu Yeer Games (Hobart), Underground Case Breaks, NWI Cards (Merrillville, 26.2), and The Shop Collectibles.

**Disconfirming check:** A store can sell Lorcana without registering on the platform. Absence from the list means no registered Lorcana organized play, not zero Lorcana sales.

---

**Finding:** Konami's Official Tournament Store list shows no Yu-Gi-Oh! OTS in LaPorte or Porter County except one address in Portage (3369 Willowcreek Rd, the Dragon's Lair address), about 18 mi away.
**Confidence:** sourced
**Source:** https://img.yugioh-card.com/en/downloads/ots/KonamiOTS_2026-0827.pdf (linked from https://www.yugioh-card.com/en/events/ots-locations/)
**Retrieved:** 2026-09-30

The PDF is dated 2026-08-27. Our text extraction misaligned the name and address columns: the Portage
row reads "Next Level Games" at the Dragon's Lair street address, and the Mishawaka row reads "Krypton
Comics" at the Rivals Gaming address. The addresses are the reliable field. Searching the text for
Michigan City, La Porte, Chesterton, Valparaiso, Merrillville, Hobart, Crown Point, South Bend, New Buffalo,
Three Oaks, and Bridgman returned no rows. Confidence is `sourced`, not `fact`, because of the column
misalignment.

**Disconfirming check:** Open the PDF in a viewer and confirm the Portage and Mishawaka store names. Not done.

---

**Finding:** The Pokémon Event Locator and the Bandai TCG+ One Piece locator could not be retrieved.
**Confidence:** n/a (not retrieved)
**Source:** https://events.pokemon.com/EventLocator/ (Incapsula bot block); https://www.pokemon.com/us/play-pokemon/pokemon-events/leagues/6238436/ (bot check); `https://api.bandai-tcg-plus.com/api/user/event/list` (HTTP 403)
**Retrieved:** 2026-09-30 (attempted)

A search-engine snippet of pokemon.com league page 6238436 names Reliquary Gaming, 1585 S Calumet Rd,
Chesterton, as a Pokémon League venue. The page itself returned a bot check, so this is `sourced` at best
and unconfirmed. A Chesterton town calendar entry (https://www.chestertonin.org/Calendar.aspx?EID=1058)
shows a past Pokémon League at Thomas Library, Tuesdays 6:30 to 8:00 PM, which the search summary dated
to 2015; it indicates past local demand, nothing current. A search result pointing to "Space Goblin
Collectibles" league 6242919 led to a store in Austin, TX, unrelated to Goblin in La Porte.

**Disconfirming check:** Open the Pokémon Event Locator and the Bandai TCG+ app in a normal browser, search 46360 at 25 and 50 mi, and record every store and event. This is a 15-minute field task.

## Who sells TCG or sports cards within 45 minutes?

**Finding:** Michigan City has one comic and game shop (Heroes Haven) and one video game store (Game Changers); no publisher locator we queried lists either, and every locator-listed TCG store is 11 mi or more away.
**Confidence:** fact for locator absence; sourced or guess per row below
**Source:** see roster
**Retrieved:** 2026-09-30

### Roster

Columns: Dist = straight-line miles (estimate). WPN = Wizards locator 2026-09-30. Lorc = Ravensburger
platform 2026-09-30. Sports = sells sports hobby product. Breaks = runs box breaks. "n/c" = not checked or
not retrievable.

| Name | Town / address | Dist | Games | Organized play | WPN | Lorc | Sports hobby / brands | Breaks | Source | Confidence |
|------|----------------|------|-------|----------------|-----|------|-----------------------|--------|--------|------------|
| Heroes Haven Comics & Games | 296-A E US Hwy 20, Michigan City | ~2-3 | Comics, Magic, HeroClix, Warhammer 40K, RPGs; principal reports small Pokémon and One Piece stock | Tabletop room; no publisher-listed events | No (mirror says yes, stale) | No | None found | None found | http://www.heroeshavenmc.com/ (expired TLS cert, read with verification off) | sourced |
| Game Changers | 4303 Franklin St, Michigan City | ~2 | Video games, retro; an aggregator guesses "other TCGs" | None listed | No | No | n/c | n/c | https://www.lgsfinder.org/indiana/michigan-city/game-changers-michigan-city | guess |
| Michigan City Card & Pokémon Show | FOP Lodge #75, 416 US-20, Michigan City | ~2 | Pokémon, sports cards (dealer tables) | Monthly Saturday show, 9 AM to 3 PM, free entry, "100 tables"; dates Sep 19, Oct 17, Nov 21, Dec 12, 2026 | n/a | n/a | Yes, dealer tables | n/c | https://cardshows.io/events/michigan-city-sports-card-and-pokemon-show-10-17-2026 ; https://www.treasurehunter.show/show/the-michigan-city-card-and-pokemon-show-michigan-city-in-2026-09-19 | sourced |
| The Sports Card Shop (New Buffalo) | 18853 US Hwy 12, New Buffalo, MI 49117 | ~10 | Sports cards; Pokémon (principal; SCD 2023 said it planned to expand Pokémon) | Release-day events, card shows (search snippet of own site) | No | No | Topps, Panini, hobby boxes, singles (search snippet of own site) | 2023 profile: family avoids breaks by choice; later site snippet: live box breaks via its marketplace. Conflicting | https://sportscollectorsdigest.com/news/sports-card-shop-new-buffalo-michigan-gotcher-family-hobby-collectibles (2023-01-12); https://thesportscardshop.com/ (blocked by Vercel checkpoint) | sourced |
| The Sports Card Shop (Valparaiso) | 118 Lincolnway, Valparaiso, IN | ~18 | Sports cards | n/c | No | No | Yes (same owner) | n/c | Search snippet of thesportscardshop.com/about | guess |
| Reliquary Gaming | 1585 S Calumet Rd, Chesterton, IN 46304 | 11.0 | Magic, Lorcana, Riftbound; Pokémon League (snippet) | Weekly posted Magic events, drafts, prereleases; Lorcana and Riftbound OP; Discord | Yes | Yes | n/c | n/c | Wizards API; Ravensburger API; https://locator.wizards.com/store/14726 | fact (WPN, Lorcana); sourced (Pokémon) |
| High Heat Cards & Collectibles | 103 J St, La Porte, IN 46350 | 11.0 | Sports cards, Pokémon, Magic, Lorcana, other TCGs | Lorcana OP registered; no posted Magic events | Yes | Yes | Yes, brands n/c | n/c | Wizards API; Ravensburger API; La Porte Herald-Dispatch grand-opening coverage (page returned HTTP 429, known from search snippet only); https://lpchamber.chambermaster.com/list/member/high-heat-cards-and-collectibles-4770.htm (not fetched) | fact (WPN, Lorcana); sourced (products) |
| Goblin Cards & Collectibles | 603 E Lincolnway, La Porte, IN 46350 | 11.5 | Magic, Pokémon, Yu-Gi-Oh!, Flesh and Blood, sports cards (listings) | No posted Magic events; free play area (listing) | Yes | No | Yes per listings, brands n/c | Whatnot account "goblincollectibles" exists; link to this store unconfirmed | Wizards API; https://goblincardsandcollectibles.com/ (hours Wed-Thu 12-8, Fri 10-9, Sat 10-8, Sun 10-6, closed Mon-Tue) | fact (WPN, hours); guess (products) |
| Monroe's Collectibles Toys & Comics | 515 State St, La Porte, IN 46350 | ~11 | Toys, comics, graded collectibles; aggregator lists Magic | n/c | No | No | n/c | n/c | https://www.lgsfinder.org/indiana/la-porte | guess |
| Sky Games & Novelties | 713 Monroe St, La Porte, IN 46350 | ~11 | Board games | n/c | No | No | n/c | n/c | https://www.lgsfinder.org/indiana/la-porte | guess |
| KeyCards LLC | La Porte (address unknown) | n/c | Listed as One Piece seller by a directory | n/c | No | No | n/c | n/c | Search-result summary only; no page retrieved | guess |
| The Cosmic Rip | Online; a listing puts it at a rural La Porte address, Facebook says Valparaiso | n/a | Pokémon singles, graded, sealed (19 products, 3 in stock) | None | No | No | No | No | https://thecosmicrip.com/products.json | fact (catalog); guess (location) |
| HB Cards | 1703 Calumet Ave, Valparaiso | 17.4 | Magic, Lorcana, Riftbound | Weekly Commander open play Tuesdays | Yes | Yes | n/c | n/c | Wizards API; https://locator.wizards.com/store/21526 | fact |
| Dragon's Lair Cards and Comics | 3369 Willowcreek Rd, Portage | 18.2 | Magic, Lorcana, Riftbound, Heroscape; Yu-Gi-Oh! OTS at this address | Friday Night Magic Commander weekly | Yes | Yes | n/c | n/c | Wizards API; Ravensburger API; Konami OTS PDF | fact |
| Galactic Greg's | 1407 E Lincolnway, Valparaiso | 19.5 | Comics, games, trading cards; "since 1990" | n/c | Yes | No | n/c | n/c | https://www.galacticgregs.com/ ; Wizards API | fact |
| GameStop 5052 / 6958 | Valparaiso / Portage | 17.9 / 18.2 | Sealed TCG | WPN listed | Yes | No | n/c | No | Wizards API | fact |
| Endzone Sport Cards | Valparaiso | ~18 | Sports cards | n/c | No | No | Yes | n/c | Yelp listing title only | guess |
| Nu Yeer Games | 154 S Illinois St, Hobart | 21.8 | Riftbound | OP registered | No | No | n/c | n/c | Ravensburger API | fact |
| Underground Case Breaks | 206 Main St, Hobart | 22.2 | Lorcana, Riftbound; name indicates sports case breaks | OP registered | No | Yes | Likely, n/c | Likely by name, n/c | Ravensburger API | fact (listing); guess (breaks) |
| NWI Cards | 5350 Broadway, Merrillville | 26.2 | Riftbound | OP registered | No | No | n/c | n/c | Ravensburger API | fact |
| Fantasy Games | 52025 State Rd 933, South Bend | 33.3 | Magic, Lorcana, Riftbound, Pokémon, Yu-Gi-Oh! | Tournament venue | Yes | Yes | n/c | n/c | Wizards API; Ravensburger API | fact |
| Rivals Gaming | 102 N Center St, Mishawaka | 36.6 | Magic, Lorcana, Riftbound; Yu-Gi-Oh! OTS at this address | OP registered | Yes | Yes | n/c | n/c | Wizards API; Ravensburger API; Konami PDF | fact |
| Topps Trade Center | 1609 Mall Dr, Benton Harbor, MI | 35.5 | Sports cards; Magic (WPN) | n/c | Yes | No | Yes by name, brands n/c | n/c | Wizards API | fact (WPN) |

Towns in scope with no store found in any source: Long Beach, Michiana Shores, Three Oaks (16.0 mi),
Bridgman (23.8 mi), Porter, Westville (11.5 mi). "No store found" means none appeared in the Wizards API,
the Ravensburger API, the Konami PDF, or the directories searched. It does not rule out a shop with no web
presence.

**Disconfirming check:** Directory listings (indianatcg.com, lgsfinder.org) are aggregators of mixed quality and can list closed or misclassified businesses. The Hi5 Cards result that surfaced for Michigan City is a Bloomington, IN business (https://hi5cardsandcollectiblesin.com/) and was excluded. The Gaming Geeks (2356 N Wozniak Rd, Michigan City) makes tabletop art and accessories and is not a card retailer (https://www.thegaminggeeks.net/); excluded.

## Is Michigan City underserved, or too small to support a better shop?

**Finding:** No publisher-authorized TCG store operates in Michigan City, and the closest three sit 11.0 to 11.5 mi away; the evidence does not distinguish between an underserved market and one too small to support a shop.
**Confidence:** estimate
**Source:** Wizards API, Ravensburger API, Konami PDF (above)
**Retrieved:** 2026-09-30

An absent competitor is ambiguous. Readings that fit the same facts:

- Underserved: Michigan City players drive 11+ mi to Chesterton or La Porte for events, and a local store captures them.
- Too small: an 11 mi drive is short enough that the regional stores already absorb Michigan City demand, and the town cannot fill a dedicated store's events on its own.
- Served by other channels: the monthly 100-table card show at the FOP Lodge, online marketplaces (TCGplayer, eBay, Whatnot), and big-box sealed product meet local demand without a storefront.

The first reading is the favorable one. It has the least direct evidence behind it here.

**Disconfirming check:** Look for who tried a TCG-focused store in Michigan City before and stopped (next section). Count attendance at Reliquary's and High Heat's events and ask how many players live in Michigan City. Neither was done.

## Who tried before and stopped?

**Finding:** The only confirmed closure found is GameStop at Michigan City Town Center, 5330 Franklin St, on a January 2025 closure list; no closed independent card or game shop in Michigan City or LaPorte County was found in online news.
**Confidence:** sourced
**Source:** https://www.newsweek.com/gamestop-stores-closing-2025-full-list-2029930 (published 2025-02-12; list compiled from an unofficial blog tracking GameStop's store locator)
**Retrieved:** 2026-09-30

Corroboration: the Wizards API lists GameStop WPN stores in Valparaiso and Portage and none in Michigan
City. GameStop's own store page (https://www.gamestop.com/store/us/in/michigan-city/5453/michigan-city-town-center-gamestop)
returned HTTP 403.

Other history found:

- A February 2014 post calls Heroes Haven a new storefront in downtown Michigan City (https://haterfreewednesdays.tumblr.com/post/78015402262/heroes-haven-in-michigan-city-in, a personal blog; `guess`). It now operates at 296-A E US Hwy 20. That reads as a relocation, not a closure. Cause unknown.
- Game Changers opened inside Marquette Mall, Michigan City, in 2011 and moved to 4303 Franklin St after growing from 800 to 4,000 sq ft (search snippet of the store's own description; `guess`). Relocation, not closure.
- High Heat opened in La Porte with a grand opening September 12 (year not confirmed; La Porte Herald-Dispatch article returned HTTP 429). Listings call Goblin a recent opening. Both La Porte card shops appear to be post-2020 openings, which means the La Porte market has not yet shown it sustains them through a downturn.

**Disconfirming check:** Online news search returned nothing, which is weak evidence of no closures. Local papers (The News-Dispatch, La Porte Herald-Dispatch) sit behind rate limits and paywalls. Ask Heroes Haven's owner (Patrick, per the store site) and the FOP card-show organizer (219-229-0411) which card or game shops have opened and closed in Michigan City since 2015. Search INBiz for dissolved entities with "cards", "comics", "games", or "collectibles" in the name and a Michigan City or La Porte address. INBiz was not queried.

## Which big-box stores compete on sealed product?

**Finding:** Michigan City has a Walmart Supercenter and a Meijer; it has no Target, no Barnes & Noble, and, since January 2025, no GameStop.
**Confidence:** fact for store existence; guess for what each stocks
**Source:** Walmart store 1487, 5780 Franklin St (https://www.walmart.com/store/1487-michigan-city-in); Meijer store 149, 5150 S Franklin St (https://www.meijer.com/shopping/store-locator/149.html, HTTP 403, address from search snippet); Target Indiana directory lists no Michigan City or La Porte store (https://www.target.com/store-locator/store-directory/indiana); Barnes & Noble nearest in Valparaiso (store 2138) and Mishawaka (store 2358), Merrillville closed (https://stores.barnesandnoble.com/store/2138)
**Retrieved:** 2026-09-30

| Retailer | Nearest location | Likely TCG / sports product | Confidence on stock |
|----------|------------------|-----------------------------|---------------------|
| Walmart | 5780 Franklin St, Michigan City; also La Porte (store 2276) | Pokémon sealed, sports blasters, hangers, megas | guess |
| Meijer | 5150 S Franklin St, Michigan City | Pokémon sealed, sports blasters and hangers | guess |
| Target | Valparaiso (~18 mi) | Pokémon, One Piece, sports retail | guess |
| Barnes & Noble | Valparaiso (~18 mi), Mishawaka | Pokémon, some Magic | guess |
| GameStop | Valparaiso, Portage (WPN listed) | Pokémon, Magic, One Piece | fact (WPN); guess (others) |
| Walgreens / CVS | Michigan City (locations not checked) | Pokémon blisters, sports packs | guess |
| Lighthouse Place Premium Outlets | 601 Wabash St, Michigan City | The directory page loads its store list client-side; the eight featured stores are apparel. No toy or card tenant seen | not verified |

Big-box stock is intermittent and allocation-driven. When in stock it sells at MSRP, which sets the
price ceiling a local shop can charge on sealed product without losing the informed buyer.

**Disconfirming check:** Walk Walmart, Meijer, and the Franklin St Walgreens and CVS on two dates (a weekday and a new-set release week). Record facings for Pokémon, One Piece, Magic, Lorcana, Topps, Panini, Bowman, and whether shelves are empty. Not done.

## Sports hobby product and authorized-retailer locators

**Finding:** The Sports Card Shop (New Buffalo and Valparaiso) is the sports-first competitor in range; the Topps/Fanatics and Panini hobby-shop locators could not be retrieved, so authorized-retailer status for any local shop is unknown.
**Confidence:** sourced (shop), n/a (locators)
**Source:** https://sportscollectorsdigest.com/news/sports-card-shop-new-buffalo-michigan-gotcher-family-hobby-collectibles ; https://ripped.topps.com/hobby-shops/ (HTTP 403); https://paninipod.com/nba-player-of-the-day/shop-locator/ (page loads store data through a WordPress AJAX call we did not reproduce)
**Retrieved:** 2026-09-30

The Sports Collectors Digest profile (John Newman, 2023-01-12) says the Gotcher family's shop started
in 2017, reports that sales almost doubled each year, and says the family chose not to run breaks or bulk
grading submissions (paraphrase from a fetched summary; confirm exact wording against the article). A later search snippet of the shop's own site describes live box breaks and auctions
through its online marketplace and a second store at 118 Lincolnway, Valparaiso. The two sources conflict
on breaks; the newer one is a snippet we could not open. High Heat, Goblin, and Topps Trade Center carry
sports cards per listings; brand lines and hobby-box depth are unknown. Underground Case Breaks (Hobart,
22.2 mi) suggests a case-break operation by name only.

**Disconfirming check:** Retrieve the Topps hobby-shop locator and Panini's list in a normal browser for 46360. Ask The Sports Card Shop, High Heat, and Goblin directly whether they hold direct accounts with Fanatics Collectibles (FC Pro) and Panini. A separate workstream covers sports-card distribution economics.

## Can the principal's pricing claims be verified?

**Finding:** No. None of the named shops publishes sealed-product prices that could be retrieved on 2026-09-30, so the 50-80% (New Buffalo) and 20% (La Porte) markups remain `guess`.
**Confidence:** guess
**Source:** thesportscardshop.com (Vercel security checkpoint, HTTP 429); goblincardsandcollectibles.com (no product catalog, `/products.json` HTTP 404); High Heat (no web store found); Heroes Haven (no web store)
**Retrieved:** 2026-09-30

The only local-area seller with a readable catalog is The Cosmic Rip, an online Pokémon seller (19
products, 3 in stock). It lists a Pokémon 151 Elite Trainer Box at $169.95 and a Prismatic Evolutions
Surprise Box at $199.99, both out of stock. These are collector-market prices for out-of-print product and
say nothing about a storefront's markup on current sealed product. We did not pull TCGplayer market prices
for comparison, because no storefront prices exist to compare them against.

A 20% or 50-80% premium over market would be plausible for a shop pricing sealed product against
MSRP-scarcity, and implausible for current in-print product that Walmart and Meijer sell at MSRP. Which
of those the principal observed is unknown.

Field check that would verify it (one afternoon per shop, same day for all):

1. Pick 10 SKUs on the same date: Pokémon current-set booster bundle, Pokémon current-set ETB, Pokémon current-set booster pack, Pokémon 151 or Prismatic Evolutions ETB (out of print), One Piece current booster box, One Piece single pack, Magic current Play Booster box, Lorcana current booster box, Topps Series 2 hobby box, Panini Prizm (current sport) blaster.
2. Record shelf price at Heroes Haven, The Sports Card Shop (New Buffalo), High Heat, Goblin, Walmart, and Meijer. Photograph price tags.
3. Pull TCGplayer Market Price and MSRP for each SKU the same day.
4. Compute markup = shelf / TCGplayer market - 1, and shelf / MSRP - 1, per SKU per shop. Report the median per shop and the range.

**Disconfirming check:** If the survey finds La Porte shops within 10% of TCGplayer market on in-print product, the "20% above market" claim fails and the pricing gap a new shop could exploit is smaller than assumed.

## What is the biggest competitive risk?

**Finding:** Reliquary Gaming in Chesterton (11.0 mi) already runs the posted, multi-game organized play (Magic weekly, Lorcana, Riftbound, and a Pokémon League per snippet) that a Michigan City store would need to build its community around, and the monthly 100-table card show in Michigan City already sells Pokémon and sports cards in town.
**Confidence:** estimate
**Source:** sections above
**Retrieved:** 2026-09-30

Pricing competition from the La Porte and New Buffalo shops is the principal's thesis for entry. It is
unverified. Organized-play competition from Chesterton and dealer-table competition from the FOP show are
verified. A new store that wins on price but not on events competes with Walmart, Meijer, TCGplayer, and
Whatnot for the price-sensitive buyer, a fight a small shop loses on sealed product.

The assumption that flips this: if Michigan City players will not drive 11 mi for weekly events and
today play at home or not at all, the regional stores do not capture them and a local event space
has an open field. The field work below tests that.

## Still unknown

- Whether Heroes Haven stocks Pokémon and One Piece, how many SKUs, and at what price. Visit and run the 10-SKU survey.
- Whether Heroes Haven left WPN or never joined. Ask the owner.
- Pokémon League and One Piece store-tournament venues within 25 mi. Query the Pokémon Event Locator and Bandai TCG+ app in a browser.
- Whether Goblin and High Heat run unposted Magic, Pokémon, or One Piece nights, and attendance. Call both; attend one event at Reliquary and one at High Heat and count players, asking each for their home town.
- Sports hobby authorized-retailer status for every sports seller in range. Topps and Panini locators in a browser, then ask the shops.
- Closed card or game shops in Michigan City or LaPorte County since 2015. INBiz dissolved-entity search; ask Heroes Haven's owner and the card-show organizer.
- Card show vendor count and turnover. Attend the October 17, 2026 show at the FOP Lodge, count tables, and note how many dealers are Pokémon-first.
- Big-box stock and restock days at Walmart and Meijer on Franklin St. Two store walks.
- Whether KeyCards LLC in La Porte exists as a storefront. INBiz lookup and a drive-by.
- Year High Heat opened. Retrieve the La Porte Herald-Dispatch article when not rate-limited.

## Re-check schedule

| Figure | Re-check by | Why |
|--------|-------------|-----|
| Wizards WPN store list within 50 mi of 46360 | 2027-03-30 | Store roster changes; re-run the API query |
| Posted Magic events at Reliquary, High Heat, Goblin | 2026-12-31 | Event calendars change monthly |
| Ravensburger Lorcana / Riftbound store list | 2027-03-30 | New registrations |
| Konami OTS PDF (dated 2026-08-27) | 2027-03-30 | Konami reissues the list |
| Michigan City Card & Pokémon Show schedule and table count | 2026-12-12 | Show dates listed only through December 2026 |
| Principal's markup claims (20%, 50-80%) | Before any decision uses them | Unverified; replace with the 10-SKU survey |
| Big-box stock observations | 2027-03-30 | Allocation and shelf space shift by set release |
| GameStop Michigan City closure | 2027-09-30 | Confirm no reopening |
| Sports Card Shop breaks policy | 2027-03-30 | Sources conflict |
