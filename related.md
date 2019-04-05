---
layout: page
title: Related
permalink: /related/
---

* TOC
{:toc}

# OSS Virtualization Projects
---

### ITL QubesOS

> "... is a security-focused desktop operating system that aims to provide security through isolation. Virtualization is performed by Xen, and user environments are based on Fedora."

- [History](http://en.wikipedia.org/wiki/Qubes_OS) &middot; [Funding](https://opencollective.com/qubes-os)
- [Software](https://qubes-os.org/), *Poland*
- [Research](https://www.qubes-os.org/research/) &middot; [Qubes Air](https://www.qubes-os.org/news/2018/01/22/qubes-air/) &middot; [Separation](https://invisiblethingslab.com/resources/2014/Software_compartmentalization_vs_physical_separation.pdf) &middot; [Intel x86](https://blog.invisiblethings.org/papers/2015/x86_harmful.pdf)
- [Users](https://groups.google.com/forum/#!forum/qubes-users) &middot; [Developers](https://groups.google.com/forum/#!forum/qubes-devel) &middot; [News](https://www.qubes-os.org/news/) &middot; [SaltStack management](https://www.qubes-os.org/doc/salt/)

### Bromium µ-Xen

> micro-virtualization, Type-2 hypervisor, VM fast fork with copy-on-write memory/disk, deprivileged Windows host, display compositing, seamless user experience

- [Software](https://bromium.com/opensource), *UK*
- Presentations: [2012](http://www.slideshare.net/xen_com_mgr/xen-14203926) &middot; [2018](https://platformsecuritysummit.com/2018/speaker/pratt)
- Linux port: [osresearch](https://github.com/osresearch/uxen)

### Xen Servers

- [XenServer / Citrix Hypervisor](http://xenserver.org) &middot; [source](https://www.citrix.com/community/citrix-developer/citrix-hypervisor1/), *China, UK*
- [XCP-ng](https://xcp-ng.org), *France*
- U.S. NRL Xenon Separation VMM: [2008](http://www-archive.xenproject.org/files/xensummitboston08/XenSummitSpring08.pdf) &middot; [2018](https://www.platformsecuritysummit.com/2018/speaker/kang/PSEC2018-Xenon-Separation-VMM-Myong-Kang.pdf), *USA*

### AIS Redfield

- [Bareflank](https://bareflank.github.io/hypervisor/) hypervisor toolkit, *USA*

  > lightweight hypervisor SDK written in C++ with support for Windows, Linux and UEFI ...  rapidly prototype and create new hypervisors ... MIT license

- [Desktop Client](https://gitlab.com/redfield/documentation/wikis/home)

  > Virtualized multi-domain graphical client based on OpenEmbedded and Xen

### QEMU/KVM

- IBM [Solo5](https://github.com/Solo5/solo5/blob/master/docs/architecture.md) sandbox &middot; [unikernel monitors](https://www.usenix.org/system/files/conference/hotcloud16/hotcloud16_williams.pdf) (2016) &middot; [unikernels as processes](https://blog.acolyer.org/2018/11/14/unikernels-as-processes/) (2018) &middot; [fosdem](https://fosdem.org/2019/schedule/event/solo5_unikernels/attachments/slides/3281/export/events/attachments/solo5_unikernels/slides/3281/solo5_fosdem19.pdf) (2019)

  > "sandboxed execution environment ... re-defines the interface between the process and its host operating system or hypervisor ... make it easy to implement new targets, targeting a variety of different sandboxing technologies (e.g. hardware virtualization, Linux seccomp, Intel SGX), host operating systems and hypervisors."

- Amazon [Firecracker](https://firecracker-microvm.github.io/) &middot; [Nitro SR-IOV](http://www.brendangregg.com/blog/2017-11-29/aws-ec2-virtualization-2017.html), *Germany, USA*
- Google [CrosVM](https://chromium.googlesource.com/chromiumos/platform/crosvm/), *USA*
- [rust-vmm](https://github.com/rust-vmm): [fosdem](https://fosdem.org/2019/schedule/event/vai_rust_vmm/) (2019) &middot; [article](https://opensource.com/article/19/3/rust-virtual-machine) (2019)

  > "... Amazon, Google, Intel, and Red Hat employees started talking about the best way of sharing virtualization packages ...  two VMMs written in Rust under active development and growing interest in building other specialized VMMs ... shared-effort, shared-ownership ... crosvm, Kata Containers, and Firecracker teams ... [Rust] memory management guarantees simplify the task of security hardening, while its roots as a system programming language ensure C-like performance."

### Kata Containers

> VM isolation of performant containers, based on Intel Clear Containers and Hyper runV

- [Community](https://katacontainers.io) &middot; [github](https://github.com/kata-containers/), *China, USA*

### Intel ACRN

>  flexible, lightweight reference hypervisor, built with real-time and safety-criticality in mind, optimized to streamline embedded development ... BSD license

- [Software](https://projectacrn.org/), *China, USA*

> NEMU is based off QEMU ... retain the absolute minimal subset ... vfio ... live migration, vhost-user ... build-time configurable device hotplug support for PCI, memory, NVDIMM and CPU ... emulate a small subset of features including PCI host bridge ... supports x86-64 and AArch64

- [Cloud hypervisor](https://github.com/intel/nemu)

### L4

> "... is a family of second-generation microkernels, generally used to implement Unix-like operating systems, but also used in a variety of other systems ... L4 is widely deployed. One variant, OKL4 from Open Kernel Labs, shipped in billions of mobile devices"

- [History](http://en.wikipedia.org/wiki/L4_microkernel_family)
- [seL4 Secure Microkernel](http://ssrg.nicta.com/projects/seL4/), *Australia*
- [Genode OS Framework](http://genode.org/), *Germany*
- Kernkonzept [L4Re](https://l4re.org) &middot; [slides (2017)](http://connect.linaro.org.s3.amazonaws.com/sfo17/Presentations/SFO17-416-L4RE.pdf), *Germany*

### Muen

> "microkernel that has been formally proven to contain no runtime errors at the source code level ... high-assurance systems on the Intel x86/64 platform" ... 32/64-bit Linux, 32-bit Windows, VT-d passthrough, Ada/SPARK  ... GPLv3 license

- [Software](https://www.muen.sk), [slides (2014)](https://www.slideshare.net/AdaCore/slides-his-2014secunethsr), *Switzerland*

# OSS Virtual Appliances for Xen
---

### Linux

- [Alpine Linux](http://alpinelinux.org/), *Europe*

  > Read-only dom0, boot from USB/SD, router/firewall use cases, musl C library, PaX

- Rob Landley, [Aboriginal Linux](http://landley.net/aboriginal/about.html), *USA*

  > Shell script that builds the smallest/simplest linux system capable of rebuilding itself from source code. This currently requires seven packages: linux, busybox, uClibc, binutils, gcc, make, and bash.

- Patrick Schleizer, [Whonix](https://www.whonix.org/), *Germany*

  > ..desktop operating system designed for advanced security and privacy ... mitigates the threat of common attack vectors while maintaining usability ... anonymity is realized via fail-safe, automatic, and desktop-wide use of the Tor network.

### BSD

- Netgate [pfSense](https://pfsense.org) network appliance, *USA*

  > "network firewall distribution ... same functionality ... of common commercial firewalls ...  includes a web interface for the configuration of all included components" ... SPI, NAT, DNS, DHCP, IPsec/OpenVPN, VLAN, IDS/IPS

- [Open vSwitch](http://openvswitch.org/) SDN [appliance](https://bsdmag.org/open-vswitch-overview/), *USA*

  > "based on Stanford's OpenFlow project .. multilayer virtual switch supports flows, VLANs, trunking, port aggregation ... network automation through programmatic extension"

- iXsystems [FreeNAS](https://freenas.org) storage appliance, *USA*

  > includes web interface, NFS, iSCSI, SMB, WebDAV, ZFS ... "an enterprise-ready open source file system, RAID controller, and volume manager with unprecedented flexibility and an uncompromising commitment to data integrity"

- [OpenBSD](https://www.openbsd.org) OS (5.9+ enables [PVHVM](https://www.openbsd.org/papers/asiabsdcon2016-xen-paper.pdf)), *Canada*

### Unikernels

> Single-purpose appliances, build-time specialised into standalone kernels, and sealed against modification after deployment.

- C/Java, [Cloudius OSV](http://osv.io), *Israel*
- C++, [Arrakis](http://arrakis.cs.washington.edu/), *Switzerland, USA*
- [Click](https://github.com/kohler/click) modular router, *USA*
- [Erlang-on-Xen](https://github.com/cloudozer), *Germany, UK*
- [FreeRTOS](https://www.freertos.org) &middot; [on-Xen](https://github.com/GaloisInc/FreeRTOS-Xen), *UK, USA*
- Go, [Clive](http://lsub.org/ls/clive.html), *Spain*
- Haskell, [HaLVM](http://halvm.org), *USA*
- Lua, [Towards a Lua scripted OS](http://www.lua.org/wshop13/Cormack.pdf)
- Ocaml, [MirageOS](http://mirage.io), *UK*
- [rumprun](https://lucina.net/files/rumprun-xpds2015.pdf) &middot; [rumpkernel](http://rumpkernel.org/), *UK*
- [Unikraft](https://xenproject.org/developers/teams/unikraft/), *Germany*

### Packer

> Immutable infrastructure via declarative customization of VM images for QEMU, VirtualBox, Docker, VMware, Hyper-V, CloudStack, AWS, Azure and GCE. Can be extended to other virtualization platforms via plugins.

- [Software](https://www.packer.io/), [tutorial](https://blog.codeship.com/packer-vagrant-tutorial/), *Japan, USA*
- Templates: [Windows](http://www.hurryupandwait.io/blog/creating-windows-base-images-for-virtualbox-and-hyper-v-using-packer-boxstarter-and-vagrant)

### Vagrant

> Is used to "create and configure lightweight, reproducible, and portable development environments". It can be considered a wrapper around VirtualBox, VMware, Docker, AWS and libvirt.

- [History](http://en.wikipedia.org/wiki/Vagrant_%28software%29)
- [Software](https://www.vagrantup.com/), *Japan, USA*
- [Boxes](https://app.vagrantup.com/boxes/search) &middot; [archive](http://www.vagrantbox.es/)

# Hardware
---

### Purism

> Intel vPro laptops with coreboot firmware, hardware kill switches for sensors, optimized for Linux, Heads and QubesOS

- [Purism](https://www.puri.sm), *USA*
- [Supply Chain](https://puri.sm/posts/protecting-the-digital-supply-chain/) &middot; [Kill switches](https://puri.sm/posts/lockdown-mode-on-the-librem-5-beyond-hardware-kill-switches/) &middot; [Intel ME](https://puri.sm/posts/measuring-the-intel-me-to-create-a-more-secure-computer/) &middot; [Qubes 4.0](https://puri.sm/posts/qubes4-fully-working-on-librem-laptops/) &middot; [Tamper Detection](https://puri.sm/posts/the-librem-key-makes-tamper-detection-easy/)

### PC Engines

> Low-power x86 devices with coreboot firmware, embedded AMD CPU, IOMMU, DRTM, optional TPM 2.0, multiple Intel NICs, mPCIe expansion and multi-year commercial availability

- [PC Engines](https://pcengines.ch), *Switzerland*

### ODroid

> low-cost single-board computer ... ARM 64-bit Cortex-A53 quad-core Amlogic CPU with virtualization extensions, Mali GPU, 2GB RAM, gigabit ethernet, HDMI 2.0 and USB 2.0

- [Hardkernel](https://www.hardkernel.com) [ODroid-C2](https://wiki.odroid.com/odroid-c2/odroid-c2), *South Korea*
- [virtualization extensions](https://wiki.odroid.com/odroid-c2/application_note/software/ubuntu_cloud_virtualization)

### Open Compute Project

> customer-led, open hardware and firmware designs for hyperscale servers, storage, networking and silicon ... contributors include Facebook, Google, IBM, Intel and  Microsoft

- OCP [Open System Firmware](https://www.opencompute.org/wiki/Open_System_Firmware) &middot; OSFC [2018 videos](https://youtube.com/playlist?list=PLJ4u8GLmFVmoRCX_gFXV6fhWmsOQ5cmuj)
- OCP [Security](https://www.opencompute.org/wiki/Security) &middot; [Cerberus](https://youtube.com/watch?v=wCMplDQLsfw) Root of Trust &middot; [specs](https://github.com/opencomputeproject/Project_Olympus/tree/master/Project_Cerberus)
- OCP [Open Domain-Specific Architecture](https://www.opencompute.org/wiki/Server/ODSA) (ODSA)

# Research Prototypes
---

### KSM

> "... fast, hackable and simple x64 VT-x hypervisor for Windows and Linux. Builtin userspace sandbox and introspection engine ... supports nesting (VT-x emulation)" ... offense/defense

- Ahmed Samy, [KSM](https://github.com/asamy/ksm) &middot; [Hypervisors in Your Toolbox, BlueHat 2016](http://tandasat.github.io/HyperPlatform/bluehatv16/BlueHat_v16_slides.pdf)

### Cappsule

> "x86-64 Linux hypervisor ... virtualize any software on the fly (e.g. web browser, office suite, media player) into lightweight VMs called cappsules. Attacks are confined inside cappsules and therefore don’t have any impact on the host OS. Applications don’t need to be repackaged, and their usage remain the same for the end user"

- Quarkslab, [software](https://github.com/cappsule) &middot; [overview](https://blog.quarkslab.com/on-the-fly-virtualization-with-cappsule.html), *France*

### OpenXCI

> "... is a Xen-based desktop hypervisor. Unlike other desktop hypervisors, it is not targeted at businesses wanting remote provisioning, but rather at individuals who want a high-performance alternative to dual/multi-booting."

- [Software](http://openxci.sourceforge.net/) -- [description](http://xen.1045712.n5.nabble.com/OpenXCI-update-almost-ready-to-release-an-alpha-version-td5721403.html), *Canada*

### Ethos OS

> "... provides stronger security services which are more resistant to attack and abstractions which are less prone to abuse by attackers. As an example of the former, all networking in Ethos is encrypted, authenticated, and authorized. As an example of the latter, Ethos I/O is typed (as in programming languages) ensuring that I/O conforms to declared types and thus preventing many attacks based on ill-formed input."

- [U of Illinois Research](https://www.ethos-os.org/), *USA*

# Commercial Products
---

### Client

- Bromium, [Secure Platform](https://www.bromium.com/our-tech/bromium-secure-platform/), *UK, USA*
- Garrison, [Secure Browsing](https://www.garrison.com/), *UK*
- Green Hills, [Integrity Multivisor](https://www.ghs.com/products/rtos/integrity_virtualization.html), *UK, USA*
- [Hysolate](https://www.hysolate.com), *Israel*
- Microsoft, [SystemGuard](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-defender-system-guard/system-guard-how-hardware-based-root-of-trust-helps-protect-windows), *Israel, USA*
- Forcepoint, [Trusted Thin Client](https://www.forcepoint.com/products/TrustedThinClient.html), *USA*
- Secunet, [SINA Virtual Workstation](https://www.secunet.com/en/products-solutions/sina-workstation/), *Germany*
- Triitus, [HyperClient](https://www.triitus.com), *USA*

### Server

- Adventium Labs, [Magrana Server](https://www.adventiumlabs.com/our-work/products-services/magrana-server-secure-virtualized-server-critical-enterprise-operations), *USA*
- Citrix [Hypervisor](https://www.citrix.com/products/citrix-hypervisor/), *China, USA*
- IBM, [Ultravisor](https://developer.ibm.com/articles/l-support-protected-computing/), *USA*
- [Tehama](https://www.tehama.io), [Platform](https://www.tehama.io/platform/), *Canada*
- VMware [ESXi](https://www.vmware.com/products/esxi-and-esx.html), *USA*

### Embedded

- Blackberry, [QNX Hypervisor](http://blackberry.qnx.com/en/products/hypervisor/index), *Canada*
- Cog, [D4 Secure](https://cog.systems/), *Australia*
- DornerWorks, [Virtuosity Hypervisor](https://dornerworks.com/xen/virtuosity/virtuosity), *USA*
- Star Lab, [Crucible Embedded Hypervisor](https://starlab.io/products/crucible/), *USA*
- [Virtual Open Systems](http://www.virtualopensystems.com) &middot; [github](https://github.com/virtualopensystems), *France*

### Guards

- Fox IT, [DataDiode](https://www.fox-it.com/en/products/datadiode/) &middot; [video](http://www.youtube.com/watch/vemwnQmnvuo), *Netherlands*
- SANS, [Tactical Data Diodes](https://www.sans.org/reading-room/whitepapers/firewalls/tactical-data-diodes-industrial-automation-control-systems-36057), *USA*
- [Tresys](https://www.tresys.com), *USA*

### Acquired or Retired

| Year | Company | Acquirer | Location | Description |
| --- | --- | --- | --- | --- |
| 2018 | Parallels | Corel | *Canada, Russia, USA* | Type-2 virtualization |
| 2018 | [Cylance](https://blogs.blackberry.com/2018/11/icymi-blackberry-to-acquire-cylance) | Blackberry | *Canada, USA* | Endpoint app ML/AI profiling |
| 2018 | Core OS | RedHat, IBM | *USA* | Enterprise container mgmt |
| 2018 | Skyport Systems | Cisco | *USA* | Hybrid cloud remote attestation |
| 2017 | Simplivity | HPE | *USA* | Hyper-converged infrastructure |
| 2016 | Ravello | Oracle | *Israel, USA* | Nested virt for cloud migration |
| 2016 | Annapurna Labs | Amazon | *Israel, USA* | Datacenter silicon |
| 2015 | Moka5 | &mdash; | *USA* | Type-2 endpoint mgmt |
| 2014 | PrivateCore | Facebook | *USA* | Memory encryption, SGX |
| 2012 | [OK Labs](https://en.m.wikipedia.org/wiki/Open_Kernel_Labs) | General Dynamics | *Australia, USA* | Microkernel hypervisor |
| 2012 | [Virtuata](https://www.theregister.co.uk/2012/07/17/cisco_buys_virtuata/) | Cisco | *USA* | VM introspection |
| 2012 | Dynamic Ops | VMware | *UK, USA* | Self-service VM orchestration |
| 2011 | [Virtual Computer](https://web.archive.org/web/20090327193417/http://www.virtualcomputer.com/) | Citrix | *USA* | Type-1 endpoint mgmt |
| 2010 | Trusted Computer Solutions | Raytheon | *USA* | Cross-domain thin clients |
| 2010 | [Neocleus](https://www.brianmadden.com/opinion/Intel-buys-client-hypervisor-maker-Neocleus-for-next-to-nothing) | Intel | *Israel, USA* | Endpoint OSS virtualization |
| 2009 | [Virtual Iron](https://web.archive.org/web/20090327193417/http://www.virtualiron.com/) | Oracle | *USA* | Virtualization management |
| 2008 | Innotek | Sun, Oracle | *Germany, USA* | Type-2 OSS virtualization (VirtualBox) |
| 2007 | XenSource | Citrix | *USA* | Type-1 OSS virtualization (Xen) |
{:.table-small}


