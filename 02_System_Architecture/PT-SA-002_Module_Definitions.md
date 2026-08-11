# PT-SA-002 — Module Definitions

## Document Control

| Field          | Value                              |
| -------------- | ---------------------------------- |
| Project        | Project Triton                     |
| Document ID    | PT-SA-002                          |
| Document Title | Module Definitions                 |
| Version        | 0.1                                |
| Status         | Draft — DR-002 Supporting Artifact |
| Owner          | Robert Schneider                   |
| Created        | 2026-08-11                         |
| Last Updated   | 2026-08-11                         |

## Revision History

| Version | Date       | Author           | Description                                                                         |
| ------- | ---------- | ---------------- | ----------------------------------------------------------------------------------- |
| 0.1     | 2026-08-11 | Robert Schneider | Initial module definitions derived from PT-SA-001 physical and modular architecture |

## 1. Purpose

This document defines the initial physical modules used to organize development of the Project Triton RDT-80 prototype.

The module architecture supports:

* Controlled design evolution.
* Replaceable experimental configurations.
* Interface definition.
* Preliminary CAD development.
* Fabrication planning.
* Assembly and disassembly.
* Inspection.
* Instrumentation.
* Testing.
* Configuration management.
* Failure investigation.

The module definitions in this document are derived from `PT-SA-001 — System Architecture`.

This document does not establish final detailed geometry, materials, tolerances, manufacturing processes, or component selections.

## 2. Relationship to the System Architecture

PT-SA-001 establishes nine principal functional subsystems and nine initial physical modules.

A physical module may implement functions assigned to more than one subsystem, and a functional subsystem may be distributed across more than one physical module.

Functional responsibility remains with the subsystem defined in PT-SA-001 even when the implementing hardware is physically located within another module.

The module structure defined here shall therefore be interpreted as a physical and configuration-management organization rather than as a replacement for the functional subsystem architecture.

## 3. Module Definition Principles

Each module shall, as applicable:

* Have a unique module identifier.
* Have a clearly defined functional purpose.
* Have identifiable physical boundaries.
* Have controlled mechanical interfaces.
* Have controlled electrical interfaces.
* Have controlled thermal interfaces.
* Have controlled fluid or environmental interfaces.
* Have controlled command, sensing, or data interfaces.
* Have defined configuration status.
* Support inspection and verification.
* Support replacement or revision when practical.
* Preserve system alignment and load paths.
* Avoid uncontrolled dependencies on adjacent modules.

A module shall not be considered interchangeable with another version solely because it can be physically installed.

Compatibility shall be evaluated before substitution.

## 4. Baseline Module Summary

| Module ID | Module                                                 |
| --------- | ------------------------------------------------------ |
| MOD-001   | Propulsor and Rotor Assembly                           |
| MOD-002   | Stator and Electromagnetic Assembly                    |
| MOD-003   | Rotor Support and Retention Assembly                   |
| MOD-004   | Primary Structural Housing                             |
| MOD-005   | Sealing and Environmental Protection Assembly          |
| MOD-006   | Thruster Thermal Management Assembly                   |
| MOD-007   | Motor-Control and Power-Electronics Assembly           |
| MOD-008   | Thruster Instrumentation and Internal Harness Assembly |
| MOD-009   | Prototype Mounting and Test Adapter Assembly           |

## 5. Module Definitions

### 5.1 MOD-001 — Propulsor and Rotor Assembly

#### Purpose

MOD-001 is the rotating assembly that receives electromagnetic torque and converts that torque into hydrodynamic thrust.

#### Principal Contents

MOD-001 may contain:

* Annular rotor structure.
* Propulsor blades.
* Blade-to-rim attachment features.
* Permanent magnets or other rotor electromagnetic elements.
* Magnet or rotor-element retention features.
* Balance-correction features.
* Replaceable wear surfaces.
* Rotor-support contact surfaces.
* Configuration-identification markings.

#### Primary Functions

MOD-001 shall support:

