# Project Decisions

This file records important project decisions and the reasoning behind them.

---

## D001 — Use a Separate Git Repository for Project 1

**Decision:**  
`sa-road-crash-intelligence` is an independent Git repository inside the local `data-intelligence-portfolio` folder.

**Reason:**  
Each major portfolio project should have its own history, documentation, codebase and GitHub repository.

**Status:** Accepted

---

## D002 — Use Personal Git Identity

**Decision:**  
Use repository-local Git configuration for the user's personal GitHub identity.

**Reason:**  
The Mac's global Git configuration is associated with the user's university identity. This portfolio project must remain associated with the personal GitHub account without disrupting university repositories.

**Status:** Accepted

---

## D003 — Keep Raw Data Out of Git

**Decision:**  
Files inside `data/raw/` are excluded from Git while the directory itself is retained using `.gitkeep`.

**Reason:**  
Downloaded source datasets should remain unchanged locally and generally do not need to be duplicated in the Git repository. The project should instead document where data came from and how it is processed.

**Status:** Accepted

---

## D004 — Use Lightweight Project Documentation for AI and Human Context

**Decision:**  
Maintain dedicated Markdown files for project context, agent instructions, data definitions, workflow and significant decisions.

**Reason:**  
Important project knowledge should live in the repository rather than only inside an AI conversation. This improves reproducibility, maintainability and portability between developers and AI agents.

**Status:** Accepted
