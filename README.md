# Known

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

Known is a voice-first, swipeless dating application founded in 2025 by Celeste Amadon and Asher Allen, headquartered in San Francisco, California. Instead of profiles, feeds, queues, and swiping, Known onboards users through a voice-AI interview and then sends one curated introduction at a time, with a 24-hour acceptance window on both sides. When both people accept, Known helps pick a restaurant that fits both sets of preferences and checks calendar availability, then collects a short post-date check-in to refine future matches.

The company optimizes for in-person dates rather than engagement, and has raised $9.7M from Forerunner Ventures, NFX, and other investors. The product is iOS-only in the United States today, with waitlists for Android and for Apple users outside the US.

**Known publishes no public API, developer portal, or SDKs.** It is catalogued here as a consumer application profile. The artifacts in this repo reflect only what Known actually publishes.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | [`llms/known-llms.txt`](llms/known-llms.txt) | searched — saved verbatim from https://known.com/llms.txt |
| Well-Known index | [`well-known/known-well-known.yml`](well-known/known-well-known.yml) | searched — all `/.well-known/` paths 404 (recorded negative) |
| Domain security | [`security/known-domain-security.yml`](security/known-domain-security.yml) | probed — TLS 1.3, HSTS, SPF, DMARC (quarantine); no DNSSEC, no CAA |

Backed by: Forerunner Ventures, NFX — https://known.com
