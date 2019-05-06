+++
title = "VOR Adaptation on a Humanoid iCub Robot Using a Spiking Cerebellar Model"
date = 2019-01-25T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Francisco Naveros","Niceto R. Luque", "Eduardo Ros", "Angelo Arleo"]

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
publication = " IEEE Transactions on Cybernetics "
publication_short = "IEEE Trans. Cybern."

# Abstract and optional shortened version.
abstract = "We embed a spiking cerebellar model within an adaptive real-time (RT) control loop that is able to operate a real robotic body (iCub) when performing different vestibulo-ocular reflex (VOR) tasks. The spiking neural network computation, including event- and time-driven neural dynamics, neural activity, and spike-timing dependent plasticity (STDP) mechanisms, leads to a nondeterministic computation time caused by the neural activity volleys encountered during cerebellar simulation. This nondeterministic computation time motivates the integration of an RT supervisor module that is able to ensure a well-orchestrated neural computation time and robot operation. Actually, our neurorobotic experimental setup (VOR) benefits from the biological sensory motor delay between the cerebellum and the body to buffer the computational overloads as well as providing flexibility in adjusting the neural computation time and RT operation. The RT supervisor module provides for incremental countermeasures that dynamically slow down or speed up the cerebellar simulation by either halting the simulation or disabling certain neural computation features (i.e., STDP mechanisms, spike propagation, and neural updates) to cope with the RT constraints imposed by the real robot operation. This neurorobotic experimental setup is applied to different horizontal and vertical VOR adaptive tasks that are widely used by the neuroscientific community to address cerebellar functioning. We aim to elucidate the manner in which the combination of the cerebellar neural substrate and the distributed plasticity shapes the cerebellar neural activity to mediate motor adaptation. This paper underlies the need for a two-stage learning process to facilitate VOR acquisition."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
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
url_custom = [{name = "Journal", url = "https://ieeexplore.ieee.org/abstract/document/8653961" }]

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