* Electromagnetic torque transfer.
* Hydrodynamic thrust generation.
* Rotor-element retention.
* Propulsor structural support.
* Rotational balance.
* Radial and axial support interfaces.
* Controlled rotor-to-stator clearance.
* Configuration identification.

#### Principal Interfaces

MOD-001 interfaces with:

* MOD-002 through the electromagnetic gap.
* MOD-003 through radial and axial rotor-support interfaces.
* MOD-004 through containment and surrounding structural relationships.
* MOD-005 through environmental-exposure and sealing boundaries where applicable.
* MOD-006 through applicable heat-transfer paths.
* MOD-008 through rotor-position, speed, vibration, displacement, or other sensing interfaces.

#### Key Design Variables

Major unresolved variables include:

* Rotor diameter.
* Rotor cross-section.
* Propulsor blade count.
* Blade geometry.
* Blade pitch.
* Blade attachment method.
* Rotor electromagnetic configuration.
* Magnet grade or alternative rotor element.
* Magnet or rotor-element retention.
* Balance method.
* Wear-surface material.
* Environmental protection.

#### Critical Concerns

* Centrifugal loading.
* Rotor-element release.
* Blade failure.
* Balance.
* Cavitation.
* Vibration.
* Corrosion.
* Water absorption.
* Rotor-to-stator contact.
* Manufacturability.

---

### 5.2 MOD-002 — Stator and Electromagnetic Assembly

#### Purpose

MOD-002 is the stationary electromagnetic assembly that converts controlled electrical power into the rotating electromagnetic field used to produce rotor torque.

#### Principal Contents

MOD-002 may contain:

* Stator core.
* Windings.
* Slot insulation.
* Phase conductors.
* Electrical terminations.
* Encapsulation or potting.
* Stator support features.
* Position-sensing features.
* Magnetic shielding or flux-control elements.

#### Primary Functions

MOD-002 shall support:

* Electromagnetic torque generation.
* Electrical insulation.
* Reaction-torque transfer.
* Electromagnetic-gap control.
* Heat transfer.
* Electrical inspection and testing.
* Required sensing interfaces.

#### Principal Interfaces

MOD-002 interfaces with:

* MOD-001 through the electromagnetic gap.
* MOD-004 through stator support and reaction-torque interfaces.
* MOD-005 through environmental barriers and electrical penetrations.
* MOD-006 through thermal interfaces.
* MOD-007 through controlled electrical power.
* MOD-008 through temperature, position, electrical, and diagnostic measurements.

#### Key Design Variables

Major unresolved variables include:

* Electromagnetic topology.
* Core geometry and material.
* Slot and tooth geometry.
* Pole count.
* Winding arrangement.
* Conductor size.
* Insulation system.
* Encapsulation.
* Wet versus dry construction.
* Cooling method.
* Stator retention method.

#### Critical Concerns

* Electrical insulation.
* Winding temperature.
* Magnetic saturation.
* Electromagnetic losses.
* Reaction torque.
* Water exposure.
* Corrosion.
* Manufacturing accuracy.
* Thermal expansion.
* Electromagnetic-gap stability.

---

### 5.3 MOD-003 — Rotor Support and Retention Assembly

#### Purpose

MOD-003 maintains controlled radial and axial rotor position while permitting rotation and preventing uncontrolled rotor release.

#### Principal Contents

MOD-003 may contain:

* Radial bearings.
* Journal surfaces.
* Bushings.
* Rollers.
* Axial thrust bearings.
* Guide elements.
* Backup or catch bearings.
* Replaceable wear components.
* Adjustment mechanisms.
* Retention rings.
* Mechanical shoulders.
* Support fasteners.

#### Primary Functions

MOD-003 shall support:

* Radial rotor positioning.
* Axial rotor positioning.
* Rotor retention.
* Rotor-to-stator clearance control.
* Load transfer.
* Friction and wear management.
* Alignment adjustment.
* Startup and shutdown support.
* Fault-condition retention.

#### Principal Interfaces

