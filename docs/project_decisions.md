# Project Decisions

This file is the authoritative record of technical choices. Keep unresolved items marked **TBD** until the team agrees. Record the date, decision, alternatives, rationale, and owner for every important freeze.

## 1. Project definition

| Item | Current status | Notes |
|---|---|---|
| Project name | Wheeled Biped | Working title |
| Main objective | Under discussion | Wheeled locomotion with articulated height adaptation and dynamic balance |
| Primary research contribution | TBD | To emerge from the literature gap analysis |
| Demonstration scenario | TBD | Define measurable terrain/obstacle and balancing tasks |
| Final prototype scope | TBD | Must fit the budget, facilities, and semester timeline |

## 2. Architecture decisions

| Decision | Options to evaluate | Status | Rationale / evidence |
|---|---|---|---|
| Overall morphology | Two-wheel platform with articulated legs; alternatives from survey | TBD | |
| Wheel arrangement and drive | Differential / other feasible arrangement | TBD | |
| Leg DOF and joint layout | Hip-knee arrangement / alternatives | TBD | |
| Leg linkage or topology | Direct link / linkage / other manufacturable mechanism | TBD | |
| Height adaptation method | Joint coordination / variable geometry / other | TBD | |
| Drivetrain | Direct drive / belt / gear / other | TBD | |
| Actuators | DC geared motor / BLDC / servo / other | TBD | |
| Sensors | IMU, encoders, distance/vision sensors as needed | TBD | |
| Main controller | TBD | TBD | |
| Power system | TBD | TBD | |
| Materials and fabrication | 3D print, machining, sheet/plate, welding as appropriate | TBD | |

## 3. Modelling, simulation and control

| Decision | Current direction | Status |
|---|---|---|
| Simulation stack | ROS 2 Humble + Gazebo | Planned; exact Gazebo distribution TBD |
| Robot description | URDF/Xacro, subject to final architecture | TBD |
| Dynamics model | Derive from frozen mechanical design | TBD |
| Baseline controller | Classical control to be established first | TBD |
| Advanced control | Adaptive / impedance / other, selected after baseline | TBD |
| Reinforcement learning | Simulation exploration only unless time and evidence justify more | Optional / TBD |
| Hardware-simulation validation | Define common metrics and scenarios | TBD |

## 4. Constraints

| Constraint | Current value / status |
|---|---|
| Project budget | Below ₹10,000 |
| Team size | 4 |
| Fabrication access | 3D printing, CNC machining, lathe/milling, welding |
| Review 1 | 18 December 2026 |
| Design completion target | 31 December 2026 |
| Manufacturing window | 1–31 January 2027 |
| Assembly/integration window | 1–11 February 2027 |
| Review 2 | 12 February 2027 |
| Final demonstration | Mid-March 2027 |

## 5. Decision log

| Date | Decision / question | Outcome | Rationale / evidence | Owner |
|---|---|---|---|---|
| 27 Nov 2026 | Architecture and project scope meeting | Pending | Record after meeting | Team |

## 6. Freeze checklist
- [ ] Demonstration objective and measurable success criteria
- [ ] Mechanical architecture and DOF
- [ ] Leg mechanism and height-adjustment method
- [ ] Wheel and drivetrain arrangement
- [ ] Actuator and sensor selection
- [ ] Controller and power architecture
- [ ] Preliminary dimensions and mass budget
- [ ] Costed BOM and sourcing plan
- [ ] Simulation model scope
- [ ] Safety and emergency-stop plan

Do not tick an item until the decision is documented and accepted by the team.
