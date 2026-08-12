# Project Triton
## Principal Prototype Geometry Analysis

---

## Document Control

| Field | Value |
|---|---|
| Project | Project Triton |
| Document ID | PT-AN-002 |
| Document Title | Principal Prototype Geometry Analysis |
| Version | 0.1 |
| Status | Draft |
| Owner | Robert Schneider |
| Created | 2026-08-11 |
| Last Updated | 2026-08-11 |
| Related Open Issue | OI-002 — Principal Prototype Geometry |
| Related Requirements | SR-005, SR-008, SR-010, SR-047, SR-049, SR-054, SR-055, SR-057, SR-062, SR-063, SR-066, SR-067 |
| Related Analysis | PT-AN-001 — RDT-80 Thrust Objective Analysis |
| Architecture Baseline | PT-SA-001 Version 1.0 / DR-002-v1.0 |

---

## Revision History

| Version | Date | Description |
|---|---|---|
| 0.1 | 2026-08-11 | Initial analysis structure established to resolve OI-002 and define the principal RDT-80 prototype geometry |

---

## 1. Purpose

This analysis establishes the technical basis for selecting the principal prototype geometry of the Project Triton RDT-80 rim-driven thruster.

The analysis is intended to resolve OI-002 sufficiently to define the system-level geometric parameters required for subsequent hydrodynamic, electromagnetic, structural, rotor-support, manufacturing, interface, and verification work.

The analysis shall evaluate the geometry as an integrated system rather than selecting dimensions independently within individual engineering disciplines.

The principal geometry decision shall consider, at minimum:

- nominal propulsor diameter;
- central flow-passage diameter;
- rotor radial thickness;
- stator radial thickness;
- annular rotor-to-stator clearance;
- duct internal and external dimensions;
- rotor axial length;
- stator axial length;
- overall thruster axial length;
- principal rotor-support clearances;
- mounting-envelope implications; and
- the geometric relationships among the propulsor, rotor, stator, duct, structural housing, and support system.

The analysis shall use the performance objective established by PT-AN-001 as a governing input:

**7.0 kgf / 68.6 N minimum continuous forward static thrust**

and:

**10.0 kgf / 98.1 N minimum peak forward static thrust**

The analysis shall compare, at minimum, nominal propulsor diameters of:

- **80 mm**;
- **90 mm**; and
- **100 mm**.

The purpose of this comparison is not to maximize propulsor diameter or minimize disk loading in isolation.

The selected geometry shall provide the best overall balance among:

- hydrodynamic performance;
- electromagnetic packaging;
- rotor-support feasibility;
- structural integrity;
- manufacturing practicality;
- prototype size and cost;
- testability;
- configuration control; and
- scalability.

Dimensions that cannot yet be established with a defensible technical basis shall remain explicitly open and shall be assigned to the applicable downstream analysis or controlled open issue rather than being selected arbitrarily.

Completion of this analysis shall provide the geometric basis required to proceed with detailed propulsor operating-point analysis and subsequent electrical and electromagnetic sizing.

---

## 2. Decision to Be Made

This analysis shall establish, or explicitly disposition to a controlled downstream decision where insufficient technical basis presently exists, the principal geometry of the initial RDT-80 prototype.

The analysis shall determine, at minimum:

1. The nominal propulsor diameter.
2. The nominal central flow-passage diameter.
3. The rotor inner and outer diameters.
4. The rotor radial thickness.
5. The stator inner and outer diameters.
6. The stator radial thickness.
7. The nominal rotor-to-stator electromagnetic clearance.
8. The nominal duct internal diameter.
9. The nominal duct external diameter.
10. The rotor axial length.
11. The stator axial length.
12. The principal duct axial length.
13. The approximate overall thruster axial length.
14. The principal rotor-support and structural clearances.
15. The geometric relationship among the propulsor, rotor, stator, duct, support elements, and structural housing.
16. The principal mounting-envelope dimensions required for subsequent prototype integration and test-fixture design.

The geometry decision shall also determine whether the current **RDT-80** designation should continue to represent:

- an approximately 80 mm nominal propulsor diameter;
- an exact 80 mm nominal propulsor diameter; or
- a historical project designation that does not constrain the selected final propulsor diameter.

The analysis shall compare at least:

- **80 mm** nominal propulsor diameter;
- **90 mm** nominal propulsor diameter; and
- **100 mm** nominal propulsor diameter.

Each candidate shall be evaluated as an integrated geometry rather than by propulsor diameter alone.

The selected geometry shall be judged against its ability to support the approved thrust objective of:

- **7.0 kgf / 68.6 N minimum continuous forward static thrust**; and
- **10.0 kgf / 98.1 N minimum peak forward static thrust**.

The geometry shall not be selected solely on the basis of minimum ideal hydrodynamic power.

The decision shall consider the coupled effects on:

- disk loading;
- required rotor speed;
- required torque;
- blade geometry;
- cavitation tendency;
- annular electromagnetic area;
- magnetic path dimensions;
- winding space;
- rotor mass;
- rotor inertia;
- rotor-support loading;
- structural stiffness;
- mechanical containment;
- allowable tolerances;
- material usage;
- manufacturing complexity;
- overall thruster size;
- prototype cost;
- test-fixture requirements; and
- scalability.

Where a dimension cannot yet be defensibly fixed, PT-AN-002 shall define an approved design range or identify the controlling downstream dependency rather than assign an arbitrary value.

The intended outcome of this analysis is a geometry definition sufficiently mature to support:

1. hydrodynamic propulsor analysis;
2. rotor-speed and torque estimation;
3. OI-003 electrical-envelope development;
4. OI-004 through OI-006 electromagnetic design;
5. rotor-support and structural development;
6. detailed CAD development; and
7. controlled prototype manufacturing planning.

---

## 3. Governing Inputs and Constraints

### 3.1 Governing Configuration Basis

The principal prototype geometry shall remain consistent with the approved system architecture:

**PT-SA-001 — System Architecture, Version 1.0**

approved through:

**DR-002 — System Architecture Review**

and configuration-controlled by:

**DR-002-v1.0**

PT-AN-002 shall not introduce a geometric feature that violates the approved rim-driven architecture without initiating a controlled architecture change.

The geometry shall therefore preserve the following fundamental characteristics:

- annular rim-driven rotor;
- direct electromagnetic torque transfer to the propulsor;
- no conventional central propulsion shaft;
- no through-hub drivetrain;
- no centrally mounted propulsion motor;
- unobstructed central propulsor flow passage except for the propulsor blades themselves and any subsequently approved hydrodynamic features;
- defined radial and axial rotor support;
- defined rotor retention and containment;
- configuration-controlled rotor-to-stator and rotor-to-structure clearances; and
- compatibility with controlled submerged prototype testing.

---

### 3.2 Governing Performance Input

The primary performance input is established by:

**PT-AN-001 — RDT-80 Thrust Objective Analysis**

The geometry shall support a credible engineering path to:

| Operating Condition | Required Forward Static Thrust |
|---|---:|
| Continuous | Not less than 7.0 kgf / 68.6 N |
| Peak | Not less than 10.0 kgf / 98.1 N |

The geometry analysis shall not assume that these thrust levels can be achieved at any arbitrary rotor speed, torque, voltage, current, or blade configuration.

Instead, the geometry shall provide sufficient design space for subsequent hydrodynamic and electromagnetic analysis to establish those operating parameters.

---

### 3.3 Governing System Requirements

The principal geometry decision shall remain consistent with the current controlled system requirements in:

**PT-REQ-001 — System Requirements, Version 0.2, Draft**

The requirements having the most direct effect on PT-AN-002 include:

| Requirement | Geometry Relevance |
|---|---|
| SR-005 | Requires preservation of the central propulsor flow passage without a conventional central shaft, shaft-support structure, or centrally mounted drive motor |
| SR-008 | Requires sufficient radial and axial clearance between rotating and stationary structure |
| SR-010 | Requires structural alignment and dimensional stability sufficient to maintain required rotor clearances |
| SR-054 | Establishes the 7.0 kgf / 68.6 N continuous forward static-thrust requirement |
| SR-055 | Establishes the 10.0 kgf / 98.1 N peak forward static-thrust requirement |
| SR-057 | Requires configuration-controlled principal propulsor and duct dimensions |
| SR-062 | Requires configuration control of propulsor blade geometry before formal thrust verification |
| SR-063 | Requires electromagnetic torque sufficient for operation throughout the approved envelope |
| SR-066 | Requires maintenance of required rotor-to-stator electromagnetic geometry and clearance |
| SR-067 | Requires positive retention of electromagnetic-drive elements |
| SR-047 | Requires critical dimensions, fits, clearances, and alignment features to be manufacturable and inspectable |
| SR-049 | Requires manufacturing and assembly tolerances to preserve critical geometric relationships |

PT-AN-002 shall provide geometric inputs to these requirements but shall not prematurely replace downstream requirements with unsupported numerical dimensions.

---

### 3.4 Relevant Open Issues

OI-002 is strongly coupled to several other unresolved Project Triton decisions.

The following open issues shall therefore be treated as governing dependencies or constraints:

| Open Issue | Relationship to Geometry |
|---|---|
| OI-001 — Thrust Objective | Provides the required continuous and peak thrust operating points |
| OI-002 — Principal Prototype Geometry | Primary issue addressed by PT-AN-002 |
| OI-003 — Operating Voltage and Power Range | Geometry affects available electromagnetic area, torque production, losses, and required electrical input |
| OI-004 — Electromagnetic Topology | May constrain stator and rotor radial/axial dimensions |
| OI-005 — Stator and Winding Geometry | Directly affects stator thickness, axial length, and winding space |
| OI-006 — Rotor Magnetic Circuit / Magnetic-Element Arrangement | Directly affects rotor radial thickness and axial length |
| OI-007 — Rotor Electromagnetic-Element Retention | May require additional rotor radial or axial material |
| OI-008 — Radial Support | Constrains support geometry and radial clearances |
| OI-009 — Axial Support and Thrust Reaction | Constrains axial packaging and load paths |
| OI-010 — Backup Containment | May increase overall radial or axial envelope |
| OI-011 — Operating Clearance | Controls rotor-to-stator and rotor-to-structure gap requirements |
| OI-012 — Materials and Structural Selection | Influences minimum wall thickness, stiffness, and containment dimensions |
| OI-013 — Environmental Protection | May require coatings, encapsulation, barriers, or sealing thickness |
| OI-014 — Thermal Management | Geometry controls conductive and convective heat-transfer paths |
| OI-015 — Propulsor Geometry | Controls blade geometry, solidity, duct interaction, and hydrodynamic operating point |
| OI-016 — Instrumentation and Sensing | May require sensor accommodation and access |
| OI-019 — Test Interfaces and Setup | Constrains prototype mounting and measurement geometry |
| OI-020 — Manufacturing and Tolerances | Determines practical dimensional precision and inspectability |
| OI-023 — Test Envelope and Test Authority | Limits which geometric configurations may be operated at increasing energy levels |
| OI-024 — Configuration and Service Traceability | Requires geometric configuration changes to remain identifiable and traceable |

PT-AN-002 shall resolve only those geometric decisions for which sufficient evidence exists.

Other dimensions shall remain ranges or controlled downstream decisions where appropriate.

---

### 3.5 Governing Architecture Assumptions

The geometry analysis shall remain compatible with the applicable approved architecture assumptions, including:

- **AS-001** — the prototype shall remain compatible with practical development and fabrication resources;
- **AS-002** — the primary propulsion concept is a direct annular rim-driven architecture;
- **AS-003** — thermal performance must be established rather than assumed;
- **AS-004** — the rotor requires deliberate radial and axial support;
- **AS-005** — rotor clearances and alignment are critical design parameters;
- **AS-006** — controlled electrical and motor-control architecture is required;
- **AS-007** — development shall occur initially in a controlled test environment;
- **AS-008** — submerged environmental exposure must be addressed;
- **AS-009** — instrumentation and prototype-development interfaces are required;
- **AS-010** — the operating envelope shall be expanded progressively;
- **AS-011** — configuration control and serviceability shall be preserved; and
- **AS-012** — the prototype should preserve a credible path to future scaling.

Where a geometry decision depends critically on one of these assumptions, the dependency shall be identified explicitly.

---

### 3.6 Relevant Technical Risks

The geometry trade shall consider its effect on the current technical-risk set, particularly:

| Risk | Geometry Relationship |
|---|---|
| RK-001 — Electromagnetic feasibility / performance | Available annular motor dimensions directly influence achievable torque and efficiency |
| RK-002 — Rotor-support positioning | Rotor dimensions affect support span, stiffness, alignment, and load |
| RK-003 — Clearance and tolerance | Radial and axial packaging determine sensitivity to manufacturing and deflection |
| RK-004 — Rotor electromagnetic-element retention | Rotor dimensions affect centrifugal and retention stresses |
| RK-005 — Thermal performance | Radial and axial geometry determine loss density and heat-transfer area |
| RK-006 — Corrosion / water ingress | Geometry affects barriers, material interfaces, coatings, and protected volumes |
| RK-007 — Hydrodynamic / thrust / cavitation performance | Propulsor and duct geometry directly control loading and performance |
| RK-008 — Structural deformation / alignment | Housing dimensions and section properties determine stiffness and alignment |
| RK-009 — Manufacturing feasibility | Geometry affects process capability, tolerances, inspection, and prototype cost |
| RK-010 — Instrumentation | Available packaging space affects sensor placement and measurement capability |
| RK-012 — Test-fixture and test-environment feasibility | Overall dimensions affect mounting, water-test infrastructure, and load measurement |
| RK-015 — Prototype materials / process uncertainty | Larger or thinner geometry may amplify uncertainty in prototype material properties |
| RK-016 — Damaging failure during powered test | Rotor size, stored rotational energy, loading, and containment geometry affect test hazard severity |

The selected geometry should reduce total system risk rather than merely optimize a single subsystem.

---

### 3.7 Current Geometric Analysis Range

PT-AN-001 established the following nominal propulsor-diameter range as the principal starting point for OI-002:

**80–100 mm**

The required comparison points are:

- **80 mm** — baseline and closest architecture-comparable benchmark;
- **90 mm** — intermediate alternative;
- **100 mm** — larger lower-disk-loading alternative.

The 70 mm, 110 mm, and 120 mm cases evaluated in PT-AN-001 remain useful sensitivity references but are not currently primary candidate geometries.

They may be reconsidered if the integrated geometry trade demonstrates that none of the 80–100 mm candidates provides a satisfactory system solution.

---

### 3.8 Preliminary Hydrodynamic Inputs

For an ideal actuator disk at the selected Candidate B thrust objective, PT-AN-001 established:

| Nominal Diameter | 7 kgf Disk Loading | 7 kgf Ideal Power | 10 kgf Disk Loading | 10 kgf Ideal Power |
|---|---:|---:|---:|---:|
| 80 mm | 13.66 kPa | 180 W | 19.51 kPa | 307 W |
| 90 mm | 10.79 kPa | 160 W | 15.42 kPa | 273 W |
| 100 mm | 8.74 kPa | 144 W | 12.49 kPa | 245 W |

These values are ideal hydrodynamic lower bounds only.

They shall be used for comparative geometry screening and shall not be interpreted as predicted propulsor mechanical power or electrical input power.

---

### 3.9 Preliminary Electrical-Power Input

PT-AN-001 established a current first-order planning basis of approximately:

- **0.6 kW continuous electrical input**; and
- **1.0 kW peak electrical input**

for the preferred thrust objective.

A preliminary component-screening level of approximately:

**1.2 kW peak electrical input**

is retained until OI-003 is resolved.

These values are planning inputs only.

PT-AN-002 shall consider whether each candidate geometry provides credible physical space and thermal area for a motor capable of operating in this approximate class, but shall not establish final voltage, current, winding, or controller requirements.

---

### 3.10 Manufacturing and Prototype Constraints

The geometry shall remain compatible with practical prototype fabrication and inspection.

At this stage, the analysis shall favor geometry that:

- can be modeled and dimensioned unambiguously in CAD;
- can be fabricated using accessible machining, additive-manufacturing, composite, or hybrid processes as appropriate;
- permits measurement of critical dimensions;
- permits controlled assembly and disassembly;
- provides practical access to rotor-support and electromagnetic elements;
- permits configuration-controlled replacement of development components;
- avoids unnecessarily extreme wall thicknesses or unsupported slender features;
- avoids tolerances substantially tighter than demonstrated manufacturing capability unless technically necessary;
- supports practical instrumentation;
- supports restrained submerged testing; and
- does not require production-grade manufacturing processes merely to demonstrate the prototype architecture.

No specific manufacturing process shall be made mandatory by PT-AN-002 unless the geometry decision itself requires that process.

---

### 3.11 Constraint Interpretation

The governing inputs do not imply that the smallest, largest, lightest, lowest-power, or simplest geometry is automatically preferred.

The principal geometry shall instead be selected as an integrated engineering compromise.

In particular:

- increasing propulsor diameter improves ideal hydrodynamic loading but increases system size;
- increasing annular motor dimensions may improve electromagnetic capability but increases rotor mass and structural demands;
- reducing clearances may improve electromagnetic performance but increases manufacturing and contact risk;
- increasing structural thickness may improve stiffness and containment but increases mass, frontal area, and material demand;
- increasing axial length may improve electromagnetic or structural packaging but may degrade overall compactness and hydrodynamic integration.

The geometry trade shall therefore evaluate coupled system effects before any principal dimension is selected.

---

## 4. Geometry Parameters to Be Established

### 4.1 Purpose of the Geometry Definition

The purpose of the principal geometry definition is to establish a common dimensional framework for subsequent hydrodynamic, electromagnetic, structural, rotor-support, manufacturing, CAD, and verification work.

Dimensions shall be defined using consistent terminology so that a value established in one discipline is not interpreted differently by another.

PT-AN-002 shall distinguish among:

1. **Primary geometry decisions** — dimensions that should be selected or bounded by this analysis.
2. **Dependent geometry parameters** — dimensions that can be estimated or assigned a preliminary design range after a primary geometry is selected.
3. **Downstream detailed geometry** — dimensions that require additional hydrodynamic, electromagnetic, structural, support, thermal, or manufacturing analysis before they can be fixed.

A dimension shall not be assigned a nominal value merely to make the geometry appear complete.

---

### 4.2 Geometry Reference Convention

For purposes of PT-AN-002, the thruster shall be represented by a nominal cylindrical coordinate system centered on the axis of propulsor rotation.

The following directions shall be used:

- **radial** — perpendicular to the rotational axis;
- **axial** — parallel to the rotational axis;
- **circumferential** — around the rotational axis.

Unless explicitly stated otherwise:

- diameter dimensions refer to nominal diameters centered on the rotational axis;
- radial thickness is one-half the difference between corresponding outer and inner diameters;
- axial dimensions are measured parallel to the rotational axis;
- clearances represent the minimum intended separation between applicable rotating and stationary features before tolerance, deformation, wear, or thermal effects are applied.

The final CAD model shall use the same dimensional definitions established by this analysis.

---

### 4.3 Principal Geometry Parameter Set

The following parameter set shall be used for the principal prototype geometry.

