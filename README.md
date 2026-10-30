# Savings Account Interest Rates

> Savings account interest rates across banks

**Category:** finance · **Data:** Bank websites (public) · **License:** CC-BY-4.0 · **Updates:** monthly

## API Endpoints

All endpoints are served as static JSON from GitHub Pages.

| Endpoint | Format |
|----------|--------|
| `/data/savings-rates.json` | JSON |

## Usage

```bash
curl https://chirag127.github.io/savings-rates/data.json
```

```javascript
const res = await fetch('https://chirag127.github.io/savings-rates/data.json');
const data = await res.json();
```

## Data

- Source: Bank websites (public)
- License: CC-BY-4.0
- Last updated: `2026-08-25T03:10:22.112Z`

See `data/` for raw JSON and `data/schema.json` for the schema.

## Documentation

Visit the [interactive docs](https://chirag127.github.io/savings-rates/) for the browsable API reference.

## Contributing

Issues and PRs welcome. Ensure `data/schema.json` validates all data files.

## License

CC-BY-4.0
