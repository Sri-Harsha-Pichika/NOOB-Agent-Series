# NOOB Agents Series
Meta‑level prompt engineering agents designed to transform user input into high‑performance prompts and direct analyses.  
This repository contains the **NOOB agent family**: **NOOB**, **NOOB++**, **NOOB‑Ω**, and **NOOB‑HYBRID**.

-----

## Overview
The NOOB agents act as **navigation systems** for AI models.  
Where public AIs are the “engine” that generates outputs, NOOB agents design optimized prompts and workflows that tell the engine exactly how to drive.

Each agent embodies a distinct philosophy:

- **NOOB** → The starting version. Simple, foundational, and experimental.  
- **NOOB++** → Transparent, verbose, reasoning‑heavy.  
- **NOOB‑Ω** → Fast, concise, hidden reasoning, production‑ready.  
- **NOOB‑HYBRID** → Fusion of both: concise public output + optional developer transparency.

-----

## Agent Comparison

| Agent           | Role / Persona        |                     Strengths                               |                Best Use Cases                        |
|-----------------|-----------------------|-------------------------------------------------------------|------------------------------------------------------|
| **NOOB**        | Prototype / Starter   | Simple, experimental, baseline agent                        | Early testing, proof‑of‑concept                      |
| **NOOB++**      | Professor             | Transparent scaffolding, reasoning chains, self‑critique    | Training, pedagogy, audits, research                 |
| **NOOB‑Ω**      | Executive Assistant   | Concise, production‑ready, hidden CoT, direct analysis      | Fast‑paced enterprise workflows, executive briefings |
| **NOOB‑HYBRID** | Bridge                | Concise outputs + optional transparency, adaptive verbosity | Mixed teams, debugging, governance                   |

-----

## Features
- **Model‑agnostic prompts**: Work with any AI engine.  
- **Domain packs**: Technical, Creative, Scientific, Business, UX.  
- **Meta‑Reasoning Units (MRUs)**: Logic, Constraints, Verification, Safety, Structure, Optimisation.  
- **Chain of Verification (CoVe)**: Micro (facts), Meso (intent), Macro (structure).  
- **Web intelligence**: NOOB‑Ω and NOOB‑HYBRID can surf the web and analyse directly.  
- **Modes**: Basic, Detail, Developer (HYBRID), Adaptive (++) depending on agent.  
- **Governance hooks**: Evidence citation, compliance checks, audit trails.  
- **Transparency options**: Verbose reasoning (++) or optional developer mode (HYBRID).  

-----

## Repository Structure
```plaintext
noob-agents/
├── [agents](agents/)                         # Definitions for NOOB, NOOB++, NOOB‑Ω, NOOB‑HYBRID
│   ├── NOOB.md
│   ├── NOOB++.md
│   ├── NOOB-OMEGA.md
│   └── NOOB-HYBRID.md
├── [docs](docs/)                             # Knowledge Base Article (KBA), usage guides
│   └── KBA.md
├── [examples](examples/)                     # Sample prompts and outputs
│   ├── cybersecurity-analysis.md
│   ├── creative-writing.md
│   └── business-report.md
├── [workflow-diagrams](workflow-diagrams/)   # Workflow diagrams (draw.io exports)
│   ├── noob-workflows.png
│   └── verification-layer.png
├── [README.md](README.md)                    # This file
├── [LICENSE](LICENSE)                        # Apache 2.0 license
├── [CONTRIBUTING.md](CONTRIBUTING.md)        # Contribution guidelines
├── [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)  # Community standards
├── [SECURITY.md](SECURITY.md)                # Security policy
└── [CHANGELOG.md](CHANGELOG.md)              # Version history

## Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/Sri-Harsha-Pichika/NOOB-Agents-Series.git
   cd NOOB-Agent-Series
2. agents/                                                      # Explore the agents in agents/
3. docs/KBA.md                                                  # Review the Knowledge Base       
4. examples/                                                    # Try example prompts 

## Examples
NOOB: Baseline agent for simple prompt generation.
NOOB++: Generates a multi‑section cybersecurity report prompt with reasoning and critique.
NOOB‑Ω: Produces a concise executive summary with one mitigation and “Why this works.”
NOOB‑HYBRID: Outputs concise findings, with optional reasoning in Developer Mode.

See the examples/ folder for full samples.

## Documentation
Full Knowledge Base: docs/KBA.md
Workflow diagrams: charts/

## Contributing
We welcome contributions from the community! Please see CONTRIBUTING.md for guidelines, including:
Branching strategy (feature/..., fix/..., release/...).
Commit message conventions (Conventional Commits).
Pull request process and review checklist.
We follow the We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/).

## Security
If you discover a vulnerability, please see SECURITY.md for responsible disclosure guidelines. Do not open public issues for sensitive security problems.

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Final Takeaway
NOOB is the prototype (Still works wonders).
NOOB++ is the professor.
NOOB‑Ω is the executive assistant.
NOOB‑HYBRID is the bridge (Between NOOB++ & NOOB-Ω).

Together, they form a complete toolkit for training, production, and governance in AI workflows.