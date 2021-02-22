+++
title = "Learning A Minimax Optimizer: A Pilot Study"
date = 2021-02-01T00:00:01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["*J. Shen", "***X. Chen**", "H. Heaton", "T. Chen", "J. Liu", "Z. Wang", "Y. Lin"]
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
publication = "*The International Conference on Learning Representations*"
publication_short = "ICLR 2021"

# Abstract and optional shortened version.
abstract = "Solving continuous minimax optimization is of extensive practical interest, yet notoriously unstable and difficult. This paper introduces the learning to optimize (L2O) methodology to the minimax problems for the first time, and addresses its accompanying unique challenges. We first present Twin L2O, the first dedicated minimax L2O framework consisting of two LSTMs for updating min and max variables, respectively. That decoupled design is found to facilitate learning, particularly when the min and max variables are highly non-symmetric. Empirical experiments on a variety of minimax problems corroborates the effectiveness of Twin-L2O. We then discuss a crucial concern of Twin-L2O, i.e., its inevitably limited generalizability to unseen optimizees, and present two complementary strategies. Our first solution, Enhanced Twin-L2O, is empirically applicable for general minimax problems, by improving L2O training via leveraging curriculum learning. We extensively benchmark our algorithms on popular minimax problems, and compare against state-of-the-art minimax solvers. Our second alternative, called Safeguarded Twin L2O, is a preliminary theoretical exploration stating that under some strong assumptions, it is possible to theoretically establish the convergence of Twin-L2O on optimizing any unseen objective. Our codes and models will be publicly released upon acceptance."
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
url_project = "https://openreview.net/forum?id=nkIDwI6oO4_"
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

