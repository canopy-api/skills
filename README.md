# Canopy API Agent Skills: Amazon Product Data

[![skills.sh](https://skills.sh/b/canopy-api/skills)](https://skills.sh/canopy-api/skills)

Agent skills for [Canopy API](https://canopyapi.co) — real-time Amazon product data for ecommerce research and product comparison: ASIN lookup, product search, prices, reviews, seller offers, sales estimates, stock levels, deals, and best sellers.

## Skills

| Skill | What it covers | skills.sh |
| --- | --- | --- |
| [amazon-data](skills/amazon-data/SKILL.md) | Canopy API REST endpoints in Python for ASIN lookup, product search, prices, reviews, seller offers, sales estimates, stock levels, deals, and best sellers | [amazon-data](https://skills.sh/canopy-api/skills/amazon-data) |

## Install

```bash
npx skills add canopy-api/skills
```

## Example prompts

- Look up ASIN B01HY0JA3G and summarize the current price, rating, and feature bullets.
- Search Amazon for wireless headphones between $20 and $80, sorted by customer rating.
- Compare seller offers for this ASIN and list the lowest price with fulfillment details.
- Estimate weekly sales and current stock for this product, then show related deals and best sellers in its category.

## What are Skills?

Skills are reusable prompt-driven modules that give AI agents structured capabilities for working with the Canopy API. They provide context, instructions, and patterns that help agents query Amazon product data over the REST API using Python.

## Related Projects

- [canopy-api](https://github.com/canopy-api/canopy-api) — Documentation and examples for the Canopy API
- [canopy-api-mcp](https://github.com/canopy-api/canopy-api-mcp) — Model Context Protocol server for Canopy API

## Getting Started

1. Sign up and create an account at [canopyapi.co](https://canopyapi.co)
2. Get an API key from your dashboard
3. Install the skills with `npx skills add canopy-api/skills`

## API

This repository's skill calls the Canopy REST API.

- **REST:** https://rest.canopyapi.co/
- **Documentation:** https://docs.canopyapi.co
- **API Dashboard:** https://canopyapi.co

## License

MIT
