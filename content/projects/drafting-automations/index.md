---
title: "Drafting Automations"
draft: false
weight: 100

# PaperMod / SEO
cover:
    image: "cover.png" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "Drafting Automations"
project_summary: "Developed a suite of AutoLISP and VBA utilities to automate repetitive civil drafting tasks, including data extraction, turnout geometry, and intelligent text replacement."
project_domains: ["Engineering", "Automation"]
project_skills: ["Scripting", "CAD Modeling"]
company_name: "JFSCO"
---

{{< carousel >}}

## Situation
* **Problem:** Manual drafting workflows for large-scale civil projects were prone to human error and consumed excessive billable hours. 
* **Goal:** Create a robust set of "one-click" tools to handle complex geometric exports and bulk text edits within the AutoCAD environment. 
* **Context:** Specialized tasks like railway turnout extraction and coordinate data exporting required custom logic not found in the standard Civil3D toolkit.

## Task
* **Responsibility:** Design, code, and document a collection of productivity scripts to be used by the wider drafting team. 
* **Constraints:** Tools had to be compatible with legacy AutoCAD versions and support external data formats (CSV/TXT) for seamless integration with field surveys. 
* **Tech Stack:** AutoLISP for core CAD manipulation and VBA/Instructions for data management. 

## Action
* **Data Automation:** Developed scripts to **automatically draw and export point data**, eliminating manual entry and ensuring coordinate accuracy between the model and field files. 
* **Geometric Specialized Tools:** Built a custom **Turnout Data Export** utility to handle specialized rail geometry calculations and reporting. 
* **Bulk Processing:** Created an **Incremental Text Replacement** tool to automate sequential labeling and systematic text updates across entire drawing sets. 
* **Documentation:** Authored comprehensive **Work Instructions** for each utility to ensure consistent application and reduce the learning curve for new users. 

## Result
* **Speed:** Reduced data extraction and export times by approximately 80% compared to manual methods. 
* **Accuracy:** Eliminated transcription errors by automating the flow of data from the drawing space to external utility reports. 
* **Scalability:** The tools allowed the team to handle significantly larger datasets without increasing the drafting headcount. 
