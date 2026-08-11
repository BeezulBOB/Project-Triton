# PT-SA-004 — Technical Risk Register

## Document Control

| Field          | Value                              |
| -------------- | ---------------------------------- |
| Project        | Project Triton                     |
| Document ID    | PT-SA-004                          |
| Document Title | Technical Risk Register            |
| Version        | 0.1                                |
| Status         | Draft — DR-002 Supporting Artifact |
| Owner          | Robert Schneider                   |
| Created        | 2026-08-11                         |
| Last Updated   | 2026-08-11                         |

## Revision History

| Version | Date       | Author           | Description                                                          |
| ------- | ---------- | ---------------- | -------------------------------------------------------------------- |
| 0.1     | 2026-08-11 | Robert Schneider | Initial technical risk register created from PT-SA-001 Section 11.14 |

## 1. Purpose

This document is the controlled register for technical risks associated with the Project Triton RDT-80.

The register implements the technical-risk-management framework established in `PT-SA-001 — System Architecture`.

A technical risk is an uncertain condition that could adversely affect:

* Safety.
* Technical feasibility.
* Performance.
* Reliability.
* Manufacturability.
* Verification.
* Cost.
* Schedule.
* Scalability.
* Project objectives.

Risks shall remain visible until they are mitigated, formally accepted, realized and transferred to issue or anomaly management, or otherwise closed through documented evidence.

## 2. Risk Management Process

Technical risks shall be managed through:

1. Identification.
2. Analysis.
3. Prioritization.
4. Assignment of ownership.
5. Mitigation planning.
6. Monitoring.
7. Verification of mitigation effectiveness.
8. Closure or formal acceptance.

Risk treatment shall generally prioritize:

1. Elimination through architecture or design.
2. Reduction of likelihood.
3. Reduction of consequence.
4. Improved detection.
5. Validation through analysis or test.
6. Transfer through external expertise, specialized testing, or qualified suppliers.
7. Formal acceptance of residual risk when further mitigation is impractical or disproportionate.

Safety risks shall not be accepted solely because their estimated likelihood is low when the potential consequence is severe and reasonable mitigation remains available.

## 3. Risk Rating Convention

Until sufficient quantitative data exist, Project Triton may use qualitative risk ratings.

### 3.1 Likelihood

| Rating       | General Meaning                                                                                         |
| ------------ | ------------------------------------------------------------------------------------------------------- |
| **Low**      | Unlikely based on current architecture, evidence, or comparable experience.                             |
| **Moderate** | Credible and reasonably possible.                                                                       |
| **High**     | Expected to occur unless specific mitigation succeeds.                                                  |
| **Critical** | Already occurring, nearly certain, or inherent to the current approach without major corrective action. |

### 3.2 Consequence

| Rating       | General Meaning                                                                                                                                          |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Low**      | Limited effect that can be corrected without material impact to project objectives.                                                                      |
| **Moderate** | Meaningful redesign, retest, cost, or schedule impact may result.                                                                                        |
| **High**     | Major effect on safety, feasibility, architecture, performance, cost, or schedule.                                                                       |
| **Critical** | Could cause serious personnel hazard, loss of fundamental feasibility, catastrophic prototype failure, or termination of the current technical approach. |

### 3.3 Overall Risk Rating

The overall rating shall reflect engineering judgment considering:

* Likelihood.
* Consequence.
* Detectability or warning capability.
* Timeframe.
* Existing controls.
* Technical uncertainty.
* Ability to recover following realization.

The overall rating is not required to equal the mathematically highest combination of likelihood and consequence when documented engineering judgment supports another classification.

Initial ratings in this register are provisional and shall be revised as analysis, supplier information, CAD development, fabrication experience, and test evidence become available.

## 4. Risk Status Definitions

| Status         | Meaning                                                                                                                   |
| -------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **Open**       | Risk is active and requires management.                                                                                   |
| **Monitoring** | No immediate additional action is required, but indicators and assumptions are being tracked.                             |
| **Mitigated**  | Planned mitigation has materially reduced likelihood or consequence, but residual risk remains.                           |
| **Accepted**   | Residual risk has been formally accepted by the applicable approval authority.                                            |
| **Realized**   | The uncertain event has occurred and shall be managed as an issue, anomaly, failure, or corrective action as appropriate. |
| **Closed**     | Risk no longer materially applies or sufficient evidence supports closure.                                                |

