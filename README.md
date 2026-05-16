# GSoC 2026 Python Software Foundation: Vorta & Borgmatic

> **GSoC 2026 Repo to follow my progress, design documents, and weekly updates.**

Welcome to my Google Summer of Code (GSoC) 2026 workspace! This repository serves as a centralized logbook for my work with the Python Software Foundation, specifically contributing to **[Vorta](https://github.com/borgbackup/vorta)** (the desktop GUI for BorgBackup) and **[Borgmatic](https://github.com/borgmatic-collective/borgmatic)**.

## 👨‍💻 About Me
* **Name:** Ebuzer Celil Durmaz 
* **Organization:** Python Software Foundation (PSF)
* **Projects:** Vorta & Borgmatic
* **Project Size:** Large 

### 👥 Mentors
* **Manuel Riel** (Primary Mentor - Vorta)
* **Dan Helfman** (Mentor / PR Reviewer - Borgmatic)
* **Thomas Waldmann** (BorgBackup Ecosystem)

---

##  Project Scope & Task Tracker

My project focuses on major architectural and UI refactoring for Vorta, alongside expanding ecosystem integrations for Borgmatic. 

### Core Vorta Architecture & UI (Mentor: Manuel)
- [ ] **1. Scheduler Refactor with Persistent Jobs Store and Jobs View (~130h)**
  - Replace in-memory scheduler with SQLite-backed jobs store.
  - Create a "Jobs" view in the UI showing pending/running/failed/skipped jobs.
- [ ] **2. Finish the Views/ViewModel Migration (~80h)**
  - Migrate remaining tabs (Source, Archive, Schedule, Misc) to `BaseTab` and `RepoTabViewModel`.
  - Add ViewModel-level tests.
- [ ] **3. Borg 2.x Repository Migration Assistant (~70h)**
  - Build an in-app guided migration path for moving users from Borg 1.x to 2.x repositories.

### Testing & Cross-Project Hooks (Mentor: Dan)
- [ ] **4. Conftest & Test Fixture Consolidation in Vorta (~30h)**
  - Consolidate duplicate fixtures and flatten directory structure.
- [ ] **5. Borgmatic: Docker and/or Podman Data Source Hook (~40h)**
  - Implement a new data source hook for containerized environments.

---

## 📅 Weekly Log

I will be updating this section weekly with my progress, pull requests, and goals for the upcoming week. Detailed logs can be found in the `weekly-reports/` directory.

## 📅 Project Timeline (Extended 22-Week Schedule)

Because this is a Large (~350 hour) project, I am utilizing the extended 22-week GSoC schedule. Detailed logs can be found in the `weekly-reports/` directory.

| Phase | Weeks | Focus | PR Links |
| :--- | :--- | :--- | :--- |
| **Community Bonding** | May - June | Planning, Architecture Design, Environment Setup | - |
| **Phase 1** | Weeks 1 - 5 | Scheduler Refactor (Backend & SQLite migration) | |
| **Phase 2** | Weeks 6 - 10 | Scheduler UI, Views/ViewModel Migration | |
| **Midterm Evaluation** | **Week 11** | **Deliverables: Complete Scheduler & ViewModel Migration** | |
| **Phase 3** | Weeks 12 - 16 | Borg 2.x Migration Assistant | |
| **Phase 4** | Weeks 17 - 21 | Vorta CI Cleanup & Borgmatic Docker Hook | |
| **Final Evaluation** | **Week 22** | Final Testing, Documentation, Wrap-up | - |

---

## 🔗 Important Links
* [Vorta Repository](https://github.com/borgbackup/vorta)
* [Borgmatic Repository](https://github.com/borgmatic-collective/borgmatic)