MOD-003 interfaces with:

* MOD-001 through rotating support and retention surfaces.
* MOD-004 through stationary support, alignment, and load-transfer features.
* MOD-005 where support components cross environmental boundaries.
* MOD-006 through bearing or frictional heat-transfer paths.
* MOD-008 through temperature, vibration, displacement, or wear monitoring.

#### Key Design Variables

Major unresolved variables include:

* Radial support technology.
* Axial support technology.
* Support material.
* Support clearance.
* Preload.
* Lubrication method.
* Cooling method.
* Adjustment method.
* Backup-support concept.
* Rotor-retention architecture.

#### Critical Concerns

* Rotor instability.
* Wear.
* Friction.
* Excessive displacement.
* Rotor-to-stator contact.
* Axial thrust loading.
* Hydrodynamic loads.
* Thermal expansion.
* Corrosion.
* Failure containment.

---

### 5.4 MOD-004 — Primary Structural Housing

#### Purpose

MOD-004 provides the primary stationary structural framework for alignment, support, containment, and transmission of system loads to the external mounting structure.

#### Principal Contents

MOD-004 may contain:

* Main annular housing.
* Stator-support rings.
* Rotor-support mounting features.
* Mounting struts.
* External mounting flange.
* Protective structures.
* Access features.
* Guard attachment points.
* Sealing surfaces.
* Lifting or handling points.
* Fairings or flow-conditioning surfaces.

#### Primary Functions

MOD-004 shall support:

* Stator alignment.
* Rotor-support alignment.
* Reaction-torque transfer.
* Thrust-load transfer.
* Radial-load transfer.
* Axial-load transfer.
* Mounting.
* Protective containment.
* Environmental boundaries.
* Handling and installation.

#### Principal Interfaces

MOD-004 interfaces with:

* MOD-002 through stator support.
* MOD-003 through rotor-support mounting and alignment.
* MOD-005 through sealing surfaces and environmental boundaries.
* MOD-006 through conductive or coolant-related thermal paths.
* MOD-008 through sensor and harness mounting.
* MOD-009 through the external test or vessel mounting interface.

#### Key Design Variables

Major unresolved variables include:

* Housing material.
* Housing segmentation.
* Structural cross-section.
* Manufacturing method.
* Access strategy.
* Stator support method.
* Rotor-support mounting.
* Test-interface geometry.
* Hydrodynamic fairing.
* Guarding.

#### Critical Concerns

* Deflection.
* Stiffness.
* Alignment.
* Corrosion.
* Galvanic interaction.
* Structural fatigue.
* Mounting distortion.
* Manufacturing tolerances.
* Serviceability.
* Flow obstruction.

---

### 5.5 MOD-005 — Sealing and Environmental Protection Assembly

#### Purpose

MOD-005 establishes required environmental boundaries and protects components that are not intended for unrestricted exposure to water, moisture, pressure, or contaminants.

#### Principal Contents

MOD-005 may contain:

* Static seals.
* Dynamic seals where required.
* O-rings.
* Gaskets.
* Cable glands.
* Electrical feedthroughs.
* Potted penetrations.
* Encapsulants.
* Moisture barriers.
* Drain features.
* Vent features.
* Pressure-compensation devices.
* Leak-detection sensors.
* Corrosion-control features.

#### Primary Functions

MOD-005 shall support:

* Water-ingress control.
* Protected electrical penetrations.
* Wet/dry boundary control.
* Drainage.
* Venting.
* Pressure equalization.
* Moisture protection.
* Inspection.
* Leak detection when required.

#### Principal Interfaces

MOD-005 interfaces with:

* MOD-001 where rotor elements require environmental protection.
* MOD-002 around stator and electrical elements.
* MOD-003 around support or bearing regions.
* MOD-004 at housing joints and sealing surfaces.
* MOD-006 at cooling penetrations.
* MOD-008 at sensor and conductor penetrations.

#### Key Design Variables

Major unresolved variables include:

