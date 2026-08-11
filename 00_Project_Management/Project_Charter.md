# Project Triton RDT

## Project Charter

**Document ID:** PT-PM-001  
**Revision:** 0.1  
**Status:** Draft  
**Project:** Triton Rim-Driven Thruster  
**Working model:** Triton RDT-80  

## 1. Purpose

Project Triton will develop a modular, hubless, rim-driven underwater thruster for remotely operated vehicles, autonomous underwater vehicles, and related marine robotics.

The thruster will have a completely unobstructed central flow passage. It will not use a conventional propeller hub, central shaft, center bearing, or structural support crossing the opening.

The project will emphasize debris resistance, serviceability, measurable performance, and practical manufacture using Fusion 360, additive manufacturing, readily available materials, and limited conventional machining.

## 2. Problem Statement

Conventional underwater thrusters normally use a central shaft and propeller hub. These components can snag seaweed, fishing line, plastic, and other debris.

Ordinary aircraft-drone motors are also poorly adapted to prolonged underwater service because their bearings, rotor components, propeller interfaces, and corrosion protection were not designed for flooded marine operation.

Project Triton will investigate whether a practical rim-driven architecture can eliminate the central obstruction while remaining manufacturable and serviceable by an individual builder.

## 3. Primary Objectives

The project shall:

1. Maintain a continuous and unobstructed opening through the center of the thruster.
2. Eliminate the conventional central propeller shaft and hub.
3. Operate with the motor assembly intentionally flooded.
4. Support forward and reverse thrust.
5. Use a modular rotor, blade cartridge, stator, bearing system, housing, and duct.
6. Permit worn or damaged components to be replaced without rebuilding the complete thruster.
7. Use parametric Fusion 360 models.
8. Record requirements, decisions, revisions, test results, and lessons learned.
9. Measure thrust, voltage, current, rotational speed, temperature, and efficiency during development.
10. Provide an architecture that can later be scaled into additional thruster sizes.

## 4. Initial Prototype Scope

The initial development model will be designated:

**Triton RDT-80**

The preliminary concept will use:

- An approximately 80 mm blade-tip diameter.
- A completely open central passage.
- A rim-mounted blade cartridge.
- A rotating permanent-magnet ring.
- A fixed annular stator.
- Flooded, water-lubricated bearing surfaces.
- A removable duct and housing assembly.
- A dry, externally located electronic speed controller.
- Initial operation at 12 volts.

These values are preliminary and are not approved production requirements.

## 5. Initial Success Criteria

The first mechanical demonstrator will be successful when:

1. The rotor is fully retained by the housing.
2. The rotor turns freely while submerged.
3. No stationary component crosses the central opening.
4. The rotor does not contact the housing during manual rotation.
5. The assembly can be disassembled without destroying major components.
6. Replaceable bearing elements can be removed and reinstalled.
7. The design can be modified through Fusion 360 user parameters.

The first powered demonstrator will be successful when:

1. The rotor starts reliably while submerged.
2. The motor operates in both directions.
3. The thruster produces measurable thrust.
4. Electrical current and temperature remain within established test limits.
5. The assembly completes a controlled-duration submerged test without mechanical failure.

## 6. Out of Scope for the Initial Prototype

The initial prototype is not intended to:

- Match the performance of a commercial Hydromea DiskDrive.
- Achieve a production-ready depth rating.
- Achieve maximum possible thrust or efficiency.
- Use a fully optimized electromagnetic design.
- Use a fully optimized hydrodynamic blade profile.
- Demonstrate long-term saltwater durability.
- Serve as a safety-critical propulsion system.
- Be sold or represented as a finished commercial product.
- Establish final intellectual-property or licensing terms.

## 7. Design Principles

The project will follow these principles:

1. **Modularity:** Major subsystems should be independently replaceable.
2. **Traceability:** Important decisions will be recorded with their reasoning.
3. **Measurability:** Performance claims will be supported by test data.
4. **Manufacturability:** Designs should use accessible tools and processes where practical.
5. **Serviceability:** Wear components should be inspectable and replaceable.
6. **Parametric design:** Important geometry will be controlled by named Fusion 360 parameters.
7. **Controlled iteration:** Changes will be versioned and evaluated against previous results.
8. **Safe testing:** Electrical and mechanical limits will be introduced progressively.
9. **Open center:** No shaft, hub, bearing, fastener, wire, grille, or stationary support may cross the central passage.
10. **Evidence before optimization:** Basic mechanical and electromagnetic function will be demonstrated before detailed optimization.

## 8. Project Records

The project repository will contain:

- Project-management records.
- Requirements.
- System architecture.
- Engineering decisions.
- Mechanical design files.
- Motor and magnetic design records.
- Hydrodynamic design records.
- Electronics documentation.
- Manufacturing records.
- Test procedures and results.
- Fusion 360 exports.
- STEP, STL, drawing, image, and video files.

Fusion 360 cloud files alone will not be considered the complete project record. Important revisions will be exported into the repository in appropriate neutral or archival formats.

## 9. Current Project Phase

The project is currently in:

**Phase 0 — Project definition and engineering infrastructure**

No detailed component geometry has been approved.

## 10. Approval

This charter becomes the governing project-level document when its status changes from **Draft** to **Approved**.

### Drafted by

Robert Schneider

### Technical support

OpenAI ChatGPT

### Approval date

Pending