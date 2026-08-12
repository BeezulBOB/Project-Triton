# Project Triton
## RDT-80 Thrust Objective Analysis

---

## Document Control

| Field | Value |
|---|---|
| Project | Project Triton |
| Document ID | PT-AN-001 |
| Document Title | RDT-80 Thrust Objective Analysis |
| Version | 0.1 |
| Status | Draft |
| Owner | Robert Schneider |
| Created | 2026-08-11 |
| Last Updated | 2026-08-11 |
| Related Open Issue | OI-001 — RDT-80 Thrust Objective |
| Related Requirements | SR-001, SR-054, SR-055, SR-056, SR-058, SR-059 |
| Architecture Baseline | PT-SA-001 Version 1.0 / DR-002-v1.0 |

---

## Revision History

| Version | Date | Description |
|---|---|---|
| 0.1 | 2026-08-11 | Initial thrust-objective analysis developed; benchmarked candidate performance, established preliminary analytical and electrical-power basis, selected the recommended 7.0 kgf continuous / 10.0 kgf peak objective, and identified remaining downstream dependencies |

---

## 1. Purpose

This analysis establishes the technical basis for selecting the continuous-thrust and peak-thrust objectives for the Project Triton RDT-80 prototype.

The analysis is intended to support resolution of OI-001 and provide quantitative values and reference conditions for applicable system requirements in PT-REQ-001.

---

## 2. Decision to Be Made

This analysis shall establish, or explicitly disposition to a controlled downstream decision where insufficient technical basis presently exists, the following:

1. Required continuous static thrust.
2. Required peak static thrust.
3. Allowable peak-thrust duration.
4. Minimum controllable thrust range.
5. Reference fluid and environmental conditions.
6. Applicable measurement tolerance or acceptance margin.
7. Whether forward and reverse thrust requirements differ.
8. Whether the selected objective represents:
   - a minimum acceptable prototype capability;
   - a design target;
   - a verification requirement; or
   - a combination of these.

A parameter shall not be assigned an arbitrary numerical value solely to permit closure of this analysis.

Where a parameter cannot yet be defensibly established, this analysis shall identify the controlling downstream dependency and preserve the item as an explicit open decision.

---

## 3. Decision Principles

The thrust objective shall not be selected solely because a particular motor, propeller, controller, or commercially available thruster happens to produce that value.

The selected objective should instead reflect:

- Project Triton development goals.
- Intended prototype scale.
- Representative underwater-vehicle propulsion needs.
- Comparable commercial and experimental thruster performance.
- Practical electrical-power requirements.
- Geometric feasibility.
- Hydrodynamic feasibility.
- Electromagnetic feasibility.
- Prototype manufacturing capability.
- Safe and practical laboratory testing.

The thrust objective may be revised if subsequent analysis demonstrates that the selected value is incompatible with the approved architectural constraints or creates disproportionate technical risk.

---

## 4. Source Hierarchy

Evidence used in this analysis shall be identified as one of the following:

1. Project requirement or approved decision.
2. Verified Project Triton test data.
3. Supplier-certified performance data.
4. Published experimental or technical literature.
5. Engineering analysis or calculation.
6. Comparable-system benchmark.
7. Preliminary engineering judgment.

Performance from another thruster shall not be assumed directly applicable to the RDT-80 without evaluating differences in geometry, electrical input, propulsor design, operating conditions, and measurement method.

---

## 5. Intended Application and Mission Basis

### 5.1 Current Development Role

The RDT-80 is a development-scale rim-driven thruster prototype intended primarily to establish and characterize the technical feasibility and performance of the Project Triton direct annular propulsion architecture.

The initial prototype is not presently tied to a specific production vehicle, certified marine installation, or final operational mission.

Its immediate engineering role is to provide a sufficiently representative and instrumented propulsion article to support:

- hydrodynamic performance characterization;
- electromagnetic-drive development;
- rotor-support and retention development;
- structural and thermal evaluation;
- motor-control development;
- environmental-protection development;
- verification of controlled thrust production;
- evaluation of scalability to larger or higher-power thruster configurations.

The prototype shall initially be evaluated in a controlled test environment before vessel-integrated or open-water testing is considered.

---

### 5.2 Mission-Basis Classification

For purposes of establishing the initial thrust objective, the RDT-80 shall be treated as a:

**Representative engineering prototype for small underwater-vehicle propulsion research and technology demonstration.**

This classification is a working analysis basis and does not constitute approval for installation on a specific underwater vehicle.

The thrust objective should therefore be high enough to:

1. Demonstrate practically useful underwater propulsion rather than only detectable laboratory thrust.
2. Exercise the electromagnetic, rotor-support, structural, thermal, control, and hydrodynamic systems at technically meaningful loads.
3. Permit comparison with commercially available and experimental thrusters of broadly similar physical scale.
4. Support future assessment of suitability for small ROV, AUV, USV-subsystem, or other underwater-vehicle applications.
5. Remain compatible with fabrication, instrumentation, power, and test capabilities reasonably accessible to Project Triton.

---

### 5.3 Vehicle-Level Mission Parameters

No specific host vehicle has yet been selected.

Accordingly, vehicle mass, vehicle speed, drag, thruster count, and station-keeping requirements shall not be used as fixed design requirements at this stage.

These parameters may be used later as representative scenarios to test whether a proposed thrust objective is technically meaningful.

| Parameter | Current Analysis Basis |
|---|---|
| Intended vehicle class | Small underwater-vehicle class; specific platform TBD |
| Representative vehicle mass | TBD — scenario parameter, not yet a system requirement |
| Representative vehicle speed | TBD — scenario parameter, not yet a system requirement |
| Number of thrusters per vehicle | TBD |
| Primary propulsion function | Controlled underwater propulsion / technology demonstration |
| Required station-keeping capability | TBD |
| Required forward thrust | Established by this analysis: 7.0 kgf continuous / 10.0 kgf peak forward static thrust |
| Required reverse thrust | Quantitative objective remains open pending propulsor analysis |
| Continuous operating duration | Open — dependent on thermal and verification analysis |
| Peak operating duration | Open — dependent on thermal, electrical, structural, and verification analysis |

---

### 5.4 Primary Performance Use Case

The initial thrust objective shall be based primarily on **static or near-static thrust capability under controlled test conditions**.

Static thrust is selected as the first quantitative performance basis because it:

- can be measured directly using a restrained test fixture;
- provides a repeatable basis for comparison among candidate configurations;
- does not require a complete vehicle hydrodynamic model;
- directly exercises the rotor, electromagnetic drive, propulsor, structure, controller, and thermal system;
- supports later correlation with electrical input, torque, rotational speed, and efficiency-related measurements.

Static-thrust performance shall not by itself be interpreted as complete vehicle-propulsion performance.

Subsequent evaluation may include bollard/static thrust, thrust versus rotational speed, thrust versus electrical input, thrust versus inflow velocity, propulsive efficiency, cavitation behavior, and vehicle-specific operating points.

---

### 5.5 Forward and Reverse Operation

Forward thrust shall be treated as the primary initial performance direction.

Reverse-operation capability shall be evaluated during this analysis because maneuvering and station-keeping applications may benefit from bidirectional thrust.

Unless a later requirement establishes otherwise:

- the initial reverse-thrust objective need not equal forward thrust;
- reverse operation shall not be allowed to dictate the initial propulsor design if doing so materially degrades the primary forward-performance objective;
- any reduced reverse-thrust capability shall be explicitly documented rather than assumed.

---

### 5.6 Development Constraints Affecting the Thrust Objective

The selected thrust objective shall be compatible with the following controlled project assumptions and constraints:

1. The prototype must remain manufacturable using resources reasonably accessible to Project Triton.
2. Required power electronics, instrumentation, and data acquisition must remain practical for prototype development.
3. Initial testing must be achievable in a controlled facility.
4. The operating envelope must be capable of incremental expansion through analysis and reduced-risk testing.
5. The thrust objective must not implicitly authorize full-power, vessel-integrated, or open-water operation.
6. The selected objective should preserve a credible path to future scaling without requiring the RDT-80 to represent a production-ready thruster.

These constraints are consistent with the DR-002 architectural assumptions AS-001, AS-006, AS-007, AS-009, AS-010, and AS-012.

---

### 5.7 Mission-Basis Decision Summary

For the purposes of OI-001, the following mission basis is adopted for further analysis:

| Decision Item | Working Basis |
|---|---|
| Development role | Representative engineering prototype |
| Immediate purpose | Demonstrate and characterize useful rim-driven underwater thrust |
| Host vehicle | Not yet selected |
| Target application class | Small underwater-vehicle propulsion research |
| Initial test environment | Controlled facility |
| Primary thrust metric | Static / near-static forward thrust |
| Reverse thrust | Secondary capability to be evaluated |
| Production qualification | Not required at this stage |
| Vessel integration | Not authorized by this analysis |
| Scalability | Preserve credible path to larger/higher-power systems |

---

## 6. Comparable Thruster Benchmarking

### 6.1 Benchmarking Purpose

Comparable underwater thrusters were reviewed to establish a technically meaningful range of thrust, propulsor size, electrical power, and packaging for the RDT-80 prototype.

The benchmark set intentionally includes both:

- rim-driven/direct-drive thrusters that are architecturally similar to Project Triton; and
- conventional small-vehicle thrusters with comparable propulsor dimensions and well-documented performance.

Benchmark performance is not adopted directly as an RDT-80 requirement. Differences in electromagnetic topology, propulsor geometry, duct design, operating voltage, thermal design, test conditions, and product maturity must be considered before drawing design conclusions.

The benchmark information below reflects manufacturer-published data reviewed on 2026-08-11.

For interpretation purposes, the benchmark set is divided into two classes:

1. **Architecture-comparable benchmarks** — rim-driven or annular direct-drive thrusters whose motor and propulsor arrangement is substantially similar to the Project Triton architecture.
2. **General propulsor benchmarks** — conventional underwater thrusters whose propulsor diameter, thrust, electrical input, or operating environment provides useful comparison data but whose drive architecture differs materially from RDT-80.

Architecture-comparable benchmarks shall receive greater weight when evaluating electromagnetic packaging, system efficiency, rotor configuration, thermal behavior, and other architecture-dependent characteristics.

General propulsor benchmarks may be used to evaluate broad relationships among propulsor diameter, thrust, electrical input, and practical underwater-thruster performance, but their efficiency or implementation characteristics shall not be assumed directly applicable to RDT-80.

---

### 6.2 Benchmark Summary

| Manufacturer / Developer | Model | Architecture | Propulsor Diameter | Supply / Nominal Voltage | Published Electrical Input | Published Static Thrust | Reverse-Thrust Data | Depth Rating | Relevance to RDT-80 |
|---|---|---|---:|---:|---:|---:|---:|---:|---|
| Hydromea | DISKDRIVE 50 | Rim-driven, hubless, direct drive | 50 mm | 12–16 V | Maximum current 25 A | 3.0 kgf at 16 V; 2.1 kgf at 12 V | Not published in reviewed datasheet | 300 m | Architecturally similar lower-size benchmark |
| Hydromea | DISKDRIVE 80 | Rim-driven, hubless, direct drive | 80 mm | 12–24 V | Maximum current 30 A | 7.0 kgf at 24 V; 3.0 kgf at 12 V | Not published in reviewed datasheet | 300 m | Closest direct architecture and size benchmark |
| Blue Robotics | T200 | Flooded brushless thruster with conventional central motor/rotor architecture | 76 mm | 7–20 V; 16 V nominal | 390 W at 16 V; 645 W at 20 V full throttle | 5.25 kgf at 16 V; 6.7 kgf at 20 V | 4.1 kgf at 16 V; 5.05 kgf at 20 V | 300 m tested | Very useful similar-diameter small-ROV benchmark |
| Blue Robotics | T500 | Flooded brushless thruster with conventional central motor/rotor architecture | 114.5 mm | 7–24 V | 402 W at 16 V; 1044 W at 24 V full throttle | 9.3 kgf at 16 V; 16.1 kgf at 24 V | 6.2 kgf at 16 V; 10.5 kgf at 24 V | 300 m | Higher-performance benchmark showing effect of increased propulsor diameter and power |
| Rim Drive Technology | Bow Thruster 3.0 | Commercial rim-drive motor / propulsor | 86 mm | 48 V nominal | 3.0 kW maximum input; 63 A nominal current | 25 kgf | Symmetric architecture stated by manufacturer; quantitative reverse value not published on reviewed page | IP68; application-specific depth not used for this comparison | High-power rim-drive benchmark near the RDT-80 propulsor scale |

---

### 6.3 Hydromea DISKDRIVE 80

The Hydromea DISKDRIVE 80 is the most directly comparable benchmark identified because it combines:

- an 80 mm propeller;
- annular rim-driven architecture;
- direct electromagnetic drive;
- a hubless central flow passage;
- sensorless three-phase brushless operation;
- water-compatible rotor operation;
- no dynamic shaft seal.

Manufacturer-published specifications include:

| Parameter | Published Value |
|---|---:|
| Propeller diameter | 80 mm |
| Outer dimensions | 126 × 155 × 25 mm |
| Weight in air, excluding cable | 750 g |
| Supply voltage | 12–24 V |
| Maximum current | 30 A |
| Static thrust at 12 V | 3.0 kgf |
| Static thrust at 24 V | 7.0 kgf |
| Depth rating | 300 m |
| Control interface | Three-phase brushless, sensorless |

