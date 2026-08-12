# Project Triton
## System Requirements

---

## Document Control

| Field | Value |
|---|---|
| Project | Project Triton |
| Document ID | PT-REQ-001 |
| Document Title | System Requirements |
| Version | 0.3 |
| Status | Draft |
| Owner | Robert Schneider |
| Created | 2026-08-11 |
| Last Updated | 2026-08-11 |
| Architecture Baseline | PT-SA-001 Version 1.0 |
| Architecture Baseline Tag | DR-002-v1.0 |

---

## Revision History

| Version | Date | Description |
|---|---|---|
| 0.1 | 2026-08-11 | Initial system requirements draft developed following DR-002 approval; established SR-001 through SR-082, requirements traceability, and ORD-001 through ORD-032 |
| 0.2 | 2026-08-11 | Incorporated PT-AN-001 thrust-objective analysis; quantified SR-054 and SR-055, updated associated requirements traceability, and partially resolved ORD-001 and ORD-015 |
| 0.3 | 2026-08-11 | Incorporated PT-AN-002 principal prototype geometry analysis; added the 90 mm nominal propulsor-diameter requirement, updated associated requirements traceability, and partially resolved ORD-016 |

---

## 1. Purpose

This document defines the system-level requirements for the Project Triton rim-driven thruster system.

The requirements established herein shall translate the approved system architecture into measurable, traceable, and verifiable engineering requirements suitable for subsequent subsystem design, analysis, trade studies, prototype development, and verification planning.

---

## 2. Scope

This document applies to the Project Triton rim-driven thruster system and its defined system boundary.

System requirements will address, as applicable:

- Functional performance
- Mechanical architecture
- Hydrodynamic performance
- Electromagnetic drive
- Rotor support and retention
- Structural integrity
- Electrical power
- Motor control
- Sealing and environmental protection
- Thermal management
- Instrumentation and sensing
- Safety and protection
- Interfaces
- Prototype testability
- Maintainability
- Manufacturing constraints

---

## 3. Governing Architecture

The governing architecture for this requirements document is:

**PT-SA-001 — System Architecture, Version 1.0**

approved through:

**DR-002 — System Architecture Review**

and configuration-controlled by Git tag:

**DR-002-v1.0**

Requirements developed in this document shall remain consistent with that architecture unless an approved architecture change is made through configuration control.

---

## 4. Requirement Development Rules

Requirements shall:

1. Be assigned a unique identifier.
2. State one principal requirement per requirement statement wherever practical.
3. Use mandatory language such as **shall** for binding requirements.
4. Be measurable or objectively assessable.
5. Avoid prescribing a specific design solution unless that solution is an approved architectural constraint.
6. Identify the source or rationale for the requirement.
7. Define an intended verification method.
8. Be traceable to applicable architecture elements, assumptions, risks, open issues, or higher-level project objectives.
9. Avoid unsupported numerical limits until those values have been established through analysis, trade study, test, or approved design decision.
10. Be maintained under configuration control.

---

## 5. Requirement Identification Scheme

System-level requirements shall use the following identifier format:

**SR-###**

Example:

**SR-001**

Subsystem requirements, when developed, will use separate subsystem-specific identifiers and trace to the applicable system-level requirement.

---

## 6. Requirement Verification Methods

The following verification-method identifiers will be used:

| ID | Method | Description |
|---|---|---|
| VM-001 | Inspection | Verification through visual examination, dimensional measurement, documentation review, material certification, configuration confirmation, or workmanship assessment |
| VM-002 | Analysis | Verification using engineering calculations, numerical models, simulations, tolerance studies, material data, or other analytical methods |
| VM-003 | Demonstration | Verification through operation or manipulation that establishes observable functionality without requiring extensive quantitative measurement |
| VM-004 | Test | Verification through controlled application of inputs and quantitative measurement of outputs under defined conditions |
| VM-005 | Similarity | Verification based on an approved comparison with previously verified hardware, materials, processes, or configurations |
| VM-006 | Certification or Record Review | Verification through approved supplier records, calibration records, compliance documentation, or other controlled evidence |

These verification-method identifiers are inherited from PT-SA-001 Section 10.2 and shall be used consistently throughout Project Triton requirements and verification records.

Multiple methods may be assigned to a requirement when appropriate.

---

## 6.1 Requirement Development Sequence

System requirements shall be developed in the following sequence so that downstream requirements are derived from established upstream needs and constraints.

### Phase 1 — Mission and Architectural Constraints

Establish requirements that are already inherent in the approved system architecture and project purpose and do not depend on unresolved sizing or performance decisions.

This phase includes:

- System purpose and primary function
- Rim-driven propulsion architecture
- Annular rotor configuration
- Absence of a conventional central propulsion shaft or through-hub drive train
- Major system-boundary requirements
- Required subsystem functions
- Fundamental environmental operating context
- Basic safety and testability principles

### Phase 2 — Primary Design Drivers

Resolve and establish the quantitative system parameters that control subsequent sizing and design.

Priority open issues are:

1. OI-001 — Required thrust/performance objective
2. OI-002 — Principal thruster geometry
3. OI-003 — Electrical voltage and power envelope

These parameters shall not be assigned arbitrary values solely to complete the requirements document.

Where a requirement depends upon an unresolved parameter, the requirement shall either:

- remain explicitly TBD and trace to the controlling Open Issue; or
- be written parametrically without establishing an unsupported numerical value.

### Phase 3 — Derived Performance Requirements

Following establishment of the primary design drivers, derive requirements for:

- Hydrodynamic performance
- Propulsor operating range
- Rotational-speed envelope
- Torque
- Electrical input power
- Efficiency
- Thermal loading
- Structural loading
- Rotor support loads
- Clearance requirements

### Phase 4 — Subsystem and Interface Requirements

Develop requirements governing interaction among the principal system elements, including:

- Propulsor and rotor
- Electromagnetic drive
- Rotor support and retention
- Structural housing
- Motor controller
- Electrical power source
- Sensors and instrumentation
- Environmental barriers
- Thermal paths
- Prototype test interfaces

### Phase 5 — Protection, Safety, and Fault Requirements

Develop requirements for:

- Rotor containment
- Mechanical retention
- Electrical protection
- Power isolation
- Overcurrent protection
- Overtemperature protection
- Overspeed protection
- Loss-of-control response
- Sensor-failure response
- Emergency shutdown
- Safe prototype testing

Safety-critical requirements shall not be considered mature solely through AI-assisted review. Appropriate independent qualified human review shall be incorporated before hazardous powered testing or safety-critical design approval.

### Phase 6 — Verification and Traceability Closure

For every system-level requirement:

1. Confirm a defined verification method.
2. Confirm traceability to its source.
3. Confirm that unresolved assumptions, risks, and open issues are identified.
4. Check for conflicts or duplication.
5. Confirm that acceptance criteria are objectively assessable.
6. Resolve or explicitly disposition all TBD values required for baseline approval.

