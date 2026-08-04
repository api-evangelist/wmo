# World Meteorological Organization (WMO)

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

The World Meteorological Organization (WMO) is a specialized agency of the United Nations that coordinates global meteorological, climatological, hydrological, and related geophysical sciences. WMO provides public REST APIs for weather data, climate observation metadata, hydrological monitoring, severe weather alerts, and the WIS2 global meteorological information exchange system.

## APIs

| API | Base URL | Auth |
|-----|----------|------|
| World Weather Information Service | `https://worldweather.wmo.int/en/json/` | None |
| OSCAR/Surface REST API | `https://oscar.wmo.int/surface/rest/api` | None (read) |
| WIS2 Global Discovery Catalogue | `https://wis2-gdc.weather.gc.ca` | None |
| WIS2 Global Broker (MQTT) | `mqtts://globalbroker.meteo.fr:8883` | Public (everyone/everyone) |
| WHOS Hydrological Observing System | `https://whos.geodab.eu/gs-service/services/essi` | Token (free registration) |

## Resources

- Website: https://wmo.int/
- Community: https://community.wmo.int/
- GitHub: https://github.com/World-Meteorological-Organization
- WIS2 Documentation: https://docs.wis2box.wis.wmo.int/
- Severe Weather: https://severeweather.wmo.int/
- Data Exchange: https://wmo.int/activities/type-of-activity/exchange-data
