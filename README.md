#  QAtlas

<div align="center ">

[![Documentation](https://img.shields.io/badge/Documentation-Markdown-blue)](https://www.markdownguide.org/)
[![Version](https://img.shields.io/badge/Version-1.0.0-green)](https://semver.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

**Single Source of Truth for Test Documentation Across All Projects**

</div>

##  Purpose

This repository serves as the **central hub** for all test documentation, providing:

- **Standardized test governance** across the organization
- **Project level test visibility** and transparency  
- **Automation coverage insights** 
- **Clear ownership** and accountability
- **Living documentation** that evolves with your systems

### What This Repository Is

- **Documentation-only** - No executable code
- **Trunk-based development** workflow
- **Markdown-first** documentation standard
- **Maintained by QA teams**

---

##  Repository Structure

```
QAtlas/
├── 📂 governance/          # Global testing principles and rules
│   ├── 📄 test_strategy.md
│   ├── 📄 ownership_model.md
│   └── 📄 how_to_use_templates.md
├── 📂 projects/           # Project documentation and templates
│   ├── 📂 templates/       # Reusable project templates
│   │   └── 📂 project_template/
│   │       ├── 📄 README.md
│   │       ├── 📄 api_tests.md
│   │       ├── 📄 integration_tests.md
│   │       ├── 📄 regression_tests.md
│   │       └── 📄 ...
│   └── 📂 [your-project]/  # Individual project folders
```

---

## Core Principles

- **Small, modular documentation files** - Easy to maintain and review
- **Explicit ownership** - Clear accountability for each area
- **Continuous updates via trunk** - Documentation evolves directly in main branch
- **No outdated documentation tolerated** - Keep it fresh or remove it
- **Documentation evolves with the system** - Living documents

---

##  Trunk-Based Development

###  Direct to Main Branch

QAtlas follows **trunk-based development** - all changes are committed directly to the main branch:

- **No feature branches** - Work directly in main
- **Small, frequent commits** - Reduce merge conflicts
- **Documentation updates** - Commit changes as they happen
- **Shared QA responsibility** - Everyone maintains documentation quality

###  Commit Guidelines

- **Descriptive messages** - Clear commit history
- **Consistent formatting** - Follow established patterns
- **Review before commit** - Ensure accuracy and completeness
- **Update immediately** - Don't let documentation lag

---

##  QA Contribution Model

Any feature that introduces the following **MUST** be updated by **QA teams** in the documentation:

- **New flow** or user journey
- **New endpoint** or API change
- **Automation addition or removal**
- **Integration behavior changes**

---

##  Getting Started

1. **Read the [Test Strategy](governance/test_strategy.md)**
2. **Understand the [QA Ownership Model](governance/ownership_model.md)**
3. **Use [Project Templates](projects/templates/project_template/)** for new projects
4. **Follow [Template Guidelines](governance/how_to_use_templates.md)**

---

<div align="center">

Quality is not an act, it is a habit.

</div>