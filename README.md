# SQL_Data_Modeling_and_Query_Set

![Language](https://img.shields.io/badge/Language-T--SQL-lightgrey)
![Analysis](https://img.shields.io/badge/Focus-Data%20Analysis%20%26%20Reporting-success)
![AI Assisted](https://img.shields.io/badge/AI-Assisted-brightgreen)
![Learning in Public](https://img.shields.io/badge/Learning-In%20Public-orange)

A focused, real-world SQL and reporting project to turn operational data into accurate, repeatable executive insights.

**At a glance**

- Uses real constraints: legacy Excel, live SQL Server, internal stakeholders.
- Replaces ad-hoc spreadsheets with documented, reproducible queries.
- Emphasizes data integrity, governance, and explainability.
- Demonstrates responsible AI use in technical workflows.

This README explains what the project is, why it was built, and how AI was used as a learning and development partner.

---

## Project Overview

This project started with a simple problem:

Leaders and supervisors needed clear, trusted reporting from existing operational data. The data was there. The reporting process was not.

I used this project to:

- Design and refine production-ready queries  
- Standardize outputs for executive reports  
- Practice industry-standard data analysis workflows  
- Integrate AI as a development and learning partner, not a shortcut  

All examples are generalized. No protected or identifiable information is included.

---

## Context

**Data**

- Operational data sets from a secure, policy-driven environment  
- Includes records, events, utilization metrics, and time-based activity  

**Stakeholders**

- Managers and supervisors  
- Compliance and quality assurance  
- External reviewers and auditors  

**Requirements**

- Accurate, repeatable reporting  
- Clear alignment with policy and legal expectations  
- No exposure of protected information  

---

## Problem

Originally, reporting was:

- **Manual**: Staff pulled ad-hoc numbers from the database or spreadsheets  
- **Inconsistent**: Different people, different methods, different answers  
- **Slow**: Leadership could not get trusted views without delays  
- **Risky**: Manual handling increased the chance of errors and missing data  

Key gaps:

- No single source of truth for daily and monthly reporting  
- No standardized queries for executive summaries  
- No friendly outputs for shift leaders and managers  
- Limited visibility into year-to-date and year-to-year patterns  

The goal was not just to get numbers.  
The goal was to build a reliable, explainable reporting process.

---

## Objectives

### Technical and Reporting Objectives

Design robust SQL queries to support:

- Identify key operational metrics  
- Daily summaries  
- Utilization and capacity views  
- Date and time-based analysis  
- Executive-ready aggregates (weekly, monthly, YTD)  

Improve data quality and consistency by:

- Handling inconsistent text entries  
- Managing keys and relationships correctly  
- Reducing duplicate logic and one-off exports  

### Governance and Assurance Objectives

- Data integrity and validation  
- Basic data governance practices  
- Least-privilege and appropriate access  
- Secure reporting practices  
- Documentation of technical decisions  

### Data Analysis Best Practices

- Reproducible queries and clear data modeling  
- Separation of raw data, logic, and presentation  
- Use of parameterization where applicable  
- Transparent logic that others can read, test, and audit  

### Use of AI

Use AI as a force multiplier to:

- Shorten development time  
- Improve clarity and structure  
- Reinforce, not replace, core conceptual understanding  

---

## Technical Environment

**Primary Stack**

- Database: Microsoft SQL Server  
- Query language: T-SQL  
- Client tools: SQL Server Management Studio (SSMS)  
- Reporting and analysis: Microsoft Excel (including Excel 2016)  
- Documentation: Internal project notes and this README  

**Patterns and Techniques Used**

- `SELECT` queries for operational and summary reports  
- Joins across multiple related tables  
- Use of primary and foreign keys for consistent relationships  
- Handling basic data quality issues (misspellings, inconsistent labels)  
- Derived fields and calculations for reporting  
- Export to CSV for use in spreadsheets and dashboards  

All schema names and fields are sanitized and generalized.

---

## Solution Approach

### Step 1: Map the Questions

- Collected leadership and supervisor reporting needs  
- Translated broad requests into specific query questions and defined outputs  

### Step 2: Understand the Data Model

- Identified core entities and measurable fields  
- Reviewed status and classification values  
- Ensured joins and keys reflected real-world behavior:
  - Many events over time per record  
  - Defined status at each event  
  - Changes tracked over time  

### Step 3: Build Targeted Queries

Each query focused on:

- Clear filters  
- Explicit date ranges  
- Simple, readable logic  
- Consistent aliases and naming conventions  

### Step 4: Shape Outputs for Real Users

Instead of raw query dumps:

- Structured results designed to drop directly into:
  - One-page supervisor summaries  
  - Monthly executive snapshots  
  - Simple tables and graphs  

Priority: make the data usable, explainable, and defensible in real-world conditions.

---

## AI Collaboration and Learning in Public

This project used ChatGPT (GPT-5 Thinking) as a working partner.

**How AI Was Used**

Discussion partner for:

- Query design  
- Troubleshooting errors  
- Optimizing joins and structure  

Instructor for:

- Explaining T-SQL concepts  
- Demonstrating temp tables, keys, and aggregation patterns  

Drafting assistant for:

- Documenting logic and decision paths  
- Writing clear, human-readable explanations and notes  

**Impact**

- Faster identification of syntax and logic issues  
- Example patterns to adapt to the real schema  
- Reduced trial-and-error  
- More time spent on understanding why the solution works  

All final decisions, testing, and validation remained human-driven.  
AI was used to learn faster, think more clearly, and deliver cleaner work.