* Environmental-region classification.
* Seal type.
* Pressure-compensation strategy.
* Penetration type.
* Encapsulation method.
* Drainage strategy.
* Leak detection.
* Serviceability.

#### Critical Concerns

* Water ingress.
* Seal wear.
* Pressure differential.
* Condensation.
* Trapped water.
* Corrosion.
* Electrical leakage.
* Inspection access.
* Material compatibility.

---

### 5.6 MOD-006 — Thruster Thermal Management Assembly

#### Purpose

MOD-006 collects and transfers heat from significant thruster heat sources to the surrounding water, housing, external cooling equipment, or another approved heat sink.

#### Principal Contents

MOD-006 may contain:

* Cooling passages.
* Cooling channels.
* Conductive thermal interfaces.
* Coolant fittings.
* Hoses or tubing.
* Internal circulation components.
* Thermal interface materials.
* Heat sinks.
* Cold plates.
* Temperature sensors.
* Flow sensors.
* Coolant manifolds.

#### Primary Functions

MOD-006 shall support:

* Stator heat rejection.
* Rotor-support heat rejection.
* Housing heat transfer.
* Controller cooling where incorporated.
* Cooling-flow distribution.
* Temperature monitoring.
* Cooling-loss detection.

#### Principal Interfaces

MOD-006 interfaces with:

* MOD-002 through stator and winding thermal paths.
* MOD-003 through support-system thermal paths.
* MOD-004 through housing conduction and structural mounting.
* MOD-005 at fluid penetrations and environmental boundaries.
* MOD-007 where motor-control hardware uses the same cooling architecture.
* MOD-008 through temperature and flow instrumentation.
* External cooling equipment when required.

#### Key Design Variables

Major unresolved variables include:

* Passive versus active cooling.
* Direct-water cooling.
* Internal coolant.
* External cooling loop.
* Flow rate.
* Coolant type.
* Cooling-passage geometry.
* Fouling allowance.
* Temperature limits.

#### Critical Concerns

* Hot spots.
* Flow blockage.
* Fouling.
* Leakage.
* Trapped air.
* Corrosion.
* Loss of cooling.
* Sensor placement.
* Post-shutdown heat soak.

---

### 5.7 MOD-007 — Motor-Control and Power-Electronics Assembly

#### Purpose

MOD-007 receives external electrical power and provides controlled, protected electrical excitation to the electromagnetic drive.

#### Principal Contents

MOD-007 may contain:

* Main disconnect.
* Fuses.
* Circuit breakers.
* Contactors.
* Precharge circuitry.
* DC bus.
* Inverter.
* Motor controller.
* Gate drivers.
* Current sensors.
* Voltage sensors.
* Communications hardware.
* Control power supplies.
* Braking or energy-dissipation hardware.
* Local status indicators.

#### Primary Functions

MOD-007 shall support:

* Electrical isolation.
* Power conversion.
* Motor control.
* Startup sequencing.
* Speed, torque, current, or power regulation.
* Protective-limit enforcement.
* Fault shutdown.
* Emergency torque inhibition.
* Communications.
* Fault logging.

#### Principal Interfaces

MOD-007 interfaces with:

* External electrical power.
* MOD-002 through stator power conductors.
* MOD-006 through controller cooling where required.
* MOD-008 through sensing and telemetry.
* MOD-009 through test-system power, control, and E-Stop connections.
* External supervisory controls.
* External emergency-stop systems.

#### Key Design Variables

Major unresolved variables include:

* Supply voltage.
* DC-bus voltage.
* Continuous current.
* Peak current.
* Controller platform.
* Inverter topology.
* Commutation method.
* Rotor-position sensing.
* Control mode.
* Contactors.
* Braking strategy.
* Fault-data retention.

#### Critical Concerns

* Overcurrent.
* Overspeed.
* Loss of commutation.
* Unintended startup.
* Failure to inhibit torque.
* Stored electrical energy.
* Controller overheating.
* Ground faults.
* Communication loss.
* Automatic restart.

