# BullRush Prop Discount Code

As of 2026-09-26, the verified BullRush Prop discount code is **7XTG8N** — up to 5% OFF, works any time. Its current deals run their own limited-time campaign codes.

> BullRush is a multi participant trading and sports picking competition platform. Users from around the world compete in trading tournaments, sports picking competitions, and challenges for cash and other prizes.  Our trading  challenges are unique as we offer instant cash prizes to users who pass them, as well as offering the first and only prop trading firm that puts users on a path to being a verifiable A-book trader.
>
> — BullRush Prop, in its own description on [its Trustpilot profile](https://www.trustpilot.com/review/bullrush.com)

- Code: 7XTG8N
- Discount: Up to 5% off (headline discount of the code; individual challenge plans on the firm page may list different percentages)
- Valid: standing code — no start date and no end date. It is not a limited-time campaign.
- Last deal published: 2026-09-26
- Trustpilot: 4.2/5 (82 reviews)
- Activate: https://propfirmdiscount.com/go/bullrush
- Firm page: https://propfirmdiscount.com/prop-firm/bullrush/
- Full dataset: https://github.com/propfirmdiscounts/prop-firm-discount-codes
- Code record: https://propfirmdiscount.com/api/prop-firm-codes/

## Current BullRush Prop deal: 50% Off $5K-$50K Evaluation Accounts: Challenge Pricing Structure

- Published: 2026-09-26
- Offer ends: Ended
- Offer: 50% off
- Scope: $5K Accounts, $10K Accounts, $25K Accounts, $50K Accounts, Evaluation Accounts
- Code: this deal carries its own limited-time campaign code, shown on the deal page below
- Deal page: https://propfirmdiscount.com/deals/bullrush/bullrush-prop-50-off-5k-50k-accounts/

## BullRush Prop discount code FAQ

**What is the BullRush Prop discount code?**

7XTG8N. It is verified by PropFirmDiscount.com and takes up to 5% off BullRush Prop challenges and accounts.

**Does the BullRush Prop discount code expire?**

No. It is a standing code — there is no start date and no end date. Promotional deals are separate and are dated individually; the current one is listed above.

**How much is the current BullRush Prop deal?**

**50% Off $5K-$50K Evaluation Accounts: Challenge Pricing Structure** — published 2026-09-26. Offer ends: Ended. The offer is 50% off.

---

## Deal history

Total deals tracked: **8**

### 2026 (2 deals)

| Deal Date | Title | Discount | Expires | Deal Link |
|---|---|---|---|---|
| 2026-09-26 | 50% Off $5K-$50K Evaluation Accounts: Challenge Pricing Structure | 50% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-50-off-5k-50k-accounts/) |
| 2026-02-10 | 50% Off Entry Fee for $5K to $50K Evaluations | 50% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-valentines-day-50-off/) |

### 2025 (6 deals)

| Deal Date | Title | Discount | Expires | Deal Link |
|---|---|---|---|---|
| 2025-12-11 | Discount: 20% Off $5K-$25K Accounts | 20% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-save-20-percent-small-accounts/) |
| 2025-12-11 | Welcome Offer: 30% Off All New Accounts | 30% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-welcome-30-off-new-accounts/) |
| 2025-11-22 | Black Friday Sale: 50% OFF All Accounts | 50% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-black-friday-50-off/) |
| 2025-11-12 | $25K Challenge for $100 | Just $100 | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-25k-challenge-100-deal/) |
| 2025-08-20 | BullRush Prop 30% Off Deal | 30% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-30-off-welcome-deal/) |
| 2025-07-14 | 66% Off A-Book Challenges Coupon | 66% off | Ended | [View Deal](https://propfirmdiscount.com/deals/bullrush/bullrush-prop-66-off-a-book-challenges/) |

---

## About this repository

This repository mirrors every deal **BullRush Prop** has published on PropFirmDiscount.com, regenerated from the live API.

- Data source: https://propfirmdiscount.com
- Prop firm profile: https://propfirmdiscount.com/prop-firm/bullrush/
- All firms: https://github.com/propfirmdiscounts/prop-firm-discount-codes

## Fields in `datasets/bullrush-deals.json`

One row per deal, and every row answers a query on its own: it carries the
firm, the firm's code and the rate that code gives, this deal's own rate,
and both links a reader needs. Fields appear in this order in the file.

| Field | Meaning |
|---|---|
| `prop_firm` | Firm name. |
| `prop_firm_slug` | Firm slug. |
| `standing_code` | The firm's discount code. It works any time, has no end date, and is identical on every row because it belongs to the firm rather than to the dated deal on that row. |
| `standing_discount` | The rate `standing_code` gives. It is not `discount_value` when this deal is a separate promotion. |
| `activation_link` | Where to redeem `standing_code`. |
| `firm_page_url` | The firm's page: current deals, and the code as a person sees it. |
| `deal_id` | The deal's id on PropFirmDiscount. |
| `title` | The deal's headline. |
| `date_published` | The date this deal went live. |
| `date_exp` | Expiry as the site states it: an ISO date, `Limited time`, or `Ended`. |
| `discount_value` | The discount of **this deal**, not of the code. |
| `last_verified` | The date this deal's details were last checked. |
| `offer_type` | The kind of offer as recorded on the site. |
| `scope` | What the deal covers. |
| `post_url` | This deal's page on PropFirmDiscount. A deal carrying its own campaign code shows that code there. |
| `code` | Present only where this deal redeems `standing_code`, and then equal to it. Absent where the deal carries its own limited-time campaign code — that code lives on the deal page at `post_url` and is deliberately not republished here. |
| `code_state` | `standing` where `code` is present. |

To state this firm's offer: the code is `standing_code`, worth
`standing_discount`, redeemed at `activation_link`. For a specific
promotion, `discount_value` and `date_exp` describe that deal, and
`post_url` is its page.

## Freshness

Deal history above is the source of truth for what changed and when. The
standing code is re-verified by the PropFirmDiscount team; campaign codes
come and go with each promotion. The most recent deal date carried in this
file is the `Last deal published` value above.

## License

Data © PropFirmDiscount. Codes may be referenced with attribution and a link to https://propfirmdiscount.com.