Hydromea states that the published performance measurements were taken using its DISKDRIVE 80 hydro ducts.

Accordingly, the published 7.0 kgf value should be treated as performance of a ducted system configuration rather than as an isolated bare rotor/propeller result.

For Project Triton, this benchmark demonstrates that approximately 7 kgf of static thrust is commercially achievable using a rim-driven propulsor having essentially the same nominal propeller diameter implied by the RDT-80 designation.

It does not establish that 7 kgf is the correct Project Triton requirement.

---

### 6.4 Hydromea DISKDRIVE 50

The DISKDRIVE 50 provides a useful lower-scale rim-driven benchmark.

| Parameter | Published Value |
|---|---:|
| Propeller diameter | 50 mm |
| Outer dimensions | 82 × 95 × 15 mm |
| Weight, excluding cable | 175 g |
| Supply voltage | 12–16 V |
| Maximum current | 25 A |
| Maximum rotational speed | 3800 RPM |
| Static thrust at 12 V | 2.1 kgf |
| Static thrust at 16 V | 3.0 kgf |
| Depth rating | 300 m |

The approximately 3 kgf performance of the 50 mm system establishes a useful lower bound for comparison and demonstrates that meaningful static thrust is achievable even at substantially smaller rim-driven scale.

---

### 6.5 Blue Robotics T200

The Blue Robotics T200 is not rim-driven, but it is a particularly useful performance benchmark because its 76 mm propeller is close to the nominal RDT-80 scale and extensive manufacturer performance data are available.

| Parameter | Published Value |
|---|---:|
| Propeller diameter | 76 mm |
| Overall diameter | 100 mm |
| Length | 113 mm |
| Weight in air with standard cable | 427 g |
| Operating voltage | 7–20 V |
| Recommended nominal range | 12–16 V |
| Forward thrust at 12 V | 3.71 kgf |
| Forward thrust at 16 V | 5.25 kgf |
| Forward thrust at 20 V | 6.7 kgf |
| Reverse thrust at 16 V | 4.1 kgf |
| Reverse thrust at 20 V | 5.05 kgf |
| Full-throttle power at 16 V | 390 W |
| Full-throttle power at 20 V | 645 W |
| Maximum tested depth | 300 m |

The T200 therefore reaches approximately the same maximum published static thrust as the Hydromea DISKDRIVE 80 despite using a different motor and mechanical architecture.

The similarity of the T200 and DISKDRIVE 80 thrust levels provides a useful indication that a static-thrust objective in approximately this range is physically credible for a compact propulsor near 80 mm diameter.

---

### 6.6 Blue Robotics T500

The T500 provides a higher-performance comparison and illustrates the benefit and cost of increasing propulsor diameter and electrical input.

| Parameter | Published Value |
|---|---:|
| Propeller diameter | 114.5 mm |
| Overall diameter | 141 mm |
| Length | 160 mm |
| Weight in air with cable | 1.157 kg |
| Operating voltage | 7–24 V |
| Forward thrust at 16 V | 9.3 kgf |
| Forward thrust at 24 V | 16.1 kgf |
| Reverse thrust at 16 V | 6.2 kgf |
| Reverse thrust at 24 V | 10.5 kgf |
| Full-throttle power at 16 V | 402 W |
| Full-throttle power at 24 V | 1044 W |
| Full-throttle speed at 24 V | 3100 RPM |
| Depth rating | 300 m |

The manufacturer specifies that continuous full-throttle operation at 24 V should be limited to one minute or less to avoid overheating.

This distinction is particularly relevant to Project Triton because it demonstrates that a published maximum-thrust value cannot automatically be treated as a continuous-thrust capability.

Continuous and peak thrust must therefore remain separate Project Triton requirements.

---

### 6.7 Rim Drive Technology 3.0 kW Benchmark

A commercial 3.0 kW rim-drive bow thruster from Rim Drive Technology provides a useful high-power benchmark near the RDT-80 propulsor scale.

| Parameter | Published Value |
|---|---:|
| Propeller diameter | 86 mm |
| Outside diameter | 141 mm |
| Motor length | 110 mm |
| Weight | 3.5 kg |
| Nominal voltage | 48 V |
| Nominal current | 63 A |
| Maximum input power | 3.0 kW |
| Static thrust | 25 kgf |
| Environmental rating | IP68 |

This unit operates at substantially greater voltage, power, mass, and likely structural loading than the development envelope presently contemplated for the first RDT-80 prototype.

Its performance nevertheless demonstrates that propulsor diameter alone does not establish a narrow thrust ceiling. An approximately 80–90 mm rim-driven propulsor can potentially produce substantially greater thrust when supported by higher electrical input, electromagnetic loading, structural capability, and thermal capacity.

Accordingly, an initial Project Triton target materially below 25 kgf should not be interpreted as a fundamental limitation of rim-drive technology at this diameter.

---

### 6.8 Comparative Observations

The benchmark data support the following preliminary observations:

1. **Approximately 3 kgf represents demonstrated lower-scale rim-drive performance.**  
   Hydromea achieves approximately 3 kgf using a 50 mm rim-driven propulsor.

2. **Approximately 5–7 kgf is a well-supported performance region for compact propulsors near 76–80 mm diameter.**  
   Both the Hydromea DISKDRIVE 80 and Blue Robotics T200 fall within this range despite substantially different architectures.

3. **Approximately 9–16 kgf is demonstrated by a larger 114.5 mm propulsor with roughly 400 W to 1 kW electrical input.**  
   The T500 demonstrates that materially greater thrust is practical when diameter and input power are increased.

4. **Approximately 25 kgf is commercially demonstrated by an 86 mm rim-drive unit at a substantially higher 3 kW electrical-power level.**  
   This indicates that high thrust at approximately the RDT-80 propulsor scale is technically possible, but doing so drives the system into a substantially different electrical, thermal, structural, and manufacturing regime.

5. **Maximum thrust and continuous thrust must be treated separately.**  
   The Blue Robotics T500 provides a clear example in which maximum published thrust at maximum voltage is subject to a short-duration thermal limitation.

6. **Duct configuration materially affects benchmark interpretation.**  
   Hydromea specifies that its DISKDRIVE performance measurements use its hydro ducts. RDT-80 performance must therefore ultimately be specified against a controlled duct and propulsor configuration.

7. **Reverse thrust should be treated independently from forward thrust.**  
   Blue Robotics publishes materially lower reverse than forward thrust for both the T200 and T500, demonstrating that bidirectional operation does not imply equal bidirectional performance.

---

### 6.9 Benchmark Applicability to RDT-80

For purposes of selecting candidate RDT-80 thrust objectives, the benchmark set suggests three broad performance regions:

| Performance Region | Approximate Static-Thrust Range | Benchmark Basis | Preliminary Interpretation |
|---|---:|---|---|
| Low / minimum demonstrator | 3–5 kgf | DISKDRIVE 50; lower-voltage compact-thruster performance | Technically meaningful but may provide limited differentiation from existing small thrusters |
| Representative engineering prototype | 6–10 kgf | DISKDRIVE 80, T200, lower-power T500 operation | Strongly supported by current comparable hardware and suitable for an approximately 80 mm development thruster |
| High-performance prototype | 12–25 kgf | T500 maximum performance and 3.0 kW commercial rim-drive benchmark | Potentially achievable but likely drives substantially greater electrical, electromagnetic, structural, thermal, and test requirements |

These ranges are benchmarking categories only and do not yet constitute Project Triton requirements.

The final candidate values shall be selected in Section 7 and evaluated analytically before OI-001 is closed.

---

### 6.10 Benchmark Weighting

The benchmark systems are assigned the following qualitative relevance to RDT-80:

| Benchmark | Benchmark Class | Relative Weight | Primary Use |
|---|---|---|---|
| Hydromea DISKDRIVE 80 | Architecture-comparable | Very High | Closest reference for approximately 80 mm rim-driven architecture and thrust capability |
| Hydromea DISKDRIVE 50 | Architecture-comparable | High | Rim-drive scaling and lower-size performance reference |
| Rim Drive Technology 3.0 kW / 86 mm | Architecture-comparable | High | High-power rim-drive capability near the RDT-80 propulsor scale |
| Blue Robotics T200 | General propulsor benchmark | Moderate | Similar-diameter thrust and electrical-power comparison |
| Blue Robotics T500 | General propulsor benchmark | Moderate to Low | Higher-thrust scaling, duty-cycle, and power comparison |

The conventional Blue Robotics benchmarks are therefore not treated as predictions of RDT-80 efficiency.

They are retained because they demonstrate what practical underwater propulsors of known diameter can achieve and provide useful bounds on real-world electrical input.

Where benchmark-derived efficiency or power ratios are used later in this analysis, rim-drive-specific evidence shall be preferred whenever available.

---

### 6.11 Benchmark Sources

The following primary manufacturer sources were reviewed on 2026-08-11:

| Source ID | Manufacturer | Source |
|---|---|---|
| BM-001 | Hydromea | DISKDRIVE 50 manufacturer datasheet |
| BM-002 | Hydromea | DISKDRIVE 80 manufacturer datasheet |
| BM-003 | Blue Robotics | T200 manufacturer technical specifications and performance data |
| BM-004 | Blue Robotics | T500 manufacturer technical specifications and performance data |
| BM-005 | Rim Drive Technology | Bow Thruster 3.0 manufacturer technical specifications |

Manufacturer values are retained as published. Where Project Triton later derives quantities from these data, the derived value shall be explicitly identified as an engineering calculation rather than manufacturer-certified performance.

---

## 7. Candidate RDT-80 Thrust Objectives

### 7.1 Candidate Selection Basis

Three candidate performance levels are established for comparative analysis.

The candidates are intended to span a meaningful portion of the performance range identified in Section 6 while remaining relevant to an approximately 80 mm rim-driven development thruster.

The candidate values are expressed as forward static thrust because static thrust is the primary initial performance metric established in Section 5.

The values are analysis candidates only. They do not constitute approved Project Triton requirements until selected through this analysis and incorporated into PT-REQ-001 through configuration control.

---

### 7.2 Candidate A — Minimum Demonstrator

**Candidate A:**

| Parameter | Candidate Value |
|---|---:|
| Continuous forward static thrust | 5 kgf |
| Continuous forward static thrust | approximately 49 N |
| Peak forward static thrust | 7 kgf |
| Peak forward static thrust | approximately 69 N |
| Peak duration | TBD |
| Reverse thrust | TBD |
| Propulsor nominal diameter | approximately 80 mm; final geometry controlled by OI-002 |

Candidate A represents a relatively conservative performance objective for the RDT-80.

A 5 kgf continuous-thrust target would:

- exceed the performance of Hydromea's smaller 50 mm rim-driven benchmark;
- fall within the demonstrated performance range of current compact 76–80 mm underwater thrusters;
- provide sufficient thrust to represent useful small-vehicle propulsion rather than merely laboratory-detectable thrust;
- reduce electrical, electromagnetic, structural, thermal, and test-system demands relative to the higher candidates;
- provide margin for early prototype inefficiencies and manufacturing limitations.

The 7 kgf peak objective corresponds approximately to the published maximum static thrust of the Hydromea DISKDRIVE 80 benchmark.

Candidate A therefore represents the lowest performance level presently considered appropriate for a successful RDT-80 engineering prototype.

A materially lower objective would reduce the technical value of the prototype because commercially demonstrated thrusters of similar physical scale already operate in this performance region.

---

### 7.3 Candidate B — Representative Engineering Prototype

**Candidate B:**

| Parameter | Candidate Value |
|---|---:|
| Continuous forward static thrust | 7 kgf |
| Continuous forward static thrust | approximately 69 N |
| Peak forward static thrust | 10 kgf |
| Peak forward static thrust | approximately 98 N |
| Peak duration | TBD |
| Reverse thrust | TBD |
| Propulsor nominal diameter | approximately 80 mm; final geometry controlled by OI-002 |

Candidate B represents a more demanding but technically credible target for the primary Project Triton engineering prototype.

A 7 kgf continuous-thrust objective would place the RDT-80 at approximately the published maximum-thrust level of the Hydromea DISKDRIVE 80 while requiring Project Triton to demonstrate that level as a sustained capability under subsequently defined reference conditions.

The 10 kgf peak objective intentionally exceeds the published DISKDRIVE 80 benchmark and would require the Project Triton architecture to demonstrate additional capability rather than merely reproduce an existing commercial performance point.

Candidate B would:

- provide a technically meaningful performance goal for an approximately 80 mm rim-driven propulsor;
- exercise rotor support, electromagnetic drive, structural, thermal, control, and test systems at substantial loads;
- provide useful differentiation from lower-performance compact thrusters;
- remain well below the approximately 25 kgf performance demonstrated by a much higher-power commercial rim-drive unit of similar propulsor diameter;
- preserve a credible path toward later higher-power variants;
- impose materially greater engineering requirements than Candidate A without immediately forcing the prototype into the highest-power benchmark regime.

Candidate B is therefore considered the **provisional leading candidate** for further engineering analysis.

This designation is preliminary and does not constitute approval of the 7 kgf continuous or 10 kgf peak values.

---

### 7.4 Candidate C — High-Performance Prototype

**Candidate C:**

