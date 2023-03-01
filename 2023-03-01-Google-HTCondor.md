---
title: Google Quantum Computing Utilizing HTCondor

author: Hannah Cheren

publish_on:
- chtc
- path
- htcondor

type: user

canonical_url: "https://chtc.cs.wisc.edu/htcondor-google-qvm.html"

image:
    path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/google-qvm.jpg"
    alt: Quantum AI Logo. Image from Quantum AI Product Manager Catherine Vollgraff Heidweiller’s research blog post.

description: |
    Google's launch of a Quantum Virtual Machine emulates the experience and results of programming one of Google's quantum computers, managed by an HTCondor system running in Google Cloud.
excerpt: |
    Google's launch of a Quantum Virtual Machine emulates the experience and results of programming one of Google's quantum computers, managed by an HTCondor system running in Google Cloud.

card_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/google-qvm.jpg"
card_alt: Quantum AI Logo. Image from Quantum AI Product Manager Catherine Vollgraff Heidweiller’s research blog post.

banner_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/google-qvm.jpg"
banner_alt: Quantum AI Logo. Image from Quantum AI Product Manager Catherine Vollgraff Heidweiller’s research blog post.
---
  ***Google's launch of a Quantum Virtual Machine emulates the experience and results of programming one of Google's quantum computers, managed by an HTCondor system running in Google Cloud.***

  <figure>
  <img class="w-100" src="https://raw.githubusercontent.com/CHTC/Articles/main/images/google-qvm.jpg" alt="Quantum AI Logo. Image from Quantum AI Product Manager Catherine Vollgraff Heidweiller’s research blog post."/>
  <figcaption class="figure-caption">Quantum AI Logo. Image from Quantum AI Product Manager Catherine Vollgraff Heidweiller’s research blog post.<br/></figcaption>
</figure>

  The CEO of Google and Alphabet, Sudar Pichai, tweeted out some thrilling news:
 
  “Excited to launch a Quantum Virtual Machine (QVM) which emulates the experience and results of programming one of our quantum computers. It will make it easier for researchers to prototype new algorithms and help students learn how to program a quantum computer.” – [Tweet](https://twitter.com/sundarpichai/status/1549448858282774528).
 
  Today’s “classical” computing systems, from laptops to large supercomputers, are built using circuit behavior defined by classical physics. Quantum computer circuity, still in the early phases of development, harnesses the laws of quantum mechanics to solve computing problems in new ways. Quantum computers offer exponential speedups – over 100 million times faster for specific issues – to produce groundbreaking results. However, quantum computing will require scientists and engineers to revisit many classical algorithms and develop new ones tailored to exploit the benefits of quantum processors. Therefore, the QVM is a helpful tool for quantum algorithms research.
 
  “The QVM is, in essence, a realistic simulation of a grid on our quantum hardware using classical computers,” Tom Downes, a consultant for High-Performance Computing (HPC) at Google Cloud, explains. Simulating a grid of qubits, the basic unit of quantum information, on a quantum processor requires many trajectory simulations of quantum noise. Downes explains, “quantum computers are noisy, so it is important to test and adjust your quantum circuits in realistic conditions so they can perform well and output the data you are looking for in your research problem. To virtualize a processor, the QVM uses the noise data and topology of Google's real hardware.” This grid size determines whether a researcher can use their laptop or require a setup utilizing many classical computers to power the simulation. Essentially, research on the QVM is "proof of concept" research.
 
  To enable researchers to test their algorithms on a larger grid of qubits, Google utilized the [HTCondor Software Suite](https://htcondor.org) (HTCSS) to organize the capacity of many classical computers to run multiple simulations of a quantum circuit simultaneously. The HTCondor Software Suite enables researchers to easily harness the collective computing power of many classical computers and submit and manage large numbers of computing jobs. Today, HTCSS is used at universities, government labs, and commercial organizations worldwide, including within Google’s own Google Cloud Platform, to power QVM.  Downes details, “this ability to test on a 32-qubit grid can extrapolate its performance to a non-simulatable grid more feasible.”
 
  The new [Google Quantum AI tutorial](https://quantumai.google/qsim/tutorials/multinode) shows users how to use the Cloud HPC Toolkit, which makes it easy for new users to deploy HTCondor pools in Google Cloud. Downes describes that the tutorial “provides the basic elements of an HTCondor pool: a central manager, an access point, and a pool of execute points that scale in size to work through the job queue.”
 
  The tutorial by Google describes how to:
- Use terraform to deploy an HTCondor cluster in the Google Cloud
- Run a multi-node quantum computing simulation using HTCondor
- Query cluster information and monitor running jobs in HTCondor
- Use terraform to destroy the cluster

 Please visit [this website](https://blog.google/technology/research/our-new-quantum-virtual-machine-will-accelerate-research-and-help-people-learn-quantum-computing/) for more information about the Quantum Virtual Machine and [how researchers can use HTCondor for multinode quantum simulations](https://quantumai.google/qsim/tutorials/multinode).
