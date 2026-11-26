# Project Roadmap

**Target final review/demo:** Mid-March 2027  
**Planning principle:** Mechanical/hardware development and simulation/control development should progress in parallel and converge during integration.

## 1. Milestones

| Period | Phase | Main activities | Deliverables / exit criteria |
|---|---|---|---|
| 26 Nov 2026 | Project setup | Create repository, collect papers, prepare team skill matrix | Repository structure; paper list; team inputs requested |
| 27 Nov–4 Dec | Literature survey | Read and compare prior work; identify feasible architectures and research gaps | Completed literature matrix; survey summary; candidate directions |
| 27 Nov | Team decision meeting | Discuss objectives, constraints, architecture candidates, and decision criteria | Meeting minutes; unresolved questions and owners |
| 5–7 Dec | Concept selection | Compare concepts against cost, manufacturability, controllability, and research value | Selected concept and documented rationale |
| 8–18 Dec | Detailed design + simulation foundation | CAD layout, preliminary calculations, actuator sizing, initial robot model | Review 1 package: detailed design, preliminary BOM, assumptions, initial simulation plan |
| 19–31 Dec | Design validation | Refine CAD, check loads/clearances, verify actuator and component choices, finalize BOM | Design freeze target: 31 Dec |
| 1–31 Jan 2027 | Manufacturing + subsystem development | Fabricate parts; develop electronics, firmware, simulation model, and baseline controllers in parallel | Fabricated subsystems; test records; working simulation |
| 1–11 Feb | Assembly and integration | Assemble, wire, calibrate, integrate controller and sensors; commission safely | Integrated robot ready for Review 2 |
| 12 Feb | Review 2 | Demonstrate assembled robot and report current performance | Review 2 evidence and action list |
| 13 Feb–mid-March | Control refinement and validation | Tune baseline control; evaluate height adaptation and obstacle tasks; advanced control/RL only if feasible | Experimental results, comparison plots, final demo and report |

## 2. Parallel workstreams

### Mechanical and hardware
- Architecture and requirements
- Mechanism and drivetrain design
- Structural and actuator calculations
- CAD, drawings, and BOM
- Manufacturing, assembly, wiring, and calibration

### Simulation and control
- Robot model and coordinate frames
- Physics/simulation setup
- Kinematics and dynamics
- Baseline balancing and wheel/leg coordination
- Test scenarios and measurable performance metrics
- Controller refinement and hardware-simulation comparison

### Research and documentation
- Literature matrix and gap analysis
- Decision records and design justification
- Weekly progress evidence
- Test reports, plots, and final presentation

## 3. Weekly cadence
- **Friday:** Update progress and prepare the faculty update.
- **Team meeting:** Review blockers, interfaces, upcoming tasks, and decisions.
- **After each milestone:** Record what was achieved, what changed, and the next actions.

## 4. Schedule risks
- Freeze the mechanical architecture early enough to protect the manufacturing window.
- Check component lead times before the design freeze.
- Keep a simple baseline controller as the minimum viable control deliverable.
- Treat advanced adaptive control or reinforcement learning as stretch work until the core robot is assembled and stable.
- Reserve time after assembly for debugging; do not schedule the final demo immediately after first power-on.

## 5. Status
This is the initial target plan. Update dates and owners after the team meeting. Actual progress belongs in `docs/progress.md`; approved technical choices belong in `docs/project_decisions.md`.
