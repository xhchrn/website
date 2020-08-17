+++
title = "SmartExchange: Trading Higher-cost Memory Storage/Access for Lower-cost Computation "
date = 2020-05-30T00:00:01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["***X. Chen**", "*Y. Zhao", "Y. Wang", "C. Li", "Y. Xie", "Z. Wang", "Y. Lin"]

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
publication = "*the 47th IEEE/ACM International Symposium on Computer Architecture*"
publication_short = "ISCA 2020"

# Abstract and optional shortened version.
abstract = "We present SmartExchange, a hardware-algorithm co-design framework to trade higher cost memory storage/access for lower cost computation, for energy-efficient inference of deep neural networks (DNNs). We have developed a novel algorithm to enforce a specially favorable DNN weight structure, where each layerwise weight matrix can be stored as the product of a small basis matrix and a large sparse coefficient matrix whose non-zero elements are all power-of-2. The resulting sparse and readily-quantized DNN thus enjoys greatly reduced energy consumption of data movement as well as weight storage. To fully explore the potential of SmartExchange, we further design a dedicated accelerator to fully utilize the SmartExchange-enforced weights to improve both energy efficiency and latency. Extensive experiments using four DNN models show that the proposed accelerator can achieve up to 4.9×and 9.6×improvement in energy efficiency and energy-delay product, respectively, as compared to state-of-the-art DNN accelerators."
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
