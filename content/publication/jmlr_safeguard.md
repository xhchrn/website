+++
title = "Safeguarded Learned Convex Optimization"
date = 2020-08-17T00:00:01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["H. Heaton", "**X. Chen**", "Z. Wang", "W. Yin"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Under review in Journal of Machine Learning Research*"
publication_short = "Under review in JMLR"

# Abstract and optional shortened version.
abstract = "Many applications require repeatedly solving a certain type of optimization problem, eachtime with new (but similar) data. Data-driven algorithms can “learn to optimize” (L2O) with much fewer iterations and with similar cost per iteration as general-purpose optimiza-tion algorithms. L2O algorithms are often derived from general-purpose algorithms, butwith the inclusion of (possibly many) tunable parameters. Exceptional performance hasbeen demonstrated when they are optimized for a particular distribution of data. Unfor-tunately, it is impossible to ensure all L2O algorithmsalwaysconverge to a solution. Wehereby present a framework that uses L2O updates together with a safeguard to guaranteeconvergence for convex problems with proximal and/or gradient oracles. The safeguard issimple and computationally cheap to implement, and it is activated only when the currentL2O updates would perform poorly or appear to diverge. This approach yields the numer-ical benefits of employing machine learning methods to create rapid L2O algorithms whilestill guaranteeing convergence. Our numerical examples demonstrate the efficacy of thisapproach for existing and new L2O schemes."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's filename without extension.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   Otherwise, set `projects = []`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/2003.01880"
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
