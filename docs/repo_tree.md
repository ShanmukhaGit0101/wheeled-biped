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

Member	Literature task	Software / learning task	Component task
Shanmukha	Read Bin 3 papers; start Bin 4	Set up ROS 2 workspace, understand nodes, topics, TF and URDF/Xacro	Identify electrical architecture, battery and controller options
Rakesh	Read Bin 1 papers; start Bin 2	Install CAD/FEA tools; learn assembly modelling, joints, materials and exporting CAD models	Explore chassis, leg configurations, structural materials and joint hardware
Surya	Read Bin 2 papers; start Bin 3	Learn motor specifications, encoder feedback, PWM and basic motor control	Identify wheel motors, hip/knee actuators and transmission alternatives
Umaa	Read Bin 4 papers; start Bin 1	Set up ROS 2 Python environment, RViz2 and Gazebo; learn sensor topics and simulation basics	Identify IMU, encoders, limit switches and obstacle-detection sensor options
