# International Energy Agency (IEA)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