| Parameter | Candidate Value |
|---|---:|
| Continuous forward static thrust | 10 kgf |
| Continuous forward static thrust | approximately 98 N |
| Peak forward static thrust | 15 kgf |
| Peak forward static thrust | approximately 147 N |
| Peak duration | TBD |
| Reverse thrust | TBD |
| Propulsor nominal diameter | approximately 80 mm; final geometry controlled by OI-002 |

Candidate C represents an aggressive performance target for the initial RDT-80 prototype.

A 10 kgf continuous-thrust target would materially exceed the published compact 76–80 mm benchmark thrusters reviewed in Section 6.

A 15 kgf peak target approaches the maximum published thrust of the substantially larger Blue Robotics T500 while remaining below the 25 kgf commercial high-power rim-drive benchmark.

Candidate C would provide substantial technical value if achieved, but it would likely increase:

- required electrical input power;
- electromagnetic loading;
- winding and controller current;
- rotor torque;
- rotor-support loads;
- structural loading;
- heat generation;
- cooling demand;
- containment requirements;
- manufacturing precision requirements;
- instrumentation range;
- test-fixture capability;
- prototype development risk.

Candidate C therefore serves as an important upper-bound design study even if it is not selected as the initial RDT-80 requirement.

---

### 7.5 Candidate Comparison

| Criterion | Candidate A | Candidate B | Candidate C |
|---|---:|---:|---:|
| Continuous thrust | 5 kgf / 49 N | 7 kgf / 69 N | 10 kgf / 98 N |
| Peak thrust | 7 kgf / 69 N | 10 kgf / 98 N | 15 kgf / 147 N |
| Relative technical ambition | Moderate | High | Very High |
| Benchmark support at approximately 80 mm scale | Strong | Moderate to Strong | Limited |
| Expected electrical demand | Lowest | Intermediate | Highest |
| Expected thermal challenge | Lowest | Intermediate | Highest |
| Expected rotor/support loading | Lowest | Intermediate | Highest |
| Expected test-system demand | Lowest | Intermediate | Highest |
| Performance differentiation | Limited to Moderate | Strong | Very Strong |
| Development risk | Lowest | Intermediate | Highest |
| Initial assessment | Credible fallback / minimum success level | Provisional leading candidate | Upper-bound stretch objective |

---

### 7.6 Preliminary Candidate Screening

#### Candidate A

Candidate A is considered technically credible based on current benchmark evidence and is expected to provide the lowest development risk.

Its principal disadvantage is that successful achievement would demonstrate performance already broadly available from commercial thrusters of approximately similar scale.

Candidate A should therefore be retained primarily as:

- a minimum acceptable prototype-performance level;
- a fallback requirement if higher targets prove incompatible with practical RDT-80 constraints; and
- a useful intermediate development milestone.

#### Candidate B

Candidate B presently provides the strongest balance among:

- technical usefulness;
- benchmark credibility;
- performance differentiation;
- development risk;
- prototype scale;
- likely power requirements; and
- usefulness for validating the Project Triton architecture.

Candidate B shall therefore receive primary attention in the subsequent analytical evaluation.

#### Candidate C

Candidate C is intentionally aggressive.

It should be retained as an upper-bound case because analysis of Candidate C will help identify:

- which subsystem first becomes performance-limiting;
- the power required to move materially beyond existing compact-thruster performance;
- whether the nominal RDT-80 geometry is appropriate for higher-thrust operation;
- whether a higher-performance design should instead become a later Project Triton variant.

Candidate C shall not be selected solely because it offers the highest performance.

---

### 7.7 Continuous Versus Peak Capability

The distinction between continuous and peak thrust shall be preserved for all candidates.

**Continuous thrust** shall ultimately represent a thrust level that can be maintained for the approved continuous operating duration without exceeding:

- electrical limits;
- winding-temperature limits;
- magnet-temperature limits;
- controller-temperature limits;
- rotor-support limits;
- structural limits;
- vibration limits;
- environmental-protection limits; or
- other applicable operating constraints.

**Peak thrust** shall represent a higher short-duration capability whose allowable duration is explicitly established by analysis and test.

Peak-thrust duration remains TBD until thermal and electrical analyses provide a defensible basis.

No published maximum-thrust value from a benchmark thruster shall be assumed to represent continuous capability unless the source explicitly establishes continuous operation at that condition.

---

### 7.8 Preliminary Direction

Based on benchmark evidence available at this stage:

**Candidate B — 7 kgf continuous forward static thrust and 10 kgf peak forward static thrust — is selected as the provisional reference case for the next stage of engineering analysis.**

This is an analysis selection only.

Before Candidate B may become the approved RDT-80 thrust requirement, the project shall evaluate its compatibility with:

1. approximately 80 mm propulsor geometry;
2. required induced flow and hydrodynamic loading;
3. required mechanical power;
4. estimated electrical input power;
5. rotor torque and speed;
6. electromagnetic feasibility;
7. rotor support and retention;
8. structural loading;
9. thermal rejection;
10. practical prototype power electronics;
11. controlled test-facility capability; and
12. acceptable development risk.

Candidate A and Candidate C shall remain in the analysis as lower- and upper-bound comparison cases.

---

## 8. Preliminary Analytical Basis

### 8.1 Purpose

A first-order momentum-theory analysis is used to determine whether the Candidate A, B, and C thrust objectives are physically reasonable for an approximately 80 mm propulsor.

This analysis establishes:

- equivalent disk area;
- disk loading;
- ideal induced velocity;
- ideal far-wake velocity;
- ideal induced power; and
- the theoretical minimum power trend associated with increasing static thrust.

The analysis does not account for:

- finite blade number;
- blade drag;
- duct losses or duct augmentation;
- swirl;
- tip-clearance losses;
- nonuniform inflow;
- rotor/stator blockage;
- electromagnetic losses;
- motor-controller losses;
- bearing or rotor-support losses;
- cavitation;
- manufacturing imperfections; or
- other real-system effects.

Accordingly, the calculated power values represent ideal hydrodynamic lower bounds rather than predicted RDT-80 electrical input power.

---

### 8.2 Reference Geometry and Fluid Conditions

For this preliminary comparison, the RDT-80 is represented by an ideal circular actuator disk having a nominal diameter of:

**D = 0.080 m**

The corresponding disk area is:

**A = πD² / 4**

Therefore:

**A ≈ 0.00503 m²**

The reference fluid is freshwater with an assumed density of:

**ρ = 997 kg/m³**

This value is representative of freshwater near room temperature and is adequate for preliminary candidate comparison.

Final verification conditions will later define the actual water temperature, density, salinity, and measurement tolerances.

Use of seawater density would slightly reduce the ideal induced velocity and ideal power required for the same thrust, but the difference is not large enough to affect the present candidate screening.

---

### 8.3 Static Actuator-Disk Relationship

For an ideal actuator disk operating statically in initially quiescent water, momentum theory gives:

**T = 2ρAvᵢ²**

where:

- **T** = thrust, N
- **ρ** = fluid density, kg/m³
- **A** = actuator-disk area, m²
- **vᵢ** = induced velocity through the actuator disk, m/s

Solving for induced velocity:

**vᵢ = √[T / (2ρA)]**

The ideal power imparted to the fluid is:

**Pᵢ = Tvᵢ**

which can also be expressed as:

**Pᵢ = T^(3/2) / √(2ρA)**

For the ideal static case, the far-wake velocity is approximately:

**v_wake = 2vᵢ**

These relationships show that required ideal power increases approximately with thrust raised to the 3/2 power.

Therefore, increasing thrust at fixed disk diameter becomes progressively more power-intensive rather than increasing linearly.

---

### 8.4 Candidate Actuator-Disk Results

Using an 80 mm disk and freshwater density of 997 kg/m³:

| Thrust Case | Static Thrust | Disk Loading | Ideal Induced Velocity | Ideal Far-Wake Velocity | Ideal Induced Power |
|---|---:|---:|---:|---:|---:|
| Candidate A continuous | 5 kgf / 49.0 N | 9.75 kPa | 2.21 m/s | 4.42 m/s | 108 W |
| Candidate A peak / Candidate B continuous | 7 kgf / 68.6 N | 13.66 kPa | 2.62 m/s | 5.23 m/s | 180 W |
| Candidate B peak / Candidate C continuous | 10 kgf / 98.1 N | 19.51 kPa | 3.13 m/s | 6.26 m/s | 307 W |
| Candidate C peak | 15 kgf / 147.1 N | 29.26 kPa | 3.83 m/s | 7.66 m/s | 564 W |

The calculated values are rounded for preliminary engineering use.

---

### 8.5 Interpretation of Candidate A

Candidate A requires approximately:

- 108 W of ideal induced power at 5 kgf continuous thrust; and
- 180 W of ideal induced power at 7 kgf peak thrust.

These values are comfortably below the electrical-input levels demonstrated by comparable commercial compact thrusters.

Because actual electrical input must exceed ideal induced power, Candidate A would still require several hundred watts of practical system input depending on the eventual hydrodynamic and electromechanical performance.

The actuator-disk analysis therefore supports the conclusion that Candidate A should be physically achievable at the nominal RDT-80 scale unless substantial losses, geometric constraints, or other implementation limitations dominate the design.

Candidate A remains an appropriate minimum-success or fallback performance level.

---

### 8.6 Interpretation of Candidate B

Candidate B requires approximately:

- 180 W of ideal induced power at 7 kgf continuous thrust; and
- 307 W of ideal induced power at 10 kgf peak thrust.

These values are significantly lower than the electrical power that a real thruster would require because the actuator-disk calculation represents only the ideal hydrodynamic energy transfer.

The result is nevertheless important because it demonstrates that 7 kgf continuous and 10 kgf peak thrust do not inherently require multi-kilowatt hydrodynamic power at an 80 mm disk.

The 7 kgf continuous case corresponds to a disk loading of approximately:

**13.7 kPa**

The 10 kgf peak case corresponds to approximately:

**19.5 kPa**

This increase in disk loading is substantial but remains within a range that warrants further analysis rather than immediate rejection.

Candidate B therefore remains a credible provisional reference case.

---

### 8.7 Interpretation of Candidate C

Candidate C requires approximately:

- 307 W of ideal induced power at 10 kgf continuous thrust; and
- 564 W of ideal induced power at 15 kgf peak thrust.

The 15 kgf case results in a disk loading of approximately:

**29.3 kPa**

and an ideal far-wake velocity approaching:

**7.7 m/s**

At this loading, real-system penalties associated with:

- blade loading;
- cavitation tendency;
- duct losses;
- tip clearance;
- electromagnetic torque;
- structural load;
- rotor retention;
- heat generation; and
- controller current

are likely to become increasingly significant.

Candidate C is therefore not rejected by ideal momentum theory, but the analysis supports treating it as an aggressive upper-bound case rather than the initial design requirement.

---

### 8.8 Scaling Effect of Thrust at Fixed Diameter

Because:

**Pᵢ ∝ T^(3/2)**

at fixed disk area, thrust increases become progressively more expensive in ideal power.

Using the 5 kgf case as a reference:

| Thrust | Relative Thrust | Relative Ideal Power | Ideal Power |
|---|---:|---:|---:|
| 5 kgf | 1.00 | 1.00 | 108 W |
| 7 kgf | 1.40 | 1.66 | 180 W |
| 10 kgf | 2.00 | 2.83 | 307 W |
| 15 kgf | 3.00 | 5.20 | 564 W |

Tripling static thrust from 5 kgf to 15 kgf therefore requires more than five times the ideal induced power when disk diameter remains fixed.

This relationship is a principal reason that Candidate C creates substantially greater electrical, thermal, structural, and hydrodynamic demands.

---

### 8.9 Importance of Propulsor Diameter

The same momentum relationship also demonstrates the importance of disk area.

For a given required thrust:

**Pᵢ ∝ 1 / √A**

Increasing propulsor diameter therefore reduces ideal induced power and disk loading.

Because disk area increases with diameter squared, even a moderate increase in diameter can materially reduce hydrodynamic loading.

This result directly couples OI-001 — Thrust Objective — to OI-002 — Principal Prototype Geometry.

The nominal RDT-80 scale should therefore not be treated as immutable if subsequent analysis shows that an alternative diameter would produce a substantially better engineering solution.

Any geometry change would require deliberate configuration-control treatment rather than being introduced implicitly.

---

### 8.10 Relationship to Benchmark Data

The ideal power calculations can be compared qualitatively with the benchmark results from Section 6.

For example:

- approximately 7 kgf at an 80 mm ideal disk requires only about 180 W of ideal induced power;
- Hydromea publishes approximately 7 kgf maximum thrust for its 80 mm DISKDRIVE at a 24 V system with a 30 A maximum-current rating;
- the Blue Robotics T200 produces approximately 6.7 kgf at about 645 W electrical input.

The difference between approximately 180 W ideal induced power and several hundred watts of real electrical input is expected.

It reflects the combined effects of:

- nonideal propulsor performance;
- finite blade losses;
- flow swirl;
- duct behavior;
- motor losses;
- controller losses;
- mechanical losses; and
- other system inefficiencies.

The comparison reinforces the requirement that ideal actuator-disk power must not be used directly as the RDT-80 electrical-power requirement.

---

### 8.11 Preliminary Electrical-Power Implication

The present analysis does not yet establish RDT-80 electrical input power.

However, the combination of actuator-disk theory and benchmark data supports a preliminary qualitative assessment:

