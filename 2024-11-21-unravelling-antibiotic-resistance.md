---
short_title: "Erik Wright: A Biologist Using High Throughput Computing"
title: "Erik Wright: A Biologist Using High Throughput Computing to Unravel Antibiotic Resistance"

author: Ria Dhingra and Bryna Goeking

publish_on:
  - htcondor
  - path
  - chtc
  - osg
  
type: user

canonical_url: https://chtc.cs.wisc.edu/unravelling-antibiotic-resistance.html

tag:
- chtc_featured_article

image:
  path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/antibiotic.jpeg"
  alt: Image of antibiotic
  
excerpt: In his quest to analyze antibiotic resistance, researcher Erik Wright has relied on capacity from the Open Science Pool (OSPool) for over twelve years, this Fall surpassing 25 million jobs over the last 12 months alone.
---

___“I have stuck with the OSPool because the access is unprecedented—the amount of compute time you can get, the number of jobs you can run at a time”___

_Erik Wright, Associate Professor of Biomedical Informatics at the University of Pittsburgh_



As bacterial infections evolve to develop resistance to drugs, it is critical to investigate methodologies to slow resistance and, potentially, even reverse it. In his quest to discover new antibiotics to counter resistance, Erik Wright’s project, BioMedInfo, aims to compare bacteria with resistant genomes by grouping them into a network of genes with related functions.



Originally studying natural antibiotic producers during his time at the University of Wisconsin Madison’s PhD program in Microbiology, Wright’s lab now examines how to shift from the existing treatment paradigm to one that mimics how antibiotics were originally deployed in nature. To do so, Wright compares the genomes of microorganisms, including both those that produce and resist antibiotics. It’s a task that requires an exorbitant amount of computing power, processing huge data sets as separate computing jobs. That’s where the work of [Open Science Pool](https://osg-htc.org/services/open_science_pool) (OSPool), an internationally recognized high throughput computing (HTC) resource comes in.



While pursuing his PhD in Microbiology at the University of Wisconsin-Madison, [Erik Wright](https://www.pmi.pitt.edu/people/ant-235) became familiar with the Center for High Throughput Computing (CHTC) and built relationships with the CHTC research facilitators who helped him organize tasks to run in a high throughput environment. Eight years after graduating with his PhD, Wright still relies on the OSPool for much of his work in genomics. Self-identifying as someone who found a niche of doing biology tied to computing, Wright sees significant value for HTC helping biologists investigate questions they can pursue with this capacity, stating that “without the right amount of capacity, some questions are kind of closed off.” While high throughput computing is not as commonly used in biology as it is in fields such as physics or astronomy, there is tremendous potential in this pairing, as HTC allows work that would otherwise take weeks on one centralized computer to be completed overnight. In the case of increasing biological genomes available to researchers like Wright, being able to process data quickly grants biologists the ability to respond quickly to the demands of their workload.



Currently, at the [University of Pittsburgh](https://www.pitt.edu/), Erik Wright is a leading [user](https://osg-htc.org/projects.html?project=BiomedInfo) of the OSPool by jobs and continues to adapt his work with the aid of CHTC research facilitators such as [Christina Koch](https://www.cs.wisc.edu/staff/koch-christina/). The OSPool harvests open capacity for its users from the idle space of contributing institutions. For users like Wright, this is beneficial because they can access enormous computing capacity. “I have stuck with the OSPool because the access is unprecedented — the amount of compute time you can get, the number of jobs you can run at a time,” he continued, “We don't have to ask permission for everything we do with it. We can just do it.”



In total, Wright’s project “BiomedInfo” has run over 25 million jobs, thanks to open capacity provided by 55 institutions sharing capacity with the OSPool. Wright notes that his workflows function best through a large number of short jobs, or “little tiny nutshells that can run in a minute or an hour.” These short jobs have contributed to Wright’s high utilization of the OSPool based on job count compared to other OSPool projects. In two weeks, he estimates that he can run around 120,000 jobs.



A recent effort made by Wright to address the deluge of biological data is the creation of a new algorithm, “[Clusterize](https://pubmed.ncbi.nlm.nih.gov/38589369/),” a tool that clusters biological sequences by their similarities. He says the algorithm is designed to help “reduce the redundancy in the data.” Building Clusterize required searching through different parameters for the best combination – a task ideally suited for HTC. For example, searching through five different values across 10 parameters results in 100,000 combinations. “You need 100,000 hours to try that one search to find the best possible combination,” Wright said. “It would take 1 computer 10 years to compute it, or it could be 1 year across 10 computers, or 3 weeks across the OSPool.”



Because of developments such as Clusterize, Wright has begun sending members of his lab to [OSG School](https://osg-htc.org/school-2024/), a week-long program for attendees to learn more about HTC. He notes that this experience has allowed members of his lab to become more than proficient with the OSPool, even implementing new solutions. One member implemented a Directed Acyclic Graph Manager ([DAGMan](https://portal.osg-htc.org/documentation/htc_workloads/automated_workflows/dagman-workflows/#introduction)) which allows current jobs to start new jobs. This is useful for Wright’s research, as new genomes are continuously being added to his files. Wright remarks, “I am addicted to the OSPool, so to speak, and I basically need it for my work.”



In the future, Wright aims to harness the power of growing data in biological research, as the number of genomes continues doubling approximately every few years. With access to OSPool, he hopes to address antibiotic resistance by continuing to work toward the discovery of new small molecules.



More on Erik Wright and his work mining genomes can be found in an [interview with him](https://chtc.cs.wisc.edu/mining-genomes.html) in the [Fall 2024 “Fearless Science” magazine](https://morgridge.org/wp-content/uploads/Fearless-Science-Mag-Fall-2024-Digital.pdf), published by [the Morgridge Institute for Research](https://morgridge.org/).

