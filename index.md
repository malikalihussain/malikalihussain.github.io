---
layout: home3
title: Ali Raza
description: "Ali Raza's website"
tags: [Jekyll, theme, responsive, blog, template]
image:
  feature: trees.jpg
---

I am a PhD candidate in the [Department of Computer Science](http://www.bu.edu/cs/) at [Boston University](http://www.bu.edu). I joined CS@BU in Fall’17. 
<br />
<br />

At BU, I am working with [Prof. Orran Krieger](https://www.bu.edu/eng/profile/orran-krieger/). My area of interest is Operating Systems, specifically turning the Linux kernel into a unikernel. 
<br />
<br />

## Research Interests: Unikernel Linux (UKL) ##
Performance-sensitive applications require specialized behavior from the OS,
e.g., custom scheduler policies, high-speed I/O, direct access to hardware, etc.
Unikernels or library-OSes provide these benefits, but still, their adoption is
low in production environments. This is because they can't always match the
battle-tested code of general-purpose OSes, their development community, the
ecosystem of management, debugging, and profiling tools, and their wide hardware
support; all of which are required by modern applications. In my research, I
explore if it's possible to preserve all the properties of general-purpose OSes
while getting the performance advantages of unikernels. Can we integrate
unikernel techniques into a general-purpose OS? What would the performance
benefits be, if any? Can unmodified applications exploit these advantages? Can
all of this be done without massive code changes and redesigning the
general-purpose OS so the community can adopt the idea and take it further? To
answer these questions, we have built a prototype that demonstrates both a path
to integrate unikernel techniques in Linux (e.g., kernel-mode execution for
applications, highly optimized transitions between kernel and application code,
run-to-completion mode, shared stacks between application and kernel, link-time
optimization of kernel and application code, etc.) and that such techniques can
result in significant performance advantages. Unmodified applications, with a
re-compilation and link to a modified Linux kernel, show performance gains
(e.g., for Redis throughput by 12% & 99th tail latency by 11%). Further, expert
developers can modify the application to better exploit the new optimizations
for more significant gains (e.g., for Redis, throughput by 25% and 99th tail
latency by 22%). The changes to the Linux kernel are modest (1250 LoC).

## Latest News ##
- **Jun, 2022:** Full length Unikernel Linux (UKL) paper available on arxiv [here](https://arxiv.org/pdf/2206.00789.pdf) and code can be found [here](https://github.com/unikernelLinux/ukl).

- **Sep, 2021:** Gave a talk on **Unikernel Linux** at **DevConf.us** organized by Red Hat. The video for the talk can be found [here](https://www.youtube.com/watch?v=Hu268xq9gMk).

- **Sep, 2020:** Gave a talk on **Unikernel Linux** at **DevConf.us** organized by Red Hat. The video for the talk can be found [here](https://www.youtube.com/watch?v=_OV7o8yImYo).

- **Sep, 2020:** Gave a talk on **Unikernel Linux** at **Red Hat Research Day** organized by Red Hat. The video for the talk can be found [here](https://www.youtube.com/watch?v=rv3EXOKK7ew).

- **Aug, 2019:** Gave a talk on **Unikernel Linux** at **DevConf.us** organized by Red Hat in Boston, MA, USA. The video for the talk can be found [here](https://www.youtube.com/watch?v=PQvxq015Psw).

- **May 12, 2019:** Presented our paper **Unikernels: The Next Stage of Linux's Dominance** at **HotOS XVII**, The 17th Workshop on Hot Topics in Operating Systems, 2019 in Bertinoro, Italy.

- **Apr 2019:** Gave a talk on **Unikernel Linux** at **Red Hat Research Day** organized by Red Hat in Boston, MA, USA.

- **Mar 3, 2019:** Our paper **Unikernels: The Next Stage of Linux's Dominance** got accepted and is set to appear at **HotOS XVII**, The 17th Workshop on Hot Topics in Operating Systems, 2019 in Bertinoro, Italy.

- **Nov 3, 2018:** I presented our paper **Using SGX-Based Virtual Clones for IoT Security** at **IEEE NCA 2018** in Boston, MA, USA.

- **Oct 30, 2018:** Gave a talk and presented a poster on **Unikernel Linux** at **2018 MOC Annual Workshop** organized by Mass Open Cloud in Boston, MA, USA.

- **Sept, 2018:** Our short paper **Using SGX-Based Virtual Clones for IoT Security** got accepted at **IEEE NCA 2018** IEEE 17th International Symposium on Network Computing and Applications (NCA), Boston, MA, USA.

- **Aug 17, 2018:** Gave a talk on **Unikernel Linux** at **DevConf.us** organized by Red Hat in Boston, MA, USA. The video for the talk can be found [here](https://youtu.be/ltvXeolVnVE?t=3h57m40s).

- **Jul, 2018:** Our paper **A Secure Cloud with Minimal Provider Trust** got accepted at **HotCloud 2018** 10th {USENIX} Workshop on Hot Topics in Cloud Computing, Boston, MA, USA.

- **May, 2018:** Will be starting as a Research Intern at **Red Hat** at the Boston office. I will be working on Unikernel Linux with Ulrich Drepper, Richard Jones and Prof. Orran Krieger.

- **April 19, 2018:** I presented our paper **It’s all in the name: Why some urls are more vulnerable to typosquatting** at **IEEE INFOCOM 2018** in Honolulu, Hawaii, USA.

- **Jan, 2018:** Our paper **It’s all in the name: Why some urls are more vulnerable to typosquatting** got accepted at **IEEE INFOCOM 2018** IEEE Conference on Computer Communications, 2018, Honolulu, Hawaii, USA.

- **May, 2017:** Our paper **An Anomaly Detection Fabric for Clouds Based on Collaborative VM Communities** got accepted at **CCGrid 2017** Proceedings of the 17th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing, Madrid, Spain.