---

### 5.8 MOD-008 — Thruster Instrumentation and Internal Harness Assembly

#### Purpose

MOD-008 provides the sensing, signal-routing, identification, calibration, and internal data interfaces required for protection, control, engineering evaluation, and test reconstruction.

#### Principal Contents

MOD-008 may contain:

* Temperature sensors.
* Position sensors.
* Speed sensors.
* Vibration sensors.
* Displacement sensors.
* Leak sensors.
* Pressure sensors.
* Flow sensors.
* Signal-conditioning hardware.
* Internal wiring.
* Harnesses.
* Connectors.
* Junctions.
* Shielding.
* Grounding features.
* Identification labels.

#### Primary Functions

MOD-008 shall support:

* Protective sensing.
* Control feedback.
* Engineering measurements.
* Data acquisition.
* Sensor health monitoring.
* Calibration traceability.
* Harness routing.
* Signal integrity.
* Configuration identification.

#### Principal Interfaces

MOD-008 interfaces with:

* All monitored physical modules.
* MOD-007 through controller inputs and telemetry.
* MOD-009 through external DAQ and test instrumentation.
* External data-acquisition equipment.

#### Key Design Variables

Major unresolved variables include:

* Required sensor types.
* Sensor locations.
* Redundancy.
* Accuracy.
* Range.
* Sampling rate.
* Connector architecture.
* Shielding.
* Grounding.
* Harness routing.
* Calibration method.

#### Critical Concerns

* Sensor failure.
* Noise.
* EMI.
* Calibration drift.
* Inadequate sampling.
* Harness damage.
* Water ingress.
* Connector failure.
* Loss of synchronization.
* Inability to reconstruct a fault.

---

### 5.9 MOD-009 — Prototype Mounting and Test Adapter Assembly

#### Purpose

MOD-009 provides the controlled mechanical, electrical, instrumentation, and safety interface between the RDT-80 prototype and the external test system.

#### Principal Contents

MOD-009 may contain:

* Thruster mounting adapter.
* Test-stand attachment features.
* Thrust-load measurement interface.
* Torque-reaction features.
* Alignment features.
* Guards.
* Test cabling.
* Junction boxes.
* External instrumentation mounts.
* Fluid connections.
* Grounding connections.
* Emergency-stop connections.
* Configuration-identification features.

#### Primary Functions

MOD-009 shall support:

* Repeatable prototype installation.
* Thrust transfer and measurement.
* Reaction-torque transfer.
* Alignment.
* Immersion positioning.
* External electrical connections.
* External data connections.
* Cooling connections.
* Guarding.
* Test-area safety interfaces.
* Configuration identification.

#### Principal Interfaces

MOD-009 interfaces with:

* MOD-004 through the thruster mounting interface.
* MOD-007 through power, command, communications, isolation, and E-Stop connections.
* MOD-008 through instrumentation and DAQ connections.
* External test stand.
* External power source.
* External cooling equipment.
* External data-acquisition system.
* External safety system.
* Surrounding test fluid.

#### Key Design Variables

Major unresolved variables include:

* Test-stand geometry.
* Mounting orientation.
* Load-cell arrangement.
* Torque-reaction method.
* Immersion depth.
* Water environment.
* Flow environment.
* Guarding.
* Power connections.
* Cooling connections.
* Instrumentation routing.

#### Critical Concerns

* Structural capacity.
* Alignment.
* Measurement error.
* Test-stand vibration.
* Electrical grounding.
* Personnel protection.
* Guarding.
* Cable routing.
* Test repeatability.
* Configuration reconstruction.

## 6. Module-to-Subsystem Relationship

