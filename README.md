# PriceQuest

Web app to hunt the best prices on PC games. Browse a ranking of the best current deals, compare a game's price across stores, and save your favourites.

Assignment for DWEC, unit 4 (see [docs/ENUNCIADO.md](docs/ENUNCIADO.md)).

## Target audience

Gamers who want to save money when buying PC games.

## Data source

[CheapShark API](https://apidocs.cheapshark.com/) (free, no API key).

Base URL: `https://www.cheapshark.com/api/1.0`

| Endpoint | Use |
|---|---|
| `GET /deals` | Deal list for the overview (`pageSize`, `sortBy`, `upperPrice`, `storeID`, `title`) |
| `GET /games?id=` | Game detail: current deals per store and cheapest price ever |
| `GET /stores` | Store names and icons |

## Views

1. **Overview** (`index.html`): ranking of deals with KPIs (sale price, discount, Metacritic score, Steam rating).
2. **Game detail** (`game.html`): interactive bar chart comparing the price of the selected game in each store.
3. **Favorites** (`favorites.html`): mark and unmark games as favorites, persisted in `localStorage`.

Optional: loading spinner and error handling on the overview.

## Tech

HTML, CSS and vanilla JavaScript (ES modules). Charts with Chart.js.

## Run

Open `index.html` in a browser, or serve the folder with any static server.

## Roadmap

See the commit history.