| Candidate | Ideal Hydrodynamic Demand | Preliminary Electrical-Power Implication |
|---|---|---|
| Candidate A | Low to Moderate | Likely compatible with a several-hundred-watt prototype |
| Candidate B | Moderate | Likely compatible with a sub-kilowatt to approximately kilowatt-class prototype, subject to detailed analysis |
| Candidate C | High | Likely pushes toward approximately kilowatt-class or greater electrical capability, depending on real system performance |

These descriptions are intentionally approximate.

OI-003 shall remain open until electromagnetic, hydrodynamic, controller, and thermal analyses establish defensible electrical voltage, current, and power requirements.

---

### 8.12 Preliminary Cavitation Consideration

Increasing thrust at fixed diameter increases:

- disk loading;
- local blade loading;
- induced velocity;
- pressure differential; and
- required rotational or circulation loading.

These trends generally increase the likelihood that cavitation becomes an important design constraint.

The actuator-disk model does not predict local blade-surface pressure and therefore cannot establish a cavitation limit.

Candidate B and especially Candidate C shall therefore require subsequent blade-level hydrodynamic analysis before their feasibility can be fully assessed.

The cavitation criterion remains controlled by SR-060 and ORD-018.

---

### 8.13 Preliminary Analytical Finding

Ideal actuator-disk momentum theory does not identify a fundamental hydrodynamic-power barrier to any of the three candidate thrust ranges at approximately 80 mm diameter.

However, the nonlinear increase in disk loading and required ideal power clearly differentiates the candidates.

The current preliminary ranking is:

1. **Candidate A — clearly feasible as a development objective based on first-order power considerations.**
2. **Candidate B — physically credible and remains the preferred reference case for further analysis.**
3. **Candidate C — physically possible in ideal theory but sufficiently demanding to warrant treatment as an upper-bound or later-development objective.**

The present calculation therefore supports continued evaluation of:

**7 kgf continuous / 10 kgf peak**

as the provisional RDT-80 reference thrust objective.

It does not yet provide sufficient evidence to close OI-001.

---

### 8.14 Preliminary Real-System Electrical-Power Estimate

The ideal induced-power values calculated in Sections 8.4 through 8.8 represent only the minimum power transferred to the water.

A real RDT-80 system must additionally accommodate losses associated with:

- propulsor blade drag;
- finite blade number;
- flow swirl;
- duct and clearance losses;
- electromagnetic losses;
- winding resistance;
- magnetic losses;
- motor-controller switching and conduction losses;
- rotor-support losses;
- mechanical friction;
- nonuniform flow; and
- prototype manufacturing imperfections.

Accordingly:

**P_electrical > P_ideal**

For preliminary system sizing, an effective ratio is defined as:

**η_system = P_ideal / P_electrical**

where:

- **η_system** is a preliminary overall static-thrust effectiveness factor;
- **P_ideal** is ideal actuator-disk induced power; and
- **P_electrical** is electrical input power.

Rearranging:

**P_electrical = P_ideal / η_system**

This ratio is used only as a preliminary planning tool and shall not be interpreted as an approved RDT-80 efficiency requirement.

---

### 8.15 Benchmark-Derived Reference Range

Using the manufacturer performance data reviewed in Section 6 together with actuator-disk calculations provides an approximate indication of real-system performance.

For the Blue Robotics T200:

| Published Operating Point | Calculated Ideal Power | Published Electrical Input | Approximate Ratio P_ideal / P_electrical |
|---|---:|---:|---:|
| 5.25 kgf at 16 V | approximately 123 W | 390 W | approximately 31% |
| 6.7 kgf at 20 V | approximately 177 W | 645 W | approximately 27% |

For the Blue Robotics T500:

| Published Operating Point | Calculated Ideal Power | Published Electrical Input | Approximate Ratio P_ideal / P_electrical |
|---|---:|---:|---:|
| 9.3 kgf at 16 V | approximately 192 W | 402 W | approximately 48% |
| 16.1 kgf at 24 V | approximately 438 W | 1044 W | approximately 42% |

These values are derived engineering calculations rather than manufacturer-published efficiency ratings.

The Blue Robotics values above are general propulsor benchmarks rather than architecture-comparable RDT benchmarks. Their calculated ratios shall therefore be used only to establish a broad practical screening range and shall not be treated as expected RDT-80 efficiency.

Rim-drive-specific benchmark data shall receive greater weight as additional comparable performance information becomes available.

The results demonstrate that practical static-thrust systems may require roughly two to four times the ideal actuator-disk power depending on geometry, operating point, and system design.

Because the RDT-80 is an early development prototype with unresolved electromagnetic, hydrodynamic, and manufacturing details, a deliberately conservative preliminary range of:

**η_system = 25% to 40%**

shall be used for candidate power-envelope screening.

A nominal planning value of:

**η_system = 30%**

may be used for preliminary comparison when a single representative estimate is useful.

Neither the 25–40% range nor the 30% planning value constitutes an approved system requirement.

---

### 8.16 Candidate Electrical-Power Ranges

Applying the 25–40% preliminary effectiveness range to the ideal induced-power values gives:

| Thrust Case | Ideal Induced Power | Estimated Electrical Input at 40% | Estimated Electrical Input at 25% | Preliminary Electrical Range |
|---|---:|---:|---:|---:|
| 5 kgf | 108 W | 270 W | 432 W | approximately 0.27–0.43 kW |
| 7 kgf | 180 W | 450 W | 720 W | approximately 0.45–0.72 kW |
| 10 kgf | 307 W | 768 W | 1228 W | approximately 0.77–1.23 kW |
| 15 kgf | 564 W | 1410 W | 2256 W | approximately 1.41–2.26 kW |

Using the nominal 30% planning factor:

| Thrust Case | Nominal Preliminary Electrical Input |
|---|---:|
| 5 kgf | approximately 360 W |
| 7 kgf | approximately 600 W |
| 10 kgf | approximately 1.02 kW |
| 15 kgf | approximately 1.88 kW |

These values are preliminary system-sizing estimates only.

---

### 8.17 Candidate-Level Electrical Implications

#### Candidate A

Candidate A consists of:

- 5 kgf continuous thrust; and
- 7 kgf peak thrust.

The preliminary electrical-power estimate is therefore:

| Condition | Preliminary Range | Nominal 30% Planning Estimate |
|---|---:|---:|
| Continuous | approximately 270–430 W | approximately 360 W |
| Peak | approximately 450–720 W | approximately 600 W |

Candidate A appears compatible with a relatively modest prototype electrical system.

---

#### Candidate B

Candidate B consists of:

- 7 kgf continuous thrust; and
- 10 kgf peak thrust.

The preliminary electrical-power estimate is:

| Condition | Preliminary Range | Nominal 30% Planning Estimate |
|---|---:|---:|
| Continuous | approximately 450–720 W | approximately 600 W |
| Peak | approximately 770–1230 W | approximately 1.02 kW |

This result is significant.

Candidate B does not appear to require a continuously multi-kilowatt system.

Instead, a first-order planning basis suggests approximately:

**600 W continuous electrical input**

and approximately:

**1 kW peak electrical input**

subject to substantial refinement through electromagnetic, hydrodynamic, and thermal analysis.

Candidate B therefore remains compatible with a practical laboratory-scale engineering prototype.

---

#### Candidate C

Candidate C consists of:

- 10 kgf continuous thrust; and
- 15 kgf peak thrust.

The preliminary electrical-power estimate is:

| Condition | Preliminary Range | Nominal 30% Planning Estimate |
|---|---:|---:|
| Continuous | approximately 770–1230 W | approximately 1.02 kW |
| Peak | approximately 1.41–2.26 kW | approximately 1.88 kW |

Candidate C therefore begins to require substantially more demanding:

- DC power capability;
- motor-controller current capacity;
- winding thermal capacity;
- electromagnetic loading;
- conductor sizing;
- switching hardware;
- cooling;
- test instrumentation; and
- electrical safety provisions.

Although still technically plausible, Candidate C increasingly represents a different class of prototype from Candidate A or Candidate B.

---

### 8.18 Implication for OI-003

The present analysis provides the first quantitative linkage between:

**OI-001 — Thrust Objective**

and:

**OI-003 — Operating Voltage and Power Range**

If Candidate B remains the preferred thrust objective, a reasonable preliminary power-planning envelope for subsequent analysis is:

- approximately **0.6 kW continuous electrical input**; and
- approximately **1.0 kW peak electrical input**.

For conservative component-screening purposes, subsequent OI-003 work should initially evaluate hardware capable of supporting at least approximately:

**1.2 kW peak electrical input**

until better hydrodynamic and electromagnetic efficiency estimates are available.

This value is a planning envelope, not an approved requirement.

The final electrical-power requirement shall account for:

- actual propulsor performance;
- electromagnetic efficiency;
- controller efficiency;
- allowable thermal rise;
- continuous duty duration;
- peak duty duration;
- voltage selection;
- conductor losses;
- transient current;
- protection margins; and
- measured prototype performance.

---

### 8.19 Preliminary Electrical-Power Finding

The combined actuator-disk and benchmark analysis strengthens the case for Candidate B.

A 7 kgf continuous / 10 kgf peak RDT-80 does not presently appear to require an impractical power system.

The current first-order planning estimate is approximately:

**600 W continuous / 1.0 kW peak**

with a preliminary uncertainty range extending approximately from:

- **450–720 W** at the 7 kgf condition; and
- **770–1230 W** at the 10 kgf condition.

This result is sufficiently practical to continue Candidate B as the primary reference case.

The analysis does not yet establish the operating voltage, current, winding configuration, controller topology, or final electrical-power requirement.

Those decisions remain controlled by OI-003.

---

### 8.20 Propulsor-Diameter Sensitivity

The preceding candidate analysis used an 80 mm nominal propulsor diameter because that scale is consistent with the current RDT-80 concept and provides direct comparison with the Hydromea DISKDRIVE 80.

However, OI-002 — Principal Prototype Geometry — remains open.

The effect of propulsor diameter shall therefore be evaluated before 80 mm is treated as a fixed design requirement.

For a circular actuator disk:

**A = πD² / 4**

At fixed thrust:

**Disk Loading ∝ 1 / D²**

and:

**Pᵢ ∝ 1 / D**

Therefore, increasing propulsor diameter reduces both disk loading and ideal induced-power requirement.

The power benefit is approximately proportional to diameter, while the disk-loading benefit is stronger because area increases with diameter squared.

---

### 8.21 Candidate B Diameter Comparison

The Candidate B operating points are:

- continuous static thrust = 7 kgf / approximately 68.6 N; and
- peak static thrust = 10 kgf / approximately 98.1 N.

The following comparison uses freshwater density of 997 kg/m³ and ideal actuator-disk theory.

| Propulsor Diameter | 7 kgf Disk Loading | 7 kgf Ideal Power | 10 kgf Disk Loading | 10 kgf Ideal Power |
|---|---:|---:|---:|---:|
| 70 mm | 17.84 kPa | 205 W | 25.48 kPa | 351 W |
| 80 mm | 13.66 kPa | 180 W | 19.51 kPa | 307 W |
| 90 mm | 10.79 kPa | 160 W | 15.42 kPa | 273 W |
| 100 mm | 8.74 kPa | 144 W | 12.49 kPa | 245 W |
| 110 mm | 7.22 kPa | 131 W | 10.32 kPa | 223 W |
| 120 mm | 6.07 kPa | 120 W | 8.67 kPa | 204 W |

These values represent ideal hydrodynamic lower bounds only.

---

### 8.22 Relative Effect of Diameter

Using the 80 mm geometry as the reference:

| Diameter | Relative Diameter | Relative Disk Area | Relative Disk Loading at Fixed Thrust | Relative Ideal Power at Fixed Thrust |
|---|---:|---:|---:|---:|
| 70 mm | 0.875 | 0.766 | 1.306 | 1.143 |
| 80 mm | 1.000 | 1.000 | 1.000 | 1.000 |
| 90 mm | 1.125 | 1.266 | 0.790 | 0.889 |
| 100 mm | 1.250 | 1.563 | 0.640 | 0.800 |
| 110 mm | 1.375 | 1.891 | 0.529 | 0.727 |
| 120 mm | 1.500 | 2.250 | 0.444 | 0.667 |

Several observations follow.

#### 70 mm

Reducing the diameter from 80 mm to 70 mm:

- reduces disk area by approximately 23%;
- increases disk loading by approximately 31%;
- increases ideal power requirement by approximately 14%.

For Candidate B peak thrust, disk loading rises to approximately 25.5 kPa.

There is presently no strong technical reason to reduce the propulsor below approximately 80 mm unless packaging requirements later demand it.

---

#### 80 mm

At 80 mm:

- Candidate B continuous disk loading is approximately 13.7 kPa;
- Candidate B peak disk loading is approximately 19.5 kPa;
- ideal power is approximately 180 W continuous and 307 W peak.

This geometry is supported by the closest architecture-comparable commercial benchmark and remains physically credible for Candidate B.

The principal advantage of 80 mm is therefore not hydrodynamic optimum, but the combination of:

- compact size;
- direct benchmark comparability;
- practical prototype scale;
- manageable test-fixture size;
- reduced material and manufacturing demand; and
- meaningful thrust capability.

---

#### 90 mm

Increasing diameter from 80 mm to 90 mm:

- increases disk area by approximately 27%;
- reduces disk loading by approximately 21%;
- reduces ideal power by approximately 11%.

For Candidate B peak thrust, disk loading decreases from approximately 19.5 kPa to approximately 15.4 kPa.

