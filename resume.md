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

My name is Andrea, and I am working every day to command every aspect of modern
computers.  I started learning scripting languages in my hometown in Nauvoo, IL
at the age of nine on the whiteboard with a longtime family friend before
eventually finding myself cutting my teeth on interesting contracts in the D.C.
and Baltimore areas.  I hope to one day be able to call myself a "full-stack
developer" as I get closer and closer to understanding the circuits that make up
modern computer systems.  Currently, I understand most things down to the
OS/embedded firmware level, but I am starting to dip my toes in the digital
logic/FPGA pool.

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

## Professional Summary
### High-Z, LLC | May 2023 to present
### Computer Engineer, Organizer
* Provide embedded firmware development services under contract.
* Offer software development and systems integration services to various
      customers.
* Develop networking solutions around yet-to-be-standardized NIST finalist
      algorithms.

### Cornerstone Integration, Inc. | October 2022 to May 2023
### Computer Engineer

* Ported embedded operating systems to new boards.
* Implemented solutions using remote out-of-band management.
* Prototyped networking solutions around yet-to-be-standardized NIST finalist algorithms.
* Wrote proof-of-concept code on embedded systems for public and private customers.

### Mahlet Consulting | August 2019 to April 2020
### Computer Engineer

* Worked on embedded C code that targeted MicroBlaze soft cores on Xilinx Ultrascale FPGAs
* Worked to port aforementioned C code from a big loop running on bare metal to FreeRTOS
* Wrote a C/Python extension wrapping Phil Karn’s LGPL’d Reed-Solomon FEC, adding an automated conformance testing suite
* Tested code on 100G OTN hardware with expensive QSFP modules
* Evaluated running Linux on Xilinx MicroBlaze soft cores
* Assembled a tcpreplay/DPDK cluster with a Python FastAPI frontend for testing network performance of our in-house IP cores

### MachineSense | April 2019 to July 2019
### Embedded IOT Engineer

* Responsible for deploying to over one hundred embedded ARM devices in an industrial environment
* Helped inform key architectural decisions in cloud and embedded middleware architecture
* Wrote SSH reverse shell tool for access to and configuration management of embedded ARM systems in industrial environments
  * Automatic sshd config file parsing
  * Forwards local SSH port to C&C server based on the embedded device’s MAC address(es)
  * Automatic key provisioning with synchronization to central RSA public key repository
* Repaired and added bodge components to misbehaving prototype boards during the development process
* Performed R&D testing on embedded machines monitoring industrial motors, vacuum pumps, blowers, and dryers
* Reverse-engineered competing product’s REST API
* Audited our web application for common security vulnerabilities
* Debugged ZMQ IPC sockets with custom pcap filter in tcpdump

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
* Responsible for key DevOps infrastructure for the Centers for Medicare and Medicaid Services
* Managed and upgraded HA Proxy, Nexus Repository Manager, Jenkins, and GitHub Enterprise servers
* Improved automated software deployment pipelines with Jenkins
* Deployed custom Red Hat Enterprise Linux AMIs to AWS
* Performed manual and automated deployments to Solaris infrastructure
* Wrote custom Bash shell scripts targeting GHE and Jira REST APIs
* Wrote custom script for monitoring Splunk forwarders

### Conduit Sports | September 2017 to February 2018
### Systems Administrator (Short-term contract)
* Built out a custom suite of VM provisioning and configuration scripts leveraging the Linode cloud API
* Helped our electrical engineer layout circuit boards using KiCAD, when not setting up cloud infrastructure

### Inspire | September 2016 to August 2017
### Software Engineer
* Responsible for maintaining backend code, updating site templates, and writing SQL for the Inspire website
* Resurrected old legacy code with modern patches
* Helped introduce new features to the site
* Deployed and used Bitbucket, GitHub Enterprise, and SSH-based pure Git installations to servers
* Deployed CircleCI continuous integration system
* Wrote experimental Python code to assist data scientist with her research
* Reviewed my peers’ Perl, SQL, and JavaScript code
* Helped test and develop the company’s TAP/prove-based test suite
* Updated our in-house release tools and scripts

### Jones LLC | July 2015 to September 2016
### Principal Systems Administrator
* Developed hardware and software solutions that allow parents to keep better tabs on their children’s web browsing habits and internet use
* Maintained Java code written by contractor
* Deployed and managed Bitbucket on Linode cloud
* Wrote new Bash shell scripts, daemons, and utilities
* Created custom Live ISO images for home network appliances with custom install scripts, Systemd units, daemons, and firewall rules
* Configured custom firewall rules using ufw, firewalld, and iptables
* Installed and deployed pfSense
* Managed switch administration and network cabling

## Open Source Contributions
### 2023
* Wrote automations for building Gentoo crossdev images using Podman containers.
* Fixed compiling Apple’s XNU kernel version 1504.15.3 on Snow Leopard on my darwin-xnu fork.
* Fixed compiling Apple’s C++ demangler on Snow Leopard on my fork.

### 2021

* Advanced Macintosh Substitute (AMS): I contributed a big-endian fix for the X11 frontend of my friend Josh Juran’s classic Macintosh emulator.
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
