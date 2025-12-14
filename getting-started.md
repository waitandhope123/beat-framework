# Getting Started with BEAT

This guide explains how to understand and use the **BEAT (Behavioral–External Alignment Theory)** framework.

BEAT is a **diagnostic framework**, not a prediction system.  
Users are encouraged to read the theory and scope documents before applying it.

---

## Step 1: Understand the Framework

Before using BEAT, read:

1. `README.md` — overview and intent  
2. `docs/phases.md` — phase definitions  
3. `docs/scope.md` — boundaries and failure modes  

These documents define **what BEAT is and is not**.

---

## Step 2: Choose an Appropriate Use Case

BEAT is best suited for:

- Historical comparison
- Structural diagnostics
- Regime and state analysis
- Identifying early warning phases (P3–P4)

BEAT is **not** suited for:
- Short-term forecasting
- Probability estimation
- Tactical decision-making

Confirm scope compatibility before proceeding.

---

## Step 3: Select Data (Optional)

BEAT does not require a specific dataset, but empirical applications have used:

- CNTS (domestic unrest)
- Polity (regime authority)
- Correlates of War (state coherence indicators)

This repository does not redistribute licensed data.  
Users must obtain datasets independently and respect their licenses.

---

## Step 4: Operationalize BEAT

A minimal operationalization involves:

1. Measuring **internal strain** over time  
2. Identifying **regime stress or authority erosion**  
3. Detecting **loss of state coherence**

Assign phases based on the joint behavior of these dimensions,
using the logic described in `docs/methods.md`.

---

## Step 5: Interpret Results Carefully

When interpreting BEAT phases:

- Treat **Phase 3–4** as diagnostic warnings, not predictions
- Treat **Phase 5** as confirmation of breakdown, not foresight
- Consider scope limitations explicitly

Avoid collapsing BEAT phases into a single numeric score.

---

## Step 6: Replication and Extension

BEAT is designed to be extended carefully.

Permissible extensions include:
- Additional internal strain indicators
- Alternative authority measures
- Domain-specific coherence signals

Extensions should preserve:
- phase logic
- conservative Phase 5 assignment
- explicit scope boundaries

---

## Step 7: Cite BEAT

If BEAT informs your work, please cite the repository using the
`CITATION.cff` file in the project root.

---

## Where to Go Next

- For theory: `docs/phases.md`
- For methods: `docs/methods.md`
- For limitations: `docs/scope.md`
- For visualization: `figures/README.md`

---

## Versioning

This guide corresponds to **BEAT v1.0**.
