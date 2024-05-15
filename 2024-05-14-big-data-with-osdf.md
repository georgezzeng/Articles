---
short_title: "Use of OSDF" 
title: "Use of OSDF"

author: Sarah Matysiak

publish_on:
- htcondor
- chtc
- osg
- path
- pelican

type: user

canonical_url:  https://pelicanplatform.org/user-stories/2024/05/14/big-data-with-osdf

image:
  path: https://raw.githubusercontent.com/CHTC/Articles/main/images/sites-use-of-osdf.png
  alt: HTCondor logo


excerpt: |
  Addressing the challenges of transferring large datasets with the OSDF Subheading: Aashish Tripathee has used multiple file transfer systems and experienced challenges with each before using the Open Science Data Federation (OSDF). With the OSDF, Tripathee has already seen an improvement in data transfers.
---

__Addressing the challenges of transferring large datasets with the OSDF Subheading: Aashish Tripathee has used multiple file transfer systems and experienced challenges with each before using the Open Science Data Federation (OSDF). With the OSDF, Tripathee has already seen an improvement in data transfers.__

<figure>
<img src="https://raw.githubusercontent.com/CHTC/Articles/main/images/sites-use-of-osdf.png" alt="Map of OSDF use"/>
<figcaption class="figure-caption">Map featuring the locations of current OSDF</figcaption>
</figure>


Map featuring the locations of current OSDF [caches in the federation](https://osg-htc.org/docs/data/stashcache/overview/#architecture).

When transferring big datasets, researchers may face numerous obstacles. University of Michigan Physics post-doctoral research fellow and [OSG David Swanson Awardee](https://osg-htc.org/spotlights/david-swanson-awardees-2023.html)  [Aashish Tripathee](https://lsa.umich.edu/physics/people/research-fellows/aashisht.html) faced these challenges too while conducting research on ripples in space-time, or continuous gravitational waves. Due to the sizing of his datasets, Tripathee needed to transfer over 30,000 gigabytes.

Over a year ago, Tripathee began using the [Open Science Data Federation (OSDF)](https://osg-htc.org/services/osdf) service that allows for the efficient delivery of data to compute as part of his workflows on the [OSPool](https://osg-htc.org/). The OSDF supports the sharing of datasets staged in autonomous “origins” that can move data to compute resources around the world through a global network of caches.

Before using the OSDF, Tripathee had experimented with a variety of data delivery systems. Though Tripathee saw successes with these systems, he was still encountering problems due to the type of data he was using and the volume he was transferring. Tripathee saw about 2–3% of his jobs failing because of completely halted transfers or far too slow transfers.

Upon switching to the OSDF, Tripathee saw significant improvements and noticed a significant number of jobs now run to completion while facing far fewer data transfer issues: With the OSDF, only about 0.5% of his jobs still show transfer issues.

<figure class="figure float-end" style="margin-left: 1em">
 <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/headshot-use-of-osdf.png' height="300" width="300" class="figure-img img-fluid rounded" alt="Physics post-doctoral research fellow at the University of Michigan Aashish Tripathee.">
  <figcaption class="figure-caption">Physics post-doctoral research fellow at <br>the University of Michigan Aashish Tripathee.</figcaption>
</figure>

The data transfer and storage problems Tripathee encountered are not isolated — difficulties in combining datasets and computing infrastructure are endemic across science. The OSDF is powered by the [Pelican Platform](https://pelicanplatform.org/), which is supported by a new $7.0 million grant from the [National Science Foundation (NSF)](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2331480) (OAC-2331480). The project is led by [Brian Bockelman](https://morgridge.org/profile/brian-bockelman/) from the Morgridge Institute for Research, director of the [Center for High Throughput Computing (CHTC)](https://chtc.cs.wisc.edu/) at University of Wisconsin–Madison Miron Livny, and [Frank Würthwein](https://www.sdsc.edu/research/researcher_spotlight/wuerthwein_frank.html), Executive Director of the San Diego Supercomputing Center at the University of California, San Diego. Through this project, the Pelican software will be enhanced to make the OSDF more reliable, easier to use, and more accessible to other fields of science.

The switch to the new platform was simple given its integration within the OSPool, which is closely related to the Pelican project at the CHTC. Tripathee reports the few changes he did make were well-documented in the [OSPool documentation](https://portal.osg-htc.org/documentation/htc_workloads/managing_data/osdf/), which “tells you exactly what you change depending on, for example, what submit node you're running from and where you want to store the data.” What it came down to for Tripathee, ultimately, was changing a few lines of code.

Tripathee is part of the [Laser Interferometer Gravitational-Wave Observatory (LIGO)](https://www.ligo.caltech.edu/) collaboration, which is starting to adopt the OSDF as part of its computing infrastructure, he mentions. While LIGO’s use of the OSDF is not yet widespread, Tripathee says he’s been using it for a couple of months and plans to continue with it since it’s been working well for him. As more LIGO members begin using the OSDF, Tripathee predicts that it is “definitely going to make a big difference in the jobs’ efficiency and reduce the number of wasted job hours.”

In May 2023, LIGO started its fourth observation run, meaning researchers, including Tripathee, will be able to analyze that data soon, which he looks forward to doing. Tripathee recalls that during the third observation round, the researchers experienced hiccups with file transfers, but now hopes retrieving the data from the OSDF should go more quickly and more smoothly. Tripathee anticipates fewer failed jobs and fewer wasted computing cycles. “As more and more universities start attaching servers, it's going to make it even faster and faster. I'm very excited about its prospects going into the future,” Tripathee says.

Sharing the results of the work in February 2024, Tripathree’s research from the third observation run was [published](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.109.043049#) in the “Physical Review D.” Searching for gravitational waves, Tripathree focused on isolated neutron stars, a potential source for these waves. Working alongside Dr. [Keith Riles](https://lsa.umich.edu/physics/people/faculty/kriles.html) of the University of Michigan, the duo determined the best upper limits for circular polarization — bringing researchers closer to detecting a continuous wave signal.

What he learned from the other services he used compared to the OSDF was that “for OSDF, people from all over the world are using it — it’s distributed everywhere, so it serves as a more general-purpose storage,” enabling his jobs to access from close by hardware instead of potentially retrieving it from across the world.

When working with big datasets that require a great amount of computing power, researchers — not so different from what Tripathee — will face obstacles that they need to jump over or duck under. Although going through may be the quickest and most direct solution to maneuver around the obstacle, this path often takes more resources. The OSDF wants to be that invaluable resource researchers will reach for when they need to push their way through that obstacle.
