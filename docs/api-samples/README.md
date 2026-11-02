# CheapShark API samples

Real responses saved to design the app. Base URL: `https://www.cheapshark.com/api/1.0`

| File | Request |
|---|---|
| `deals.json` | `GET /deals?pageSize=3&sortBy=Metacritic` |
| `game.json` | `GET /games?id=<gameID of the first deal>` |
| `stores.json` | `GET /stores` |

## Findings

- All values come as **strings** (prices, savings, IDs): convert with `Number()` before sorting or charting.
- CORS is open (`Access-Control-Allow-Origin: *`), so `fetch` works from the browser.
- Requests without a descriptive `User-Agent` get `400`. Browsers send one automatically; with `curl` use `-A "PriceQuest-student-project/1.0"`.
- `/games?id=` only returns `cheapestPriceEver` (price and date), **not a price history**.
- Deal and game images are in `thumb`; store icons are relative paths (`https://www.cheapshark.com` + `images.icon`).
- Total pages are exposed in the `X-Total-Page-Count` response header.
