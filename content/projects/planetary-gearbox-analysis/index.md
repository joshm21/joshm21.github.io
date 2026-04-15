---
title: "Planetary Gearbox Analysis"
draft: true
weight: 100

# PaperMod / SEO
cover:
    image: "cover.png" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "Planetary Gearbox Analysis"
project_summary: "Engineered a system dynamics calculator and technical white papers to analyze inertial loads across multi-stage planetary gearboxes, bridging the gap between complex engineering data and end user resources."
project_domains: ["Engineering"]
project_skills: ["Calculations" , "Techincal Writing", "Scripting", "CAD Modeling"]
company_name: "Groschopp"
---

{{< carousel >}}

## Situation
* **Problem:** Sales teams lacked an accurate, quick way to estimate system dynamics for custom gearbox configurations, often leading to under- or over-specified components.
* **Goal:** Create a reliable tool to determine inertial loads for 1, 2, and 3-step reduction gearboxes and document the underlying physics for the engineering team.
* **Context:** Manual extraction of mass moments of inertia from CAD models was too slow for the rapid pace of sales inquiries.

## Task
* **Responsibility:** Develop an automated data extraction pipeline and a user-friendly calculator for non-engineers.
* **Constraints:** Calculations had to account for varying gear ratios, material densities, and multi-stage stacking (up to 3 stages).
* **Tech Stack:** VBA (Excel/SolidWorks API), SolidWorks PDM database, and MathCAD for technical equations and documentation.

## Action
* **Data Scraping:** Wrote a **VBA script** to interface with the **SolidWorks API**, automatically extracting actual mass moments of inertia and physical properties from the master component database.
* **Algorithm Development:** Built a mathematical model to calculate **system dynamics and reflected inertia** across multiple reduction stages.
* **Tool Creation:** Developed a standalone **Excel-based calculator** for the sales team, simplifying complex mechanical inputs into a "plug-and-play" interface.
* **Documentation:** Authored a series of **internal white papers** detailing the derivation of the formulas used, ensuring the engineering team could audit and validate the tool's logic.

## Result
* **Speed:** Reduced the time to generate accurate dynamic load profiles from hours to seconds.
* **Accuracy:** Improved quote precision by using **actual CAD-derived data** rather than theoretical approximations.
* **Knowledge Sharing:** Established a centralized technical reference for planetary gearbox dynamics, improving onboarding for junior engineers.
