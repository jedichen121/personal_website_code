---
title: "Latency analysis of self-suspending task chains"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Tomasz Kloda
- admin
- Antoine Bertout
- Lui Sha
- Marco Caccamo

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-03-01T00:00:00Z"
doi: "10.23919/DATE54114.2022.9774655"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Design, Automation & Test in Europe Conference & Exhibition, DATE 2022
publication_short: In *2022 Design, Automation & Test in Europe Conference & Exhibition (DATE)*

abstract: Many cyber-physical systems are offloading computation-heavy programs to hardware accelerators (e.g., GPU and TPU) to reduce execution time. These applications will self-suspend between offloading data to the accelerators and obtaining the returned results. Previous efforts have shown that self-suspending tasks can cause scheduling anomalies, but none has examined inter-task communication. This paper aims to explore self-suspending tasks’ data chain latency with periodic activation and asynchronous message passing. We first present the cause for suspension-induced delays and worst-case latency analysis. We then propose a rule for utilizing the hardware co-processors to reduce data chain latency and schedulability analysis. Simulation results show that the proposed strategy can improve overall latency while preserving system schedulability.


# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
