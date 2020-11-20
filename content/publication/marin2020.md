+++
title = "Optimization of Efficient Neuron Models With Realistic Firing Dynamics. The Case of the Cerebellar Granule Cell"
date = 2020-07-14T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Milagros Marín", "María J. Sáez-Lara", "Eduardo Ros", "Jesús A. Garrido"]

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
publication = "Frontiers in Cellular Neuroscience"
publication_short = "Front. Cell. Neurosci."

# Abstract and optional shortened version.
abstract = "Biologically relevant large-scale computational models currently represent one of the main methods in neuroscience for studying information processing primitives of brain areas. However, biologically realistic neuron models tend to be computationally heavy and thus prevent these models from being part of brain-area models including thousands or even millions of neurons. The cerebellar input layer represents a canonical example of large scale networks. In particular, the cerebellar granule cells, the most numerous cells in the whole mammalian brain, have been proposed as playing a pivotal role in the creation of somato-sensorial information representations. Enhanced burst frequency (spiking resonance) in the granule cells has been proposed as facilitating the input signal transmission at the theta-frequency band (4–12 Hz), but the functional role of this cell feature in the operation of the granular layer remains largely unclear. This study aims to develop a methodological pipeline for creating neuron models that maintain biological realism and computational efficiency whilst capturing essential aspects of single-neuron processing. Therefore, we selected a light computational neuron model template (the adaptive-exponential integrate-and-fire model), whose parameters were progressively refined using an automatic parameter tuning with evolutionary algorithms (EAs). The resulting point-neuron models are suitable for reproducing the main firing properties of a realistic granule cell from electrophysiological measurements, including the spiking resonance at the theta-frequency band, repetitive firing according to a specified intensity-frequency (I-F) curve and delayed firing under current-pulse stimulation. Interestingly, the proposed model also reproduced some other emergent properties (namely, silent at rest, rheobase and negligible adaptation under depolarizing currents) even though these properties were not set in the EA as a target in the fitness function (FF), proving that these features are compatible even in computationally simple models. The proposed methodology represents a valuable tool for adjusting AdEx models according to a FF defined in the spiking regime and based on biological data. These models are appropriate for future research of the functional implication of bursting resonance at the theta band in large-scale granular layer network models."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["cerebrot","hbp"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "pdf/marin2020.pdf"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""
url_custom = [{name = "Journal", url = "https://www.frontiersin.org/articles/10.3389/fncel.2020.00161/full" }]

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
