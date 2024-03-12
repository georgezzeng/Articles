---
title: Using HTC expanded scale of research using noninvasive measurements of tendons and ligaments

author: Sarah Matysiak

publish_on:
  - htcondor
  - path
  - osg
  - chtc
  
type: user

canonical_url:  https://chtc.cs.wisc.edu/adjacent-tissues-paper.html

image:
  path: https://raw.githubusercontent.com/CHTC/Articles/main/images/jonblank.jpg
  alt: Jonathon Blank, a co-author of the paper
  
excerpt: With this technique and the computing power of high throughput computing (HTC) combined, researchers can obtain thousands of simulations to study the pathology of tendons and ligaments.

---
**With this technique and the computing power of high throughput computing (HTC) combined, researchers can obtain thousands of simulations to study the pathology of tendons 
and ligaments.**

  

A recent paper published in the [Journal of the Mechanical Behavior of Biomedical Materials](https://www.sciencedirect.com/science/article/abs/pii/S1751616123004915) by former Ph.D. 
student in the Department of Mechanical Engineering (and current post-doctoral researcher at the University of Pennsylvania)
[Jonathon Blank](https://www.med.upenn.edu/orl/personnel/jonathon-blank-ph-d.html) and John Bollinger Chair of Mechanical Engineering
[Darryl Thelen](https://directory.engr.wisc.edu/me/faculty/thelen_darryl/) used the [Center for High Throughput Computing (CHTC)](https://chtc.cs.wisc.edu/) to obtain their results. 
Results that, Blank says, would not have been obtained at the same scale without HTC. “[This project], and a number of other projects, would have had a very small snapshot of the 
problem at hand, which would not have allowed me to obtain the understanding of shear waves that I did. Throughout my time at UW, I ran tens of thousands of simulations — probably 
even hundreds of thousands.”

  <figure class="figure float-end" style="margin-left: 1em; width: 250px;">
  <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/jonblank.jpg' class="figure-img img-fluid rounded" alt="Post-doctoral researcher at the University of Pennsylvania Jonathon Blank." width="250px">
  <figcaption class="figure-caption">Post-doctoral researcher at the University of Pennsylvania Jonathon Blank.<br/></figcaption>
</figure>

Using noninvasive sensors called shear wave tensiometers, researchers on this project applied HTC to study tendon structure and function. Currently, research in this field is hard 
to translate because most assessments of tendon and ligament structure-function relationships are performed on the benchtop in a lab, Blank explains. To translate the benchtop
experiments into studying tendons in humans, the researchers use tensiometers as a measurement tool, and this study developed from trying to better understand these measurements 
and how they can be applied to humans. “Tendons are very complex materials from an engineering perspective. When stretched, they can bear loads far exceeding your body weight, and 
interestingly, even though they serve their roles in transmitting force from muscle to bone really well, the mechanisms that give rise to injury and pathology in these tissues aren’t 
well understood.”
 
  <figure class="figure float-end" style="margin-left: 1em; width: 250px;">
  <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/darrylthelen.jpg' class="figure-img img-fluid rounded" alt="John Bollinger Chair of Mechanical Engineering Darryl Thelen." width="250px">
  <figcaption class="figure-caption">John Bollinger Chair of Mechanical Engineering Darryl Thelen.<br/></figcaption>
</figure>

In living organisms, researchers have used tensiometers to study the loading of muscles and tendons, including the triceps surae, which connects to the Achilles tendon, Blank notes. 
Since humans are variable regarding the size, stiffness, composition, and length of their tendons or ligaments, it’s “challenging to use a model to accurately represent a parameter 
space of human biomechanics in the real world. High throughput computing is particularly useful for our field just because we can readily express that variability at a large scale” 
through HTC. With Thelen and Orthopedics and Rehabilitation assistant professor [Josh Roth](https://directory.engr.wisc.edu/me/Faculty/Roth_Josh/), Blank developed a pipeline for 
simulating shear wave propagation in tendons and ligaments with HTC, which Blank and Thelen used in the paper.

  

With HTC, the researchers of this paper were able to further explore the mechanistic causes of changes in wave speed. “The advantage of this technique is being able to fully explore
an input space of different stiffnesses, geometries, microstructures, and applied forces. The advantage of the capabilities offered by the CHTC is that we can fill the entire input
space, not just between two data points, and thereby study changes in shear wave speed due to physiological factors and the mechanical underpinning driving those changes,” Blank 
elaborates.

  

It wasn’t challenging to implement, Blank states, since facilitators were readily available to help and meet with him. When he first started using HTC, Blank attended the CHTC 
office hours to get answers to his questions, even during COVID-19; during this time, there were also numerous one-on-one meetings. Having this backbone of support from the CHTC 
research facilitators propelled Blank’s research and made it much easier. “For a lot of modeling studies, you'll have this sparse input space where you change a couple of parameters 
and investigate the sensitivity of your model that way. But it’s hard to interpret what goes on in between, so the CHTC quite literally saved me a lot of time. There were some 
1,000 simulations in the paper, and HTC by scaling out the workload turned a couple thousand hours of simulation time into two or three hours of wall clock time. It’s a unique tool 
for this kind of research.”

  

The next step from this paper’s findings, Blank describes, is providing subject-specific measurements of wave speeds. This involves “understanding if when we use a tensiometer on 
someone’s Achilles tendon, for example, can we account for the tendon's shape, size, injury status, etcetera — all of these variables matter when measuring shear wave speeds.” 
Researchers from the lab can then use wearable tensiometers to measure tension in the Achilles and other tendons to study human movement in the real world.

  

From his CHTC-supported studies, Blank learned how to design computational research, diagnose different parameter spaces, and manage data. “For my field, it [HTC] is very important
because people are extremely variable — so our models should be too. The automation and capacity enabled by HTC makes it easy to understand whether our models are useful, and if 
they are, how best to tune them to inform human biomechanics,” Blank says.