## 5. Initial Technical Risks

### RK-001 — Insufficient Electromagnetic Torque Capability

**Risk Statement:**
The selected electromagnetic topology may not produce the required torque within acceptable size, current, temperature, and manufacturability limits, resulting in inadequate thruster performance or substantial redesign.

**Category:**
Electromagnetic

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Electromagnetic topology remains an open architectural decision.
* Preliminary CAD is restricted until DR-002 approval.
* Electromagnetic analysis is required before final design commitment.
* Operating power and thermal limits are not yet fixed.

**Mitigation Actions:**

* Establish quantitative thrust and torque objectives.
* Perform electromagnetic topology trade study.
* Develop preliminary electromagnetic sizing models.
* Evaluate current density, magnetic loading, losses, and thermal limits.
* Compare multiple rotor/stator configurations before committing to hardware.
* Conduct low-energy electromagnetic bench testing where useful.

**Trigger or Indicator:**

* Required torque cannot be achieved without excessive current, magnetic saturation, thermal loading, unacceptable gap sensitivity, or impractical geometry.

**Target Completion:**
Before final electromagnetic topology selection.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-002; OI-001; OI-002; OI-003; OI-004; OI-005; OI-006; MOD-001; MOD-002.

---

### RK-002 — Rotor-Support Instability or Insufficient Load Capacity

**Risk Statement:**
The rotor-support architecture may not maintain required radial and axial rotor position throughout the intended operating envelope, resulting in instability, excessive displacement, contact, wear, or mechanical failure.

**Category:**
Rotor Dynamics / Mechanical

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Rotor support is treated as a dedicated subsystem.
* Radial and axial support are explicit architectural functions.
* Rotor support remains an unresolved design decision.
* Reduced-energy and incremental testing are required.

**Mitigation Actions:**

* Perform rotor-support technology trade study.
* Determine radial and axial load cases.
* Develop rotor-dynamic models.
* Analyze support stiffness, damping, clearance, friction, and wear.
* Evaluate backup or catch-bearing concepts.
* Conduct bench and reduced-speed support tests before unrestricted operation.

**Trigger or Indicator:**

* Excessive displacement, unstable motion, unexpected vibration, increasing wear, high friction, or inability to maintain required clearances.

**Target Completion:**
Before detailed rotor-support design and powered rotor testing.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-004; AS-005; OI-008; OI-009; OI-010; OI-011; MOD-003; SF-006; SF-007.

---

### RK-003 — Loss of Rotor-to-Stator Clearance

**Risk Statement:**
Manufacturing tolerance accumulation, structural deflection, wear, rotor motion, or thermal expansion may reduce rotor-to-stator clearance below a safe level, causing contact, damage, excessive losses, or loss of control.

**Category:**
Mechanical / Integration

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Electromagnetic gap is identified as a critical cross-subsystem interface.
* Clearance must be analytically or experimentally bounded before powered-envelope approval.
* A controlled datum structure is required.
* Rotor displacement may be instrumented.

**Mitigation Actions:**

* Establish nominal and minimum allowable clearances.
* Perform tolerance stack-up analysis.
* Analyze housing and support deflection.
* Analyze thermal expansion.
* Define datum and alignment scheme.
* Define inspection and acceptance methods.
* Instrument rotor displacement during early testing where practical.

**Trigger or Indicator:**

* Predicted or measured minimum clearance approaches the required safety margin, or evidence of rub, contact, wear, or unexpected displacement is observed.

**Target Completion:**
Before approval of powered rotor operation.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-005; OI-011; OI-020; MOD-001; MOD-002; MOD-003; MOD-004; INT-002; INT-003; INT-004.

---

### RK-004 — Rotor Electromagnetic Element Release

**Risk Statement:**
Permanent magnets or other rotor electromagnetic elements may not remain securely retained under centrifugal, thermal, hydrodynamic, electromagnetic, and fault loads, resulting in rotor damage, secondary mechanical failure, or personnel hazard.

**Category:**
Safety / Mechanical

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Rotor retention is identified as safety-critical.
* Rotor electromagnetic retention remains an explicit open issue.
* Reduced-risk testing and mechanical containment are required.
* Rotating components require retention appropriate to stored rotational energy.

