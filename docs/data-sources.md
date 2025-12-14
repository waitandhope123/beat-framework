# Data Sources and Usage

This document lists the principal data sources used during the development,
testing, and stress evaluation of the **BEAT (Behavioral–External Alignment Theory)**
framework.

BEAT is a conceptual and diagnostic framework.  
Licensed datasets are **not redistributed** in this repository.

---

## Core Data Sources

### Cross-National Time-Series (CNTS)
- **Purpose:** Measurement of internal strain and domestic unrest
- **Usage:** Aggregate domestic conflict indicators were used to identify
  sustained internal stress patterns over time.
- **Role in BEAT:** Primary internal strain signal

---

### Polity / Polity5
- **Purpose:** Measurement of regime authority and political transitions
- **Usage:** Regime scores and regime change events were used to identify
  authority erosion and institutional stress.
- **Role in BEAT:** Regime / authority stress signal

---

### Correlates of War (COW)

#### State System Membership (Independent States Since 1815)
- **Purpose:** Identification of sovereign states and state lifespans
- **Usage:** Used to determine state entry, exit, and dissolution timing.
- **Role in BEAT:** State continuity and breakdown confirmation

#### Intra-State Wars
- **Purpose:** Identification of internal armed conflict
- **Usage:** War onset and participation were used as indicators of loss of
  state coherence.
- **Role in BEAT:** Coherence breach detection

#### Intra-State War Participants
- **Purpose:** Identification of all state participants in internal conflicts
- **Usage:** Used to avoid attributing conflict solely to initiating actors.
- **Role in BEAT:** Improved breakdown classification

---

## Supplementary and Contextual Data

### National Material Capabilities (NMC)
- **Purpose:** Broad state capacity context
- **Usage:** Used for contextual comparison, not direct phase assignment.
- **Role in BEAT:** Background external capacity reference

---

### Quality of Government (QoG)
- **Purpose:** Institutional quality and governance indicators
- **Usage:** Supplementary validation and contextual checks.
- **Role in BEAT:** Supporting institutional context

---

### Maddison Project Database
- **Purpose:** Long-run economic and population context
- **Usage:** Historical plausibility checks and comparative context.
- **Role in BEAT:** Deep-time structural background

---

### Historical Population Datasets
- **Purpose:** Demographic scale and pressure context
- **Usage:** Used for qualitative interpretation of historical cases.
- **Role in BEAT:** Structural background, not phase triggers

---

### Climate and Environmental Proxies
- **Purpose:** Environmental stress context (ancient and pre-modern cases)
- **Usage:** Used to contextualize long-run instability patterns.
- **Role in BEAT:** Stress amplifier context only

---

## Important Notes

- BEAT does **not** require any single dataset to function.
- Minimal modern implementations can be constructed using:
  - CNTS
  - Polity
  - Correlates of War
- Historical and environmental datasets were used for
  comparative validation, not mechanical replication.
- Users must obtain and cite all datasets independently
  and comply with their respective licenses.

---

## Versioning

This data usage summary corresponds to **BEAT v1.0**.
