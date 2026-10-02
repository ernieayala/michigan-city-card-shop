# Online-Only TCG Selling from Indiana: Fees, Shipping, Competition, Supply, and Legal Setup

> Last updated: 2026-10-02

## Summary

Selling cards online from Indiana costs 11% to 15% in marketplace fees before
postage: a $100 single nets $78.81 on TCGplayer after fees and postage. New TCGplayer sellers start
capped at 100 items and $1,000 listed, and new registration may be paused. An
online-only seller gets no distributor account and competes on price against
198 to 263 listings on popular cards, so its margin comes only from buying
below market. Indiana tax setup is light for marketplace-only sales, and
Michigan City's home-occupation zoning bars retail sales at a home.

## Headline, pessimistic first

1. **Fees take 11.4% to 14.7% of a $100 single on the marketplaces, and tracked postage takes another 6.9% to 8.4%.** A $100 card sold on TCGplayer at Level 1 to 4 nets $86.27 before postage and $78.81 after a zone-4 Ground Advantage label (estimate, arithmetic in section 1.8).
2. **A new TCGplayer seller starts capped at 100 items, $1,000 listed value and $500 per item**, and needs 51 delivered orders to reach Level 4. Direct, Pro and the Verified Seller filter all sit behind Level 4 and volume thresholds. The storefront-only Certified Hobby Shop badge is out of reach for an online-only seller.
3. **Online-only sellers get no distributor or publisher account.** The sibling file [distribution-and-supply.md](distribution-and-supply.md) found written refusals from Southern Hobby and PHD, and a storefront requirement in every publisher program. Supply for an online-only seller is buying from the public, opening secondary-market sealed, and buylists.
4. **An online seller is a price taker.** TCGplayer ranks listings by combined price and shipping; a sample $119 Magic card had 198 live listings and a Pokémon card 263 (fact, 2026-09-30). The margin has to come from buying below market, not from selling above it.
5. **Tax setup is light for marketplace-only sales and heavier once there is a Shopify store or card-show sales.** Indiana treats the marketplace as the retailer on facilitated sales. Buying inventory tax-free on an ST-105 still needs an Indiana taxpayer ID.
6. **Michigan City has no secondhand-dealer or pawn licensing article in its code, but its home-occupation zoning bars retail sales activity at a home and limits deliveries to cars and USPS letter carriers.** Buying collections from the public at a residence may conflict with that text. The state statute side was not verified (section 6).

---

## 1. Marketplace fees and requirements

### 1.1 TCGplayer commission and transaction fees

