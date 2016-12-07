# Awesome Forensics

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Build Status](https://api.travis-ci.org/Cugu/awesome-forensics.svg?branch=master)](https://travis-ci.org/Cugu/awesome-forensics)

A curated list of awesome forensic analysis tools and resources.


- [Awesome Forensics](#awesome-forensics)
- [Collections](#collections)
- [Tools](#tools)
    - [Distributions](#distributions)
    - [Frameworks](#frameworks)
    - [Live forensics](#live-forensics)
    - [Imageing](#imageing)
    - [Carving](#carving)
    - [Memory Forensics](#memory-forensics)
    - [Network Forensics](#network-forensics)
    - [Windows Artifacts](#windows-artifacts)
    - [OS X Forensics](#os-x-forensics)
    - [Internet Artifacts](#internet-artifacts)
    - [Hex Editors](#hex-editors)
    - [Binary Converter](#binary-converter)
    - [File Grammars](#file-grammars)
    - [Disk image handling](#disk_image_handling)
    - [Decryption](#decryption)
- [Learn Forensics](#learn-forensics)
    - [CTFs](#ctfs)
- [Resources](#resources)
    - [File System Corpora](#file-system-corpora)
    - [Websites](#websites)
    - [Twitter](#twitter)
    - [Blogs](#blogs)
    - [Other](#other)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

---

# Collections
* [Devon Ackerman's Definitive DFIR Compendium Project](https://docs.google.com/spreadsheets/d/1JY-iyw-LEuPCkBAdjorMJhmhGRusN95eLmejWcky7XU/edit#gid=0) - Google Docs Sheets with lists of certifications, books, blogs, challenges and more
* [dfir.training](http://www.dfir.training/) - Database with events, tools and other forensics material

# Tools

## Distributions
* [deft](http://www.deftlinux.net/) - Linux distribution for forensic analysis

## Frameworks
* [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit) - Tools for low level forensic analysis
* [dff](https://github.com/arxsys/dff) - Forensic framework
* [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - PowerForensics is a framework for live disk forensic analysis

## Live forensics
* [mig](https://github.com/mozilla/mig) - Distributed & real time digital forensics at the speed of the cloud
* [grr](https://github.com/google/grr) - GRR Rapid Response: remote live forensics for incident response

## Imageing
* [FTK Imager](http://accessdata.com/product-download/digital-forensics/ftk-imager-version-3.4.2) - Free imageing tool
* [dcfldd](http://dcfldd.sourceforge.net/) - Improved version of dd
* [dc3dd](https://sourceforge.net/projects/dc3dd/) - Different improved version of dd

## Carving
* [bstrings](https://github.com/EricZimmerman/bstrings) - Improved strings utility
* [photorec](http://www.cgsecurity.org/wiki/PhotoRec) - File carving tool
* [see Maleware Analysis List](https://github.com/rshipp/awesome-malware-analysis#file-carving)

## Memory Forensics
* [volatility](https://github.com/volatilityfoundation/volatility) - The memory forensic framework
* [KeeFarce](https://github.com/denandz/KeeFarce) - Extract KeePass passwords from memory
* [see Maleware Analysis List](https://github.com/rshipp/awesome-malware-analysis#memory-forensics)

## Network Forensics
* [Wireshark](https://www.wireshark.org/) - The network traffic analysis tool

## Windows Artifacts
* [MFT-Parsers](http://az4n6.blogspot.de/2015/09/whos-your-master-mft-parsers-reviewed.html) - Comparison of MFT-Parsers
* [MFTExtractor](https://github.com/aarsakian/MFTExtractor) - MFT-Parser
* [python-ntfs](https://github.com/williballenthin/python-ntfs) - NTFS analysis
* [NTFS journal parser](http://strozfriedberg.github.io/ntfs-linker/)
* [NTFS USN Journal parser](https://github.com/PoorBillionaire/USN-Journal-Parser)
* [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector) - Collect artifacts on windows
* [see Maleware Analysis List](https://github.com/rshipp/awesome-malware-analysis#windows-artifacts)

## OS X Forensics
* [OSXAuditor](https://github.com/jipegit/OSXAuditor)

## Internet Artifacts
* [hindsight](https://github.com/obsidianforensics/hindsight) - Internet history forensics for Google Chrome/Chromium

## Hex Editors
* [HxD](https://mh-nexus.de/de/hxd/) - Small, fast hex editor for Windows
* [0xED](http://www.suavetech.com/0xed/) - Native hex editor for OS X
* [wxHex Editor](http://www.wxhexeditor.org/) - Cross platform editor with file comparison
* [iBored](http://apps.tempel.org/iBored/) - Cross platform, sektor based hex editor
* [Synalyze It!](http://www.synalysis.net/) - Hex editor with templates for binary analysis
* [Hexinator](https://hexinator.com/) - Windows Version of Synalyze It!

## Binary Converter
* [CyberChef](https://github.com/gchq/CyberChef) - The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis
* [DateDecode](http://sandersonforensics.com/forum/content.php?245-DateDecode-a-forensic-tool-to-decode-a-number-as-various-date-formats) - Convert binary data into differnt kinds of date formats

## File Grammars
* [WinHex Templates](https://www.x-ways.net/winhex/templates/) - Grammars for the WinHex editor and X-Ways
* [Synalyse It! Grammars](https://www.synalysis.net/formats.xml) - File type grammars for the Synalyze It! editor
* [HFSPlus Grammars](https://github.com/mac4n6/HFSPlus_Resources/tree/master/HFSPlus_Grammars) - HFS+ grammars for Synalysis
* [Contruct formats](https://github.com/construct/construct/tree/master/construct/examples/formats) - Parser for different file formats for the python construct package
* [010 Editor Templates](http://www.sweetscape.com/010editor/templates/) - Templates for the 010 Editor
* [Sleuth Kit file system grammars](https://github.com/sleuthkit/sleuthkit/tree/develop/tsk/fs) - Grammars for different file systems
* [TestDisk grammars](https://github.com/cgsecurity/testdisk/tree/master/src) - Grammars used by TestDisk and PhotoRec

## Disk image handling
* [libewf](https://github.com/libyal/libewf) - Libewf is a library and some tools to access the Expert Witness Compression Format (EWF, E01)
* [aff4](https://github.com/google/aff4) - AFF4 is an alternative, fast file format
* [xmount](https://www.pinguin.lu/xmount) - Convert between different disk image formats

## Decryption
* [John the Ripper](http://www.openwall.com/john/) - Password cracker
* [hashcat](https://hashcat.net/hashcat/) - Fast password cracker with GPU support

# Learn forensics

* [Forensic Challanges](http://www.amanhardikar.com/mindmaps/ForensicChallenges.html) - Mindmap of forensic challanges

## CTFs
* [Forensics CTFs](https://github.com/apsdehal/awesome-ctf/blob/master/README.md#forensics)

# Resources

## File System Corpora
* [Digital Forensics Tool Testing Images](http://dftt.sourceforge.net/)
* [The CFReDS Project](http://www.cfreds.nist.gov/)
  * [Hacking Case (4.5 GB NTFS Image)](http://www.cfreds.nist.gov/Hacking_Case.html)
* [FAU Open Research Challenge Digital Forensics](https://openresearchchallenge.org/digitalForensics/appliedforensiccomputinggroup)
* [Digital Forensic Challenge Images](http://www.ashemery.com/dfir.html) - Two DFIR challanges with images

## Websites
* [Forensics tools on Wikipedia](https://en.wikipedia.org/wiki/List_of_digital_forensics_tools)
* [Free computer forensic tools](https://forensiccontrol.com/resources/free-software/) - Comprehensive list of free computer forensic tools
* [Digital Forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#digital_forensics) - Online training material by European Union Agency for Network and Information Security
* [Network forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#network_forensics) - Online training material by European Union Agency for Network and Information Security

## Twitter
* [@4n6ist](https://twitter.com/4n6ist)
* [@4n6k](https://twitter.com/4n6k)
* [@aheadless](https://twitter.com/aheadless)
* [@AppleExaminer](https://twitter.com/AppleExaminer) - Apple OS X & iOS Digital Forensics
* [@blackbagtech](https://twitter.com/blackbagtech)
* [@carrier4n6](https://twitter.com/carrier4n6) - Brian Carrier, author of Autopsy and the Sleuth Kit
* [@CindyMurph](https://twitter.com/CindyMurph) - Detective & Digital Forensic Examiner
* [@forensikblog](https://twitter.com/forensikblog) - Computer forensic geek
* [@HECFBlog](https://twitter.com/HECFBlog) - SANS Certified Instructor
* [@Hexacorn](https://twitter.com/Hexacorn) - DFIR+Malware
* [@hiddenillusion](https://twitter.com/hiddenillusion)
* [@iamevltwin](https://twitter.com/iamevltwin) - Mac Nerd, Forensic Analyst, Author & Instructor of SANS FOR518 
* [@jaredcatkinson](https://twitter.com/jaredcatkinson) - PowerShell Forensics
* [@maridegrazia](https://twitter.com/maridegrazia) - Computer Forensics Examiner
* [@sleuthkit](https://twitter.com/sleuthkit)
* [@williballenthin](https://twitter.com/williballenthin)
* [@XWaysGuide](https://twitter.com/XWaysGuide)

## Blogs
* [thisweekin4n6.wordpress.com](thisweekin4n6.wordpress.com) - Weekly updates for forensics

## Other
* [/r/computerforensics/](https://www.reddit.com/r/computerforensics/) - Subreddit for computer forensics
* [ForensicPosters](https://github.com/Invoke-IR/ForensicPosters) - Posters of file system structures

# Related Awesome Lists

* [Android Security](https://github.com/ashishb/android-security-awesome)
* [AppSec](https://github.com/paragonie/awesome-appsec)
* [CTFs](https://github.com/apsdehal/awesome-ctf)
* ["Hacking"](https://github.com/carpedm20/awesome-hacking)
* [Honeypots](https://github.com/paralax/awesome-honeypots)
* [Incident-Response](https://github.com/meirwah/awesome-incident-response)
* [Infosec](https://github.com/onlurking/awesome-infosec)
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis)
* [PCAP Tools](https://github.com/caesar0301/awesome-pcaptools)
* [Pentesting](https://github.com/enaqx/awesome-pentest)
* [Security](https://github.com/sbilly/awesome-security)

# [Contributing](CONTRIBUTING.md)

Pull requests and issues with suggestions are welcome!


