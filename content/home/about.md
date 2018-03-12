+++
# About/Biography widget.
widget = "about"
active = true
date = "2018-02-16T00:00:00"

# Order that this section will appear in.
weight = 5

# List your academic interests.
#[interests]
#  interests = [
#    "Computational Neuroscience",
#    "Cerebellum",
#    "Neurorobotics",
#    "Learning"
#  ]

# List your qualifications (such as academic degrees).
#[[education.courses]]
#  course = "PhD in Computational Neuroscience"
#  institution = "University of Granada"
#  year = 2011

#[[education.courses]]
#  course = "MSc in Computer Architecture and Networks"
#  institution = "University of Granada"
#  year = 2007

#[[education.courses]]
#  course = "MSc in Computer Science"
#  institution = "University of Granada"
#  year = 2006
 
+++

The Computational Neuroscience and Neurorobotics Group is part of the [Computer Architecture and Technology Department](https://atc.ugr.es/) at [University of Granada](https://www.ugr.es). The group is leaded by Prof. Eduardo Ros. Our group develops and uses computational tools to gain understanding on brain information processing and motor control.

We are experts in simulating neural centres (such as cerebellum, inferior olive, basal ganglia and the visual system) both off-line (in large parallel computers) or in real-time (towards embedded simulations) with a robot on the loop (closed perception-action loops).

Among other potential application domains, rehabilitation, control schemes for robots interacting safely with humans and reverse engineering of human brain system are our focus.

Our value proposition is the following:

* Computational Neuroscience. We simulate biologically plausible neural systems (at different levels of detail) to contrast working hypotheses related to these centres and evaluate how their computational features are supported by the physiological substrate. We can do large scale simulations (off-line) and medium scale simulations (for embedded systems and interacting with robotics). For this purpose, we can use widely used simulators such as NEST or our own real-time simulator
([EDLUT](https://github.com/EduardoRosLab/edlut)) optimized for real-time (making intensive use of parallel computing at the CPU and GPU levels).

* Neurorobotics. Robots with low power actuators can be designed to be inherently safe. In addition, robotics devices made with soft and flexible materials are becoming more frequent in research and industry. But in this case, the dynamics (and even the kinematics) of the plant may not have an analytic reference model. Furthermore, some of these actuators or the plant itself may have long perception or action delays making standard control schemes challenging. In this framework, biology is still far away of our best solution. We use biologically inspired adaptive control (similarly to what the cerebellum is actually doing) based on model acquisition and retrieval. This can be embedded in the control loops for creating safer robots.
