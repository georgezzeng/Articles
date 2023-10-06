---
title: OSPool As a Tool for Advancing Research in Computational Chemistry

author: Shirley Obih

publish_on:
- osg
- path
- htcondor
- chtc

type: user

canonical_url: 
image:
  path: https://raw.githubusercontent.com/CHTC/Articles/main/images/ospool-comp.jpg
  alt: Microscope beside computer by Tima Miroshnichenko from Pexels.

description: Assistant Professor Eric Jonas uses OSG resources to understand the structure of molecules based on their measurements and derived properties.
excerpt: Assistant Professor Eric Jonas uses OSG resources to understand the structure of molecules based on their measurements and derived properties.

card_src: https://raw.githubusercontent.com/CHTC/Articles/main/images/ospool-comp.jpg
card_alt: Microscope beside computer by Tima Miroshnichenko from Pexels.

banner_src: https://raw.githubusercontent.com/CHTC/Articles/main/images/ospool-comp.jpg
banner_alt: Microscope beside computer by Tima Miroshnichenko from Pexels.
---

**Assistant Professor Eric Jonas uses OSG resources to understand the structure of molecules based on their measurements and derived properties.**
<figure>
  <img src="https://raw.githubusercontent.com/CHTC/Articles/main/images/ospool-comp.jpg" alt="Microscope beside computer by Tima Miroshnichenko from Pexels."/>
  <figcaption class="figure-caption">Microscope beside computer by Tima Miroshnichenko from Pexels.<br/></figcaption>
</figure>

<figure class="figure float-end" style="margin-left: 1em">
  <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/ericjonasheadshot.png' height="200" width="200" class="figure-img img-fluid rounded" alt="Eric Jonas, Assistant Professor at UChicago">
  <figcaption class="figure-caption">Eric Jonas, Assistant professor at UChicago<br/></figcaption>
</figure>

Picture this: You have just developed a model that predicts the properties of some molecules and plan to include this model in a section of a research paper. However, just a few days before the paper is to be published on your professional website, you discover an error in the data generation process, which requires you to compute your work again and quickly! 
This scenario was the case with Assistant Professor [Eric Jonas](https://jonaslab.uchicago.edu), who works in the Department of Computer Science at the University of Chicago (UChicago). 
While this process is normally tedious, he noted how the OSPool helped streamline the steps needed to regenerate results: “The OSPool made it easy to go back and regenerate the data set with about 70 million new molecules in just a matter of days.”

Although this was a fairly recent incident for Jonas, he is not new to high throughput computing or the OSPool. With usage reaching as far back as his graduate school days, Jonas has utilized resources ranging from cloud computing infrastructures like Amazon Web Services to the National Supercomputing Center for his work with biological signal acquisition, molecular inverse problems, machine learning, and other ways of exploiting scalable computation. 

He soon realized, though, that although these other resources could run large amounts of data in a relatively short time, they required a long, drawn-out sequence of actions to provide results – creating an application, waiting for it to be accepted, and then waiting in line for long periods for a job to run. Faced with this problem in 2021, Jonas found a solution with the [OSG Consortium](https://osg-htc.org) and its OSPool, OSG’s distributed pool of computing resources for running high-throughput jobs.

In April of 2021, he enlisted the help of [HTCondor](https://htcondor.com) and the OSPool to run pre-exising computations that allow for the generation of training data and the development of new machine learning techniques to determine molecular structures in mixtures, chemical structures in new plant species, and other related queries. 

Jonas’ decision to transition to the OSPool boiled down to three simple reasons:
Less red tape involved in getting started.
Better communication and assistance from staff.
Greater flexibility with running other people’s software to generate data for his specific research, which, in his words, are a much better fit for his specific research which would otherwise have been too computationally bulky to handle alone.

In terms of challenges with OSPool utilization, Jonas’ only point of concern is the amount of time it takes for code that has been uploaded to reach the OSPool. “It takes between 8 and 12 hours for that code to get to OSG. The time-consuming containerization process means that any bug in code that prevents it from running isn't discovered and resolved as quickly, and takes quite a while, sometimes overnight.”

He and his research team have since continued to utilize OSPool to generate output and share data with other users. They have even become advocates for the resource: “After we build our models, as a next step, we’re like, let’s run our model on the OSPool to allow the community (which constitutes the entirety of OSPool users) also to generate their datasets. I guess my goal, in a way, is to help OSG grow any way I can, whether that involves sharing my output with others or encouraging people to look into it more.”

Jonas spoke about how he hopes more people would take advantage of OSPool:
“We’re already working on expanding our use of it at UChicago, but I want even more people to know that OSPool is out there and to know what kind of jobs it's a good fit for because if it fits the kind of work you’re doing, it’s like having a superpower!”
