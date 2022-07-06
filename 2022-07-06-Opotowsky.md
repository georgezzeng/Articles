---
title: "Expediting Nuclear Forensics and Security Using High Through Computing"

author: Hannah Cheren

publish_on:
  - htcondor
  - path
  - chtc
  
type: user

canonical_url: https://htcondor.org/featured-users/2022-07-06-Opotowsky.html

image:
  path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/Opotowsky-card.jpeg"
  alt: Photo by Dan Myers on Unsplash
  
description: Arrielle C. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, describes how she utilized high throughput computing to expedite nuclear forensics investigations. 
excerpt: Arrielle C. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, describes how she utilized high throughput computing to expedite nuclear forensics investigations. 

card_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/Opotowsky-card.jpeg"
card_alt: Arrielle C. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, describes how she utilized high throughput computing to expedite nuclear forensics investigations. 

banner_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/Opotowsky-card.jpeg"
banner_alt: Arrielle C. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, describes how she utilized high throughput computing to expedite nuclear forensics investigations. 
---
  ***Arrielle C. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, describes how she utilized high throughput computing to expedite nuclear forensics investigations.***

  <figure>
  <img src="https://raw.githubusercontent.com/CHTC/Articles/main/images/Opotowsky-card.jpeg" alt="Computer rendering of DNA."/>
  <figcaption class="figure-caption">Photo by Dan Myers <a href="https://unsplash.com/photos/xXbQIrWH2_A">on Unsplash.</a><br/></figcaption>
</figure>

  <figure class="figure float-end" style="margin-left: 1em; width: 250px;">
  <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/Opotowsky-headshot.png' class="figure-img img-fluid rounded" alt="Arrielle C. Opotowsky, 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics" width="250px">
  <figcaption class="figure-caption">Arrielle C. Opotowsky, 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics<br/></figcaption>
</figure>
  
  "Each year, there can be from two to twenty incidents related to the malicious use of nuclear materials,” including theft, sabotage, illegal transfer, and even terrorism, [Arrielle C. Opotowsky](http://scifun.org/Thesis_Awards/opotowsky.html) direly warned. Opotowsky, a 2021 Ph.D. graduate from the University of Wisconsin-Madison's Department of Engineering Physics, immediately grabbed the audience’s attention at [HTCondor Week 2022](https://agenda.hep.wisc.edu/event/1733/timetable/?view=standard). 

  Opotowsky's work focuses on nuclear forensics. Preventing nuclear terrorism is the primary concern of nuclear security, and nuclear forensics is “the *response* side to a nuclear event occurring,” Opotowsky explains. Typically in a nuclear forensics investigation, specific measurements need to be processed; unfortunately, some of these measurements can take months to process. Opotowsky calls this “slow measure” general mass spectrometry. Although this measurement can help point investigators in the right direction, they wouldn’t be able to do until long after the incident has occurred.

  In trying to learn how she could expedite a nuclear forensics investigation, Opotowsky wanted to see if Gamma Spectroscopy, a “fast measurement”, could be the solution. This measure can potentially point investigators in the right direction, but in days rather than months.

  To test whether this “fast measurement” could expedite a nuclear forensics investigation compared to a “slow measurement”, Opotowsky created a workflow and compared the two measurements.

  While Opotowsky was a graduate student working on this problem, the workflow she created was running on her personal computer and suddenly stopped working. In a panic, she went to her advisor, [Paul Wilson](https://directory.engr.wisc.edu/ep/faculty/wilson_paul), for help, and he pointed her to the UW-Madison Center for High Throughput Computing (CHTC).

  CHTC Research Computing Facilitators came to her aid, and “the support was phenomenal – there was a one-on-one introduction and a tutorial and incredible help via emails and office hours…I had a ton of help along the way.”

  She needed capacity from the CHTC because she used a machine-learning workflow and 10s of case variations. She had a relatively large training database because she used several algorithms and hyperparameter variations and wanted to predict several labels. The sheer magnitude of these training databases is the leading reason why Opotowsky needed the services of the CHTC.

  She used two computation categories, the second of which required a specific capability offered by the CHTC - the ability to scale out a large problem into an ensemble of smaller jobs running in parallel. With 500,000 total entries in the databases and a limit of 10,000 jobs per case submission, Opotowsky split the computations into fifty calculations per job. This method resulted in lower memory needs per job, each taking only a few minutes to run.

  “I don’t think my research would have been possible” without HTC, Opotowsky noted as she reflected on how the CHTC impacted her research. “The main component of my research driving my need [for the CHTC] was the size of my database. It would’ve had to be smaller, have fewer parameter variations, and that ‘fast’ measurement was like a ‘real-world’ scenario; I wouldn’t have been able to have that.” 

  Little did Opotowsky know that her experience using HTC would also benefit her professionally. Having HTC experience has helped Opotowsky in job interviews and securing her current position in nuclear security. As a nuclear methods software engineer, “knowledge of designing code and interacting with job submission systems is something I use all the time,” she comments, “[learning HTC] was a wonderful experience to gain” from both a researcher and professional point of view. 


...

  *Watch a video recording of Arrielle C. Opotowsky’s talk at HTCondor Week 2022, and browse her [slides](https://agenda.hep.wisc.edu/event/1733/contributions/25511/attachments/8299/9577/HTCondorWeek_AOpotowsky.pdf).*
  
  <iframe width="100%" height="315" src="https://www.youtube.com/embed/60lQS9dH0ag" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
