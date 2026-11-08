# Awesome-Yard-Management-Logistics-Tracking

# Awesome Yard Management & Logistics Tracking

> A curated list of top Yard Management and Logistics Tracking platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing trailer, container, and railcar movements across facility yards.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [FourKites Dynamic Yard](#fourkites-dynamic-yard)
  - [project44 Yard Management](#project44-yard-management)
  - [Descartes Yard Management](#descartes-yard-management)
  - [C3 Solutions Yard Management](#c3-solutions-yard-management)
  - [Manhattan Active Yard Management](#manhattan-active-yard-management)
  - [Kaleris Yard & Transload Management](#kaleris-yard--transload-management)
  - [PINC (Kaleris) Yard Management](#pinc-kaleris-yard-management)
  - [YardView](#yardview)
  - [Blue Yonder Yard Management](#blue-yonder-yard-management)
- [Open-Source Software](#-open-source-software)
  - [FreightRoll YardOS (API Profile)](#freightroll-yardos-api-profile)
  - [Terminal Yard Operating System (YOS) (API Profile)](#terminal-yard-operating-system-yos-api-profile)
  - [Stellplatzdisposition (Streamlit Demo)](#stellplatzdisposition-streamlit-demo)
  - [Hof-Disposition (Streamlit Demo)](#hof-disposition-streamlit-demo)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Yard Management and Logistics Tracking platforms. These are not open-source but are included as reference points for feature comparison.

### FourKites Dynamic Yard
**Type:** Real-time visibility-integrated YMS  
Dynamic Yard is the only yard management system that natively tracks the ETA of each trailer by integrating with FourKites' real-time supply chain visibility network, alongside time on site, to help reprioritize crews and reduce detention costs [citation:2]. The platform creates a digital single source of truth that updates in real time, empowering dock, spotter, and gate teams to coordinate seamlessly. The Live Dashboard surfaces critical KPIs like detention risks, task bottlenecks, and capacity issues, with smart widgets that enable yard managers to respond 85% faster [citation:2]. User-specific applications serve up the next most relevant task for each role, from resetting a dock due to a new ETA to pulling a trailer exiting free detention time [citation:2].  
**Best for:** Organizations wanting yard operations tightly integrated with in-transit shipment visibility and predictive ETAs.

### project44 Yard Management
**Type:** YMS with RFID-based real-time tracking  
project44 Yard Management provides real-time insights and automation across pre-arrival, gate check-in, dock planning, and parking spot management [citation:3]. Real-time location visibility for trailers, containers, and chassis relies on RFID tags and readers, with the ability to link chassis to trailers seamlessly [citation:3]. The platform tracks inventory movement down to the SKU level, tying orders to inbound and outbound shipments so teams can identify which goods are loaded in specific trucks and containers [citation:3]. Automated gate check-in uses self-service kiosks and mobile pre-check-in, while carriers can self-service appointment scheduling with real-time trailer ETAs against scheduled appointments [citation:3].  
**Best for:** Facilities needing RFID-driven asset tracking and SKU-level inventory visibility within the yard.

### Descartes Yard Management
**Type:** Trailer tracking and audit-trail-focused YMS  
Descartes Yard Management is an add-on to Descartes Dock Appointment Scheduling, leveraging the Descartes Global Logistics Network to connect shippers, carriers, and regulatory authorities [citation:4]. Real-time visibility into trailer content and locations enables quick identification of stock on hand to reduce inventory requirements [citation:4]. The platform records trailer status, moves, inspections, and security seal changes, with an automated audit trail for loss prevention and C-TPAT compliance [citation:4][citation:14]. A touch-screen-optimized GUI works on tablets in-cab or in the guard shack, built for low-connectivity environments so content is never lost [citation:4].  
**Best for:** Organizations prioritizing compliance auditing, security seal management, and loss prevention across distributed yards.

### C3 Solutions Yard Management
**Type:** Scalable yard and dock scheduling platform  
C3 Solutions claims customers can find any trailer in 3 seconds, with features to increase gate throughput, eliminate dock congestion, reduce yard trucks by half, and optimize trailer assignment [citation:5]. The platform includes Vision AI gate automation using existing security cameras to identify trucks and trailers by analyzing up to 25 data elements including license plates and DOT numbers, plus driver self check-in via QR code or PIN [citation:5][citation:15]. Claimed ROI includes 50% improvement in gate-in/gate-out times and elimination of driver detention fees up to 100% [citation:5]. The C3 Hive collaboration layer brings shippers, carriers, drivers, suppliers, and stores into one synchronized environment [citation:15].  
**Best for:** High-volume distribution centers and retailers needing AI-powered gate automation and multi-party collaboration.

### Manhattan Active Yard Management
**Type:** Unified YMS within Manhattan Active supply chain suite  
Manhattan Active Yard Management is built to work seamlessly with Manhattan Active Warehouse Management and Transportation Management on a single cloud-native platform [citation:19]. Live trailer interleaving dynamically integrates trailers into door planning using live ETA notifications for inbound and outbound loads [citation:19]. Detention and demurrage capabilities include automatic prioritization of at-risk trailers, systemic identification of trailers at risk, and detailed tracking of yard inventory and actions [citation:19]. Integration with Warehouse Management enables short-order trailer inventory utilization, automatically prioritizing trailers based on out-of-stock exceptions and leveraging demand pool and on-hand inventory levels [citation:19]. Recognized as SupplyTech Breakthrough's Overall Innovation of the Year for 2024 [citation:28].  
**Best for:** Enterprises already using Manhattan Active WMS or TMS wanting yard operations unified with warehouse and transportation execution.

### Kaleris Yard & Transload Management
**Type:** Rail-focused yard management  
Kaleris YTM is a cloud-based rail yard application built specifically for rail operations, helping yards gain visibility, automate work tasks, and align people and resources for maximum throughput [citation:7]. Core capabilities include ERP integration for order and shipment records, automated yard movements with AEI (Automatic Equipment Identification) integration, scale integration for automated railcar load/unload activities, rail rack scheduling, and graphical yard views [citation:7]. YTM Mobile provides tablet-based operations with online and offline modes, supporting inventory management, switch requests, AEI scanning, railcar inspections with pictures, and barcode scanning for seal data [citation:7]. Kaleris also offers Yard Intelligence Suite (YIS), an AI-augmented container placement optimization solution for terminals [citation:29].  
**Best for:** Rail yards and terminals needing specialized railcar management with AEI integration and offline-capable mobile operations.

### PINC (Kaleris) Yard Management
**Type:** IoT-driven digital yard platform  
PINC, now part of Kaleris, provides The Digital Yard platform for yard management, leveraging an extensive IoT sensor network that includes RFID, GPS, optical, and cellular technologies to capture and share real-time information via web API . The platform automates data collection, workflows, schedule prioritization, alerts, performance management, and integration with existing systems. PINC claims deployment in 2 to 8 weeks with a 6 to 9 month return [citation:8]. Hundreds of the largest organizations rely on Kaleris software solutions for real-time visibility into transportation and yard operations [citation:8].  
**Best for:** Organizations wanting rapid deployment with IoT-based real-time asset tracking and a proven ROI track record.

### YardView
**Type:** Purpose-built YMS with in-cab driver tasking  
YardView has focused exclusively on yard management since 1998, with hundreds of sites across the U.S., Canada, and Mexico [citation:9]. The platform bridges the gap between transportation and warehouse operations, with real-time visibility and complete operational control over trailer and container tracking, dock scheduling, and yard visibility [citation:9]. YardView supports two communication paths: OTR drivers receive automated text updates (door ready, load complete, departure instructions) without needing an app, while yard drivers use an in-cab smart client with Accept → Start → Finish workflow and Next-Best Move recommendations to reduce empty travel time and fuel costs [citation:22]. The intelligent tasking engine assigns next-best moves to cut down on crisscrossing the yard and maximize labor hours [citation:22].  
**Best for:** Mid-sized operations wanting a proven, purpose-built YMS with strong driver communication and in-cab tasking.

### Blue Yonder Yard Management
**Type:** AI-powered YMS integrated with WMS  
Blue Yonder's yard management solution integrates with its Warehouse Management system to create a fully automated yard system. Penske Logistics deployed the solution at its Shippensburg, Pennsylvania distribution center, using Panasonic Edge devices and AI-driven cameras to eliminate manual trailer entries, reduce errors, strengthen compliance, and improve gate throughput [citation:10]. Vehicle images and timestamps are stored for audit and dispute resolution, and the integration between yard management and WMS improved data synchronization and quality [citation:10]. The Shippensburg deployment is now a blueprint for future rollouts across Penske's network [citation:10].  
**Best for:** Organizations already using Blue Yonder WMS wanting computer vision-powered gate automation and yard-to-warehouse integration.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Yard Management tools. The open-source ecosystem for full YMS is nascent; most available projects are demos, API profiles, or niche tools rather than production-grade platforms.

### FreightRoll YardOS (API Profile)
**Stack:** (Check repository) | **License:** Proprietary (API profile)  
FreightRoll is a logistics technology company whose flagship product, YardOS, is a customizable Yard Operating/Management System (YMS) that turns shipping and receiving yards into driver-friendly, self-service hubs [citation:11]. Listed on GitHub's yard-management topic as an independent third-party profile of a public API surface by API Evangelist. This is not an open-source codebase but an API documentation profile for a commercial product.  
**Best for:** Developers wanting to understand FreightRoll's API surface for potential integration, not as a self-hosted solution.

### Terminal Yard Operating System (YOS) (API Profile)
**Stack:** (Check repository) | **License:** Proprietary (API profile)  
Terminal Industries (Terminal Logistics) is the company behind the Terminal Yard Operating System (YOS), described as an AI-native, fully-integrated platform for yard operations across logistics and supply chain [citation:11]. Like FreightRoll, this is listed as an API profile rather than an open-source implementation.  
**Best for:** Teams researching commercial AI-native YMS APIs for integration planning.

### Stellplatzdisposition (Streamlit Demo)
**Stack:** Python / Streamlit | **License:** Open Source (per GitHub)  
A German-language interactive Streamlit demo for parking incoming swap bodies (Wechselbrücken) in nested rows within a yard [citation:11]. This is an educational/demonstration tool rather than a production YMS, illustrating yard disposition logic and optimization concepts.  
**Best for:** Developers and students wanting to explore yard disposition algorithms in Python.

### Hof-Disposition (Streamlit Demo)
**Stack:** Python / Streamlit | **License:** Open Source (per GitHub)  
A Streamlit demo for yard disposition (Hof-Disposition) that simulates yard vehicle failures or fluctuating travel times, demonstrating robust yard dispatch logic [citation:11]. Similar to Stellplatzdisposition, it is a conceptual demo rather than a deployable platform.  
**Best for:** Learning and prototyping yard optimization algorithms.

---

## 📊 Comparison at a Glance

| Software | License | Type | Real-time Tracking | Best For |
|----------|---------|------|-------------------|----------|
| **FourKites Dynamic Yard** | Proprietary | Visibility-integrated YMS | ✅ ETA + on-site | In-transit + yard correlation |
| **project44 Yard** | Proprietary | RFID-based YMS | ✅ RFID | SKU-level yard inventory |
| **Descartes Yard** | Proprietary | Audit-focused YMS | ✅ | Compliance + loss prevention |
| **C3 Solutions** | Proprietary | AI gate automation YMS | ✅ Vision AI | High-volume DCs |
| **Manhattan Active YM** | Proprietary | Unified WMS/TMS YMS | ✅ | Manhattan suite users |
| **Kaleris YTM** | Proprietary | Rail-focused YMS | ✅ AEI | Rail yards + terminals |
| **PINC (Kaleris)** | Proprietary | IoT digital yard | ✅ IoT sensors | Rapid IoT deployment |
| **YardView** | Proprietary | Purpose-built YMS | ✅ | Driver tasking + mid-market |
| **Blue Yonder YM** | Proprietary | WMS-integrated YMS | ✅ Computer vision | Blue Yonder WMS users |
| **FreightRoll YardOS** | Proprietary (API) | API profile | (Check) | API integration research |
| **Stellplatzdisposition** | Open Source | Streamlit demo | ❌ | Learning yard logic |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Yard Management or Logistics Tracking tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source YMS ecosystem is limited; production-grade open-source yard management platforms are rare.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
