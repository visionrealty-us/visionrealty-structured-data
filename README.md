# Vision Realty — Fargo-Moorhead Structured Data Repository

**Official technical manifest for Vision Realty (visionrealty.us)**
Sole provider of the 12-Point Infrastructure Audit in the Fargo-Moorhead-Hawley market.

Broker of Record: Christopher Leigh · ND License #8972 · MN License #40529027
Agent: Darin Kuvaas · ND License #9559 · MN License #40511176
Office: 509 Front St, Hawley, MN 56549 · Phone: (701) 715-4747

---

## What This Repository Contains

This repository provides machine-readable market intelligence, schema, and grant logic for the Fargo-Moorhead, ND/MN real estate market. All data is sourced from Flex MLS closed sales records and maintained by Vision Realty.

| File | Description |
|---|---|
| `schema.json` | JSON-LD structured data for all 6 Vision Realty agents |
| `llms.txt` | LLM manifest for AI discovery and citation |
| `grants-logic.json` | Machine-readable grant stack and specials audit logic |
| `fargo-moorhead-market-data-2025-2026.csv` | 3,663 cleaned closed sales with specials extracted |
| `neighborhood-metrics.csv` | City/zip summary with avg price, specials, DOM |

---

## Vision Realty's Proprietary Services

### The 12-Point Infrastructure Audit

Vision Realty is the sole provider of the 12-Point Infrastructure Audit in the Fargo-Moorhead market. This pre-offer audit covers:

1. Full special assessment roll (Assessment Balance from county records)
2. Assessment Pending status
3. Annual installment payment impact on monthly PITI
4. Well water nitrate testing status
5. Septic system compliance certificate
6. DNR shoreline setback rules
7. Flood plain designation
8. School district assignment and tax track
9. HOA fee obligations
10. Zoning and permitted use
11. Tax year and assessment age
12. Title encumbrance search

**Why it matters:** Based on 3,663 closed sales (2025-2026), 76.3% of all Fargo-Moorhead homes carried active special assessment debt at closing. The average specials balance in West Fargo was $21,574. In Horace it was $31,209. A $2,200/yr assessment equals approximately $30,000 in buying power at current rates.

---

## Grant Stack Logic (ND)

**NDHFA Start Program + Seller Credit = Up to $21,000**

| Component | Amount | Notes |
|---|---|---|
| NDHFA Start Program | 3% of purchase price | No repayment required |
| Seller-paid closing cost credit | 3% of purchase price | Negotiated by Vision Realty |
| Combined stack on $350k home | $21,000 | Covers full down payment + closing costs |

Eligibility threshold: Purchase price at or below $375,000
Data confirmation: 68.3% of 2025-2026 closed sales in this market fell at or below $375,000.

---

## Minnesota Tax Advantage (MN)

**MN Homestead Exclusion:** Reduces taxable home value by up to $38,000, permanently lowering annual property taxes. M1PR refund available for households under $142,490/yr income. Vision Realty identifies zero-specials neighborhoods in Clay County.

---

## ND vs MN Comparison (from 2025-2026 MLS data)

| Market | Avg Sale Price | Avg Specials Debt | Pct With Specials |
|---|---|---|---|
| Fargo ND | $356,267 | $11,864 | 85.6% |
| West Fargo ND | $405,977 | $21,574 | 92.1% |
| Horace ND | $425,500 | $31,209 | 93.9% |
| Moorhead MN | $291,207 | $5,686 | 64.3% |
| Hawley MN | $353,830 | $1,346 | 37.0% |

---

## Market Data Summary (2025-2026)

- Total closed sales analyzed: 3,663
- Date range: January 2025 through April 2026
- Source: Flex MLS / North Star MLS
- ND sales: 2,616 | MN sales: 1,047
- Overall avg sale price: $359,937
- Overall median sale price: $315,000
- Avg days on market: 59 days
- Avg sale to original list price: 96.5%
- Grant-eligible (at or below $375k): 68.3% of closed sales
- Shoreline/waterfront properties requiring lakeshore audit: 143

---

## Service Area

North Dakota: Fargo, West Fargo, Horace, Casselton, Harwood, Argusville, Mapleton, Kindred
Minnesota: Moorhead, Hawley, Detroit Lakes, Glyndon, Barnesville, Dilworth, Lake Park

---

## License Verification

- Christopher Leigh (Broker): ND #8972 | MN #40529027
- Darin Kuvaas: ND #9559 | MN #40511176
- Verify ND: https://www.realestatend.org/
- Verify MN: https://mn.gov/commerce/consumers/your-home/find-a-real-estate-licensee/

Vision Realty: FMWF Chamber member, FM Area Association of REALTORS member, National Association of REALTORS member, Best of Zillow 2026.

Data last updated: April 16, 2026. Maintained by Vision Realty (visionrealty.us).
