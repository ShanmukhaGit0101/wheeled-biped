# Height-Adaptive Wheeled-Biped Robot

> **Design, Dynamics and Intelligent Control of a Height-Adaptive Wheeled-Biped Robot for Terrain Adaptability**

A robotics research and development project focused on combining the efficiency of wheeled locomotion with the terrain adaptability of articulated legs. The platform explores active body-height adjustment, wheel–leg coordination, dynamic stability, and intelligent locomotion.

---

## 1. Project Overview

Wheeled robots offer efficient mobility on relatively smooth surfaces, while legged mechanisms provide greater adaptability when negotiating uneven terrain and obstacles.

This project explores a wheeled-biped architecture that combines both capabilities. Wheels provide the primary means of mobility, while articulated legs enable active body-height adjustment and adaptation to changing terrain conditions.

The research focuses on the mechanical design, drivetrain architecture, coupled dynamics, and control strategies required to achieve stable and adaptive locomotion.

**Note:** The robot is currently under development. Specific mechanisms, component selections, dimensions, and control methods will be documented as they are evaluated and finalized.

## 2. Project Objectives

- Develop a mechanically practical wheeled-biped morphology with active height adaptability.
- Investigate leg mechanisms and wheel-drive transmission architectures.
- Model the coupled dynamics of the wheels, articulated legs, and robot body.
- Develop control strategies for balance, height regulation, and coordinated locomotion.
- Explore terrain adaptation and obstacle traversal through simulation and experiments.
- Investigate structural optimization and lightweight mechanical design.

## 3. System Overview

The proposed platform consists of the following major subsystems:

| Subsystem | Function |
|---|---|
| Wheeled Mobility | Efficient movement across traversable surfaces |
| Articulated Legs | Active body-height adjustment and terrain adaptation |
| Mechanical Structure | Structural support and actuator load transmission |
| Drivetrain | Torque transmission to wheels and joints |
| Sensing | Robot state estimation and environmental feedback |
| Control System | Coordination of wheel motion, leg configuration, and stability |

The exact degrees of freedom, actuator arrangement, transmission architecture, and sensor configuration will be established through the design process.

## 4. Research and Development Areas

### Bin 1 — Robot Morphology & Mechanical Design

- Wheeled-biped configurations and kinematic architecture
- Leg geometry, linkage design, and workspace analysis
- Structural design and lightweighting
- Active height-adjustment mechanisms
- Design for manufacturing and assembly

### Bin 2 — Actuation, Drivetrain & Transmission

- Actuator selection and sizing
- Wheel-drive architecture
- Belt, gear, and alternative transmission mechanisms
- Torque, speed, efficiency, and backlash analysis
- Mechanical integration and packaging

### Bin 3 — Dynamics, Balance & Control

- Wheel–leg–body dynamic modelling
- Stability and balance analysis
- Independent and coordinated joint control
- Height and posture regulation
- Adaptive and impedance-based control approaches

### Bin 4 — Locomotion, Terrain Adaptation & Intelligent Control

- Coordinated wheel–leg locomotion
- Obstacle traversal and terrain adaptation
- Motion planning and trajectory generation
- Reinforcement-learning-based locomotion
- Simulation-to-hardware validation

## 5. Development Workflow

The project follows an iterative engineering workflow:

1. **Literature Review** — Study existing morphologies, mechanical mechanisms, dynamic models, and control approaches.
2. **Concept Development** — Compare candidate architectures against functional and manufacturing requirements.
3. **Mechanical Design** — Develop CAD models, evaluate structural loads, and refine the drivetrain.
4. **Modelling & Simulation** — Formulate kinematics and dynamics and validate the proposed design.
5. **Control Development** — Implement and evaluate balance, height-regulation, and locomotion controllers.
6. **Prototype Integration** — Integrate mechanical, electrical, sensing, and computational subsystems.
7. **Testing & Evaluation** — Measure performance, document limitations, and iterate on the design.

## 6. Repository Structure

The repository serves as the shared technical record for the project.

```text
wheeled-biped/
│
├── README.md
├── LICENSE
├── .gitignore
├── project_rules.md
│
├── docs/
│   ├── project_decisions.md
│   ├── progress.md
│   └── meeting_minutes.md
│
├── research/
│   └── literature-survey/
│
└── engineering-subsystems/
    ├── mechanical/
    ├── drivetrain/
    ├── modelling/
    ├── simulation/
    ├── electronics/
    └── control/
```

*The engineering directory structure is illustrative and will evolve as implementation progresses.*

## 7. Project Status

**Current Stage: Research, Concept Evaluation & Preliminary System Design**

| Work Area | Status |
|---|---|
| Project Scope and Objectives | Defined |
| Literature Review | In Progress |
| Robot Morphology | Under Evaluation |
| Leg Mechanism and Drivetrain | Under Evaluation |
| Kinematic and Dynamic Modelling | Planned |
| Simulation Model | Planned |
| Control Architecture | Under Research |
| Prototype Fabrication | Planned |
| Experimental Validation | Planned |

Project statuses will be updated as work progresses and technical evidence becomes available.

## 8. Engineering Principles

- Distinguish between proposed, under-review, and approved design decisions.
- Record significant technical decisions and their rationale.
- Support engineering claims with calculations, simulation results, drawings, or experimental evidence.
- Document assumptions, parameters, units, and limitations.
- Prioritize modularity, manufacturability, maintainability, and safe testing.

For repository conventions and collaboration guidelines, refer to [project_rules.md](project_rules.md).

## 9. Team Contributions

This is a collaborative engineering project involving research and development across:

- Literature Review
- Mechanical Design
- Drivetrain Development
- Kinematic and Dynamic Modelling
- Simulation
- Electronics and Sensing
- Control Systems
- Intelligent Locomotion

All contributions should follow the repository's Git workflow and documentation guidelines.

## 10. License

This project is intended to be distributed under the MIT License. Refer to [LICENSE](LICENSE) for licensing details.

---

*This README represents the project's current research direction and development plan. It will evolve as design decisions are finalized and implementation results become available.*
