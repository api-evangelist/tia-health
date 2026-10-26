# Tia Health (tia-health)

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

Tia Health is a Canadian telehealth platform that connects patients with licensed Canadian providers - family doctors, nurse practitioners, specialists, and naturopaths - for on-demand virtual care by phone, video, and secure messaging. Services include virtual walk-in and family-practice appointments, prescription renewals, sick notes, lab requisitions, and mental health therapy (via partner Focus Mental Wellness). Visits are covered by provincial health plans in Ontario (OHIP), British Columbia (MSP), and Alberta (AHCIP), with paid options elsewhere. Tia Health is part of WELL Health Technologies Corp., one of the largest outpatient clinic networks in Canada.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tia-health/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tia-health/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Canada
- Telehealth
- Virtual Care
- Digital Health
- Primary Care
- Mental Health
- Prescriptions

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

Tia Health is a consumer-facing virtual-care product. As of this review it publishes **no public developer portal, no documented REST/OpenAPI, and no HL7 FHIR CapabilityStatement or SMART-on-FHIR configuration**. Care is delivered through an authenticated patient application (app.tiahealth.com), not through a documented developer API.

Probes performed (see `review.yml` for full HTTP status detail):

- `developer.tiahealth.com`, `docs.tiahealth.com`, `api.tiahealth.com`, `fhir.tiahealth.com` — do not resolve
- `tiahealth.com/developers`, `/developer`, `/api`, `/interoperability` — HTTP 404
- `tiahealth.com/.well-known/smart-configuration`, `/.well-known/openid-configuration` — HTTP 404

In the Canadian market, pan-Canadian FHIR interoperability (CA Core / CA Baseline) is stewarded federally by Canada Health Infoway; Tia Health does not publicly surface a conformance statement.

## Common Properties

- [Website](https://tiahealth.com/)
- [About](https://tiahealth.com/about/)
- [Blog](https://tiahealth.com/blog/)
- [Support](https://tiahealth.com/support/)
- [Contact](https://tiahealth.com/contact/)
- [Login](https://app.tiahealth.com/auth/login/tiaHealth;patientLogin=true)
- [Terms of Service](https://tiahealth.com/terms-of-use)
- [Privacy Policy](https://tiahealth.com/tia-privacy-policy)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