Only after this process is complete shall the system requirements be considered ready for formal requirements review.

---

## 7. System-Level Requirements

### 7.1 Mission and Functional Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-001 | The RDT-80 prototype shall convert supplied electrical power into controlled hydrodynamic thrust. | VM-004 | Draft |
| SR-002 | The RDT-80 shall generate propulsor torque through an annular rim-driven rotor and shall not use a conventional central propulsion shaft or through-hub drivetrain. | VM-001 | Draft |
| SR-003 | The RDT-80 shall control electromagnetic torque applied to the annular rotor in response to commanded operation so that propulsor operation and resulting hydrodynamic thrust are controllable. | VM-003, VM-004 | Draft |
| SR-004 | The RDT-80 shall transfer electromagnetic drive torque directly from the annular rotor to the propulsor without an intermediate gearbox, belt drive, chain drive, or conventional shaft transmission. | VM-001 | Draft |
| SR-005 | The RDT-80 shall maintain a central propulsor flow passage that is free of a conventional propulsion shaft, shaft-support structure, or centrally mounted drive motor. | VM-001 | Draft |

### 7.2 Propulsive Performance Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-054 | The RDT-80 shall produce not less than 7.0 kgf (68.6 N) forward static thrust while operating within the approved continuous operating envelope under defined reference test conditions. | VM-002, VM-004 | Draft |
| SR-055 | The RDT-80 shall produce not less than 10.0 kgf (98.1 N) forward static thrust for the approved peak operating duration while operating within the approved peak operating envelope and defined reference test conditions. | VM-002, VM-004 | Draft |
| SR-056 | The RDT-80 shall provide controllable thrust over the approved operating range in response to valid operating commands. | VM-003, VM-004 | Draft |
| SR-057 | The RDT-80 propulsor and duct geometry shall be defined by configuration-controlled principal dimensions sufficient to support hydrodynamic, structural, electromagnetic, manufacturing, and test analyses. | VM-001 | Draft |
| SR-058 | The RDT-80 shall operate within approved rotor-speed, torque, electrical-input, and thrust limits established through requirements, analysis, and test evidence. | VM-002, VM-004 | Draft |
| SR-059 | The RDT-80 hydrodynamic design shall achieve an approved minimum propulsive-performance criterion under defined reference conditions. | VM-002, VM-004 | Draft |
| SR-060 | The RDT-80 shall operate without cavitation exceeding the approved acceptance criterion throughout the portion of the operating envelope designated for normal continuous operation. | VM-002, VM-004 | Draft |
| SR-061 | The RDT-80 shall operate without hydrodynamically induced vibration exceeding approved limits throughout the authorized operating envelope. | VM-002, VM-004 | Draft |
| SR-062 | The propulsor blade count, geometry, pitch, and attachment configuration shall be defined and configuration-controlled before performance verification testing is used to establish compliance with system thrust requirements. | VM-001 | Draft |
| SR-083 | The initial RDT-80 prototype shall use a nominal propulsor diameter of 90 mm. | VM-001 | Draft |

### 7.3 Mechanical and Structural Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-009 | The RDT-80 structural housing shall provide a continuous load path capable of reacting the mechanical, hydrodynamic, electromagnetic, and rotor-support loads generated throughout the approved operating envelope and transferring those loads to the system mounting interface. | VM-002, VM-001, VM-004 | Draft |
| SR-010 | The RDT-80 structural housing shall maintain the relative position and alignment of the rotor-support interfaces, stationary electromagnetic components, and rotor-containment features within limits necessary to satisfy rotor-clearance requirements throughout the approved operating envelope. | VM-002, VM-001, VM-004 | Draft |

### 7.4 Electromagnetic Drive Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-063 | The RDT-80 electromagnetic drive shall produce sufficient torque to operate the annular rotor and propulsor throughout the approved operating envelope. | VM-002, VM-004 | Draft |
| SR-064 | The electromagnetic-drive topology shall be compatible with the approved annular rim-driven architecture and shall transfer electromagnetic torque directly to the rotor without a conventional central motor shaft or intermediate mechanical transmission. | VM-002, VM-001 | Draft |
| SR-065 | The electromagnetic drive shall operate within the approved system voltage, current, power, speed, torque, and thermal limits throughout the authorized operating envelope. | VM-002, VM-004 | Draft |
| SR-066 | The rotor and stator electromagnetic elements shall maintain the relative geometry and electromagnetic clearance necessary for required operation throughout the approved operating envelope. | VM-002, VM-001, VM-004 | Draft |
| SR-067 | Permanent magnets, magnetic inserts, laminations, windings, conductors, or other electromagnetic-drive elements subjected to rotational, electromagnetic, thermal, hydrodynamic, or environmental loads shall be positively retained against unacceptable movement or separation throughout the approved operating envelope. | VM-002, VM-001, VM-004 | Draft |
| SR-068 | The electromagnetic-drive design shall limit electrical, magnetic, mechanical, and thermal losses sufficiently to satisfy the approved system performance and thermal requirements. | VM-002, VM-004 | Draft |
| SR-069 | The electromagnetic drive shall avoid torque ripple, cogging, electromagnetic excitation, or other periodic effects exceeding approved limits that could produce unacceptable vibration, noise, control instability, or mechanical loading. | VM-002, VM-004 | Draft |
| SR-070 | Electromagnetic-drive materials and insulation systems shall maintain required electrical and magnetic performance throughout the approved temperature and submerged environmental conditions. | VM-002, VM-001, VM-004 | Draft |
| SR-071 | The electromagnetic-drive configuration, winding arrangement, magnetic-element configuration, and other performance-critical electromagnetic parameters shall be defined and configuration-controlled before formal electromagnetic performance verification testing. | VM-001 | Draft |

### 7.5 Rotor Support and Retention Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-006 | The RDT-80 shall provide radial and axial support and retention of the annular rotor throughout its approved operating envelope while permitting the rotor to rotate as required for commanded operation. | VM-002, VM-001, VM-004 | Draft |
| SR-007 | The RDT-80 shall provide a secondary mechanical retention or containment feature that prevents uncontrolled separation of the annular rotor from the thruster housing following loss or failure of the primary rotor support or retention function within defined design conditions. | VM-002, VM-001, VM-004 | Draft |
| SR-008 | The RDT-80 shall maintain sufficient radial and axial clearance between the rotating annular rotor and stationary thruster structure to prevent unintended mechanical contact throughout the approved operating envelope. | VM-002, VM-001, VM-004 | Draft |