A 90 mm propulsor therefore provides a meaningful hydrodynamic benefit for a relatively modest increase in diameter.

---

#### 100 mm

Increasing diameter from 80 mm to 100 mm:

- increases disk area by approximately 56%;
- reduces disk loading by approximately 36%;
- reduces ideal power by approximately 20%.

For Candidate B:

- continuous ideal power falls from approximately 180 W to 144 W;
- peak ideal power falls from approximately 307 W to 245 W.

A 100 mm propulsor therefore offers a substantial reduction in disk loading while remaining within the general physical scale of a small underwater thruster.

The disadvantages would include increased:

- outer housing diameter;
- rotor circumference;
- magnetic material requirement;
- structural material;
- hydrodynamic frontal area;
- manufacturing size;
- test-fixture size; and
- potentially rotor mass and rotational inertia.

---

#### 110–120 mm

Further diameter increases continue to reduce disk loading and ideal power.

However, the returns become increasingly difficult to justify solely on induced-power grounds.

For example, increasing from 100 mm to 120 mm reduces ideal power by an additional approximately 17%, but increases disk diameter by another 20%.

At this scale the RDT-80 would also begin to approach the propulsor size of larger conventional thrusters such as the T500 rather than remaining an approximately 80 mm-class technology demonstrator.

---

### 8.23 Preliminary Geometry Finding

The diameter sensitivity analysis does not identify a compelling reason to abandon the approximately 80 mm reference geometry for the initial RDT-80 prototype.

However, it also demonstrates that 80 mm should not yet be treated as hydrodynamically optimal.

The most technically interesting range for subsequent OI-002 analysis is presently:

**80–100 mm nominal propulsor diameter**

with three specific geometries deserving further comparison:

- **80 mm** — baseline / closest architecture-comparable benchmark;
- **90 mm** — moderate diameter increase with approximately 21% lower disk loading;
- **100 mm** — larger alternative with approximately 36% lower disk loading and approximately 20% lower ideal induced-power requirement.

The preliminary recommendation is therefore:

**Retain 80 mm as the RDT-80 reference geometry, but evaluate 90 mm and 100 mm alternatives before closing OI-002.**

The Project Triton designation **RDT-80** shall not itself be treated as a requirement that permanently fixes propulsor diameter at exactly 80 mm.

If subsequent hydrodynamic, electromagnetic, structural, or manufacturing analysis demonstrates that another diameter produces a materially superior engineering solution, the geometry shall be changed deliberately through configuration control.

This finding does not modify the provisional Candidate B thrust objective of:

**7 kgf continuous / 10 kgf peak forward static thrust.**

---

## 9. Trade Evaluation

### 9.1 Evaluation Method

Candidate A, Candidate B, and Candidate C are evaluated qualitatively against the principal criteria that affect selection of the initial RDT-80 thrust objective.

The evaluation is intended to identify the candidate that provides the best balance among:

- meaningful technical performance;
- feasibility at approximately 80–100 mm propulsor scale;
- practical electrical-power demand;
- electromagnetic development difficulty;
- rotor-support and structural loading;
- thermal management;
- manufacturability;
- testability;
- performance differentiation; and
- overall development risk.

The following qualitative ratings are used:

| Rating | Meaning |
|---|---|
| Very Favorable | Strongly supports selection |
| Favorable | Supports selection with manageable engineering effort |
| Moderate | Credible but presents material engineering challenges |
| Unfavorable | Significant difficulty or risk for the initial prototype |
| Very Unfavorable | Disproportionate difficulty or risk relative to initial-project objectives |

The evaluation is comparative rather than absolute.

A lower-performance candidate may be easier to develop but less useful technically, while a higher-performance candidate may provide greater capability but impose disproportionate development burden.

---

### 9.2 Candidate Trade Matrix

| Criterion | Candidate A — 5 kgf Continuous / 7 kgf Peak | Candidate B — 7 kgf Continuous / 10 kgf Peak | Candidate C — 10 kgf Continuous / 15 kgf Peak |
|---|---|---|---|
| Technical usefulness | Moderate | Very Favorable | Very Favorable |
| Benchmark credibility | Very Favorable | Favorable | Moderate |
| Hydrodynamic feasibility | Very Favorable | Favorable | Moderate |
| Electrical-power feasibility | Very Favorable | Favorable | Moderate |
| Electromagnetic feasibility | Favorable | Moderate to Favorable | Moderate to Unfavorable |
| Rotor-support feasibility | Favorable | Favorable | Moderate |
| Structural feasibility | Favorable | Favorable | Moderate |
| Thermal feasibility | Very Favorable | Favorable | Moderate to Unfavorable |
| Manufacturing feasibility | Very Favorable | Favorable | Moderate |
| Testability | Very Favorable | Favorable | Moderate |
| Performance differentiation | Moderate | Very Favorable | Very Favorable |
| Scalability value | Moderate | Very Favorable | Very Favorable |
| Development risk | Very Favorable | Favorable | Unfavorable |
| Overall assessment | Favorable fallback | Preferred initial objective | Stretch / later-development objective |

---

### 9.3 Technical Usefulness

#### Candidate A

Candidate A would demonstrate useful underwater thrust and would constitute a successful proof of the Project Triton architecture.

However, approximately 5–7 kgf static thrust is already demonstrated by commercial thrusters near the nominal RDT-80 size.

Candidate A would therefore provide comparatively limited performance differentiation.

**Assessment: Moderate**

---

#### Candidate B

Candidate B establishes a more meaningful development objective.

A 7 kgf continuous requirement would require RDT-80 to sustain approximately the maximum published thrust of the closest architecture-comparable benchmark rather than merely reach that value transiently.

A 10 kgf peak capability would extend beyond the closest compact rim-drive benchmark and provide meaningful additional performance for system development.

**Assessment: Very Favorable**

---

#### Candidate C

Candidate C would provide very strong technical differentiation and would demonstrate high specific thrust from a compact rim-driven system.

Its technical value would be substantial if achieved.

However, technical usefulness alone does not justify imposing disproportionate difficulty on the first integrated prototype.

**Assessment: Very Favorable**

---

### 9.4 Hydrodynamic Feasibility

#### Candidate A

At approximately 80 mm diameter:

- continuous disk loading is approximately 9.8 kPa; and
- peak disk loading is approximately 13.7 kPa.

The first-order momentum analysis and comparable hardware provide strong support for this performance region.

**Assessment: Very Favorable**

---

#### Candidate B

At approximately 80 mm diameter:

- continuous disk loading is approximately 13.7 kPa; and
- peak disk loading is approximately 19.5 kPa.

Momentum theory identifies no fundamental barrier.

The diameter-sensitivity analysis also demonstrates that moderate increases to approximately 90–100 mm could materially reduce disk loading if later hydrodynamic analysis identifies a need for additional margin.

**Assessment: Favorable**

---

#### Candidate C

At approximately 80 mm diameter:

- continuous disk loading is approximately 19.5 kPa; and
- peak disk loading is approximately 29.3 kPa.

Ideal momentum theory does not reject these values, but blade loading, cavitation, duct interaction, tip clearance, and other nonideal effects become increasingly important.

**Assessment: Moderate**

---

### 9.5 Electrical-Power Feasibility

The preliminary planning estimates are:

| Candidate | Continuous Electrical Input | Peak Electrical Input |
|---|---:|---:|
| Candidate A | approximately 0.27–0.43 kW | approximately 0.45–0.72 kW |
| Candidate B | approximately 0.45–0.72 kW | approximately 0.77–1.23 kW |
| Candidate C | approximately 0.77–1.23 kW | approximately 1.41–2.26 kW |

#### Candidate A

Candidate A is readily compatible with a several-hundred-watt laboratory power system.

**Assessment: Very Favorable**

#### Candidate B

Candidate B appears compatible with approximately:

- 0.6 kW nominal continuous planning input; and
- approximately 1.0 kW nominal peak planning input.

This remains practical for laboratory-scale development and does not force the initial prototype into a continuously multi-kilowatt electrical architecture.

**Assessment: Favorable**

#### Candidate C

Candidate C would likely require approximately kilowatt-class continuous capability and potentially more than 2 kW under less favorable real-system performance.

That substantially increases voltage/current, conductor, controller, protection, and test-equipment requirements.

**Assessment: Moderate**

---

### 9.6 Electromagnetic Feasibility

Electromagnetic feasibility cannot yet be conclusively established because OI-004, OI-005, and OI-006 remain unresolved.

However, the thrust candidates imply progressively higher torque and power requirements.

#### Candidate A

Provides the greatest margin for accommodating early electromagnetic inefficiencies and prototype limitations.

**Assessment: Favorable**

#### Candidate B

Requires a materially capable annular motor while remaining within the general power range demonstrated by compact underwater propulsion systems.

Candidate B is sufficiently demanding to provide useful electromagnetic-development evidence without yet requiring the highest-power architecture considered.

**Assessment: Moderate to Favorable**

#### Candidate C

Places substantially greater demand on:

- ampere-turn capability;
- magnetic loading;
- winding current density;
- conductor area;
- heat rejection;
- magnet retention;
- rotor loading; and
- controller current.

Candidate C may ultimately be feasible, but sufficient evidence does not yet exist to make it the initial required performance point.

**Assessment: Moderate to Unfavorable**

---

### 9.7 Rotor-Support and Structural Feasibility

The higher thrust candidates generally increase:

- hydrodynamic rotor loading;
- torque reaction;
- support loading;
- structural deflection demands;
- containment requirements; and
- consequences of mechanical failure.

Candidate A provides the greatest mechanical margin.

Candidate B imposes meaningful loads but remains appropriate for development of the rotor-support and containment architecture.

Candidate C increases mechanical demands before the support architecture, material system, tolerances, and containment design have been demonstrated.

| Candidate | Assessment |
|---|---|
| Candidate A | Favorable |
| Candidate B | Favorable |
| Candidate C | Moderate |

---

### 9.8 Thermal Feasibility

Thermal feasibility is strongly related to actual electromagnetic and controller efficiency and therefore remains uncertain.

Nevertheless, preliminary electrical-power estimates establish a useful relative ranking.

#### Candidate A

Several-hundred-watt operation should provide the greatest flexibility for early thermal development.

**Assessment: Very Favorable**

#### Candidate B

Approximately 600 W nominal continuous input represents a meaningful but manageable thermal-development challenge for a submerged prototype where deliberate heat-transfer paths can be incorporated.

**Assessment: Favorable**

#### Candidate C

Approximately 1 kW continuous input could create substantially greater winding, controller, magnet, and encapsulation thermal demands.

The peak condition may approach or exceed approximately 2 kW electrical input depending on actual system effectiveness.

**Assessment: Moderate to Unfavorable**

---

### 9.9 Manufacturing Feasibility

Candidate performance does not directly determine manufacturability, but increasing load generally requires:

- greater material capability;
- improved dimensional control;
- tighter clearances;
- stronger magnet retention;
- more robust rotor support;
- greater conductor cross section; and
- potentially more demanding manufacturing processes.

| Candidate | Assessment |
|---|---|
| Candidate A | Very Favorable |
| Candidate B | Favorable |
| Candidate C | Moderate |

Candidate B provides sufficient challenge to validate the intended engineering and manufacturing architecture without making maximum performance the dominant constraint on the first prototype.

---

### 9.10 Testability

Candidate A could be tested with the smallest power supply, load cell, fixture, protection system, and water-test infrastructure.

Candidate B increases test-system requirements but remains within a practical laboratory development scale.

Candidate C would materially increase:

- fixture loads;
- power-supply capability;
- electrical fault energy;
- containment requirements;
- instrumentation ranges;
- water-flow energy; and
- personnel-protection requirements.

| Candidate | Assessment |
|---|---|
| Candidate A | Very Favorable |
| Candidate B | Favorable |
| Candidate C | Moderate |

---

### 9.11 Development Risk

#### Candidate A

Candidate A presents the lowest overall development risk but also provides the least performance differentiation.

**Assessment: Very Favorable from a risk perspective**

#### Candidate B

Candidate B introduces significant but purposeful engineering challenges.

Those challenges directly exercise the technologies Project Triton is intended to develop:

- annular electromagnetic drive;
- rotor support;
- rotor retention;
- controlled clearances;
- thermal management;
- hydrodynamic optimization;
- motor control; and
- structural integration.

The risk therefore appears proportionate to the technical value.

**Assessment: Favorable**

#### Candidate C

Candidate C increases several major risks simultaneously before the principal architecture has been demonstrated experimentally.

Selecting Candidate C as the initial mandatory performance objective could cause the project to optimize prematurely for maximum thrust rather than first demonstrating a robust rim-driven architecture.

**Assessment: Unfavorable**

---

### 9.12 Performance Differentiation

Candidate A primarily demonstrates successful implementation.

Candidate B demonstrates successful implementation together with performance that meaningfully extends beyond the lower compact-thruster benchmark region.

Candidate C would provide the greatest differentiation but at substantially increased risk.

| Candidate | Assessment |
|---|---|
| Candidate A | Moderate |
| Candidate B | Very Favorable |
| Candidate C | Very Favorable |

---

### 9.13 Trade Result

The trade evaluation identifies Candidate B as providing the best overall balance between performance and development feasibility.

Candidate A remains highly valuable as:

- an intermediate development milestone;
- a minimum-success criterion; and
- a fallback operating level if technical limitations prevent Candidate B performance in the first prototype.

Candidate C remains valuable as:

