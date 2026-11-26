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

## File placement rules
- Keep only essential entry-point files at the root.
- Store source data with a README explaining its origin, format, and use.
- Avoid committing generated build folders, temporary files, duplicate exports, and large recordings.
- Use Git LFS for large binary assets only after the team agrees on file types and storage needs.
- Update this tree when the actual repository structure changes.
