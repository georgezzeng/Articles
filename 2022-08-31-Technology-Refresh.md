---
title: Technology Refresh

author: Christina Koch

publish_on:
  - chtc

type: news

canonical_url: "https://chtc.cs.wisc.edu/Technology-Refresh.html"

image:
    path: "https://raw.githubusercontent.com/CHTC/Articles/main/images/PATh_Facility_Preview.jpeg"
    alt: Image of Servers

description: |
    Thanks to the generous support of the Office of the Vice Chancellor for Research and Graduate 
    Education with funding from the Wisconsin Alumni Research Foundation, CHTC has been able 
    to execute a major refresh of hardware.  This provided 207 new servers for our systems, 
    representing over 40,000 batch slots of computing capacity.
excerpt: |
    Thanks to the generous support of the Office of the Vice Chancellor for Research and Graduate
    Education with funding from the Wisconsin Alumni Research Foundation, CHTC has been able
    to execute a major refresh of hardware.  This provided 207 new servers for our systems,
    representing over 40,000 batch slots of computing capacity.

card_src: "https://raw.githubusercontent.com/CHTC/Articles/main/images/PATh_Facility_Preview.jpeg"
card_alt: Image of Servers
---

Thanks to the generous support of the Office of the Vice Chancellor for Research and Graduate Education with funding from the Wisconsin Alumni Research Foundation, CHTC has been able to execute a major refresh of hardware.  This provided 207 new servers for our systems, representing over 40,000 batch slots of computing capacity. Most of this hardware arrived over the summer and we have started adding them to CHTC systems.

Continue reading to learn more about the types of servers we are adding and how to access them.

### HTC System

On the HTC system, we are adding 167 servers of new capacity, representing 36,352 job slots and 40 high-end GPU cards.

The new servers will be running CentOS Linux 8 – CHTC users should see our website page about how to test your jobs and
take advantage of servers running CentOS Stream 8. Details on user actions needed for this change can be found on the
[OS transition page](/uw-research-computing/os-transition-htc.html).

#### New Server specs

##### PowerEdge ​R6525

- 157 servers with 128 cores / 256 job slots using the AMD Epyc 7763 processor
- 512 GB RAM per server

##### PowerEdge XE8545

- 10 servers, each with four A100 SXM4 80GB GPU cards
- 128 cores per server
- 512GB RAM per server

### HPC Cluster

For the HPC cluster, we are adding 40 servers representing 5,120 cores. These servers have arrived but have not yet been added to the HPC cluster. In most cases, when we add them, they will form a new partition and displace some of our oldest servers, currently in the “univ2” partition.

#### New server specs:

##### Dell Poweredge R6525

- 128 cores using the AMD Epyc 7763 processor
- 512GB of memory

Users interested in early access to AMD processors before all 40 servers are installed should contact CHTC at [chtc@cs.wisc.edu](chtc@cs.wisc.edu).

We have also obtained hardware and network infrastructure to completely replace the HPC cluster’s underlying file system and infiniband network fabric. We will be sending more updates to the chtc-users mailing list as we schedule specific transition dates for these major cluster components. 