| Symbol | Parameter | Definition | Initial Decision Status |
|---|---|---|---|
| D_P | Nominal propulsor diameter | Nominal diameter of the primary rotating propulsor swept envelope used for hydrodynamic sizing | Primary variable — evaluate 80, 90, and 100 mm |
| D_FP | Central flow-passage diameter | Minimum nominal diameter of the principal central passage through the stationary thruster structure available for propulsor flow | To be established or bounded |
| D_RI | Rotor inner diameter | Nominal inside diameter of the annular rotating rotor structure | To be derived from propulsor and attachment geometry |
| D_RO | Rotor outer diameter | Nominal outside diameter of the annular rotating rotor structure | To be established or bounded |
| t_R | Rotor radial thickness | Nominal radial build of the annular rotor, equal to approximately (D_RO − D_RI) / 2 | Dependent on electromagnetic, retention, and structural requirements |
| D_SI | Stator inner diameter | Nominal inside diameter of the stationary electromagnetic envelope where applicable | Topology dependent |
| D_SO | Stator outer diameter | Nominal outside diameter of the stationary electromagnetic envelope | To be established or bounded |
| t_S | Stator radial thickness | Nominal radial build of the stationary electromagnetic region where applicable | Topology dependent |
| g_EM | Electromagnetic clearance | Nominal physical separation between interacting rotating and stationary electromagnetic structures | Downstream value controlled by OI-004, OI-005, OI-006, and OI-011 |
| D_DI | Duct internal diameter | Nominal inside diameter of the hydrodynamic duct at the applicable propulsor plane | To be established or bounded |
| D_DO | Duct external diameter | Nominal maximum outside diameter of the duct / principal housing envelope | To be established or bounded |
| L_R | Rotor axial length | Nominal axial length of the annular rotating structure | Dependent on electromagnetic and structural design |
| L_S | Stator axial length | Nominal axial length of the principal stationary electromagnetic structure | Topology dependent |
| L_D | Duct axial length | Nominal axial extent of the principal hydrodynamic duct | Dependent on hydrodynamic analysis |
| L_SYS | Overall thruster axial length | Approximate maximum axial envelope of the integrated thruster excluding external cable or test-fixture extensions | To be established or bounded |
| C_R | Radial operating clearance | Minimum intended radial separation between rotating and non-electromagnetic stationary structure | Controlled principally by OI-008, OI-011, OI-020 |
| C_A | Axial operating clearance | Minimum intended axial separation between rotating and stationary structure where relative motion could cause contact | Controlled principally by OI-009, OI-011, OI-020 |
| E_MNT | Mounting envelope | Principal radial and axial space required for attachment of the thruster to an approved mounting structure or test fixture | To be established after primary geometry selection |

Symbols introduced here are analysis conventions for PT-AN-002 and do not become controlled interface identifiers solely by appearing in this document.

---

### 4.4 Propulsor Diameter Definition

The nominal propulsor diameter, **D_P**, is the primary independent geometry variable for the initial trade.

For this analysis, D_P represents the nominal diameter associated with the rotating propulsor swept area used for first-order hydrodynamic comparison.

The required candidate values are:

- **D_P = 80 mm**
- **D_P = 90 mm**
- **D_P = 100 mm**

The final detailed blade geometry may result in minor differences between the nominal hydrodynamic diameter and specific manufactured blade or rotor features.

Any such difference shall be documented explicitly.

D_P shall not be interpreted as fixing:

- blade count;
- blade chord;
- blade pitch;
- blade twist;
- blade section;
- blade inner termination;
- rotor attachment geometry; or
- duct clearance.

Those parameters remain principally associated with OI-015.

---

### 4.5 Central Flow-Passage Definition

The central flow passage required by the architecture refers to the principal axial flow path through the thruster that is free of a conventional central:

- drive shaft;
- shaft-support structure;
- gearbox;
- centrally mounted propulsion motor; or
- equivalent stationary propulsion-drive obstruction.

This architectural requirement does **not** mean that the flow passage must be free of the rotating propulsor blades.

Accordingly, **D_FP** shall describe the minimum principal stationary bore or flow-passage envelope through which the propulsor operates.

This distinction is important because the Project Triton architecture is intended to eliminate the conventional central drivetrain obstruction, not the propulsor itself.

The relationship among D_FP, D_P, D_RI, blade geometry, and duct geometry shall be established during the integrated geometry and hydrodynamic development.

---

### 4.6 Rotor Geometry

The annular rotor geometry shall ultimately provide sufficient space and structural capability for:

- direct attachment or integration of the propulsor;
- electromagnetic torque production;
- rotor magnetic elements;
- magnetic-element retention;
- structural load transfer;
- radial and axial support interfaces;
- required operating clearances;
- environmental protection where applicable; and
- containment-related features where allocated to the rotor.

The principal rotor dimensions are:

- **D_RI**
- **D_RO**
- **t_R**
- **L_R**

The rotor inner diameter is expected to be closely coupled to the propulsor outer swept envelope, but PT-AN-002 shall not assume that:

**D_RI = D_P**

exactly.

Possible geometric allowances may be required for:

- blade attachment;
- rotor liners;
- structural material;
- hydrodynamic transitions;
- coatings;
- encapsulation;
- manufacturing tolerances; or
- other development features.

The exact relationship shall therefore be established deliberately rather than implicitly.

---

### 4.7 Stator and Electromagnetic Envelope

The principal stationary electromagnetic geometry must provide sufficient physical volume for the eventual motor topology while preserving the annular propulsion architecture.

Because OI-004 — Electromagnetic Topology — remains open, PT-AN-002 shall not assume that all electromagnetic designs require the same radial and axial geometry.

For example, the significance of:

- D_SI;
- D_SO;
- t_S;
- L_S; and
- g_EM

may differ depending on whether the eventual topology primarily uses radial-flux, axial-flux, transverse-flux, or another approved annular electromagnetic arrangement.

PT-AN-002 may establish an **electromagnetic packaging envelope** without fixing the detailed motor geometry.

Where a candidate propulsor diameter provides substantially more or less circumferential, radial, or axial electromagnetic packaging space, that effect shall be considered in the geometry trade.

---

### 4.8 Duct and Housing Geometry

The hydrodynamic duct and structural housing may perform overlapping or integrated functions, but they shall not be assumed to be geometrically identical until the design is sufficiently mature.

The principal duct parameters are:

- **D_DI**
- **D_DO**
- **L_D**

The geometry shall provide sufficient space for:

- propulsor operation;
- hydrodynamic inlet and outlet treatment;
- rotor and stator packaging;
- structural load paths;
- environmental protection;
- rotor containment;
- support interfaces;
- instrumentation where required; and
- manufacturing features.

The final duct profile shall be established by OI-015 and subsequent hydrodynamic analysis.

PT-AN-002 shall initially establish only the principal dimensional envelope required to compare candidate system geometries.

---

### 4.9 Radial Packaging Relationship

For a conventional concentric radial packaging concept, the principal radial dimensions may be represented conceptually as:

**central flow region → propulsor / rotor → electromagnetic region → structural / duct envelope**

This representation is useful for system packaging but shall not be interpreted as approval of a specific electromagnetic topology.

A candidate geometry shall be rejected or reconsidered if the nominal propulsor diameter leaves insufficient radial or axial space for a credible:

- rotor structure;
- electromagnetic drive;
- rotor support;
- containment feature;
- housing structure; or
- manufacturing tolerance scheme.

Conversely, excessive radial build shall be penalized if it produces disproportionate:

- frontal area;
- mass;
- material usage;
- rotor inertia;
- test-fixture demand; or
- prototype manufacturing complexity.

---

### 4.10 Axial Packaging Relationship

The principal axial geometry must accommodate, as applicable:

- propulsor blade axial sweep;
- rotor structural width;
- electromagnetic active length;
- radial-support elements;
- axial-support / thrust-reaction elements;
- containment features;
- hydrodynamic inlet and outlet transitions;
- structural load-transfer features;
- instrumentation;
- assembly features; and
- maintenance access.

PT-AN-002 shall distinguish between:

1. **active electromagnetic axial length**;
2. **rotor structural axial length**;
3. **hydrodynamic duct axial length**; and
4. **overall system axial envelope**.

These dimensions need not be equal.

The geometry trade shall avoid increasing axial length solely to simplify one subsystem if the resulting overall package becomes disproportionately large.

---

### 4.11 Clearance Definition

PT-AN-002 shall distinguish among three general classes of clearance:

1. **Electromagnetic clearance** — physical separation required between interacting rotating and stationary electromagnetic structures.
2. **Radial mechanical clearance** — separation required to prevent rotating-to-stationary contact under manufacturing variation, support motion, structural deformation, thermal expansion, and dynamic loading.
3. **Axial mechanical clearance** — separation required to prevent unintended axial contact during normal and approved transient operation.

The final numerical values for these clearances shall not be selected until the project has sufficient information regarding:

- rotor-support architecture;
- electromagnetic topology;
- material selection;
- manufacturing capability;
- tolerance stack-up;
- structural deformation;
- thermal expansion;
- rotor dynamics; and
- allowable contact risk.

Accordingly, PT-AN-002 may reserve physical design allowance for these clearances without prematurely establishing their final numerical values.

---

### 4.12 Geometry Decision Classes

For PT-AN-002, geometry parameters shall be classified as follows:

| Decision Class | Meaning | Examples |
|---|---|---|
| Class A — Select in PT-AN-002 | Sufficient basis is expected to select a nominal value | Nominal propulsor diameter |
| Class B — Bound in PT-AN-002 | A useful dimensional range or packaging allowance can be established, but the final value depends on downstream work | Overall OD packaging-study range |
| Class C — Transfer downstream | Insufficient basis exists until another technical decision is resolved | Final electromagnetic gap, detailed blade dimensions, bearing/support dimensions |
| Class D — Configuration dependent | Value may intentionally differ among prototype configurations and shall be controlled rather than permanently fixed at this stage | Development duct profiles, instrumentation provisions, replaceable rotor or propulsor features |

Every principal dimension addressed by PT-AN-002 shall ultimately receive one of these dispositions.

---

### 4.13 Minimum Geometry Output of PT-AN-002

Before PT-AN-002 can be considered sufficiently mature to support downstream sizing, it shall establish at least:

- one recommended nominal propulsor diameter;
- a defined relationship between the propulsor and annular rotor;
- a preliminary system-level radial packaging objective where defensible;
- a defined central flow-passage interpretation;
- identified physical allowances for electromagnetic-drive development;
- identified allowances for rotor support, containment, and operating clearances;
- identified mounting-envelope implications;
- explicit classification of unresolved geometry parameters as Class B, Class C, or Class D as applicable; and
- explicit downstream ownership of geometry values that cannot yet be established defensibly.

Where sufficient evidence exists, PT-AN-002 may establish a preliminary dimensional range.

Where sufficient evidence does not exist, the analysis shall instead identify the applicable controlling dependency and preserve adequate placeholder geometry for subsequent development.

The resulting geometry shall be sufficiently defined to create a controlled **system-level CAD envelope** that distinguishes among:

1. selected dimensions;
2. preliminary packaging objectives; and
3. unresolved placeholder geometry.

PT-AN-002 need not contain final blade, winding, magnet, bearing, support, clearance, seal, or manufacturing-detail geometry before downstream engineering proceeds.

---

## 5. Candidate Propulsor Diameters

### 5.1 Purpose of the Candidate Comparison

The first principal geometry decision is selection of the nominal propulsor diameter, **D_P**.

PT-AN-001 identified the most technically relevant initial range as:

**80–100 mm nominal propulsor diameter**

and established three primary comparison cases:

- **Candidate Geometry G80 — 80 mm**
- **Candidate Geometry G90 — 90 mm**
- **Candidate Geometry G100 — 100 mm**

These candidate designations apply only to the nominal propulsor diameter comparison.

They do not yet define the complete rotor, stator, duct, housing, support, or mounting geometry.

The purpose of Section 5 is to establish the physical and analytical significance of each diameter before evaluating discipline-specific consequences in Sections 6 through 9.

---

### 5.2 Common Performance Basis

All three candidate diameters shall be evaluated against the same required performance objective:

| Operating Condition | Required Forward Static Thrust |
|---|---:|
| Continuous | 7.0 kgf / 68.6 N minimum |
| Peak | 10.0 kgf / 98.1 N minimum |

The candidate comparison shall therefore evaluate how changing diameter affects the engineering difficulty of producing the same required thrust.

A larger candidate shall not receive credit merely because it could potentially produce more absolute thrust.

Likewise, a smaller candidate shall not receive credit merely because it produces a more compact package.

Each candidate shall be judged by the integrated system required to satisfy the same Project Triton performance objective.

---

### 5.3 Common First-Order Fluid Basis

For consistency with PT-AN-001, the preliminary comparison shall use:

**ρ = 997 kg/m³**

for freshwater density.

The reference static-thrust condition is an initially quiescent fluid with no imposed vehicle advance velocity.

The ideal actuator-disk relationships are:

**A = πD² / 4**

**Disk Loading = T / A**

**vᵢ = √[T / (2ρA)]**

**Pᵢ = T vᵢ**

At fixed required thrust:

**Disk Loading ∝ 1 / D²**

and:

**Pᵢ ∝ 1 / D**

These relationships are used for comparative screening only.

They do not establish actual blade performance, rotor speed, torque, cavitation margin, or electrical input power.

---

### 5.4 Candidate G80 — 80 mm Propulsor

Candidate G80 uses:

**D_P = 80 mm**

This is the current reference geometry and the diameter most directly associated with the historical RDT-80 designation.

The ideal circular disk area is approximately:

**A = 0.00503 m²**

PT-AN-001 established the following first-order performance values:

| Operating Point | Value |
|---|---:|
| Continuous thrust | 7.0 kgf / 68.6 N |
| Continuous disk loading | approximately 13.66 kPa |
| Continuous ideal induced power | approximately 180 W |
| Peak thrust | 10.0 kgf / 98.1 N |
| Peak disk loading | approximately 19.51 kPa |
| Peak ideal induced power | approximately 307 W |

#### G80 Advantages

Candidate G80 provides the strongest direct comparison with the closest architecture-comparable benchmark identified in PT-AN-001.

Potential advantages include:

- closest continuity with the existing RDT-80 concept;
- smallest candidate hydrodynamic diameter;
- smallest candidate frontal-area contribution from the propulsor scale;
- potentially lower material usage;
- potentially lower rotor mass and rotational inertia;
- smaller test article;
- smaller test-fixture and water-test envelope;
- potentially lower prototype fabrication cost;
- direct comparison with existing 80 mm-class rim-driven performance data.

#### G80 Disadvantages

Relative to G90 and G100, Candidate G80 has:

- the highest disk loading;
- the highest ideal induced-power requirement;
- potentially higher blade loading;
- potentially greater cavitation sensitivity;
- less circumference available for electromagnetic torque production;
- less radial and circumferential packaging freedom;
- potentially greater required torque density or rotational speed;
- potentially tighter competition for rotor, stator, support, and structural packaging.

Candidate G80 is therefore the most compact option but provides the least geometric margin for meeting the required thrust objective.

---

### 5.5 Candidate G90 — 90 mm Propulsor

Candidate G90 uses:

**D_P = 90 mm**

The ideal circular disk area is approximately:

**A = 0.00636 m²**

Relative to G80, this represents approximately:

- **12.5% greater diameter**; and
- **26.6% greater disk area**.

PT-AN-001 established:

| Operating Point | Value |
|---|---:|
| Continuous thrust | 7.0 kgf / 68.6 N |
| Continuous disk loading | approximately 10.79 kPa |
| Continuous ideal induced power | approximately 160 W |
| Peak thrust | 10.0 kgf / 98.1 N |
| Peak disk loading | approximately 15.42 kPa |
| Peak ideal induced power | approximately 273 W |

Relative to G80, G90 provides approximately:

- **21% lower disk loading** at fixed thrust; and
- **11% lower ideal induced power** at fixed thrust.

#### G90 Advantages

Candidate G90 may provide an attractive intermediate system compromise.

Potential advantages include:

- meaningful reduction in hydrodynamic loading;
- moderate reduction in ideal power requirement;
- increased rotor circumference;
- increased available electromagnetic interaction length around the annulus;
- potentially reduced required torque density;
- increased space for rotor magnetic elements and retention features;
- increased packaging margin for structural and rotor-support elements;
- only a moderate increase in overall nominal diameter relative to G80.

G90 may therefore provide materially greater system-design margin without moving the prototype into a substantially larger physical class.

#### G90 Disadvantages

Relative to G80, Candidate G90 may increase:

- rotor circumference;
- rotor material usage;
- magnet quantity;
- winding or stator material requirement;
- rotor mass;
- rotational inertia;
- housing size;
- duct frontal area;
- test-fixture size;
- manufacturing time and cost.

Candidate G90 also loses exact nominal continuity with the RDT-80 designation if that designation is interpreted literally.

That naming consideration shall not override technical merit.

---

### 5.6 Candidate G100 — 100 mm Propulsor

Candidate G100 uses:

**D_P = 100 mm**

The ideal circular disk area is approximately:

**A = 0.00785 m²**

Relative to G80, this represents approximately:

- **25% greater diameter**; and
- **56% greater disk area**.

PT-AN-001 established:

| Operating Point | Value |
|---|---:|
| Continuous thrust | 7.0 kgf / 68.6 N |
| Continuous disk loading | approximately 8.74 kPa |
| Continuous ideal induced power | approximately 144 W |
| Peak thrust | 10.0 kgf / 98.1 N |
| Peak disk loading | approximately 12.49 kPa |
| Peak ideal induced power | approximately 245 W |

Relative to G80, G100 provides approximately:

- **36% lower disk loading** at fixed thrust; and
- **20% lower ideal induced power** at fixed thrust.

#### G100 Advantages

Candidate G100 provides the greatest hydrodynamic margin of the three primary candidates.

Potential advantages include:

- lowest disk loading;
- lowest ideal induced-power requirement;
- potentially lower blade loading;
- potentially improved cavitation margin;
- greatest rotor circumference;
- greatest available annular electromagnetic interaction length;
- potentially lower required electromagnetic torque density;
- greater physical space for magnetic-element retention;
- greater packaging space for rotor-support features;
- potentially improved structural design flexibility if adequate section depth is available.

G100 may permit the required 7.0/10.0 kgf performance to be achieved at a less aggressive hydrodynamic and electromagnetic operating point.

#### G100 Disadvantages

Candidate G100 creates the largest system-scale penalties among the primary candidates.

Potential disadvantages include:

- largest overall radial package;
- greater duct and housing frontal area;
- increased rotor circumference and material usage;
- potentially greater magnet and winding material quantity;
- increased rotor mass;
- increased polar moment of inertia;
- potentially greater stored rotational energy at a given RPM;
- increased containment demand;
- larger test article;
- larger test-fixture envelope;
- increased fabrication time and cost;
- greater departure from the original approximately 80 mm-class concept.

G100 therefore provides the greatest performance margin but may reduce the compactness and development simplicity that make the RDT-80 concept attractive.

---

### 5.7 First-Order Candidate Comparison

The primary first-order comparison is:

| Parameter | G80 | G90 | G100 |
|---|---:|---:|---:|
| Nominal propulsor diameter | 80 mm | 90 mm | 100 mm |
| Diameter relative to G80 | 1.000 | 1.125 | 1.250 |
| Ideal disk area | approximately 0.00503 m² | approximately 0.00636 m² | approximately 0.00785 m² |
| Area relative to G80 | 1.000 | 1.266 | 1.563 |
| 7 kgf disk loading | 13.66 kPa | 10.79 kPa | 8.74 kPa |
| 7 kgf ideal power | 180 W | 160 W | 144 W |
| 10 kgf disk loading | 19.51 kPa | 15.42 kPa | 12.49 kPa |
| 10 kgf ideal power | 307 W | 273 W | 245 W |
| Relative disk loading | 1.000 | 0.790 | 0.640 |
| Relative ideal induced power | 1.000 | 0.889 | 0.800 |

The relationship is monotonic:

- larger diameter reduces disk loading;
- larger diameter reduces ideal induced power;
- larger diameter increases physical system size.

The geometry decision must therefore determine where additional hydrodynamic and electromagnetic margin ceases to justify additional physical size, mass, material, manufacturing demand, and test burden.

---

### 5.8 Circumference Effect

An annular rim-driven motor differs from a conventional centrally driven propulsor because increasing diameter also increases the available rotor circumference.

Nominal circumference is:

**C = πD**

For the three candidates:

| Candidate | Nominal Propulsor Diameter | Nominal Circumference |
|---|---:|---:|
| G80 | 80 mm | approximately 251 mm |
| G90 | 90 mm | approximately 283 mm |
| G100 | 100 mm | approximately 314 mm |

Relative to G80:

- G90 provides approximately **12.5% greater circumference**;
- G100 provides approximately **25% greater circumference**.

This additional circumference may provide increased opportunity for:

- electromagnetic pole placement;
- active conductor length;
- magnetic-element area;
- distributed torque production;
- structural attachment;
- rotor support features.

However, increased circumference also increases:

- rotor material;
- magnetic-element count or size;
- structural path length;
- manufacturing effort; and
- potential dimensional runout accumulation.

The electromagnetic benefit therefore requires explicit evaluation rather than assuming that greater circumference is automatically advantageous.

---

### 5.9 Rotor Peripheral Speed Consideration

For a given rotational speed, rotor peripheral speed is proportional to diameter:

**V_tip = πDN / 60**

where:

- **V_tip** = peripheral speed;
- **D** = applicable rotating diameter;
- **N** = rotational speed in RPM.

Accordingly, at identical RPM:

- G90 has approximately 12.5% greater peripheral speed than G80;
- G100 has approximately 25% greater peripheral speed than G80.

Higher peripheral speed may affect:

- propulsor blade-tip velocity;
- cavitation;
- rotor magnetic-element retention;
- centrifugal stress;
- rotor-support behavior;
- hydrodynamic drag;
- seal or barrier design where applicable.

However, a larger propulsor may achieve the required thrust at a lower rotational speed.

Therefore, PT-AN-002 shall not compare centrifugal or cavitation effects solely at equal RPM.

Final comparison requires the operating RPM derived from subsequent hydrodynamic analysis.

---

### 5.10 Rotor Inertia Consideration

Increasing nominal diameter will generally increase rotor polar moment of inertia if material density, section proportions, and axial dimensions remain comparable.

The actual inertia relationship cannot yet be calculated because:

- rotor radial build is unresolved;
- rotor axial length is unresolved;
- electromagnetic topology is unresolved;
- magnetic-element arrangement is unresolved;
- material selection is unresolved.

Nevertheless, candidate evaluation shall recognize that increased rotor diameter may increase:

- startup energy;
- stopping energy;
- transient torque demand;
- emergency-stop challenge;
- stored kinetic energy;
- containment consequence;
- bearing or support transient loads.

This effect may partially offset the hydrodynamic and electromagnetic advantages of increased diameter.

---

### 5.11 Frontal-Area Consideration

The nominal propulsor disk area is not the same as the final external frontal area of the complete thruster.

The final external frontal area will depend upon:

- rotor radial build;
- stator radial build;
- electromagnetic topology;
- structural housing thickness;
- duct geometry;
- support structure;
- containment;
- environmental barriers.

Nevertheless, increasing D_P creates upward pressure on the final system outside diameter.

Accordingly, G100 shall not be assumed acceptable solely because its hydrodynamic disk loading is lowest.

The complete outside-diameter penalty shall be evaluated in later sections.

---

### 5.12 Candidate Naming Interpretation

The candidate designation shall be independent of the final project naming convention.

For analysis:

- **G80** means nominal D_P = 80 mm;
- **G90** means nominal D_P = 90 mm;
- **G100** means nominal D_P = 100 mm.

If G90 or G100 is ultimately selected, Project Triton may either:

1. retain **RDT-80** as a historical development designation; or
2. adopt a revised configuration designation through configuration control.

The geometry shall not be intentionally degraded to preserve a legacy name.

---

### 5.13 Initial Candidate Screening

No candidate is eliminated at this stage.

The preliminary interpretation is:

| Candidate | Preliminary Strength | Preliminary Concern |
|---|---|---|
| G80 | Compactness, benchmark continuity, smallest prototype envelope | Highest disk loading and least packaging margin |
| G90 | Balanced increase in hydrodynamic and electromagnetic margin for moderate size increase | Moderate increase in size, material, and inertia |
| G100 | Greatest hydrodynamic and annular packaging margin | Largest system envelope, material demand, inertia, and test burden |

At this stage:

**G80 remains the baseline candidate.**

**G90 is the leading intermediate alternative.**

**G100 remains the upper end of the primary candidate range.**

No preferred geometry is selected in Section 5.

The candidates shall next be evaluated for their hydrodynamic consequences in Section 6 before any integrated geometry recommendation is made.

---

## 6. Hydrodynamic Geometry Effects

### 6.1 Purpose

This section evaluates how the three candidate propulsor diameters affect the first-order hydrodynamic burden associated with the required RDT-80 thrust objective.

The comparison shall use the same required performance basis for all candidates:

- **7.0 kgf / 68.6 N minimum continuous forward static thrust**; and
- **10.0 kgf / 98.1 N minimum peak forward static thrust**.

The purpose is not to establish final propeller geometry or predicted thruster performance.

Instead, the analysis shall identify how candidate diameter influences:

- disk loading;
- induced velocity;
- ideal induced power;
- blade-loading tendency;
- cavitation tendency;
- required propulsor aggressiveness;
- duct-development sensitivity;
- flow-field intensity; and
- the difficulty of achieving the required thrust efficiently and repeatably.

Detailed blade design remains controlled principally by OI-015.

---

### 6.2 First-Order Hydrodynamic Comparison

Using the actuator-disk basis established by PT-AN-001 and freshwater density of:

**ρ = 997 kg/m³**

the three candidate diameters produce the following first-order values.

#### Continuous Operating Point — 7.0 kgf / 68.6 N

| Candidate | Diameter | Disk Loading | Ideal Induced Velocity | Ideal Far-Wake Velocity | Ideal Induced Power |
|---|---:|---:|---:|---:|---:|
| G80 | 80 mm | approximately 13.66 kPa | approximately 2.62 m/s | approximately 5.23 m/s | approximately 180 W |
| G90 | 90 mm | approximately 10.79 kPa | approximately 2.33 m/s | approximately 4.65 m/s | approximately 160 W |
| G100 | 100 mm | approximately 8.74 kPa | approximately 2.09 m/s | approximately 4.19 m/s | approximately 144 W |

#### Peak Operating Point — 10.0 kgf / 98.1 N

| Candidate | Diameter | Disk Loading | Ideal Induced Velocity | Ideal Far-Wake Velocity | Ideal Induced Power |
|---|---:|---:|---:|---:|---:|
| G80 | 80 mm | approximately 19.51 kPa | approximately 3.13 m/s | approximately 6.26 m/s | approximately 307 W |
| G90 | 90 mm | approximately 15.42 kPa | approximately 2.78 m/s | approximately 5.56 m/s | approximately 273 W |
| G100 | 100 mm | approximately 12.49 kPa | approximately 2.50 m/s | approximately 5.00 m/s | approximately 245 W |

The calculated values are ideal hydrodynamic quantities and shall not be interpreted as predicted RDT-80 shaft-equivalent power or electrical input power.

---

### 6.3 Disk-Loading Effect

Disk loading is one of the clearest hydrodynamic differentiators among the three candidates.

At fixed thrust:

**Disk Loading ∝ 1 / D²**

Relative to G80:

- G90 reduces disk loading by approximately **21%**;
- G100 reduces disk loading by approximately **36%**.

The reduction applies at both the continuous and peak operating points because the candidate diameters remain unchanged while thrust is held constant.

Lower disk loading generally provides more hydrodynamic design margin because the required pressure rise is distributed across a larger effective area.

For Project Triton, lower disk loading may reduce the burden placed on:

- local blade circulation;
- blade section loading;
- propulsor rotational speed;
- local pressure reduction;
- duct loading; and
- sensitivity to nonideal losses.

This does not establish that the largest diameter is optimal.

The benefit must be weighed against the mechanical, electromagnetic, packaging, and manufacturing penalties developed elsewhere in PT-AN-002.

---

### 6.4 Induced-Velocity Effect

The required ideal induced velocity also decreases as diameter increases.

At the continuous operating point:

- G80 requires approximately **2.62 m/s**;
- G90 requires approximately **2.33 m/s**;
- G100 requires approximately **2.09 m/s**.

At the peak operating point:

- G80 requires approximately **3.13 m/s**;
- G90 requires approximately **2.78 m/s**;
- G100 requires approximately **2.50 m/s**.

The corresponding ideal far-wake velocities likewise decrease with increasing diameter.

This means that the larger candidate disks achieve the same thrust by accelerating a larger mass flow through a smaller velocity increment.

That is the fundamental hydrodynamic reason their ideal power requirement is lower.

---

### 6.5 Ideal-Power Effect

At fixed required thrust:

**P_i ∝ 1 / D**

Relative to G80:

- G90 requires approximately **11% less ideal induced power**;
- G100 requires approximately **20% less ideal induced power**.

For the 7.0 kgf continuous case:

- G80: approximately 180 W;
- G90: approximately 160 W;
- G100: approximately 144 W.

For the 10.0 kgf peak case:

- G80: approximately 307 W;
- G90: approximately 273 W;
- G100: approximately 245 W.

The difference between G80 and G100 is therefore approximately:

- **36 W** at the continuous operating point; and
- **62 W** at the peak operating point

in ideal induced power.

Those differences are meaningful, but they are not large enough by themselves to justify selection of G100.

Real-system losses and geometry-dependent propulsor efficiency may be of similar or greater magnitude.

---

### 6.6 Blade-Loading Implications

Actual blade loading cannot yet be calculated because the following remain unresolved:

- blade count;
- blade chord;
- radial blade extent;
- blade section;
- pitch;
- twist;
- solidity;
- duct geometry;
- rotor speed.

Nevertheless, the disk-loading trend provides a useful first-order indication.

For the same required thrust, G80 will generally require a more highly loaded propulsor than G90 or G100 unless compensated by:

- increased blade area;
- increased blade count;
- higher circulation;
- greater rotational speed;
- more aggressive pitch;
- stronger duct augmentation; or
- some combination of these.

These compensating measures may introduce penalties in:

- drag;
- torque;
- cavitation;
- vibration;
- manufacturing;
- startup behavior; or
- efficiency.

Accordingly, G80 provides less hydrodynamic design freedom than the larger candidates.

G90 and G100 provide progressively more opportunity to achieve the required thrust without relying on highly aggressive blade loading.

---

### 6.7 Rotational-Speed Implications

The actuator-disk analysis does not determine rotor RPM.

Actual required RPM will depend upon the propulsor geometry and resulting thrust coefficient.

However, for geometrically similar propulsors operating under broadly comparable nondimensional conditions, increased diameter generally allows a required thrust to be achieved at lower rotational speed.

That trend is potentially beneficial because lower RPM may reduce:

- blade-tip speed;
- cavitation tendency;
- hydrodynamic excitation frequency;
- rotor centrifugal loading;
- magnetic-element retention demand;
- bearing or support speed demand; and
- control bandwidth requirements.

The benefit cannot yet be quantified because the propulsor thrust coefficient is unresolved.

Subsequent hydrodynamic analysis shall therefore determine RPM independently for each candidate rather than assume equal rotational speed.

---

### 6.8 Blade-Tip-Speed Consideration

Blade-tip speed is approximately:

**V_tip = πD_P N / 60**

where:

- **D_P** = propulsor diameter;
- **N** = propulsor rotational speed.

At equal RPM, the larger candidates would have higher tip speed.

However, equal-RPM comparison is not the relevant design condition if larger propulsors can satisfy the thrust requirement at lower RPM.

The hydrodynamic trade must therefore compare:

**required thrust at the candidate-specific operating RPM**

rather than:

**different diameters at a common arbitrary RPM**.

No candidate shall be penalized or favored for tip speed until the corresponding RPM has been established through propulsor analysis.

---

### 6.9 Cavitation Implications

PT-AN-001 identified cavitation as an unresolved hydrodynamic constraint controlled by SR-060 and ORD-018.

The present geometry analysis cannot establish cavitation inception because that requires local blade pressure information.

However, the first-order trends are relevant.

At fixed required thrust, larger diameter reduces:

- disk loading;
- induced velocity;
- required average pressure rise.

These trends generally provide greater opportunity to maintain acceptable local pressure margins.

Accordingly, the preliminary cavitation ranking is:

| Candidate | Relative Preliminary Cavitation Margin |
|---|---|
| G80 | Least favorable |
| G90 | Intermediate |
| G100 | Most favorable |

This ranking is qualitative only.

A poorly designed 100 mm propulsor could cavitate earlier than a well-designed 80 mm propulsor.

Final cavitation assessment shall therefore depend on:

- blade geometry;
- RPM;
- local pressure distribution;
- water temperature;
- ambient pressure;
- immersion depth;
- duct interaction; and
- operating condition.

---

### 6.10 Duct Interaction

The RDT-80 is intended to operate as an integrated ducted rim-driven propulsor.

The duct may influence:

- static thrust;
- inlet acceleration;
- pressure recovery;
- tip-region flow;
- rotor loading;
- flow separation;
- reverse performance;
- cavitation behavior;
- external drag.

The final duct shape is not determined by nominal diameter alone.

However, increasing D_P will generally increase the minimum physical scale of the duct and may alter the practical relationship among:

- blade tip;
- rotor;
- duct throat;
- inlet lip;
- outlet diffuser; and
- structural housing.

PT-AN-002 shall therefore avoid treating the nominal propulsor disk as equivalent to the final effective hydrodynamic capture area.

Detailed duct optimization remains downstream hydrodynamic work under OI-015.

---

### 6.11 Tip and Rotor Clearance Effects

Rim-driven architecture creates a geometry relationship unlike a conventional propeller with an external blade-tip gap.

The outer blade region transitions into or attaches to the annular rotor.

The design must therefore control hydrodynamic leakage and disturbances associated with:

- rotor-to-duct clearance;
- blade-to-rotor transitions;
- rotating/stationary annular interfaces;
- support features;
- local recesses or steps;
- structural discontinuities.

The final effect cannot yet be calculated.

However, a candidate geometry that forces excessively large clearance relative to propulsor diameter may lose part of the theoretical hydrodynamic benefit predicted by ideal disk-area scaling.

Clearance shall therefore ultimately be evaluated as a nondimensional quantity as well as an absolute dimension.

For example, the ratio:

**C_R / D_P**

may be useful when comparing alternative configurations.

No acceptable numerical ratio is established at this stage.

---

### 6.12 Hubless Architecture Effect

One intended hydrodynamic advantage of the Project Triton architecture is elimination of the conventional central propulsion shaft, motor hub, and associated stationary support obstruction.

The geometry analysis shall preserve this feature.

Potential benefits may include:

- increased effective central flow area;
- reduced central blockage;
- reduced hub-wake disturbance;
- simplified central flow path.

However, PT-AN-002 shall not assume that removal of the central hub automatically yields a particular efficiency improvement.

Actual benefit will depend upon:

- blade inner geometry;
- blade root termination;
- duct design;
- rotor geometry;
- inflow uniformity; and
- resulting wake structure.

These effects require subsequent computational or experimental hydrodynamic evaluation.

---

### 6.13 Reverse-Thrust Implications

Reverse thrust remains a secondary capability and has no quantitative requirement yet.

Increasing propulsor diameter does not by itself ensure improved reverse performance.

Reverse capability will depend strongly upon:

- blade-section symmetry or asymmetry;
- pitch distribution;
- duct inlet/outlet asymmetry;
- rotor direction;
- control strategy.

The geometry trade shall therefore avoid selecting G80, G90, or G100 primarily on speculative reverse-thrust performance.

The selected diameter shall preserve sufficient design flexibility for controlled reverse operation to be evaluated during OI-015 development.

---

### 6.14 Static-Test Facility Effects

The initial performance requirement is based on restrained static thrust.

The selected propulsor and duct geometry therefore affects the validity and practicality of the eventual water-test setup.

Larger candidates may require greater separation from:

- tank walls;
- tank floor;
- free surface;
- upstream obstruction;
- downstream obstruction;
- recirculating wake.

Otherwise, confinement effects may distort measured static thrust.

G100 therefore imposes a somewhat greater test-environment burden than G80 or G90.

The exact required tank dimensions cannot yet be established because they depend on:

- final duct geometry;
- wake structure;
- mounting arrangement;
- facility configuration; and
- accepted verification methodology.

This dependency shall remain coordinated with OI-019 and OI-023.

---

### 6.15 Hydrodynamic Scalability

A geometry that performs successfully at the initial scale should ideally support later scaling studies.

Larger diameter at the same thrust reduces loading, but the first prototype should not be oversized merely to obtain an artificially easy hydrodynamic operating point.

A technically useful demonstrator should exercise:

- meaningful blade loading;
- meaningful rotor torque;
- useful power density;
- realistic clearance sensitivity;
- realistic electromagnetic loading.

G80 therefore remains valuable because it creates a demanding compact-propulsor problem.

G100 provides more hydrodynamic margin but may make the first prototype less representative of a compact high-specific-performance rim-driven thruster.

G90 may provide an intermediate scaling point.

---

### 6.16 Hydrodynamic Candidate Assessment

Based solely on the current hydrodynamic evidence:

| Criterion | G80 | G90 | G100 |
|---|---|---|---|
| Disk loading | Least favorable | Favorable | Most favorable |
| Ideal induced power | Least favorable | Favorable | Most favorable |
| Induced velocity | Highest | Intermediate | Lowest |
| Blade-loading design margin | Lowest | Intermediate | Highest |
| Preliminary cavitation margin | Lowest | Intermediate | Highest |
| Potential for lower operating RPM | Lowest | Intermediate | Highest |
| Compact hydrodynamic package | Most favorable | Favorable | Least favorable |
| Static-test facility burden | Most favorable | Favorable | Least favorable |
| Compact high-performance development value | Very favorable | Very favorable | Favorable |

From a purely hydrodynamic standpoint:

**G100 is the most favorable candidate.**

However, the hydrodynamic advantage from G90 to G100 is incremental rather than transformative.

G90 already captures a meaningful portion of the benefit relative to G80 while increasing nominal diameter by only 12.5%.

---

### 6.17 Hydrodynamic Finding

The hydrodynamic analysis does not justify eliminating any of the three candidate diameters.

The current interpretation is:

**G80** remains technically credible but imposes the highest hydrodynamic loading and provides the least margin for blade and cavitation development.

**G90** materially reduces disk loading and induced-power demand while retaining a relatively compact physical scale.

**G100** provides the greatest hydrodynamic margin but increases system and test scale for an additional ideal-power reduction of only approximately 10% relative to G90.

Accordingly, the preliminary hydrodynamic ranking is:

1. **G90 — strongest current balance of hydrodynamic benefit and compact scale**
2. **G100 — best pure hydrodynamic performance but greater system-size penalty**
3. **G80 — credible compact baseline but highest hydrodynamic burden**

This ranking is **hydrodynamic only** and does not constitute the integrated geometry selection.

The next evaluation shall determine whether increased diameter provides corresponding benefits or penalties for the annular electromagnetic-drive packaging.

---

## 7. Electromagnetic Packaging Effects

### 7.1 Purpose

This section evaluates how the three candidate propulsor diameters affect the physical packaging available for the annular electromagnetic drive.

The comparison does not select the final electromagnetic topology.

OI-004 — Electromagnetic Topology, OI-005 — Stator and Winding Geometry, and OI-006 — Rotor Magnetic Circuit / Magnetic-Element Arrangement remain open.

Accordingly, the purpose of this section is to determine whether G80, G90, or G100 provides materially greater or lesser opportunity for a practical annular motor capable of supporting the required RDT-80 thrust objective.

The comparison shall consider:

- available circumference;
- available active electromagnetic area;
- torque-production leverage;
- radial packaging;
- axial packaging;
- winding space;
- magnetic-element space;
- pole-placement flexibility;
- heat-generating area;
- rotor magnetic-element retention;
- electromagnetic clearance;
- manufacturing segmentation; and
- compatibility with future topology selection.

