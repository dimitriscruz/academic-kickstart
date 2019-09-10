+++
title = "Erasure Coding & Read/Write Separation in Flash Storage"
date = 2014-04-29T23:36:49-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["D. Skourtis, D. Achlioptas, N. Watkins, C. Maltzahn, S. Brandt"]

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
publication = "Workshop on Interactions of NVM/Flash with Operating Systems and Workloads"
publication_short = "INFLOW '14"

# Abstract and optional shortened version.
abstract = "We want to create a scalable flash storage system that provides read/write separation and uses erasure coding to provide reliability without the storage cost of replication. Flash on Rails is a system for enabling consistent performance in flash storage by physically separating reads from writes through redundancy. In principle, Rails supports erasure codes. However, it has only been evaluated using replication in small arrays, so it is currently uncertain how it would scale with erasure coding. <br/> <br/>In this work we consider the applicability of erasure coding in Rails, in a new system called eRails. We consider the effects of computation due to encoding/decoding on the raw performance, as well as its effect on performance consistency. We demonstrate that up to a certain number of drives the performance remains unaffected while the computation cost remains modest. After that point, the computational cost grows quickly due to coding itself making further scaling inefficient. To support an arbitrary number of drives we present a design allowing us to scale eRails by constructing overlapping erasure coding groups that preserve read/write separation. Finally, through benchmarks we demonstrate that eRails achieves read/write separation and consistent read performance under read/write workloads."
abstract_short = "In this work we consider the applicability of erasure coding in Rails and consider the effects of computation due to encoding/decoding on the raw performance, as well as its effect on performance consistency."

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["rails"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://www.usenix.org/system/files/conference/inflow14/inflow14-skourtis.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

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
