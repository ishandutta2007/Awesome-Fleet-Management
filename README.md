# Awesome-Fleet-Management

## Top Fleet Management Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Telematics, GPS Tracking, ELD/HOS Compliance, Driver Safety, Fuel & Vehicle Operations*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Fleet Management**. These systems provide real-time vehicle tracking, electronic logging, safety cameras, maintenance, fuel insights, and compliance tools for commercial fleets.

**Examples** include Samsara, Motive (formerly KeepTruckin), Geotab, Verizon Connect, Azuga, Teletrac Navman, Quartix, Linxup, and ClearPathGPS (the category leaders).

**Open-source emphasis**: Full commercial telematics suites dominate regulated and large fleets. The strongest open option is **Traccar** for GPS tracking and basic fleet visibility, plus related open GPS and mapping tools. This section lists the best available open resources and is realistic about the commercial gap for ELD, AI video, and enterprise compliance.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Samsara](https://www.samsara.com/)**  
  Leading connected operations platform combining vehicle telematics, AI dash cams, ELD, asset tracking, and safety coaching for mid-to-large fleets.

- **[Motive (formerly KeepTruckin)](https://gomotive.com/)**  
  Fleet and driver platform focused on ELD compliance, safety, AI cameras, and fleet visibility with flexible contracting for carriers of many sizes.

- **[Geotab](https://www.geotab.com/)**  
  Open-platform telematics provider with broad vehicle coverage, marketplace integrations, ELD, and strong data/analytics capabilities at competitive entry pricing.

- **[Verizon Connect](https://www.verizonconnect.com/)**  
  Enterprise fleet and field-service platform offering tracking, routing, compliance, and workforce tools backed by carrier-grade infrastructure.

- **[Azuga](https://www.azuga.com/)**  
  Fleet tracking and safety platform with GPS, driver behavior, and vehicle diagnostics for commercial fleets.

- **[Teletrac Navman](https://www.teletracnavman.com/)**  
  Fleet management and compliance solutions covering tracking, ELD, and operational insights for commercial vehicles.

- **[Quartix](https://www.quartix.com/)**  
  Vehicle tracking platform popular with small-to-mid fleets for simple, reliable GPS tracking and reporting.

- **[Linxup](https://www.linxup.com/)**  
  Affordable GPS fleet tracking and dash-cam solutions aimed at small and medium businesses.

- **[ClearPathGPS](https://www.clearpathgps.com/)**  
  Fleet tracking and management software for real-time location, alerts, and operational visibility.

- **[Other regional and specialty telematics providers](https://www.example.com/)**  
  Additional ELD, camera, and tracking platforms serving niche or geographic markets.

## Open-Source GitHub Projects
- **[Traccar](https://github.com/traccar/traccar)**  
  Leading open-source GPS tracking platform (Apache 2.0)—supports 200+ device protocols, real-time tracking, geofences, reports, and multi-user fleet management; self-host or use managed hosting.

- **[Traccar Web & Manager apps](https://github.com/traccar)**  
  Open web dashboard and mobile apps that complete the Traccar tracking experience.

- **[OwnTracks and personal/location open trackers](https://github.com/owntracks)**  
  Open location-tracking tools sometimes adapted for light asset or vehicle monitoring.

- **[Open GPS protocol parsers and device libraries](https://github.com/)**  
  Community libraries for decoding common GPS tracker protocols used with Traccar or custom servers.

- **[OsmAnd / open mapping and navigation](https://github.com/osmandapp)**  
  Open-source offline maps and navigation that can complement fleet routing and driver apps.

- **[OpenStreetMap-based routing open engines](https://github.com/)**  
  Open routing engines (e.g., OSRM, GraphHopper) usable for custom dispatch and route optimization prototypes.

- **[EL D / HOS open research and compliance helpers](https://github.com/)**  
  Limited open tools and documentation around hours-of-service concepts (full certified ELD remains commercial/regulated).

- **[Telematics data open pipelines](https://github.com/)**  
  ETL and warehouse patterns for ingesting GPS and CAN data into open analytics stacks.

- **[Dashcam and video open analysis prototypes](https://github.com/)**  
  Experimental computer-vision projects for event detection (not a substitute for certified AI safety platforms).

- **[Documentation and self-hosting guides for Traccar](https://www.traccar.org/)**  
  Official and community resources for deploying and scaling open GPS tracking.

### Additional Strong Open-Source Options
- Self-hosting **Traccar** for full ownership of tracking data and hardware flexibility across many GPS device brands.
- Combining Traccar with open maps and routing for basic fleet visibility and geofencing.
- Accepting that certified ELD/HOS, AI video safety, OEM deep integrations, predictive maintenance, and enterprise support still require commercial platforms (Samsara, Motive, Geotab, Verizon Connect, etc.).
- Focusing open-source efforts on data ownership, avoiding per-vehicle lock-in, and lower cost for smaller or non-regulated fleets.

**Frameworks for building custom systems**: Deploy GPS devices that speak supported protocols → run Traccar server → view real-time and historical tracks → add geofences and reports → optionally feed data to open BI or commercial ELD/safety layers. Suitable for small fleets, asset tracking, and organizations that prioritize self-hosting. Most regulated commercial carriers and large fleets rely on commercial telematics platforms for compliance and safety features.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Fleet systems involve vehicle location, driver data, and often regulated hours-of-service. Certified ELD devices and proper privacy/security practices are required where mandated by law. This list is not legal or compliance advice.

---
**Made for fleet managers, transportation operators, and telematics engineers.**
Let's keep vehicles visible, data-owned, and as open as practical.