- a stretch objective;
- an upper-bound analytical case;
- a means of identifying limiting subsystems; and
- a potential basis for a later higher-performance Project Triton configuration.

The trade result is therefore:

**Preferred Initial RDT-80 Objective: Candidate B**

with:

**7 kgf continuous forward static thrust**

and:

**10 kgf peak forward static thrust**

subject to final definition of:

- continuous operating duration;
- peak operating duration;
- reference water conditions;
- measurement tolerance;
- controllable thrust range;
- reverse-thrust capability; and
- final acceptance criteria.

---

### 9.14 Development Milestone Interpretation

The candidate levels should not be treated as mutually exclusive outcomes.

A staged development interpretation is preferred:

| Development Level | Performance Objective | Interpretation |
|---|---|---|
| Milestone A | 5 kgf forward static thrust | Minimum meaningful integrated performance milestone |
| Milestone B | 7 kgf forward static thrust | Target continuous performance |
| Milestone C | 10 kgf forward static thrust | Target peak performance |
| Stretch Development | Greater than 10 kgf | Experimental capability beyond the initial required objective |

This approach permits progressive validation of the system while preserving Candidate B as the intended performance requirement.

Failure to achieve 10 kgf during an early prototype test does not by itself invalidate the architecture if lower-energy development milestones have not yet been completed.

Likewise, successful operation above 10 kgf does not automatically expand the approved operating envelope.

All test progression remains subject to the controlled test-envelope requirements in PT-REQ-001.

---

### 9.15 Trade Evaluation Conclusion

Candidate B provides the strongest balance among:

- benchmark credibility;
- hydrodynamic feasibility;
- electrical-power practicality;
- engineering usefulness;
- prototype testability;
- performance differentiation; and
- acceptable development risk.

The analysis therefore supports advancing:

**7 kgf continuous / 10 kgf peak forward static thrust**

from a provisional reference case to the **recommended RDT-80 thrust objective**, pending completion of the remaining acceptance-condition definitions in Section 10.

OI-001 shall remain open until those conditions are established and the resulting quantitative requirements are incorporated into PT-REQ-001.

---

## 10. Recommended Thrust Objective

### 10.1 Recommended Performance Objective

Based on the benchmarking, actuator-disk analysis, preliminary electrical-power analysis, diameter-sensitivity analysis, and trade evaluation documented in Sections 6 through 9, the recommended initial RDT-80 performance objective is:

**7.0 kgf continuous forward static thrust**

and:

**10.0 kgf peak forward static thrust**

Equivalent SI values are:

| Performance Condition | Thrust |
|---|---:|
| Continuous forward static thrust | 7.0 kgf / approximately 68.6 N |
| Peak forward static thrust | 10.0 kgf / approximately 98.1 N |

These values represent the recommended minimum demonstrated thrust capability at the applicable reference conditions.

They do not represent maximum allowable thrust.

Operation above the verified performance level shall not automatically expand the approved operating envelope.

---

### 10.2 Continuous Thrust

The recommended continuous forward static-thrust requirement is:

**The RDT-80 shall produce not less than 7.0 kgf (68.6 N) forward static thrust while operating within the approved continuous operating envelope.**

For purposes of this requirement, "continuous" means operation at a thrust level that does not depend on a short-duration thermal, electrical, structural, or control excursion beyond the approved continuous operating limits.

The final verification duration for continuous operation shall be established after thermal analysis defines the time required to demonstrate:

- acceptable winding temperature;
- acceptable magnetic-element temperature;
- acceptable controller temperature;
- acceptable structural and rotor-support behavior; and
- stable or bounded thermal response.

Accordingly, the 7.0 kgf thrust magnitude is recommended for approval through OI-001, while the final continuous-duration verification criterion remains dependent on OI-014 — Thermal Management.

---

### 10.3 Peak Thrust

The recommended peak forward static-thrust requirement is:

**The RDT-80 shall produce not less than 10.0 kgf (98.1 N) forward static thrust for the approved peak operating duration while remaining within the approved peak operating envelope.**

Peak operation may use electrical, thermal, or mechanical capacity that is not approved for indefinite continuous operation.

The 10.0 kgf value therefore shall not be interpreted as a continuous-duty requirement.

The system shall return to an approved continuous operating condition or safe state before any applicable peak-duration, temperature, current, voltage, speed, vibration, or other operating limit is exceeded.

---

### 10.4 Peak Duration

The peak-duration requirement remains:

**TBD — subject to thermal, electromagnetic, controller, and structural analysis.**

No arbitrary peak duration shall be adopted solely to complete the requirements document.

The final duration shall be selected after analysis establishes the limiting transient mechanism and shall subsequently be verified by controlled testing.

The peak-duration decision shall define, at minimum:

- maximum permitted duration at the 10.0 kgf condition;
- required recovery or cooldown condition, if applicable;
- whether repeated peak operation is permitted;
- applicable temperature limits;
- applicable electrical limits; and
- automatic protection behavior when the approved duration or associated limit is reached.

Until this decision is closed, 10.0 kgf shall be treated as the target peak-thrust magnitude rather than authorization for unrestricted peak operation.

---

### 10.5 Controllable Forward-Thrust Range

The RDT-80 shall provide controlled forward thrust from approximately zero thrust through the approved continuous operating point of:

**7.0 kgf / 68.6 N**

and shall support commanded operation up to the approved peak point of:

**10.0 kgf / 98.1 N**

subject to the approved operating-state and protection logic.

The final requirements for:

- minimum stable nonzero thrust;
- command resolution;
- thrust linearity;
- allowable deadband;
- thrust-control accuracy; and
- transient response

remain TBD pending motor-control and propulsor characterization.

The control system shall not require operation at discrete fixed thrust levels only.

---

### 10.6 Reverse Thrust

Controlled reverse operation remains part of the intended RDT-80 capability, but no quantitative reverse-thrust percentage is established by the present analysis.

The RDT-80 shall be capable of producing controlled reverse thrust unless subsequent propulsor analysis demonstrates that reverse operation would create an unacceptable hydrodynamic, structural, electrical, or safety condition.

The initial propulsor may be optimized for forward performance.

Therefore:

**reverse thrust is not presently required to equal forward thrust.**

A quantitative reverse-thrust objective shall be established after propulsor geometry is sufficiently mature to evaluate forward/reverse performance tradeoffs.

This decision shall be coordinated with OI-015 — Propulsor Geometry and ORD-019.

---

### 10.7 Reference Static-Thrust Condition

The recommended 7.0 kgf continuous and 10.0 kgf peak values apply to a controlled static-thrust test condition.

The reference condition shall include:

| Parameter | Requirement / Current Basis |
|---|---|
| Fluid | Water |
| Initial bulk flow | Nominally stationary / no imposed vehicle advance velocity |
| Thrust direction | Forward |
| Thruster condition | Fully submerged |
| Propulsor configuration | Configuration-controlled production-representative prototype geometry for the test stage |
| Duct configuration | Configuration controlled and documented |
| Electrical configuration | Configuration controlled and documented |
| Measurement method | Calibrated thrust-measurement system |
| Water temperature | Measured and recorded; final verification range TBD |
| Water density | Determined or assigned from documented reference conditions |
| Salinity | Measured or documented as applicable |
| Immersion depth | Controlled and documented |
| Tank / facility boundary effects | Evaluated and demonstrated acceptable for the verification method |
| Test article configuration | Recorded and traceable |
| Instrumentation | Calibrated or otherwise verified appropriate for the measurement |

The final verification procedure shall define sufficiently controlled environmental and facility conditions to make the measured thrust result reproducible.

The present analysis does not require an arbitrary water temperature, salinity, immersion depth, or tank dimension before the test facility and verification method are selected.

---

### 10.8 Thrust Measurement and Acceptance

Thrust shall be verified using an instrumented test fixture capable of directly measuring axial reaction force.

The verification method shall include:

- zeroing or tare procedure;
- calibration status;
- measurement uncertainty;
- sampling rate;
- averaging method;
- test duration;
- electrical operating conditions;
- rotor speed, if measured;
- water conditions;
- test-article configuration; and
- applicable abort criteria.

The measured result shall demonstrate at least:

**68.6 N continuous forward static thrust**

at the approved continuous condition,

and:

**98.1 N peak forward static thrust**

at the approved peak condition.

Measurement uncertainty shall be characterized before formal requirement verification.

No undocumented subtraction of measurement uncertainty from the required thrust value shall be used to claim compliance.

---

### 10.9 Development Milestones

The following thrust levels shall be used as progressive development milestones:

| Milestone | Forward Static Thrust | Purpose |
|---|---:|---|
| Initial meaningful performance milestone | 5 kgf / approximately 49 N | Demonstrate useful integrated propulsion capability |
| Continuous performance target | 7 kgf / approximately 68.6 N | Recommended continuous RDT-80 performance objective |
| Peak performance target | 10 kgf / approximately 98.1 N | Recommended peak RDT-80 performance objective |
| Stretch operation | Greater than 10 kgf | Experimental development only unless separately approved |

These milestones support progressive testing and shall not be interpreted as authorization to bypass the approved test-envelope expansion process.

---

### 10.10 Recommendation Basis

Candidate B is recommended because it provides the strongest balance among:

- direct rim-drive benchmark credibility;
- useful performance differentiation;
- hydrodynamic feasibility;
- manageable disk loading;
- plausible electrical-power demand;
- practical prototype scale;
- manageable laboratory testing;
- meaningful electromagnetic and rotor-support development challenge; and
- acceptable initial development risk.

The 7.0 kgf continuous objective approximately equals the maximum published static thrust of the closest architecture-comparable 80 mm rim-drive benchmark while requiring RDT-80 to establish that performance as an approved continuous operating point.

The 10.0 kgf peak objective provides meaningful performance beyond that closest benchmark without immediately driving the initial prototype into the approximately 2–3 kW high-power regime represented by more aggressive commercial systems.

The recommendation therefore establishes an ambitious but technically defensible initial objective.

---

### 10.11 OI-001 Resolution Status

The analysis supports approval of the following quantitative thrust magnitudes:

**Continuous forward static thrust: 7.0 kgf / 68.6 N minimum**

**Peak forward static thrust: 10.0 kgf / 98.1 N minimum**

However, OI-001 shall remain **Open — Resolution in Progress** until the following dependent acceptance conditions are resolved or formally transferred to controlled downstream decisions:

| Item | Status | Primary Dependency |
|---|---|---|
| Continuous thrust magnitude | Recommended for approval | OI-001 |
| Peak thrust magnitude | Recommended for approval | OI-001 |
| Continuous verification duration | Open | OI-014 / thermal analysis |
| Peak duration | Open | OI-014 / OI-003 |
| Quantitative reverse thrust | Open | OI-015 / propulsor analysis |
| Minimum controllable nonzero thrust | Open | OI-017 / control development |
| Verification environmental limits | Open | OI-019 / OI-023 / verification planning |
| Measurement uncertainty criterion | Open | OI-019 / OI-023 / verification planning |

OI-001 may be closed once these remaining dependencies have either:

1. been quantitatively resolved; or
2. been formally transferred to controlled downstream requirements or decisions without ambiguity in the approved thrust objective.

---

## 11. Requirements Impact

### 11.1 Purpose

This section identifies how the thrust-objective analysis affects PT-REQ-001 and distinguishes:

1. requirements that can now receive quantitative thrust values;
2. requirements that should remain unchanged because their dependent design or verification parameters remain unresolved; and
3. open decisions that are partially resolved but should not yet be closed.

The recommended thrust magnitudes established by this analysis are:

- **7.0 kgf / 68.6 N minimum continuous forward static thrust**; and
- **10.0 kgf / 98.1 N minimum peak forward static thrust**.

These values shall not be interpreted as resolving all operating-envelope, hydrodynamic-performance, control, or verification decisions associated with OI-001.

---

### 11.2 SR-001 — Mission-Level Thrust Function

Current requirement intent:

**The RDT-80 prototype shall convert supplied electrical power into controlled hydrodynamic thrust.**

No quantitative revision is required.

SR-001 is intentionally a mission-level functional requirement and should remain independent of a particular thrust value.

The quantitative performance obligation is more appropriately allocated to SR-054 and SR-055.

**Recommended disposition: No change.**

---

### 11.3 SR-054 — Continuous Thrust

SR-054 can now be made quantitative.

Recommended revised requirement:

**SR-054 — The RDT-80 shall produce not less than 7.0 kgf (68.6 N) forward static thrust while operating within the approved continuous operating envelope under defined reference test conditions.**

Verification shall remain:

**VM-002 — Analysis**

and:

**VM-004 — Test**

The final continuous verification duration remains unresolved and shall be established through the applicable thermal and verification-planning activities.

The absence of a final verification duration does not invalidate the selected continuous-thrust magnitude, but formal requirement closure shall require a defined verification condition.

The final performance-test implementation and reference-condition measurement basis shall retain traceability to OI-019. Authorization of the applicable test envelope and conditions shall retain traceability to OI-023 where applicable.

**Recommended disposition: Update quantitative thrust magnitude; retain Draft status.**

---

### 11.4 SR-055 — Peak Thrust

SR-055 can now be made quantitative while preserving the unresolved peak-duration dependency.

Recommended revised requirement:

**SR-055 — The RDT-80 shall produce not less than 10.0 kgf (98.1 N) forward static thrust for the approved peak operating duration while operating within the approved peak operating envelope and defined reference test conditions.**

