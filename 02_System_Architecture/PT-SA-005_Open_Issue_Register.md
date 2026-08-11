# PT-SA-005 — Open-Issue Register

## Document Control

| Field          | Value                              |
| -------------- | ---------------------------------- |
| Project        | Project Triton                     |
| Document ID    | PT-SA-005                          |
| Document Title | Open-Issue Register                |
| Version        | 0.1                                |
| Status         | Draft — DR-002 Supporting Artifact |
| Owner          | Robert Schneider                   |
| Created        | 2026-08-11                         |
| Last Updated   | 2026-08-11                         |

## Revision History

| Version | Date       | Author           | Description                                                      |
| ------- | ---------- | ---------------- | ---------------------------------------------------------------- |
| 0.1     | 2026-08-11 | Robert Schneider | Initial open-issue register created from PT-SA-001 Section 11.17 |

## 1. Purpose

This document is the controlled register for unresolved architectural questions, missing inputs, decisions, dependencies, and technical actions associated with the Project Triton RDT-80.

The register implements the open-issue-management framework established in `PT-SA-001 — System Architecture`.

An open issue is a question, conflict, discrepancy, missing input, unresolved interface, or incomplete technical matter requiring documented resolution.

Open issues shall remain visible until they are:

* Resolved.
* Closed through an approved disposition.
* Transferred to an Architectural Decision Record.
* Converted into a controlled requirement.
* Converted into a technical risk.
* Converted into an analysis, test, procurement, or engineering task.
* Superseded by another controlled issue.

An issue shall not be considered closed solely because work has started.

## 2. Priority Definitions

| Priority     | Meaning                                                                                                                             |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Critical** | Resolution is required before continuation of affected architecture, safety, fabrication, or powered-test activities.               |
| **High**     | Resolution is required before a major downstream design commitment, procurement, fabrication, analysis baseline, or test milestone. |
| **Moderate** | Resolution is important but does not presently prevent controlled progress in unaffected areas.                                     |
| **Low**      | Resolution is desirable for completeness or future development but is not currently constraining major work.                        |

Priority may change as the project develops.

## 3. Status Definitions

| Status       | Meaning                                                                                                    |
| ------------ | ---------------------------------------------------------------------------------------------------------- |
| **Open**     | Issue has been identified but resolution work has not been completed.                                      |
| **In Work**  | Active analysis, research, trade study, design work, procurement, or testing is being performed.           |
| **Blocked**  | Resolution depends on another issue, decision, resource, supplier, test, or external event.                |
| **Resolved** | A technically supported answer or disposition has been established but final closure actions may remain.   |
| **Closed**   | Required actions are complete and the resolution has been incorporated into affected controlled artifacts. |

## 4. Initial Open Issues

### OI-001 — RDT-80 Thrust Objective

**Issue Statement:**
What continuous and peak thrust shall define the RDT-80 performance objective?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Define intended prototype mission and evaluation purpose.
* Establish preliminary continuous and peak thrust objectives.
* Identify associated duration requirements.
* Determine whether the objective is absolute thrust, thrust-per-power, scalability demonstration, or another primary metric.
* Transfer approved values into controlled system requirements.

**Dependencies:**

* OI-002 — Principal geometry.
* OI-003 — Voltage and power range.
* OI-015 — Propulsor geometry.
* Electromagnetic and hydrodynamic trade studies.

**Target Resolution:**
Before quantitative electromagnetic and hydrodynamic sizing is baselined.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; RK-007; AS-002.

---

### OI-002 — Principal Prototype Geometry

**Issue Statement:**
What rotor diameter, duct dimensions, and principal geometric envelope shall define the prototype?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Define initial rotor outer diameter.
* Define rotor inner diameter or propulsor flow diameter.
* Define allowable overall thruster envelope.
* Establish preliminary duct and housing dimensions.
* Evaluate manufacturability and test-facility compatibility.
* Record selected baseline geometry through an approved decision.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-003 — Power range.
* OI-004 — Electromagnetic topology.
* OI-015 — Propulsor geometry.
* OI-019 — Test configuration.

**Target Resolution:**
Before detailed preliminary CAD and electromagnetic sizing.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; RK-007; AS-002; AS-005.

---

### OI-003 — Operating Voltage and Power Range

**Issue Statement:**
What operating voltage and power range shall be used?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Establish candidate DC-bus or supply-voltage range.
* Define expected continuous and peak electrical power.
* Evaluate commercially available motor-control hardware.
* Evaluate conductor, insulation, protection, thermal, and safety implications.
* Confirm compatibility with available test power sources.
* Establish preliminary electrical operating envelope.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-004 — Electromagnetic topology.
* OI-017 — Motor controller.
* OI-019 — Test configuration.

