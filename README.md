# Tia Health (tia-health)

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
