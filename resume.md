---
header-includes:
  - \usepackage{hyperref}
  - \hypersetup{colorlinks=false,
            allbordercolors={0 0 0},
            pdfborderstyle={/S/U/W 1}}
---

# Andrea Rogers
**Email:** [targetdisk1394@gmail.com](mailto:targetdisk1394@gmail.com)
| **GitHub:** [targetdisk](https://github.com/targetdisk)
| **Website:** [sqt.wtf/~targetdisk](https://sqt.wtf/~targetdisk)

## Technical Overview

* C, C++, Objective-C, Java, Perl, Python, and shell programming
     * Able to learn new libraries, frameworks, and languages quickly
* Strong understanding of security best practices
* Amazon, Azure, Digital Ocean, Google, and Linode clouds
* Expert-level automation experience
  * Continuous integration with Circle CI, GitLab runners, and Jenkins
  * PCRE/grep/sed, Python re and ECMAScript regex
  * Linux: LFS, Yocto, Buildroot, Gentoo Crossdev, Red Hat, Debian/Ubuntu, SUSE, and others
  * KVM/Qemu, Xen, Docker, and Podman virtualization
  * Embedded toolchain and Linux image creation
* On-prem/colocated server administration
* WiFi and general hardware hacking, password cracking, and basic auth sniffing

## Open Source Contributions
### 2023
* Created a partially-working cross-compiler toolchain for 16-bit 8088/8086 (needs libC still).
* Created a RIFF-based file format based around my 1-bit RLE encoding scheme from the earlier Linux framebuffer application.
* Wrote a graphical UEFI program that mimics the look and feel of Apple’s New World PowerPC target disk mode UI.
* Wrote a mess of regex and C code to convert the Linux PMI project’s wiki from Trac to Markdown.
* Wrote a simple Linux framebuffer application with statically-compiled bitmapped graphics in 1-bit RLE, 32-bit RLE, and raw 32-bit RGBA image formats.
* Wrote a simple wrapper around Clang to aid in using clangd with more build systems.
* Wrote automations for building Gentoo crossdev images using Podman containers.
* Contributed various fixes to building Josh Juran’s Mac Relix on modern GCC like this one.
* Fixed compiling Apple’s XNU kernel version 1504.15.3 on Snow Leopard on my darwin-xnu fork.
* Fixed compiling Apple’s C++ demangler on Snow Leopard on my fork.

### 2021

* Advanced Macintosh Substitute (AMS): I contributed a big-endian fix for the X11 frontend of my friend Josh’s classic Macintosh emulator.
* avc_psp: a script that encodes videos for the Sony PSP’s very specific flavor of AVC (a subset of modern H.264). Can be run on batches of videos across a cluster of nodes.
* SnapCam for Python: A free software reimplementation of iON’s Camera+ app with a functional V4L2 streaming demo.
* squid-dl: A massively parallel yt-dlp-based YouTube downloader with proxying support.
* Wrote a test suite capable of testing Bash, C, Perl, and Python code from a single test harness.
  * https://github.com/swolegoal/weeb2psp/blob/main/scripts/test-runner

## Personal Study

* Learning Rust and Haskell as time permits
* 2022 - present, SecKC regular
* 2017 – 2021, Unallocated Space regular
* B-Sides DC 2017, Charm 2019, KC 2022, KC 2023, and KC 2024 attendee
  * 3rd place in 2017 B-Sides DC Wireless Village CTF
* 2016 – 2021, HacDC member
* 2016 - 2021, DC Perl Mongers
* 2014, Attended BYU-I for computer science

## Professional Summary
### High-Z, LLC | May 2023 to present
### Computer Engineer, Organizer
1. Provide embedded firmware development services under contract.
1. Offer software development and systems integration services to various customers.
1. Develop networking solutions around yet-to-be-standardized NIST finalist algorithms.

### Cornerstone Integration, Inc. | October 2022 to May 2023
### Computer Engineer

1. Ported embedded operating systems to new boards.
1. Implemented solutions using remote out-of-band management.
1. Prototyped networking solutions around yet-to-be-standardized NIST finalist algorithms.
1. Wrote proof-of-concept code on embedded systems for public and private customers.

### Mahlet Consulting | August 2019 to April 2020
### Computer Engineer

1. Worked on embedded C code that targeted MicroBlaze soft cores on Xilinx Ultrascale FPGAs
1. Worked to port aforementioned C code from a big loop running on bare metal to FreeRTOS
1. Wrote a C/Python extension wrapping Phil Karn’s LGPL’d Reed-Solomon FEC
  * Wrote automated test suite for my Reed-Solomon C/Python extension
1. Tested code on very expensive 100G OTN hardware with expensive QSFP modules (never broke anything!)
1. Experimented with running Linux on Xilinx MicroBlaze soft cores
1. Assembled a tcpreplay/DPDK cluster with a Python FastAPI frontend for testing network performance of our in-house IP cores.

### MachineSense | April 2019 to July 2019
### Embedded IOT Engineer

1. Helped inform key architectural decisions in cloud and embedded middleware architecture
1. Wrote SSH reverse shell tool for access to and configuration management of embedded ARM systems in industrial environments.
  * Automatic sshd config file parsing
  * Forwards local SSH port to C&C server based on the embedded device’s MAC address(es).
  * Automatic key provisioning with synchronization to central RSA public key repository.
1. Responsible for deploying to over one hundred embedded ARM devices in an industrial environment.
1. Reworked misbehaving prototype and final prototype boards with SMD hot-air soldering station and iron
1. Performed R&D testing on embedded machines monitoring industrial motors, vacuum pumps, blowers, and dryers
1. Built custom Linux-based firmware images for embedded hardware.
1. Reverse-engineered competing product’s REST API
1. Web app vulnerability testing
1. Debugged ZMQ IPC sockets with custom pcap filter in tcpdump

### Walmart Labs | October 2018 to February 2019
### Cloud Infrastructure Analyst
 * Provided recommendations and manual tagging changes to over 20,000 systems
 * Created python code to create new portals for other departments to request additional capacity
 * Supported 3000+ internal applications and their e-commerce in an Openstack cloud environment
 * Managed Walmart’s Azure cloud capacity
 * Reverse-engineered an internal Ruby-based tool with the Ruby debugger (without prior Ruby knowledge)
 * Performed capacity planning and performance analysis

### Ventech Solutions | February 2018 to August 2018
### DevOps Engineer
1. Responsible for key DevOps infrastructure for the Centers for Medicare and Medicaid Services
1. Managed and upgraded HA Proxy, Nexus Repository Manager, Jenkins, and GitHub Enterprise servers
1. Improved automated software deployment pipelines with Jenkins
1. Deployed custom Red Hat Enterprise Linux AMIs to AWS
1. Performed manual and automated deployments to Solaris infrastructure
1. Wrote custom Bash shell scripts targeting GHE and Jira REST APIs
1. Wrote custom script for monitoring Splunk forwarders

### Conduit Sports | September 2017 to February 2018
### Systems Administrator (Short-term contract)
1. Built out a custom suite of VM provisioning and configuration scripts leveraging the Linode cloud API
1. Helped our electrical engineer layout circuit boards using KiCAD, when not setting up cloud infrastructure

### Inspire | September 2016 to August 2017
### Software Engineer
1. Responsible for maintaining backend code, updating site templates, and writing SQL for the Inspire website
1. Resurrected old legacy code with modern patches
1. Helped introduce new features to the site
1. Deployed and used Bitbucket, GitHub Enterprise, and SSH-based pure Git installations to servers
1. Deployed CircleCI continuous integration system
1. Wrote experimental Python code to assist data scientist with her research
1. Reviewed my peers’ Perl, SQL, and JavaScript code
1. Helped test and develop the company’s TAP/prove-based test suite
1. Updated our in-house release tools and scripts

### Jones LLC | July 2015 to September 2016
### Principal Systems Administrator
1. Developed hardware and software solutions that allow parents to keep better tabs on their children’s web browsing habits and internet use
1. Maintained Java code written by contractor
1. Deployed and managed Bitbucket on Linode cloud
1. Wrote new Bash shell scripts, daemons, and utilities
1. Created custom Live ISO images for home network appliances with custom install scripts, Systemd units, daemons, and firewall rules
1. Configured custom firewall rules using ufw, firewalld, and iptables
1. Installed and deployed pfSense
1. Managed switch administration and network cabling