**Mitigation Actions:**

* Determine rotor speed envelope and centrifugal loads.
* Evaluate magnet or rotor-element retention concepts.
* Perform adhesive, mechanical, sleeve, pocket, or hybrid retention trade study as applicable.
* Analyze thermal expansion and material compatibility.
* Conduct structural analysis and proof testing.
* Incorporate secondary containment where warranted.

**Trigger or Indicator:**

* Retention margin is inadequate, material properties degrade at operating conditions, dimensional movement occurs, or inspection identifies loosening or cracking.

**Target Completion:**
Before operation at rotational energy capable of producing hazardous release.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
OI-006; OI-007; OI-010; MOD-001; SF-007; AC-009.

---

### RK-005 — Inadequate Thermal Management

**Risk Statement:**
Thermal losses may exceed the heat-rejection capability of the selected cooling architecture, resulting in winding, power-electronics, bearing, magnet, insulation, seal, adhesive, or structural-material temperatures exceeding acceptable limits.

**Category:**
Thermal

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* A defined thermal-management subsystem exists.
* Significant heat sources require identified heat-transfer paths.
* Critical temperatures require monitoring or analytical bounding.
* Loss of cooling is a protective trigger.

**Mitigation Actions:**

* Develop loss estimates for motor, controller, conductors, and supports.
* Develop steady-state and transient thermal models.
* Characterize candidate cooling methods.
* Measure temperatures during reduced-energy testing.
* Establish conservative thermal limits and shutdown thresholds.
* Provide external cooling capability if passive cooling is inadequate.

**Trigger or Indicator:**

* Model or test temperatures approach material limits, heat continues accumulating during steady operation, or cooling effectiveness is substantially below prediction.

**Target Completion:**
Before approval of the initial sustained powered operating envelope.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-003; OI-014; MOD-006; INT-007; INT-008; INT-009; SF-004; SF-005.

---

### RK-006 — Marine Environmental Degradation

**Risk Statement:**
Corrosion, galvanic interaction, water absorption, fouling, or water ingress may degrade structural, electrical, magnetic, sealing, or instrumentation performance, resulting in premature failure or invalid test results.

**Category:**
Environmental

**Owner:**
Robert Schneider

**Likelihood:**
High

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Marine environmental compatibility is an architectural driver.
* Environmental regions must be classified.
* Sealing and environmental protection are dedicated subsystem responsibilities.
* Materials and coatings require compatibility evaluation.

**Mitigation Actions:**

* Establish environmental exposure assumptions.
* Develop material and galvanic compatibility matrix.
* Identify intentionally wet, flooded, encapsulated, sealed, and dry regions.
* Evaluate coatings, encapsulants, seals, and penetrations.
* Conduct immersion and coupon testing where necessary.
* Include drainage, inspection, leak detection, and maintenance provisions.

**Trigger or Indicator:**

* Visible corrosion, galvanic attack, moisture intrusion, insulation degradation, swelling, seal leakage, fouling, or sensor instability.

**Target Completion:**
Initial controls before wet testing; continuing throughout prototype development.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-008; OI-013; MOD-005; AC-008; SF-008.

---

### RK-007 — Insufficient Hydrodynamic Performance or Excessive Cavitation

**Risk Statement:**
The propulsor may not achieve the desired thrust and efficiency or may experience unacceptable cavitation, vibration, or flow separation, resulting in poor system performance or redesign of the rotor and propulsor.

**Category:**
Hydrodynamic

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Propulsor geometry remains an open design decision.
* Hydrodynamic analysis and performance testing are required.
* Cavitation risk is explicitly included in the verification architecture.
* Experimental variants are permitted.

**Mitigation Actions:**

* Establish quantitative thrust and operating objectives.
* Perform propulsor and duct hydrodynamic analysis.
* Compare blade count, pitch, chord, and profile alternatives.
* Evaluate flow obstruction from supports and housing.
* Plan thrust, torque, vibration, and cavitation measurements.
* Preserve modularity for propulsor replacement.

**Trigger or Indicator:**

* Thrust, efficiency, vibration, acoustic behavior, or cavitation performance fails to meet established criteria.

