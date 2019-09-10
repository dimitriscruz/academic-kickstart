+++
title = "QBox: guaranteeing I/O performance on black box storage systems"
date = 2012-06-30T00:02:08-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dimitris Skourtis, Shinpei Kato, Scott Brandt"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "21st International Symposium on High-Performance Parallel and Distributed Computing"
publication_short = "HPDC '12"

# Abstract and optional shortened version.
abstract = "Many storage systems are shared by multiple clients with different types of workloads and performance targets. To achieve performance targets without over-provisioning, a system must provide isolation between clients. Throughput-based reservations are challenging due to the mix of workloads and the stateful nature of disk drives, leading to low reservable throughput, while existing utilization-based solutions require specialized I/O scheduling for each device in the storage system. <br/> <br/> Qbox is a new utilization-based approach for generic black box storage systems that enforces utilization (and, indirectly, throughput) requirements and provides isolation between clients, without specializedlow-level I/O scheduling. Our experimental results show that Qbox provides good isolation and achieves the target utilizations of its clients."
abstract_short = "Qbox is a new utilization-based approach for generic black box storage systems that enforces utilization (and, indirectly, throughput) requirements and provides isolation between clients, without specializedlow-level I/O scheduling."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.709.4303&rep=rep1&type=pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = "https://dl.acm.org/citation.cfm?id=2287087"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