**Target Resolution:**
Before final motor-controller selection and detailed electromagnetic design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; RK-011; AS-006; EXT-001.

---

### OI-004 — Electromagnetic Topology

**Issue Statement:**
What electromagnetic topology shall be selected?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Identify credible rim-drive motor topologies.
* Define evaluation criteria.
* Perform preliminary electromagnetic sizing.
* Compare torque density, losses, manufacturability, gap sensitivity, control complexity, cooling, material availability, and scalability.
* Document the selection in an Architectural Decision Record.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-002 — Geometry.
* OI-003 — Voltage and power.
* OI-005 — Stator architecture.
* OI-006 — Rotor electromagnetic configuration.

**Target Resolution:**
Before commitment to detailed rotor and stator design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; AS-002; MOD-001; MOD-002.

---

### OI-005 — Stator and Winding Architecture

**Issue Statement:**
What stator winding, core, insulation, and encapsulation architecture shall be used?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Evaluate stator-core options.
* Define candidate winding configuration.
* Define insulation strategy.
* Determine wet, dry, encapsulated, or hybrid environmental approach.
* Evaluate manufacturability, repairability, cooling, electrical stress, and corrosion exposure.
* Perform electrical and thermal analysis.
* Document the selected architecture.

**Dependencies:**

* OI-003 — Voltage and power.
* OI-004 — Electromagnetic topology.
* OI-013 — Environmental classification.
* OI-014 — Cooling architecture.

**Target Resolution:**
Before detailed stator CAD and winding fabrication.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; RK-005; RK-006; MOD-002.

---

### OI-006 — Rotor Electromagnetic Configuration

**Issue Statement:**
What permanent-magnet or rotor electromagnetic configuration shall be used?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Evaluate candidate magnet grades or alternative rotor electromagnetic elements.
* Define pole count and arrangement.
* Evaluate corrosion protection.
* Evaluate demagnetization limits.
* Evaluate temperature capability.
* Coordinate configuration with electromagnetic topology and retention strategy.

**Dependencies:**

* OI-004 — Electromagnetic topology.
* OI-007 — Rotor-element retention.
* OI-013 — Environmental classification.
* OI-014 — Cooling architecture.

**Target Resolution:**
Before detailed rotor electromagnetic design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-001; RK-004; MOD-001.

---

### OI-007 — Rotor Electromagnetic Element Retention

**Issue Statement:**
How shall rotor electromagnetic elements be retained?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Establish centrifugal, thermal, hydrodynamic, and electromagnetic load cases.
* Evaluate mechanical, adhesive, sleeve, pocket, encapsulated, or hybrid retention concepts.
* Consider corrosion, fatigue, inspection, manufacturability, and failure containment.
* Define required safety margin.
* Verify the selected approach analytically and experimentally.

**Dependencies:**

* OI-002 — Rotor geometry.
* OI-006 — Rotor electromagnetic configuration.
* OI-010 — Backup retention or containment.

**Target Resolution:**
Before high-energy rotor testing.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-004; SF-007; AC-009; MOD-001.

---

### OI-008 — Radial Rotor-Support Technology

**Issue Statement:**
What radial rotor-support technology shall be used?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Define expected radial loads and displacement limits.
* Evaluate candidate support technologies.
* Compare friction, wear, stiffness, damping, water compatibility, manufacturability, serviceability, and scalability.
* Evaluate startup, running, shutdown, and fault behavior.
* Conduct reduced-risk testing as required.
* Document the selected support architecture.

**Dependencies:**

* OI-002 — Geometry.
* OI-011 — Rotor-to-stator clearance.
* OI-012 — Housing architecture.
* OI-020 — Manufacturing capability.

**Target Resolution:**
Before detailed rotor-support and housing design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-002; RK-003; AS-004; MOD-003.

---

### OI-009 — Axial Rotor Support and Thrust Reaction

**Issue Statement:**
What axial rotor-support and thrust-reaction architecture shall be used?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Establish expected axial thrust and transient loads.
* Determine whether axial load is reacted through dedicated thrust bearings, distributed supports, hydrodynamic features, or another method.
* Evaluate wear, friction, alignment, cooling, serviceability, and fault behavior.
* Coordinate with structural load paths and rotor retention.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-002 — Geometry.
* OI-008 — Radial support.
* OI-010 — Backup retention.
* OI-012 — Housing architecture.

