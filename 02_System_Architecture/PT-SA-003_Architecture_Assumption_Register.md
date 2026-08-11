# PT-SA-003 — Architecture Assumption Register

## Document Control

| Field          | Value                              |
| -------------- | ---------------------------------- |
| Project        | Project Triton                     |
| Document ID    | PT-SA-003                          |
| Document Title | Architecture Assumption Register   |
| Version        | 0.1                                |
| Status         | Draft — DR-002 Supporting Artifact |
| Owner          | Robert Schneider                   |
| Created        | 2026-08-11                         |
| Last Updated   | 2026-08-11                         |

## Revision History

| Version | Date       | Author           | Description                                                     |
| ------- | ---------- | ---------------- | --------------------------------------------------------------- |
| 0.1     | 2026-08-11 | Robert Schneider | Initial assumption register created from PT-SA-001 Section 11.8 |

## 1. Purpose

This document is the controlled register for material architectural assumptions associated with the Project Triton RDT-80.

The register implements the assumption-management framework established in `PT-SA-001 — System Architecture`.

An assumption is a condition treated as true for planning, analysis, design, or testing without complete confirming evidence.

Assumptions recorded here shall remain visible until they are validated, revised, rejected, or retired.

This register does not convert an assumption into a verified fact, approved requirement, or demonstrated technical capability.

## 2. Status Definitions

Assumptions shall use the following status values:

| Status        | Meaning                                                                                                                         |
| ------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Open**      | The assumption is currently being relied upon and has not yet been validated.                                                   |
| **Validated** | Sufficient evidence confirms the assumption for its applicable scope.                                                           |
| **Revised**   | New information requires the assumption statement or its applicable scope to be changed.                                        |
| **Rejected**  | Evidence demonstrates that the assumption is incorrect.                                                                         |
| **Retired**   | The assumption is no longer applicable or has been replaced by controlled requirements, verified data, or an approved decision. |

## 3. Initial Architecture Assumptions

### AS-001 — Accessible Prototype Development Resources

**Assumption Statement:**
The RDT-80 can be developed as a modular prototype using fabrication and test resources reasonably accessible to Project Triton.

**Basis:**
Initial project development concept and modular prototype strategy.

**Owner:**
Robert Schneider

**Affected Items:**
Physical architecture, manufacturing approach, module design, test planning, cost, schedule, and supplier strategy.

**Consequence if Incorrect:**
The selected architecture may require redesign, outsourcing, specialized fabrication capability, additional funding, or a revised development schedule.

**Validation Method:**
Manufacturing-capability assessment, supplier research, preliminary CAD development, fabrication trials, and test-facility assessment.

**Target Resolution:**
Before commitment to irreversible fabrication of the integrated prototype.

**Status:**
Open

---

### AS-002 — Useful Annular Electromagnetic Torque

**Assumption Statement:**
A direct annular electromagnetic drive can generate useful hydrodynamic thrust at the intended prototype scale.

**Basis:**
Project Triton rim-driven propulsion concept.

**Owner:**
Robert Schneider

**Affected Items:**
Electromagnetic architecture, rotor geometry, stator geometry, electrical power requirements, thermal design, propulsor sizing, and overall technical feasibility.

**Consequence if Incorrect:**
The fundamental RDT-80 propulsion concept may require major redesign or may not be technically viable at the selected scale.

**Validation Method:**
Electromagnetic analysis, preliminary sizing calculations, benchtop electromagnetic testing, and reduced-energy integrated prototype testing.

**Target Resolution:**
Before final electromagnetic topology selection and commitment to the integrated rotor/stator design.

**Status:**
Open

---

### AS-003 — Adequate Heat Rejection

**Assumption Statement:**
The surrounding water or an associated cooling path can provide sufficient heat rejection for initial prototype testing.

**Basis:**
Expected availability of water as a substantial thermal sink and the ability to incorporate supplemental cooling if required.

**Owner:**
Robert Schneider

**Affected Items:**
Stator design, winding current limits, housing design, encapsulation, rotor-support design, motor controller, cooling architecture, and operating envelope.

**Consequence if Incorrect:**
Prototype power, run duration, torque, or speed may require restriction, or an active cooling architecture may become mandatory.

