# Project Rules

## 1. Working principles
- Treat this repository as the shared technical record for the Wheeled Biped project.
- Separate **proposed**, **under review**, and **approved** decisions. Do not present an unapproved concept as final.
- Record important technical decisions and their rationale in `docs/project_decisions.md`.
- Prefer measured results, calculations, drawings, simulation evidence, and test data over unsupported claims.
- Raise risks and blockers early; do not silently change another member's design or code.

## 2. Git workflow
- `main`: stable, reviewed material suitable for project reviews.
- `dev`: integration branch for ongoing work.
- Use short-lived feature branches for substantial work, e.g. `mechanical/leg-concept`, `simulation/urdf-model`, `control/balance-controller`.
- Avoid committing unfinished or unverified work directly to `main`.
- Use clear commit messages such as `docs: add literature survey matrix` or `sim: add initial robot model`.
- Open a pull request into `dev) for significant changes; request at least one teammate review.
- Pull the latest target branch before starting or merging work. Resolve conflicts carefully.

## 3. Documentation and file conventions
- Use lowercase file and folder names; use hyphens where needed.
- Keep the repository root limited to essential project files.
- Put project documentation in `docs/`, research material in `research/`, and engineering work in its relevant subsystem folder.
- Give every drawing, plot, dataset, and experiment a descriptive name and record units, assumptions, and revision where relevant.
- Keep source files and reproducible scripts. Do not commit temporary exports, cache folders, build outputs, or duplicate files.
- Do not commit large videos, raw datasets, or generated simulation recordings without team agreement. Consider Git LFS for large CAD or binary assets.

## 4. Engineering deliverable standard
Where applicable, a technical contribution should include:
1. Purpose and scope.
2. Design assumptions and requirements.
3. Equations, parameters, units, and references.
4. CAD/model/source files.
5. Verification method and results.
6. Known limitations and next steps.

## 5. Team coordination
- Update `docs/progress.md` before the weekly Friday faculty update.
- Record meeting decisions, action owners, and due dates in `docs/meeting_minutes.md`.
- A task is complete only when its deliverable or evidence is linked or committed.
- Discuss major scope, cost, safety, or architecture changes with the team before proceeding.

## 6. Safety and review
- Check structural integrity, electrical ratings, actuator limits, pinch points, and emergency-stop behavior before powered testing.
- Test subsystems at low speed and with the robot safely supported before full operation.
- Do not run an autonomous test without a defined stop procedure and a clear test area.

---
These rules are the initial working agreement and may be revised by the team.
