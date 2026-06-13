# DecodeLabs DevOps Engineering Internship — Week 1 Portfolio

Welcome to my official DevOps industrial training workspace. This repository serves as a comprehensive portfolio demonstrating my practical mastery of core systems administration, structured version control workflows, containerization strategies, and cloud-managed automation pipelines.

---

##  Project 1: Linux & Command Line Basics

### Objective
To move from a passive user to an active infrastructure operator by navigating, managing, and automating operations directly within the Linux kernel terminal environment without relying on graphical interfaces.

### Core Skills Mastered
* **System Mapping & Navigation:** Utilized `pwd` and `cd` variations to precisely map and traverse the system terrain.
* **File Architecture & Engineering:** Leveraged `mkdir -p` to construct clean, production-grade nested directory trees, and managed data with `touch`, `cp`, and `mv`.
* **Content Manipulation:** Implemented stream handling using `cat` and `echo` paired with output redirection (`>` and `>>`) to generate systemic logs.
* **Housekeeping & Maintenance:** Enforced safe workspace cleanup processes using `rm`.
* **Systems Architecture Knowledge:** Understood and mapped configurations directly matching the Linux Filesystem Hierarchy Standard (FHS) such as `/bin`, `/etc`, and `/var`.

---

##  Project 2: Version Control Workflow (Git & GitHub)

### Objective
To implement an enterprise-level Software Development Lifecycle (SDLC) workflow, ensuring absolute traceability and codebase protection through strict version control boundaries.

### Implementation Highlights
* **Tree Separation:** Separated volatile sandbox workspaces (Working Directory) from the loading dock (Staging Area) before committing to the immutable Ship's Log (Local Repository).
* **Branch Isolation:** Developed features cleanly on a dedicated `feature/git-basics` branch to protect the integrity of the main branch.
* **Traceable Documentation:** Sealed changes using crisp, imperative-verb commit messages to establish a seamless audit trail (`git log --oneline`).

---

## Project 3: The Automated Software Factory (CI/CD Pipeline)

### Objective
To remove human error and establish a continuous, efficient software delivery engine by replacing manual terminal commands with a digital conveyor belt via GitHub Actions.

### Pipeline Infrastructure (`.github/workflows/decodelabs-ci.yml`)
* **Trigger Event:** Automated execution triggers instantly upon any code push to the `main` or `master` branches.
* **Cloud Runner:** Runs isolated steps on a fresh, virtual cloud-hosted environment (`ubuntu-latest`).
* **Sequential Automation Stages:**
  1. **Stage 1 — Checkout Code Base:** Automatically pulls the fresh repository state into the runner workspace.
  2. **Stage 2 — Verify Linux Basics Setup:** Runs a lint script confirming your Week 1 directory structure exists.
  3. **Stage 3 — Evaluate Version Control Integrity:** Executes structural terminal analysis (`ls -la`) to report immediate pipeline metrics.

---

##  Project 4: Containerization with Docker (Advanced Optional Milestone)

### Objective
To eliminate the classic environment drift issue ("it works on my machine") by packaging an application and all its system dependencies into an immutable, lightweight container blueprint.

### Implementation Highlights
* **Application Layering:** Built a standalone Node.js-based micro-server running cleanly inside an isolated space.
* **Dockerfile Infrastructure:** Written a custom production-ready `Dockerfile` layout to configure execution paths, set workspaces, and minimize image sizes utilizing Alpine Linux bases (`node:18-alpine`).
* **Network Strategy:** Configured explicit port forwarding parameters (`-p 8080:8080`) allowing the host operating system to cleanly bridge web traffic straight to the isolated cloud engine environment.

---

##  Tech Stack Summary
* **Operating System:** Linux / Ubuntu
* **Version Control Hub:** Git / GitHub
* **Automation Engine:** GitHub Actions (YAML Syntax)
* **Containerization Platform:** Docker Engine

---

##  Author
* **Name:** Sudip Sherpa  
* **Role:** DevOps Engineer in Training — Batch 2026  
* **Organization:** DecodeLabs
