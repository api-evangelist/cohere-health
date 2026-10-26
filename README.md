# Cohere Health (cohere-health)

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

Cohere Health is a United States clinical-intelligence and utilization-management company that digitizes prior authorization for health plans. Its Unify platform applies clinical AI and evidence-based policy to authorization intake, review, and decisioning, and its API suite implements the HL7 Da Vinci Burden Reduction guides — Coverage Requirements Discovery (CRD), Documentation Templates and Rules (DTR), and Prior Authorization Support (PAS) — to help payers meet the CMS Interoperability and Prior Authorization Final Rule (CMS-0057-F). The FHIR R4 APIs support SMART on FHIR applications and are sold to and embedded with health plans rather than offered through a self-serve public developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cohere-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cohere-health/refs/heads/main/apis.yml)

## Tags

- Healthcare
- United States
- Prior Authorization
- Utilization Management
- Payer
- FHIR
- HL7
- Da Vinci
- SMART on FHIR
- Interoperability

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Cohere Health Coverage Requirements Discovery (CRD) API

HL7 Da Vinci Coverage Requirements Discovery (CRD) FHIR API that lets a provider system instantly verify whether prior authorization is required and confirm service coverage at the point of care.

- **Human URL:** [https://www.coherehealth.com/utilization-management/api-based](https://www.coherehealth.com/utilization-management/api-based)

#### Tags

- Coverage Requirements Discovery
- FHIR
- Da Vinci
- Prior Authorization

#### Properties

- [Documentation](https://www.coherehealth.com/utilization-management/api-based)

### Cohere Health Documentation Templates and Rules (DTR) API

HL7 Da Vinci Documentation Templates and Rules (DTR) FHIR API that intelligently gathers and submits the documentation a prior authorization request requires, driven by digitized medical policy (FHIR Questionnaire plus CQL).

- **Human URL:** [https://www.coherehealth.com/utilization-management/api-based](https://www.coherehealth.com/utilization-management/api-based)

#### Tags

- Documentation Templates and Rules
- FHIR
- Da Vinci
- Prior Authorization

#### Properties

- [Documentation](https://www.coherehealth.com/utilization-management/api-based)

### Cohere Health Prior Authorization Support (PAS) API

HL7 Da Vinci Prior Authorization Support (PAS) FHIR API that submits an authorization request and returns the outcome, wrapping X12 278 utilization-management exchange in a FHIR interface for CMS-0057-F compliance.

- **Human URL:** [https://www.coherehealth.com/utilization-management/api-based](https://www.coherehealth.com/utilization-management/api-based)

#### Tags

- Prior Authorization Support
- FHIR
- Da Vinci
- Prior Authorization

#### Properties

- [Documentation](https://www.coherehealth.com/utilization-management/api-based)

## Common Properties

- [Website](https://www.coherehealth.com/)
- [Documentation](https://www.coherehealth.com/utilization-management/api-based)
- [Login](https://login.coherehealth.com/)
- [GitHub Organization](https://github.com/coherehealth)
- [LinkedIn](https://www.linkedin.com/company/cohere-health)
- [Blog](https://www.coherehealth.com/blog)
- [Support](https://www.coherehealth.com/connect)
- [Privacy Policy](https://www.coherehealth.com/privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