**Target Resolution:**
Before detailed rotor-support design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-002; AS-004; MOD-003; INT-003; INT-004.

---

### OI-010 — Backup Rotor Retention and Containment

**Issue Statement:**
What backup retention or containment features are required?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Identify credible rotor, bearing, magnet, blade, and structural failure modes.
* Estimate stored rotational energy.
* Determine whether catch bearings, retention rings, shoulders, guards, containment structures, or another backup feature is required.
* Define acceptable failure motion and containment loads.
* Coordinate with hazard analysis.

**Dependencies:**

* OI-007 — Rotor-element retention.
* OI-008 — Radial support.
* OI-009 — Axial support.
* Final speed envelope.

**Target Resolution:**
Before operation at hazardous rotational energy.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-002; RK-004; SF-007; AC-009.

---

### OI-011 — Rotor-to-Stator Clearance

**Issue Statement:**
What nominal and minimum rotor-to-stator clearances are required?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Establish electromagnetic performance sensitivity to gap.
* Establish mechanical minimum clearance.
* Perform tolerance stack-up.
* Include rotor motion, wear, housing deformation, mounting distortion, and thermal expansion.
* Define inspection and service limits.
* Determine whether active displacement monitoring is required.

**Dependencies:**

* OI-002 — Geometry.
* OI-008 — Radial support.
* OI-009 — Axial support.
* OI-012 — Housing.
* OI-020 — Manufacturing tolerance.

**Target Resolution:**
Before powered rotor operation.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-002; RK-003; AS-005; Section 9.7.

---

### OI-012 — Housing Material and Architecture

**Issue Statement:**
What housing material, segmentation, and manufacturing process shall be used?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Define structural, stiffness, environmental, manufacturing, and serviceability requirements.
* Evaluate metallic, polymeric, composite, additive, machined, fabricated, or hybrid construction.
* Evaluate segmentation and access strategy.
* Analyze structural deformation.
* Coordinate with rotor support, stator retention, seals, cooling, and mounting.

**Dependencies:**

* OI-002 — Geometry.
* OI-008 — Radial support.
* OI-009 — Axial support.
* OI-013 — Environmental classification.
* OI-020 — Manufacturing capability.

**Target Resolution:**
Before detailed housing CAD.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-003; RK-006; RK-008; RK-009; MOD-004.

---

### OI-013 — Environmental Region Classification

**Issue Statement:**
Which regions shall be wet-exposed, flooded, encapsulated, sealed and dry, or pressure-compensated?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Identify all electrical, magnetic, structural, bearing, and instrumentation regions.
* Assign intended environmental classification.
* Define boundaries and penetrations.
* Evaluate pressure, leakage, condensation, drainage, corrosion, and inspection implications.
* Coordinate with stator, bearings, sensors, and cooling architecture.

**Dependencies:**

* OI-005 — Stator architecture.
* OI-006 — Rotor electromagnetic configuration.
* OI-012 — Housing.
* OI-014 — Cooling.

**Target Resolution:**
Before detailed sealing, electrical-penetration, and cooling design.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-006; AS-008; MOD-005; Section 6.9.

---

### OI-014 — Cooling Architecture

**Issue Statement:**
What cooling architecture shall be used for the stator, rotor support, and power electronics?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Estimate heat generation for major components.
* Evaluate direct-water, conductive, internal-loop, external-loop, or hybrid cooling.
* Define heat-transfer paths.
* Evaluate fouling, leakage, trapped air, corrosion, flow loss, and test-system complexity.
* Establish cooling monitoring and protective requirements.

**Dependencies:**

* OI-003 — Power range.
* OI-005 — Stator architecture.
* OI-013 — Environmental classification.
* OI-017 — Motor controller.

**Target Resolution:**
Before approval of sustained powered operation.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-005; AS-003; MOD-006; SF-004; SF-005.

---

### OI-015 — Propulsor Geometry and Attachment

**Issue Statement:**
What propulsor blade count, geometry, pitch, and attachment method shall be used?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Establish hydrodynamic operating objectives.
* Evaluate blade count, chord, pitch, profile, skew, and flow area.
* Evaluate duct interaction.
* Evaluate structural and centrifugal loads.
* Determine removable versus integral blade architecture.
* Evaluate cavitation and vibration.
* Coordinate with rotor balance and manufacturability.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-002 — Geometry.
* OI-020 — Manufacturing capability.

