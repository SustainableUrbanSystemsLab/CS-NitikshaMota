<img width="1013" height="459" alt="image" src="https://raw.githubusercontent.com/SustainableUrbanSystemsLab/CS-NitikshaMota/main/GraphicalAbstract.png" />

# Climate-Migration Readiness in Atlanta  
## Missing-Middle Housing + Resilient Infrastructure Simulations  
*(Revit + Autodesk Forma)*

**Independent Study – M.S. Urban Design**  
**Author:** Nitiksha Mota  - [LinkedIn](https://www.linkedin.com/in/nitiksha-mota/)

**Institution:** Georgia Institute of Technology  
**Advisors:** Prof. Brian Stone, Prof. Patrick Kastner  

---

## 1. Overview

This repository documents a **replicable workflow** for evaluating how **missing-middle housing infill** can support **climate-migration readiness** while balancing **environmental resilience** in Atlanta neighborhoods.

The study focuses on:
- Translating **zoning and overlay codes** into buildable scenarios  
- Testing **density increases** through ADUs, townhomes, and small multifamily housing  
- Evaluating **microclimate, energy, wind, and stormwater impacts** using simulation tools  

This repo is intended as a **guide for future students** who want to:
- Run neighborhood-scale simulations
- Compare multiple density scenarios
- Produce policy-relevant, climate-informed urban design analysis

---

## 2. Research Question

**How can existing zoning frameworks in climate-migration receiving cities like Atlanta be leveraged to increase housing supply while minimizing environmental and microclimatic impacts?**

---

## 3. Case Study Neighborhoods

| Neighborhood | Role in Study | Development Pattern |
|-------------|-------------|---------------------|
| Reynoldstown | Retrofit model | Built-out historic neighborhood |
| Vine City | Rebuild model | Disinvested, vacant-parcel-rich TOD area |
| Midtown | Reference model | Dense, transit-connected urban core |

---

## 4. Tools Used

### Modeling & Simulation
- **Autodesk Revit** – massing + context modeling
- **Autodesk Forma** – climate and performance simulations
  - Sun hours
  - Heat stress
  - Wind comfort
  - Solar panel potential

### Planning & Policy
- Atlanta Zoning Ordinance (R-5, SPI-19, SPI-16)
- BeltLine Overlay District regulations
- MARTA proximity and TOD guidelines

---


---

## 5. Workflow Summary

### Step 1 — Define Site Type
Each neighborhood is categorized by **growth logic**:
- **Retrofit** (Reynoldstown): limited vacancy, backyard infill
- **Rebuild** (Vine City): block-scale redevelopment
- **Reference** (Midtown): contextual benchmark

---

### Step 2 — Translate Zoning Into Design Rules
For each site:
- Maximum units per lot
- Height and setback limits
- Parking requirements or reductions
- ADU permissions
- Overlay intent (TOD, walkability, affordability)

This step ensures proposals are **code-aligned**.

---

### Step 3 — Create Density Scenarios
Each site includes:
- **Existing condition**
- **Proposal 1** (moderate infill)
- **Proposal 2** (higher density infill)

Scenarios differ in:
- Number of units
- Roof area
- Tree canopy loss
- Ground permeability

---

## 6. Simulation Workflow (Core of the Study)

### 6.1 Revit Preparation
**Goal:** Comparable, clean massing models.

Best practices:
- Use simple massing (avoid detailed components)
- Keep ground plane constant across scenarios
- Maintain consistent building heights
- Represent trees as simplified canopy objects
- One Revit file per scenario

---

### 6.2 Import to Autodesk Forma
- Create a Forma site using real address
- Import Revit massing
- Verify:
  - Orientation
  - Scale
  - Terrain alignment

⚠️ **Important:** Do not change simulation settings between scenarios.

---

## 7. Simulations Performed

### A. Sun Hours Analysis
<img width="1281" height="425" alt="image" src="https://github.com/user-attachments/assets/07b20c77-d0d0-4515-be04-7ffd5c7ed367" />

**Purpose:** Measure daylight tradeoffs caused by density.

**Run conditions:**
- Winter Solstice (Dec 21)
- Summer Solstice (Jul 21)
- Daytime window (e.g. 8:00–16:00)

**Recorded outputs:**
- % ground with ≥ 3 hours sun
- % facades with ≥ 3 hours sun
- % roofs with ≥ 3 hours sun

**Interpretation focus:**
- Backyard livability
- Passive solar access
- Roof usability for PV

---

### B. Microclimate / Heat Stress
<img width="1274" height="420" alt="image" src="https://github.com/user-attachments/assets/85fd81ac-d35b-42ce-9bc6-76ecff93d060" />

**Purpose:** Evaluate thermal comfort impacts of added density.

**Run condition:**
- July 21, 2 PM (peak summer heat)

**Metrics recorded:**
- % strong heat stress
- % moderate heat stress
- Spatial concentration of heat

**Key insight:**
> Heat stress changes were driven more by **tree canopy loss** than by density alone.

---

### C. Wind Comfort Analysis
<img width="1283" height="423" alt="image" src="https://github.com/user-attachments/assets/9824d9f3-5445-433d-a01b-8c03c8fb20ab" />

**Purpose:** Understand pedestrian-level comfort and ventilation.

**Run condition:**
- Prevailing **east wind**

**Outputs:**
- Comfort categories (sitting → uncomfortable)
- Wind stagnation vs channeling
- Block interior ventilation

**Key tradeoff:**
- Trees improve comfort but can reduce cooling airflow

---

### D. Solar Panel Potential
<img width="1285" height="434" alt="image" src="https://github.com/user-attachments/assets/da5dde2b-5b41-446e-be50-0ce2eb9514af" />

**Purpose:** Evaluate energy resilience benefits of added density.

**Metrics recorded:**
- Total roof surface area
- Panel placement area
- Estimated annual energy output (kWh)

**Finding:**
> Higher density increases **total solar capacity**, even if per-square-foot performance remains similar.

---

### E. Stormwater + Runoff (Interpretive Analysis)
While Forma does not directly model runoff volume, geometry-based conclusions were drawn:

**Observed impacts:**
- Increased roof area → increased runoff volume
- Reduced parking helps lower impervious surface per unit
- Tree loss reduces interception and evapotranspiration

**Mitigation strategies proposed:**
- Mandatory rainwater harvesting
- Cool / reflective roofs
- Green roofs
- Bioswales + green streets
- Permeable paving
- Tree replacement ratios

---

## 8. Writing Findings (Reusable Template)

For every analysis slide:

**Findings**
- Quantitative results (% or area)
- Spatial patterns

**Interpretation**
- Comfort impacts
- Environmental tradeoffs
- Policy relevance
- Equity implications

---

## 9. Key Results Summary

### Reynoldstown (Retrofit Model)
- ~230 new units via ADUs + small MF
- Minimal heat increase with canopy preservation
- Stormwater manageable with lot-scale mitigation
- Low displacement risk

### Vine City (Rebuild + TOD Model)
- 196–263 new units across scenarios
- Heat stress remains similar across densities
- Significant solar + housing gains
- Stormwater impacts require **district-scale solutions**

---

## 10. Resilience Toolkit (Recommended Requirements)

For missing-middle infill:
- Rainwater harvesting on all new roofs
- Cool or green roofs
- Bioswales + curbside green infrastructure
- Permeable paving
- Tree replacement (1–2 new trees per removal)

---

## 11. Future Extensions

- Quantitative stormwater modeling (SWMM / SCS-CN)
- Canopy sensitivity testing
- Neighborhood-to-neighborhood comparison toolkit
- Policy scenario testing (density bonuses tied to resilience)

---

## 12. Citation

This repository is based on the Independent Study submission:
**“Climate-Migration Readiness in Atlanta: Housing + Resilient Infrastructure”**  
Georgia Institute of Technology, 2025

---

## 13. For Future Students

If you are continuing this work:
- Keep **simulation settings constant**
- Always compare **Existing vs Proposal**
- Pair density increases with **required mitigation**
- Use simulations to support **policy arguments**, not just visuals


