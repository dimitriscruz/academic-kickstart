+++
title = "Carving Perfect Layers out of Docker Images"
date = 2019-06-15T23:44:01-07:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dimitris Skourtis and Lukas Rupprecht and Vasily Tarasov and Nimrod Megiddo"]

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
publication = "11th USENIX Workshop on Hot Topics in Cloud Computing"
publication_short = "HotCloud 19"

# Abstract and optional shortened version.
abstract = "Container frameworks such as Docker have changed the way developers package, share, and deploy applications. Container images form a cornerstone of this new model. Images contain applications and their required runtime dependencies and can be easily versioned, stored, and shared via centralized registry services. The ease of creating and sharing images has led to a rapid adoption of container technology but registries are now faced with the task of efficiently storing and serving millions of images. While in theory identical parts of Docker images can be shared across images and stored only once as layers, in practice this provides limited benefits as layers are rarely fully identical. In this paper, we argue that Docker image layers should be reorganized in order to maximize their overlap and, thereby, reduce storage and network consumption. This argument is based on the observation that many layers only differ in a small number of files but would otherwise be identical. We present a set of design challenges that need to be solved when realizing such a reorganization approach, e.g., how to optimally reorganize layers, how to deal with the scale of current registries, and how to integrate the approach into the container image lifecycle. We then present a mathematical formulation of the problem and evaluate it on a set of real Docker images. Our preliminary results provide storage savings of 2:3x, and indicate that promising network savings are possible."
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
url_pdf = "https://www.usenix.org/system/files/hotcloud19-paper-skourtis_0.pdf"
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
