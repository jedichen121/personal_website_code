---
title: "vFPIO: A Virtual I/O Abstraction for FPGA-accelerated I/O Devices"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Harshavardhan Unnibhavi
- Atsushi Koshiba
- Pramod Bhatotia

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In 2024 USENIX Annual Technical Conference
publication_short: In *2024 USENIX Annual Technical Conference*

abstract: Modern cloud systems have adopted a variety of FPGA-accelerated I/O devices, such as SmartNICs and computational storage, while they face programmability and portability challenges. Existing FPGA frameworks either directly expose device-specific I/O interfaces to user logic or offer virtualized I/Os limited to a single device type. The lack of I/O abstraction imposes high engineering costs, less design portability, and even unexpected throughput degradation. We introduce vFPIO, an FPGA-based I/O acceleration framework that brings better programmability and design portability. vFPIO extends modern FPGA OSes to expose virtual I/O ports to user logic, which abstracts device-dependent I/O specifications and makes the user logic design platform-agnostic. The connectivity between virtual and physical I/O ports can be easily configured by host applications using POSIX-like file APIs. vFPIO also offers a preemptive I/O transaction scheduler that alleviates the I/O throughput degradation caused by concurrent I/O requests from multiple accelerators in a multi-tenant environment. We implement a prototype of the vFPIO framework on x86 servers equipped with AMD Xilinx Alveo U280 cards. Our prototype supports four different I/O interfaces, PCIe, DRAM, HBM, and network. Our evaluation highlights that vFPIO incurs negligible performance overheads compared to Coyote, one of the latest FPGA OSes, while preserving the maximum I/O throughput for high-priority tasks even under resource contention.


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