---

### 7.2 Electromagnetic Design Basis

The electromagnetic drive must ultimately provide the rotor torque required by the hydrodynamic operating point.

The governing mechanical relationship is:

**P_mechanical = τω**

where:

- **P_mechanical** = propulsor mechanical power;
- **τ** = rotor torque; and
- **ω** = rotor angular velocity.

PT-AN-002 does not yet establish the required mechanical power, torque, or RPM because detailed propulsor analysis has not been completed.

However, candidate diameter affects the geometry available to produce a required torque.

For an annular motor, useful electromagnetic torque generally benefits from:

- greater effective radius;
- greater active circumferential length;
- adequate magnetic loading;
- adequate conductor loading;
- adequate active axial length.

The candidate comparison shall therefore evaluate electromagnetic opportunity rather than assume equal motor capability at every diameter.

---

### 7.3 Circumference Available for Electromagnetic Interaction

Nominal circumference increases directly with diameter:

**C = πD**

Using the nominal propulsor diameter as a first-order comparison reference:

| Candidate | Nominal Diameter | Nominal Circumference | Relative Circumference |
|---|---:|---:|---:|
| G80 | 80 mm | approximately 251 mm | 1.000 |
| G90 | 90 mm | approximately 283 mm | 1.125 |
| G100 | 100 mm | approximately 314 mm | 1.250 |

Relative to G80:

- G90 provides approximately **12.5% more circumference**;
- G100 provides approximately **25% more circumference**.

This additional circumferential length may provide greater space for:

- stator teeth or electromagnetic segments;
- windings;
- permanent magnets or rotor magnetic elements;
- pole pairs;
- retention features;
- sensor features;
- phase grouping.

The actual benefit depends on topology and shall not be treated as a direct percentage increase in torque capability.

---

### 7.4 Electromagnetic Radius and Torque Leverage

Torque is the product of tangential force and effective radius:

**τ = F_t r**

where:

- **F_t** = net tangential electromagnetic force;
- **r** = effective torque radius.

For comparable tangential electromagnetic force, increasing effective radius increases torque.

Using nominal propulsor radius only as a geometric comparison:

| Candidate | Nominal Radius | Relative Radius |
|---|---:|---:|
| G80 | 40 mm | 1.000 |
| G90 | 45 mm | 1.125 |
| G100 | 50 mm | 1.250 |

Thus, if comparable electromagnetic loading could be maintained:

- G90 would provide greater torque leverage than G80;
- G100 would provide still greater torque leverage.

In practice, the effective electromagnetic radius will be larger than or otherwise offset from the propulsor radius depending on the final rotor and stator arrangement.

The relationship remains useful because larger candidate geometry generally moves the active electromagnetic region farther from the axis.

---

### 7.5 Combined Circumference-and-Radius Effect

For a simplified annular electromagnetic system with similar:

- tangential stress;
- axial active length;
- radial active build; and
- duty condition,

torque capability may increase more rapidly than diameter alone because both:

- available circumference; and
- effective torque radius

increase with diameter.

A first-order conceptual relationship is:

**τ ∝ electromagnetic shear stress × active cylindrical area × radius**

For a similar cylindrical annular active surface:

**active area ∝ circumference × axial length**

and therefore, with axial length held constant:

**τ ∝ D²**

as a rough geometric trend.

This is not a predictive motor-design equation for the RDT-80.

It is used only to illustrate why modest increases in annular diameter can materially affect electromagnetic torque opportunity.

Using D² as a purely geometric comparison index:

| Candidate | Relative Diameter | Relative D² Index |
|---|---:|---:|
| G80 | 1.000 | 1.000 |
| G90 | 1.125 | approximately 1.266 |
| G100 | 1.250 | approximately 1.563 |

This indicates that G90 may offer roughly **27% more geometric torque-production opportunity** than G80 under highly simplified equal-loading assumptions, while G100 may offer roughly **56% more**.

These values shall not be interpreted as predicted motor torque.

---

### 7.6 Radial Packaging Considerations

Increasing D_P does not automatically increase available rotor or stator radial thickness.

The final outside diameter also grows as radial motor, structural, support, clearance, containment, and duct dimensions are added.

The candidate geometry must therefore distinguish between:

- increased **circumference and torque radius**; and
- increased **radial build**.

A design could, for example, use a larger propulsor diameter while retaining approximately similar rotor and stator radial thickness.

Alternatively, a larger system envelope could use some of the added size to provide:

- thicker magnets;
- greater winding depth;
- deeper stator teeth;
- stronger rotor back iron;
- stronger retention material;
- greater structural section depth.

The correct radial build cannot be selected until topology and magnetic-circuit analysis are completed.

PT-AN-002 shall therefore reserve a packaging envelope rather than prescribe final electromagnetic thickness.

---

### 7.7 Axial Active-Length Considerations

Electromagnetic torque capability also depends on available active axial length.

A longer active electromagnetic region may permit:

- greater conductor length;
- greater magnetic interaction area;
- lower required electromagnetic loading for the same torque;
- reduced current density;
- improved thermal spreading.

However, increased axial length may increase:

- overall thruster length;
- rotor mass;
- magnet volume;
- winding material;
- manufacturing complexity;
- structural demand;
- hydrodynamic integration difficulty.

Candidate diameter may influence how much axial length is required.

A larger diameter may permit the same torque to be produced with a shorter active electromagnetic length if electromagnetic loading remains comparable.

This possibility is potentially valuable because a slightly larger diameter could produce a more compact axial package.

No numerical axial-length reduction is assumed at this stage.

---

### 7.8 Winding Space

The final stator winding arrangement remains unresolved.

Nevertheless, available packaging must eventually support:

- required conductor cross section;
- electrical insulation;
- phase separation;
- slot or segment geometry;
- manufacturing access;
- termination and connection geometry;
- thermal conduction paths;
- encapsulation or environmental protection where required.

G80 provides the least circumferential packaging space.

G90 provides an intermediate increase.

G100 provides the greatest physical opportunity for distributed winding space.

This may allow a larger-diameter geometry to achieve a required ampere-turn level using:

- more conductor area;
- lower local current density;
- more distributed phase geometry;
- improved thermal spreading.

However, increased winding length can also increase copper resistance and material quantity.

Accordingly, additional circumference is not automatically equivalent to lower electrical loss.

---

### 7.9 Pole-Count and Magnetic-Element Flexibility

The final pole count and magnetic-element configuration remain controlled by OI-004 through OI-006.

Increasing circumference may provide greater flexibility to select:

- pole count;
- pole pitch;
- magnet segment width;
- stator segment width;
- phase grouping;
- sensor spacing;
- retention segmentation.

G80 may force relatively small pole pitches if a high pole count is desired.

G100 permits a given pole count to use a larger physical pole pitch.

Alternatively, G100 could support a higher pole count while retaining similar physical pole dimensions.

G90 provides an intermediate compromise.

No pole count shall be selected based solely on circumference.

The final choice shall also account for:

- electrical frequency;
- switching losses;
- cogging;
- torque ripple;
- magnetic saturation;
- manufacturing segmentation;
- controller capability;
- rotor-speed range.

---

### 7.10 Electromagnetic Frequency Consideration

Electrical frequency for a synchronous permanent-magnet-type topology is related to mechanical speed and pole-pair count:

**f_e = pN / 60**

where:

- **f_e** = electrical frequency;
- **p** = number of pole pairs;
- **N** = rotor speed in RPM.

Candidate diameter affects this indirectly.

A larger propulsor may permit lower required RPM for the same thrust, while larger circumference may also permit a different pole-count choice.

These two effects may partially offset or compound each other.

Accordingly, no candidate shall be favored solely because it provides room for more poles.

Electrical-frequency consequences shall be evaluated after:

- propulsor RPM is estimated; and
- candidate electromagnetic topologies are defined.

---

### 7.11 Magnetic Back-Iron and Flux-Path Implications

Where the selected electromagnetic topology requires ferromagnetic flux-return structures, sufficient physical cross section must be provided to avoid unacceptable saturation.

Rotor and stator flux-path dimensions may consume:

- radial thickness;
- axial thickness;
- circumferential segmentation space.

A larger nominal diameter may permit greater total flux-transfer area without requiring extreme local section thickness.

However, larger circumference may also increase:

- total ferromagnetic material volume;
- rotor mass;
- magnetic loss;
- manufacturing segmentation requirements.

PT-AN-002 shall therefore ensure that each candidate preserves plausible space for a magnetic circuit but shall not select final back-iron dimensions.

---

### 7.12 Rotor Magnetic-Element Retention

OI-007 requires a credible means of retaining rotor electromagnetic elements against:

- centrifugal loading;
- electromagnetic force;
- thermal expansion;
- hydrodynamic effects;
- vibration;
- environmental degradation.

Candidate diameter influences retention in two opposing ways.

Larger diameter may provide:

- greater circumferential packaging space;
- larger structural attachment regions;
- less aggressive electromagnetic loading for equivalent torque.

However, at a given RPM, larger radius increases:

- peripheral speed;
- centrifugal acceleration;
- centrifugal stress demand.

Because the larger propulsors may operate at lower RPM, the net retention effect cannot yet be determined.

Final retention analysis shall therefore use the candidate-specific operating RPM rather than equal-RPM assumptions.

---

### 7.13 Electromagnetic Clearance Sensitivity

The physical electromagnetic clearance, **g_EM**, can strongly affect torque production for many motor topologies.

A smaller clearance may improve electromagnetic coupling but increases sensitivity to:

- rotor runout;
- bearing/support deflection;
- manufacturing tolerances;
- housing deformation;
- thermal expansion;
- debris;
- assembly error.

A larger diameter does not automatically permit a larger or smaller electromagnetic clearance.

However, the nondimensional ratio:

**g_EM / D**

decreases for a fixed absolute gap as diameter increases.

This means a practical manufacturing gap may represent a smaller fraction of the machine diameter in G90 or G100 than in G80.

That may provide some relative design benefit, but final electromagnetic performance depends on magnetic-circuit geometry rather than diameter ratio alone.

No numerical electromagnetic clearance is established by this analysis.

---

### 7.14 Thermal-Surface Implications

Electromagnetic losses must ultimately be rejected to the surrounding water or other approved thermal path.

Increasing diameter may increase:

- external wetted circumference;
- potential housing heat-transfer area;
- stator surface area;
- distributed thermal path length.

This may improve heat spreading and reduce local heat flux.

However, a larger electromagnetic system may also contain:

- more copper;
- more magnetic material;
- greater total loss-producing volume.

Thermal benefit therefore depends on both loss density and heat-transfer geometry.

At this stage, G90 and G100 are considered to provide greater thermal packaging opportunity than G80, but not necessarily lower total loss.

Final thermal assessment remains controlled by OI-014.

---

### 7.15 Segmented Manufacturing Considerations

An annular electromagnetic system may be manufactured using:

- segmented magnets;
- segmented stator teeth;
- individual coils;
- modular stator sectors;
- composite retaining structures;
- machined annular components;
- additively manufactured support geometry.

Larger circumference may increase the practical number of segments and total part count.

G100 could therefore provide greater design flexibility while simultaneously increasing assembly and tolerance-management burden.

G80 minimizes total circumference but may require smaller and more densely packaged electromagnetic features.

G90 again represents an intermediate geometry.

The candidate trade shall favor geometry that can be fabricated and inspected using realistic prototype processes rather than requiring unnecessarily small or numerous components.

---

### 7.16 Controller and Electrical-Envelope Interaction

Geometry affects the electromagnetic design, which in turn affects:

- voltage;
- current;
- winding turns;
- back-EMF;
- inductance;
- switching behavior;
- electrical frequency;
- controller rating.

PT-AN-001 established only a preliminary planning basis of approximately:

- **0.6 kW continuous electrical input**; and
- **1.0 kW peak electrical input**.

The geometry shall preserve a credible path to operating in this class without assuming that all three candidates will use identical voltage or current.

A geometry requiring very high current because of insufficient winding area or torque density shall be penalized in subsequent OI-003 and OI-004 analysis.

Likewise, a geometry requiring excessive voltage or electrical frequency shall not be accepted merely because it fits physically.

---

### 7.17 Electromagnetic Candidate Assessment

Based solely on the current electromagnetic packaging evidence:

| Criterion | G80 | G90 | G100 |
|---|---|---|---|
| Available circumference | Least favorable | Favorable | Most favorable |
| Torque radius | Least favorable | Favorable | Most favorable |
| Simplified geometric torque opportunity | Least favorable | Favorable | Most favorable |
| Winding packaging freedom | Lowest | Intermediate | Highest |
| Magnetic-element packaging freedom | Lowest | Intermediate | Highest |
| Pole-layout flexibility | Lowest | Intermediate | Highest |
| Potential to reduce required active axial length | Lowest | Intermediate | Highest |
| Compact motor package | Most favorable | Favorable | Least favorable |
| Rotor material quantity | Most favorable | Favorable | Least favorable |
| Potential rotor inertia | Most favorable | Intermediate | Least favorable |
| Prototype electromagnetic fabrication scale | Most favorable | Favorable | Moderate |
| Overall electromagnetic packaging balance | Moderate | Very Favorable | Favorable |

From a pure electromagnetic **space and torque-leverage** perspective:

**G100 provides the greatest opportunity.**

However, G100 also carries the greatest rotor-size, material, inertia, and manufacturing penalties.

---

### 7.18 Electromagnetic Finding

No candidate is eliminated by electromagnetic packaging considerations.

The current interpretation is:

**G80** appears feasible but provides the least circumferential and torque-radius margin. It may require higher electromagnetic loading, greater active axial length, higher current density, higher RPM, or some combination of these once the hydrodynamic operating point is established.

**G90** provides approximately 12.5% greater torque radius and circumference than G80 while increasing nominal diameter by only 10 mm. Under simplified equal-loading assumptions, its geometric torque-production opportunity is materially greater than G80 without imposing the full physical penalty of G100.

**G100** provides the greatest electromagnetic packaging freedom and potentially the greatest ability to reduce local electromagnetic loading, but at the cost of increased rotor size, material, inertia, containment burden, and manufacturing scale.

Accordingly, the preliminary electromagnetic-packaging ranking is:

1. **G90 — strongest current balance of torque opportunity, packaging space, and prototype scale**
2. **G100 — greatest electromagnetic opportunity but increased mechanical and manufacturing burden**
3. **G80 — compact and credible, but least electromagnetic packaging margin**

This ranking is preliminary because actual torque, RPM, topology, pole count, winding geometry, magnetic loading, and thermal losses remain unresolved.

Notably, **G90 now ranks first in both the hydrodynamic and preliminary electromagnetic comparisons**, but no integrated geometry selection shall be made until the mechanical, structural, and manufacturing consequences are evaluated.

---

## 8. Mechanical and Structural Effects

### 8.1 Purpose

This section evaluates how the three candidate propulsor diameters affect the principal mechanical and structural demands of the RDT-80 prototype.

The comparison does not establish the final rotor-support, bearing, structural-material, containment, or clearance architecture.

Those decisions remain controlled principally by:

- OI-008 — Radial Support;
- OI-009 — Axial Support and Thrust Reaction;
- OI-010 — Backup Containment;
- OI-011 — Operating Clearance;
- OI-012 — Materials and Structural Selection; and
- OI-020 — Manufacturing and Tolerances.

The purpose of this section is to determine whether G80, G90, or G100 materially changes the difficulty of:

- supporting the annular rotor;
- reacting axial thrust;
- reacting electromagnetic and hydrodynamic loads;
- maintaining rotor alignment;
- maintaining radial and axial clearance;
- limiting structural deformation;
- retaining rotor components;
- containing credible rotor failures;
- controlling rotor inertia and stored energy; and
- producing a mechanically practical development prototype.

---

### 8.2 Governing Mechanical Loads

The integrated RDT-80 structure shall ultimately react or accommodate, as applicable:

- forward hydrodynamic thrust;
- reverse hydrodynamic thrust;
- rotor torque;
- electromagnetic radial force;
- electromagnetic axial force;
- rotor-support reaction loads;
- rotor imbalance;
- centrifugal loading;
- transient acceleration and deceleration;
- emergency-stop loading;
- hydrodynamic disturbance;
- obstruction or impact loading;
- gravity and handling loads;
- test-fixture loads;
- thermal expansion;
- manufacturing misalignment; and
- vibration.

The currently established principal thrust loads are:

| Operating Condition | Forward Static Thrust |
|---|---:|
| Continuous | 68.6 N minimum |
| Peak | 98.1 N minimum |

These values establish minimum performance operating points rather than maximum structural design loads.

The eventual structural design load shall include applicable margin and any higher transient or abnormal loads established through downstream analysis.

---

### 8.3 Axial Thrust Reaction

The propulsor generates an axial reaction that must be transferred from the rotating system through the axial-support architecture into the stationary thruster structure and ultimately to the mounting interface.

For the selected performance objective, the support system must accommodate at least the loads associated with:

- 68.6 N continuous forward static thrust; and
- 98.1 N peak forward static thrust.

The required axial-support capacity will exceed these nominal thrust values after accounting for:

- design margin;
- transient thrust;
- reverse operation;
- hydrodynamic disturbance;
- axial electromagnetic forces;
- assembly preload, where applicable;
- impact or obstruction loads;
- test-stage expansion.

Nominal propulsor diameter does not directly change the required thrust reaction when thrust is held constant.

Accordingly, the axial thrust requirement itself does not favor G80, G90, or G100.

Diameter influences the **mechanical implementation** of the thrust-reaction system rather than the nominal axial force.

---

### 8.4 Rotor Diameter and Structural Radius

As candidate diameter increases, the rotating annular structure becomes larger in radius.

Using nominal propulsor radius as the comparison basis:

| Candidate | Nominal Radius | Relative Radius |
|---|---:|---:|
| G80 | 40 mm | 1.000 |
| G90 | 45 mm | 1.125 |
| G100 | 50 mm | 1.250 |

A larger radius may provide:

- greater physical room for support interfaces;
- increased circumferential attachment length;
- larger structural section possibilities;
- more space for distributed load transfer.

However, larger radius may also increase sensitivity to:

- rotor ovalization;
- circumferential distortion;
- runout;
- tolerance accumulation;
- imbalance;
- centrifugal loading;
- structural resonance;
- containment size.

Therefore, increased radius is not automatically structurally favorable.

---

### 8.5 Rotor Mass Trend

Rotor mass cannot yet be calculated because the following remain unresolved:

- rotor radial thickness;
- rotor axial length;
- magnetic-element volume;
- retention architecture;
- material density;
- support-interface geometry;
- encapsulation;
- blade attachment.

Nevertheless, for broadly similar cross-sectional proportions, increasing diameter generally increases:

- rotor circumference;
- material volume;
- magnetic-element quantity;
- retention material;
- total rotating mass.

The expected qualitative trend is:

| Candidate | Expected Rotor-Mass Tendency |
|---|---|
| G80 | Lowest |
| G90 | Intermediate |
| G100 | Highest |

This trend may be altered if a larger candidate permits a thinner or shorter motor structure for equivalent torque.

Final mass comparison shall therefore use actual candidate motor and rotor geometry rather than circumference alone.

---

### 8.6 Rotor Polar Inertia

Polar moment of inertia is particularly important for a rim-driven rotor because a significant fraction of rotating mass is located relatively far from the axis.

For discrete mass:

**I = mr²**

and for a distributed annular structure, inertia remains strongly dependent on radius.

Accordingly, even modest increases in rotor radius can materially increase rotational inertia if mass remains comparable.

Higher inertia affects:

- startup torque;
- acceleration time;
- stopping time;
- emergency-stop energy;
- motor-control response;
- support transient loading;
- stored kinetic energy;
- containment consequence.

The qualitative inertia ranking is therefore presently:

| Candidate | Expected Rotor-Inertia Tendency |
|---|---|
| G80 | Most favorable |
| G90 | Intermediate |
| G100 | Least favorable |

This ranking is provisional because candidate-specific rotor mass and operating RPM remain unresolved.

---

### 8.7 Stored Rotational Energy

Rotational kinetic energy is:

**E_k = 1/2 Iω²**

where:

- **E_k** = rotational kinetic energy;
- **I** = polar moment of inertia;
- **ω** = angular velocity.

A larger candidate may increase **I**, but it may also permit a lower required **ω** for the same thrust.

Because kinetic energy depends on the square of angular velocity, the net stored-energy ranking cannot yet be determined.

For example:

- G100 could have substantially greater inertia but materially lower RPM;
- G80 could have lower inertia but potentially higher RPM.

Accordingly, containment and emergency-stop analysis shall use the candidate-specific combination of:

- rotor mass;
- inertia;
- operating RPM; and
- overspeed limit.

No candidate shall be declared safer solely because it is smaller or larger.

---

### 8.8 Centrifugal Loading

For a mass element rotating at radius **r**:

**a_c = ω²r**

and:

**F_c = mω²r**

At equal RPM, increasing radius increases centrifugal acceleration and centrifugal force.

However, equal RPM is not expected to be the final comparison basis.

If larger propulsors achieve the required thrust at lower speed, their centrifugal loading may be comparable to or lower than a smaller higher-speed design.

The final rotor-retention analysis shall therefore use:

- actual rotor radius;
- candidate-specific RPM;
- component mass;
- overspeed condition;
- material properties;
- retention geometry.

This is particularly important for OI-007 — Rotor Electromagnetic-Element Retention.

---

### 8.9 Rotor Radial Support

The radial-support system must maintain the rotor concentrically relative to stationary structure throughout the approved operating envelope.

Candidate diameter may affect radial support through:

- larger support circumference;
- different available contact length;
- different support-element count;
- greater rotor mass;
- greater inertia;
- increased susceptibility to runout;
- increased structural deflection;
- different hydrodynamic disturbance loads.

G80 offers the smallest rotor and potentially the lowest support mass burden.

G100 offers the greatest physical packaging space for distributed support features.

G90 provides an intermediate combination.

The correct support architecture cannot yet be selected because OI-008 remains open.

Potential future concepts may include:

- rolling-element support;
- hydrodynamic or water-lubricated support;
- polymer bearing surfaces;
- magnetic support;
- distributed guide features;
- hybrid arrangements.

PT-AN-002 shall not select one of these merely to complete the geometry definition.

---

### 8.10 Axial Support and Thrust Reaction

The axial-support system must:

- maintain rotor axial position;
- react propulsor thrust;
- preserve electromagnetic alignment;
- maintain axial clearances;
- accommodate bidirectional operation if required.

Larger candidate diameter may provide greater circumferential space for distributed axial-reaction features.

However, larger diameter may also increase:

- rotor inertia;
- support alignment sensitivity;
- differential thermal expansion;
- manufacturing variation.

Because required axial thrust is common to all three candidates, the preliminary structural distinction is driven primarily by packaging rather than nominal load.

The current qualitative axial-support ranking is therefore:

| Candidate | Axial-Support Packaging Assessment |
|---|---|
| G80 | Favorable but least packaging space |
| G90 | Very Favorable |
| G100 | Favorable with greater size burden |

---

### 8.11 Rotor Runout and Alignment

Maintaining annular rotor alignment is critical to:

- electromagnetic clearance;
- mechanical clearance;
- support life;
- vibration;
- prevention of rotor-to-stator contact.

Relevant geometric errors may include:

- radial runout;
- axial runout;
- rotor eccentricity;
- rotor ovality;
- stator concentricity error;
- housing distortion;
- support misalignment.

As diameter increases, absolute geometric deviation associated with a given angular, concentricity, or manufacturing error can become larger.

Likewise, larger annular structures may be more sensitive to:

- warpage;
- curing distortion;
- machining distortion;
- assembly preload;
- thermal gradients.

G100 therefore may impose greater absolute dimensional-control challenges than G80.

G90 is expected to remain comparatively manageable while providing more packaging margin than G80.

---

### 8.12 Clearance Preservation

SR-008 and SR-066 require preservation of mechanical and electromagnetic clearances.

The final clearance budget shall account for:

- manufacturing tolerance;
- assembly error;
- support deflection;
- rotor runout;
- rotor dynamic motion;
- structural deformation;
- thermal expansion;
- coating or encapsulation variation;
- wear;
- debris or contamination where applicable.

The required absolute clearance may not scale directly with diameter.

If manufacturing capability results in approximately similar absolute tolerance capability across all candidates, the larger candidates may have a relative advantage because the required gap represents a smaller fraction of machine diameter.

Conversely, larger annular components may experience larger absolute deformation and runout.

The net clearance effect remains unresolved and shall ultimately be established through OI-011 and OI-020.

---

### 8.13 Housing and Structural Stiffness

The stationary structure must maintain:

- rotor-support alignment;
- electromagnetic alignment;
- mounting-interface geometry;
- containment geometry;
- duct geometry.

Increasing diameter increases the structural span across the annular housing.

For similar material and wall thickness, a larger diameter may become more flexible.

Maintaining comparable stiffness may therefore require:

- greater wall thickness;
- deeper sections;
- ribs;
- higher-modulus material;
- improved load paths.

These changes can increase:

- mass;
- outer diameter;
- material usage;
- manufacturing effort.

G80 therefore has an inherent compactness/stiffness advantage.

G100 may require more deliberate structural reinforcement.

G90 again represents an intermediate case.

---

### 8.14 Rotor Structural Stiffness

The rotating annulus must maintain sufficient shape under:

- centrifugal loading;
- electromagnetic attraction;
- torque;
- blade reaction forces;
- support forces;
- temperature change.

Excessive rotor deformation could reduce:

- electromagnetic clearance;
- mechanical clearance;
- rotor-support stability.

A larger annular rotor may require:

- greater radial thickness;
- greater axial section depth;
- higher-modulus material;
- composite reinforcement;
- circumferential reinforcement.

The final section design cannot yet be established.

However, G100 shall receive a structural penalty in the integrated trade if its larger diameter requires disproportionate rotor reinforcement.

---

### 8.15 Propulsor-to-Rotor Load Transfer

Project Triton directly couples the propulsor to the annular rotor.

The blade-to-rotor interface must transfer:

- blade hydrodynamic load;
- torque;
- axial thrust contribution;
- transient loading;
- vibration.

Candidate diameter affects:

- blade span;
- blade root or outer attachment geometry;
- circumference available for attachment;
- local structural section.

Larger diameter may permit larger attachment features and lower average loading per unit circumference.

However, larger blades or greater radial extent can also increase local bending moments.

Detailed blade-load transfer remains downstream work under OI-015 and OI-012.

---

### 8.16 Rotor Containment

SR-007 requires a secondary retention or containment function for rotor failure conditions within defined design conditions.

Containment demand depends strongly on:

- rotor mass;
- rotor speed;
- stored kinetic energy;
- fragment size;
- likely failure mode;
- material toughness;
- available containment geometry.

G100 may require a larger containment ring or housing simply because the rotating system is larger.

G80 may require less containment mass but could operate at higher RPM.

Because the relevant energy state is unresolved, no final containment ranking is possible.

Nevertheless, G100 is expected to impose the greatest **packaging** burden for containment.

---

### 8.17 Mounting-Interface Effects

The mounting structure must ultimately react:

- thrust;
- torque;
- weight;
- test-fixture forces;
- transient loads.

The same nominal thrust objective applies to all three candidates.

However, larger overall thruster diameter can increase:

- mounting footprint;
- moment arm to external supports;
- fixture size;
- alignment burden;
- handling difficulty.

G80 is therefore most favorable for compact test mounting.

G90 remains practical.

G100 imposes the largest mounting and fixture envelope.

---

### 8.18 Handling and Assembly

Prototype development will require repeated:

- assembly;
- disassembly;
- inspection;
- rotor replacement;
- propulsor changes;
- instrumentation changes;
- test-fixture installation.

Larger candidate geometry may increase:

- component mass;
- handling difficulty;
- alignment difficulty;
- fixture demand;
- assembly time.

However, larger components may also provide:

- better tool access;
- larger fasteners;
- easier sensor packaging;
- less congested assembly space.

G80 is likely easiest to handle but may be more crowded internally.

G100 may be easiest to access but physically more cumbersome.

G90 is expected to provide a useful compromise.

---

### 8.19 Mechanical Failure Consequence

The mechanical consequence of failure is affected by:

- rotating mass;
- RPM;
- stored energy;
- containment geometry;
- rotor fragment trajectory;
- electrical fault response.

A higher-energy failure condition may require:

- stronger guarding;
- greater standoff distance;
- stronger test fixture;
- more conservative test progression.

Candidate diameter therefore affects not only mechanical design but also test risk under RK-016.

No candidate geometry shall be operated at full performance solely because the static structural design appears adequate.

Progressive test-envelope expansion remains mandatory.

---

### 8.20 Mechanical Scalability

A useful development geometry should expose the project to realistic mechanical problems without making the first prototype unnecessarily difficult.

G80 provides:

- compact support architecture;
- lower likely rotor mass;
- lower likely handling burden;
- a more demanding packaging environment.

G100 provides:

- more support packaging space;
- more structural design freedom;
- greater likely mass and inertia;
- a larger containment and fixture burden.

G90 may preserve the essential mechanical challenges of an annular rotor while avoiding the most severe compactness penalty of G80 and the size/inertia penalty of G100.

---

### 8.21 Mechanical and Structural Candidate Assessment

Based on currently available mechanical and structural evidence:

| Criterion | G80 | G90 | G100 |
|---|---|---|---|
| Rotor mass tendency | Most favorable | Favorable | Least favorable |
| Rotor inertia tendency | Most favorable | Favorable | Least favorable |
| Support packaging space | Least favorable | Very Favorable | Most favorable |
| Axial-support packaging | Favorable | Very Favorable | Favorable |
| Structural compactness | Most favorable | Very Favorable | Least favorable |
| Housing stiffness burden | Most favorable | Favorable | Least favorable |
| Runout / dimensional-control burden | Most favorable | Favorable | Least favorable |
| Containment packaging burden | Most favorable | Favorable | Least favorable |
| Mounting / fixture compactness | Most favorable | Favorable | Least favorable |
| Assembly access | Moderate | Very Favorable | Very Favorable |
| Expected overall mechanical balance | Favorable | Very Favorable | Moderate |

From a purely compact mechanical standpoint:

**G80 is the most favorable.**

From a support-packaging standpoint:

**G100 provides the greatest space.**

However, the larger G100 geometry introduces increasing penalties in rotor size, inertia, structural span, containment, and test-fixture scale.

---

### 8.22 Mechanical and Structural Finding

No candidate is eliminated by the present mechanical and structural analysis.

The current interpretation is:

**G80** provides the lowest expected rotor mass, inertia, system size, and containment envelope, but offers the least space for support and internal packaging.

**G90** adds enough radial and circumferential space to improve rotor-support, structural, and assembly packaging while retaining a relatively compact machine and avoiding the largest inertia and containment penalties.

**G100** provides the greatest physical support space but may require disproportionate structural stiffness, rotor-mass, inertia, alignment, containment, and fixture accommodations for the first prototype.

Accordingly, the preliminary mechanical/structural ranking is:

1. **G90 — strongest overall balance**
2. **G80 — strongest compactness and lowest expected inertia**
3. **G100 — greatest packaging space but highest structural and inertia burden**

This result is notable because **G90 now ranks first in the hydrodynamic, electromagnetic-packaging, and mechanical/structural evaluations**.

That convergence strengthens G90 as the current leading geometry candidate, but a recommendation shall not be made until manufacturing and prototype constraints are evaluated in Section 9.

---

## 9. Manufacturing and Prototype Constraints

### 9.1 Purpose

This section evaluates how the three candidate propulsor diameters affect practical fabrication, assembly, inspection, configuration control, prototype cost, instrumentation, and controlled testing.

The objective is not to select a production manufacturing process.

The initial RDT-80 is an engineering prototype whose geometry must permit repeated development cycles involving:

- fabrication;
- assembly;
- inspection;
- dimensional verification;
- component substitution;
- instrumentation;
- disassembly;
- repair;
- redesign;
- controlled retesting.

The preferred geometry shall therefore be compatible with realistic prototype resources while preserving sufficient dimensional control to support meaningful engineering conclusions.

---

### 9.2 Prototype Manufacturing Philosophy

The initial geometry shall favor:

- manufacturable dimensions;
- measurable critical features;
- accessible assembly interfaces;
- replaceable development components;
- modularity where technically appropriate;
- tolerance schemes compatible with available processes;
- repeatable configuration control;
- practical instrumentation access;
- economical iteration.

The prototype shall not require production-grade manufacturing merely to demonstrate the architecture unless analysis establishes that such precision is fundamentally necessary.

Likewise, geometry shall not be intentionally oversized solely to make fabrication easy if doing so materially reduces the technical value of the prototype.

The design goal is:

**sufficient precision and robustness to produce technically valid development data without imposing unnecessary manufacturing burden.**

---

### 9.3 Candidate Scale Comparison

The nominal diameter difference among the three candidates is relatively modest in absolute terms:

| Candidate | Nominal Propulsor Diameter | Increase Relative to G80 |
|---|---:|---:|
| G80 | 80 mm | — |
| G90 | 90 mm | 10 mm |
| G100 | 100 mm | 20 mm |

However, the complete thruster outside diameter will exceed D_P because additional radial space is required for:

- rotor structure;
- electromagnetic elements;
- electromagnetic clearance;
- stator structure;
- housing;
- rotor support;
- containment;
- duct structure;
- coatings or environmental barriers.

Therefore, a 10 mm increase in propulsor diameter can produce a greater-than-10 mm increase in final material volume, circumference, and overall fabrication burden.

Candidate selection shall consider the complete system rather than nominal propulsor diameter alone.

---

### 9.4 Circumferential Manufacturing Burden

Nominal circumference increases from approximately:

- 251 mm for G80;
- 283 mm for G90;
- 314 mm for G100.

Greater circumference may increase:

- machined surface length;
- composite layup length;
- magnet count or magnetic-element length;
- stator segmentation;
- winding length;
- inspection path length;
- assembly time.

However, larger circumference also permits physically larger individual features.

This can reduce difficulty associated with:

- tiny magnets;
- narrow winding slots;
- miniature fasteners;
- closely spaced supports;
- small sensor features;
- inaccessible assembly regions.

Accordingly, manufacturing burden does not necessarily increase linearly with circumference.

A slightly larger geometry may actually be easier to prototype if it avoids excessively small or congested features.

---

### 9.5 Machining Considerations

Potential machined components may include:

- rotor structural rings;
- stator carriers;
- housing rings;
- support races or guides;
- alignment features;
- mounting structures;
- test fixtures.

For a given machining process, increasing diameter may require:

- larger stock;
- larger workholding;
- greater machine travel;
- more material removal;
- longer cycle time.

Conversely, G80 may require thinner or more tightly packed features that are more difficult to machine accurately.

G90 is not expected to create a substantial increase in conventional prototype machining difficulty relative to G80.

G100 remains physically modest in absolute terms, but its larger final system envelope may begin to increase material and fixture demand more noticeably.

---

### 9.6 Additive-Manufacturing Considerations

Project Triton may use additive manufacturing for development components where appropriate.

Potential applications include:

- propulsor prototypes;
- ducts;
- alignment fixtures;
- housings;
- instrumentation mounts;
- noncritical support components;
- manufacturing aids.

Increasing candidate diameter affects:

- build-envelope utilization;
- print time;
- resin or polymer consumption;
- dimensional distortion;
- shrinkage;
- post-processing.

Larger annular components may also be more sensitive to:

- warping;
- ovality;
- differential cure;
- support-induced distortion.

G80 uses the least build area and material.

G100 uses the most.

G90 retains comparatively modest additive-manufacturing scale while providing more feature space.

No critical rotating or structural component shall be accepted for powered testing solely because it can be additively manufactured.

Material properties, process capability, inspection, and authorized test envelope remain applicable.

---

### 9.7 Resin-Printed Propulsor Development

Smooth propulsor surfaces and complex blade geometry may make resin additive manufacturing useful during hydrodynamic development.

Candidate diameter affects the practical resolution of blade features.

At larger scale, G90 or G100 may permit:

- greater blade-section thickness;
- larger attachment geometry;
- more easily resolved leading and trailing edges;
- improved dimensional inspection;
- greater allowance for reinforcement or inserts.

G80 may place more aggressive geometric demands on:

- thin blade sections;
- blade-root or blade-rim attachment;
- local minimum wall thickness.

However, increasing diameter also increases:

- blade span;
- hydrodynamic moment arms;
- material loading;
- probability of print distortion.

The final propulsor manufacturing method remains controlled by OI-015 and applicable structural analysis.

---

### 9.8 Rotor Manufacturing and Roundness

Annular rotor geometry makes:

- roundness;
- concentricity;
- radial runout;
- axial runout

important manufacturing characteristics.

As diameter increases, maintaining a specified absolute runout may become more difficult because:

- the structure spans a larger circumference;
- workholding becomes more important;
- thermal and curing distortion can accumulate;
- segmented assemblies introduce more interfaces.

G80 therefore has a geometric advantage in absolute roundness control.

G100 potentially has the greatest distortion sensitivity.

G90 provides an intermediate size while retaining substantially more internal packaging room than G80.

This relationship supports treating rotor dimensional stability as a significant discriminator during later detailed design.

---

### 9.9 Segmentation Versus Monolithic Construction

Some annular components may be fabricated:

- monolithically;
- from multiple circumferential segments;
- from layered rings;
- using hybrid manufactured assemblies.

Increasing diameter may make segmented manufacture increasingly attractive.

Segmentation can improve:

- material availability;
- machining access;
- coil installation;
- magnet installation;
- repairability;
- modular development.

However, segmentation introduces:

- alignment interfaces;
- tolerance accumulation;
- joints;
- fasteners or bonding;
- possible structural discontinuities;
- configuration-control complexity.

G80 may more readily support monolithic components.

G100 may provide greater incentive for segmentation.

G90 preserves both options without strongly forcing either manufacturing architecture.

---

### 9.10 Electromagnetic Component Fabrication

The final electromagnetic topology remains unresolved, but the selected geometry must support practical fabrication of:

- coils;
- stator segments;
- magnets or other rotor magnetic elements;
- magnetic back iron;
- retention structures;
- electrical insulation;
- phase connections.

G80 may create manufacturing difficulty if electromagnetic sizing ultimately requires:

- very small pole pitches;
- tightly packed windings;
- narrow structural webs;
- highly constrained phase connections.

G100 provides the most room but may increase:

- component count;
- magnet quantity;
- copper length;
- segmentation;
- material cost.

G90 provides increased component scale without a large increase in system diameter.

---

### 9.11 Rotor-Support Manufacturing

The rotor-support system is expected to be one of the most tolerance-sensitive portions of the prototype.

Manufacturing must eventually control the relative geometry among:

- rotor;
- radial support;
- axial support;
- stator;
- housing;
- containment.

G80 provides the smallest annular package, which may reduce absolute structural distortion but also reduces physical access and support-feature size.

G100 provides the most room for support elements but may require tighter management of:

- large-diameter concentricity;
- support preload;
- housing distortion;
- thermal expansion.

G90 appears likely to provide sufficient support-feature space while maintaining manageable component diameter.

---

### 9.12 Inspection and Metrology

Critical dimensions must be inspectable using available or realistically obtainable measurement methods.

Likely measurements include:

- OD and ID;
- radial thickness;
- axial thickness;
- concentricity;
- circular runout;
- flatness;
- axial runout;
- clearance;
- blade geometry;
- assembled rotor position.