**Target Resolution:**
Before fabrication of the first performance-test propulsor.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-007; MOD-001.

---

### OI-016 — Required Sensors and Instrumentation

**Issue Statement:**
What position, speed, temperature, displacement, vibration, and ingress sensors are required?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Define control, safety, diagnostic, and engineering measurement needs.
* Separate safety-critical channels from engineering-only channels.
* Establish range, accuracy, resolution, sampling, environmental, and response requirements.
* Identify calibration requirements.
* Define minimum channels for first powered operation.

**Dependencies:**

* OI-008 — Rotor support.
* OI-011 — Clearance.
* OI-014 — Cooling.
* OI-017 — Motor controller.
* OI-018 — Protective architecture.
* OI-019 — Test system.

**Target Resolution:**
Before detailed instrumentation design and first powered Test Readiness Review.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-010; AS-006; MOD-008; SF-012.

---

### OI-017 — Motor Controller and Commutation

**Issue Statement:**
What motor controller, commutation method, and control mode shall be used?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Define motor electrical characteristics.
* Identify candidate controllers or inverter platforms.
* Determine rotor position or sensorless commutation approach.
* Determine primary speed, torque, current, or other control mode.
* Evaluate startup behavior.
* Evaluate fault response, communications, configurability, and data logging.
* Bench-test before integrated use.

**Dependencies:**

* OI-003 — Voltage and power.
* OI-004 — Electromagnetic topology.
* OI-016 — Instrumentation.
* OI-018 — Safety functions.

**Target Resolution:**
Before integrated powered testing.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-011; AS-006; MOD-007.

---

### OI-018 — Independent Safety and Power-Isolation Features

**Issue Statement:**
What independent emergency-stop, overspeed, and power-isolation features are required?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Conduct preliminary hazard analysis.
* Define emergency torque-inhibit architecture.
* Determine contactor and electrical-isolation strategy.
* Determine need for independent overspeed protection.
* Determine required sensor redundancy.
* Define reset and restart requirements.
* Define stored-energy discharge provisions.

**Dependencies:**

* OI-003 — Power range.
* OI-016 — Instrumentation.
* OI-017 — Motor controller.
* Hazard analysis.

**Target Resolution:**
Before first integrated powered test.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-011; SF-001 through SF-012; Section 8.

---

### OI-019 — Prototype Test Configuration

**Issue Statement:**
What test stand, water environment, mounting arrangement, and load-measurement approach shall be used?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Define candidate test environments.
* Establish required thrust and torque reaction capacity.
* Define immersion and flow conditions.
* Determine load-cell or thrust-measurement architecture.
* Determine electrical power and cooling interfaces.
* Define guarding and exclusion-zone controls.
* Evaluate facility availability and cost.

**Dependencies:**

* OI-001 — Thrust objective.
* OI-002 — Geometry.
* OI-003 — Power range.
* OI-016 — Instrumentation.
* OI-023 — Test progression and authority.

**Target Resolution:**
Before first powered Test Readiness Review.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-012; AS-007; MOD-009; EXT-004 through EXT-008.

---

### OI-020 — Manufacturing Tolerances and Inspection Capability

**Issue Statement:**
What manufacturing tolerances and inspection methods are achievable?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Identify candidate fabrication methods.
* Assess machine, additive, composite, and supplier capabilities as applicable.
* Establish realistic dimensional tolerances.
* Identify measurement and inspection equipment.
* Conduct fabrication trials where uncertainty is significant.
* Feed achievable tolerances into clearance and structural analyses.

**Dependencies:**

* OI-002 — Geometry.
* OI-008 — Rotor support.
* OI-011 — Clearance.
* OI-012 — Housing.
* OI-015 — Propulsor design.

**Target Resolution:**
Before release of tolerance-critical detailed designs.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-003; RK-009; AS-001.

---

### OI-021 — Engineering Analysis Software

**Issue Statement:**
What software tools shall be used for electromagnetic, structural, thermal, hydrodynamic, and rotor-dynamic analysis?

**Owner:**
Robert Schneider

**Priority:**
Moderate

**Required Action:**

* Identify candidate software for each engineering discipline.
* Evaluate cost, licensing, capability, validation history, learning curve, interoperability, and file preservation.
* Identify whether analytical calculations or open-source tools are sufficient for any discipline.
* Establish model naming, version, and storage conventions.

**Dependencies:**

* Analysis needs identified in PT-SA-001 Section 10.5.
* Project budget and available computing resources.

**Target Resolution:**
Before each discipline begins controlled analytical work.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
Section 10.5; Section 14.8.

