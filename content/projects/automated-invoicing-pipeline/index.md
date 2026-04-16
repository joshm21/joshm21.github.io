---
title: "Automated Invoicing Pipeline"
draft: false
weight: 40

# PaperMod / SEO
cover:
    image: "cover.png" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "Automated Invoicing Pipeline"
project_summary: "Streamlined financial operations by developing an automation suite that eliminated manual data entry between spreadsheets and vendor portals."
project_domains: ["Automation"]
project_skills: ["Scripting", "APIs", "Integrations"]
company_name: "Freelancer"
---

{{< carousel >}}

## Situation
The client’s quoting process was stalled by a massive manual bottleneck involving:
* **Manual "Swivel-Chair" Entry:** Copying 20+ data points from a Google Sheet into a difficult 3rd-party vendor site.
* **Complex Logic:** Vendor forms included hundreds of nested options, leading to frequent errors.
* **Slow Turnaround:** Employees had to manually log in, submit, and copy results back to calculate final pricing.

## Task
Replace the manual copy-paste workflow with an automated system to:
* **Centralize Operations:** Allow employees to stay within a single Google Sheet.
* **Eliminate Latency:** Reduce quote turnaround from days to hours.
* **Ensure Accuracy:** Automate data mapping to prevent costly human errors.

## Action
I engineered an end-to-end automation suite using **Google Apps Script**:
* **Multi-User Environment:** Configured **Named Filter Views** and **Protected Ranges** to allow multiple sales employees to work simultaneously. This ensured each user only saw and edited their assigned leads, preventing data overwrites.
* **Spreadsheet UI:** Built a configuration interface with strict **Data Validations** for sales employees to select vendor options accurately.
* **Headless Submission:** Developed a script to programmatically **authenticate** and **auto-complete** the complex vendor form.
* **Real-time Updates:** Utilized **onEdit triggers** to automatically refresh vendor pricing as soon as quote parameters were adjusted.
* **Auto-Invoicing:** Created a post-processing trigger that populates a **PDF invoice template**, saves it to Drive, and emails the customer automatically.

## Result
* **Speed:** Slashed processing time from **days to hours**.
* **Responsiveness:** Sales team could quickly adjust and re-quote customers.
* **Backlog Recovery:** Successfully cleared a multi-month backlog of old requests.
* **Reliability:** Achieved 100% data integrity between vendor costs and customer invoices.