The selected geometry should permit practical use of:

- calipers;
- micrometers;
- bore gauges;
- dial indicators;
- height gauges;
- surface plates;
- coordinate measurement where available;
- optical or 3D scanning where justified.

A geometry that requires inspection capability substantially beyond the manufacturing capability available to the project should be avoided unless necessary for technical feasibility.

---

### 9.13 Tolerance Relative to Feature Size

A fixed absolute manufacturing tolerance represents a larger percentage of a small feature than of a large feature.

Accordingly, increased diameter can provide some relative tolerance advantage.

For example, a 0.1 mm dimensional deviation represents:

- 0.125% of an 80 mm diameter;
- 0.111% of a 90 mm diameter;
- 0.100% of a 100 mm diameter.

This simple comparison does not determine acceptable rotor clearance or electromagnetic gap.

However, it illustrates that slightly increased physical scale may reduce some relative dimensional sensitivity.

The countervailing effect is that larger annular parts may themselves develop greater absolute runout or distortion.

Final tolerances must therefore be established through OI-020 rather than geometric scaling alone.

---

### 9.14 Assembly Access

Prototype assembly may require access for:

- magnetic-element installation;
- winding installation;
- electrical termination;
- support adjustment;
- sensor installation;
- clearance measurement;
- fastener installation;
- inspection.

G80 provides the least available physical space and may become congested.

G100 provides the greatest access.

G90 is expected to provide a meaningful improvement over G80 while retaining a compact package.

Assembly access is especially important because the first prototype is expected to undergo repeated configuration changes rather than remain permanently assembled.

---

### 9.15 Modularity and Replaceable Development Components

Where practical, the initial prototype should allow controlled replacement of:

- propulsor;
- rotor;
- magnetic elements;
- stator or winding assembly;
- support elements;
- duct;
- sensors.

The purpose is to permit engineering iteration without rebuilding the entire thruster.

Candidate geometry should therefore provide sufficient space for:

- detachable interfaces;
- alignment features;
- fasteners;
- removable modules;
- accessible electrical connections.

G80 may impose the greatest packaging challenge for modularity.

G100 provides the greatest physical space but potentially the largest and most expensive replacement components.

G90 provides a favorable compromise.

---

### 9.16 Instrumentation Packaging

Development instrumentation may require accommodation for:

- temperature sensors;
- rotor-speed sensing;
- displacement or clearance sensing;
- vibration sensing;
- electrical measurements;
- water-ingress sensing;
- temporary diagnostic wiring.

A prototype optimized solely for minimum physical size could make instrumentation unnecessarily difficult.

G90 and G100 provide more available packaging space than G80.

However, sensor accommodation alone does not justify larger diameter.

Instrumentation provisions shall be designed deliberately into the selected prototype configuration.

---

### 9.17 Prototype Material Usage and Cost

Material usage generally increases with candidate size.

The expected qualitative trend is:

| Candidate | Material / Component Cost Tendency |
|---|---|
| G80 | Lowest |
| G90 | Intermediate |
| G100 | Highest |

Potential cost drivers include:

- structural material;
- magnetic material;
- copper;
- printed material;
- composite reinforcement;
- machining stock;
- test-fixture material.

The exact cost difference cannot yet be quantified because the complete geometry and electromagnetic topology remain unresolved.

For the present project, cost should be treated as a development constraint rather than the principal optimization objective.

---

### 9.18 Iteration Cost

Prototype engineering typically requires multiple versions.

Therefore, the relevant cost is not merely the cost of one finished thruster.

It includes the cost of:

- failed parts;
- revised parts;
- alternate propulsors;
- alternate ducts;
- alternate rotor structures;
- support experiments;
- electromagnetic revisions.

A geometry that materially increases the cost of every iteration can slow development.

G100 therefore carries a greater iteration-cost risk.

G80 minimizes part size but could incur additional iterations if packaging is too constrained.

G90 may reduce the risk of expensive redesign caused by insufficient initial packaging while avoiding the largest material penalty.

---

### 9.19 Test-Fixture Manufacturing

The selected prototype geometry also affects the test hardware.

Larger geometry may require:

- larger mounting plates;
- longer structural members;
- larger guards;
- larger containment;
- increased water-tank clearance;
- larger instrumentation fixtures.

The thrust load itself remains common among candidates, but fixture **geometry** increases with thruster size.

G80 therefore offers the smallest fixture envelope.

G90 remains practical.

G100 creates the largest test-infrastructure burden.

---

### 9.20 Configuration Control

Because Project Triton will likely compare multiple development configurations, each test article must be distinguishable by controlled geometry.

At minimum, configuration records should eventually identify:

- D_P;
- propulsor revision;
- blade geometry revision;
- rotor revision;
- stator revision;
- electromagnetic configuration;
- duct revision;
- support configuration;
- applicable clearances;
- materials;
- manufacturing process.

The selected principal geometry should therefore use stable datum definitions and measurable reference features.

PT-AN-002 shall establish the system envelope; subsequent CAD and manufacturing records shall preserve the detailed configuration.

---

### 9.21 Manufacturing Risk by Candidate

The principal candidate-specific manufacturing risks are:

#### G80

Primary risks:

- constrained internal space;
- small electromagnetic features;
- tight assembly access;
- potentially demanding clearance-to-feature-size relationship;
- greater risk of packaging conflict discovered late.

Primary benefit:

- smallest component and material scale.

#### G90

Primary risks:

- moderate increase in material usage;
- moderate increase in annular dimensional-control burden.

Primary benefits:

- larger workable features;
- improved access;
- more packaging margin;
- still modest absolute prototype size.

#### G100

Primary risks:

- greatest material usage;
- greatest runout/distortion sensitivity;
- largest fixture requirements;
- largest iteration cost;
- potentially increased segmentation complexity.

Primary benefit:

- greatest physical manufacturing and assembly space.

---

### 9.22 Manufacturing and Prototype Candidate Assessment

Based on the current prototype-development basis:

| Criterion | G80 | G90 | G100 |
|---|---|---|---|
| Material usage | Very Favorable | Favorable | Moderate |
| Part size | Very Favorable | Very Favorable | Favorable |
| Internal packaging freedom | Moderate | Very Favorable | Very Favorable |
| Assembly access | Moderate | Very Favorable | Very Favorable |
| Electromagnetic feature scale | Moderate | Very Favorable | Very Favorable |
| Rotor roundness / distortion burden | Very Favorable | Favorable | Moderate |
| Metrology practicality | Favorable | Very Favorable | Favorable |
| Support-system fabrication space | Moderate | Very Favorable | Very Favorable |
| Instrumentation packaging | Moderate | Very Favorable | Very Favorable |
| Iteration cost | Very Favorable | Favorable | Moderate |
| Test-fixture scale | Very Favorable | Favorable | Moderate |
| Overall prototype manufacturability | Favorable | Very Favorable | Favorable |

---

### 9.23 Manufacturing and Prototype Finding

No candidate is eliminated by prototype manufacturing considerations.

**G80** offers the lowest material and fixture burden, but its compact geometry increases the risk of internal packaging congestion, difficult assembly access, and late discovery that electromagnetic or rotor-support features cannot be manufactured conveniently.

**G100** offers excellent physical working space but increases material usage, annular dimensional-control burden, iteration cost, test-fixture scale, and likely rotor manufacturing complexity.

**G90** increases nominal diameter by only 10 mm relative to G80 while providing materially greater space for:

- electromagnetic features;
- rotor support;
- assembly;
- inspection;
- instrumentation;
- replaceable development components.

Accordingly, the preliminary manufacturing/prototype ranking is:

1. **G90 — strongest overall prototype-development balance**
2. **G80 — lowest cost and smallest scale but greater packaging risk**
3. **G100 — highly workable geometry but greater material, dimensional-control, and iteration burden**

The independent evaluations completed to this point therefore produce the following convergence:

| Evaluation Area | Preferred Candidate |
|---|---|
| Hydrodynamic balance | G90 |
| Electromagnetic packaging balance | G90 |
| Mechanical / structural balance | G90 |
| Manufacturing / prototype balance | G90 |

This convergence provides a strong basis for treating **G90 as the leading integrated candidate**.

However, G90 shall not become the selected Project Triton geometry until the explicit multi-criteria trade is completed in Section 10.

---

## 10. Candidate Geometry Trade

### 10.1 Purpose

This section integrates the hydrodynamic, electromagnetic-packaging, mechanical/structural, and manufacturing/prototype assessments developed in Sections 6 through 9.

The objective is to select the nominal propulsor diameter that provides the strongest overall system-level basis for the initial RDT-80 prototype.

The trade shall compare:

- **G80 — 80 mm nominal propulsor diameter**
- **G90 — 90 mm nominal propulsor diameter**
- **G100 — 100 mm nominal propulsor diameter**

The decision shall not be based on any single discipline.

The preferred candidate must provide a credible path to satisfying:

- the 7.0 kgf / 68.6 N continuous forward static-thrust requirement;
- the 10.0 kgf / 98.1 N peak forward static-thrust requirement;
- the approved annular rim-driven architecture;
- practical electromagnetic development;
- practical rotor support and structural design;
- practical manufacturing and inspection;
- controlled prototype testing; and
- future configuration development.

---

### 10.2 Trade Method

A numerical weighted-score model is not used at this stage.

Assigning precise numerical weights to hydrodynamic, electromagnetic, structural, manufacturing, and test considerations would create false precision because:

- final propulsor geometry is unresolved;
- required rotor RPM and torque are unresolved;
- electromagnetic topology is unresolved;
- rotor-support architecture is unresolved;
- material selection is unresolved;
- final manufacturing processes are unresolved.

Instead, the trade uses an evidence-based qualitative comparison.

The following ratings are used:

| Rating | Interpretation |
|---|---|
| Very Favorable | Strong system-level advantage |
| Favorable | Positive trade contribution with manageable disadvantages |
| Moderate | Acceptable but with meaningful penalties or uncertainty |
| Unfavorable | Significant disadvantage for the initial prototype |
| Very Unfavorable | Disproportionate disadvantage or development risk |

The trade shall also consider whether a candidate offers a **balanced solution** or merely maximizes one particular characteristic.

---

### 10.3 Integrated Evaluation Criteria

The principal integrated criteria are:

1. **Hydrodynamic feasibility and margin**
2. **Electromagnetic packaging and torque opportunity**
3. **Rotor-support and structural feasibility**
4. **Manufacturing and assembly practicality**
5. **Prototype testability**
6. **Compactness**
7. **Rotor mass and inertia tendency**
8. **Clearance and tolerance manageability**
9. **Instrumentation and development access**
10. **Material and iteration cost**
11. **Scalability and technical development value**
12. **Overall integration risk**

These criteria are not independent.

For example:

- increased diameter improves hydrodynamic loading but increases structural span;
- increased circumference improves electromagnetic packaging but increases rotor material;
- increased size improves assembly access but increases fixture burden;
- reduced compactness may improve development margin but weaken the value of demonstrating a compact rim-driven system.

The decision shall therefore consider coupled effects.

---

### 10.4 Integrated Candidate Matrix

| Criterion | G80 | G90 | G100 |
|---|---|---|---|
| Hydrodynamic feasibility | Favorable | Very Favorable | Very Favorable |
| Disk-loading margin | Moderate | Favorable | Very Favorable |
| Ideal induced-power burden | Moderate | Favorable | Very Favorable |
| Electromagnetic circumference | Moderate | Very Favorable | Very Favorable |
| Electromagnetic torque-radius opportunity | Moderate | Very Favorable | Very Favorable |
| Winding / magnetic packaging freedom | Moderate | Very Favorable | Very Favorable |
| Rotor-support packaging | Moderate | Very Favorable | Very Favorable |
| Structural compactness | Very Favorable | Very Favorable | Moderate |
| Rotor mass tendency | Very Favorable | Favorable | Moderate |
| Rotor inertia tendency | Very Favorable | Favorable | Moderate |
| Clearance / tolerance practicality | Favorable | Very Favorable | Favorable |
| Manufacturing practicality | Favorable | Very Favorable | Favorable |
| Assembly access | Moderate | Very Favorable | Very Favorable |
| Instrumentation packaging | Moderate | Very Favorable | Very Favorable |
| Material usage | Very Favorable | Favorable | Moderate |
| Iteration cost | Very Favorable | Favorable | Moderate |
| Test-fixture scale | Very Favorable | Favorable | Moderate |
| Compact high-performance development value | Very Favorable | Very Favorable | Favorable |
| Overall integration flexibility | Favorable | Very Favorable | Favorable |
| Overall initial-prototype risk | Favorable | Very Favorable | Moderate |

The matrix demonstrates that all three candidates remain technically credible.

However, their advantages are distributed differently.

---

### 10.5 G80 Integrated Assessment

G80 retains several important advantages.

It is:

- the smallest candidate;
- the least material-intensive;
- likely to have the lowest rotor mass;
- likely to have the lowest rotor inertia;
- the easiest to accommodate in a compact test fixture;
- the closest dimensional match to the Hydromea DISKDRIVE 80 benchmark;
- the most consistent with the historical RDT-80 designation.

These are substantial benefits.

However, G80 also combines the greatest concentration of design constraints.

It has:

- the highest disk loading;
- the highest ideal induced-power requirement;
- the least available circumference;
- the smallest effective torque radius;
- the least electromagnetic packaging freedom;
- the least rotor-support packaging space;
- the least assembly and instrumentation space.

G80 would therefore require the project to solve several difficult compact-packaging problems simultaneously.

This may be technically valuable, but it increases the likelihood that the initial integrated prototype is constrained by physical packaging before the underlying rim-drive technologies have been adequately characterized.

**Integrated assessment: Favorable**

G80 shall remain a credible compact alternative and a useful basis for future optimization, but it is not the preferred initial prototype geometry.

---

### 10.6 G100 Integrated Assessment

G100 provides the greatest hydrodynamic and electromagnetic geometric margin.

It offers:

- the lowest disk loading;
- the lowest ideal induced-power requirement;
- the greatest nominal circumference;
- the greatest torque radius;
- the greatest winding and magnetic-element packaging freedom;
- the greatest space for support and instrumentation;
- potentially the lowest required hydrodynamic and electromagnetic loading for the selected thrust objective.

These are meaningful advantages.

However, G100 also introduces the largest penalties in:

- rotor size;
- expected material usage;
- rotor mass tendency;
- rotor inertia tendency;
- annular structural span;
- runout and distortion management;
- containment envelope;
- test-fixture scale;
- iteration cost;
- departure from the compact approximately 80 mm-class development concept.

The hydrodynamic improvement from G90 to G100 is also relatively modest compared with the physical-size increase.

For example, relative to G90, increasing nominal diameter to G100 reduces ideal induced power by only approximately:

- 16 W at the 7 kgf operating point; and
- 28 W at the 10 kgf operating point.

Those ideal-power savings are useful but do not presently justify the additional system-scale penalties for the initial prototype.

**Integrated assessment: Favorable**

G100 shall remain an important higher-margin geometry and a potential future scaling configuration, but it is not the preferred first integrated prototype.

---

### 10.7 G90 Integrated Assessment

G90 provides an intermediate physical scale while capturing a substantial portion of the technical benefit of G100.

Relative to G80, G90 provides approximately:

- 12.5% greater nominal diameter;
- 26.6% greater disk area;
- 21% lower disk loading;
- 11% lower ideal induced power;
- 12.5% greater circumference;
- 12.5% greater nominal torque radius;
- approximately 27% greater simplified D² electromagnetic geometry index.

The absolute increase in nominal propulsor diameter is only:

**10 mm**

This modest increase provides additional physical margin for:

- electromagnetic elements;
- winding space;
- rotor structure;
- rotor support;
- retention features;
- assembly;
- instrumentation;
- inspection.

At the same time, G90 avoids the full penalties associated with G100 in:

- rotor size;
- inertia;
- structural span;
- material usage;
- test-fixture scale;
- iteration cost.

G90 therefore does not maximize any single parameter.

Instead, it provides the strongest overall balance among the competing system objectives.

**Integrated assessment: Very Favorable**

---

### 10.8 Cross-Discipline Convergence

The individual discipline assessments produced the following results:

| Evaluation Area | First-Ranked Candidate |
|---|---|
| Hydrodynamic balance | G90 |
| Electromagnetic packaging balance | G90 |
| Mechanical / structural balance | G90 |
| Manufacturing / prototype balance | G90 |
| Integrated system trade | G90 |

This convergence is important.

G90 is not being selected because one discipline dominates the trade.

It emerges as the preferred candidate independently across all four principal engineering areas evaluated to date.

That result provides stronger justification than a weighted score based on unsupported numerical weighting factors.

---

### 10.9 Sensitivity of the Decision

The G90 recommendation is not expected to be invalidated by small changes in the current preliminary assumptions.

For G80 to become preferable, subsequent analysis would likely need to demonstrate that the additional compactness produces a substantial system-level advantage and that:

- hydrodynamic loading;
- required RPM;
- electromagnetic torque density;
- winding space;
- rotor-support packaging

remain comfortably achievable.

For G100 to become preferable, subsequent analysis would likely need to demonstrate that the additional diameter produces a substantial improvement in:

- efficiency;
- cavitation margin;
- required RPM;
- electromagnetic loading;
- thermal performance; or
- structural feasibility

that outweighs its size, mass, inertia, cost, and test penalties.

Neither condition is supported by the current evidence.

Accordingly, G90 appears robust as the present system-level selection.

---

### 10.10 Selection Decision

The recommended nominal propulsor diameter for the initial Project Triton prototype is:

**D_P = 90 mm**

The selected candidate designation is:

**G90**

This selection establishes the nominal propulsor diameter for subsequent system-level sizing.

It does not yet establish:

- final manufactured blade-tip diameter;
- blade count;
- blade pitch;
- blade twist;
- blade section;
- rotor inner diameter;
- rotor outer diameter;
- stator dimensions;
- electromagnetic gap;
- duct profile;
- rotor-support dimensions;
- final outer system diameter;
- final axial system length.

Those dimensions remain subject to the applicable downstream analyses identified in PT-AN-002.

---

### 10.11 G80 and G100 Disposition

G80 and G100 shall not be discarded.

Their disposition is:

| Candidate | Disposition |
|---|---|
| G80 | Retain as compact reference / potential later optimization configuration |
| G90 | Select as initial principal prototype diameter |
| G100 | Retain as higher-margin / scaling reference configuration |

These alternatives remain useful for:

- sensitivity analysis;
- future performance scaling;
- electromagnetic comparison;
- hydrodynamic comparison;
- later-generation prototype development.

No future geometry change shall occur implicitly.

A change from the selected G90 basis shall be documented through configuration control and supported by engineering evidence.

---

### 10.12 RDT-80 Designation Decision

The selection of a 90 mm nominal propulsor diameter means that the project designation:

**RDT-80**

shall no longer be interpreted as a controlled requirement for exactly 80 mm propulsor diameter.

For the present Project Triton development effort:

**RDT-80 shall be retained as the historical project / prototype-family designation.**

The controlled nominal propulsor diameter shall instead be established by:

- PT-AN-002;
- PT-REQ-001 when the applicable requirement is updated; and
- configuration-controlled CAD and design records.

If a future formal product or configuration naming scheme is adopted, the designation may be revised through configuration control.

The geometry shall not be degraded or constrained merely to preserve the literal numerical meaning of the historical name.

---

### 10.13 Geometry-Trade Decision Summary

The integrated trade result is:

> **Select G90 — 90 mm nominal propulsor diameter — as the principal geometry basis for the initial Project Triton RDT-80 prototype.**

The decision basis is:

- substantially reduced hydrodynamic loading relative to G80;
- increased annular electromagnetic packaging and torque opportunity;
- improved rotor-support and assembly packaging;
- manageable structural size;
- practical prototype manufacturing;
- manageable material and test-fixture burden;
- preservation of a compact small-thruster development scale;
- strong cross-discipline convergence.

