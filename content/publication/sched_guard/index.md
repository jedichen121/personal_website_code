---
title: "SchedGuard: Protecting against Schedule Leaks Using Linux Containers"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Tomasz Kloda
- Ayoosh Bansal
- Rohan Tabish
- Chien-Ying Chen
- Bo Liu
- Sibin Mohan
- Marco Caccamo
- Lui Sha

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-05-18T00:00:00Z"
doi: "10.1109/RTAS52030.2021.00010"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-05-18T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2021 IEEE 27th Real-Time and Embedded Technology and Applications Symposium
publication_short: In *RTAS*

abstract: Real-time systems have recently been shown to be vulnerable to timing inference attacks, mainly due to their predictable behavioral patterns. Existing solutions such as schedule randomization lack the ability to protect against such attacks, often limited by the system's real-time nature. This paper presents “SchedGuard”, a temporal protection framework for Linux-based hard real-time systems that protects against posterior scheduler side-channel attacks by preventing untrusted tasks from executing during specific time segments. SchedGuard is integrated into the Linux kernel using cgroups, making it amenable to use with container frameworks. We demonstrate the effectiveness of our system using a realistic radio-controlled rover platform and synthetically generated workloads. Not only is SchedGuard able to protect against the attacks mentioned above, but it also ensures that the real-time tasks/containers meet their temporal requirements.


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
