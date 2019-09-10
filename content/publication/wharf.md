+++
title = "Wharf: Sharing Docker images in a distributed file system"
date = 2019-02-15T23:44:01-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Zheng, Chao and Rupprecht, Lukas and Tarasov, Vasily and Thain, Douglas and Mohamed, Mohamed and Skourtis, Dimitrios and Warke, Amit S. and Hildebrand, Dean"]

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
publication = "ACM Symposium on Cloud Computing"
publication_short = "SoCC '18"

# Abstract and optional shortened version.
abstract = "Container management frameworks, such as Docker, package diverse applications and their complex dependencies in self-contained images, which facilitates application deployment, distribution, and sharing. Currently, Docker employs a shared-nothing storage architecture, i.e. every Docker-enabled host requires its own copy of an image on local storage to create and run containers. This greatly inflates storage utilization, network load, and job completion times in the cluster. In this paper, we investigate the option of storing container images in and serving them from a distributed file system. By sharing images in a distributed storage layer, storage utilization can be reduced and redundant image retrievals from a Docker registry become unnecessary. We introduce Wharf, a middleware to transparently add distributed storage support to Docker. Wharf partitions Docker's runtime state into local and global parts and efficiently synchronizes accesses to the global state. By exploiting the layered structure of Docker images, Wharf minimizes the synchronization overhead. Our experiments show that compared to Docker on local storage, Wharf can speed up image retrievals by up to 12x, has more stable performance, and introduces only a minor overhead when accessing data on distributed storage."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["containers"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "http://ccl.cse.nd.edu/research/papers/wharf-socc-2018.pdf"
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
