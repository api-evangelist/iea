# International Energy Agency (IEA)

The International Energy Agency (IEA) provides a REST API and data subscription services for accessing authoritative global energy statistics, renewables data, CO2 emissions factors, monthly electricity generation data, oil market reports, and energy policy information. IEA data covers 150+ countries with historical datasets going back to 1971 and real-time emissions data updated up to hourly.

## APIs

- **Real-Time Emissions Factors API** — Up-to-hourly CO2 intensity and emissions from the power sector, approximately 100 data points per country per day. Requires bearer token authentication via active subscription.
- **Data Products API** — Programmatic access to purchased IEA data products including World Energy Balances, World Energy Statistics, Monthly Electricity Statistics, Energy Prices, and Emissions Factors packages.

## Authentication

All IEA API requests use Bearer token authentication. Tokens are managed in the user account under Settings > Releases API. Generating a new token revokes all previous tokens.

```
Authorization: Bearer {your_token}
```

## Data Products

| Product | Coverage | Format |
|---|---|---|
| Real-Time Emissions Factors | Up-to-hourly, power sector, global | REST API (JSON) |
| World Energy Balances | 156 countries, 1971–present | .Stat, CSV, SDMX |
| World Energy Statistics | 156 countries + 35 regions, 1971–present | .Stat, CSV, SDMX |
| Monthly Electricity Statistics | OECD+ countries, monthly | Free web + .Stat, SDMX |
| Emissions Factors Package | 52 countries, 2015–present | .Stat, CSV |
| Energy Prices | 150 countries, 1970–present | .Stat, CSV |
| OECD Energy Prices and Taxes Quarterly | OECD countries, quarterly | .Stat, CSV |

## Links

- **Website:** https://www.iea.org
- **Documentation:** https://www.iea.org/documentation
- **Data Products:** https://www.iea.org/data-and-statistics/data-sets
- **Real-Time Emissions API:** https://www.iea.org/data-and-statistics/data-product/real-time-emissions-factors-api-access
- **LinkedIn:** https://www.linkedin.com/company/international-energy-agency
- **X / Twitter:** https://x.com/IEA
- **Newsroom / Blog:** https://www.iea.org/newsroom
- **Help Centre:** https://www.iea.org/help-centre/accessing-iea-products-and-services
- **Sales Contact:** datasales@iea.org