### 7.6 Electrical Power and Motor Control Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-015 | The RDT-80 shall accept electrical power through a defined external power interface and provide that power to the motor-control and electromagnetic-drive functions necessary for commanded operation. | VM-001, VM-003, VM-004 | Draft |
| SR-016 | The RDT-80 motor-control function shall convert commanded operation into controlled electrical excitation of the electromagnetic drive sufficient to produce the required rotor torque and rotational behavior. | VM-003, VM-004 | Draft |
| SR-017 | The RDT-80 shall provide a means to positively isolate electrical power from the motor-control and electromagnetic-drive functions independently of the normal commanded operating state. | VM-001, VM-003, VM-004 | Draft |
| SR-072 | The RDT-80 control architecture shall implement defined operating states that include, at minimum, De-Energized, Safe/Disabled, Initialization, Ready, Starting, Running, Controlled Stop, Fault-Limited, Fault Shutdown, Emergency Stop, and Maintenance/Configuration. | VM-001, VM-003, VM-004 | Draft |
| SR-073 | The RDT-80 shall transition between operating states only through defined and configuration-controlled transition logic, and commands capable of producing powered rotor motion shall be accepted only when the required safety conditions and operating interlocks are satisfied. | VM-001, VM-003, VM-004 | Draft |
| SR-074 | Before transition into the Starting state, the RDT-80 shall verify all applicable startup preconditions required by the approved test configuration and operating envelope. | VM-001, VM-003, VM-004 | Draft |
| SR-075 | Following Fault Shutdown or Emergency Stop, the RDT-80 shall not return to Ready until rotor motion is stopped or otherwise in an explicitly approved safe condition, the initiating condition has been identified, required corrective action has been completed, fault indications have been deliberately reset, and required initialization and interlock checks have been repeated. | VM-001, VM-003, VM-004 | Draft |

### 7.7 Environmental and Sealing Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-011 | The RDT-80 shall protect electrical, electromagnetic, structural, and mechanical elements from water exposure and environmental degradation to the extent necessary to maintain required system function throughout the approved operating environment. | VM-002, VM-001, VM-004 | Draft |
| SR-012 | The RDT-80 shall electrically isolate energized conductors and electrical connections from the surrounding conductive-water environment throughout the approved operating envelope, except where intentional electrical exposure is specifically required by an approved design. | VM-001, VM-004 | Draft |
| SR-013 | The RDT-80 shall use materials, coatings, finishes, and material combinations that maintain required structural, electrical, magnetic, and mechanical performance throughout the approved operating environment without unacceptable corrosion or environmentally induced degradation. | VM-002, VM-001, VM-004 | Draft |

### 7.8 Thermal Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-014 | The RDT-80 shall provide thermal paths sufficient to dissipate internally generated heat and maintain temperature-sensitive components within their approved operating temperature limits throughout the approved operating envelope. | VM-002, VM-004 | Draft |

### 7.9 Instrumentation and Protection Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-018 | The RDT-80 shall detect electrical current conditions that exceed approved operating limits and shall initiate a protective response that prevents unacceptable damage to the motor-control, electromagnetic-drive, power-distribution, or associated electrical components. | VM-002, VM-003, VM-004 | Draft |
| SR-019 | The RDT-80 shall monitor temperatures at locations necessary to detect thermal conditions that exceed approved operating limits and shall initiate a protective response before unacceptable thermal damage occurs. | VM-002, VM-003, VM-004 | Draft |
| SR-020 | The RDT-80 shall detect rotor-speed conditions that exceed approved operating limits and shall initiate a protective response before the rotor reaches a speed that could produce unacceptable mechanical or safety risk. | VM-002, VM-003, VM-004 | Draft |
| SR-021 | The RDT-80 shall detect loss, invalidity, or failure of the normal command or motor-control function and shall transition to a defined protective state that prevents uncontrolled rotor operation. | VM-003, VM-004 | Draft |
| SR-022 | The RDT-80 shall detect loss, invalidity, or implausibility of safety-critical sensor inputs and shall transition to a defined protective state when continued operation cannot be shown to remain within approved limits. | VM-003, VM-004 | Draft |
| SR-023 | The RDT-80 shall provide an emergency shutdown function that can terminate powered rotor operation independently of the normal operating command path. | VM-001, VM-003, VM-004 | Draft |
| SR-076 | The RDT-80 shall detect DC-bus or supply overvoltage, undervoltage, and short-circuit conditions that exceed approved limits and shall initiate the defined protective response. | VM-002, VM-003, VM-004 | Draft |
| SR-077 | The RDT-80 shall detect loss or inadequacy of required cooling when continued powered operation could cause an approved thermal limit to be exceeded and shall initiate the defined protective response. | VM-002, VM-003, VM-004 | Draft |
| SR-078 | The RDT-80 shall detect rotor obstruction, stall, or abnormal acceleration when such conditions could result in operation outside approved mechanical, electrical, thermal, or control limits and shall initiate the defined protective response. | VM-002, VM-003, VM-004 | Draft |
| SR-079 | Where vibration or mechanical displacement is monitored for protection, the RDT-80 shall detect values exceeding approved protective limits and shall initiate the defined protective response. | VM-002, VM-003, VM-004 | Draft |
| SR-080 | Where protected volumes are required to remain free of unintended water ingress, the RDT-80 shall detect applicable ingress conditions before continued operation could create unacceptable electrical, mechanical, or environmental risk and shall initiate the defined protective response. | VM-001, VM-003, VM-004 | Draft |
| SR-081 | The RDT-80 shall detect loss of communications with control equipment required for safe powered operation and shall transition to the approved protective state. | VM-003, VM-004 | Draft |
| SR-082 | The RDT-80 shall detect failure or loss of a required operating or safety interlock and shall prevent initiation or continuation of powered rotor operation unless an explicitly approved fault-limited condition permits continued operation. | VM-001, VM-003, VM-004 | Draft |

### 7.10 Interface Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-025 | The RDT-80 shall provide a defined external electrical-power interface that establishes the required electrical connection, polarity, conductor configuration, and interface ratings necessary for safe and correct connection to the approved power source. | VM-001, VM-004 | Draft |
| SR-026 | The RDT-80 shall provide a defined command interface through which the motor-control function receives authorized operating commands and control inputs. | VM-001, VM-003, VM-004 | Draft |
| SR-027 | The RDT-80 shall provide a defined mechanical mounting interface that establishes the geometry and load-transfer features necessary to install the thruster into an approved mounting structure or test fixture. | VM-002, VM-001, VM-004 | Draft |
| SR-028 | The RDT-80 shall provide defined instrumentation and data interfaces sufficient to acquire, transmit, or record the system parameters required for development testing, protection functions, and verification activities. | VM-001, VM-003, VM-004 | Draft |
| SR-029 | The RDT-80 shall provide test and service interfaces that permit required diagnostic, measurement, configuration, and maintenance activities without requiring defeat of mandatory safety or protection functions during normal approved procedures. | VM-001, VM-003 | Draft |

