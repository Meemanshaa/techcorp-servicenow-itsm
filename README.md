# 🏢 TechCorp IT Operations Centre

![ServiceNow](https://img.shields.io/badge/Platform-ServiceNow-00A550?style=for-the-badge&logo=servicenow&logoColor=white)

A production-grade **Enterprise IT Service Management (ITSM)** environment built entirely on a **ServiceNow Personal Developer Instance (PDI)** as part of ServiceNow **CSA preparation**.

Built for a fictional **200-employee technology company**, simulating a real-world ServiceNow implementation including administration, automation, security, CMDB design, and self-service workflows.

---

## 📌 Project Overview

TechCorp IT Operations Centre simulates a complete IT ecosystem for a fictional company called **TechCorp**.

The project was designed as a real deployment scenario — from configuring users and access control to implementing automation workflows, CMDB relationships, and ITSM components.

This project covers all major **ServiceNow CSA domains** and demonstrates practical understanding of platform administration and enterprise workflows.

---

## 🚀 Project Highlights

| Feature | Count |
|----------|--------|
| Users | 8 |
| Departments | 3 |
| Assignment Groups | 3 |
| Configuration Items | 18 |
| ACL Rules | 4 |
| CSA Topics Covered | 6/6 |

---

# ✨ What I Built

### 🔧 Instance Configuration
- Renamed and branded the instance as **TechCorp IT Operations Centre**
- Configured company structure and departments
- Created users, assignment groups, and role mappings
- Built an IT Manager Dashboard

### 📋 Forms, Lists & Collaboration
- Customized Incident form layouts
- Created saved filters and templates
- Configured email notifications
- Built Visual Task Boards

### 🛒 Self-Service Portal
- Service Catalog with:
  - Laptop Request
  - Password Reset
  - New Employee IT Setup
- Knowledge Base implementation
- Virtual Agent chatbot
- Approval workflows using Flow Designer

### 🔐 Security & Access Control
- Created custom user roles:
  - `techcorp_it_agent`
  - `techcorp_it_manager`
  - `techcorp_end_user`
- Implemented record-level and field-level ACLs
- Applied least-privilege access principles

### 🗄️ CMDB & CSDM
Created **18 Configuration Items** across multiple CI classes:

- Linux Servers
- Computers / Laptops
- Business Applications
- Network Devices
- Peripherals

Relationship hierarchy:

```text
TechCorp ITSM Portal
      ↓ Runs on
TECH-APP-01
      ↓ Depends on
TECH-DB-01
      ↑ Connects to
TECH-WEB-01
```

### ⚙️ Automation & Scripting

- Business Rule for automatic incident assignment
- UI Policy for dynamic form validation
- Script Include (`TechCorpUtils`)
- Import Sets with Transform Maps

---

## 📁 Repository Structure

```bash
techcorp-servicenow-itsm/

├── README.md

├── import-data/
│   ├── TechCorp_Incidents_Import.csv
│   ├── TechCorp_CMDB_Import.csv
│   └── TechCorp_User_Import.csv

└── screenshots/
    ├── 01_instance_home.png
    ├── 02_dashboard.png
    ├── 03_incident_list.png
    ├── 04_service_catalog.png
    ├── 05_catalog_item_laptop.png
    ├── 06_knowledge_base.png
    ├── 07_acl_list.png
    ├── 08_custom_roles.png
    ├── 09_cmdb_relationship_map.png
    ├── 10_cmdb_ci_list.png
    ├── 11_business_rule.png
    ├── 12_ui_policy.png
    ├── 13_update_set.png
    ├── 14_approval_flow.png
    └── 15_import_set_results.png
```

---

## 💼 Resume Impact

Skills and concepts demonstrated:

- ServiceNow administration
- ITSM implementation
- Role-based security
- CMDB design
- Workflow automation
- Flow Designer
- Business Rules
- Data import and transformation
- Enterprise workflow design

---

## 🛠️ Tech Stack

![ServiceNow](https://img.shields.io/badge/ServiceNow-PDI-00A550?style=flat-square)
![Flow Designer](https://img.shields.io/badge/Flow%20Designer-Automation-1B3A6B?style=flat-square)
![GlideScript](https://img.shields.io/badge/GlideScript-Business%20Rules-F0A500?style=flat-square)
![CMDB](https://img.shields.io/badge/CMDB-CSDM-brightgreen?style=flat-square)
![ACL](https://img.shields.io/badge/Security-ACL%20%26%20Roles-red?style=flat-square)