**Target Completion:**
Progressively through hydrodynamic design and prototype testing.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
OI-001; OI-002; OI-015; MOD-001; EXT-006.

---

### RK-008 — Housing Deflection Alters Rotor Alignment

**Risk Statement:**
The structural housing and mounting system may deform sufficiently under thrust, reaction torque, support loads, electromagnetic forces, mounting distortion, or thermal effects to degrade rotor alignment or electromagnetic clearance.

**Category:**
Structural / Integration

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Housing stiffness and dimensional stability are explicit subsystem responsibilities.
* Structural load paths are defined.
* Clearance analysis must include housing deflection and mounting distortion.

**Mitigation Actions:**

* Establish structural load cases.
* Develop housing structural model.
* Analyze mounting-induced distortion.
* Include thermal deformation.
* Define stiffness and alignment requirements.
* Perform dimensional and static-load verification before high-energy operation.

**Trigger or Indicator:**

* Predicted or measured deformation materially consumes clearance margin or shifts rotor/stator alignment.

**Target Completion:**
Before release of the primary structural housing for integrated powered testing.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-005; OI-012; MOD-004; INT-004; INT-005; EXT-005.

---

### RK-009 — Inadequate Manufacturing Precision or Repeatability

**Risk Statement:**
Available fabrication methods may not achieve required concentricity, surface finish, dimensional stability, tolerance, or repeatability, resulting in poor fit, excessive rotor clearance variation, imbalance, or assembly inconsistency.

**Category:**
Manufacturing

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Manufacturability is an architectural driver.
* Critical datums and inspection methods are required.
* Experimental components are intended to remain modular and replaceable.
* Material and process verification is required.

**Mitigation Actions:**

* Assess available machining, additive-manufacturing, composite, and fabrication processes.
* Establish achievable tolerance ranges before final sizing.
* Perform fabrication coupons and trial components.
* Define inspection methods and gauges.
* Design adjustment capability where technically appropriate.
* Avoid tolerance-sensitive geometry that exceeds available manufacturing capability.

**Trigger or Indicator:**

* Trial parts repeatedly fail dimensional requirements, assembly requires uncontrolled fitting, or measured variation materially affects rotor alignment or performance.

**Target Completion:**
Before detailed release of tolerance-critical components.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-001; OI-020; MOD-001; MOD-002; MOD-003; MOD-004.

---

### RK-010 — Insufficient Instrumentation or Measurement Integrity

**Risk Statement:**
Instrumentation may be insufficiently accurate, fast, robust, or comprehensive to establish safe operating limits and validate analytical models, resulting in unreliable engineering conclusions or inability to diagnose failures.

**Category:**
Verification / Instrumentation

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Instrumentation is a dedicated architectural subsystem.
* Minimum data categories are established.
* Calibration and measurement uncertainty are explicitly required.
* Fault-data preservation is identified as a safety function.

**Mitigation Actions:**

* Define measurement objectives before sensor selection.
* Establish accuracy, range, resolution, and sampling requirements.
* Develop instrumentation channel list.
* Identify protective versus engineering-data sensors.
* Maintain calibration records.
* Perform uncertainty analysis for key performance measurements.
* Validate data synchronization and logging before powered tests.

**Trigger or Indicator:**

* Sensor saturation, excessive noise, inadequate sampling, calibration uncertainty, missing channels, inconsistent measurements, or inability to reconstruct an event.

**Target Completion:**
Before the Test Readiness Review for the first powered integrated test.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-006; OI-016; MOD-008; INT-010; INT-013; SF-012.

---

### RK-011 — Motor-Control Instability or Inadequate Protection

**Risk Statement:**
The motor-control system may not provide stable startup, commutation, operating control, limit enforcement, or fault response for the selected electromagnetic architecture, resulting in uncontrolled current, torque, speed, shutdown behavior, or prototype damage.

**Category:**
Control / Electrical

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Motor control is a dedicated subsystem.
* Defined operating states and startup preconditions exist.
* Protective functions include current, speed, thermal, cooling, sensor, and communication faults.
* Automatic restart following serious faults is prohibited.

**Mitigation Actions:**

