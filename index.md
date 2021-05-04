---
layout: default
---

# About Me

I recently completed my PhD at Stanford University advised by Professor [Nick McKeown](http://yuba.stanford.edu/~nickm/) and am currently a postdoctoral scholar at Stanford.
Prior to my PhD, I received my bachelors degree in Engineering from Harvey Mudd College.

I am passionate about building high performance network systems by leveraging hardware/software co-design.
I am currently working on [the nanoPU]({{ site.baseurl }}/docs/nanoPU-arxiv.pdf), a novel CPU-NIC architecture designed to provide ultra low latency and high throughput.
The nanoPU moves the entire network stack into line-rate hardware: programmable transport, core selection, and thread scheduling.
It uses a novel register file network interface rather than the traditional DMA-based network interface in order to provide the lowest possible latency and most predictable performance.
We developed an [open source](https://github.com/l-nic/chipyard/wiki), end-to-end FPGA prototype that runs on AWS F1 instances using [Firesim](https://fires.im/).
The wire-to-wire latency through the nanoPU is just 69ns – an order of magnitude lower latency than state-of-the-art commercial NICs!
The nanoPU also enables single-digit microsecond 99% tail latencies and message processing throughput of over 100 Mrps per-core.
You can learn more about the nanoPU from our [paper]({{ site.baseurl }}/docs/nanoPU-arxiv.pdf) and this [30min talk](https://www.youtube.com/watch?v=Bu_nx5gLfmY&feature=youtu.be&ab_channel=OpenNetworkingFoundation).

## Research Interests

* Network Systems
* Computer Architecture
* Distributed Applications
* Domain Specific Hardware/Software Co-Design

## Education

* Ph.D. and M.S. in Electrical Engineering, 2021 --- **Stanford University**
* B.S. in Engineering, 2015 --- **Harvey Mudd College**

# Publications

[The nanoPU: Redesigning the CPU-Network Interface to Minimize RPC Tail Latency]({{ site.baseurl }}/docs/nanoPU-arxiv.pdf)  
**Stephen Ibanez**, Alex Mallery, Serhat Arslan, Theo Jepsen, Muhammad Shahbaz, Nick McKeown, and Changhoon Kim  
*To appear in USENIX OSDI 21*  
[Open source artifact](https://github.com/l-nic/chipyard/wiki)  
[30min Talk Recording](https://www.youtube.com/watch?v=Bu_nx5gLfmY&feature=youtu.be&ab_channel=OpenNetworkingFoundation)

---

Zerializer: Towards Zero-Copy Serialization  
Adam Wolnikowski, **Stephen Ibanez**, Jonathan Stone, Changhoon Kim, Rajit Manohar, Robert Soule  
*To appear in HotOS 2021*

---

[The Case for a Network Fast Path to the CPU]({{ site.baseurl }}/docs/lnic.pdf)  
**Stephen Ibanez**, Muhammad Shahbaz, and Nick McKeown  
*HotNets 2019*

---

[Event-Driven Packet Processing]({{ site.baseurl }}/docs/event-driven-pisa.pdf)  
**Stephen Ibanez**, Gianni Antichi, Gordon Brebner, and Nick McKeown  
*HotNets 2019*  
[Open source artifact](https://github.com/NetFPGA/P4-NetFPGA-public/wiki/Workflow-Overview#sume-event-switch-architecture)

---

[The P4-NetFPGA workflow for line-rate packet processing]({{ site.baseurl }}/docs/p4-netfpga.pdf)  
**Stephen Ibanez**, Gordon Brebner, Nick McKeown, and Noa Zilberman  
*FPGA 2019*  
[Open source artifact](https://github.com/NetFPGA/P4-NetFPGA-public/wiki)

---

[s-PERC: A distributed algorithm to calculate max-min fair rates without per-flow state]({{ site.baseurl }}/docs/s-PERC.pdf)  
Lavanya Jose, **Stephen Ibanez**, Mohammad Alizadeh, and Nick McKeown  
*SIGMETRICS 2019*  
[Open source artifact](https://github.com/lavanyaj/perc)

---

# Teaching Experience

[CS344: Build an Internet Router](https://cs344-stanford.github.io/), Stanford University
* Spring 2018, Spring 2019

P4 Language Tutorial Instructor
* P4 Developer Day, Spring 2019
* SIGCOMM, 2019
* FPGA Conference, 2018
* P4 Developer Day, Spring 2018
* East Coast P4 Developer Day, 2018
* P4 Developer Day, Fall 2017

P4-NetFPGA Tutorial Instructor
* FPGA Conference, 2019
* SIGCOMM, 2017
* NetFPGA Summer Camp, University of Cambridge, 2017
* P4 Developer Day, Spring 2017