**Validation Method:**
Thermal-loss analysis, heat-transfer modeling, material-property evaluation, component temperature testing, and reduced-energy thermal testing.

**Target Resolution:**
Before approval of the initial powered operating envelope.

**Status:**
Open

---

### AS-004 — Shaftless Rotor Support Feasibility

**Assumption Statement:**
Rotor radial and axial support can be achieved without a conventional central shaft.

**Basis:**
Core rim-driven architecture and availability of candidate annular rotor-support technologies.

**Owner:**
Robert Schneider

**Affected Items:**
Rotor architecture, bearing selection, housing geometry, rotor retention, electromagnetic clearance, mechanical losses, wear, and hydrodynamic performance.

**Consequence if Incorrect:**
The current direct rim-driven architecture may require a fundamental change to rotor support or propulsion configuration.

**Validation Method:**
Rotor-support trade study, load analysis, tolerance analysis, benchtop support testing, and reduced-speed rotor testing.

**Target Resolution:**
Before detailed rotor-support and housing design.

**Status:**
Open

---

### AS-005 — Controllable Electromagnetic Gap

**Assumption Statement:**
The rotor, propulsor, support, stator, and housing can be packaged while maintaining a controllable electromagnetic gap.

**Basis:**
Initial physical architecture and intended use of controlled mechanical datums, supports, clearances, and manufacturing tolerances.

**Owner:**
Robert Schneider

**Affected Items:**
Rotor diameter, stator diameter, housing stiffness, bearing/support clearances, manufacturing tolerances, thermal expansion, alignment, and electromagnetic efficiency.

**Consequence if Incorrect:**
Rotor-to-stator contact, excessive electromagnetic gap, poor motor performance, instability, or substantial redesign may result.

**Validation Method:**
Preliminary CAD packaging, tolerance stack-up analysis, structural-deflection analysis, thermal-expansion analysis, dimensional inspection, and rotor-displacement testing.

**Target Resolution:**
Before approval of powered rotor operation.

**Status:**
Open

---

### AS-006 — Availability of Electrical and Instrumentation Resources

**Assumption Statement:**
Required electrical power, motor-control hardware, instrumentation, and data acquisition can be obtained or developed within the project’s practical constraints.

**Basis:**
Commercial availability of motor-control, sensing, power-electronics, and data-acquisition technologies suitable for prototype development.

**Owner:**
Robert Schneider

**Affected Items:**
Motor-control architecture, power requirements, sensing, protection, data acquisition, test planning, cost, and schedule.

**Consequence if Incorrect:**
The project may require custom electronics, specialized test equipment, reduced prototype power, additional cost, or schedule changes.

**Validation Method:**
Supplier research, component availability review, preliminary electrical architecture, pricing, procurement analysis, and benchtop integration testing.

**Target Resolution:**
Before final motor-control and instrumentation architecture selection.

**Status:**
Open

---

### AS-007 — Controlled-Facility Initial Testing

**Assumption Statement:**
The prototype can be tested initially in a controlled facility before any vessel-integrated or open-water testing.

**Basis:**
Project verification strategy requiring progressive testing from low-risk activities toward higher-energy and operational environments.

**Owner:**
Robert Schneider

**Affected Items:**
Test adapter, mounting architecture, instrumentation, power supply, cooling, personnel safety, hydrodynamic testing, and verification planning.

**Consequence if Incorrect:**
Initial testing may require substantially more complex safety controls, portable support equipment, environmental controls, or vessel integration earlier than planned.

**Validation Method:**
Test-facility research, capability assessment, space and power requirements, water-system requirements, and test-stand concept development.

**Target Resolution:**
Before final test-system architecture and powered-test planning.

**Status:**
Open

---

### AS-008 — Availability of Suitable Materials

**Assumption Statement:**
Materials suitable for water exposure, electrical insulation, structural loading, thermal management, and corrosion control are commercially available.

**Basis:**
Known existence of marine, electrical, polymeric, metallic, composite, and encapsulation material systems potentially applicable to the prototype.

**Owner:**
Robert Schneider

**Affected Items:**
Rotor, stator, housing, bearings, insulation, encapsulation, seals, fasteners, corrosion protection, and manufacturing processes.

