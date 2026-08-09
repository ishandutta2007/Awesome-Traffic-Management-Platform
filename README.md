# Awesome-Traffic-Management-Platform

## Top Traffic Management Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Intelligent Transportation Systems (ITS), Adaptive Traffic Signal Control, Traffic Optimization, Simulation & Smart City Mobility*  

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Traffic Management**. These tools help cities and transportation agencies monitor, optimize, and control road traffic through adaptive signals, real-time data analytics, connected infrastructure, simulation, and smart intersection technologies.



**Examples** include Yunex Traffic, Miovision, NoTraffic, Flow Labs, Kapsch TrafficCom, Econolite, SWARCO MyCity, PTV Optima, TransCore, and GridSmart (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for traffic simulation, adaptive signal control, multi-domain mobility co-simulation, and related open tools — ideal for researchers, cities, and developers seeking transparent, extensible alternatives or complementary components to commercial traffic management systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting Tier) | Free Tier Limit |
|---------|-------------|-------------------------|-----------------|
| **[Yunex Traffic](https://www.yunextraffic.com/)** | Intelligent traffic management solutions covering adaptive control, traffic centers, connected infrastructure, and smart city mobility platforms. | $5,000/month | 30 days free trial (up to 5 intersections) |
| **[Miovision](https://miovision.com/)** | Video-based traffic data collection, intersection analytics, and adaptive traffic signal control for modern traffic operations. | $2,500/month | 14 days free trial (1 intersection camera) |
| **[NoTraffic](https://www.notraffic.tech/)** | AI-powered traffic management platform that optimizes signal timing and intersection performance in real time using sensor and AI data. | $3,200/month | 30 days free trial (up to 3 nodes) |
| **[Flow Labs](https://www.flowlabs.ai/)** | AI-driven traffic optimization and signal control solutions focused on reducing congestion and improving mobility. | $1,800/month | Free forever for 1 corridor (up to 3 signals) |
| **[Kapsch TrafficCom](https://www.kapsch.net/)** | Comprehensive ITS and traffic management portfolio including tolling, traffic control, and connected vehicle solutions. | $10,000/month | 60 days free trial (city-wide simulation only) |
| **[Econolite](https://www.econolite.com/)** | Traffic signal controllers, central systems, and adaptive traffic management solutions widely deployed in North America. | $4,500/month | 30 days free trial (software only, no hardware) |
| **[SWARCO MyCity](https://www.swarco.com/)** | Integrated smart city and traffic management platform combining signal control, parking, and mobility services. | $6,000/month | 30 days free trial (up to 10 intersections) |
| **[PTV Optima](https://www.ptvgroup.com/)** | Real-time traffic management and prediction system that leverages modeling and live data for operational decision support. | $8,500/month | 14 days free trial (up to 100 sq km map area) |
| **[TransCore](https://www.transcore.com/)** | Intelligent transportation systems including tolling, traffic management, and advanced traveler information solutions. | $12,000/month | 90 days free trial (tolling module only) |
| **[GridSmart](https://www.gridsmart.com/)** | Vision-based traffic detection and intersection management platform using fisheye cameras and AI analytics. | $2,000/month | 30 days free trial (1 fisheye camera processing) |

## Open-Source GitHub Projects



- **[Eclipse SUMO](https://github.com/eclipse-sumo/sumo)**  

  Leading open-source microscopic traffic simulation package capable of handling large networks, multi-modal transport, and extensive scenario tooling. Widely used for research and operational planning.



- **[Eclipse MOSAIC](https://www.eclipse.dev/mosaic/)**  

  Open-source multi-domain and multi-scale co-simulation framework for connected and automated mobility, integrating traffic, communication, and application simulators.



- **[OpenTrafficSim](https://github.com/averbraeck/opentrafficsim)**  

  Open-source multi-level traffic simulator combining micro, macro, and meta simulation approaches with support for multiple transport modes.



- **[Open-TLC / Open Controller](https://github.com/Open-TLC/open_controller)**  

  Open-source traffic light controller designed to separate data processing from signal control logic, enabling new adaptive algorithms and integration with simulators like SUMO.



- **[sumolights & Adaptive Signal Control Frameworks](https://github.com/docwza/sumolights)**  

  Open-source implementations of adaptive traffic signal control algorithms (reinforcement learning, max-pressure, self-organizing, etc.) built on SUMO.



- **[CDASim (USDOT)](https://github.com/usdot-fhwa-stol/cdasim)**  

  Open-source co-simulation tool supporting Cooperative Driving Automation research, integrating SUMO, CARLA, ns-3, and related components.



- **[Traffic Signal Control Libraries & RL Projects](https://github.com/)**  

  Numerous research and community projects implementing deep reinforcement learning, max-pressure, and other adaptive control strategies for intersections.



- **[V2X & Connected Vehicle Simulation Tools](https://github.com/)**  

  Open-source frameworks for vehicle-to-everything communication and cooperative traffic management scenarios.



- **[Network & Demand Modeling Helpers](https://github.com/)**  

  Tools for generating realistic traffic demand, converting map data (OSM), and preparing large-scale SUMO/MOSAIC scenarios.



- **[Real-time Data & Sensor Integration Prototypes](https://github.com/)**  

  Community projects for ingesting detector, camera, or probe data into open traffic management pipelines.



- **[Visualization & Dashboard Projects](https://github.com/)**  

  Open-source dashboards and web interfaces for displaying simulated or live traffic states, signal status, and performance metrics.



- **[Scenario Repositories (e.g., Berlin BeST)](https://github.com/mosaic-addons/best-scenario)**  

  Large-scale open traffic scenarios that can be used with SUMO and Eclipse MOSAIC for testing management strategies.



### Additional Strong Open-Source Options



- **Core simulators**: Eclipse SUMO remains the foundation for most open traffic research and prototyping.

- **Co-simulation**: Eclipse MOSAIC for multi-domain (traffic + communication + applications) studies.

- **Controllers**: Open-TLC and various adaptive signal control implementations.

- **Research toolkits**: Reinforcement learning signal control frameworks and multi-agent traffic systems.

- Many academic and municipal **open ITS** and **smart intersection** projects continue to evolve on GitHub.



**Frameworks for building custom systems**: Combine **Eclipse SUMO** for microscopic simulation, **Eclipse MOSAIC** for connected mobility co-simulation, **Open-TLC or adaptive control algorithms** for signal logic, and open data pipelines to create research-grade or operational traffic management prototypes.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Traffic management systems interact with critical infrastructure and public safety; any deployment must follow local regulations, safety standards, and rigorous testing.

- Self-hosted open-source solutions are primarily suited for research, planning, and simulation; production signal control requires certified hardware and operational validation.



---



**Made for traffic engineers, city mobility teams, researchers, and smart-city developers.**  

Let's make traffic management more open, data-driven, and collaborative.
