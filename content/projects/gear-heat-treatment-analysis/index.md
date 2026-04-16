---
title: "Gear Heat Treatment Analysis"
draft: true
weight: 140

# PaperMod / SEO
cover:
    image: "cover.png" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "Gear Heat Treatment Analysis"
project_summary: "Established a rigorous heat treatment validation process for third-party gears, utilizing micro-indentation testing and automated data analysis to ensure gearbox reliability."
project_domains: ["Mechanical Engineering"] 
project_skills: ["Quality Assurance", "Technical Writing", "Testing", "Scripting"]
company_name: "Groschopp"
---

{{< carousel >}}

## Situation
* **Problem:** Variable quality from third-party gear suppliers threatened the long-term reliability of our gearboxes.
* **Goal:** Create a standardized method to verify effective case depth and surface hardness uniformity.
* **Context:** We needed a way to scientifically differentiate between high-performing suppliers and those delivering "bad batches" before they reached the assembly line.

## Task
* **Responsibility:** Design the testing protocol, automate data processing, and train operators on the new equipment.
* **Constraints:** Data needed to be cross-referenced with original SolidWorks design specifications to ensure compliance.
* **Tech Stack:** LECO LM-100AT Vickers Micro-indentation Tester, VBA (Excel-to-SolidWorks API), and custom Excel templates.

## Action
* **Protocol Design:** Developed a process to measure and record **surface hardness vs. distance from the tooth root**, mapping the hardening profile of the gears.
* **Automation:** Developed **Excel templates** that queried the **SolidWorks API** to pull design specs and automatically calculate deviations from required hardness values.
* **Standardization:** Authored detailed **work instructions** for machine operators to ensure repeatable, accurate data collection across different shifts.
* **Visualization:** Built **filterable dynamic graphs** within the tool, allowing engineers to visually inspect data for uniformity and heat-treatment "depth of case."

## Result
* **Reliability:** Significantly improved gearbox longevity by catching out-of-spec batches before they were integrated into products.
* **Supplier Management:** Provided data-driven leverage to evaluate and hold third-party suppliers accountable for material quality.
* **Efficiency:** Automated the calculation of complex hardening curves, reducing the engineering review time per batch.
