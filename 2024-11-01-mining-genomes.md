---
title: Mining millions of genomes for the next powerful antibiotic

author: Morgridge Communications

publish_on:
  - htcondor
  - path
  - chtc
  - osg
  
type: user

canonical_url: https://chtc.cs.wisc.edu/mining-genomes.html

tag:
- chtc_featured_article

image:
  path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/erik-wright.png"
  alt: Image of Erik Wright
  
excerpt: Interview of Erik Wright, assistant professor of biomedical informatics at the University of Pittsburgh and his use of the OSPool.

---

Erik Wright, assistant professor of
biomedical informatics at the University of
Pittsburgh, spoke to Fearless Science Magazine
about how his quest to discover new antibiotics
to counter resistance — and how that pursuit
has made him biology’s No. 1 user of the Open
Science Pool for advanced computing.

#### How did an electrical engineer end up as a microbiologist?

After a few years working at Apple as an electrical
engineer, I decided to go back to grad school and
switched to environmental engineering. Studying
water and wastewater treatment introduced me to
microbes and bacteria and I just fell in love with it. I
shifted to microbiology for my Ph.D. at UW–Madison,
and the prerequisite classes felt like I was being
fed gold nuggets of information. There’s this whole
invisible universe out there of microorganisms that I
was completely oblivious to. I found a little niche for
myself doing biology tied to computing. And now I
run what I call soggy lab, which is a hybrid wet and
dry lab together.

#### Why did you decide to make antibiotic resistance the focus of your research work?

The bugs evolve resistance to our drugs. It’s a really
hard thing to counter, and it’s especially hard to
reverse. I like that it’s so difficult, that’s probably
the main draw. I live and breathe the idea that
resistance is something that can be stopped and
reversed. I began to study the natural antibiotic producers, the
microorganisms that we get about 70% of our antibiotics from.
These organisms have been naturally producing antibiotics for
about half a billion years at least, and because they’re mostly
bacteria, they’ve also figured out how to resist them.

#### What are the areas of focus for your lab?

We’re one of the few labs that studies what strategies bacteria
use to avoid resistance. Then we want to understand how to
use to avoid resistance. Then we want to understand how to
bring that strategy to the clinic and scale it up.
We are studying durability, to understand why some antibiotics
have been able to avoid resistance. And we are exploring how we
can prescribe them in a multidrug cocktail such as for HIV and
tuberculosis. The vast majority of the antibiotics we give are pure
compounds in a high dose, but that’s only one hurdle for the bug
to jump over, we want to present them with many hurdles.
We’re trying to figure out how to work with the existing available
pool of drugs to do something that’s better than what we
currently do. And we think that by changing the way we treat
patients — mimicking the biology that currently exists — then
maybe we can figure out a more sustainable solution.

#### You are the number one biology user of high throughput computing with the Open Science Pool. How do you integrate computational approaches to tackle antibiotic resistance?

I had the extreme advantage of being part of the Wisconsin
Institute for Discovery at UW–Madison, so I was an early adopter
and that has completely changed my career. I’ve been using the
Open Science Pool for 12 years and we simply could not reach
the kind of computing capacity we need without it. Because it’s
open, we don’t have to write grant proposals, which allows us to
do a lot of exploratory work. I can’t overstate how much that is
worth to me. It is also set up in a way amenable to my research.
Instead of shared memory computing, the OS Pool is set up
with a distributed memory. We like to split up our work into tiny
compartments that each last an hour, so we hit something like 17
million jobs last year.

#### Why is your lab so computationally intensive?

The main thing my lab’s doing is comparing genomes by
processing huge data sets in millions of separate computing
jobs on the grid. We have access to about 2 million bacterial
genomes, and we have developed software that can draw on
thousands of computers to quickly compare new genomes to
those that already exist. Then other computers store the data,
and thousands more process and analyze the results — all
through this gigantic set of grid jobs that is always running.
We end up having groups of genes that are the same gene
across different organisms, and then we build software that tells
us which genes work together. From that we can do things like
find which groups make natural products like antibiotics.
We aim to build an ecosystem that will live on the grid, which
is a little bit of a wild idea, but it will continuously update and
compute new genomes and add them into a giant comparison
of all genomes versus all genomes. What we’re ultimately
going to do is take those groups of genes that work together,
transplant them into a host organism, and then turn them on and
see what product they make.

#### What would a dream outcome look like from the research that you’re doing now?

I would like to discover new small molecules that no one has
known about. And to find totally new drugs if I could. We’ve
developed ways of finding genes that work together, that
nobody’s seen before. But we have no idea what antibiotic or
other compound that makes. It’s on the order of millions of
different possible compounds and it’s a dream to bring some of
those to reality. We have developed ways of handling hundreds
of thousands of genomes, approaching millions, so this is very
much possible.

This feature was originally published by the Morgridge Institute for Research in their [“Fearless Science” magazine, Fall 2024](https://morgridge.org/wp-content/uploads/Fearless-Science-Mag-Fall-2024-Digital.pdf).

