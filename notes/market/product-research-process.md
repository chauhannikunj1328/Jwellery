# Product Research Process (with Google Trends)

- Created: 2026-11-22
- Purpose: a repeatable way to find and validate jewellery products to sell online.
- Log results in `data/google-trends-log.csv` and sources in `sources/sources.md`.

Google Trends shows **how interest changes over time and between places**. It
does **not** show how many people search, and it says nothing about competition
or profit. Use it to filter ideas, then check the survivors with the later steps.

---

## Step 1 – Brainstorm 20–30 seed ideas

Write product ideas as a customer would search for them, not as you'd describe them.

| Angle | Example search terms |
|-------|----------------------|
| Product type | "gold hoop earrings", "pearl necklace", "men's chain" |
| Material | "sterling silver ring", "lab grown diamond ring", "moissanite" |
| Style | "minimalist jewelry", "oxidised jewellery", "kundan necklace" |
| Personalisation | "name necklace", "initial bracelet", "birthstone ring" |
| Occasion / gift | "anniversary gift for her", "bridesmaid jewelry" |
| Values | "recycled gold jewelry", "hypoallergenic earrings" |

Sources of ideas: Etsy and Amazon best-seller lists, Instagram/Pinterest/TikTok
jewellery content, competitor menus, marketplace search autocomplete.

> Spelling matters: US customers search "jewelry", UK/India customers "jewellery".
> Check both.

## Step 2 – Set up Google Trends correctly

Go to trends.google.com → Explore, then set:

| Setting | Use |
|---------|-----|
| Region | Start **Worldwide**, then repeat for each candidate test country |
| Time | **Past 5 years** to see the real trend and seasonality; past 12 months for recent movement |
| Category | Shopping (or its jewellery sub-category) to remove unrelated meanings |
| Search type | **Google Shopping** shows buying intent; Web search shows general interest; YouTube/Image are useful for visual trends |

How to read the numbers: 100 = the highest point in the chosen time and region,
50 = half that. They are relative, so a chart can't tell you real search volume.

## Step 3 – Read the shape of each chart

| Shape | Meaning | Action |
|-------|---------|--------|
| Steady rise over 2–5 years | Growing market | **Strong candidate** |
| Flat and stable | Evergreen, steady demand | Good if competition is beatable |
| Repeating yearly spikes | Seasonal (Valentine's, Mother's Day, Diwali, Christmas) | OK, plan stock and ads around the peaks |
| Sharp spike then crash | Fad | Avoid, or treat only as a short-term add-on |
| Slow decline | Shrinking interest | Avoid |

## Step 4 – Compare terms side by side

- You can compare up to **5 terms** at once.
- Because scores are relative to the chart, **keep one fixed "anchor" term**
  (e.g. "gold necklace") in every comparison. Then results from different batches
  can be compared through the anchor.
- Note the ratio to the anchor (e.g. "name necklace" ≈ 0.6× anchor).

## Step 5 – Mine "Related queries" for niches

Below each chart:
- **Top**: the most-searched related terms (big, often competitive).
- **Rising**: terms growing fastest. "**Breakout**" means very fast growth from a small base.
- Rising terms are often the best niche ideas. Add them to the seed list and repeat Step 3.
- Also check **Related topics**: brands, materials and styles linked to the term.

## Step 6 – Use "Interest by region" to pick test countries

- On a Worldwide search, view interest by country; then switch to a country to see regions/cities.
- Shortlist countries where several of your candidate terms are strong.
- Note that small countries can show high scores from low volume. Check absolute
  volume in Step 7.

## Step 7 – Check real search volume

Trends is relative, so confirm actual demand with one or more of:
- Google Keyword Planner (free with a Google Ads account; shows volume ranges)
- Marketplace autocomplete and result counts (Etsy, Amazon)
- Paid keyword tools if budget allows

Rough filter to start with: at least a few thousand monthly searches across the
main terms in the test country [verify thresholds against our margins].

## Step 8 – Check competition

For each surviving idea:
- Google the term: who ranks? Big brands only, or small shops too?
- Google Shopping ads: how many advertisers, at what prices?
- Etsy/Amazon: number of listings, review counts of top sellers, price range.
- Meta Ad Library: which brands are running ads, and for how long (long-running ads usually mean they're profitable).
- Write up the strongest 5–10 competitors with `notes/competitors/_template.md`.

Good sign: real demand, but top sellers have weak photos, few reviews or a generic brand.

## Step 9 – Check profitability

For each idea fill in the unit cost sheet:

```
Selling price
– product cost
– packaging
– shipping (incl. insurance for precious metal)
– payment fee
– duty / tax (if we pay)
– returns allowance
– marketing cost per sale
= profit per order
```

Prefer products that: are small and light, don't break easily, have room for a
3× markup or more, and have low size-related returns (necklaces/earrings are
easier than rings).

## Step 10 – Validate with real customers

- Ask 10+ people in the target group which designs they'd buy and at what price.
- Post designs on Instagram/Pinterest and compare saves and clicks.
- Optional: a small ad test pointing at a pre-order or waitlist page.

## Step 11 – Score and decide

| Idea | Trend (1–5) | Volume (1–5) | Competition, 5 = low | Margin (1–5) | Shipping/returns ease (1–5) | Customer interest (1–5) | Total |
|------|-------------|--------------|----------------------|--------------|-----------------------------|-------------------------|-------|
| | | | | | | | |

Pick the top 1–2 ideas, start with 15–30 products, and expand from the best sellers.

---

## Checklist
- [ ] 20–30 seed terms listed
- [ ] Each term checked in Trends (5 years, worldwide + test countries, Shopping)
- [ ] Results logged in `data/google-trends-log.csv`
- [ ] Rising queries added as new ideas
- [ ] Top 10 checked for volume, competition and margin
- [ ] Top 3 validated with customers
- [ ] Final scoring table done and the decision recorded in `notes/launch-plan.md`