| Functional Subsystem                     | Primary Module or Modules                                                  |
| ---------------------------------------- | -------------------------------------------------------------------------- |
| Propulsor and Rotor                      | MOD-001                                                                    |
| Electromagnetic Drive                    | MOD-002 and portions of MOD-001                                            |
| Rotor Support and Retention              | MOD-003 and supporting features within MOD-004                             |
| Structural Housing and Mounting          | MOD-004 and MOD-009                                                        |
| Electrical Power and Motor Control       | MOD-007                                                                    |
| Sealing and Environmental Protection     | MOD-005 and environmental features within other modules                    |
| Thermal Management                       | MOD-006 and thermal features within MOD-002, MOD-003, MOD-004, and MOD-007 |
| Sensing, Protection, and Instrumentation | MOD-008 and sensors incorporated into other modules                        |
| Prototype Test Interface                 | MOD-009 and external portions of MOD-007 and MOD-008                       |

## 7. Module Interface Control

As detailed design progresses, each module shall have its interfaces defined sufficiently to support controlled development.

Interface information shall include, as applicable:

* Mechanical attachment.
* Datums.
* Alignment.
* Clearances.
* Load transfer.
* Fasteners.
* Electrical voltage.
* Electrical current.
* Connector type.
* Grounding.
* Shielding.
* Control signals.
* Communications.
* Sensor interfaces.
* Thermal loads.
* Cooling connections.
* Fluid exposure.
* Sealing surfaces.
* Installation.
* Removal.
* Inspection.
* Maintenance.

Detailed interface values shall be transferred into controlled Interface-Control Documents, drawings, requirements, or other approved engineering artifacts.

## 8. Module Configuration Control

Each physical module variant shall eventually have, as applicable:

* Module ID.
* Variant identifier.
* Revision.
* Part or assembly number.
* Serial number.
* Applicable drawings or CAD models.
* Material definition.
* Manufacturing process.
* Applicable analyses.
* Applicable inspection records.
* Required software or controller settings.
* Interface definition.
* Approved operating restrictions.
* Test history.
* Disposition.

A modified module shall not retain an unchanged configuration identity when the modification could affect:

* Safety.
* Fit.
* Alignment.
* Performance.
* Electrical characteristics.
* Thermal performance.
* Structural strength.
* Rotor dynamics.
* Hydrodynamics.
* Environmental protection.
* Instrumentation.
* Verification results.

## 9. Module Compatibility

Physical installation alone does not establish compatibility.

Module substitutions shall be evaluated for:

* Geometry.
* Datums.
* Rotor-to-stator clearance.
* Mechanical loads.
* Structural stiffness.
* Electrical ratings.
* Electromagnetic characteristics.
* Thermal interfaces.
* Cooling.
* Environmental boundaries.
* Material compatibility.
* Sensor ranges.
* Control parameters.
* Protective limits.
* Software compatibility.
* Test-stand capability.
* Approved operating envelope.

An interchangeability matrix shall be created when multiple controlled module variants exist.

## 10. Module Definition Change Control

A change to a module definition shall be reviewed when it materially affects:

* Functional allocation.
* Module boundaries.
* Controlled interfaces.
* Rotor alignment.
* Rotor retention.
* Structural load paths.
* Electromagnetic gap.
* Electrical power architecture.
* Thermal architecture.
* Environmental classification.
* Instrumentation.
* Safety functions.
* Test-system compatibility.
* Configuration identification.

Material changes affecting the approved system architecture shall require review against PT-SA-001 and may require an Architectural Decision Record or architecture revision.

## 11. Open Module-Definition Decisions

The following module-definition subjects remain open:

* Final module separation boundaries.
* Final rotor installation method.
* Final stator installation method.
* Rotor-support adjustment architecture.
* Primary mechanical datum scheme.
* Housing segmentation.
* Propulsor construction method.
* Rotor electromagnetic-element retention.
* Seal replacement strategy.
* Internal wiring and sensor routing.
* Cooling routing.
* Motor-controller physical location.
* Handling and lifting features.
* Guarding and containment.
* Module serialization method.
* Encapsulation strategy.
* Experimental-module interchangeability criteria.

These items shall remain unresolved until supported by approved requirements, analyses, trade studies, CAD development, supplier information, fabrication experience, or prototype testing.
