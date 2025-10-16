# Y–K Delta SAR — Hyperspectral Imaging for Search & Rescue (Working Literature Review)

*Last updated: 2025-10-16*

## Project Summary&#x20;

When a person or boat goes missing, local Search and Rescue (SAR) teams often have to cover large areas  very quickly. Most searches today use **drones** and **thermal cameras** that detect **heat**. Thermal imaging works best when there’s a strong temperature difference between people and the ground. But during daylight, in fog, or on water, thermal sensors don't work, especially when the surface is cold or when people wear insulated clothing.

**Hyperspectral imaging** is different. Instead of measuring heat, it captures **hundreds of narrow colors of light** that reflect from different materials, such as life jackets, boats, or human skin. Every object has a unique “spectral fingerprint.” By teaching the computer what these fingerprints look like, hyperspectral cameras can find people or debris even when they’re cold, covered, or in the water.

Because the Yukon–Kuskokwim (Y–K) Delta is so big and hard to reach, **manned aircraft** are better for this system than small drones. Aircraft can carry heavier sensors, cover hundreds of miles, and stay in the air for hours. Drones are excellent for local follow-up, but airplanes are faster for wide-area searches after storms. Our proposal would combine Nalaquq’s experience in local SAR training with new **real-time hyperspectral imaging** developed by Jayson Boubin (SUNY-B) to help villages like Quinhagak, Eek, and Goodnews detect people and boats quickly and safely.

---

## Summary Table of Key Studies

| No. | Citation                                       | Platform                     | Sensor Type / Range                       | Main Application                                       | SAR Relevance                                                           |
| --- | ---------------------------------------------- | ---------------------------- | ----------------------------------------- | ------------------------------------------------------ | ----------------------------------------------------------------------- |
| 1   | Park et al. (2023) – *Adv. Space Res.*         | Manned aircraft (Cessna 208) | Specim AisaEAGLE (400–1000 nm, 127 bands) | Small-object detection at sea                          | Direct maritime SAR use; detected mannequins and lifebuoys              |
| 2   | Krekeler et al. (2023) – *Environ. Earth Sci.* | Ground / lab-based           | FieldSpec 4 (350–2500 nm)                 | Human materials library (skin, clothing, blood)        | Foundation for human detection and spectral library design              |
| 3   | Bhargava et al. (2024) – *Heliyon*             | Airborne, UAV, Satellite     | Multi-platform review (0.4–2.5 µm)        | Agriculture, flood, medical, and disaster applications | Establishes core sensor principles, flood mapping methods useful to SAR |
| 4   | Stevenson et al. (2005) – *SPIE*               | Manned aircraft (CAP ARCHER) | VNIR pushbroom HSI + panchromatic         | Real-time U.S. Civil Air Patrol system                 | Operational manned-aircraft HSI for SAR                                 |
| 5   | Schaum (2015) – *Applied Optics*               | Algorithmic (NRL)            | ACE/RX algorithms                         | Spectral anomaly detection                             | Real-time algorithms for spectral cueing                                |
| 6   | Yan et al. (2019) – *Optical Review*           | Hyperspectral dataset        | Deep learning (CNN)                       | Small-object detection                                 | Adaptable to debris/person detection from HSI                           |
| 7   | Army University Press (2024) – *AI‑HyperCal*   | Tactical aircraft            | AI-based calibration system               | Crash/wreckage detection                               | Real-time calibration under field conditions                            |
| 8   | USGS (2014) – *OFR 2014‑1197*                  | Airborne/ground              | ENVI-based workflow                       | Environmental anomaly mapping                          | Workflow transferable to SAR spectral anomaly detection                 |
| 9   | Wired (2007) – *Super‑Vision Camera Search*    | CAP ARCHER aircraft          | VNIR system                               | Steve Fossett search                                   | Documented real-world HSI SAR use                                       |

---

## Integration Notes for Proposal

- Combine **Krekeler (2023)** human-material library with **ARCHER-style real-time cueing** and **Park (2023)** object detection workflow.
- Use **Bhargava (2024)** as the framework for HSI fundamentals, platform selection, and flood-response applications.
- Develop a **Y–K Delta spectral library** including local materials (PFDs, aluminum skiffs, tundra soils, ice).
- Employ **manned aircraft** for regional coverage, with **drones** for follow-up verification.
- Ensure all data collection follows **Nalaquq’s co-production principles** for community control and training.

---
