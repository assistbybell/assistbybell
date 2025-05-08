---
title: "SOP for Creating SOPs"
author: "Operations Team"
date: "2025-05-08"
version: "1.0"
approval: "COO"
status: "Active"
tags:
  - sop
  - template
aliases: sop-creating-sops-001
---

# Standard Operating Procedure (SOP) - Creating SOPs

## Purpose
- Provide a standardised method for creating new SOPs across all departments.

## Scope
- Applies to any team member tasked with defining or documenting an internal procedure.

## Procedure

### 1. Use the Template
- Download and use this markdown SOP template: [[202504130144-archive-sop.md]]
- Save the new SOP using this naming format: `YYYYMMDDHHMM-title-sop.md`
- Ensure all content is in **markdown (.md)** format for GitHub compatibility.

### 2. Define Scope & Steps
- Clearly define what the SOP is for, who it applies to, and what success looks like.
- Break down the procedure step-by-step using numbered headers (e.g., Step 1, Step 2...).
- Use active voice and ensure tasks can be executed without further clarification.

### 3. Include:
- Due Date Management section (based on Jira automation)
- KPIs that are clear and measurable
- Jira Task references (e.g., "[[202504112316-returns-management-sop.md]]") where relevant
- Any forms or message templates used in the process

### 4. Tag Properly
- Include tags in the YAML frontmatter that reflect:
  - Department or function (e.g., `finance`, `logistics`, `customer-support`)
  - Operational category (e.g., `returns`, `order-management`, `qc`, `automation`)

### 5. Task Integration
- Ensure the process aligns with Jira task flows.
- Indicate which steps trigger task creation, status updates, or automation rules.

### 6. Save and Store
- Save in GitHub with version tracking enabled.
- Link the SOP in the master SOP index for accessibility.

## Due Date Management
- All SOPs must specify due date expectations where applicable.
- Jira automation assigns official due dates based on suggested entries.

## KPIs
- SOPs must include a KPI table tracking outcomes or execution timelines.
- State if KPIs are Jira-trackable or require manual reporting.

**Reminder:**
- SOPs should be concise, actionable, and always refer back to the template: [[202504130144-archive-sop.md]]
