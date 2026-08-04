# Manulife Bank (manulife-bank)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
