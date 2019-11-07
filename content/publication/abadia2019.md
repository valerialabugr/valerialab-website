+++
title = "On robot compliance. A cerebellar control approach."
date = 2019-10-23T17:44:35+01:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ignacio Abadía", "Francisco Naveros", "Jesús A. Garrido", "Eduardo Ros", "Niceto R. Luque"]

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
publication = "IEEE transaction on cybernetics"
publication_short = "IEEE trans. on cybernetics"

# Abstract and optional shortened version.
abstract = "The work presented here is a novel biological approach for the compliant control of a robotic arm in real time (RT). We integrate a spiking cerebellar network at the core of a feedback control loop performing torque driven control. The spiking cerebellar controller provides torque commands allowing for accurate and coordinated arm movements. To compute these output motor commands, the spiking cerebellar controller receives the robot’s sensorial signals, the robot’s goal behaviour, and an instructive signal. These input signals are translated into a set of evolving spiking patterns, representing univocally a specific system state at every point of time. Spike Timing- Dependent Plasticity (STDP) is then supported, allowing for building adaptive control. The spiking cerebellar controller continuously adapts the torque commands provided to the robot from experience as STDP is deployed. Adaptive torque commands, in turn, help the spiking cerebellar controller to cope with built-in elastic elements within the robot’s actuators mimicking human muscles (inherently elastic). We propose a natural integration of a bio-inspired control scheme, based on the cerebellum, with a compliant robot. We prove that our compliant approach outperforms the accuracy of the default factory-installed position control in a set of tasks used for addressing cerebellar motor behaviour: controlling six degrees of freedom (DoF) in (i) smooth movements, (ii) fast ballistic movements, and (iii) unstructured scenario compliant movements."
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
tags = ["EDLUT", "Compliant robots"]

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
url_custom = [{name = "Journal", url = "https://ieeexplore.ieee.org/document/8880621" }]

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

