---
title: "School Behavior App"
draft: false
weight: 2

# PaperMod / SEO
cover:
    image: "cover.png" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "School Behavior App"
project_summary: "A full-stack web app serving teachers, students, parents, and admins to manage behavioral data and reward systems across an entire school district."
project_domains: ["Software Engineering"]
project_skills: ["Web Apps", "Rapid Prototyping"]
company_name: "Freelancer"
---

{{< carousel >}}

## Situation
A school district needed a centralized way to track behavioral data for hundreds of students across multiple classrooms. Existing paper-based or disjointed systems made it difficult to identify long-term trends, manage reward "point" economies, or keep parents updated in real-time without significant manual effort from teachers.

## Task
I was tasked with building a low-friction, high-impact web application that would:
* **Empower Teachers:** Quick entry for positive/negative behavioral incidents.
* **Engage Students:** A portal to view "merit points" and redeem them for school rewards.
* **Inform Parents:** Automated, easy-to-read progress reports.
* **Equip Admins:** High-level analytics to monitor trends per teacher or student over time.

## Action
I leveraged **Google Apps Script** as a serverless backend to minimize deployment friction and technical overhead for the district:

* **Role-Based Web App:** Developed a custom frontend that dynamically serves different views based on the logged-in user (Teacher, Student, Parent, or Admin).
* **Gamified Reward Logic:** Built a ledger system within Google Sheets that calculates point balances in real-time, allowing students to "spend" points on a rewards catalog.
* **Automated Parent Reporting:** Engineered a trigger-based mail merge system that sends weekly reports to parents. I implemented **conditional formatting logic** in the email templates (e.g., green for positive trends, red for frequent incidents) for instant legibility.
* **Administrative Dashboards:** Created filtered aggregate views for admins to track behavioral KPIs across the entire district without needing a dedicated database administrator.

## Result
* **Proven Longevity:** The application has remained in active production use since **2019**, successfully handling years of data and user rotations with minimal maintenance.
* **Zero-Friction Deployment:** The app was deployed within the existing school Google Workspace, requiring no employee training, new software installations, or server maintenance.
* **High Adoption:** Successfully scaled to handle hundreds of students and parents simultaneously.
* **Improved Outcomes:** Admins could identify behavioral patterns weeks earlier than the previous manual system, allowing for faster intervention and more consistent positive reinforcement.
