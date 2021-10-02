+++
title = "SmartDeal: Re-Modeling Deep Network Weights for Efficient Inference and Training"
date = 2020-12-31T00:00:01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["***X. Chen**", "*Y. Zhao", "Y. Wang", "P. Xu", "H. You", "C. Li", "Y. Fu", "Y. Lin", "Z. Wang"]

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
publication = "arXiv preprint, under review in Journal of Machine Learning Research"
publication_short = "arXiv pre-print, under review in JMLR"

# Abstract and optional shortened version.
abstract = "The record-breaking performance of deep neural networks (DNNs) comes with heavy parameterization, leading to external dynamic random-access memory (DRAM) for storage. The prohibitive energy of DRAM accesses makes it non-trivial to deploy DNN on resource-constrained devices, calling for minimizing the weight and data movements to improve the energy efficiency. We present SmartDeal (SD), an algorithm framework to trade higher-cost memory storage/access for lower-cost computation, in order to aggressively boost the storage and energy efficiency, for both inference and training. The core of SD is a novel weight decomposition with structural constraints, carefully crafted to unleash the hardware efficiency potential. Specifically, we decompose each weight tensor as the product of a small basis matrix and a large structurally sparse coefficient matrix whose non-zeros are quantized to power-of-2. The resulting sparse and quantized DNNs enjoy greatly reduced energy for data movement and weight storage, incurring minimal overhead to recover the original weights thanks to the sparse bit-operations and cost-favorable computations. Beyond inference, we take another leap to embrace energy-efficient training, introducing innovative techniques to address the unique roadblocks arising in training while preserving the SD structures. We also design a dedicated hardware accelerator to fully utilize the SD structure to improve the real energy efficiency and latency. We conduct experiments on both multiple tasks, models and datasets in different settings. Results show that: 1) applied to inference, SD achieves up to 2.44x energy efficiency as evaluated via real hardware implementations; 2) applied to training, SD leads to 10.56x and 4.48x reduction in the storage and training energy, with negligible accuracy loss compared to state-of-the-art training baselines. Our source codes are available online."
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
url_pdf = "https://arxiv.org/pdf/2101.01163"
url_preprint = "https://arxiv.org/abs/2101.01163"
url_code = "https://github.com/VITA-Group/SmartDeal"
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