**Consequence if Incorrect:**
Material substitutions, environmental restrictions, specialized coatings, custom processing, or architectural redesign may be required.

**Validation Method:**
Supplier research, material-data review, compatibility analysis, corrosion evaluation, coupon testing, and manufacturing trials.

**Target Resolution:**
Before release of material specifications for critical prototype components.

**Status:**
Open

---

### AS-009 — External Support Equipment Compatibility

**Assumption Statement:**
The initial prototype may use external power electronics, cooling equipment, and test instrumentation without invalidating the core rim-driven architecture.

**Basis:**
The RDT-80 system architecture intentionally permits external support equipment during development.

**Owner:**
Robert Schneider

**Affected Items:**
System boundary, motor controller, cooling architecture, test interface, instrumentation, packaging, and scalability assessment.

**Consequence if Incorrect:**
The prototype may need greater integration of power electronics, cooling, or instrumentation into the thruster assembly before meaningful architecture validation can occur.

**Validation Method:**
Interface analysis, system-boundary review, prototype testing, and assessment of whether external equipment materially alters relevant operating behavior.

**Target Resolution:**
During initial integrated prototype testing and before conclusions are drawn regarding production scalability.

**Status:**
Open

---

### AS-010 — Incremental Operating-Envelope Development

**Assumption Statement:**
A controlled operating envelope can be established and expanded incrementally through analysis and reduced-risk testing.

**Basis:**
Verification and safety architecture established in PT-SA-001 Sections 8 and 10.

**Owner:**
Robert Schneider

**Affected Items:**
Safety controls, test procedures, instrumentation, motor-control limits, structural analysis, thermal analysis, rotor dynamics, and verification planning.

**Consequence if Incorrect:**
The project may be unable to establish safe progression to intended operating conditions, potentially restricting prototype performance or requiring significant redesign.

**Validation Method:**
Hazard analysis, analytical limit development, reduced-energy testing, incremental powered testing, and post-test inspection.

**Target Resolution:**
Validated progressively throughout powered prototype development.

**Status:**
Open

---

### AS-011 — Replaceable Experimental Modules

**Assumption Statement:**
Major experimental modules can be replaced or revised without complete redesign of the test system.

**Basis:**
Modular-development objective and physical architecture established in PT-SA-001.

**Owner:**
Robert Schneider

**Affected Items:**
Module boundaries, mounting interfaces, electrical connectors, cooling interfaces, instrumentation, test adapter, configuration management, and experimental schedule.

**Consequence if Incorrect:**
Design iterations may require substantial test-system rework, increasing cost, schedule, and risk of losing comparability among experiments.

**Validation Method:**
Preliminary CAD packaging, interface definition, module compatibility assessment, assembly planning, and physical prototype integration.

**Target Resolution:**
Before fabrication of the first integrated modular test article.

**Status:**
Open

---

### AS-012 — Prototype Certification Scope

**Assumption Statement:**
The RDT-80 is a development prototype and is not required at DR-002 to satisfy final marine certification, classification-society, or production-installation criteria.

**Basis:**
Project scope and DR-002 limitations established in PT-SA-001.

**Owner:**
Robert Schneider

**Affected Items:**
Standards selection, materials, detailed design, documentation, testing, certification strategy, vessel integration, cost, and schedule.

**Consequence if Incorrect:**
Additional mandatory standards, documentation, design controls, qualification testing, material requirements, or independent review may need to be incorporated earlier in development.

**Validation Method:**
Project-scope review and evaluation of regulatory, classification, certification, or intended-use requirements before vessel installation or commercialization.

**Target Resolution:**
Before any decision to pursue vessel installation, certification, classification approval, or commercial production.

**Status:**
Open

## 4. Register Maintenance

This register shall be updated whenever:

* A new material architectural assumption is introduced.
* Evidence validates or rejects an existing assumption.
* An assumption is revised.
* An assumption becomes an approved requirement or architectural decision.
* A design, test, supplier, or project change materially affects an assumption.
* An assumption is no longer applicable.

Changes to an assumption shall identify affected decisions, requirements, interfaces, analyses, models, configurations, and test results as applicable.

Assumption identifiers shall not be reused after an assumption is retired, rejected, or superseded.