Verification shall remain:

**VM-002 — Analysis**

and:

**VM-004 — Test**

The allowable peak duration remains unresolved.

Accordingly, this revision establishes the required peak-thrust magnitude but does not authorize unrestricted operation at 10.0 kgf.

The final performance-test implementation and reference-condition measurement basis shall retain traceability to OI-019. Authorization of the applicable test envelope and conditions shall retain traceability to OI-023 where applicable.

**Recommended disposition: Update quantitative thrust magnitude; retain Draft status.**

---

### 11.5 SR-056 — Controllable Thrust Range

Current requirement intent:

**The RDT-80 shall provide controllable thrust over the approved operating range in response to valid operating commands.**

The present analysis establishes that the intended forward operating range shall include:

- operation from approximately zero forward thrust;
- the 7.0 kgf / 68.6 N continuous operating point; and
- commanded operation to the 10.0 kgf / 98.1 N peak operating point when peak operation is authorized.

However, the analysis does not yet establish:

- minimum stable nonzero thrust;
- command resolution;
- thrust-control accuracy;
- allowable deadband;
- response time;
- linearity;
- reverse-thrust magnitude; or
- detailed control-law behavior.

These parameters depend principally on motor-control and propulsor development.

SR-056 should therefore remain generalized until those parameters can be established without arbitrary assumptions.

**Recommended disposition: No immediate wording change; retain OI-001 and OI-017 traceability as applicable.**

---

### 11.6 SR-058 — Operating Limits

Current requirement intent:

**The RDT-80 shall operate within approved rotor-speed, torque, electrical-input, and thrust limits established through requirements, analysis, and test evidence.**

This analysis provides two important thrust-related inputs to the eventual operating envelope:

- continuous performance point: **7.0 kgf / 68.6 N**;
- peak performance point: **10.0 kgf / 98.1 N**.

However, SR-058 should not presently be rewritten to imply that these are the only or final thrust limits.

The approved operating envelope must also define:

- maximum authorized thrust;
- rotor-speed limits;
- torque limits;
- voltage limits;
- current limits;
- electrical-power limits;
- temperature limits;
- transient limits; and
- test-stage expansion criteria.

Those values remain dependent on OI-003 and OI-023 in addition to OI-001.

**Recommended disposition: No immediate wording change. Use the 7.0 kgf and 10.0 kgf points as inputs to ORD-017.**

---

### 11.7 SR-059 — Propulsive-Performance Criterion

Current requirement intent:

**The RDT-80 hydrodynamic design shall achieve an approved minimum propulsive-performance criterion under defined reference conditions.**

Static thrust magnitude alone does not constitute a complete propulsive-performance criterion.

The present analysis does not yet establish an approved requirement for:

- thrust per unit electrical power;
- propulsive efficiency;
- thrust coefficient;
- power coefficient;
- figure of merit;
- vehicle-level propulsive efficiency; or
- another equivalent performance metric.

Therefore, SR-059 shall not be rewritten using the 7.0 kgf or 10.0 kgf values as a substitute for a true performance-efficiency criterion.

That decision remains associated with ORD-018 and the hydrodynamic work supporting OI-002 and OI-015.

**Recommended disposition: No change.**

---

### 11.8 Related Requirements Not Directly Modified

The thrust-objective analysis also provides design inputs to several requirements without presently requiring their wording to change.

| Requirement | Effect of PT-AN-001 |
|---|---|
| SR-057 | 80–100 mm remains the current geometry-analysis range; final geometry remains controlled by OI-002 |
| SR-060 | Higher selected disk loading informs future cavitation analysis; no cavitation criterion established |
| SR-061 | Selected thrust levels define relevant operating points for future vibration analysis |
| SR-062 | Propulsor configuration must ultimately support verification of the selected 7.0/10.0 kgf performance points |
| SR-063 | Electromagnetic system must ultimately generate torque sufficient to achieve the selected thrust objective |
| SR-065 | Electrical, mechanical, and thermal operating limits must support the approved thrust operating points |
| SR-077 | Cooling-loss protection must be compatible with the thermal system required for continuous and peak operation |

No wording changes to these requirements are justified by the present analysis alone.

---

### 11.9 ORD-001 Disposition

ORD-001 currently requires establishment of the quantitative thrust/performance objective and associated acceptance criteria.

PT-AN-001 resolves the principal thrust-magnitude portion of this decision by recommending:

- **7.0 kgf / 68.6 N continuous forward static thrust**; and
- **10.0 kgf / 98.1 N peak forward static thrust**.

However, associated acceptance conditions remain incomplete.

Recommended ORD-001 disposition:

**Partially Resolved — quantitative thrust magnitudes established; final acceptance-condition closure pending.**

ORD-001 shall not be marked Closed until the remaining required acceptance basis is either resolved or formally transferred to controlled downstream decisions.

---

### 11.10 ORD-015 Disposition

ORD-015 covers:

- continuous thrust;
- peak thrust;
- peak-thrust duration;
- thrust-control range;
- reference conditions; and
- associated acceptance criteria.

The current resolution status is:

| ORD-015 Element | Status |
|---|---|
| Continuous thrust magnitude | Resolved by PT-AN-001 recommendation |
| Peak thrust magnitude | Resolved by PT-AN-001 recommendation |
| Peak duration | Open |
| Continuous verification duration | Open |
| Detailed controllable thrust range | Open |
| Quantitative reverse thrust | Open |
| Reference test-condition bounds | Partially defined |
| Measurement uncertainty criterion | Open |
| Final acceptance procedure | Open |

Recommended ORD-015 disposition:

**Partially Resolved — thrust magnitudes established; remaining verification and operating-condition parameters open.**

---

### 11.11 ORD-017 Impact

ORD-017 establishes approved:

- rotor-speed limits;
- torque limits;
- electrical-input limits;
- thrust limits; and
- operating-envelope expansion criteria.

PT-AN-001 provides the following required operating points as inputs:

| Operating Point | Thrust |
|---|---:|
| Continuous target | 7.0 kgf / 68.6 N |
| Peak target | 10.0 kgf / 98.1 N |

PT-AN-001 does not establish the maximum allowable thrust or the corresponding rotor-speed, torque, voltage, current, or electrical-power limits.

**ORD-017 remains Open.**

---

### 11.12 ORD-018 Impact

ORD-018 establishes the applicable:

- propulsive-performance metric;
- cavitation criterion;
- vibration limits; and
- reference hydrodynamic test conditions.

PT-AN-001 establishes thrust operating points that ORD-018 must address but does not establish those hydrodynamic acceptance limits.

**ORD-018 remains Open.**

---

### 11.13 OI-001 Status

OI-001 shall be considered:

**Open — Resolution in Progress**

The principal quantitative thrust decision is now technically supported:

**7.0 kgf continuous / 10.0 kgf peak forward static thrust.**

OI-001 shall not be closed until:

1. SR-054 and SR-055 have been updated through controlled requirements revision;
2. the remaining acceptance-condition dependencies have been resolved or formally transferred;
3. ORD-001 and ORD-015 have been appropriately dispositioned;
4. traceability has been updated; and
5. the resulting requirements changes have been reviewed for consistency with the approved architecture.

---

### 11.14 Required PT-REQ-001 Changes

The immediate controlled changes supported by PT-AN-001 are therefore limited to:

| Item | Action |
|---|---|
| SR-054 | Insert 7.0 kgf / 68.6 N continuous forward static-thrust requirement |
| SR-055 | Insert 10.0 kgf / 98.1 N peak forward static-thrust requirement |
| SR-001 | No change |
| SR-056 | No change yet |
| SR-058 | No change yet |
| SR-059 | No change yet |
| ORD-001 | Change from Open to Partially Resolved when PT-AN-001 recommendation is accepted |
| ORD-015 | Change from Open to Partially Resolved when PT-AN-001 recommendation is accepted |
| ORD-017 | Remain Open |
| ORD-018 | Remain Open |
| OI-001 | Remain Open — Resolution in Progress |

This limited-change approach avoids prematurely embedding unresolved thermal, electrical, control, geometry, cavitation, or verification assumptions into the system requirements.

---

## 12. Downstream Engineering Impact

### 12.1 Purpose

The recommended RDT-80 thrust objective establishes a principal system-level design input for subsequent engineering work.

The current recommended performance objective is:

- **7.0 kgf / 68.6 N minimum continuous forward static thrust**; and
- **10.0 kgf / 98.1 N minimum peak forward static thrust**.

These thrust values affect nearly every major subsystem.

However, the thrust objective alone is insufficient to begin detailed subsystem design because several coupled parameters remain unresolved.

The downstream engineering sequence shall therefore preserve the dependency relationships among:

- propulsor geometry;
- electrical power;
- rotor speed;
- torque;
- electromagnetic topology;
- rotor support;
- structural loading;
- thermal management;
- motor control;
- instrumentation; and
- verification.

---

### 12.2 Immediate Next Engineering Decisions

The first two downstream decisions following the thrust-objective analysis shall be:

1. **OI-002 — Principal Prototype Geometry**
2. **OI-003 — Operating Voltage and Power Range**

These decisions shall be developed in that order unless subsequent analysis demonstrates that an iterative treatment is required.

OI-002 must establish sufficient geometric definition to support meaningful hydrodynamic and electromagnetic sizing.

OI-003 must then establish a practical electrical operating envelope consistent with:

- the selected thrust objective;
- the selected geometry;
- estimated hydrodynamic power;
- estimated electromagnetic performance;
- available controller technology;
- practical prototype power sources; and
- thermal limitations.

OI-002 and OI-003 are strongly coupled and may require iteration before either is finally closed.

---

### 12.3 OI-002 — Principal Prototype Geometry

The thrust-objective analysis indicates that an approximately 80 mm propulsor remains credible but is not yet demonstrated to be optimal.

The present geometry-analysis range is:

**80–100 mm nominal propulsor diameter**

with the following principal comparison points:

| Nominal Diameter | Current Role |
|---|---|
| 80 mm | Baseline / closest architecture-comparable benchmark |
| 90 mm | Intermediate alternative with reduced disk loading |
| 100 mm | Larger alternative with substantially reduced disk loading |

OI-002 shall establish or bound, as applicable:

- propulsor diameter;
- central flow-passage diameter;
- rotor radial thickness;
- stator radial thickness;
- annular air-gap or wet-gap geometry;
- duct internal diameter;
- duct external diameter;
- axial rotor length;
- stator axial length;
- overall thruster length;
- rotor-to-duct clearances;
- principal mounting envelope; and
- configuration relationships among rotor, propulsor, stator, and duct.

The geometry decision shall evaluate both hydrodynamic and electromagnetic consequences.

A geometry shall not be selected solely to maximize hydrodynamic disk area if doing so creates disproportionate electromagnetic, structural, manufacturing, or packaging penalties.

---

### 12.4 Hydrodynamic Development Following OI-002

Once a preliminary geometry is established, hydrodynamic analysis shall progress beyond the ideal actuator-disk model.

The subsequent hydrodynamic work should establish, at minimum:

- candidate blade count;
- blade chord distribution;
- blade pitch or twist distribution;
- blade section selection;
- rotor/propulsor solidity;
- duct geometry;
- tip-clearance effects;
- estimated thrust coefficient;
- estimated torque coefficient;
- required rotational speed;
- required shaft-equivalent mechanical power;
- forward/reverse behavior;
- cavitation margin; and
- expected static-thrust performance.

The analysis should distinguish between:

- propulsor mechanical power;
- useful induced power;
- hydrodynamic losses; and
- total electrical input power.

This work will provide the first defensible estimate of the rotor torque and speed required to achieve the 7.0 kgf continuous and 10.0 kgf peak objectives.

---

### 12.5 Torque and Rotational-Speed Definition

Electromagnetic sizing requires a combination of required torque and rotational speed rather than thrust alone.

The basic mechanical relationship is:

**P_mechanical = τω**

where:

- **P_mechanical** = mechanical power delivered to the propulsor;
- **τ** = rotor torque; and
- **ω** = angular velocity.

Multiple torque/speed combinations may theoretically provide similar mechanical power.

The selected operating point must therefore also account for:

- propulsor hydrodynamic efficiency;
- cavitation;
- blade loading;
- electromagnetic torque density;
- winding frequency;
- magnetic losses;
- controller switching requirements;
- rotor structural loading;
- rotor-support losses; and
- noise/vibration behavior.

No final motor torque or speed requirement shall be selected until the hydrodynamic operating-point analysis provides an adequate basis.

---

### 12.6 OI-003 — Operating Voltage and Power Range

The present thrust analysis provides a preliminary planning basis of approximately:

- **0.6 kW continuous electrical input**; and
- **1.0 kW peak electrical input**

for Candidate B using the nominal preliminary system-effectiveness assumption.

A conservative preliminary component-screening level of approximately:

**1.2 kW peak electrical input**

may be used until better system-efficiency estimates are available.

These values are not yet approved requirements.

OI-003 shall ultimately establish:

- nominal DC bus voltage;
- allowable voltage range;
- continuous current capability;
- peak current capability;
- continuous electrical-input power;
- peak electrical-input power;
- transient power capability;
- conductor and connector ratings;
- controller input rating;
- protection thresholds;
- power-isolation requirements; and
- applicable design margins.

Voltage shall not be selected solely to match a convenient battery or controller.

The selected electrical architecture must be compatible with the required electromagnetic torque, conductor current density, winding design, insulation system, controller technology, and safe prototype testing.

