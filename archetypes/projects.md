---
title: "{{ replace .Name "-" " " | title }}"
draft: true
weight: 10

# PaperMod / SEO
cover:
    image: "cover.jpg" # Reference local file in the same folder
    alt: "Project cover image"
    caption: "Project Description"
    relative: true # Essential for Page Bundles
    responsiveImages: true

# Custom Metadata
project_title: "{{ replace .Name "-" " " | title }}"
project_summary: ""
project_domains: []
project_skills: []
company_name: ""
---

{{< carousel >}}

## Situation
*Context is key. Describe the challenge or the environment.*
- What was the problem you were trying to solve?
- What was the goal?
- **Example:** "Our team needed a way to track inventory in real-time, as the manual spreadsheet was causing 20% data loss."

## Task
*Define your specific responsibility.*
- What were you personally responsible for?
- What were the constraints (time, budget, tech stack)?
- **Example:** "I was tasked with building a secure API that could handle 500 requests per second."

## Action
*This should be the longest section. Focus on the 'How'.*
- What steps did you take?
- What tools or technologies did you choose and why?
- How did you handle setbacks?
- **Example:** "I implemented a Redis caching layer to reduce database load and wrote the backend in Go for its concurrency features."

## Result
*Quantify your success if possible.*
- What happened in the end?
- What did you learn?
- **Metrics:** "Reduced latency by 40% and eliminated data discrepancies entirely."

---

### Related Work
* [Live Demo](https://your-demo-link.com)
* [GitHub Repository](https://github.com/your-username/project)