* Select controller architecture only after electromagnetic topology is sufficiently defined.
* Bench-test control hardware before integration.
* Verify current, voltage, speed, and torque limits.
* Validate commutation and feedback behavior at reduced energy.
* Verify all relevant failure modes and interlocks.
* Independently verify emergency torque inhibition.

**Trigger or Indicator:**

* Unstable startup, current spikes, loss of synchronization, unexpected acceleration, incorrect fault response, failure to inhibit torque, or inconsistent restart behavior.

**Target Completion:**
Before unrestricted integrated powered testing.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-006; OI-017; OI-018; MOD-007; SF-001; SF-002; SF-003; SF-009; SF-011.

---

### RK-012 — Inadequate Test Facility or Support Equipment

**Risk Statement:**
Test equipment or facilities may not provide adequate electrical power, load reaction, water conditions, cooling, guarding, instrumentation, or measurement capacity, resulting in delayed testing, restricted verification, unsafe conditions, or invalid data.

**Category:**
Verification / Integration

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Prototype testing is treated as a controlled external interface.
* A dedicated test-adapter module is identified.
* Test readiness review is required before powered test phases.
* Facility capability is an explicit project dependency.

**Mitigation Actions:**

* Define preliminary power, thrust, torque, flow, immersion, and measurement requirements.
* Survey candidate facilities.
* Develop a test-stand concept early.
* Confirm structural reaction capacity.
* Confirm electrical supply and protection.
* Confirm water, cooling, guarding, and data-acquisition capability.
* Identify alternate test approaches if a single facility cannot support all objectives.

**Trigger or Indicator:**

* Facility capacity is lower than required, required instrumentation is unavailable, or test setup cannot provide safe and controlled operating conditions.

**Target Completion:**
Before final test-system architecture and first powered Test Readiness Review.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-007; OI-019; OI-023; MOD-009; EXT-004; EXT-005; EXT-006; EXT-008.

---

### RK-013 — Loss of Test Comparability Through Configuration Drift

**Risk Statement:**
Experimental changes may reduce comparability among tests if hardware, software, instrumentation, protective limits, or test conditions are not adequately identified and controlled, resulting in misleading conclusions or unusable test history.

**Category:**
Configuration / Verification

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Moderate

**Initial Rating:**
Moderate

**Existing Controls:**

* Configuration items are explicitly defined.
* Powered test configurations require identification.
* Temporary modifications must be documented.
* Test evidence must identify applicable configuration.

**Mitigation Actions:**

* Establish controlled configuration identifiers.
* Record module revisions and serial numbers.
* Record controller and firmware versions.
* Record sensor and calibration status.
* Record protective parameters and operating envelope.
* Preserve test procedures, raw data, and deviations.
* Require configuration audit before each significant test.

**Trigger or Indicator:**

* Test results cannot be traced to an exact configuration or changes occur without revision records.

**Target Completion:**
Configuration-control process established before first powered integrated test.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
OI-024; CI-001 through CI-013; MOD-001 through MOD-009.

---

### RK-014 — Prototype Architecture Does Not Scale Credibly

**Risk Statement:**
Prototype design choices may create unnecessary barriers to later scaling or redesign, resulting in conclusions that are useful only for the RDT-80 geometry or requiring fundamental architectural changes for larger or higher-power thrusters.

**Category:**
Scalability

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Moderate

**Initial Rating:**
Moderate

**Existing Controls:**

* Scalability is an architectural driver.
* Module boundaries are intended to preserve future design flexibility.
* DR-002 explicitly distinguishes prototype architecture from production design.

**Mitigation Actions:**

* Identify scaling-sensitive parameters during each major trade study.
* Distinguish prototype conveniences from fundamental architectural features.
* Record decisions that intentionally sacrifice scalability.
* Compare electromagnetic, structural, thermal, and hydrodynamic scaling behavior.
* Avoid unnecessary dependence on components available only at RDT-80 scale.

**Trigger or Indicator:**

* A proposed solution works only because of prototype dimensions, specialized one-off hardware, or scaling relationships that become technically unfavorable.

**Target Completion:**
Evaluated continuously during major architecture and subsystem decisions.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-009; architectural driver 4.1.8; module and subsystem trade studies.

---

### RK-015 — Cost, Lead-Time, or Complexity Growth

