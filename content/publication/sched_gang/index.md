---
title: "Schedulability Analysis of Non-preemptive Sporadic Gang Tasks on Hardware Accelerators"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Binqi Sun
- Tomasz Kloda
- admin
- Cen Lu
- Marco Caccamo


# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-05-18T00:00:00Z"
doi: "10.1109/RTAS58335.2023.00019"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2023 IEEE 29th Real-Time and Embedded Technology and Applications Symposium
publication_short: In *2023 IEEE 29th Real-Time and Embedded Technology and Applications Symposium (RTAS)*

abstract: Non-preemptive rigid gang scheduling combines the performance benefits of parallel execution with the low overhead of non-preemptive scheduling and rigid task programming model. This approach appears particularly well-suited for parallel hardware accelerators where the context switch and migration overheads are critical and should be avoided. One of the most notable examples today is Google's Edge Tensor Processing Unit (TPU) used for neural network inference on embedded boards. The paper studies sporadic non-preemptive rigid gang scheduling applied to multi-TPU edge AI accelerators. Each gang task spawns a fixed number of threads that must execute simultaneously on distinct processing units. We consider non-preemptive fixed-priority gang (NP-FP-Gang) scheduling and propose the first carry-in limitation for gang task response time analysis. The gang task carry-in limitation differs from conventional sequential tasks due to the intra-task parallelism. We formulate it as a generalized knapsack problem and develop a linear programming relaxation and a dynamic programming approach to solve the problem under different time complexities. The performance of the proposed schedulability analysis is evaluated through randomly generated synthetic task sets and a case study using neural network benchmarks executed on commercial off-the-shelf multi-TPU edge AI accelerators. The evaluation results show that the proposed response time analysis effectively improves the state of-the-art NP-FP-Gang schedulability test even by 85.7% for the Edge TPU benchmarks in particular.


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