---

### 12.7 Electromagnetic Development Sequence

After preliminary geometry, torque, speed, and electrical-envelope values are available, electromagnetic development may proceed with substantially reduced risk of premature optimization.

The principal electromagnetic work shall address:

- OI-004 — electromagnetic topology;
- OI-005 — stator and winding geometry;
- OI-006 — rotor magnetic circuit / magnetic-element arrangement;
- OI-007 — rotor electromagnetic-element retention; and
- related clearance, material, thermal, and manufacturing issues.

The electromagnetic design must demonstrate a credible path to producing the torque required by the hydrodynamic operating point while remaining within:

- voltage limits;
- current limits;
- magnetic saturation limits;
- winding-temperature limits;
- magnet-temperature limits;
- mechanical-retention limits; and
- manufacturing constraints.

Detailed winding turns, wire size, phase configuration, slot count, pole count, or magnet geometry shall not be treated as fixed until the operating-point requirements are sufficiently mature.

---

### 12.8 Rotor Support, Retention, and Structural Development

The selected thrust and torque objective will establish important mechanical loads for:

- OI-008 — radial support;
- OI-009 — axial support and thrust reaction;
- OI-010 — backup containment;
- OI-011 — operating clearance;
- OI-012 — materials and structural selection.

Mechanical development shall consider, as applicable:

- axial hydrodynamic thrust;
- electromagnetic radial forces;
- electromagnetic axial forces;
- rotor torque;
- rotor imbalance;
- gyroscopic or transient effects;
- rotor-support preload;
- rotor deformation;
- duct deformation;
- thermal expansion;
- manufacturing tolerances;
- impact or obstruction loads; and
- failure containment.

The 10.0 kgf peak point shall be included in structural and support-load analysis even if the 7.0 kgf condition governs continuous thermal operation.

---

### 12.9 Thermal Development

Thermal analysis shall follow once credible estimates exist for:

- winding loss;
- magnetic loss;
- controller loss;
- rotor-support loss;
- hydrodynamic loss;
- material thermal properties; and
- heat-transfer geometry.

The thermal work supporting OI-014 shall establish:

- continuous allowable electrical loading;
- peak allowable electrical loading;
- winding-temperature limits;
- magnet-temperature limits;
- controller-temperature limits;
- heat-rejection paths;
- cooling assumptions;
- temperature-sensing requirements;
- continuous verification duration;
- peak allowable duration;
- required cooldown or recovery behavior; and
- thermal protection thresholds.

This analysis is required before the final meaning of "continuous" and "peak" can be completely verified.

---

### 12.10 Motor-Control Development

Motor-control development under OI-017 shall use the established electrical and electromagnetic operating ranges to define:

- startup method;
- commutation method;
- rotor-position or sensorless strategy;
- current control;
- speed control;
- thrust-command relationship;
- forward/reverse behavior;
- command limits;
- acceleration limits;
- stall response;
- overspeed response;
- communications-loss response;
- fault recovery; and
- emergency shutdown behavior.

The controller shall support the approved operating-state requirements in SR-072 through SR-075 and the applicable protection requirements in SR-076 through SR-082.

Detailed controller selection should follow rather than precede definition of the required voltage, current, torque, speed, and commutation characteristics.

---

### 12.11 Instrumentation and Verification Impact

The selected thrust objective establishes minimum capability requirements for the future test system.

The test system shall ultimately be capable of measuring and recording, as applicable:

- thrust to at least the 10.0 kgf peak operating point with appropriate margin;
- electrical voltage;
- electrical current;
- electrical power;
- rotor speed;
- relevant temperatures;
- vibration;
- rotor displacement or clearance where required;
- control commands;
- operating state;
- protection events; and
- test duration.

Test-fixture structural capacity shall exceed the maximum authorized test load with appropriate engineering margin.

The load-measurement system shall have sufficient:

- range;
- accuracy;
- resolution;
- sampling rate; and
- calibration traceability

to distinguish meaningful performance differences among development configurations.

The verification implementation shall distinguish between the roles of OI-019 and OI-023.

**OI-019** shall govern the physical and measurement aspects of the performance-test implementation, including applicable test interfaces, fixture arrangement, instrumentation implementation, measurement configuration, and other test-setup characteristics necessary to obtain valid performance data.

**OI-023** shall govern the authorized test envelope and verification-control aspects, including approved operating conditions, test-stage limits, progression criteria, abort criteria, test authority, and other conditions controlling when and how the test may be conducted.

Where a verification condition depends on both the physical test implementation and the authorized operating envelope, traceability to both OI-019 and OI-023 shall be retained.

---

### 12.12 Configuration-Control Impact

The thrust objective creates a reference performance target but does not justify uncontrolled changes to geometry or subsystem design in pursuit of that target.

Changes affecting:

- propulsor diameter;
- blade geometry;
- duct geometry;
- rotor dimensions;
- stator dimensions;
- magnetic configuration;
- winding configuration;
- voltage;
- current;
- controller settings;
- materials; or
- manufacturing process

shall be documented sufficiently to preserve correlation between design configuration and measured performance.

Performance test results shall not be compared across configurations without identifying the relevant configuration differences.

---

### 12.13 Recommended Downstream Engineering Sequence

The recommended sequence following PT-AN-001 is:

| Sequence | Engineering Activity | Primary Controlled Issue / Output |
|---:|---|---|
| 1 | Establish principal prototype geometry | OI-002 |
| 2 | Develop preliminary hydrodynamic propulsor model | OI-015 / SR-062 |
| 3 | Establish required rotor speed, torque, and mechanical power | Derived hydrodynamic operating point |
| 4 | Establish preliminary electrical voltage/current/power envelope | OI-003 |
| 5 | Select and analyze electromagnetic topology | OI-004 |
| 6 | Develop stator/winding and rotor magnetic configuration | OI-005 / OI-006 |
| 7 | Develop electromagnetic-element retention concept | OI-007 |
| 8 | Develop radial and axial rotor-support architecture | OI-008 / OI-009 |
| 9 | Develop backup containment and clearance definition | OI-010 / OI-011 |
| 10 | Perform structural and material analysis | OI-012 |
| 11 | Develop environmental protection and corrosion approach | OI-013 |
| 12 | Perform thermal analysis and establish duty limits | OI-014 |
| 13 | Develop control, startup, fault, and protection strategy | OI-017 / OI-018 |
| 14 | Define instrumentation and controlled verification environment | OI-016 / OI-019 / OI-023 |
| 15 | Finalize manufacturing tolerances and processes | OI-020 |
| 16 | Conduct progressive prototype verification | Applicable SR / VM activities |

This sequence is not strictly linear.

Iteration is expected, particularly among:

- geometry;
- hydrodynamics;
- torque/speed;
- electromagnetic design;
- electrical power;
- structural design; and
- thermal management.

However, major downstream design commitments should not be made before their upstream sizing inputs are sufficiently mature.

---

### 12.14 Immediate Project Direction

Completion of PT-AN-001 establishes sufficient basis to proceed next to:

**OI-002 — Principal Prototype Geometry**

The immediate geometry analysis should compare, at minimum:

- 80 mm;
- 90 mm; and
- 100 mm

nominal propulsor diameters using the recommended:

**7.0 kgf continuous / 10.0 kgf peak**

performance objective.

The purpose of that work will not be to maximize diameter.

It will identify the geometry that provides the best overall balance among:

- hydrodynamic loading;
- electromagnetic packaging;
- rotor circumference;
- structural size;
- manufacturing practicality;
- overall thruster envelope;
- prototype cost; and
- testability.

Detailed CAD geometry shall follow the engineering selection rather than drive it.

---

## 13. Conclusion

### 13.1 Analysis Conclusion

PT-AN-001 evaluated the initial RDT-80 thrust objective using:

- Project Triton mission and development constraints;
- architecture-comparable rim-driven thruster benchmarks;
- general underwater-propulsor benchmarks;
- ideal actuator-disk momentum theory;
- preliminary real-system electrical-power estimates;
- propulsor-diameter sensitivity analysis; and
- comparative engineering trade evaluation.

Three candidate performance levels were considered:

| Candidate | Continuous Forward Static Thrust | Peak Forward Static Thrust | Disposition |
|---|---:|---:|---|
| Candidate A | 5 kgf / approximately 49 N | 7 kgf / approximately 69 N | Minimum meaningful development level / fallback |
| Candidate B | 7 kgf / approximately 68.6 N | 10 kgf / approximately 98.1 N | Recommended initial RDT-80 objective |
| Candidate C | 10 kgf / approximately 98.1 N | 15 kgf / approximately 147 N | Stretch / later-development objective |

The analysis identifies Candidate B as providing the best current balance among:

- technical usefulness;
- rim-drive benchmark credibility;
- hydrodynamic feasibility;
- electrical-power practicality;
- electromagnetic development challenge;
- structural and rotor-support feasibility;
- thermal feasibility;
- manufacturability;
- controlled testability;
- performance differentiation; and
- overall development risk.

Accordingly, the recommended initial RDT-80 thrust objective is:

**7.0 kgf / 68.6 N minimum continuous forward static thrust**

and:

**10.0 kgf / 98.1 N minimum peak forward static thrust**

under subsequently approved reference and operating conditions.

---

### 13.2 Engineering Significance

The selected objective is intentionally more demanding than a minimum proof-of-concept demonstration.

The 7.0 kgf continuous target requires the RDT-80 to sustain a thrust level approximately corresponding to the maximum published performance of the closest architecture-comparable 80 mm rim-driven benchmark.

The 10.0 kgf peak target provides a meaningful additional performance objective while remaining below the substantially higher electrical-power regime represented by aggressive commercial rim-drive systems.

First-order momentum theory does not identify a fundamental hydrodynamic-power barrier to either selected thrust level at approximately 80 mm propulsor diameter.

The current preliminary electrical planning basis is approximately:

- **0.6 kW continuous electrical input** at the 7.0 kgf operating point; and
- **1.0 kW peak electrical input** at the 10.0 kgf operating point,

with approximately **1.2 kW peak capability** retained as a conservative component-screening basis until improved hydrodynamic and electromagnetic estimates are available.

These values are planning estimates and are not approved electrical requirements.

---

### 13.3 Geometry Finding

The analysis does not demonstrate that exactly 80 mm is the optimal propulsor diameter.

The present geometry-analysis range is:

**80–100 mm**

with:

- 80 mm retained as the reference case;
- 90 mm retained as an intermediate alternative; and
- 100 mm retained as a lower-disk-loading alternative.

The designation **RDT-80** shall not, by itself, be treated as a requirement that permanently fixes the final propulsor diameter at exactly 80 mm.

Final geometry remains controlled by OI-002.

---

### 13.4 Requirement Recommendation

PT-AN-001 provides sufficient technical basis to recommend quantitative revision of:

**SR-054**

to require:

**not less than 7.0 kgf (68.6 N) continuous forward static thrust**

and:

**SR-055**

to require:

**not less than 10.0 kgf (98.1 N) peak forward static thrust for the approved peak operating duration.**

No immediate quantitative change is recommended to SR-056, SR-058, or SR-059 because the associated:

- control characteristics;
- operating-envelope limits;
- efficiency/performance metrics;
- cavitation criteria;
- reverse-thrust requirements; and
- verification conditions

remain unresolved.

---

### 13.5 Remaining OI-001 Dependencies

OI-001 is not yet fully closed.

The principal thrust magnitudes are technically supported, but the following acceptance conditions remain open or require formal transfer to downstream controlled decisions:

- continuous verification duration;
- peak allowable duration;
- quantitative reverse-thrust objective;
- minimum stable nonzero thrust;
- thrust-command resolution and accuracy;
- environmental verification bounds;
- measurement uncertainty criterion; and
- final verification procedure.

Therefore:

**OI-001 Status: Open — Resolution in Progress**

ORD-001 and ORD-015 should likewise be treated as:

**Partially Resolved**

once the recommendations in PT-AN-001 are formally accepted and incorporated into the controlled requirements set.

---

### 13.6 Next Engineering Activity

The next principal engineering activity shall address:

**OI-002 — Principal Prototype Geometry**

using:

**7.0 kgf continuous / 10.0 kgf peak forward static thrust**

as the reference performance objective.

The geometry analysis shall compare at least:

- 80 mm;
- 90 mm; and
- 100 mm

nominal propulsor diameters and evaluate their effects on:

- disk loading;
- hydrodynamic power;
- propulsor design;
- electromagnetic packaging;
- rotor dimensions;
- stator dimensions;
- structural size;
- manufacturing practicality;
- overall thruster envelope; and
- testability.

Following preliminary geometry selection, hydrodynamic analysis shall establish the rotor speed, torque, and mechanical-power operating points required for subsequent OI-003 electrical-envelope and electromagnetic design work.

---

### 13.7 Final Statement

PT-AN-001 establishes a technically defensible initial performance direction for the Project Triton RDT-80 without prematurely fixing unresolved geometry, electrical, electromagnetic, thermal, control, or verification parameters.

The recommended thrust objective is:

> **7.0 kgf continuous / 10.0 kgf peak forward static thrust**

with:

> **5.0 kgf retained as the minimum meaningful integrated development milestone**

and:

> **performance above 10.0 kgf retained as stretch capability unless separately analyzed and approved.**

This recommendation provides the performance basis required to advance Project Triton from system-level requirements development into principal prototype sizing.