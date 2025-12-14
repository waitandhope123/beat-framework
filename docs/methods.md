# Methods and Operationalization

This document describes how **BEAT (Behavioral–External Alignment Theory)** phases are operationalized using empirical data.

The goal of BEAT’s methods is **diagnostic classification**, not prediction or optimization.  
All thresholds and rules are chosen to favor interpretability, robustness, and cross-historical consistency.

---

## Conceptual Structure

BEAT evaluates state stability along three conceptual dimensions:

1. **Internal Strain**  
   Observable domestic stress within a polity.

2. **Regime / Authority Stress**  
   Erosion or loss of governing authority and institutional legitimacy.

3. **State Coherence**  
   The ability of the state to maintain monopoly over authority and violence.

Phases are assigned based on the **joint behavior** of these dimensions over time.

---

## Data Sources (Indicative)

BEAT has been empirically tested using established datasets, including:

- **CNTS** — internal unrest and conflict indicators  
- **Polity** — regime authority and transitions  
- **Correlates of War (COW)** — state membership and intra-state conflict  
- Supplementary historical and climatic datasets where relevant

Licensed raw data are not redistributed in this repository.

---

## Internal Strain Measurement

Internal strain is operationalized using:
- Aggregate domestic conflict indicators
- Absolute levels (not only within-country deviations)
- Multi-year persistence rather than single-year spikes

Key principles:
- **Sustained strain > episodic unrest**
- Volatility is treated as meaningful only when persistent

Rolling windows (typically 3–5 years) are used to reduce noise.

---

## Regime / Authority Stress

Regime stress is captured through:
- Absolute regime weakness
- Sharp regime deterioration over short time horizons

Examples include:
- Low authority scores
- Rapid multi-year drops in regime indicators
- Periods of institutional ambiguity or interregnum

Regime stress alone is **not sufficient** to indicate breakdown.

---

## State Coherence (Hard Constraint)

State coherence represents the **loss of effective monopoly of authority**.

Indicators include:
- Participation in intra-state armed conflict
- Fragmentation of governing authority
- State dissolution or functional collapse

**Coherence loss is required for Phase 5 assignment.**  
This constraint is intentionally strict to prevent overclassification.

---

## Phase Assignment Logic (Simplified)

- **Phase 2:**  
  Low sustained internal strain; no regime or coherence stress

- **Phase 3:**  
  Rising or moderate internal strain and/or early regime stress

- **Phase 4:**  
  Sustained internal strain combined with regime stress  
  (without confirmed coherence loss)

- **Phase 5:**  
  Sustained internal strain + regime stress + coherence loss

Phase definitions are rule-based, not model-optimized.

---

## Calibration Philosophy

BEAT calibration prioritizes:
- Cross-case consistency
- Resistance to false positives
- Interpretability over maximal fit

Phase 5 is deliberately conservative.  
Early warning functionality is concentrated in **Phases 3 and 4**.

---

## Validation and Stress Testing

BEAT has been stress-tested by:
- Blind historical runs
- Cross-national post-1945 analysis
- False-positive and false-negative evaluation
- Explicit failure-mode classification

Performance varies by scope category, as documented in `scope.md`.

---

## Replication

Replication requires:
- Access to the relevant licensed datasets
- Reimplementation of the documented rules
- Attention to scope compatibility

This repository provides sufficient methodological detail for independent replication.

---

## Versioning

These methods correspond to **BEAT v1.0**.  
Changes to operationalization will be versioned explicitly.