### 7.11 Safety Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-030 | The RDT-80 shall provide a defined safe state in which commanded electromagnetic torque cannot be produced and unintended powered rotor operation is prevented. | VM-001, VM-003, VM-004 | Draft |
| SR-031 | Following activation of an emergency shutdown or safety-critical protective response, the RDT-80 shall remain in a non-operating state until a deliberate reset action has occurred and a new valid operating command is received. | VM-003, VM-004 | Draft |
| SR-032 | The RDT-80 shall provide a means by which the absence or isolation of hazardous electrical power can be verified before maintenance, adjustment, assembly, or other activities requiring personnel interaction with potentially energized components. | VM-001, VM-003 | Draft |
| SR-033 | The RDT-80 prototype and its approved test configuration shall provide physical restraint, guarding, containment, or equivalent protective measures sufficient to prevent personnel exposure to unacceptable hazards associated with rotating-component release or unintended mechanical contact during authorized powered testing. | VM-002, VM-001, VM-004 | Draft |
| SR-034 | Safety-critical protection functions shall be implemented such that a single normal operating command cannot intentionally bypass or defeat required emergency shutdown, power isolation, or rotor-containment provisions during authorized operation or testing. | VM-001, VM-003, VM-004 | Draft |
| SR-035 | The RDT-80 shall identify and control electrical, mechanical, thermal, and rotating-equipment hazards applicable to each authorized prototype test configuration before powered operation is permitted. | VM-002, VM-001 | Draft |

### 7.12 Prototype and Test Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-024 | The RDT-80 prototype shall provide a defined test-mounting interface capable of transferring thrust, torque reaction, weight, and other applicable test loads to an approved test fixture throughout the authorized test envelope. | VM-002, VM-001, VM-004 | Draft |
| SR-036 | The RDT-80 prototype test configuration shall permit measurement of the parameters necessary to evaluate thrust performance, rotor operation, electrical input, thermal behavior, and applicable protection functions during authorized testing. | VM-001, VM-003, VM-004 | Draft |
| SR-037 | Powered prototype testing shall be conducted only within a defined and approved test envelope specifying the applicable limits for electrical input, rotor speed, operating duration, mechanical loading, and other parameters necessary to control test risk. | VM-001 | Draft |
| SR-038 | Prototype testing shall progress from lower-energy or reduced-risk conditions toward higher-energy conditions only after the preceding test stage has satisfied its defined acceptance and safety criteria. | VM-001 | Draft |
| SR-039 | The RDT-80 prototype and test configuration shall be inspected and verified against the approved test configuration before each powered test sequence. | VM-001 | Draft |
| SR-040 | Prototype testing shall record sufficient configuration information, commanded conditions, measured data, anomalies, and test results to permit subsequent engineering evaluation and reconstruction of the test conditions. | VM-001 | Draft |

### 7.13 Maintainability and Service Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-041 | The RDT-80 shall permit inspection of components and interfaces whose condition materially affects safe operation, rotor support, electrical integrity, environmental protection, or structural integrity. | VM-001 | Draft |
| SR-042 | The RDT-80 shall permit replacement or repair of designated serviceable components without requiring destructive disassembly of unrelated major system elements. | VM-001, VM-003 | Draft |
| SR-043 | The RDT-80 shall provide access sufficient to perform required electrical, mechanical, sealing, instrumentation, and rotor-support maintenance activities using defined service procedures. | VM-001, VM-003 | Draft |
| SR-044 | Serviceable electrical and mechanical interfaces shall be configured to minimize the risk of incorrect reassembly, misconnection, reversed polarity, or improper component orientation when practical. | VM-001, VM-003 | Draft |
| SR-045 | Following maintenance or service that affects safety-critical, structural, electrical, rotor-support, sealing, or control functions, the RDT-80 shall be subject to defined post-maintenance inspection or verification before powered operation is authorized. | VM-001, VM-003 | Draft |
| SR-046 | The RDT-80 shall support identification and traceability of replaceable or configuration-controlled components whose revision or condition can affect system performance, safety, or verification status. | VM-001 | Draft |

### 7.14 Manufacturing and Assembly Requirements

| ID | Requirement | Verification | Status |
|---|---|---|---|
| SR-047 | The RDT-80 shall be designed such that critical dimensions, fits, clearances, and alignment features can be produced and verified using defined manufacturing and inspection processes. | VM-002, VM-001 | Draft |
| SR-048 | The RDT-80 assembly architecture shall provide positive location or alignment features sufficient to establish the required relative position of the annular rotor, rotor-support elements, electromagnetic-drive components, and structural housing. | VM-001 | Draft |
| SR-049 | The RDT-80 shall accommodate manufacturing and assembly tolerances without violating required rotor clearances, structural alignment, electromagnetic clearances, or other performance-critical geometric relationships throughout the approved operating envelope. | VM-002, VM-001, VM-004 | Draft |
| SR-050 | Components requiring controlled orientation, polarity, rotational position, or assembly sequence shall incorporate identification, geometry, tooling provisions, or documented assembly controls sufficient to reduce the likelihood of incorrect assembly. | VM-001, VM-003 | Draft |
| SR-051 | Assembly processes affecting safety-critical, structural, rotor-support, electromagnetic, electrical, or environmental-protection functions shall define the applicable inspection or verification criteria necessary to confirm correct assembly before powered operation. | VM-001 | Draft |
| SR-052 | Prototype manufacturing methods and materials shall be selected and controlled such that fabricated components possess properties adequate for their intended function and authorized test envelope. | VM-002, VM-001, VM-004 | Draft |
| SR-053 | The RDT-80 design shall permit configuration-controlled replacement of prototype manufacturing processes, materials, or component designs when test results or engineering analysis demonstrate that revision is required. | VM-001 | Draft |

---

## 8. Requirements Traceability Matrix

