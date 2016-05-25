---
layout: page
title: History
permalink: /history/
---

## Ecosystem

#### 2016

* [Simplevisor](http://ionescu007.github.io/SimpleVisor/), *Alex Ionescu*

* [iOS 9 Security](https://www.apple.com/business/docs/iOS_Security_Guide.pdf), *Apple*

* BSides, [QNX Security Architecture Whitepaper](https://labs.mwrinfosecurity.com/publications/qnx-architectural/)

* [Open-source microkernel projects](http://www.microkernel.info), Jakub Jermar

#### 2015

* Xen Summit, [Virtual Machine Introspection with Xen](http://events.linuxfoundation.org/sites/events/files/slides/xendevsummit.pdf), *Tamas Lengyel* ([video](https://www.youtube.com/watch?v=k0BVFyyuvRA))

* blackhat, [How Windows 10 rewrites OS architecture](http://www.alex-ionescu.com/blackhat2015.pdf), *Alex Ionescu*

* [Genode OS Architecture](http://genode.org/documentation/genode-foundations-15-05.pdf), *Norman Feske*

#### 2014

* LinuxCon NA, [Security in the Cloud: Xen, KVM, Containers](http://www.slideshare.net/xen_com_mgr/lcna14-security-of-virtualization-solutions), *George Dunlap*

* Xen Summit, [Security and the Properties of a Xen Virtualization Platform](http://www.slideshare.net/xen_com_mgr/tricca-xen-summit2014), *Philip Tricca* ([video](https://www.youtube.com/watch?v=ESS2UGBi4eI))

* [Software compartmentalization vs. physical separation](http://invisiblethingslab.com/resources/2014/Software_compartmentalization_vs_physical_separation.pdf), *Joanna Rutkowska*

* Xen Summit, [Zero-Footprint Guest Memory Introspection from Xen](http://www.slideshare.net/xen_com_mgr/zero-footprint-guest-memory-introspection-from-xen), *Mihai Dontu & Ravi Sahita*

> VM Introspection, Hypervisor support for Introspection using Hardware Virtualization Extensions

#### 2013

* LinuxCon EU, [Securing your cloud with Xen's advanced security features](http://www.slideshare.net/xen_com_mgr/lceu13-securing-your-cloud-with-xens-advanced-security-features-ge), *George Dunlap* ([video](http://www.youtube.com/watch?v=fvW3kzl-bfY))

* Xen Summit, [In-Guest Mechanisms to Strengthen Guest Separation](http://events.linuxfoundation.org/sites/events/files/slides/XenSummit_2013_Tricca.pdf), *Philip Tricca* ([video](https://www.youtube.com/watch?v=6Q8mlTBn-ZI))

* Xen Summit, [Secure Server Project](http://www.slideshare.net/xen_com_mgr/xen-summit2013-secureserverproject), *Jason Sonnek* ([video](http://www.youtube.com/watch?v=v_RJZTFcKoc))

> Multi-Level (MLS) Hypervisor for Server 

* [Thoughts on Intel's upcoming Software Guard Extensions, Part 1](http://theinvisiblethings.blogspot.com/2013/08/thoughts-on-intels-upcoming-software.html) &mdash; [Part 2](http://theinvisiblethings.blogspot.com/2013/09/thoughts-on-intels-upcoming-software.html), *Joanna Rutkowska*

#### 2012 

* Xen Summit, [&mu;-Xen](http://www.slideshare.net/xen_com_mgr/xen-14203926), *Ian Pratt*

> Micro-Virtualization, Type-2 Hypervisor, VM Fork, Deprivileged Windows Host 

* Xen Summit, [Xen and Client Virtualization: the case of XenClient XT](http://www.slideshare.net/xen_com_mgr/xen-and-client-virtualization-the-case-of-xenclient-xt), *Gianluca Guida*

> Client Virtualization, VPN VM, Linux Stub Domains, Graphics Virtualization, Inter-VM Communication, SE Linux, Xen Security Modules (XSM), Dynamic Root of Trust Measurement (DRTM), Service VMs, Intel VT-d, Intel TXT.

#### 2010 

* [Qubes OS Architecture](https://www.qubes-os.org/attachment/wiki/QubesArchitecture/arch-spec-0.3.pdf), *Joanna Rutkowska*

> Secure GUI, Secure networking, Secure storage, Analysis of potential attack vectors

#### 2009 

* Xen Summit, [HXEN: Hosted Xen](http://wiki.xen.org/old-wiki/xenwiki/Xen_HXEN.html), *Christian Limpach & Peter Johnston*

> Type-2 Hypervisor for Windows Host

#### 2007 

* Xen Summit, [Trusted Boot: Verifying the Xen Launch](https://web.archive.org/web/20140611161423/http://www-archive.xenproject.org/files/xensummit_fall07/23_JosephCihula.pdf), *Joseph Cihula*

#### 1986

* Computer History Museum, [ACM Conference on the History of Personal Workstations](http://www.computerhistory.org/atchm/the-1986-acm-conference-on-the-history-of-personal-workstations/)

## Research Papers

#### 2013

* IEEE Symposium on Security and Privacy, [XMHF: Design, Implementation and Verification of an eXtensible and Modular Hypervisor Framework](http://ieeexplore.ieee.org/ielx7/6547086/6547088/06547125.pdf?tp=&arnumber=6547125&isnumber=6547088), *Amit Vasudevan et al.*

* Security Protocols Workshop, [Towards a Theory of Application Compartmentalisation](http://www.cl.cam.ac.uk/~kg365/pubs/2013spw-compartmentalisation.pdf), *Robert N.M. Watson et al.*

* ASPLOS, [Unikernels: Library Operating Systems for the Cloud](http://anil.recoil.org/papers/2013-asplos-mirage.pdf), *Anil Madhavapeddy et al.*

* SOSP, [VirtuOS: an operating system with kernel virtualization](http://people.cs.vt.edu/~gback/papers/sosp13final.pdf), *Ruslan Nikolaev and Godmar Back*

#### 2011 

* ACM Symposium on Operating Systems Principles, [Breaking Up is Hard to Do: Security and Functionality in a Commodity Hypervisor](http://www.cs.ubc.ca/~andy/papers/xoar-sosp-final.pdf), *Patrick Colp et al.*

> "We present Xoar, a modified version of Xen that retrofits the modularity and 
isolation principles used in microkernels onto a mature virtualization platform. 
Xoar breaks the control VM into single-purpose components called
service VMs. We show that this componentized abstraction brings a number of
benefits: sharing of service components by guests is configurable and auditable, 
making exposure to risk explicit, and access to the hypervisor is restricted 
to the least privilege required for each component."

 * [Bear – A Resilient Operating System for Scalable Multi-processors](http://thayer.dartmouth.edu/tr/reports/tr11-005.pdf), *Stephen Taylor et al.*
 
> "This paper describes a minimalist operating system design aimed at scalable multi-processor systems whose primary goal is resilience. The design is expressly targeted toward critical military applications for the purpose of operating through failures, errors, and malicious attacks."

#### 2010

* [Folk Models of Home Computer Security](http://www.rickwash.com/papers/rwash-homesec-soups10-final.pdf), *Rick Wash*

#### 2008 

* ACM Conference on Virtual Execution Environments, [Improving Xen Security through Disaggregation](https://www.cl.cam.ac.uk/research/srg/netos/papers/2008-murray2008improving.pdf), *Derek Murray et al.*

> "We introduce our work to disaggregate the management virtual machine 
in a Xen-based system ... moves
the domain builder, the most important privileged component, into a minimal 
trusted compartment. We illustrate how this approach may be used to implement 
“trusted virtualisation” and improve the security of virtual TPM implementations. 

#### 2007

* ACM Workshop on New Security Paradigms, [Robustly Secure Computer Systems: A new security paradigm of system discontinuity](http://parsys.eecs.uic.edu/~solworth/solworth07systemDiscontinuity.pdf), *Jon A. Solworth*

#### 2006 

* *Computer* magazine, [Can We Make Operating Systems Reliable and Secure?](http://cs.furman.edu/~chealy/cs75/important%20papers/secure%20computer-2006a.pdf), *Andrew S. Tanenbaum et al.*

* USENIX Security, [Virtualizing the Trusted Platform Module](https://www.usenix.org/event/sec06/tech/full_papers/berger/berger.pdf), *Stefan Berger et al.*

* ASPLOS, [A Comparison of Software and Hardware Techniques for x86 Virtualization](http://www.scs.stanford.edu/13wi-cs240/sched/readings/vm-techniques.pdf), *Keith Adams et al.*

#### 2005

* Annual Computer Security Applications Conference, [A Nitpicker's guide to a minimal-complexity secure GUI](https://www.acsac.org/2005/papers/54.pdf), *Norman Feske and Christian Helmuth*

#### 2003

* ACM Symposium on Operating Systems Principles, [Xen and the Art of Virtualization](http://www.cl.cam.ac.uk/research/srg/netos/papers/2003-xensosp.pdf), *Paul Barham et al.*

> "This paper presents Xen, an x86 virtual machine monitor which allows multiple commodity operating systems to share conventional hardware in a safe and resource managed fashion, but without sacricing either performance or functionality."

#### 1998 

* USENIX Security, [The Flask Security Architecture: System Support for Diverse Security Policies](https://www.cs.cmu.edu/~dga/papers/flask-usenixsec99.pdf), *Ray Spencer et al.*

#### 1991

* IEEE Transactions on Software Engineering, [A Retrospective on the VAX VMM Security Kernel](http://www.cse.psu.edu/~trj1/cse543-f06/papers/vax_vmm.pdf), *Paul Karger et al.*
 
#### 1981

* IBM Journal of Research & Development, [The Origin of the VM/370 Time-sharing System](http://lass.cs.umass.edu/~shenoy/courses/fall07/papers/vm370.pdf), *R.J. Creasy*