G90 therefore provides the strongest current balance between:

**performance margin**

and:

**prototype complexity.**

The next section shall use the selected 90 mm propulsor diameter to establish which remaining principal geometry parameters can be selected, bounded, or transferred to downstream engineering work.

---

## 11. Recommended Principal Geometry

### 11.1 Purpose

This section converts the integrated trade decision from Section 10 into the principal geometry basis for subsequent Project Triton engineering.

The objective is to establish only those dimensions and geometric relationships that are supported by the present evidence.

Where sufficient technical basis does not yet exist, the parameter shall remain:

- bounded for downstream packaging analysis;
- dependent on another controlled engineering decision; or
- explicitly transferred to the applicable open issue.

No unsupported nominal dimension shall be introduced merely to complete the geometry table.

---

### 11.2 Selected Nominal Propulsor Diameter

The selected nominal propulsor diameter for the initial Project Triton prototype is:

**D_P = 90 mm**

This is a **Class A — Select in PT-AN-002** geometry decision.

The selected configuration is:

**G90**

This dimension shall become the common reference for subsequent:

- hydrodynamic analysis;
- propulsor development;
- rotor sizing;
- electromagnetic packaging;
- structural sizing;
- support-system development;
- system-level CAD;
- test-fixture planning.

The 90 mm value represents the nominal hydrodynamic propulsor diameter.

The final manufactured blade-tip, blade-to-rotor, or rotating-envelope dimensions may differ slightly where required by detailed design, but any such difference shall be explicitly documented and configuration controlled.

---

### 11.3 RDT-80 Designation

The historical designation:

**RDT-80**

shall be retained for the Project Triton prototype family.

It shall not be interpreted as a dimensional requirement that fixes D_P at 80 mm.

The controlled geometry shall be defined by the approved engineering documents and CAD configuration.

Accordingly:

**RDT-80 = project / prototype-family designation**

while:

**D_P = 90 mm = selected initial prototype nominal propulsor diameter**

A future configuration-naming convention may be established if multiple diameter variants are developed.

---

### 11.4 Central Flow Passage

The selected architecture shall preserve a substantially unobstructed central propulsion flow passage without a conventional:

- propulsion shaft;
- shaft-support strut system;
- central gearbox;
- centrally mounted propulsion motor.

The rotating propulsor blades are permitted within this passage and are not considered an architectural obstruction.

The exact value of **D_FP** shall not yet be fixed.

Its final value depends on:

- blade inner and outer geometry;
- blade-to-rotor attachment;
- rotor inner geometry;
- duct throat geometry;
- hydrodynamic transition geometry.

Accordingly:

**D_FP — Class C: define through subsequent propulsor and rotor development**

The central flow passage shall remain as large as practical within the selected 90 mm propulsor architecture without compromising required blade, rotor, support, or structural geometry.

---

### 11.5 Propulsor-to-Rotor Relationship

The propulsor shall transfer torque and hydrodynamic load directly to the annular rotor.

The selected principal relationship is therefore:

**propulsor → annular rotor → electromagnetic drive**

with no intermediate central propulsion shaft or gearbox.

The outer region of the propulsor shall interface structurally with the rotating annulus.

However, PT-AN-002 shall not require:

**D_RI = D_P**

because the detailed interface may require allowances for:

- blade attachment;
- structural reinforcement;
- rotor liners;
- hydrodynamic transitions;
- manufacturing tolerances;
- environmental coatings;
- encapsulation;
- retention features.

Accordingly:

**D_RI — Class C: derive from the 90 mm propulsor and blade-to-rotor interface**

The final D_RI shall be established during coordinated OI-015, OI-006, OI-007, and structural development.

---

### 11.6 Rotor Radial Build

The rotor radial build must ultimately accommodate:

- structural load transfer;
- electromagnetic rotor elements;
- magnetic flux-return structure where applicable;
- electromagnetic-element retention;
- environmental protection;
- radial-support interfaces;
- required mechanical clearances.

The present analysis does not provide sufficient basis to select a final value for:

- **D_RO**; or
- **t_R**.

These dimensions depend strongly upon electromagnetic topology and rotor construction.

Accordingly:

**D_RO — Class C: establish during electromagnetic topology development**

**t_R — Class C: establish through OI-004, OI-006, OI-007, and OI-012**

The system-level CAD envelope shall reserve radial space for the rotor rather than assume a final thin-ring geometry.

---

### 11.7 Electromagnetic Packaging Envelope

The selected 90 mm geometry shall preserve sufficient radial and axial space to evaluate multiple annular motor arrangements before OI-004 is closed.

The geometry shall not yet assume:

- radial-flux topology;
- axial-flux topology;
- transverse-flux topology;
- a specific pole count;
- a specific magnet thickness;
- a specific stator tooth depth;
- a specific winding depth.

Accordingly:

- **D_SI — Class C**
- **D_SO — Class C**
- **t_S — Class C**
- **L_S — Class C**
- **g_EM — Class C**

These parameters shall be established through electromagnetic and mechanical-clearance analysis.

The system-level envelope shall preserve sufficient development space that the 90 mm propulsor selection does not artificially force a single motor topology.

---

### 11.8 Electromagnetic Clearance

No numerical value for **g_EM** shall be established in PT-AN-002.

The final electromagnetic clearance must consider:

- magnetic performance;
- rotor runout;
- stator concentricity;
- support deflection;
- manufacturing tolerance;
- thermal expansion;
- structural deformation;
- protective coatings or encapsulation;
- debris tolerance;
- rotor-dynamic behavior.

Accordingly:

**g_EM — Class C: controlled by OI-004, OI-005, OI-006, OI-011, and OI-020**

Any early CAD model shall identify g_EM as a controlled placeholder dimension rather than an approved operating gap.

---

### 11.9 Mechanical Operating Clearances

No final numerical value shall yet be established for:

- **C_R — radial mechanical clearance**
- **C_A — axial mechanical clearance**

Both remain dependent upon:

- radial-support architecture;
- axial-support architecture;
- material selection;
- manufacturing capability;
- rotor runout;
- structural deformation;
- thermal effects;
- rotor dynamics.

Accordingly:

**C_R — Class C**

**C_A — Class C**

These values shall ultimately be established through OI-008, OI-009, OI-011, OI-012, and OI-020.

Physical allowance for these clearances shall nevertheless be preserved in all subsequent system packaging.

---

### 11.10 Duct Geometry

The duct shall remain an integral part of the principal system geometry.

The selected 90 mm propulsor diameter establishes the reference scale for subsequent duct development.

However, PT-AN-002 does not provide sufficient evidence to select:

- inlet-lip profile;
- throat geometry;
- outlet profile;
- diffuser angle;
- blade-to-duct relationship;
- duct axial length;
- exact internal diameter.

Accordingly:

- **D_DI — Class C**
- **L_D — Class C**

These dimensions shall be established principally through OI-015 hydrodynamic development.

The duct shall be developed together with the propulsor rather than treated as an independent cosmetic housing feature.

---

### 11.11 Preliminary Outer-Diameter Packaging Objective

The complete thruster outside diameter must include the radial build associated with:

- the 90 mm propulsor;
- annular rotor;
- electromagnetic clearance;
- stator;
- structural housing;
- containment;
- environmental protection;
- applicable support geometry.

Current architecture-comparable and rim-drive benchmark data indicate that the external envelope can be substantially larger than the propulsor diameter.

However, the published benchmark geometries use different motor, duct, structural, and packaging approaches and shall not be treated as directly scalable designs.

For the next stage of Project Triton development, the outside diameter shall therefore be treated as a **packaging objective rather than an approved requirement**.

The initial system-level CAD study shall investigate whether the G90 architecture can be contained within approximately:

**140–160 mm overall outside diameter**

without compromising:

- electromagnetic feasibility;
- structural stiffness;
- rotor support;
- containment;
- clearance;
- environmental protection.

Accordingly:

**D_DO — Class B: preliminary system packaging study range of approximately 140–160 mm**

This range is not a final dimensional requirement.

If subsequent engineering demonstrates that a technically credible system requires an outside diameter outside this range, the geometry shall be revised using documented engineering evidence rather than forcing the design to remain within an arbitrary envelope.

---

### 11.12 Axial Geometry

The present evidence does not support selection of a final:

- rotor axial length;
- stator axial length;
- duct axial length; or
- complete thruster axial length.

These dimensions depend strongly on:

- electromagnetic topology;
- required torque;
- propulsor RPM;
- rotor support;
- axial thrust reaction;
- duct hydrodynamics;
- structural arrangement;
- instrumentation.

Accordingly:

- **L_R — Class C**
- **L_S — Class C**
- **L_D — Class C**
- **L_SYS — Class C**

The next system-level CAD study shall reserve sufficient axial packaging space for all principal functions without imposing a final length requirement.

Compact axial packaging remains desirable, but no arbitrary maximum axial length is established by PT-AN-002.

---

### 11.13 Rotor-Support Allowance

The geometry shall explicitly reserve space for both:

- radial rotor support; and
- axial rotor support / thrust reaction.

These functions shall not be treated as details to be inserted after the electromagnetic geometry has been completed.

The principal geometry shall therefore preserve physical regions capable of accommodating:

- radial positioning elements;
- axial reaction elements;
- alignment features;
- replaceable wear components where applicable;
- preload or adjustment features where applicable;
- inspection access.

Exact support dimensions remain controlled by OI-008 and OI-009.

---

### 11.14 Containment Allowance

The system geometry shall preserve a structurally credible external load path capable of supporting the eventual containment strategy required by OI-010.

The initial CAD envelope shall therefore avoid using all available radial thickness for electromagnetic components.

Space must remain available for:

- structural housing;
- rotor-fragment restraint;
- impact-resistant material;
- mounting load transfer.

The final containment thickness cannot be established until rotor mass, RPM, material, and credible failure modes are defined.

---

### 11.15 Mounting Envelope

No final mounting interface shall be selected by PT-AN-002.

However, the G90 geometry shall preserve externally accessible stationary structure suitable for:

- restrained thrust testing;
- torque reaction;
- alignment;
- repeatable installation;
- instrumentation;
- future vehicle integration.

The mounting system shall transfer loads through stationary structure and shall not rely on the hydrodynamic duct alone unless the duct is deliberately designed and verified as a structural member.

Accordingly:

**E_MNT — Class C: establish during system CAD and OI-019 test-interface development**

---

### 11.16 Recommended Geometry Disposition

The principal geometry parameters are dispositioned as follows:

| Parameter | Recommended Disposition |
|---|---|
| C_A — Axial mechanical clearance | Class C — support / tolerance decision |
| C_R — Radial mechanical clearance | Class C — support / tolerance decision |
| E_MNT — Mounting envelope | Class C — CAD / test-interface development |
| D_DI — Duct internal diameter | Class C — hydrodynamic development |
| D_DO — Overall duct / housing outside diameter | **Class B — investigate approximately 140–160 mm packaging range** |
| D_FP — Central flow-passage diameter | Class C — derive with propulsor and rotor geometry |
| D_P — Nominal propulsor diameter | **Class A — Select 90 mm** |
| D_RI — Rotor inner diameter | Class C — derive from 90 mm propulsor interface |
| D_RO — Rotor outer diameter | Class C — downstream EM packaging decision |
| D_SI — Stator inner diameter | Class C — topology dependent |
| D_SO — Stator outer diameter | Class C — downstream EM packaging decision |
| g_EM — Electromagnetic clearance | Class C — downstream EM / clearance decision |
| L_D — Duct axial length | Class C — hydrodynamic development |
| L_R — Rotor axial length | Class C — downstream EM / structural decision |
| L_S — Stator axial length | Class C — topology dependent |
| L_SYS — Overall system axial length | Class C — establish through integrated CAD packaging |
| t_R — Rotor radial thickness | Class C — downstream EM / structural decision |
| t_S — Stator radial thickness | Class C — topology dependent |

---

### 11.17 Recommended System-Level Geometry Basis

The initial Project Triton prototype shall therefore proceed using the following system-level geometric basis:

**Nominal propulsor diameter: 90 mm**

**Architecture: annular rim-driven, direct-drive, central-shaft-free propulsion system**

**Propulsor: directly coupled structurally to the annular rotor**

**Central passage: preserved without conventional central propulsion-drive obstruction**

**Outer-diameter study envelope: approximately 140–160 mm for initial packaging analysis**

**Rotor, stator, clearance, duct-profile, support, and axial dimensions: deliberately unresolved pending their controlling engineering analyses**

This definition is sufficiently specific to establish the next controlled system-level CAD and analytical studies while avoiding unsupported detailed dimensions.

---

### 11.18 Geometry Maturity Finding

PT-AN-002 has established the first principal geometric dimension required for continued engineering development:

**D_P = 90 mm**

The remaining unresolved dimensions do not invalidate this selection.

Instead, they represent the normal downstream sizing work required to convert the selected system scale into a complete design.

The next technical sequence should therefore use G90 as the fixed nominal propulsor reference while determining:

1. detailed hydrodynamic propulsor geometry;
2. required rotor RPM and torque;
3. electrical-power envelope;
4. electromagnetic topology and dimensions;
5. rotor-support geometry;
6. structural and containment geometry;
7. final system envelope.

The G90 selection shall be reconsidered only if one of those analyses identifies a substantive incompatibility that cannot be resolved within a practical system envelope.

---

## 12. Requirements Impact

### 12.1 Purpose

This section identifies the effect of the PT-AN-002 geometry decision on the current Project Triton system requirements and controlled open decisions.

The principal new design decision established by PT-AN-002 is:

**D_P = 90 mm nominal propulsor diameter**

for the initial Project Triton prototype.

This decision should be incorporated into PT-REQ-001 so that the selected prototype scale is controlled independently of the historical RDT-80 project designation.

PT-AN-002 does not provide sufficient basis to establish final numerical requirements for:

- rotor inner diameter;
- rotor outer diameter;
- stator dimensions;
- electromagnetic clearance;
- mechanical clearances;
- duct profile;
- complete outside diameter;
- complete axial length;
- rotor-support dimensions.

Those parameters shall remain controlled by their applicable downstream open issues.

---

### 12.2 Requirement-Change Philosophy

The geometry analysis distinguishes between:

1. a **selected design requirement** that should now be controlled;
2. existing requirements whose wording remains valid;
3. existing requirements that require later numerical refinement.

The selected 90 mm propulsor diameter is sufficiently mature to become a controlled system requirement.

The remaining preliminary geometry ranges are not sufficiently mature to become fixed numerical requirements.

In particular, the approximately 140–160 mm outside-diameter range identified in Section 11 is a:

**design-study packaging objective**

and shall **not** be converted into a mandatory system requirement at this stage.

---

### 12.3 New Derived Geometry Requirement

PT-REQ-001 should add the next available system requirement:

**SR-083**

with the following proposed wording:

> **SR-083 — The initial RDT-80 prototype shall use a nominal propulsor diameter of 90 mm.**

Recommended verification method:

**VM-001 — Inspection**

Rationale:

The nominal propulsor diameter is a directly inspectable configuration characteristic rather than a performance quantity requiring powered testing.

The final manufactured configuration may contain detailed blade, rotor-interface, or tolerance features that differ slightly from the nominal hydrodynamic reference diameter, but the controlled configuration shall identify the nominal propulsor diameter as:

**90 mm**

Any future change to that nominal value shall require documented configuration control and engineering justification.

---

### 12.4 SR-057 Impact

SR-057 currently requires configuration control of the principal propulsor and duct geometry.

PT-AN-002 strengthens the technical basis for SR-057 but does not require its fundamental intent to change.

SR-057 shall continue to control the applicable principal geometry.

After SR-083 is added, the requirement relationship shall be:

- **SR-083** establishes the selected nominal propulsor diameter;
- **SR-057** requires the principal propulsor and duct geometry to remain configuration controlled.

The requirements therefore perform different functions and should remain separate.

No numerical duct diameter shall be added to SR-057 at this stage.

---

### 12.5 Performance Requirements

PT-AN-002 does not change the established thrust requirements.

The following requirements remain unchanged:

**SR-054**

- not less than 7.0 kgf / 68.6 N continuous forward static thrust.

**SR-055**

- not less than 10.0 kgf / 98.1 N peak forward static thrust.

The selected 90 mm geometry becomes part of the design basis used to satisfy these requirements.

The thrust requirements shall not be reduced merely because a particular prototype geometry has been selected.

---

### 12.6 Architectural Requirements

The following architecture-related requirements remain applicable without wording change:

- **SR-005** — preservation of the central flow passage without a conventional central propulsion shaft, shaft-support structure, or centrally mounted drive motor;
- **SR-008** — required separation between rotating and stationary structure;
- **SR-010** — structural alignment and dimensional stability.

PT-AN-002 clarifies the interpretation of the central flow passage but does not alter the approved architecture.

The 90 mm geometry therefore remains subordinate to the DR-002 architecture baseline.

---

### 12.7 Propulsor Requirements

SR-062 remains applicable without wording change.

Selection of:

**D_P = 90 mm**

does not establish:

- blade count;
- blade chord;
- pitch;
- twist;
- blade section;
- solidity;
- detailed blade-to-rotor attachment.

Those parameters remain subject to OI-015 and shall be configuration controlled before formal thrust verification as required by SR-062.

Accordingly:

**SR-062 — no wording change at this stage.**

---

### 12.8 Electromagnetic Requirements

The selected G90 geometry affects the physical basis for electromagnetic development but does not yet establish final electromagnetic performance or dimensions.

Accordingly:

- **SR-063 — no wording change**
- **SR-066 — no wording change**
- **SR-067 — no wording change**

Subsequent resolution of OI-003 through OI-007 may require additional derived numerical requirements for:

- torque;
- rotor speed;
- voltage;
- current;
- power;
- electromagnetic gap;
- magnetic-element retention.

Those requirements shall not be invented in PT-AN-002.

---

### 12.9 Manufacturing and Tolerance Requirements

The following existing requirements remain applicable:

- **SR-047** — critical dimensions, fits, clearances, and alignment features must be manufacturable and inspectable;
- **SR-049** — manufacturing and assembly tolerances must preserve required geometric relationships.

The G90 selection does not yet provide sufficient technical basis to establish numerical tolerances.

Accordingly:

**SR-047 — no wording change**

**SR-049 — no wording change**

Numerical tolerances shall be developed through OI-011 and OI-020 after the rotor-support and electromagnetic geometry are sufficiently mature.

---

### 12.10 Requirement Traceability for SR-083

The proposed new requirement shall initially trace to:

- **PT-AN-002 — Principal Prototype Geometry Analysis**
- **OI-002 — Principal Prototype Geometry**
- **RK-007 — Hydrodynamic / thrust / cavitation performance**
- **RK-001 — Electromagnetic feasibility / performance**
- **RK-002 — Rotor-support positioning**
- **RK-003 — Clearance and tolerance**
- **RK-008 — Structural deformation / alignment**
- **RK-009 — Manufacturing feasibility**

Recommended verification:

**VM-001 — Inspection**

The final PT-REQ-001 traceability table shall be updated when SR-083 is formally added.

---

### 12.11 OI-002 Status

PT-AN-002 has resolved the most important first-order scale decision associated with OI-002:

**nominal propulsor diameter = 90 mm**

However, OI-002 also concerns principal prototype geometry more broadly.

Several system-level geometry parameters remain unresolved, including:

- rotor inner and outer diameter;
- rotor radial build;
- stator radial build;
- electromagnetic clearance;
- final duct dimensions;
- overall outside diameter;
- overall axial envelope;
- support clearances.

Accordingly, OI-002 shall not yet be closed.

Recommended status:

**OI-002 — Open — Resolution in Progress**

The issue may be closed after the remaining principal system-envelope dimensions are either:

1. established; or
2. formally transferred to controlled downstream design decisions with sufficient interface definition.

---

### 12.12 ORD-016 Impact

ORD-016 is the controlled open decision associated with OI-002 principal geometry.

PT-AN-002 materially advances that decision by selecting the nominal propulsor diameter.

However, the complete principal geometry is not yet resolved.

Accordingly, the recommended status is:

**ORD-016 — Partially Resolved**

The decision basis recorded for ORD-016 should identify:

- **90 mm nominal propulsor diameter selected**
- G80 retained as compact reference;
- G100 retained as higher-margin scaling reference;
- remaining rotor, stator, duct, clearance, and axial geometry transferred to their controlling downstream analyses.

ORD-016 shall remain partially resolved until the remaining system-level geometry dependencies are dispositioned.

---

### 12.13 Other Open Decisions

PT-AN-002 does not resolve the following downstream decisions:

- operating voltage and power envelope;
- electromagnetic topology;
- stator and winding geometry;
- rotor magnetic circuit;
- magnetic-element retention;
- radial support;
- axial support;
- operating clearance;
- material selection;
- thermal management;
- detailed propulsor geometry;
- manufacturing tolerances.

Their associated open decisions shall remain open.

PT-AN-002 provides a common **90 mm nominal propulsor basis** for resolving them.

---

### 12.14 No Requirement for the Preliminary Outside-Diameter Range

The preliminary:

**140–160 mm**

outside-diameter study range identified in Section 11 shall not be placed into PT-REQ-001 as an approved numerical requirement.

The range exists to guide the next packaging analysis.

It may be:

- narrowed;
- expanded;
- or replaced

when electromagnetic, structural, rotor-support, containment, and environmental-protection requirements are better defined.

Prematurely converting this range into a requirement could force later subsystem designs into an unsupported envelope.

---

### 12.15 Configuration-Control Effect

Once SR-083 is incorporated into PT-REQ-001, the 90 mm nominal propulsor diameter shall be treated as part of the controlled prototype design basis.

A future proposed change to:

- 80 mm;
- 100 mm;
- or another nominal diameter

shall require evaluation of its effect on at least:

- thrust performance;
- hydrodynamic loading;
- rotor RPM and torque;
- electromagnetic design;
- structural design;
- rotor support;
- thermal performance;
- manufacturing;
- test configuration.

The diameter shall therefore no longer be an informal CAD choice.

---

### 12.16 Requirements Impact Summary

The requirements impact from PT-AN-002 is:

| Item | Recommended Action |
|---|---|
| SR-083 | **Add — nominal propulsor diameter = 90 mm** |
| SR-005 | No wording change |
| SR-008 | No wording change |
| SR-010 | No wording change |
| SR-047 | No wording change |
| SR-049 | No wording change |
| SR-054 | No wording change |
| SR-055 | No wording change |
| SR-057 | No wording change; use with SR-083 |
| SR-062 | No wording change |
| SR-063 | No wording change |
| SR-066 | No wording change |
| SR-067 | No wording change |
| OI-002 | **Open — Resolution in Progress** |
| ORD-016 | **Change to Partially Resolved** |
| 140–160 mm preliminary OD range | Retain as analysis / packaging objective only |

PT-REQ-001 shall be revised only after PT-AN-002 is completed and internally validated.

---

## 13. Downstream Engineering Impact

### 13.1 Purpose

Selection of:

**D_P = 90 mm nominal propulsor diameter**

establishes the common geometric scale for the next phase of Project Triton engineering.

The G90 decision does not complete the thruster design.

Its purpose is to remove the principal diameter uncertainty so that subsequent hydrodynamic, electromagnetic, mechanical, structural, electrical, thermal, manufacturing, CAD, and verification analyses can proceed using the same controlled geometry basis.

The next engineering activities shall therefore treat:

**90 mm nominal propulsor diameter**

as fixed unless a downstream analysis identifies a substantive incompatibility requiring formal reconsideration.

---

### 13.2 Immediate Hydrodynamic Development

The next hydrodynamic activity shall develop the propulsor operating point for the selected G90 geometry.

The analysis shall determine, at minimum:

- candidate blade count;
- blade radial extent;
- blade chord distribution;
- blade pitch distribution;
- blade twist;
- blade-section family or preliminary section geometry;
- propulsor solidity;
- candidate duct relationship;
- estimated thrust coefficient;
- estimated torque coefficient;
- required rotor RPM;
- required torque;
- estimated propulsor mechanical power;
- preliminary cavitation indicators.

The analysis shall evaluate the established performance points:

- **68.6 N continuous forward static thrust**
- **98.1 N peak forward static thrust**

using the selected:

**D_P = 90 mm**

geometry.

This work shall principally support resolution of:

- OI-015 — Propulsor Geometry;
- OI-017 — Controller / Commutation, through required speed range;
- ORD-018 — performance / cavitation / vibration-related open decision, where applicable.

The hydrodynamic operating point shall be established before detailed electromagnetic sizing because the motor must be designed to the required propulsor torque-speed envelope rather than an assumed RPM.

---

### 13.3 Rotor Speed and Torque Definition

Once a credible preliminary propulsor geometry exists, the project shall establish the required rotor mechanical operating envelope.

At minimum, this shall include estimates for:

- continuous operating RPM;
- peak operating RPM;
- continuous torque;
- peak torque;
- continuous mechanical power;
- peak mechanical power;
- startup torque;
- reverse operating requirements where applicable;
- overspeed condition for structural analysis.

The governing relationship is:

**P = τω**

The resulting torque-speed envelope will become a principal input to:

- OI-003 — Operating Voltage and Power Range;
- OI-004 — Electromagnetic Topology;
- OI-005 — Stator and Winding Geometry;
- OI-006 — Rotor Magnetic Circuit / Magnetic-Element Arrangement;
- OI-007 — Rotor Electromagnetic-Element Retention;
- OI-014 — Thermal Management;
- OI-017 — Controller / Commutation.

No detailed motor design shall be frozen before this operating envelope is sufficiently established.

---

### 13.4 Electrical-Envelope Development

After the preliminary torque-speed requirement is available, OI-003 shall establish a defensible electrical operating envelope.

The current PT-AN-001 planning values of approximately:

- **0.6 kW continuous electrical input**
- **1.0 kW peak electrical input**
- **approximately 1.2 kW preliminary peak hardware-screening level**

shall remain planning estimates only until replaced by a more rigorous power-budget analysis.

The OI-003 analysis shall establish or bound:

- nominal system voltage;
- allowable voltage range;
- continuous current;
- peak current;
- continuous electrical input power;
- peak electrical input power;
- allowable peak duration;
- electrical margin;
- controller power rating;
- conductor sizing implications;
- protection requirements.

The G90 geometry shall be used as the physical motor-packaging basis for this analysis.

---

### 13.5 Electromagnetic Topology Development

OI-004 shall evaluate electromagnetic topologies against the selected G90 annular geometry and the required torque-speed envelope.

The topology trade shall consider, as applicable:

- radial-flux arrangements;
- axial-flux arrangements;
- transverse-flux arrangements;
- other technically credible annular direct-drive configurations.

The trade shall evaluate:

- achievable torque;
- torque density;
- power density;
- active axial length;
- radial build;
- magnetic loading;
- conductor loading;
- pole count;
- electrical frequency;
- cogging;
- torque ripple;
- thermal loss;
- manufacturability;
- environmental protection;
- rotor retention;
- compatibility with radial and axial support.

The selected topology shall fit within a practical G90 system envelope rather than forcing an unsupported geometry expansion.

If no credible electromagnetic topology can satisfy the required operating point within a practical G90 envelope, PT-AN-002 shall be reconsidered through configuration control.

---

### 13.6 Rotor and Stator Geometry

Following topology selection, OI-005 and OI-006 shall establish the detailed electromagnetic geometry.

This shall include, as applicable:

- rotor inner diameter;
- rotor outer diameter;
- rotor radial thickness;
- rotor axial length;
- magnet dimensions;
- magnet segmentation;
- magnetic back-iron geometry;
- stator inner diameter;
- stator outer diameter;
- stator radial thickness;
- stator axial length;
- winding geometry;
- pole pitch;
- slot or segment geometry;
- electromagnetic clearance.

These values shall replace the preliminary Class C dispositions established in PT-AN-002.

They shall then be incorporated into the controlled CAD configuration.

---

### 13.7 Rotor Electromagnetic-Element Retention

OI-007 shall establish the method used to retain the rotating electromagnetic elements under the approved operating and overspeed conditions.

The analysis shall consider:

- centrifugal loading;
- adhesive strength where applicable;
- mechanical retention;
- composite or metallic retaining bands;
- environmental degradation;
- thermal expansion;
- rotor deformation;
- assembly tolerances.

The final retention geometry may increase:

- rotor radial thickness;
- rotor axial length;
- overall outside diameter.

Any resulting change shall be checked against the system-level G90 packaging basis.

---

### 13.8 Radial Rotor Support

OI-008 shall establish the radial-support architecture needed to maintain concentricity and prevent unacceptable rotor motion.

The analysis shall determine:

- support type;
- support locations;
- support count;
- support contact geometry;
- allowable radial displacement;
- preload where applicable;
- wear allowance;
- water lubrication where applicable;
- friction;
- support material;
- serviceability.

The support system shall be developed concurrently with electromagnetic clearance rather than after the motor geometry is complete.

The output shall provide the basis for establishing:

**C_R — radial mechanical clearance**

and the associated tolerance budget.

---

### 13.9 Axial Support and Thrust Reaction

OI-009 shall establish the mechanism for:

- axial rotor positioning;
- forward thrust reaction;
- reverse thrust reaction;
- electromagnetic axial-force reaction where applicable.

The design shall address at least:

- continuous thrust;
- peak thrust;
- transient loads;
- approved reverse operation;
- alignment;
- wear;
- preload where applicable;
- serviceability.

The output shall provide the basis for establishing:

**C_A — axial mechanical clearance**

and the final axial support packaging.

---

### 13.10 Clearance and Tolerance Development

OI-011 and OI-020 shall convert the placeholder clearance geometry into controlled numerical values.

The clearance budget shall include, as applicable:

- nominal electromagnetic gap;
- rotor radial runout;
- rotor axial runout;
- support clearance;
- stator concentricity;
- housing concentricity;
- manufacturing tolerance;
- assembly tolerance;
- structural deflection;
- thermal expansion;
- coating thickness;
- encapsulation variation;
- wear;
- dynamic rotor motion.

This analysis shall establish whether the selected clearances can be manufactured, measured, assembled, and maintained reliably.

The resulting numerical requirements shall be incorporated into PT-REQ-001 or lower-level controlled specifications as appropriate.

---

### 13.11 Structural and Containment Development

OI-010 and OI-012 shall establish the principal structural and containment geometry.

The analysis shall consider:

- housing stiffness;
- rotor structural stiffness;
- electromagnetic force;
- hydrodynamic thrust;
- torque reaction;
- support loads;
- mounting loads;
- rotor kinetic energy;
- credible rotor fragmentation;
- material strength;
- material stiffness;
- fatigue where applicable;
- environmental exposure;
- manufacturing process.

The structural design shall preserve:

- electromagnetic alignment;
- mechanical clearance;
- duct geometry;
- support geometry.

The approximately **140–160 mm outside-diameter study range** may be used as a packaging target during this work, but it shall not override structural or safety requirements.

---

### 13.12 Environmental and Thermal Development

OI-013 and OI-014 shall use the G90 geometry and subsequent electromagnetic design to establish:

- water-exposure strategy;
- corrosion-control approach;
- coatings;
- encapsulation;
- galvanic compatibility;
- ingress protection where applicable;
- heat-transfer path;
- continuous thermal limit;
- peak thermal limit;
- allowable peak duration;
- winding temperature limits;
- magnet temperature limits;
- structural-material temperature limits.

Thermal analysis shall use predicted electromagnetic and mechanical losses rather than the ideal induced-power values from PT-AN-001.

---

### 13.13 System-Level CAD Development

The G90 decision now provides sufficient basis to begin a controlled system-level CAD envelope.

The first CAD configuration shall show, at minimum:

- 90 mm nominal propulsor reference envelope;
- central rotational axis;
- central flow passage;
- annular rotor placeholder;
- electromagnetic packaging region;
- stationary housing / duct envelope;
- radial-support reserved region;
- axial-support reserved region;
- containment reserved region;
- mounting-interface reserved region;
- principal datum structure.

The CAD model shall clearly distinguish between:

1. **selected dimensions**;
2. **preliminary packaging dimensions**;
3. **placeholder geometry**.

Placeholder geometry shall not be mistaken for approved detailed design.

---

### 13.14 System Outside Diameter

The next integrated packaging studies shall investigate whether the G90 architecture can remain within the preliminary:

**140–160 mm overall outside-diameter study range**

while satisfying:

- electromagnetic requirements;
- structural requirements;
- rotor support;
- clearance;
- containment;
- environmental protection.

The resulting outside diameter shall be established through evidence from the downstream analyses.

If the final credible design falls outside 140–160 mm, the reason shall be documented and PT-AN-002 updated as necessary.

---

### 13.15 System Axial Length

No axial system-length target has yet been approved.

The final axial envelope shall emerge from the coupled requirements of:

- propulsor hydrodynamics;
- electromagnetic active length;
- rotor structural width;
- radial support;
- axial support;
- containment;
- duct geometry;
- mounting;
- instrumentation.

Axial compactness shall remain a design objective, but no subsystem shall be compromised solely to meet an arbitrary length.

---

### 13.16 Test-Interface Development

OI-019 shall use the selected G90 geometry to establish the physical test interfaces required for:

- static thrust measurement;
- torque reaction;
- electrical instrumentation;
- rotor-speed measurement;
- thermal measurement;
- vibration measurement;
- controlled mounting;
- guarding / containment;
- configuration identification.

The test-fixture geometry shall prevent unacceptable interference with:

- inlet flow;
- outlet wake;
- duct flow;
- structural load measurement.

The fixture shall also permit repeatable installation of revised development configurations.

---

### 13.17 Test-Envelope Development

OI-023 shall establish the authorized progression from low-energy checkout to full-performance testing.

The progression shall account for the eventual G90 rotor:

- mass;
- inertia;
- RPM;
- electrical power;
- stored energy;
- support maturity;
- containment maturity.

The test program shall include appropriate limits for:

- initial rotation;
- incremental RPM;
- incremental electrical power;
- incremental thrust;
- vibration;
- temperature;
- abnormal noise;
- leakage;
- rotor displacement where monitored.

The selection of G90 does not authorize operation at the 7 kgf or 10 kgf performance points until the applicable test-entry criteria are satisfied.

---

### 13.18 Configuration-Control Impact

All downstream analyses and CAD models shall explicitly identify the geometry basis as:

**G90 — D_P = 90 mm nominal propulsor diameter**

unless evaluating an intentional alternative configuration.

G80 or G100 studies may continue for comparison, but they shall be clearly identified as:

- alternate;
- sensitivity;
- reference;
- future configuration.

They shall not silently replace the G90 design basis.

This distinction is required to prevent analytical, CAD, manufacturing, and test results from different nominal diameter configurations from being mixed.

---

### 13.19 Recommended Engineering Sequence

Following completion of PT-AN-002, the recommended technical sequence is:

1. **Develop the G90 preliminary hydrodynamic propulsor operating point.**
2. Establish continuous and peak rotor RPM, torque, and mechanical power.
3. Resolve the preliminary electrical voltage/current/power envelope.
4. Perform the electromagnetic topology trade.
5. Develop stator, winding, and rotor magnetic geometry.
6. Develop rotor electromagnetic-element retention.
7. Develop radial rotor support.
8. Develop axial support and thrust reaction.
9. Establish mechanical and electromagnetic clearance budgets.
10. Develop structural housing and backup containment.
11. Select structural and environmental materials.
12. Develop environmental-protection and corrosion-control provisions.
13. Complete thermal analysis and duty limits.
14. Refine controller, startup, commutation, and fault-protection requirements.
15. Develop detailed instrumentation and test interfaces.
16. Establish manufacturing tolerances and inspection methods.
17. Mature the integrated CAD configuration.
18. Conduct progressive prototype verification.

Iteration among these activities is expected.

The sequence identifies the principal dependency order; it does not prohibit concurrent work where adequate inputs exist.

---

### 13.20 Immediate Next Engineering Activity

The immediate next major technical analysis after PT-AN-002 shall be:

**preliminary hydrodynamic propulsor geometry and operating-point development for the selected 90 mm nominal propulsor.**

This activity shall convert the currently controlled:

- diameter;
- continuous thrust objective; and
- peak thrust objective

into the first defensible estimates of:

- blade geometry;
- rotor RPM;
- torque;
- propulsor mechanical power.

Those outputs are required before the Project Triton electromagnetic system can be sized rigorously.

---

## 14. Conclusion

PT-AN-002 evaluated the principal prototype geometry for the Project Triton RDT-80 rim-driven thruster using an integrated system trade among:

- hydrodynamic performance;
- electromagnetic packaging;
- mechanical and structural feasibility;
- manufacturing practicality;
- prototype testability;
- configuration control;
- development risk.

The analysis compared three primary nominal propulsor diameters:

- **G80 — 80 mm**
- **G90 — 90 mm**
- **G100 — 100 mm**

All three candidates remain technically credible.

However, the analyses in Sections 6 through 10 consistently identify G90 as the strongest overall development geometry.

The selected nominal propulsor diameter for the initial Project Triton prototype is therefore:

**D_P = 90 mm**

The selected candidate is:

**G90**

This decision is based on the combined finding that G90:

- materially reduces disk loading relative to G80;
- reduces ideal induced-power demand relative to G80;
- provides additional annular circumference and electromagnetic torque leverage;
- provides improved packaging space for windings, magnetic elements, rotor support, instrumentation, and assembly;
- retains a comparatively compact system scale;
- avoids the larger rotor, structural, inertia, containment, manufacturing, and test penalties associated with G100;
- preserves meaningful compact rim-driven-thruster development challenges;
- provides the strongest cross-discipline balance for the initial integrated prototype.

The historical designation:

**RDT-80**

shall be retained as the Project Triton prototype-family designation and shall not be interpreted as a requirement for exactly 80 mm nominal propulsor diameter.

The analysis does **not** establish final values for:

- rotor inner diameter;
- rotor outer diameter;
- rotor radial thickness;
- stator dimensions;
- electromagnetic clearance;
- radial mechanical clearance;
- axial mechanical clearance;
- detailed duct geometry;
- rotor-support dimensions;
- complete outside diameter;
- complete axial length.

Those parameters remain controlled by their applicable downstream analyses and open issues.

The approximately:

**140–160 mm overall outside-diameter range**

identified in this analysis is a preliminary packaging-study objective only.

It is not an approved system requirement.

PT-AN-002 therefore recommends the following requirements and open-decision actions:

- add **SR-083 — The initial RDT-80 prototype shall use a nominal propulsor diameter of 90 mm**;
- verify SR-083 by **VM-001 — Inspection**;
- retain **OI-002 — Open — Resolution in Progress**;
- change **ORD-016 — Principal Prototype Geometry** to **Partially Resolved**.

The selected G90 geometry now provides the common dimensional basis required for the next engineering activity:

**preliminary hydrodynamic propulsor geometry and operating-point development.**

That analysis shall use:

- **90 mm nominal propulsor diameter**;
- **68.6 N minimum continuous forward static thrust**; and
- **98.1 N minimum peak forward static thrust**

to establish the first defensible estimates of:

- blade geometry;
- rotor RPM;
- rotor torque;
- propulsor mechanical power.

Those outputs will become the principal inputs to the subsequent electrical and electromagnetic design activities.

PT-AN-002 therefore resolves the nominal prototype diameter decision while deliberately preserving the remaining detailed geometry for evidence-based downstream development.