| Requirement ID | Requirement Summary | Architecture Source | Assumption | Risk | Open Issue | Verification Method | Status |
|---|---|---|---|---|---|---|---|
| SR-001 | Convert supplied electrical power into controlled hydrodynamic thrust | PT-SA-001 Sections 2.1 and 3.3 | AS-002 | RK-001, RK-007 | OI-001 | VM-004 | Draft |
| SR-002 | Use annular rim-driven propulsion architecture without a conventional central shaft or through-hub drivetrain | PT-SA-001 Sections 2 and 4 | AS-002 | RK-001 | OI-004 | VM-001 | Draft |
| SR-003 | Control electromagnetic torque and resulting propulsor thrust in response to commanded operation | PT-SA-001 Sections 3.3 and 4 | AS-002, AS-006 | RK-001, RK-011 | OI-017 | VM-003, VM-004 | Draft |
| SR-004 | Transfer electromagnetic torque directly from the annular rotor to the propulsor without an intermediate mechanical transmission | PT-SA-001 Sections 2 and 4 | AS-002 | RK-001 | OI-004 | VM-001 | Draft |
| SR-005 | Maintain an unobstructed central propulsor flow passage without a conventional shaft or centrally mounted drive motor | PT-SA-001 Sections 2 and 4 | — | RK-007 | OI-002 | VM-001 | Draft |
| SR-006 | Provide radial and axial support and retention of the annular rotor throughout the approved operating envelope | PT-SA-001 Sections 4 and 6 | AS-004 | RK-002 | OI-008, OI-009 | VM-002, VM-001, VM-004 | Draft |
| SR-007 | Provide secondary rotor retention or containment following loss of the primary support or retention function | PT-SA-001 Sections 4, 6, and 11 | AS-004 | RK-002, RK-016 | OI-010 | VM-002, VM-001, VM-004 | Draft |
| SR-008 | Maintain sufficient radial and axial rotor clearance to prevent unintended contact throughout the approved operating envelope | PT-SA-001 Sections 4 and 6 | AS-005 | RK-002, RK-003 | OI-011 | VM-002, VM-001, VM-004 | Draft |
| SR-009 | Provide a structural load path from the thruster internal assemblies to the system mounting interface | PT-SA-001 Sections 4 and 6 | AS-001 | RK-008 | OI-012 | VM-002, VM-001, VM-004 | Draft |
| SR-010 | Maintain structural alignment and dimensional stability necessary to satisfy rotor-clearance requirements | PT-SA-001 Sections 4 and 6 | AS-005 | RK-003, RK-008 | OI-011, OI-012, OI-020 | VM-002, VM-001, VM-004 | Draft |
| SR-011 | Protect system elements from water exposure and environmental degradation throughout the approved operating environment | PT-SA-001 Sections 4 and 6 | AS-008 | RK-006 | OI-013 | VM-002, VM-001, VM-004 | Draft |
| SR-012 | Isolate energized conductors and electrical connections from the surrounding conductive-water environment | PT-SA-001 Sections 4 and 6 | AS-008 | RK-006 | OI-005, OI-013 | VM-001, VM-004 | Draft |
| SR-013 | Maintain required system performance without unacceptable corrosion or environmentally induced material degradation | PT-SA-001 Sections 4 and 6 | AS-008 | RK-006 | OI-012, OI-013 | VM-002, VM-001, VM-004 | Draft |
| SR-014 | Dissipate internally generated heat and maintain temperature-sensitive components within approved limits | PT-SA-001 Sections 4 and 6 | AS-003 | RK-005 | OI-014 | VM-002, VM-004 | Draft |
| SR-015 | Accept external electrical power through a defined interface and supply the motor-control and electromagnetic-drive functions | PT-SA-001 Sections 3, 4, and 5 | AS-006, AS-009 | RK-011, RK-012 | OI-003 | VM-001, VM-003, VM-004 | Draft |
| SR-016 | Convert commanded operation into controlled electromagnetic-drive excitation and resulting rotor torque | PT-SA-001 Sections 3, 4, and 5 | AS-006 | RK-011 | OI-017 | VM-003, VM-004 | Draft |
| SR-017 | Provide positive electrical power isolation independent of normal commanded operation | PT-SA-001 Sections 5, 6, and 11 | AS-006 | RK-011, RK-016 | OI-018 | VM-001, VM-003, VM-004 | Draft |
| SR-018 | Detect excessive electrical current and initiate protective action before unacceptable electrical-system damage occurs | PT-SA-001 Sections 5, 6, and 11 | AS-006 | RK-011, RK-016 | OI-003, OI-018 | VM-002, VM-003, VM-004 | Draft |
| SR-019 | Detect excessive temperature and initiate protective action before unacceptable thermal damage occurs | PT-SA-001 Sections 6, 7, and 11 | AS-003, AS-006 | RK-005, RK-010, RK-016 | OI-014, OI-016 | VM-002, VM-003, VM-004 | Draft |
| SR-020 | Detect excessive rotor speed and initiate protective action before unacceptable mechanical or safety risk occurs | PT-SA-001 Sections 6 and 11 | AS-006, AS-010 | RK-010, RK-011, RK-016 | OI-016, OI-018, OI-023 | VM-002, VM-003, VM-004 | Draft |
| SR-021 | Detect loss or failure of normal command/control and transition to a protective state that prevents uncontrolled rotor operation | PT-SA-001 Sections 5, 6, and 11 | AS-006 | RK-011, RK-016 | OI-017, OI-018 | VM-003, VM-004 | Draft |
| SR-022 | Detect failure or invalidity of safety-critical sensor inputs and transition to a protective state when safe continued operation cannot be assured | PT-SA-001 Sections 6 and 11 | AS-006 | RK-010, RK-011, RK-016 | OI-016, OI-017, OI-018 | VM-003, VM-004 | Draft |
| SR-023 | Provide emergency shutdown independent of the normal operating command path | PT-SA-001 Sections 6, 9, and 11 | AS-006 | RK-011, RK-016 | OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-024 | Provide a defined prototype test-mounting interface capable of transferring applicable loads to an approved test fixture | PT-SA-001 Sections 4 and 9 | AS-007, AS-009 | RK-012 | OI-019, OI-023 | VM-002, VM-001, VM-004 | Draft |
| SR-025 | Provide a defined external electrical-power interface for safe and correct connection to the approved power source | PT-SA-001 Sections 5 and 8 | AS-006, AS-009 | RK-012 | OI-003 | VM-001, VM-004 | Draft |
| SR-026 | Provide a defined command interface for authorized control of the motor-control function | PT-SA-001 Sections 5 and 8 | AS-006 | RK-011 | OI-017 | VM-001, VM-003, VM-004 | Draft |
| SR-027 | Provide a defined mechanical mounting interface for installation and transfer of applicable loads | PT-SA-001 Sections 4, 8, and 9 | AS-007 | RK-008, RK-012 | OI-019 | VM-002, VM-001, VM-004 | Draft |
| SR-028 | Provide defined instrumentation and data interfaces for development testing, protection, and verification | PT-SA-001 Sections 6, 8, and 9 | AS-006, AS-009 | RK-010, RK-012 | OI-016, OI-019 | VM-001, VM-003, VM-004 | Draft |
| SR-029 | Provide test and service interfaces that support diagnostic and maintenance activities without defeating required protection functions | PT-SA-001 Sections 8, 9, and 11 | AS-001, AS-011 | RK-013 | OI-024 | VM-001, VM-003 | Draft |
| SR-030 | Provide a defined safe state that prevents commanded torque and unintended powered rotor operation | PT-SA-001 Sections 6 and 11 | AS-006 | RK-011, RK-016 | OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-031 | Prevent automatic restart following emergency shutdown or safety-critical protective response | PT-SA-001 Sections 6 and 11 | AS-006 | RK-011, RK-016 | OI-018 | VM-003, VM-004 | Draft |
| SR-032 | Provide a verifiable means of confirming hazardous electrical power isolation before personnel interaction | PT-SA-001 Sections 5, 6, and 11 | AS-006 | RK-016 | OI-018 | VM-001, VM-003 | Draft |
| SR-033 | Protect personnel from rotating-component release and unintended mechanical contact during powered testing | PT-SA-001 Sections 6, 9, and 11 | AS-007 | RK-012, RK-016 | OI-010, OI-019, OI-023 | VM-002, VM-001, VM-004 | Draft |
| SR-034 | Prevent normal operating commands from bypassing required emergency shutdown, isolation, or containment provisions | PT-SA-001 Sections 6 and 11 | AS-006 | RK-011, RK-016 | OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-035 | Identify and control applicable prototype hazards before authorized powered testing | PT-SA-001 Sections 9 and 11 | AS-007, AS-010 | RK-012, RK-016 | OI-019, OI-023 | VM-002, VM-001 | Draft |
| SR-036 | Permit measurement of parameters necessary to evaluate prototype performance, operation, thermal behavior, and protection functions | PT-SA-001 Sections 6 and 9 | AS-006, AS-007, AS-009 | RK-010, RK-012, RK-016 | OI-016, OI-019, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-037 | Restrict powered testing to a defined and approved test envelope | PT-SA-001 Sections 9 and 11 | AS-007, AS-010 | RK-012, RK-016 | OI-019, OI-023 | VM-001 | Draft |
| SR-038 | Require progressive test advancement from reduced-risk to higher-energy conditions based on successful completion of preceding stages | PT-SA-001 Sections 9 and 11 | AS-010 | RK-016 | OI-023 | VM-001 | Draft |
| SR-039 | Verify the prototype and test configuration before each powered test sequence | PT-SA-001 Sections 9 and 11 | AS-007, AS-010 | RK-013, RK-016 | OI-023, OI-024 | VM-001 | Draft |
| SR-040 | Record configuration, operating conditions, measurements, anomalies, and results sufficient to reconstruct prototype tests | PT-SA-001 Section 9 | AS-007, AS-009 | RK-010, RK-013, RK-016 | OI-019, OI-024 | VM-001 | Draft |
| SR-041 | Permit inspection of components and interfaces whose condition materially affects safe or required operation | PT-SA-001 Sections 4, 6, and 11 | AS-011 | — | — | VM-001 | Draft |
| SR-042 | Permit repair or replacement of designated serviceable components without destructive disassembly of unrelated major elements | PT-SA-001 Sections 4 and 6 | AS-011 | — | — | VM-001, VM-003 | Draft |
| SR-043 | Provide access sufficient for required electrical, mechanical, sealing, instrumentation, and rotor-support maintenance | PT-SA-001 Sections 4 and 6 | AS-011 | — | OI-013 | VM-001, VM-003 | Draft |
| SR-044 | Minimize incorrect reassembly or connection of serviceable interfaces when practical | PT-SA-001 Sections 5, 6, and 8 | AS-011 | RK-016 | — | VM-001, VM-003 | Draft |
| SR-045 | Require post-maintenance verification before powered operation following work affecting critical functions | PT-SA-001 Sections 6, 9, and 11 | AS-011 | RK-013, RK-016 | OI-023, OI-024 | VM-001, VM-003 | Draft |
| SR-046 | Maintain identification and traceability of configuration-controlled or replaceable components affecting performance or safety | PT-SA-001 Sections 4, 6, and 9 | AS-011 | RK-013 | OI-024 | VM-001 | Draft |
| SR-047 | Permit manufacture and inspection of critical dimensions, fits, clearances, and alignment features | PT-SA-001 Sections 4, 6, and 10 | AS-001 | RK-009 | OI-020 | VM-002, VM-001 | Draft |
| SR-048 | Provide positive assembly location and alignment of rotor, support, electromagnetic, and housing elements | PT-SA-001 Sections 4 and 6 | AS-005 | RK-002, RK-003, RK-008, RK-009 | OI-008, OI-009, OI-011, OI-020 | VM-001 | Draft |
| SR-049 | Accommodate manufacturing and assembly tolerances without violating critical geometric relationships | PT-SA-001 Sections 4, 6, and 10 | AS-005 | RK-002, RK-003, RK-008, RK-009 | OI-011, OI-020 | VM-002, VM-001, VM-004 | Draft |
| SR-050 | Reduce the likelihood of incorrect orientation, polarity, position, or assembly sequence for controlled components | PT-SA-001 Sections 5, 6, and 10 | AS-001 | RK-009 | OI-020 | VM-001, VM-003 | Draft |
| SR-051 | Define inspection or verification criteria for assembly processes affecting critical system functions | PT-SA-001 Sections 6, 9, and 10 | AS-001 | RK-009, RK-013, RK-016 | OI-020, OI-023, OI-024 | VM-001 | Draft |
| SR-052 | Use prototype manufacturing methods and materials adequate for their intended function and authorized test envelope | PT-SA-001 Sections 6 and 10 | AS-001, AS-008 | RK-009, RK-015, RK-016 | OI-012, OI-020, OI-023 | VM-002, VM-001, VM-004 | Draft |
| SR-053 | Permit configuration-controlled revision of prototype processes, materials, and components based on engineering evidence | PT-SA-001 Sections 9 and 10 | AS-001, AS-011 | RK-013, RK-015 | OI-024 | VM-001 | Draft |
| SR-054 | Produce not less than 7.0 kgf (68.6 N) continuous forward static thrust under approved continuous and reference test conditions | PT-SA-001 Sections 3, 4, 10, and 11 | AS-002, AS-007 | RK-007, RK-012 | OI-001, OI-019, OI-023 | VM-002, VM-004 | Draft |
| SR-055 | Produce not less than 10.0 kgf (98.1 N) peak forward static thrust for the approved peak duration and reference test conditions | PT-SA-001 Sections 4, 10, and 11 | AS-002, AS-007 | RK-007, RK-012 | OI-001, OI-019, OI-023 | VM-002, VM-004 | Draft |
| SR-056 | Provide controllable thrust over the approved operating range | PT-SA-001 Sections 3, 5, and 10 | AS-002, AS-006 | RK-007, RK-011 | OI-001, OI-017 | VM-003, VM-004 | Draft |
| SR-057 | Define configuration-controlled principal propulsor and duct dimensions | PT-SA-001 Sections 4, 9, and 11 | AS-005 | RK-007, RK-008, RK-009 | OI-002, OI-012, OI-020 | VM-001 | Draft |
| SR-058 | Operate within approved rotor-speed, torque, electrical-input, and thrust limits | PT-SA-001 Sections 4, 5, and 10 | AS-010 | RK-001, RK-002, RK-003, RK-005, RK-007, RK-011, RK-016 | OI-001, OI-003, OI-023 | VM-002, VM-004 | Draft |
| SR-059 | Meet an approved propulsive-performance criterion under defined reference conditions | PT-SA-001 Sections 3 and 10 | AS-002, AS-007 | RK-007, RK-012 | OI-001, OI-002, OI-015, OI-019 | VM-002, VM-004 | Draft |
| SR-060 | Limit cavitation to the approved criterion during normal continuous operation | PT-SA-001 Sections 10 and 11 | AS-007 | RK-007, RK-012 | OI-002, OI-015, OI-019 | VM-002, VM-004 | Draft |
| SR-061 | Limit hydrodynamically induced vibration throughout the authorized operating envelope | PT-SA-001 Sections 10 and 11 | AS-007 | RK-002, RK-007, RK-010, RK-012 | OI-002, OI-015, OI-016, OI-019, OI-023 | VM-002, VM-004 | Draft |
| SR-062 | Define and configuration-control the propulsor blade configuration before formal performance verification | PT-SA-001 Sections 4, 9, 10, and 11 | AS-011 | RK-007, RK-013 | OI-015, OI-024 | VM-001 | Draft |
| SR-063 | Produce sufficient electromagnetic torque throughout the approved operating envelope | PT-SA-001 Sections 3, 4, 5, and 10 | AS-002, AS-006 | RK-001 | OI-003, OI-004, OI-005, OI-006 | VM-002, VM-004 | Draft |
| SR-064 | Use an electromagnetic-drive topology compatible with direct annular rim drive | PT-SA-001 Sections 2 and 4 | AS-002 | RK-001 | OI-004, OI-005, OI-006 | VM-002, VM-001 | Draft |
| SR-065 | Operate the electromagnetic drive within approved electrical, mechanical, and thermal limits | PT-SA-001 Sections 4, 5, 7, and 10 | AS-003, AS-006 | RK-001, RK-005, RK-011 | OI-003, OI-004, OI-005, OI-014, OI-017 | VM-002, VM-004 | Draft |
| SR-066 | Maintain required rotor-to-stator electromagnetic geometry and clearance throughout operation | PT-SA-001 Sections 4 and 6 | AS-005 | RK-002, RK-003, RK-008, RK-009 | OI-008, OI-009, OI-011, OI-020 | VM-002, VM-001, VM-004 | Draft |
| SR-067 | Positively retain electromagnetic-drive elements against unacceptable movement or separation | PT-SA-001 Sections 4, 6, and 11 | AS-008 | RK-004, RK-006, RK-016 | OI-006, OI-007 | VM-002, VM-001, VM-004 | Draft |
| SR-068 | Limit electromagnetic-drive losses sufficiently to satisfy system performance and thermal requirements | PT-SA-001 Sections 4, 7, and 10 | AS-003 | RK-001, RK-005 | OI-004, OI-005, OI-006, OI-014 | VM-002, VM-004 | Draft |
| SR-069 | Limit torque ripple, cogging, and electromagnetic excitation to approved levels | PT-SA-001 Sections 4, 6, and 10 | AS-002 | RK-001, RK-002, RK-007, RK-011 | OI-004, OI-005, OI-006 | VM-002, VM-004 | Draft |
| SR-070 | Maintain required electrical and magnetic material performance throughout approved thermal and environmental conditions | PT-SA-001 Sections 4, 6, and 7 | AS-008 | RK-004, RK-005, RK-006 | OI-005, OI-006, OI-007, OI-013, OI-014 | VM-002, VM-001, VM-004 | Draft |
| SR-071 | Define and configuration-control performance-critical electromagnetic parameters before formal verification | PT-SA-001 Sections 4, 9, and 10 | AS-006 | RK-001, RK-013 | OI-004, OI-005, OI-006, OI-024 | VM-001 | Draft |
| SR-072 | Implement the approved RDT-80 operating-state model | PT-SA-001 Sections 5.1, 5.2, and 10.16 | AS-006 | RK-011 | OI-017, OI-018 | VM-001, VM-003, VM-004 | Draft |
| SR-073 | Restrict state transitions and powered-motion commands to approved transition logic and satisfied safety interlocks | PT-SA-001 Sections 5.1, 5.3, 5.4, and 10.16 | AS-006 | RK-011, RK-016 | OI-017, OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-074 | Verify applicable startup preconditions before entering Starting | PT-SA-001 Sections 5.4 and 10.16 | AS-006, AS-007, AS-009, AS-010 | RK-011, RK-012, RK-016 | OI-017, OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-075 | Require controlled fault identification, correction, reset, and reinitialization before return from Fault Shutdown or Emergency Stop to Ready | PT-SA-001 Sections 5.3, 5.5, 10.16, and 10.17 | AS-006 | RK-011, RK-016 | OI-017, OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-076 | Detect supply overvoltage, undervoltage, and short-circuit conditions and initiate protective response | PT-SA-001 Sections 5.6, 8, 10.15, and 10.17 | AS-006 | RK-011, RK-016 | OI-003, OI-018 | VM-002, VM-003, VM-004 | Draft |
| SR-077 | Detect loss or inadequacy of required cooling and initiate protective response | PT-SA-001 Sections 5.6, 7, 8, and 10.17 | AS-003, AS-009 | RK-005, RK-012, RK-016 | OI-014, OI-016, OI-018 | VM-002, VM-003, VM-004 | Draft |
| SR-078 | Detect rotor obstruction, stall, or abnormal acceleration and initiate protective response | PT-SA-001 Sections 5.6, 8, and 10.16 | AS-004, AS-006 | RK-002, RK-011, RK-016 | OI-008, OI-009, OI-016, OI-017, OI-018 | VM-002, VM-003, VM-004 | Draft |
| SR-079 | Detect excessive monitored vibration or mechanical displacement and initiate protective response | PT-SA-001 Sections 5.6, 8, and 10.16 | AS-006 | RK-002, RK-003, RK-010, RK-016 | OI-016, OI-018, OI-023 | VM-002, VM-003, VM-004 | Draft |
| SR-080 | Detect applicable water ingress into protected volumes and initiate protective response | PT-SA-001 Sections 5.6, 8, and 10.15 | AS-008 | RK-006, RK-010, RK-016 | OI-013, OI-016, OI-018 | VM-001, VM-003, VM-004 | Draft |
| SR-081 | Detect loss of required control communications and transition to the approved protective state | PT-SA-001 Sections 5.6, 8, 10.15, and 10.16 | AS-006 | RK-011, RK-016 | OI-017, OI-018 | VM-003, VM-004 | Draft |
| SR-082 | Detect failure of required interlocks and prevent unsafe powered operation | PT-SA-001 Sections 5.4, 5.6, 8, 10.16, and 10.17 | AS-006 | RK-011, RK-016 | OI-018, OI-023 | VM-001, VM-003, VM-004 | Draft |
| SR-083 | Use a 90 mm nominal propulsor diameter for the initial prototype | PT-SA-001 Sections 4, 9, and 11; PT-AN-002 | AS-002, AS-005 | RK-001, RK-002, RK-003, RK-007, RK-008, RK-009 | OI-002 | VM-001 | Draft |