---

### OI-022 — Standards and Marine Engineering Practices

**Issue Statement:**
What standards, codes, or marine-design practices shall be adopted for the prototype phase?

**Owner:**
Robert Schneider

**Priority:**
Moderate

**Required Action:**

* Research potentially applicable standards and engineering practices.
* Evaluate applicability to prototype safety, electrical design, rotating machinery, materials, ingress protection, EMC, testing, and marine use.
* Record specific editions and adopted clauses.
* Distinguish mandatory requirements from voluntary engineering guidance.
* Establish controlled reference entries.

**Dependencies:**

* Intended test environment.
* Future vessel-integration plans.
* Safety and electrical architecture.
* Certification or commercialization objectives.

**Target Resolution:**
Initial prototype standards set before detailed design requirements are baselined.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
AS-012; Section 14.5.

---

### OI-023 — Operating-Envelope Progression and Test Authority

**Issue Statement:**
What operating-envelope progression and test-readiness authority shall govern powered testing?

**Owner:**
Robert Schneider

**Priority:**
Critical

**Required Action:**

* Define authority to approve powered-test phases.
* Define Test Readiness Review process.
* Establish initial restricted operating envelope.
* Define permissible increments in speed, current, voltage, power, and duration.
* Establish hold points and abort criteria.
* Define evidence required before envelope expansion.

**Dependencies:**

* OI-016 — Instrumentation.
* OI-018 — Safety architecture.
* OI-019 — Test configuration.
* Hazard and structural analyses.

**Target Resolution:**
Before first powered integrated test.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
AS-010; RK-016; Sections 10.11 and 10.19.

---

### OI-024 — Configuration-Management Tools and Identifiers

**Issue Statement:**
What configuration-management tools and identifiers shall be used for hardware, software, analyses, and tests?

**Owner:**
Robert Schneider

**Priority:**
High

**Required Action:**

* Define document and artifact identifier conventions.
* Define hardware part, revision, and serial-number conventions.
* Define software and firmware versioning.
* Define test-configuration identifiers.
* Define model and analysis identifiers.
* Define revision and release workflow.
* Define use of GitHub and other controlled repositories.
* Establish rules for superseded and archived artifacts.

**Dependencies:**

* Existing Project Triton repository structure.
* PT-SA document conventions.
* Future CAD, software, analysis, and test workflows.

**Target Resolution:**
Before substantial controlled CAD, software, or prototype configuration data are generated.

**Status:**
Open

**Resolution:**
Not yet resolved.

**Related Items:**
RK-013; Section 9 configuration architecture; Section 13.11.

## 5. Issue Resolution and Transfer

An open issue may be transferred to another controlled artifact when appropriate.

Typical transfers include:

| Issue Outcome                      | Controlled Destination           |
| ---------------------------------- | -------------------------------- |
| Significant architecture choice    | Architectural Decision Record    |
| Mandatory system behavior or limit | System or subsystem requirement  |
| Uncertain adverse condition        | Technical Risk Register          |
| Unverified planning basis          | Architecture Assumption Register |
| Detailed engineering evaluation    | Analysis task or report          |
| Alternative comparison             | Trade study                      |
| Experimental resolution            | Test plan or test procedure      |
| Supplier-dependent resolution      | Procurement or supplier action   |
| Fabrication-dependent resolution   | Manufacturing task               |
| Review deficiency                  | DR finding or corrective action  |

Transfer shall not close the original issue until the receiving record exists and the relationship is documented.

## 6. Issue Closure

An issue may be closed when:

1. A technically adequate resolution has been established.
2. Required approvals are complete.
3. Affected project artifacts have been updated.
4. Related risks and assumptions have been reviewed.
5. Required downstream actions have been assigned or completed.
6. Closure evidence is identified.

Issue identifiers shall not be reused after closure.

## 7. Register Maintenance

The Open-Issue Register shall be reviewed when:

* A major architectural decision is made.
* A new technical dependency is identified.
* A material assumption changes.
* A risk is realized.
* A trade study is completed.
* Preliminary CAD reveals a conflict.
* Supplier information materially changes an approach.
* Fabrication exposes a capability limitation.
* Testing reveals unexpected behavior.
* A formal review produces new findings.
* A project milestone changes the priority or timing of unresolved work.

Each review shall confirm:

* Issue priority.
* Owner.
* Dependencies.
* Target resolution.
* Current status.
* Related controlled records.
* Whether the issue should be transferred, resolved, or closed.