**Risk Statement:**
Project cost, component lead time, fabrication effort, or development complexity may increase substantially as unresolved architectural decisions are converted into detailed designs, resulting in delay, redesign, or inability to complete the intended prototype program.

**Category:**
Cost and Schedule

**Owner:**
Robert Schneider

**Likelihood:**
High

**Consequence:**
High

**Initial Rating:**
High

**Existing Controls:**

* Modular development is intended to limit full-system redesign.
* Major technical decisions require controlled trade studies.
* Availability and practical project resources are recognized assumptions.
* Supplier capability and cost are valid decision criteria.

**Mitigation Actions:**

* Perform early supplier and fabrication research.
* Estimate cost and lead time during major trade studies.
* Identify long-lead and single-source components.
* Prefer modular experiments before irreversible full-system fabrication.
* Maintain alternate components and fabrication approaches where practical.
* Sequence work so unresolved high-risk decisions do not trigger premature procurement.

**Trigger or Indicator:**

* Supplier quotations materially exceed assumptions, lead times threaten development sequence, or required fabrication becomes substantially more complex than planned.

**Target Completion:**
Managed continuously throughout development.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
AS-001; AS-006; AS-008; project dependencies; unresolved architectural issues.

---

### RK-016 — Cascading Prototype Damage During Early Powered Testing

**Risk Statement:**
A mechanical or electrical failure during early powered testing may damage multiple prototype modules before sufficient diagnostic data are collected, resulting in extensive rework, loss of evidence, higher cost, or delayed root-cause analysis.

**Category:**
Safety / Verification / Integration

**Owner:**
Robert Schneider

**Likelihood:**
Moderate

**Consequence:**
Critical

**Initial Rating:**
High

**Existing Controls:**

* Verification progresses from low-risk to higher-energy testing.
* Initial testing must use minimum practical energy.
* Operating-envelope expansion is incremental.
* Fault data and test configuration are required to be recorded.
* Rotor retention, electrical protection, and emergency shutdown are architectural functions.

**Mitigation Actions:**

* Establish strict initial current, voltage, speed, and duration limits.
* Use mechanical restraint and guarding.
* Instrument critical parameters before initial powered operation.
* Configure rapid protective shutdown.
* Inspect hardware between early test points.
* Preserve controller logs and pre-trigger data.
* Use sacrificial, replaceable, or modular components where appropriate.
* Do not expand the test envelope following unexplained anomalies.

**Trigger or Indicator:**

* Unexpected current, vibration, displacement, temperature rise, noise, contact, fault indications, loose hardware, or material damage occurs during early testing.

**Target Completion:**
Controls established before the first integrated powered test and maintained throughout operating-envelope expansion.

**Residual Rating:**
To be determined.

**Status:**
Open

**Related Items:**
RK-002; RK-003; RK-004; RK-005; RK-011; SF-003; SF-006; SF-007; SF-012; Section 10 verification architecture.

## 6. Risk Review and Maintenance

The Technical Risk Register shall be reviewed when:

* A major architectural decision is proposed or approved.
* A material assumption is validated, revised, or rejected.
* A trade study changes the preferred technical approach.
* A new component or supplier is selected.
* Preliminary CAD identifies a packaging or interface conflict.
* Analysis changes an expected structural, electromagnetic, thermal, or hydrodynamic margin.
* Fabrication experience reveals unexpected limitations.
* A test result differs materially from prediction.
* A significant anomaly or failure occurs.
* The operating envelope is expanded.
* A new hazard or failure mode is identified.
* Cost or schedule conditions materially change.

For each review, the project shall determine whether:

1. Likelihood has changed.
2. Consequence has changed.
3. Existing controls remain effective.
4. New mitigation actions are required.
5. Residual risk can be estimated.
6. The risk has been realized.
7. Formal acceptance is appropriate.
8. Closure is supported by sufficient evidence.

## 7. Risk Closure

A risk may be closed when:

* The underlying uncertainty has been eliminated.
* The affected technical approach has been abandoned.
* Verification demonstrates the risk is no longer material.
* The risk has been realized and transferred to controlled issue, anomaly, or corrective-action management.
* Another controlled risk record supersedes it.

Closure shall identify the supporting evidence and approval authority.

Risk identifiers shall not be reused after closure.