---

## 9. Open Requirement Decisions

Requirement values or constraints that cannot yet be established shall be linked to the applicable PT-SA-005 Open Issue rather than assigned arbitrary values.

This section will track requirement-development decisions that remain unresolved.

| Item | Related Requirement | Related Open Issue | Decision Needed | Status |
|---|---|---|---|---|
| ORD-001 | SR-001 | OI-001 | Establish the required quantitative thrust/performance objective and associated acceptance criteria | Partially Resolved |
| ORD-002 | SR-015 | OI-003 | Establish the system nominal voltage, allowable voltage range, maximum electrical input power, and associated electrical-interface ratings | Open |
| ORD-003 | SR-017 | OI-018 | Establish the required power-isolation architecture, actuation method, isolation location, and acceptance criteria | Open |
| ORD-004 | SR-023 | OI-018, OI-023 | Establish the emergency-shutdown actuation method, shutdown response, required independence, reset behavior, and acceptance criteria | Open |
| ORD-005 | SR-025 | OI-003 | Establish the electrical power-interface voltage, current, connector, conductor, polarity-protection, and interface-rating criteria | Open |
| ORD-006 | SR-026 | OI-017 | Establish the command-interface architecture, signal format, command authority, communication method, and interface acceptance criteria | Open |
| ORD-007 | SR-028, SR-029 | OI-023 | Establish the required development-test instrumentation, data interfaces, diagnostic access, and test-service interface criteria | Open |
| ORD-008 | SR-030, SR-031 | OI-018, OI-023 | Define the system safe state, reset logic, restart authorization criteria, and protective-state behavior | Open |
| ORD-009 | SR-032, SR-034 | OI-018 | Define the power-isolation verification method and required independence of safety-critical shutdown and isolation functions | Open |
| ORD-010 | SR-033, SR-035 | OI-010, OI-023 | Define powered-test guarding, restraint, containment, exclusion-zone, and personnel-protection criteria | Open |
| ORD-011 | SR-037, SR-038, SR-039 | OI-023 | Establish the initial prototype test envelope, test-stage progression criteria, pre-test configuration checks, abort criteria, and authority required to approve advancement to higher-energy testing | Open |
| ORD-012 | SR-041, SR-042, SR-043, SR-046 | — | Define which components are designated serviceable, inspectable, replaceable, or configuration-controlled and establish the associated maintenance-access and traceability criteria | Open |
| ORD-013 | SR-047, SR-048, SR-049 | OI-008, OI-009, OI-011 | Establish critical manufacturing dimensions, tolerances, alignment criteria, inspection methods, and allowable tolerance stack-up for the rotor-support and electromagnetic assemblies | Open |
| ORD-014 | SR-052 | OI-023 | Establish which prototype manufacturing processes and materials are approved for each test stage and define any associated inspection, proof-test, or qualification requirements | Open |
| ORD-015 | SR-054, SR-055, SR-056 | OI-001 | Establish continuous thrust, peak thrust, peak-thrust duration, thrust-control range, reference conditions, and associated acceptance criteria | Partially Resolved |
| ORD-016 | SR-057, SR-083 | OI-002 | Establish the remaining rotor, duct, flow-passage, and principal system-envelope dimensions after selection of the 90 mm nominal propulsor diameter by PT-AN-002 | Partially Resolved |
| ORD-017 | SR-058 | OI-001, OI-003, OI-023 | Establish approved rotor-speed, torque, electrical-input, and thrust operating limits and define how those limits expand during development testing | Open |
| ORD-018 | SR-059, SR-060, SR-061 | OI-001, OI-002, OI-015 | Establish the applicable efficiency or propulsive-performance metric, cavitation acceptance criterion, vibration limits, and reference hydrodynamic test conditions | Open |
| ORD-019 | SR-062 | OI-015 | Select and document the propulsor blade count, blade geometry, pitch, attachment method, and configuration-control basis | Open |
| ORD-020 | SR-063, SR-064, SR-065 | OI-003, OI-004 | Select the electromagnetic-drive topology and establish required torque, speed, voltage, current, power, and associated operating limits | Open |
| ORD-021 | SR-066 | OI-008, OI-009, OI-011 | Establish the required electromagnetic air gap, allowable variation, rotor-to-stator alignment criteria, and associated tolerance limits | Open |
| ORD-022 | SR-067, SR-070 | OI-007 | Establish the electromagnetic rotor-element retention architecture, materials, attachment method, allowable loads, environmental protection, and verification criteria | Open |
| ORD-023 | SR-068, SR-069 | OI-004 | Establish electromagnetic efficiency/loss targets and allowable torque-ripple, cogging, and electromagnetic-excitation criteria | Open |
| ORD-024 | SR-071 | OI-004 | Define the winding topology, phase configuration, pole count, slot configuration or equivalent electromagnetic geometry, magnetic materials, and configuration-control parameters | Open |
| ORD-025 | SR-072, SR-073 | OI-017, OI-018 | Define the detailed operating-state implementation, permitted state transitions, command gating, and state-transition acceptance criteria | Open |
| ORD-026 | SR-074 | OI-017, OI-018, OI-023 | Define the complete startup-precondition and interlock set for each authorized powered-test configuration | Open |
| ORD-027 | SR-075 | OI-017, OI-018, OI-023 | Define fault classification, required corrective actions, reset authorization, reinitialization behavior, and return-to-service criteria | Open |
| ORD-028 | SR-076 | OI-003, OI-018 | Establish overvoltage, undervoltage, short-circuit thresholds, detection timing, and protective-response criteria | Open |
| ORD-029 | SR-077 | OI-014, OI-016, OI-018 | Establish required cooling-status sensing, loss-of-cooling criteria, protective thresholds, and shutdown response | Open |
| ORD-030 | SR-078, SR-079 | OI-016, OI-017, OI-018 | Establish stall, obstruction, abnormal-acceleration, vibration, and displacement detection methods, thresholds, persistence times, and protective responses | Open |
| ORD-031 | SR-080 | OI-013, OI-016, OI-018 | Establish which protected regions require ingress detection, sensor methods, ingress thresholds, and resulting protective actions | Open |
| ORD-032 | SR-081, SR-082 | OI-017, OI-018, OI-023 | Establish communication-loss timing, required interlocks, interlock-failure detection, fault-limited allowances, and protective-state behavior | Open |

---

## 10. Requirements Review and Approval

A dedicated requirements review shall be conducted after the system-level requirements have been developed, traced, and verified for completeness and internal consistency.

The review designation and exit criteria will be established before formal requirements-baseline approval.