**Finding:** A TCGplayer Level 1 to 4 Marketplace seller pays a 10.75% commission on items and shipping (capped at $75 per product) and a transaction fee of 2.5% of the order total including tax and $0.30 per transaction.
**Confidence:** fact
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/201357836-TCGplayer-Fees> (article updated 2026-09-27; read through the help center's public JSON endpoint <https://help.tcgplayer.com/api/v2/help_center/en-us/articles/201357836.json> because the HTML page returns HTTP 403 to automated fetches) ; fee change announcement <https://seller.tcgplayer.com/blog/important-changes-to-tcgplayer-direct-minimum-pricing-and-marketplace-fees> (posted 2026-01-08)
**Retrieved:** 2026-09-30

Fee table from the help article:

| Seller type | Commission | Pro fee | Direct fee | Transaction fee |
|---|---|---|---|---|
| Marketplace, Level 1 to 4 | 10.75% | n/a | n/a | 2.5% + $0.30 on items + shipping + tax |
| Marketplace, Pro (non-Direct) | 9.25% | 2.5% | n/a | 2.5% + $0.30 |
| Marketplace, Sync (Crystal Commerce, BinderPOS, Ion) | 9.25% | n/a | n/a | 2.5% + $0.30, and the sync provider's fee |
| Direct (non-Pro) | 8.95% | n/a | item-based | 2.5% on items only, no fixed fee |
| Direct (Pro) | 8.95% | 2.5% | item-based | 2.5% on items only |
| Pro website sale, shipped | 0% | 2.5% | n/a | 2.5% + $0.30 |

The commission applies to shipping as well as items; the Fee Calculation Examples article (<https://help.tcgplayer.com/hc/en-us/articles/360047732673-Fee-Calculation-Examples>, updated 2026-09-23) shows "shipping cost x 10.75% (no cap)". TCGplayer rounds fees with banker's rounding. The fee change took effect 2026-02-10: Level 1 to 4 commission rose from 10.25% to 10.75% and the per-product cap from $50 to $75.

A Pro account costs more per sale than a plain Level 1 to 4 account for marketplace sales: 9.25% + 2.5% = 11.75% against 10.75%. Pro pays off only through the Pro website and in-store tools. TCGplayer Pro has "no contract, no monthly payment, and no startup cost" (<https://help.tcgplayer.com/hc/en-us/articles/115003242688-TCGplayer-Pro-Pricing>).

**Disconfirming check:** What would contradict a 13% to 14% total? A sync or Pro discount on commission. Pro and sync accounts pay 9.25% commission, but Pro adds 2.5% and sync adds the provider's fee (BinderPOS charges 2.5% on TCGplayer integration sales per the BinderPOS section of <https://help.tcgplayer.com/hc/en-us/articles/23315007565079-How-to-Understand-Commissions-and-Fees>). No path found to a lower all-in marketplace rate for a new online seller.

### 1.2 TCGplayer seller levels

**Finding:** Every new seller starts at Level 1: at most 100 items listed, $1,000 total listed value, and $500 per item. Level 2 needs 2 orders past their expected delivery date and 80% feedback; Level 3 needs 11 orders and 85%; Level 4 needs 51 orders and 90%.
**Confidence:** fact
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/201868548-How-do-seller-levels-work> (updated 2026-09-29)
**Retrieved:** 2026-09-30

| Level | Max items | Max listed value | Max price per item | To advance |
|---|---|---|---|---|
| 1 | 100 | $1,000 | $500 | 2 orders past EDD, feedback 80%+ |
| 2 | 500 | $5,000 | $1,000 | 11 orders, 85%+ |
| 3 | 50,000 | $100,000 | $20,000 | 51 orders, 90%+ |
| 4 | unlimited | unlimited | not stated | top level |

Level 4 unlocks mass pricing, custom shipping options and app scanning. Pro requires Level 4 (<https://help.tcgplayer.com/hc/en-us/articles/115004316388-Joining-TCGplayer-Pro>).

**Disconfirming check:** Could an experienced seller skip the ladder? No article describes an exception. A seller who buys a $2,000 collection cannot list the high cards for weeks; that capital sits idle.

### 1.3 TCGplayer registration status

**Finding:** TCGplayer's "Start Selling" article carries a change-log entry dated 2026-07-20, "Added note about paused seller registration," but the article body retrieved today shows no pause notice; a new "Registering as a Seller" article (updated 2026-09-30) describes identity, bank and business verification, and states "Your business address must be a physical place of business. PO Boxes aren't accepted."
**Confidence:** fact (text of both articles); whether registration is open today is not verified
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/115004439288-Start-Selling-on-TCGplayer-com> ; <https://help.tcgplayer.com/hc/en-us/articles/43707036556823-Registering-as-a-Seller-on-TCGplayer>
**Retrieved:** 2026-09-30

The Start Selling page also says TCGplayer conducts "an initial review of your application before you can go live." The TCGplayer seller blog (2026-02-18, <https://seller.tcgplayer.com/blog/our-commitment-to-sellers-building-and-delivering-in-2026-and-beyond>) describes "an updated seller registration process requiring additional upfront verification to reduce risk and fraud." The sibling file [storefront-costs-and-demand.md](storefront-costs-and-demand.md) recorded that BinderPOS (a TCGplayer product) states "we are pausing new seller onboarding and sign-ups."

**Disconfirming check:** A home address is a physical place, so the PO box rule does not by itself block a home-based seller. Only starting a registration will show whether the July 2026 pause has lifted. If it has not lifted, the online-only route loses its primary channel until it does.

### 1.4 TCGplayer Direct and Store Your Products

**Finding:** TCGplayer Direct requires Level 4, 99.5% feedback over 30 days, about 3,000 unique Direct-eligible products, and 100 sales a month averaging $600 a week. Since 2026-06-18 the Direct fee is 50% of card value for cards at or below $2.49 (no other fees) and $1.12 per card for cards at $2.50 and up, on top of 8.95% commission and a 2.5% transaction fee with no fixed fee.
**Confidence:** fact
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/204824458-How-do-I-get-started-with-TCGplayer-Direct> (updated 2026-09-21) ; <https://help.tcgplayer.com/hc/en-us/articles/40419491006231-TCGplayer-Direct-Reimbursement-Invoice-and-Store-Your-Product-fee-update-FAQ> ; minimum price: <https://seller.tcgplayer.com/blog/important-changes-to-tcgplayer-direct-minimum-pricing-and-marketplace-fees>
**Retrieved:** 2026-09-30

Direct covers Magic, Pokémon and Yu-Gi-Oh! singles only. TCGplayer ships from its own stock and the seller restocks it in one package; the seller carries loss risk until TCGplayer receives the restock. Direct items carry a $0.40 minimum price since 2026-02-10. Direct sellers are "featured items," and the Cart Optimizer offers buyers a Direct-only cart (<https://help.tcgplayer.com/hc/en-us/articles/201769673-How-does-the-Cart-Optimizer-work>).

Store Your Products (consignment into TCGplayer's warehouse) needs Level 4, 99.5% feedback and about 500 Direct-eligible cards, with shipments of $2,000 or 1,000 cards minimum, and "we are not accepting new seller applications at this time" (<https://help.tcgplayer.com/hc/en-us/articles/360053041514-What-Is-Store-Your-Products-SYP>). A "Managed Inventory" waitlist replaces it.

**Disconfirming check:** Direct's 50% fee on sub-$2.50 cards means Direct does not rescue bulk economics. A new seller reaches Direct eligibility only after it already moves 100 orders a month, so Direct cannot be part of the launch plan.

### 1.5 eBay

**Finding:** eBay charges 13.25% on the total sale amount up to $7,500 for Collectible Card Games, Sports Trading Cards and Non-Sport Trading Cards, and 2.35% above $7,500, with a per-order fee of $0.30 at $10.00 or less and $0.40 above; the total includes shipping and sales tax.
**Confidence:** fact
**Source:** <https://www.ebay.com/help/selling/fees-credits-invoices/selling-fees?id=4822>
**Retrieved:** 2026-09-30

Insertion fees: 250 free listings a month, then $0.35 each. Surcharges: 6% on final value fees for "Below Standard" sellers (7% after four consecutive months), 5% for sellers with high return rates (6%). The page lists no 2025 or 2026 change to the trading card rate. It dates one change: the seller currency conversion charge rises to 3.25% on 2026-10-14. The net below excludes promoted listing fees, which are optional.

**Disconfirming check:** Looked for a 2025 to 2026 trading card fee change. None on the page. The 13.25% applies to the tax-inclusive total, so on a 7% tax order the effective rate on the item is 14.18%.

### 1.6 Whatnot

**Finding:** Since 2026-09-21 Whatnot charges US TCG sellers a tiered commission on item price only (8.00% under $15,000 of sales in a 28-day period, falling to 6.50% at $500,000+), and payment processing of 2.9% + $0.30 on the full buyer total including shipping and tax.
**Confidence:** fact
**Source:** <https://help.whatnot.com/hc/en-us/articles/4847069165965-Whatnot-seller-fees> (updated 2026-09-30; read through <https://help.whatnot.com/api/v2/help_center/en-us/articles/4847069165965.json>)
**Retrieved:** 2026-09-30

US TCG tiers per 28-day period: $0 to $14,999, 8.00%; $15,000 to $34,999, 7.75%; $35,000 to $49,999, 7.50%; $50,000 to $99,999, 7.25%; $100,000 to $249,999, 7.00%; $250,000 to $499,999, 6.75%; $500,000+, 6.50%. The rate is set by the prior period and resets every 28 days. Local pickup orders do not count toward the tier. Whatnot lists "new-seller 0% fees" as an example of a promotional rate without terms. The Premier Shop 10% commission discount ends 2026-11-01. Rates "as low as 3%" are custom deals for the largest sellers.

**Disconfirming check:** A small seller stays at 8% unless it clears $15,000 in a 28-day window. The sibling file [sports-cards.md](sports-cards.md) records a July 2025 California qui tam suit naming Whatnot over box breaks; singles sales are not the subject of that suit.

### 1.7 Shopify own store

**Finding:** Shopify Basic costs $39/month billed monthly or $29/month billed yearly, with online card processing at 2.9% + $0.30 through Shopify Payments and a 2% fee on sales through a third-party processor; Grow is $105 monthly or $79 yearly at 2.7% + $0.30.
**Confidence:** fact
**Source:** <https://www.shopify.com/pricing>
**Retrieved:** 2026-09-30

Advanced is $399 monthly or $299 yearly at 2.5% + $0.30. A premium-card rate (3.5% + $0.30 on Basic) also exists. A Shopify store brings no buyers: traffic, apps, a card-catalog and inventory tool, and sales tax compliance (section 5) are the seller's cost. TCGplayer's BinderPOS adds $100 to $150 a month and 2% on Shopify sales (same BinderPOS source as 1.1).

**Disconfirming check:** The low processing rate is the draw. No retrieved source gives a conversion rate or customer acquisition cost for a new card webstore, so the revenue side of this channel is unknown.

### 1.8 Net on a $100 single, by platform

**Finding:** Before postage, a $100 single nets $85.27 to $88.60 on the marketplaces and $96.60 on a Shopify store before its subscription.
**Confidence:** estimate
**Source:** fee pages in 1.1 to 1.7
**Retrieved:** 2026-09-30

Assumptions: item price $100.00; the seller charges $0 shipping; the buyer pays 7% sales tax ($7.00), so the order total is $107.00; the seller is not in Direct unless stated; Shopify processing is charged on the full card charge including tax (not verified on Shopify's page).

| Platform | Fee components | Arithmetic | Fees | Net on $100 single | Source |
|---|---|---|---|---|---|
| TCGplayer Level 1 to 4 | 10.75% commission; 2.5% + $0.30 on total | $10.75 + ($107.00 x 2.5% = $2.675, rounds to $2.68) + $0.30 | $13.73 | **$86.27** | help.tcgplayer.com 201357836 |
| TCGplayer Pro (non-Direct) | 9.25% + 2.5% Pro; 2.5% + $0.30 | $9.25 + $2.50 + $2.98 | $14.73 | **$85.27** | same |
| TCGplayer Direct (non-Pro), card $2.50+ | 8.95%; 2.5% on items; $1.12 Direct fee | $8.95 + $2.50 + $1.12 | $12.57 | **$87.43**, no outbound postage | help.tcgplayer.com 201357836, 40419491006231 |
| eBay | 13.25% of total incl. tax; $0.40 per order | $107.00 x 13.25% = $14.18; + $0.40 | $14.58 | **$85.42** | ebay.com/help id=4822 |
| Whatnot (US, TCG, standard tier) | 8% on item; 2.9% + $0.30 on total | $8.00 + ($107.00 x 2.9% = $3.10) + $0.30 | $11.40 | **$88.60** | help.whatnot.com 4847069165965 |
| Shopify Basic | 2.9% + $0.30 on charge; $39/mo | $107.00 x 2.9% = $3.10; + $0.30 | $3.40 | **$96.60** before subscription and marketing | shopify.com/pricing |
| Card Kingdom buylist (exit) | Buy price 50% to 65% of CK retail, cash; x1.30 in credit | see 1.9 | n/a | **about $50 to $65 cash, $65 to $85 credit** for a card CK sells at $100 | cardkingdom.com |
| Cardmarket | EU-based marketplace | not researched | n/a | n/a | out of scope for a US seller |

After postage (tracking is mandatory on TCGplayer orders over $49.99, section 2.3), using USPS Ground Advantage commercial at 4 oz, zone 4, $7.46 (range $6.93 zone 1 to $8.40 zone 8):

| Platform | Net before postage | Less $7.46 | Net after postage |
|---|---|---|---|
| TCGplayer Level 1 to 4 | $86.27 | $7.46 | $78.81 |
| TCGplayer Pro | $85.27 | $7.46 | $77.81 |
| eBay | $85.42 | $7.46 | $77.96 |
| Whatnot | $88.60 | $7.46 | $81.14 |
| Shopify Basic | $96.60 | $7.46 | $89.14 before $29 to $39/mo |

Mailer, sleeve, top loader and label stock are not included (`guess`: $0.25 to $0.75 per order).

**A $2 single on TCGplayer** (Level 1 to 4; buyer pays the $1.49 minimum shipping that TCGplayer's fee examples cite for orders under $5; 7% tax on $3.49 = $0.24; order total $3.73): commission $2.00 x 10.75% = $0.215, rounds to $0.22, and $1.49 x 10.75% = $0.16; transaction fee $3.73 x 2.5% = $0.09, + $0.30 = $0.39. Fees $0.77. Seller receives $3.49 - $0.77 = $2.72. Less a 1 oz stamped letter ($0.82) and supplies (`guess` $0.15): **$1.75**. If the envelope holds a rigid top loader and USPS applies the $0.49 nonmachinable surcharge ($1.31 postage) and supplies run $0.30: **$1.11**. The same card in Direct nets $1.00 (50% fee). Fixed costs, not the percentage, decide low-value singles.

**Disconfirming check:** What would make these nets too low? Charging the buyer for shipping moves postage off the seller, but TCGplayer ranks listings by combined price and shipping (section 3.1), so shipping charged is price lost. What would make them too high? eBay promoted listings, returns, and TCGplayer disputes are excluded.

### 1.9 Buylists as an exit

**Finding:** Card Kingdom's cash buy prices for four Sol Ring printings ran 25% to 65% of Card Kingdom's own NM retail price; store credit pays 30% more than cash; TCGplayer closed its own Trade-in/Buylist program on 2024-07-17.
**Confidence:** estimate (ratios from two page reads by a summarizing fetch tool; prices move daily) ; fact (TCGplayer closure)
**Source:** buy prices: <https://www.cardkingdom.com/purchasing/mtg_singles?filter%5Bname%5D=sol+ring> ; retail: <https://www.cardkingdom.com/catalog/search?search=header&filter%5Bname%5D=sol+ring> ; terms: <https://www.cardkingdom.com/purchasing/how_to_sell> ; TCGplayer: <https://help.tcgplayer.com/hc/en-us/articles/24925325925783-TRADE-IN-BUYLIST-UPDATE-JULY-17-2024>
**Retrieved:** 2026-09-30

| Printing | CK cash buy | CK credit | CK retail NM | Cash / retail |
|---|---|---|---|---|
| LTR Commander, Elven variant | $1,760.00 | $2,288.00 | $2,699.99 | 65.2% |
| Masterpiece Series: Inventions | $1,325.00 | $1,722.50 | $2,199.99 | 60.2% |
| 3rd Edition | $14.00 | $18.20 | $27.99 | 50.0% |
| Modern Horizons 3 Commander | $0.75 | $0.98 | $2.99 | 25.1% |

Credit check: $14.00 x 1.30 = $18.20 and $1,760 x 1.30 = $2,288, which matches the 30% bonus. Card Kingdom's condition schedule pays 80% to 90% of NM for EX, 70% to 80% for VG, 50% to 70% for G, and 75% / 50% / 30% for foils. Its sell page names Magic and Pokémon. Card Kingdom retail runs above TCGplayer market for many cards (not measured here), so the ratio to TCGplayer market would be higher than the ratio to CK retail.

**Disconfirming check:** Four printings of one card are not a buylist survey. The pattern that holds across them: the lower the card's price, the smaller the share a buylist pays. A buylist is an exit for high-value inventory at a 35% to 50% haircut to CK retail, not for bulk.

---

## 2. Shipping costs and loss exposure

### 2.1 USPS letter and Ground Advantage rates

**Finding:** From 2026-07-12, a stamped First-Class letter costs $0.82 for 1 oz, $1.11 for 2 oz and $1.40 for 3 oz (metered: $0.78, $1.07, $1.36), with a $0.49 nonmachinable surcharge; USPS Ground Advantage commercial for parcels up to 15.999 oz costs $6.93 (zone 1) to $8.40 (zones 8 and 9).
**Confidence:** fact
**Source:** USPS Notice 123 Price List, <https://pe.usps.com/text/dmm300/Notice123.htm> ("Effective July 12, 2026")
**Retrieved:** 2026-09-30

| Service | Zone 1 | Zone 2 | Zone 4 | Zone 5 | Zone 8 |
|---|---|---|---|---|---|
| Ground Advantage commercial, up to 15.999 oz | $6.93 | $6.94 | $7.46 | $7.69 | $8.40 |
| Ground Advantage retail, 4 to 8 oz | $7.90 | $8.05 | $8.30 | $8.60 | $9.45 |
| First-Class large envelope (flat), 1 oz / 4 oz | $1.69 / $2.56 flat rate, not zoned | | | | |

Extra services (same notice): Signature Confirmation on Ground Advantage $4.15 electronic, $5.15 retail; insurance $2.80 for $0.01 to $50, $3.50 to $100, $4.50 to $200, $4.55 to $300. "Large envelope-sized pieces that are rigid, nonrectangular, or not uniformly thick pay parcel prices." The notice says letters with a DMM 101.1.2 nonmachinable characteristic pay the $0.49 surcharge. DMM 101.1.2 was not fetched, so this file does not settle whether a letter with one top loader counts as rigid.

**Disconfirming check:** Notice 123 lists insurance only as an extra service and does not show whether Ground Advantage includes any coverage. Treat included coverage as unverified.

### 2.2 eBay Standard Envelope

**Finding:** eBay Standard Envelope ships up to 24 raw trading cards (no graded cards) in an envelope up to 3 oz and 0.25 in thick, for items selling at $20 or less, at $0.82 for 1 oz, $1.11 for 2 oz and $1.40 for 3 oz, with tracking and $20 of shipping protection per single-item order ($50 combined).
**Confidence:** fact (help page) ; conflicting rate on a second eBay page
**Source:** <https://www.ebay.com/help/selling/shipping-items/setting-shipping-options/ebay-standard-envelope?id=5308> ; conflicting: <https://www.ebay.com/sellercenter/shipping/choosing-a-carrier-and-service/ebay-standard-envelope>
**Retrieved:** 2026-09-30

The Seller Center page lists $0.78, $1.07 and $1.36. Those equal USPS's metered letter prices in Notice 123, and the help page's figures equal the stamped prices. Which one eBay charges today is not resolved; the difference is $0.04 per envelope. Claims: wait 30 days, file within 90 days of label creation. The program exists only on eBay; TCGplayer and Whatnot sellers have no equivalent tracked letter service on the pages retrieved.

**Disconfirming check:** The $20 cap and 24-card limit mean eSE does not cover the $100 single in section 1.8.

### 2.3 Loss, damage and dispute exposure on TCGplayer

**Finding:** A TCGplayer seller must refund a buyer in full when an untracked package fails to arrive, must ship orders over $49.99 with tracking and orders over $250.00 with signature confirmation, and gets untracked-loss coverage only after 1,000 lifetime orders and only on orders of $49.99 or less placed from 2026-08-17.
**Confidence:** fact
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/201318116-How-do-I-resolve-missing-orders-packages-for-my-customers> (updated 2026-09-28) ; <https://help.tcgplayer.com/hc/en-us/articles/43189079296791-TCGplayer-Safeguard-Untracked-Order-Coverage-FAQ> ; <https://help.tcgplayer.com/hc/en-us/articles/202366108-How-should-I-ship-my-TCGplayer-orders>
**Retrieved:** 2026-09-30

Other terms: buyers have 30 calendar days after the estimated delivery date to claim; the seller has 2 business days to answer before escalation. TCGplayer covers US sellers on tracked orders to the US and Canada when tracking shows the package left "Acceptance"/"Label Created." For "delivered but not received," TCGplayer writes: "We fully cover our sellers in the event of a discrepancy between buyer and USPS claims on domestic and international sealed orders with tracking." The text does not say whether "sealed" limits this to sealed product. TCGplayer investigates signature-confirmed disputes case by case, and "the seller may still be held liable."

Arithmetic for a $250+ single at zone 4: $7.46 + $4.15 signature = $11.61 postage (estimate).

**Disconfirming check:** A new seller ships untracked letters on sub-$50 orders with no coverage until order 1,000. Loss rate on untracked letters was not found from any source; any figure used in a forecast is a `guess`. Card-network chargebacks on a Shopify store fall on the seller; Shopify's chargeback fee was not retrieved.

---

## 3. Competitive structure

### 3.1 How TCGplayer sets and displays price

**Finding:** TCGplayer orders listings by combined price and shipping, lowest first; its Market Price is an average of recent completed sales that ignores outliers; its Cart Optimizer "always finds the lowest priced cards" and offers buyers Direct-only and Verified-Seller-only carts.
**Confidence:** fact
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/201914668-Best-Practices-for-Pricing-Your-Items> ; <https://help.tcgplayer.com/hc/en-us/articles/213588017-TCGplayer-Market-Price> ; <https://help.tcgplayer.com/hc/en-us/articles/201769673-How-does-the-Cart-Optimizer-work>
**Retrieved:** 2026-09-30

Verified Sellers are Gold Star sellers (99.5% feedback and 100+ transactions in 90 days) or Certified Hobby Shops, which must show a storefront with signage and an interior photo (<https://help.tcgplayer.com/hc/en-us/articles/229659207> ; <https://help.tcgplayer.com/hc/en-us/articles/202366238>). An online-only newcomer qualifies for neither badge at launch and can reach only Gold Star.

**Disconfirming check:** Buyers who sort by seller rating or buy single cards without the optimizer see more than price. No TCGplayer data on the share of orders placed through the optimizer or Direct was found.

### 3.2 Listing depth on sample cards

**Finding:** On 2026-09-30, The One Ring (LTR Tales of Middle-earth, Magic) had 198 live listings, Market Price $119.07 and lowest listing $108.00; Charizard ex 199/165 (Pokémon 151) had 263 live listings, Market Price $351.69 and lowest $240.00.
**Confidence:** fact (TCGplayer public search endpoint, point-in-time) ; the lowest listings may be lower-condition copies
**Source:** <https://mp-search-api.tcgplayer.com/v1/search/request?q=the%20one%20ring> (product 487805) ; <https://mp-search-api.tcgplayer.com/v1/search/request?q=charizard%20ex%20199> (product 517045)
**Retrieved:** 2026-09-30

Arithmetic: ($119.07 - $108.00) / $119.07 = 9.3% below market for the cheapest One Ring. A seller listing at market sits behind every cheaper copy of the same condition.

**Disconfirming check:** Two cards are not the catalog. Long-tail singles (older sets, non-English, low-population games) have fewer listings; the sample shows the depth on popular cards, where volume is.

### 3.3 Seller count

**Finding:** No retrieved TCGplayer page states the number of sellers; the seller homepage says "millions of global buyers," and a 2026-02-18 TCGplayer blog post references "more than 1,200 sellers" earning WPN retailer recognition.
**Confidence:** sourced (the 1,200 figure counts WPN stores among sellers, not all sellers)
**Source:** <https://seller.tcgplayer.com/> ; <https://seller.tcgplayer.com/blog/our-commitment-to-sellers-building-and-delivering-in-2026-and-beyond>
**Retrieved:** 2026-09-30

**Disconfirming check:** Listing counts in 3.2 imply at least 198 to 263 competing listings per popular card. A total seller count needs eBay Inc. filings (eBay owns TCGplayer) or a TCGplayer statement; not retrieved.

### 3.4 Evidence of margin compression

**Finding:** Fees rose in 2026 (Level 1 to 4 commission 10.25% to 10.75% and cap $50 to $75 on 2026-02-10; Direct fee on cards up to $2.49 set at 50% on 2026-06-18); no published survey of online singles seller margins was found.
**Confidence:** fact (fee changes) ; no source for margin trend
**Source:** sections 1.1 and 1.4
**Retrieved:** 2026-09-30

The sibling file [category-and-unit-economics.md](category-and-unit-economics.md) records a store owner's 2021 statement of 45% to 50% singles margin before labor, with online fees "up to 15%." Label: `guess`, anecdotal, older than 18 months. This research did not collect forum or Reddit seller anecdotes.

**Disconfirming check:** Whatnot cut its commission in September 2026 (from a flat rate to tiers starting at 8%), which runs against a pure compression story. Rising fees on one platform and falling fees on another point to channel competition, not to a proven squeeze on seller margin.

---

## 4. Where an online-only seller gets product

**Finding:** Distributors and publishers exclude online-only sellers from accounts and store programs; an online-only seller sources by buying collections and single cards from the public, buying sealed product at retail or on the secondary market and opening it, and trading against buylists.
**Confidence:** fact (exclusions, per the sibling file) ; sourced (sourcing routes)
**Source:** [distribution-and-supply.md](distribution-and-supply.md) sections 1, 2 and 4 (Southern Hobby <https://www.southernhobby.com/new_account.php> ; PHD <https://www.phdgames.com/pre-qualification-application/> ; GTS <https://www.gtsdistribution.com/images/GTS_Terms-of-sale.pdf> ; Play! Pokémon, WPN, Bandai TCG+ pages cited there) ; TCGplayer seller blog on sourcing: <https://seller.tcgplayer.com/blog/4-ways-to-source-pok%C3%A9mon-inventory-when-distributors-are-sold-out>
**Retrieved:** 2026-09-30

Pokémon: the Play! Pokémon Store program needs a window, signage, public hours and seating for 8. Bandai: "can apply as a Brick and Mortar store." WPN: open storefront and a play space for 8. Southern Hobby and PHD refuse online-only applicants in writing. GTS bars residences, flea market spaces and pop-ups from "brick and mortar exclusive" product. The sibling file's worked example shows secondary-sourced sealed One Piece losing $10.01 per box when resold on TCGplayer.

Buying price ceiling for a $100 single (estimate): net after fees and postage on TCGplayer is $78.81 (section 1.8). Paying 60% of market ($60.00) leaves $18.81 per card before labor, unsold stock, condition disputes and returns. Paying 70% ($70.00) leaves $8.81. Card Kingdom pays sellers 50% to 65% of its retail in cash (section 1.9), so a local seller of a high-value card has a ready alternative near the price we would need to pay.

**Disconfirming check:** What would break the "no account" finding? A distributor that accepts online-only sellers. GTS's account page does not refuse them outright; its terms exclude them only from B&M-exclusive lines. Which TCG SKUs carry that flag is unknown (see sibling file). Opening sealed product for singles was not costed here; expected value per box needs set-level pull rates and singles prices.

---

## 5. Indiana tax and entity setup

### 5.1 Sales tax rate and Registered Retail Merchant Certificate

**Finding:** Indiana charges 7% sales tax. A retail merchant registers through INBiz and pays a $25 registration fee per location. The Registered Retail Merchant Certificate renews every two years, without a new application when filings and payments are current.
**Confidence:** fact
**Source:** <https://www.in.gov/dor/i-am-a/business-corp/sales-tax/> ; <https://www.in.gov/dor/i-am-a/business-corp/business-faq/>
**Retrieved:** 2026-09-30

A registered merchant must file $0 returns in periods with no activity. The RRMC is revoked for unpaid liabilities or unfiled returns.

**Disconfirming check:** None of the pages retrieved gives a lower rate or a local add-on for card sales; the sibling file notes the county food and beverage tax does not apply to cards.

### 5.2 Marketplace facilitator law

**Finding:** Indiana treats a marketplace facilitator as the retail merchant for third-party sales on its marketplace; "A seller that only makes sales through a marketplace facilitator is not required to register and file Indiana sales tax returns," and a seller registered for other reasons reports marketplace sales as exempt on Form ST-103.
**Confidence:** fact
**Source:** <https://www.in.gov/dor/i-am-a/business-corp/remote-sellers/marketplace-facilitators/> (statute cited: IC 6-2.5-2-1(d), effective 2019-07-01)
**Retrieved:** 2026-09-30

eBay collects and remits sales tax in all 50 states, DC and Puerto Rico (<https://www.ebay.com/help/selling/fees-credits-invoices/taxes-import-charges?id=4121>). Whatnot collects in a list that includes Indiana, Illinois and Michigan (<https://help.whatnot.com/hc/en-us/articles/360061196012-U-S-Sales-Tax-Collection-on-Whatnot>). TCGplayer states it "collects and pays sales tax on all transactions in the 46 states that have sales tax" (<https://help.tcgplayer.com/hc/en-us/articles/213914008>, updated 2025-01-24). The TCGplayer article also tells sellers how to request collection "for sales within your state," which reads as if in-state collection is opt-in; Indiana's DOR text says the facilitator is the retailer on facilitated sales regardless. The two were not reconciled.

**Disconfirming check:** If TCGplayer does not collect on Indiana-to-Indiana orders for a given seller, that seller owes the tax. Confirm with TCGplayer support and check the Sales Tax Report in the seller portal after the first Indiana order.

### 5.3 Resale exemption for buying inventory

**Finding:** Form ST-105 lets a registered merchant buy for resale without tax, and the form asks for the purchaser's 10-digit Indiana TID and 3-digit location number.
**Confidence:** fact
**Source:** <https://forms.in.gov/Download.aspx?id=2717> (ST-105 form fields read from the PDF) ; <https://www.in.gov/dor/i-am-a/business-corp/business-faq/>
**Retrieved:** 2026-09-30

A marketplace-only seller that skips registration cannot issue an ST-105, and pays 7% tax on taxable inventory purchases from Indiana vendors. Purchases from private individuals (collection buys) are not retail sales by a merchant and carry no sales tax to the buyer, per general sales tax structure; this last point was not confirmed on a DOR page.

**Disconfirming check:** Whether TCGplayer, eBay or big-box stores honor an ST-105 was not verified (also open in the sibling file).

### 5.4 Other states' thresholds for own-website sales

**Finding:** Illinois requires a remote retailer to collect Illinois tax at the destination rate once it reaches $100,000 in Illinois gross receipts or 200 separate transactions in the prior 12 months, tested quarterly.
**Confidence:** fact
**Source:** <https://tax.illinois.gov/research/taxinformation/sales/rot.html>
**Retrieved:** 2026-09-30

The 200-transaction test matters for a singles webstore: 200 orders averaging $15 is $3,000 in Illinois sales. Indiana's own remote-seller test is $100,000 only (the DOR marketplace facilitator page states the $100,000 test; the removal of the 200-transaction test effective 2024-01-01 comes from a search-result summary of <https://www.in.gov/dor/i-am-a/business-corp/remote-sellers/>, page not fetched, `sourced`). Michigan's page (<https://www.michigan.gov/taxes/business-taxes/sales-use-tax/remote-sellers>) returned HTTP 404 (page removed); its threshold was not verified. Other states were not checked. Marketplace sales do not count toward these thresholds in Indiana; Illinois applies the same thresholds to facilitators.

**Disconfirming check:** A Shopify store with Chicago buyers could cross Illinois's 200-order line in its first year. Shopify Tax pricing was not retrieved.

### 5.5 Business entity

**Finding:** Indiana's Articles of Organization for a domestic LLC (State Form 49459, revision 12/01-26) list a $100.00 filing fee; business entity reports are due every two years in the formation anniversary month.
**Confidence:** fact
**Source:** <https://forms.in.gov/Download.aspx?id=16989> ; <https://inbiz.in.gov/business-filings>
**Retrieved:** 2026-09-30

The online INBiz fee for Articles and the business entity report fee were not shown on any page retrieved. The sibling file totals LLC and RRMC at $125.

**Disconfirming check:** The online filing fee may differ from the paper form's $100. Confirm in the INBiz fee calculator (<https://inbiz.in.gov/Inbiz/FeeCalculator/Index>, not opened).

### 5.6 Federal information reporting

**Finding:** TCGplayer states that for 2025 it issues Form 1099-K to sellers with more than $20,000 in gross payments and more than 200 sales.
**Confidence:** sourced (platform restating the IRS rule)
**Source:** <https://help.tcgplayer.com/hc/en-us/articles/29427153131031-1099-K-FAQ> (updated 2026-02-03)
**Retrieved:** 2026-09-30

An older TCGplayer article (2025-01-24) cites a $600 threshold for 2026 and later under IRS Notice 2024-85; the 2026-02-03 FAQ supersedes it for 2025 sales. The 2026 tax year threshold was not confirmed on an IRS page. The threshold governs reporting only; all profit is taxable either way.

**Disconfirming check:** Checked for a conflict between the two TCGplayer articles; found one and recorded both.

---

## 6. Secondhand dealer rules for buying from the public

### 6.1 Michigan City code

**Finding:** The Michigan City Code of Ordinances (codified through Ordinance 4808, adopted 2026-08-05) has no secondhand dealer, pawnbroker, junk dealer or precious metal dealer licensing article; "secondhand" appears only as a zoning use ("Secondhand stores and rummage shops"), and Chapter 26 (Businesses) covers new-business registration, peddlers, transient merchants, garage sales, horse carriages, short-term rentals and outdoor refreshment areas.
**Confidence:** fact
**Source:** Municode, Michigan City, IN, Code of Ordinances, product 14947, job 498086 (Supp. No. 22, Update 1), <https://library.municode.com/in/michigan_city/codes/code_of_ordinances> ; searched through <https://api.municode.com/search?clientId=3292> for "secondhand" (3 hits, all zoning), "pawnbroker" (0), "precious metal" (0), "junk dealer" (1 hit, parking table), "second hand" (0 relevant)
**Retrieved:** 2026-09-30

Other provisions that apply:

- **Sec. 26-2, new business registration:** "Any new business establishing itself within the corporate city limits must register with the planning and zoning department within 15 calendar days," with zoning review and referral for an annual fire code inspection. Whether a home-based online business counts as "establishing itself" is not stated.
- **Zoning definition, home occupation (App. C, Sec. 31.09):** "Any gainful occupation or profession conducted within a dwelling unit ... provided that no retail sales activities are conducted."
- **Home occupation standards (App. C, Sec. 14.01):** no more than one-fourth of a floor's area; "no services rendered that require receipt and delivery of merchandise, goods, or equipment by other than a passenger motor vehicle or by U.S. letter carrier mail service"; "There shall normally be no more than one customer or client on the premises at the same time," and none in the R1E district; no activity 11:00 p.m. to 7:00 a.m.

**Disconfirming check:** What would make a home-based online store legal as-is? A planning department reading that shipping online orders is not "retail sales activities" at the dwelling. The text alone points the other way for collection buys at home (customers arriving) and for UPS or FedEx inventory deliveries. Ask the Michigan City Planning Department before relying on a home base.

### 6.2 Indiana Code

**Finding:** Not verified. Indiana's statutes on pawnbrokers, precious metal dealers and any secondhand goods dealer could not be retrieved.
**Confidence:** none (not retrieved)
**Source:** <https://iga.in.gov/laws/2026/ic/titles/24> renders only through JavaScript and returned no statute text; Justia mirrors returned HTTP 403; no other route was found
**Retrieved:** 2026-09-30

From general knowledge, not checked against statute text, `guess`: Indiana licenses pawnbrokers (lending against pledged goods) under IC 28-7-5 and regulates precious metal dealers separately; neither is known to cover outright purchase of trading cards. This must be confirmed against iga.in.gov before any conclusion rests on it. LaPorte County ordinances were not checked.

**Disconfirming check:** A county ordinance or a state secondhand-goods statute with a record-keeping or hold-period rule would add cost to collection buying. Not ruled out.

---

## 7. Hybrid models: shows, pop-ups, conventions

### 7.1 Local and regional shows

**Finding:** The Michigan City Card and Pokemon Show runs at FOP Lodge #75, 416 US-20, on 2026-10-17 and 2026-12-12 (9 a.m. to 3 p.m., contact 219-229-0411), with a 2026-11-21 date at the same venue listed; table fees are not published.
**Confidence:** sourced (show aggregator listing)
**Source:** <https://www.treasurehunter.show/show/the-michigan-city-card-and-pokemon-show-michigan-city-in-2026-12-12>
**Retrieved:** 2026-09-30

Nearby listings on the same aggregator: South Bend Sports & Trading Card Show (2026-10-03), TCG Trade Zone at the Marriott Chicago O'Hare (2026-10-03), Valparaiso Comic & Card Show (2026-10-04), Stockroom Collectibles Card Fest 2 in Oak Lawn, IL (2026-10-04), Chicago Sports Spectacular in Rosemont (2026-11-20 to 22). No table fees published on any listing (<https://www.treasurehunter.show/shows/illinois>).

**Disconfirming check:** The sibling file [storefront-costs-and-demand.md](storefront-costs-and-demand.md) reads the 100+ table local show as proof of local buyers and of 100 dealers already competing on price. Both readings hold.

### 7.2 Chicago conventions

**Finding:** Collect-A-Con Chicago runs 2026-10-10 to 11 at the Donald E. Stephens Convention Center in Rosemont with "over 900 vendor tables"; Hall A tables are sold out, and extra tables used at the show are charged $150 each.
**Confidence:** fact (organizer pages)
**Source:** <https://collectaconusa.com/chicago-2/> ; <https://collectaconusa.com/chicago-2-vendors/>
**Retrieved:** 2026-09-30

The base table price was not shown. The National Sports Collectors Convention ran at the same venue 2026-07-29 to 08-02; no dealer price on its homepage (<https://www.nsccshow.com/>). Selling at an Illinois show may require Illinois sales tax registration; not verified.

**Disconfirming check:** The $150 figure is a penalty rate for unbooked tables, not the list price; the list price could be higher or lower.

### 7.3 Michigan City pop-up licensing

**Finding:** A transient merchant license in Michigan City costs $125 and is valid 180 days; a street vendor license costs $25 a day, $100 a week or $550 a year; the violation fine is $250. A seller in a city-sponsored or city-authorized event, or included by agreement with a Chapter 10 amusement licensee, needs no license.
**Confidence:** fact
**Source:** Michigan City Code Sec. 50-161, 50-163, 26-31, 26-32, 26-83 (Municode, job 498086)
**Retrieved:** 2026-09-30

"Transient merchant" covers anyone selling "on a temporary basis" who does not expect to be established for 180 days or more, including in rented rooms or lots. A table at a private card show inside the city likely falls under it unless the organizer holds a license that covers vendors; confirm with the city controller.

**Disconfirming check:** Sec. 26-83(b) exempts garage, rummage and estate sales. A one-off collection sale by an individual differs from a dealer's recurring table; the exemption does not cover a business.

### 7.4 Platform features that fit a hybrid

**Finding:** Whatnot local pickup orders do not count toward the commission tier; TCGplayer Pro charges no fees on in-store pickup, pay-later orders, but Pro needs Level 4 and the Certified Hobby Shop badge needs a storefront.
**Confidence:** fact
**Source:** <https://help.whatnot.com/hc/en-us/articles/4847069165965-Whatnot-seller-fees> ; <https://help.tcgplayer.com/hc/en-us/articles/201357836-TCGplayer-Fees> ; <https://help.tcgplayer.com/hc/en-us/articles/202366238-What-is-a-Certified-Hobby-Shop>
**Retrieved:** 2026-09-30

**Disconfirming check:** A hybrid seller still has no storefront, so every publisher and distributor exclusion in section 4 still applies.

---

## Fee comparison table (summary)

| Platform | Fee components | Net on $100 single (before postage) | Source |
|---|---|---|---|
| TCGplayer Level 1 to 4 | 10.75% commission (cap $75/product); 2.5% + $0.30 on items, shipping and tax | $86.27 | <https://help.tcgplayer.com/hc/en-us/articles/201357836-TCGplayer-Fees> |
| TCGplayer Pro | 9.25% + 2.5% Pro; 2.5% + $0.30 | $85.27 | same |
| TCGplayer Direct (needs Level 4, 3,000 products, 100 sales/mo) | 8.95%; 2.5% on items; $1.12/card ($2.50+) or 50% (up to $2.49) | $87.43, no outbound postage | same; <https://help.tcgplayer.com/hc/en-us/articles/40419491006231> |
| eBay | 13.25% of total incl. tax and shipping up to $7,500; $0.40/order | $85.42 | <https://www.ebay.com/help/selling/fees-credits-invoices/selling-fees?id=4822> |
| Whatnot (US TCG, under $15,000 per 28 days) | 8.00% of item price; 2.9% + $0.30 on total | $88.60 | <https://help.whatnot.com/hc/en-us/articles/4847069165965-Whatnot-seller-fees> |
| Shopify Basic | $39/mo ($29 yearly); 2.9% + $0.30 | $96.60 before subscription and marketing | <https://www.shopify.com/pricing> |
| Card Kingdom buylist | 50% to 65% of CK retail cash on three sampled printings retailing over $25; 30% more as store credit | about $50 to $65 cash | <https://www.cardkingdom.com/purchasing/how_to_sell> |

All nets are `estimate`, arithmetic in section 1.8.

---

## Still unknown

- Whether TCGplayer seller registration is open today (2026-07-20 change log mentions a pause). Start a registration.
- Whether TCGplayer collects Indiana tax on Indiana-to-Indiana orders by default. Ask TCGplayer support; check the first Sales Tax Report.
- Whether TCGplayer, eBay or big-box stores honor an Indiana ST-105. Ask each.
- Indiana state law on secondhand goods dealers, pawnbrokers (IC 28-7-5) and precious metal dealers, and any LaPorte County ordinance. Read iga.in.gov in a browser; call the LaPorte County Auditor.
- Whether Michigan City treats a home-based online card business as a "new business" under Sec. 26-2 and whether shipping orders from home breaches the home-occupation "no retail sales activities" clause. Ask the Planning Department in writing.
- Whether a card-show table in Michigan City needs a transient merchant license. Ask the city controller and the FOP show organizer (219-229-0411).
- Table fees for the FOP Lodge show, Valparaiso, South Bend and Collect-A-Con base tables. Call organizers.
- Illinois registration for a vendor at a Rosemont or Chicago show. Illinois DOR.
- Michigan and other states' remote-seller thresholds. State revenue pages (Michigan's page returned 404).
- Indiana LLC online filing fee and business entity report fee. INBiz fee calculator.
- Untracked letter loss rate and TCGplayer dispute rate for new sellers. Only our own shipping log after launch would answer it.
- Card Kingdom and other buylist spreads against TCGplayer Market Price across a sample of 50 cards. Pull both on one day.
- Expected value of opening sealed product for singles, per set. Needs pull rates and a same-day singles price pull.
- Shopify chargeback fee and Shopify Tax cost. Shopify help center.
- Total TCGplayer seller count and order share through Direct and the Cart Optimizer. eBay Inc. filings or TCGplayer.
- Whether USPS treats a PWE with one top loader as nonmachinable. Read DMM 101.1.2 or ask the Michigan City post office.

## Re-check schedule

| Figure | Re-check by | Why |
|---|---|---|
| TCGplayer 10.75% commission, $75 cap, 2.5% + $0.30 | 2027-03-30 | Changed 2026-02-10; fees move yearly |
| TCGplayer Direct fee ($1.12 / 50%) and eligibility | 2027-03-30 | Changed 2026-06-18; Managed Inventory replacing SYP |
| TCGplayer registration pause | 2026-10-31 | Change log entry 2026-07-20, status unclear |
| TCGplayer untracked coverage (1,000 orders, $49.99) | 2027-01-31 | Stated as interim "until we are able to implement an improved tracking solution" |
| eBay 13.25% and $0.30 / $0.40 per order | 2027-03-30 | Platform fee |
| eBay Standard Envelope rates ($0.78 vs $0.82) | 2026-10-31 | Two eBay pages conflict |
| Whatnot tiers and 2.9% + $0.30 | 2026-12-31 | New structure since 2026-09-21; Premier discount ends 2026-11-01 |
| Shopify plan prices and rates | 2027-03-30 | Platform pricing |
| USPS Notice 123 (effective 2026-07-12) | 2027-01-15 | USPS changes prices each January and July |
| Card Kingdom buy/sell ratios | 2026-12-31 | Prices move daily; four-printing sample |
| TCGplayer listing counts and prices (One Ring, Charizard) | 2026-10-31 | Point-in-time |
| Indiana 7% rate, $25 RRMC, marketplace facilitator rules | 2027-09-30 | Stable statute; annual check |
| Illinois $100,000 / 200 transaction threshold | 2027-03-30 | States have been dropping transaction tests |
| Indiana LLC $100 fee (form R12/01-26) | 2027-09-30 | Form revision |
| TCGplayer 1099-K threshold ($20,000 and 200 for 2025) | 2027-01-31 | Federal rule changed twice since 2024 |
| Michigan City code (through Ord. 4808) | 2027-03-30 | Supplements issued through the year |
| Collect-A-Con $150 extra-table rate, show dates | 2027-03-30 | Event terms change per show |
