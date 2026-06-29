# 📄 Document Metadata Standard (SHEQ OS)

This document defines the **required metadata structure for all Markdown files** within SHEQ OS. The purpose is to ensure:

- Consistent document structure  
- ISO traceability  
- Automation readiness (MD → Word/PDF/Web)  
- AI interpretability  
- Version control integrity  

---

# 🧠 1. Core Principle

Every document in SHEQ OS is treated as a **structured data object**, not just text.

This means every file must contain **machine-readable metadata (frontmatter)** at the top of the Markdown file.

---

# 🧾 2. Required Frontmatter Structure

All documents MUST include the following base schema:

```md
---
title: string
type: string
domain: string
status: string
version: string
owner: string
last_updated: date
---
