---
layout: page
permalink: /research/
title: My Research
tags: [research]
modified: 8-7-2014
comments: false
---

### Unikernel Linux ###

My research is based in the field of Operating Systems, with a focus on Unikernels. Unikernels are small, lightweight, single address space operating systems, with the kernel included as a library with the application. Since unikernels run a single application, there is no sharing or competition for resources among different applications, it has been shown that unikernels give performance and security benefits as compared to normal kernels. I am interested in turning the Linux kernel into a unikernel. This will result in 1) a unikernel which can easily be compiled for any application, 2) a unikernel which uses the battle tested Linux code and thus is production ready, 3) once upstreamed, the entire Linux developer community to maintain and develop this unikernel, 4) a way to get performance and security benefits of unikernels for applications which normally run on vanilla Linux. I am interested in many research aspects that arise from this e.g., studying the advantages of bypassing syscalls and directly invoking internal kernel functionality, impact of link time optimizations across application/kernel boundaries, benefits of profile driven optimizations on performance, and performance gains from simplification of user level synchronization mechanisms, etc. These research will lead us to create an application specific, stripped down unikernel from the Linux code base.

Github repo for the project can be found [here](https://github.com/razaaliraza/ukl).