# Repository Structure

This document describes the intended organisation of the Wheeled Biped repository. Create engineering folders when their work begins; avoid empty folders and unnecessary documentation.

```text
wheeled-biped/
├── README.md
├── LICENSE
├── .gitignore
├── project_rules.md
├── docs/
│   ├── project_decisions.md
│   ├── team_strengths.md
│   ├── roadmap.md
│   ├── progress.md
│   ├── meeting_minutes.md
│   └── repo_tree.md
├── research/
│   └── literature_survey.md
├── mechanical/
├── electronics/
├── simulation/
├── control/
├── experiments/
├── project_management/
└── .github/
    └── ISSUE_TEMPLATE/
```

## Directory responsibilities

| Path | Purpose |
|---|---|
| `README.md` | Short project introduction, objectives, team, milestones, and navigation |
| `project_rules.md` | Collaboration, Git, documentation, and engineering standards |
| `docs/` | Decisions, team skills, roadmap, progress, meeting records, and repository guide |
| `research/` | Literature survey, paper notes, research gap, and references |
| `mechanical/` | CAD, drawings, mechanism design, calculations, and structural analysis |
| `electronics/` | Electrical architecture, schematics, wiring, PCB, firmware interfaces, and component datasheets |
| `simulation/` | Robot description, worlds, simulation launch files, and simulation-specific documentation |
| `control/` | Control models, algorithms, implementation, and tuning records |
| `experiments/` | Test procedures, raw/processed results, plots, and validation reports |
| `project_management/` | Optional detailed schedules, procurement tracking, and risk records if needed |
| `.github/ISSUE_TEMPLATE/` | Reusable issue templates for bugs, tasks, and design reviews |

## 1. Team task allocation

| Member | Assigned Role | Literature Review | Software / Learning Tasks | Component Selection & BOM Ownership | Week 1 Deliverables (27–30 Nov) | Week 2 Deliverables (1–4 Dec) |
|---|---|---|---|---|---|---|
| **Shanmukha** | System Integration, Electronics & Control Lead | Bin 3 – Dynamics, Balance & Control; Bin 4 – Locomotion, Terrain Adaptation & Intelligent Control | Install ROS 2 Humble; learn ROS 2 nodes, topics, TF, URDF/Xacro and basic robot visualisation in RViz2 | Battery, BMS, motor drivers, voltage regulators, microcontroller, onboard computer, power distribution and wiring | Read Bin 3 papers; identify electronics and power-system options; prepare preliminary electrical architecture | Complete Bin 4 review; calculate power budget, peak/continuous current, battery capacity and runtime; shortlist electronics |
| **Rakesh** | Mechanical Design & Fabrication Lead | Bin 1 – Robot Morphology & Mechanical Design; Bin 2 – Actuation, Drivetrain & Transmission | Set up CAD/FEA tools; learn assembly modelling, joints, material selection and CAD export | Chassis, leg links, hip/knee joint structures, wheel mounts, bearings, shafts, brackets, fasteners and structural materials | Read Bin 1 papers; explore robot morphologies, leg mechanisms, chassis and material options | Complete Bin 2 review; prepare preliminary dimensions, mass estimate, structural-load calculations and mechanical BOM |
| **Surya** | Actuation, Drivetrain & Engineering Validation Lead | Bin 2 – Actuation, Drivetrain & Transmission; Bin 3 – Dynamics, Balance & Control | Learn motor specifications, encoder feedback, PWM, motor drivers and basic motor-control concepts | Wheel motors, hip/knee actuators, gearboxes, belt drives, pulleys, couplings, wheel hubs and transmission components | Read Bin 2 papers; identify motor and drivetrain alternatives; collect datasheets and specifications | Complete Bin 3 review; calculate wheel torque, RPM, power, joint torque, gear ratios and shortlist actuators |
| **Umaa** | Sensors, Simulation & Research Documentation Lead | Bin 4 – Locomotion, Terrain Adaptation & Intelligent Control; Bin 1 – Robot Morphology & Mechanical Design | Set up Python environment, Gazebo, RViz2; learn sensor topics, basic simulation and sensor integration in ROS 2 | IMU, wheel encoders, joint-position sensors, limit switches, obstacle/distance sensors and optional camera/depth sensor | Read Bin 4 papers; identify sensor options, specifications and interfaces | Complete Bin 1 review; compare sensors, determine sensor placement, update sensor BOM and prepare simulation requirements |

