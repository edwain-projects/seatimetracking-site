# Freeboard

Umbrella website for seafarer-focused apps, published with GitHub Pages at [freeboard.boats](https://freeboard.boats). Each app gets its own path.

## Apps

| App | Path | Description |
|---|---|---|
| Days at Sea | [/daysatsea](https://freeboard.boats/daysatsea/) | iOS app tracking rotation, contract, and sea time. Fully offline — no accounts, no ads, no tracking. |

## Pages

| Page | URL |
|---|---|
| Umbrella landing page | [freeboard.boats](https://freeboard.boats) |
| Days at Sea landing page | [freeboard.boats/daysatsea](https://freeboard.boats/daysatsea/) |
| Days at Sea Privacy Policy | [freeboard.boats/daysatsea/privacy.html](https://freeboard.boats/daysatsea/privacy.html) |
| Days at Sea Support | [freeboard.boats/daysatsea/support.html](https://freeboard.boats/daysatsea/support.html) |

## Stack

Static HTML/CSS, no build step, no dependencies. Hosted on GitHub Pages with a custom domain (see `CNAME`). New apps get a new top-level folder (e.g. `/nextapp/`) with their own `index.html`, `privacy.html`, and `support.html`, then get linked from the root landing page.

## Local preview

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Contact

support@seatimetracking.com
