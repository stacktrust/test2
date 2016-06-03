---
layout: page
title: Summit
permalink: /summit/
---

### Program Summary

 * [Day 1 Presentations](#presentations): 8:45am - 5:15pm, Tuesday 7th June, 2016
 * Evening Reception: 5:30pm - 7:00pm, Tuesday 7th June, 2016
 * [Day 2 Discussions](#discussions): 9:00am - 5:00pm, Wednesday 8th June, 2016
 * Devices permitted, wireless internet and some power outlets available
 * Breakfast, Lunch & Snack will be served
 * [Directions](#location)
 
## 2016 OpenXT Summit

The inaugural OpenXT Summit brings together developers and ecosystem participants for a 2-day conference in Fairfax, VA, USA on June 7-8, 2016.   The event is hosted by Intel Corporation.  The audience for this event includes kernel and application developers, hardware designers, system integrators and security architects.

Released as open-source software in 2014, OpenXT stands on the shoulders of the Xen Project, OpenEmbedded Linux and Citrix XenClient XT.  It is optimized for hardware-assisted virtualization with an IOMMU and a TPM.  Guest operating systems include Windows, Linux and FreeBSD. 

OpenXT enables loose coupling of open-source and proprietary software components, verifiable measurements of hardware and software, and verified launch of derivative products.  It has been used to develop centrally managed software appliances that isolate high-risk workloads, networks and devices. 

The 2016 OpenXT Summit will chart the evolution of OpenXT from cross-domain endpoint virtualization to an extensible systems innovation platform, enabling derivative products to make security assurances for diverse hardware, markets and use cases.

### Registration

There is no fee for attendance, but space is limited and building security will check identification against the list of registered attendees.  To reserve a seat, please email [summit2016@openxt.org](mailto:summit2016@openxt.org?Subject=OpenXT%20Summit%20Registration,%20June%207-8,%20Fairfax,%20VA) with the following information:

 * First and last name
 * Organizational affiliation
 * Publish name and organization in public attendee list: Yes/No

### <a name="location"></a> Location

The event will take place at Intel Corporation, [4100 Monument Corner Drive](https://goo.gl/maps/hqaSDhDshx62), Suite 540, Fairfax, VA 22030.

### Transportation

 * Visitor parking: free, available on-site
 * 6 miles, Washington Metro station, Vienna/Fairfax-GMU (Orange Line)
 * 12 miles, Dulles (IAD) Airport
 * 22 miles, Washington Reagan (DCA) Airport
 * 24 miles, Amtrak Union Station

### <a name="presentations"></a> Sponsors

<a href="http://intel.com"><img src="{{ site.baseurl }}/images/intel.png" width="200"></a>

### Presentation Agenda: Tuesday 7 June, 2016

 * 08:00 Breakfast

 * 08:45 Introduction
 
 * 09:00 OpenXT Architecture, *Christopher Clark*, BAE Systems
 
 > A whistle-stop tour of the structure of an OpenXT system today: an overview of the primary technology and distinguishing properties of the platform.  This presentation will cover hardware, the Xen hypervisor and other software used by an OpenXT system.  It will provide a shared foundation for OpenXT Summit discussions.
 
 * 09:30 OpenXT Platform, *Ross Philipson*, Assured Information Security
 
 > Can OpenXT be moved towards an extensible platform model? The key concepts to be covered are, (a) minimal base platform with core security attributes central to OpenXT, (b) layers that enable the base platform to be easily extended and customized.
 
 * 10:00 Secure Virtual Platform Research, *Peter Loscocco*, National Security Agency
 
 > NSA has a long history of investing in research focused on advancing the security of computer systems. Virtualization and Trusted Computing technologies present a great opportunity to enhance system security. This presentation highlights portions of NSA's Secure Virtual Platform (SVP) research program which has been focused on how best to leverage these technologies to construct more secure systems. The concepts explored under SVP offer a potential vision for OpenXT's future as a robust secure system.
  
 * 10:45 Break

 * 11:00 Trusted Platform Module 2.0 and OpenEmbedded, *Philip Tricca*, Intel Corporation
 
 > The TPM is at the core of the OpenXT measured launch implementation. The second iteration of the Trusted Platform Module spec (TPM2) is becoming more widely deployed and this new spec isn't backward compatible with TPM 1.2. Intel released and develops a BSD-licensed implementation of the core TPM2 components for Linux. This talk introduces the architecture of this implementation and related work in the Grub2 bootloader. It will cover benefits and a potential roadmap for TPM2 integration in OpenXT. As a first step in this direction, this talk will review a reference implementation that integrates these technologies into the OpenEmbedded meta-measured layer, using the Minnowboard Max as a test platform.

 * 11:30 OpenXT Measured Launch, *Daniel Smith*, Apertus Solutions
 
 > This talk will present the enhancements being made to the OpenXT Measured Launch process. It will cover the re-architecture of the Key, TPM, and Measured Launch management to provide a flexible framework that can be more easily extended. This will allow Implementers to use OpenXT as a base platform and tailor the process to meet the security needs of their platform. The presentation will conclude with some remaining challenges and longer term goals that still need to be accomplished.

 * 12:00 Lunch

 * 13:00 Looking to the Future: ARM Client Virtualization and Operating with an Untrusted dom0, *Kyle Temkin*, Assured Information Security
 
 > As the OpenXT platform has developed and matured, the upstream Xen community has focused on a number of new architectural developments and enhancements—many of which can be used to significantly enhance the OpenXT project. This talk explores two separate areas that may significantly shape the future of OpenXT: the development of client virtualization support for ARM platforms, and the potential to leverage new Xen features and disaggregation techniques to significantly improve OpenXT’s security posture

 * 13:30 Display Handlers, *Brendan Kerrigan*, Assured Information Security
 
 > Display Handler is a framework and implementation for handling diverse guest and host rendering environments in client virtualization systems. The goal of the project was to address deficiencies in OpenXT's surfman, while providing flexibility to easily integrate forthcoming virtual graphics technologies (such as Intel XenGT). This talk will cover the overall architecture, design decisions, strengths, and weaknesses of Display Handler. It will also provide a comparison of surfman, as currently integrated into OpenXT, and Display Handler. Finally, a road map for future work will be presented.

 * 14:00 Toolstack Modernization, *Chris Rogers*, Assured Information Security
 
 > Much OpenXT development over the past year has been motivated by our desire to bring the code base more in line with upstream counterparts.  The Modernization of the toolstack is another such effort.  Until now, OpenXT has used a XenServer-derived toolstack component (xenvm) underneath a domain management-level component (XenMgr). Since the Xen Project has adopted XL as its default toolstack, OpenXT should do the same in order to further reduce technical debt and support newer versions of Xen. Specifically, the Toolstack Modernization effort incorporates libXL into the base platform and focuses on four major areas of integration: communication between XenMgr and libXL, linux-based stubdomains on libXL, removal of old helper daemons such as dm-agent, and support for newer versions of blktap.
 
 * 14:30 Test Automation (UI, ATF, BVT), *Garrett Morgan*, Assured Information Security
 
 > How do we implement an automated test framework on a virtualized platform?  The current CLI-based implementation (BVT) provides a great foundation, and is currently being expanded.  In parallel, a UI-based OO automation framework/plugin is being explored which utilizes Intel's AMT KVM and the SikuliX Java application.  As with any automated framework, certain compromises are made, and by integrating the two technologies we look to expand the testing capabilities and bring the test devices as close to a production configuration as possible.
 
 * 15:00 Break

 * 15:15 Intel Software Guard Extensions (SGX), *Jacob Torrey*, Assured Information Security
 
> As networks become increasingly targeted by attackers in search of sensitive data, a new data protection model is arising: one in which data must be protected even on contested networks. In this new paradigm, a stronger isolation boundary is needed than the current process model of the status quo: hardware-enforced enclaves are a step towards true data protection in contested networks. This talk provides a background of enclaves provided by Intel SGX, followed by an example case study of well-known malware that could have been prevented through the deployment of enclave technologies. Finally a discussion on the weaknesses of the current enclave technologies is provided before concluding remarks.
 
 * 15:45 Securing dom0 today and in the future, *Derek Straka*, Star Lab
  
 > Over time there has been a lot of talks and proposals for improving Xen and dom0 basic security principles, but many are not followed years later. This talk will focus on a few items that can be done today, items that can be done relatively easily and items that we would like to undertake in the future. Attendees are invited to join the discussion and help come up with a plan. The end goal will be to make this a standing topic at future Xen conferences to keep focus on this area and continue to evolve the security of Xen and of the dom0 baseline.
 
 * 16:15 Virtualization Based Security – Big Deal or BS?, *Sherban Naum*, Bromium

> Endpoints and their human users are increasingly subjected to sophisticated, targeted attacks that evade detection to compromise the system in some unforeseen way. But a new defensive technique can change the odds in favor of security “by design”. Virtualization Based Security is a term that incorporates several approaches: micro-virtualization mutually isolates applications, whereas a virtual secure mode within an OS can be used to protect key data and processes – as in Windows 10. Intel VT can enable hardware enforced isolation between tasks within a single OS – using micro-virtualization and a specialized hypervisor that has been modified for inter-task isolation, called a Microvisor. In our work we use an extension of the Xen Project® hypervisor. Micro-virtualization reduces the attack surface of the OS by several orders of magnitude. It can be integrated into a PC or mobile device in a way that does not interfere with the user experience. Finally, its granular isolation of single tasks permits real-time introspection and detection of otherwise undetectable malware.
 
 * 16:45 Virtualization and Business Models, *Rich Persaud*, BAE Systems
 
 > License revenue for proprietary operating systems on OEM hardware is being supplanted by vertically integrated hardware, utility pricing of hosted services, and fees for "app store" software distribution. End-users often work across multiple device form factors, connected to public and private services. As diverse hardware and networked services proliferate, in complex supply chains with open and closed components, how can virtualization architectures support evolving business models?
 
 * 17:15 End of Day 1 presentations 
 
 * 17:30 Evening Reception

### <a name="discussions"></a> Discussion Agenda: Wednesday 8 June, 2016

Please add your questions and discussion topics to the [OpenXT wiki](https://openxt.atlassian.net/wiki/display/CS/Discussion+Topics).

 * 08:00 Breakfast

 * 09:00 Definition: Base Platform and Disaggregated dom0
 
 > Moderator: *Ross Philipson*, Assured Information Security
 
 * 09:30 Definition: Layers and Modular Build
 
 > Moderator: *Daniel Smith*, Apertus Solutions
 
 * 10:00 Definition: Display Architectures, UX
 
 > Moderator: *Brendan Kerrigan*, Assured Information Security
 
 * 10:30 Break
 
 * 11:00 Planning: Upstream: Xen, Qemu, OpenEmbedded, meta-virtualization, meta-openxt 
 
 > Moderator: *Derek Strata*, Star Lab
 
 * 11:30 Planning: Governance, Security Disclosure Process
 
 > Moderator: *Christopher Clark*, BAE Systems
 
 * 12:00 Lunch
 
 * 13:00 Strategy: UEFI, SecureBoot, TPM2, Virtual TPM, VMCS Shadowing
 
 > Moderator: *Philip Tricca*, Intel Corporation
 
 * 13:30 Strategy: Modular Policy (SE Linux, XSM, Toolstack, Service VM)
 
 > Moderator: *Stephen Smalley*, National Security Agency
 
 * 14:00 Strategy: Tablets, Mobility, Embedded and ARM
 
 > Moderator: *Kyle Temkin*, Assured Information Seurity
 
 * 14:30 Strategy: Use Case Spectrum, NIAP Protection Profiles
 
 > Moderator: *Jim Rauscher*, National Security Agency
 
 * 15:00 Break
 
 * 15:20 Strategy: Platform APIs, Ecosystem Interfaces, Compatibility, HCL
 
 > Moderator: *Daniel Smith*, Apertus Solutions 
 
 * 16:00 Planning: 2016 Roadmap and Timeline
 
 > Moderator: *Rich Persaud*, BAE Systems
 
 * 17:00 End of Day 2 discussions
 

### Hotels

 * 2 miles, [Fairfax Marriott at Fair Oaks](http://www.marriott.com/hotels/travel/iadmc-fairfax-marriott-at-fair-oaks/)
 * 2 miles, [Hilton Garden Inn Fairfax](http://hiltongardeninn3.hilton.com/en/hotels/virginia/hilton-garden-inn-fairfax-IADFHGI/index.html)
 * 2 miles, [Hyatt Regency Fairfax](http://fairfax.regency.hyatt.com/en/hotel/home.html)
 * 3 miles, [Hampton Inn Fairfax City](http://hamptoninn3.hilton.com/en/hotels/virginia/hampton-inn-fairfax-city-FFCVAHX/index.html)
 * 8 miles, [Westin Reston Heights](http://westinreston.com)



Intel and the Intel logo are trademarks of Intel Corporation or its subsidiaries in the U.S. and/or other countries.
