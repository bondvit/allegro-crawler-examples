# Allegro Crawler — examples

Runnable examples for the **[Allegro.pl Scraper — Offers, Prices & Sellers | $4/1K](https://apify.com/bovi/allegro-offers)** on Apify.

Scrape Allegro.pl offers by keyword: title, price, auction/buy-now format, images, category, and offer URL. No login, OAuth2, or proxy setup — DataDome anti-bot is handled for you. Pay per result.

## What you get per record
`categoryId` · `currency` · `format` · `id` · `imageUrl` · `images` · `location` · `name` · `offerUrl` · `parse_confidence` · `price` · `scraped_at` · `stock` · `warnings`

## Who uses this
- **Price intelligence** — track competitor pricing and Buy-Box dynamics on Allegro.
- **Assortment monitoring** — what sellers list, at what price, in any category.
- **Cross-border arbitrage** — spot price gaps between Allegro and Western marketplaces.

## Quickstart
1. Get your Apify token: <https://console.apify.com/account/integrations>
2. Run a language example below. Both call the actor and print the results.

| Example | File |
|---|---|
| Python (`apify-client`) | [`examples/python/run.py`](examples/python/run.py) |
| JavaScript (`apify-client`) | [`examples/javascript/run.js`](examples/javascript/run.js) |
| Sample output (real records) | [`examples/sample_output.json`](examples/sample_output.json) |

## Example input
```json
{
  "phrase": "laptop",
  "maxItems": 100,
  "country": "pl"
}
```

## Links
- **Actor on Apify Store:** <https://apify.com/bovi/allegro-offers>
- **Apify client docs:** [Python](https://docs.apify.com/api/client/python/) · [JavaScript](https://docs.apify.com/api/client/js/)

---
_MIT-licensed examples. The actor runs on the caller's Apify account (you pay platform compute + per-result)._
