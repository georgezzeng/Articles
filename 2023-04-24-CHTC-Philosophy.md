---
title: The CHTC Philosophy of High Throughput Computing – A Talk by Greg Thain

author: Hannah Cheren

publish_on:
- chtc
- path
- htcondor
- osg

type: news

canonical_url: "https://chtc.cs.wisc.edu/chtc-philosophy.html"

image:
path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-philosophy-banner.jpg"
alt: Image from Greg Thain’s CHTC Philosophy of High Throughput Computing slideshow.

description: |
    HTCondor Core Developer Greg Thain spoke to UW faculty and researchers about research computing and the missions and goals of the Center for High Throughput Computing (CHTC).
excerpt: |
    HTCondor Core Developer Greg Thain spoke to UW faculty and researchers about research computing and the missions and goals of the Center for High Throughput Computing (CHTC).

card_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-philosophy-banner.png"
card_alt: Image from Greg Thain’s CHTC Philosophy of High Throughput Computing slideshow.

banner_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-philosophy-banner.png"
banner_alt: Image from Greg Thain’s CHTC Philosophy of High Throughput Computing slideshow.
---
  ***HTCondor Core Developer Greg Thain spoke to UW faculty and researchers about research computing and the missions and goals of the Center for High Throughput Computing (CHTC).***

<figure>
  <img class="w-100" src="https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-philosophy-banner.jpg" alt="Photo credits: Greg Thain’s CHTC Philosophy of High Throughput Computing slideshow."/>
  <figcaption class="figure-caption">Photo credits: Greg Thain’s CHTC Philosophy of High Throughput Computing slideshow.<br/></figcaption>
</figure>

[The Center for High Throughput Computing](https://chtc.cs.wisc.edu/) (CHTC)  is proud to be home to a breadth of research on campus, with over 300 projects and 20 million core hours used by departments on the University of Wisconsin-Madison campus, ranging from the College of Agriculture and Life Sciences (CALS) to the School of Education, School of Pharmacy, and many more. “The CHTC is known best for being a place to run lots of fast jobs for free, to which we hope to continue democratizing computing across the campus,” Greg Thain began in his talks to UW-Madison researchers and staff on March 9 and 17, organized by UW-Madison Chief Technology Officer Todd Shechter.

“We like to think of the CHTC like the UW Hospital,” Thain explained, “like the hospital’s main purpose is to train the next generation of health professionals and conduct medical research. In the same way, the CHTC is our research laboratory and is where others can come and conduct their research; we do both research and provide a service.”

The main asset leveraged by the CHTC is research computing. “Research computing consists of research that happens to use computing and research about computing,” Thain explained, “both of which start and end with people.” Thain then described the two phases researchers go through when they approach the CHTC for help; “first, they seek assistance and guidance on a problem they’re currently facing. Second, they realize they can do something revolutionary with high throughput computing (HTC).”

A component of research computing using the CHTC tailored to scientists and researchers is that they don’t have to spend time supervising their programs running. Users can configure an [HTCondor Access Point](https://osg-htc.org/docs/submit/osg-flock/) to manage all their work, allowing them to essentially “submit it and forget it.” This compute system is similar to others in that any user can understand it and have it be reliable, “except ours has the extra touch of being a ‘submit it and forget it’ system,” Thain clarified. 

Similarly, the CHTC also created software for where the work runs, called an HTCondor Execution Point (EP). These Execution Points may be machines owned by other researcher providers and have different policies.

Both researchers and research providers may have constraints; the goal then of HTCondor is to “manage and maintain these restraints; there are many users and researcher providers in the real world, and the CHTC is currently working on optimizing these individuals' wants and needs.”

“This is a distributed problem,” Thain continued, “not because of the machines; it’s distributed because of the people.” Having distributed authority as opposed to distributed machines means that tools and policies are distributed.

The implicit assumption is that all work can be divided into smaller, mostly independent jobs. In this way, “the goal is to optimize the time to finish running these jobs instead of the time to run a single one; to do this, we want to break up the jobs as much as possible so they can run in parallel,” Thain explained. The implication of this is there are a lot of different jobs, and how difficult it is to break them up varies. 

  <figure class="figure float-end" style="margin-left: 1em; width: 250px;">
  <img src='https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-facilitation.jpeg' class="figure-img img-fluid rounded" alt="Research Computing Facilitator Christina Koch with a researcher." width="250px">
  <figcaption class="figure-caption">Research Computing Facilitator Christina Koch with a researcher.<br/></figcaption>
</figure>

To mitigate this, [research computing facilitators](https://chtc.cs.wisc.edu/CHTC-Facilitation.html) (RCFs) work with users and researchers to overcome their specific problems. RCFs are different from a traditional “help desk;” their role is to interface with graduate students, PIs, and other researchers and guide them to find the best-fit solution for their projects. RCFs must have a broad understanding of the basic sciences to communicate with the researchers, understand their work, and give them useful and reasonable recommendations and other technological approaches.  

“The CHTC’s top priority is always reliability, but with all this work going on, the dream for us is scalability,” Thain described. Ideally, more loads would increase performance; in reality, it boosts performance a little, and then it plateaus. To compensate for this, the CHTC goes out of its way to make access points more reliable. “Adding access points helps to scale and allows submission near the user.” Thain notes the mantra: “submit locally, run globally.” 

As the CHTC is our on-campus laboratory for experimenting with distributing computing, the [Open Science Pool](https://osg-htc.org/services/open_science_pool.html) (OSPool) is a bolder experiment expanding these idea onto a national scale of interconnected campuses.

  <figure>
  <img src="https://raw.githubusercontent.com/CHTC/Articles/main/images/chtc-map.jpg" alt="Map of campuses using OSPool computing resources."/>
  <figcaption class="figure-caption">Map of campuses using OSPool computing resources.<br/></figcaption>
</figure>

The OSG and subsequent OSPool provide computing access on a national level in the same way that someone can access an available machine locally. For example, if the machines on campus are unavailable or all being used, users can access machines in the greater OSG Consortium. “But at the end of the day, all this computing, storage and networking research is in service to the needs of people who rely on high throughput computing to accomplish their research,” Thain maintains. “We hope the OSPool will be an accelerator for a broad swath of researchers in all kinds of disciplines, from all over the United States.”

...

*The full slideshow can be found [here](https://github.com/GregThain/talks/blob/master/2023misc/CHTC%20for%20Research%20Computing.pptx). Please click [here](https://chtc.cs.wisc.edu/uw-research-computing/index.html) for more information about researching computing within the CHTC, or visit [this page](https://chtc.cs.wisc.edu/uw-research-computing/get-help.html) to contact our RCFs for any questions.*
