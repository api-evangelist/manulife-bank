# Manulife Bank (manulife-bank)

Manulife Bank of Canada is a Schedule I federally chartered bank and a wholly-owned subsidiary of The Manufacturers Life Insurance Company, part of Manulife Financial Corporation. Launched in 1993 as Canada's first branchless (direct) bank — and the first federally regulated bank opened by an insurance company in Canada — it operates entirely through online banking, a mobile app, and telephone banking, with no physical branches. It is best known for the Manulife One all-in-one account, the Advantage Account, GICs, mortgages, and lines of credit.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/manulife-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/manulife-bank/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Manulife Bank publishes **no first-party public developer portal and no downloadable API specifications**. Host probes on `developer.manulifebank.ca`, `api.manulifebank.ca`, `apis.manulifebank.ca`, `developer.manulife.ca`, and `developer.manulife.com` did not resolve (HTTP 000), and the public site (`www.manulifebank.ca`) is bot-protected (HTTP 403 to automated clients). The bank is not among the small number of Canadian institutions that run a developer portal.

Canada's **Consumer-Driven Banking** (open-banking) framework — legislated in Budget 2024 and the Fall Economic Statement 2024, with the Financial Consumer Agency of Canada (FCAC) as overseer — is legislated but **not yet operational**; the Bank of Canada has not committed to a launch date. As a result, consumer financial data access to Manulife Bank today is voluntary and occurs through **financial-data aggregators** (Plaid, Flinks, MX) using consumer-permissioned / screen-scraping access, not a first-party bank API. Interac e-Transfer is available as a consumer feature but is not exposed as a documented public API.

This is an **identity-only (built-stub)** record: no public API surface exists to catalog.

## Tags

- Financial Services
- Banking
- Canada
- Schedule I Bank
- Direct Bank
- Digital Banking
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Manulife Bank exposes no documented first-party public API.

## Common Properties

- [Website](https://www.manulifebank.ca/)
- [About Us](https://www.manulifebank.ca/support/about-us.html)
- [LinkedIn](https://www.linkedin.com/company/manulife-bank)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
