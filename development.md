---
layout: page
title: Development
permalink: /development/
---

* TOC
{:toc}

## Introduction

Please see the [Getting Started](https://openxt.atlassian.net/wiki/display/OD/Getting+Started) and [How to Contribute](https://openxt.atlassian.net/wiki/display/OD/How+to+contribute) pages. There are 50+ source repositories on [Github](https://github.com/openxt), with [build instructions](https://openxt.atlassian.net/wiki/spaces/OD/pages/10747922/How+to+build+OpenXT).

Issues and enhancements are tracked in [JIRA](https://openxt.atlassian.net/browse/OXT). To request a JIRA account, send a message to the mailing list.

Questions and comments are welcome on the [mailing list](https://groups.google.com/forum/#!forum/openxt). To join the mailing list, send an empty email to [openxt+subscribe@googlegroups.com](mailto:openxt+subscribe@googlegroups.com).  There is an OpenXT IRC [channel](http://webchat.freenode.net/?channels=#openxt) and Slack [workspace](https://open-xt.slack.com).

## Documentation

- [Community](https://openxt.atlassian.net/wiki/spaces/CS/pages)
- [Getting Started](https://openxt.atlassian.net/wiki/spaces/OD/pages/10747910/Getting+Started)
- [How to Contribute](https://openxt.atlassian.net/wiki/spaces/OD/pages/11206680/How+to+contribute)
- [Development and Coding](https://openxt.atlassian.net/wiki/spaces/DC/pages)

The documents below are dated, especially with respect to video architecture, but may be useful to new developers.

- [OpenXT Architecture Guide](https://github.com/OpenXT-Extras/docs/blob/master/snapshot/XTArchitectureGuide.pdf?raw=true)
- [OpenXT Appliance Developer Guide](https://github.com/OpenXT-Extras/docs/blob/master/snapshot/XTEngineDeveloperGuide.pdf?raw=true)
- [OpenXT Appliance Administrator Guide](https://github.com/OpenXT-Extras/docs/blob/master/snapshot/XTEngineAdministratorGuide.pdf?raw=true)
- [OpenXT Management Administrator Guide](https://github.com/OpenXT-Extras/docs/blob/master/snapshot/XTSynchronizerAdministratorGuide.pdf?raw=true)

## Build

- [How to build OpenXT](https://openxt.atlassian.net/wiki/spaces/OD/pages/10747922/How+to+build+OpenXT)
- [Container-based](https://openxt.atlassian.net/wiki/spaces/OD/pages/21397507/Building+-+Version+6+and+Later) (Version 6+)
- [Debian Wheezy](https://openxt.atlassian.net/wiki/spaces/OD/pages/24707094/Building+-+Version+5+and+Earlier) (Version 5-)
- [Build System Wiki](https://openxt.atlassian.net/wiki/spaces/BS/pages)
- [OpenEmbedded and Xen](https://wiki.xen.org/wiki/Category:OpenEmbedded)

We are hosting a [mirror](http://mirror.openxt.org) of 3rd-party components needed for an appliance build. Please cache these files locally and build from your local mirror. The system hosting the mirror has limited bandwidth.

## Quality Assurance

OpenXT testing:

- Unsigned [development builds](https://openxt.atlassian.net/wiki/spaces/OD/pages/96534529/OpenXT+Downloads)
- Wiki: [Testing, Validation and Troubleshooting](https://openxt.atlassian.net/wiki/spaces/TEST/pages)
- Automated Test Harness:  [BVT](https://github.com/OpenXT-Extras/bvt) &middot; [BATS](https://github.com/OpenXT/bats-suite)
- [Manual Test Cases](https://github.com/OpenXT-Extras/test-cases/blob/master/OpenXT_Test_Cases.doc)

Xen, Linux and QEMU/KVM testing:

- RedHat Testing: [cobbler](https://github.com/cobbler/cobbler) &middot; [avocado-vt](https://github.com/avocado-framework/avocado-vt) &middot; [Continuous Kernel Integration (CKI)](https://cki-project.org)
- QubesOS [Automated Tests](https://www.qubes-os.org/doc/automated-tests/) &middot; [openQA](https://openqa.qubes-os.org/) &middot; [HCL](https://www.qubes-os.org/hcl/)
- Safety Certification: [Xen](https://wiki.xenproject.org/wiki/Category:Safety_Certification) &middot; [OSADL](https://www.osadl.org) &middot; [LF ELISA](https://elisa.tech)
- Intel [Graphics CI](https://intel-gfx-ci.01.org) &middot; [gitlab](https://gitlab.freedesktop.org/gfx-ci) &middot; [igt-gpu-tools](https://drm.pages.freedesktop.org/igt-gpu-tools/)
- Intel [CHIPSEC](http://www.c7zero.info/stuff/Platform%20Firmware%20Security%20Assessment%20wCHIPSEC-csw14-final.pdf) firmware security &middot; [github](https://github.com/chipsec/chipsec)
- Phoronix Linux Benchmarking [History](http://en.wikipedia.org/wiki/Phoronix_Test_Suite) &middot; [Software](http://www.phoronix-test-suite.com/)
- Guest Debug: [pyvmidbg](https://github.com/Wenzel/pyvmidbg) &middot; [xendbg](https://github.com/nccgroup/xendbg)
- 2018, Yocto [Automated Testing Summit](https://elinux.org/Automated_Testing_Summit)
- 2018, [Xen testing at Intel](https://www.youtube.com/watch?v=VE77esbf90w) (WindRiver Simics)
- 2018, [Performance tuning on Xen](https://www.youtube.com/watch?v=tae_M_4QENw)
- 2018, [Microsoft Security Features and Firmware Configurations](https://uefi.org/sites/default/files/resources/Microsoft_Spring%202018%20UEFI_Plugfest_Microsoft_Day2-Public.pdf)
- 2017, Andrew Cooper, [Xen Test Framework](https://www.youtube.com/watch?v=Jz0_QnZHoFw)
- 2016, Yocto Toaster: [video](https://www.youtube.com/watch?v=BlXdOYLgPxA) &middot; [manual](https://www.yoctoproject.org/docs/latest/toaster-manual/toaster-manual.html)
- 2016, Fedora: [Testing secureboot with KVM](https://fedoraproject.org/wiki/Testing_secureboot_with_KVM)
- 2015, KVM [Unit Testing](https://www.linux-kvm.org/images/5/5f/03x05-Aspen-Andrew_Jones_kvm_unit_tests.pdf)
- 2014, DornerWorks: [Xen and the art of certification](https://xenbits.xen.org/people/larsk/XPDS14%20-%20Xen%20and%20the%20Art%20of%20Certification.pdf)
- 2013, Xen OSSTest [Standalone Mode Step by Step](https://blog.xenproject.org/2013/09/30/osstest-standalone-mode-step-by-step/)
- 2013, Alex Brett, Test-as-a-Service: [video](http://www.youtube.com/watch?v=s11_Iw7AI_U) &middot; [slides](http://events.linuxfoundation.org/sites/events/files/slides/XenSummit%20TaaS%20and%20XenRT_0.pdf)
- 2013, Citrix XenRT [Code](http://xenserver.org/discuss-virtualization/virtualization-blog/entry/introducing-open-source-xenrt.html) &middot; [Architecture](http://wiki.xen.org/wiki/XenRT_Architecture_Guide) &middot; [Getting Started](http://wiki.xen.org/wiki/Getting_Started_with_XenRT) &middot; [User Guide](http://wiki.xenproject.org/wiki/XenRT_User_Guide)
- 2009, [Practical Xen Testing at Intel](http://www.slideshare.net/xen_com_mgr/practical-xen-testing-at-intel)
- 2009, Kernel Autotest: [Testing the Untestable](https://www.kernel.org/doc/ols/2009/ols2009-pages-9-18.pdf) &middot; [Software](http://autotest.github.io/)
- 2005, IBM, [Testing the Xen Hypervisor and Linux Virtual Machines](https://www.kernel.org/doc/ols/2005/ols2005v1-pages-279-288.pdf)
- 2005, [Xen 3.0 Test CD](https://lists.xenproject.org/archives/html/xen-users/2005-11/msg00584.html)

## Hardware

- Intel maintains a list of Dell, HP & Lenovo [vPro devices](https://msp.intel.com/find-a-vpro-system). OpenXT requires a vPro device with an integrated Intel GPU. Desktops can add AMD GPUs via IOMMU and PCI passthrough.  Nvidia GPUs are not supported, except on desktops with Quadro 2000 and higher models.

- OpenXT does not claim compatibility with specific hardware models or BIOS versions.  Hardware is validated by OEMs and/or integrators of tailored solutions based on the OpenXT toolkit.  The following test reports are informal and advisory:

  | Year | Client Generation | OpenXT | Xen | Linux |
  | --- | --- | --- |
  | 2019 | [Coffee Lake](https://openxt.atlassian.net/wiki/spaces/TEST/pages/630194218/Release+9.0+2019)| 9.0 | 4.12 | 4.19 |
  | 2018 | [Kaby Lake Refresh](https://openxt.atlassian.net/wiki/spaces/TEST/pages/620789765/OpenXT+8.0+Measurement+test) | 8.0 | 4.9 | 4.14 |
  | 2017 | [Kaby Lake](https://openxt.atlassian.net/wiki/spaces/TEST/pages/76319886/OpenXT+7.0+Hardware+Testing) | 7.0 | 4.6 | 4.9 |
  | 2016 | [Skylake](https://openxt.atlassian.net/wiki/spaces/TEST/pages/46989316/Release+6.0+Hardware+Testing) | 6.0 | 4.3 | 4.4 |
{:.table-small}

- QEMU/KVM users perform IOMMU and PCI device testing, often for gaming:
  - [The Passthrough Post](https://passthroughpo.st/) &middot; [Hardware](https://passthroughpo.st/vfio-increments/) &middot; [Level1Techs](https://forum.level1techs.com/t/the-vfio-and-passthrough-one-stop-shop/129897)
  - VFIO [subreddit](https://www.reddit.com/r/VFIO/)
  - Arch Linux [PCI passthrough](https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF)
  - RedHat's [vfio-users mailing list](https://www.redhat.com/archives/vfio-users/)
  - Alex Williamson's [VFIO tips & tricks](https://vfio.blogspot.com/)
  - Intel NEMU [VFIO passthrough](https://github.com/intel/nemu/wiki/Testing-VFIO-with-GPU)
