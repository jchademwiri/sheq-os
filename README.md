# 🛡️ SHEQ OS

An open-source, Markdown-based operating system and web platform for Health, Safety, Environment, and Quality (SHEQ) compliance.

---

## 📖 The Vision

The compliance industry is still dominated by static Word documents, fragmented SharePoint folders, and unmanaged PDF archives. **SHEQ OS replaces this fragmentation with a structured, version-controlled, and developer-friendly Integrated Management System (IMS).**

We are building a modern IMS infrastructure for ISO 9001, ISO 14001, and ISO 45001 by treating compliance documentation as **code (Markdown)** and rendering it through a fast, modular web system (Astro).

This enables compliance systems that are:

- Version-controlled  
- AI-readable and AI-generatable  
- Searchable and structured  
- Reusable and scalable  
- Automation-ready (MD → Word/PDF outputs)  

---

## 🧠 System Overview

SHEQ OS is not just a document repository. It is a structured IMS framework composed of four interconnected systems:

### 📚 1. Knowledge System (Academy)
A structured learning environment covering SHEQ fundamentals, ISO standards, and implementation knowledge.

- SHEQ fundamentals  
- ISO 9001 / 14001 / 45001 theory  
- Risk management  
- Legal compliance  
- Internal auditing  
- Incident investigation  
- Continuous improvement  

---

### ⚙️ 2. Execution System (Consultant Playbook)
A structured implementation methodology that guides organisations through IMS deployment.

**9-week implementation lifecycle:**
- Gap Analysis  
- Leadership & Context  
- Risk Mapping  
- Planning & Objectives  
- Operational Design  
- Emergency Preparedness  
- Training & Awareness  
- Internal Audit  
- Certification Readiness  

---

### 🗄️ 3. Asset System (Core Library)
A reusable, version-controlled library of IMS documentation assets:

- Policies  
- Procedures  
- Registers  
- Templates  
- Flowcharts  
- Forms  

Organised by **operational domains** rather than strict ISO clauses.

---

### 👤 4. Capability System (Practitioner Path)
A structured professional development framework that defines progression in SHEQ competence.

Levels include:
- Student  
- SHEQ Fundamentals  
- IMS Practitioner  
- Internal Auditor  
- Lead Auditor  
- SHEQ Consultant  
- SHEQ Manager  
- Head of SHEQ  
- Independent Consultant  

Each level includes:
- Required knowledge  
- Practical exercises  
- Templates to produce  
- Portfolio evidence requirements  
- Recommended certifications  

---

## 🏗️ System Architecture

SHEQ OS is built using **Astro** with a Markdown-first content architecture.

```bash
sheq-os/
├── public/                   # Static assets (PDFs, logos, downloads)
├── src/
│   ├── components/          # UI components (navigation, search, layout)
│   ├── layouts/             # Page structure templates
│   ├── pages/               # File-based routing system
│   └── content/             # 🧠 CORE IMS KNOWLEDGE BASE
│       │
│       ├── 01-core-library/  # Policies, procedures, templates, registers
│       ├── 02-playbook/      # 9-week IMS implementation system
│       ├── 03-academy/       # Learning modules and theory base
│       └── 04-journal/       # Build-in-public development notes
│
├── astro.config.mjs
├── package.json
└── README.md
