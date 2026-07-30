# Known

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
