Welcome to Awesome Fuzzing [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
===================

A curated list of fuzzing resources ( Books, courses - free and paid, videos, tools, tutorials and vulnerable applications to practice on ) for learning Fuzzing and initial phases of Exploit Development like root cause analysis.

### Contents
- [Books](#books)
- [Courses](#courses)
   + [Free](#free)
   + [Paid](#paid)
- [Videos](#videos)
  + [NYU Poly Course videos](#nyu-poly-course-videos)
  + [Conference talks and tutorials](#conference-talks-and-tutorials)
- [Tutorials and Blogs](#tutorials-and-blogs)
- [Tools](#tools)
  + [Cloud Fuzzers](#cloud-fuzzers)
  + [File Format Fuzzers](#file-format-fuzzers)
  + [Network Protocol Fuzzers](#network-protocol-fuzzers)
  + [Browser Fuzzing](#browser-fuzzing)
  + [Taint Analysis](#taint-analysis)
  + [Symbolic Execution SAT and SMT Solvers](#symbolic-execution-sat-and-smt-solvers)
  + [Essential Tools](#essential-tools)
- [Vulnerable Applications](#vulnerable-applications)
- [Anti-Fuzzing](#anti-fuzzing)
- [Contributing](#contributing)


# Awesome Fuzzing Resources

## Books

*Books on fuzzing*
- [Fuzzing: Brute Force Vulnerability Discovery](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119) by Michael Sutton, Adam Greene, Pedram Amini.

- [Fuzzing for Software Security Testing and Quality Assurance ](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507) by Ari Takanen, Charles Miller, Jared D Demott and Atte Kettunen.

- [Open Source Fuzzing Tools](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950) by by Gadi Evron and Noam Rathaus.

- [Gray Hat Python](https://www.amazon.com/Gray-Hat-Python-Programming-Engineers/dp/1593271921) by Justin Seitz.


> **Note:** Chapter(s) in the following books are dedicated to fuzzing.

> - [The Shellcoder's Handbook: Discovering and Exploiting Security Holes ( Chapter 15 )](https://www.amazon.com/Shellcoders-Handbook-Discovering-Exploiting-Security/dp/047008023X) by Chris Anley, Dave Aitel, David Litchfield and others.

> - [iOS Hacker's Handbook - Chapter 1](https://www.amazon.com/iOS-Hackers-Handbook-Charlie-Miller/dp/1118204123) Charles Miller, Dino DaiZovi, Dion Blazakis, Ralf-Philip Weinmann, and Stefan Esser.

> - [IDA Pro - The IDA Pro Book: The Unofficial Guide to the World's Most Popular Disassembler](https://www.amazon.com/IDA-Pro-Book-2nd-ebook/dp/B005EI84TM)


## Courses

*Courses/Training videos on fuzzing*


### Free  

[NYU Poly ( see videos for more )](https://vimeo.com/5236104 ) - Made available freely by Dan Guido.

[Samclass.info ( check projects section and chapter 17 ) ](https://samsclass.info/127/127_F15.shtml) - by Sam.

[Modern Binary Exploitation ( RPISEC ) - Chapter 15 ](https://github.com/RPISEC/MBE) - by RPISEC.

[Offensive Computer Security - Week 6](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) - by W. Owen Redwood and Prof. Xiuwen Liu. 

### Paid

[Offensive Security, Cracking The Perimeter ( CTP ) and Advanced Windows Exploitation ( AWE )](https://www.offensive-security.com/information-security-training/)

[SANS 660/760 Advanced Exploit Development for Penetration Testers](https://www.sans.org/course/advanced-exploit-development-penetration-testers)

[Exodus Intelligence - Vulnerability development master class](https://blog.exodusintel.com/2016/05/18/exodus-intelligence-2016-training-course/)


## Videos

*Videos talking about fuzzing techniques, tools and best practices*


### NYU Poly Course videos
[Fuzzing 101 (Part 1)](https://vimeo.com/5236104) - by Mike Zusman.

[Fuzzing 101 (Part 2)](https://vimeo.com/5237484) - by Mike Zusman.

[Fuzzing 101 (2009)](https://vimeo.com/7574602) - by Mike Zusman.

[Fuzzing - Software Security Course on Coursera](https://www.coursera.org/lecture/software-security/fuzzing-VgyOn) - by University of Maryland.

### Conference talks and tutorials
[Youtube Playlist of various fuzzing talks and presentations ](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD) - Lots of good content in these videos. 

[Browser bug hunting - Memoirs of a last man standing](https://vimeo.com/109380793) - by Atte Kettunen

[Coverage-based Greybox Fuzzing as Markov Chain](https://www.comp.nus.edu.sg/~mboehme/paper/CCS16.pdf)

[DerbyCon 2016: Fuzzing basics...or how to break software](http://www.irongeek.com/i.php?page=videos/derbycon6/411-fuzzing-basicshow-to-break-software-grid-aka-scott-m)


## Tutorials and Blogs

*Tutorials and blogs which explain methodology, techniques and best practices of fuzzing*

[Effective File Format Fuzzing](https://j00ru.vexillium.org/slides/2016/blackhat.pdf) - Mateusz “j00ru” Jurczyk @ Black Hat Europe 2016, London

[A year of Windows kernel font fuzzing Part-1 the results](https://googleprojectzero.blogspot.com/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html) - Amazing article by Google's Project Zero, describing what it takes to do fuzzing and create fuzzers.

[A year of Windows kernel font fuzzing Part-2 the techniques](https://googleprojectzero.blogspot.com/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html) - Amazing article by Google's Project Zero, describing what it takes to do fuzzing and create fuzzers.

[Interesting bugs and resources at fuzzing project](https://blog.fuzzing-project.org/) - by fuzzing-project.org.

[Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) - by @BrandonPrry.

[A gentle introduction to fuzzing C++ code with AFL and libFuzzer](http://jefftrull.github.io/c++/clang/llvm/fuzzing/sanitizer/2015/11/27/fuzzing-with-sanitizers.html) - by Jeff Trull.

[A 15 minute introduction to fuzzing](https://www.mwrinfosecurity.com/our-thinking/15-minute-guide-to-fuzzing/) - by folks at MWR Security.

> **Note:** Folks at fuzzing.info has done a great job of collecting some awesome links, I'm not going to duplicate their work. I will add papers missed by them and from 2015 and 2016.
[Fuzzing Papers](https://fuzzing.info/papers/) - by fuzzing.info

[Fuzzing Blogs](https://fuzzing.info/resources/) - by fuzzing.info 

[Root Cause Analysis of the Crash during Fuzzing](
https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - by Corelan Team. 
[Root cause analysis of integer flow](https://www.corelan.be/index.php/2013/07/02/root-cause-analysis-integer-overflows/) - by Corelan Team.

[Creating custom peach fuzzer publishers](http://blog.opensecurityresearch.com/2014/01/creating-custom-peach-fuzzer-publishers.html) - by Open Security Research

[7 Things to Consider Before Fuzzing a Large Open Source Project](https://www.linuxfoundation.org/blog/2016/02/7-things-to-consider-before-fuzzing-a-large-open-source-project/) - by Emily Ratliff.


##### From Fuzzing to Exploit:
[From fuzzing to 0-day](https://blog.techorganic.com/2014/05/14/from-fuzzing-to-0-day/) - by Harold Rodriguez(@superkojiman).

[From crash to exploit](https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - by Corelan Team. 

##### Peach Fuzzer related tutorials

[Getting Started with Peach](http://community.peachfuzzer.com/v2/PeachQuickstart.html)

[Fuzzing with Peach Part 1](http://www.flinkd.org/fuzzing-with-peach-part-1/) - by Jason Kratzer of corelan team


[Fuzzing with Peach Part 2](http://www.flinkd.org/fuzzing-with-peach-part-2-fixups-2/) - by Jason Kratzer of corelan team.

[Auto generation of Peach pit files/fuzzers](http://doc.netzob.org/en/latest/tutorials/peach.html) - by Frédéric Guihéry, Georges Bossert.

##### AFL Fuzzer related tutorials
[Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) - by @BrandonPrry.

[Fuzzing capstone using AFL persistent mode](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html) - by @toasted_flakes

[RAM disks and saving your SSD from AFL Fuzzing](http://cipherdyne.org/blog/2014/12/ram-disks-and-saving-your-ssd-from-afl-fuzzing.html)

[Bug Hunting with American Fuzzy Lop](https://josephg.com/blog/bug-hunting-with-american-fuzzy-lop/)

[Advanced usage of American Fuzzy Lop with real world examples](https://volatileminds.net/2015/07/01/advanced-afl-usage.html)

[Segfaulting Python with afl-fuzz](https://tomforb.es/segfaulting-python-with-afl-fuzz)

[Fuzzing With AFL-Fuzz, a Practical Example ( AFL vs Binutils )](https://www.evilsocket.net/2015/04/30/fuzzing-with-afl-fuzz-a-practical-example-afl-vs-binutils/)

[The Importance of Fuzzing...Emulators?](https://mgba.io/2016/09/13/fuzzing-emulators/)

[How Heartbleed could've been found](https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html)

[Filesystem Fuzzing with American Fuzzy lop](https://events.static.linuxfound.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)

[Fuzzing Perl/XS modules with AFL](https://medium.com/@dgryski/fuzzing-perl-xs-modules-with-afl-4bfc2335dd90)

[How to fuzz a server with American Fuzzy Lop](https://www.fastly.com/blog/how-fuzz-server-american-fuzzy-lop) - by Jonathan Foote

[Fuzzing with AFL Workshop - a set of challenges on real vulnerabilities](https://github.com/ThalesIgnite/afl-training)

[Fuzzing 101 - PHDays](https://github.com/RootUp/PHDays9)

##### libFuzzer Fuzzer related tutorials

[libFuzzer Tutorial](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)

[libFuzzer Workshop: "Modern fuzzing of C/C++ Projects"](https://github.com/Dor1s/libfuzzer-workshop)

##### honggfuzz related tutorials

[Double-Free RCE in VLC. A honggfuzz how-to](https://www.pentestpartners.com/security-blog/double-free-rce-in-vlc-a-honggfuzz-how-to/)

##### Spike Fuzzer related tutorials

[Fuzzing with Spike to find overflows](https://null-byte.wonderhowto.com/how-to/hack-like-pro-build-your-own-exploits-part-3-fuzzing-with-spike-find-overflows-0162789/)

[Fuzzing with Spike](https://samsclass.info/127/proj/p18-spike.htm) - by samclass.info


##### FOE Fuzzer related tutorials

[Fuzzing with FOE](https://samsclass.info/127/proj/p16-fuzz.htm) - by Samclass.info


##### SMT/SAT solver tutorials

[Z3 - A guide](https://rise4fun.com/z3/tutorial/guide) - Getting Started with Z3: A Guide

##### Building a Feedback Fuzzer (for educational purposes)

[Building A Feedback Fuzzer](https://blog.fadyothman.com/tag/myfuzzer/) - by @fady_othman

## Tools

*Tools which helps in fuzzing applications*

### Cloud Fuzzers

*Fuzzers which help fuzzing in cloud environments.*

[Cloudfuzzer](https://github.com/ouspg/cloudfuzzer) - Cloud fuzzing framework which makes it possible to easily run automated fuzz-testing in cloud environments.

[ClusterFuzzer](https://google.github.io/clusterfuzz/) - ClusterFuzzer, scalable open source fuzzing infrastructure. It is used by Google for fuzzing Chrome Browser.

[Fuzzit](https://fuzzit.dev) - Fuzzit, Continuous fuzzing as a service platform. Free for open source. used by various open-source projects (systemd, radare2) and close-source projects. To join oss program drop a line at oss@fuzzit.dev

### File Format Fuzzers

*Fuzzers which helps in fuzzing file formats like pdf, mp3, swf etc.,*

[MiniFuzz - Wayback Machine link](https://web.archive.org/web/20140512203517/http://download.microsoft.com/download/D/6/E/D6EDC908-A1D7-4790-AB0B-66A8B35CD931/MiniFuzzSetup.msi) - Basic file format fuzzing tool by Microsoft. (No longer available on Microsoft website).

[BFF from CERT](https://resources.sei.cmu.edu/library/asset-view.cfm?assetID=507974) - Basic Fuzzing Framework for file formats.

[AFL Fuzzer (Linux only)]( http://lcamtuf.coredump.cx/afl/) - American Fuzzy Lop Fuzzer by Michal Zalewski aka lcamtuf

[Win AFL](https://github.com/ivanfratric/winafl) - A fork of AFL for fuzzing Windows binaries by Ivan Fratic

[Shellphish Fuzzer](https://github.com/shellphish/fuzzer) - A Python interface to AFL, allowing for easy injection of testcases and other functionality.

[TriforceAFL](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/june/project-triforce-run-afl-on-everything/) - A modified version of AFL that supports fuzzing for applications whose source code not available.

[Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/) - Framework which helps to create custom dumb and smart fuzzers.

[MozPeach](https://github.com/MozillaSecurity/peach) - A fork of peach 2.7 by Mozilla Security.

[Failure Observation Engine (FOE)](www.cert.org/vulnerability-analysis/tools/foe.cfm) - mutational file-based fuzz testing tool for windows applications.

[rmadair](http://rmadair.github.io/fuzzer/) - mutation based file fuzzer that uses PyDBG to monitor for signals of interest.

[honggfuzz](https://github.com/google/honggfuzz) - A general-purpose, easy-to-use fuzzer with interesting analysis options. Supports feedback-driven fuzzing based on code coverage. Supports GNU/Linux, FreeBSD, Mac OSX and Android.

[zzuf](https://github.com/samhocevar/zzuf) - A transparent application input fuzzer. It works by intercepting file operations and changing random bits in the program's input.

[radamsa](https://github.com/aoh/radamsa) - A general purpose fuzzer and test case generator.

[binspector](https://github.com/binspector/binspector) - A binary format analysis and fuzzing tool

[grammarinator](https://github.com/renatahodovan/grammarinator) - Fuzzing tool for file formats based on ANTLR v4 grammars (lots of grammars already available from the ANTLR project).

### Network Protocol Fuzzers

*Fuzzers which helps in fuzzing applications which use network based protocals like HTTP, SSH, SMTP etc.,*

[Peach Fuzzer](https://sourceforge.net/projects/peachfuzz/) - Framework which helps to create custom dumb and smart fuzzers.

[Sulley](https://github.com/OpenRCE/sulley) -  A fuzzer development and fuzz testing framework consisting of multiple extensible components by Pedram Amini.

[boofuzz](https://github.com/jtpereyda/boofuzz) -  A fork and successor of Sulley framework.

[Spike](http://www.immunitysec.com/downloads/SPIKE2.9.tgz) - A fuzzer development framework like sulley, a predecessor of sulley. 

[Metasploit Framework](https://github.com/rapid7/metasploit-framework) - A framework which contains some fuzzing capabilities via Auxiliary modules. 

[Nightmare](https://github.com/joxeankoret/nightmare) - A distributed fuzzing testing suite with web administration, supports fuzzing using network protocols.

[rage_fuzzer](https://github.com/deanjerkovich/rage_fuzzer) - A dumb protocol-unaware packet fuzzer/replayer.

[Fuzzotron](https://github.com/denandz/fuzzotron) - A simple network fuzzer supporting TCP, UDP and multithreading.

[Mutiny](https://github.com/Cisco-Talos/mutiny-fuzzer) - The Mutiny Fuzzing Framework is a network fuzzer that operates by replaying PCAPs through a mutational fuzzer.

[Fuzzing For Worms](https://github.com/dobin/ffw) - A fuzzing framework for network servers.

### Browser Fuzzing
[BFuzz](https://github.com/RootUp/BFuzz) - An input based, browser fuzzing framework.

### Misc 
*Other notable fuzzers like Kernel Fuzzers, general purpose fuzzer etc.,*

[Choronzon](https://github.com/CENSUS/choronzon) - An evolutionary knowledge-based fuzzer

[QuickFuzz](https://github.com/CIFASIS/QuickFuzz) - A tool written in Haskell designed for testing un-expected inputs of common file formats on third-party software, taking advantage of off-the-shelf, well known fuzzers.

[gramfuzz](https://github.com/d0c-s4vage/gramfuzz) - A grammar-based fuzzer that lets one define complex grammars to model text and binary data formats

[KernelFuzzer](https://github.com/mwrlabs/KernelFuzzer) - Cross Platform Kernel Fuzzer Framework.

[honggfuzz](http://honggfuzz.com/) - A general-purpose, easy-to-use fuzzer with interesting analysis options.

[Hodor Fuzzer](https://github.com/nccgroup/hodor) - Yet Another general purpose fuzzer.

[libFuzzer](http://llvm.org/docs/LibFuzzer.html) - In-process, coverage-guided, evolutionary fuzzing engine for targets written in C/C++.

[syzkaller](https://github.com/google/syzkaller) - Distributed, unsupervised, coverage-guided Linux syscall fuzzer.

[ansvif](https://oxagast.github.io/ansvif/) - An advanced cross platform fuzzing framework designed to find vulnerabilities in C/C++ code.

[Tribble](https://github.com/SatelliteApplicationsCatapult/tribble) - Easy-to-use, coverage-guided JVM fuzzing framework. 

[go-fuzz](https://github.com/dvyukov/go-fuzz) - Coverage-guided testing of go packages.

[FExM](https://github.com/fgsect/fexm) - Automated Large-Scale Fuzzing Framework

### Taint Analysis
*How user input affects the execution*

[PANDA ( Platform for Architecture-Neutral Dynamic Analysis )](https://github.com/moyix/panda)

[QIRA (QEMU Interactive Runtime Analyser)](http://qira.me/)

[kfetch-toolkit](https://github.com/j00ru/kfetch-toolkit) - Tool to perform advanced logging of memory references performed by operating systems’ kernels

[moflow](https://github.com/vrtadmin/moflow) - A software security framework containing tools for vulnerability, discovery, and triage.

### Symbolic Execution SAT and SMT Solvers

[Z3](https://github.com/Z3Prover/z3) - A theorem prover from Microsoft Research.

[SMT-LIB](http://smtlib.cs.uiowa.edu/) - An international initiative aimed at facilitating research and development in Satisfiability Modulo Theories (SMT)


### References

I haven't included some of the legends like AxMan, please refer the following link for more information.
https://www.ee.oulu.fi/research/ouspg/Fuzzers 


### Essential Tools

*Tools of the trade for exploit developers, reverse engineers*


#### Debuggers 


[Windbg](https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools) - The preferred debugger by exploit writers.

[Immunity Debugger](http://debugger.immunityinc.com) - Immunity Debugger by Immunity Sec.

[OllyDbg ](http://www.ollydbg.de/) - The debugger of choice by reverse engineers and exploit writers alike.

[Mona.py ( Plugin for windbg and Immunity dbg )](https://github.com/corelan/mona/) - Awesome tools that makes life easy for exploit developers.

[x64dbg](https://github.com/x64dbg/) - An open-source x64/x32 debugger for windows.

[Evan's Debugger (EDB)](http://codef00.com/projects#debugger) - Front end for gdb.

[GDB - Gnu Debugger](http://www.sourceware.org/gdb/) - The favorite linux debugger.

[PEDA](https://github.com/longld/peda) - Python Exploit Development Assistance for GDB.

[Radare2](http://www.radare.org/r/) - Framework for reverse-engineering and analyzing binaries.


#### Disassemblers and some more

*Dissemblers, disassembly frameworks etc.,*


[IDA Pro](https://www.hex-rays.com/products/ida/index.shtml) - The best disassembler

[binnavi](https://github.com/google/binnavi) - Binary analysis IDE, annotates control flow graphs and call graphs of disassembled code.

[Capstone](https://github.com/aquynh/capstone) - Capstone is a lightweight multi-platform, multi-architecture disassembly framework.


#### Others

[ltrace](http://ltrace.org/) - Intercepts library calls 

[strace](https://sourceforge.net/projects/strace/) - Intercepts system calls


## Vulnerable Applications

Exploit-DB - https://www.exploit-db.com
(search and pick the exploits, which have respective apps available for download, reproduce the exploit by using fuzzer of your choice)

PacketStorm - https://packetstormsecurity.com/files/tags/exploit/

[Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - Vulnerable C program for testing fuzzers.

[vulnserver](https://github.com/stephenbradshaw/vulnserver) - A vulnerable server for testing fuzzers.


##### Samples files for seeding during fuzzing:

https://files.fuzzing-project.org/

[PDF Test Corpus from Mozilla](https://github.com/mozilla/pdf.js/tree/master/test/pdfs)

[MS Office file format documentation](https://www.microsoft.com/en-us/download/details.aspx?id=14565)

[Fuzzer Test Suite](https://github.com/google/fuzzer-test-suite) - Set of tests for fuzzing engines. Includes different well-known bugs such as Heartbleed, c-ares $100K bug and others.

[Fuzzing Corpus](https://github.com/strongcourage/fuzzing-corpus) - A corpus, including various file formats for fuzzing multiple targets in the fuzzing literature.

## Anti Fuzzing

[Introduction to Anti-Fuzzing: A Defence In-Depth Aid](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2014/january/introduction-to-anti-fuzzing-a-defence-in-depth-aid/)


## Contributing

[Please refer the guidelines at contributing.md for details](Contributing.md).

Thanks to the following folks who made contributions to this project. 
+ [Tim Strazzere](https://twitter.com/timstrazz)
+ [jksecurity](https://github.com/jksecurity)
+ [and these awesome people](https://github.com/secfigo/Awesome-Fuzzing/graphs/contributors)


### Table of Contents
- [Books](#books)
- [Courses](#courses)
   + [Free](#free)
   + [Paid](#paid)
- [Videos](#videos)
  + [NYU Poly Course videos](#nyu-poly-course-videos)
  + [Conference talks and tutorials](#conference-talks-and-tutorials)
- [Tutorials and Blogs](#tutorials-and-blogs)
- [Tools](#tools)
  + [File Format Fuzzers](#file-format-fuzzers)
  + [Network Protocol Fuzzers](#network-protocol-fuzzers)
  + [Taint Analysis](#taint-analysis)
  + [Symbolic Execution SAT and SMT Solvers](#symbolic-execution-sat-and-smt-solvers)
  + [Essential Tools](#essential-tools)
- [Vulnerable Applications](#vulnerable-applications)
- [Anti-Fuzzing](#anti-fuzzing)
- [Contributing](#contributing)


# Awesome Fuzzing Resources

## Books

*Books on fuzzing*
- [Fuzzing: Brute Force Vulnerability Discovery](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119) by Michael Sutton, Adam Greene, Pedram Amini.

- [Fuzzing for Software Security Testing and Quality Assurance ](https://www.amazon.com/Fuzzing-Software-Security-Assurance-Information/dp/1596932147) by Ari Takanen, Charles Miller, and Jared D Demott.

- [Open Source Fuzzing Tools](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950) by by Gadi Evron and Noam Rathaus.

- [Gray Hat Python](https://www.amazon.com/Gray-Hat-Python-Programming-Engineers/dp/1593271921) by Justin Seitz.


> **Note:** Chapter(s) in the following books are dedicated to fuzzing.

> - [The Shellcoder's Handbook: Discovering and Exploiting Security Holes ( Chapter 15 )](https://www.amazon.com/Shellcoders-Handbook-Discovering-Exploiting-Security/) by Chris Anley, Dave Aitel, David Litchfield and others.

> - [iOS Hacker's Handbook - Chapter 1](https://www.amazon.com/iOS-Hackers-Handbook-Charlie-Miller/dp/1118204123/) Charles Miller, Dino DaiZovi, Dion Blazakis, Ralf-Philip Weinmann, and Stefan Esser.

> - [IDA Pro - The IDA Pro Book: The Unofficial Guide to the World's Most Popular Disassembler](https://www.amazon.com/IDA-Pro-Book-Unofficial-Disassembler-ebook/dp/B005EI84TM)


## Courses

*Courses/Training videos on fuzzing*


### Free  

[NYU Poly ( see videos for more )](https://vimeo.com/5236104 ) - Made available freely by Dan Guido.

[Samclass.info ( check projects section and chapter 17 ) ](https://samsclass.info/127/127_F15.shtml) - by Sam.

[Modern Binary Exploitation ( RPISEC ) - Chapter 15 ](https://github.com/RPISEC/MBE) - by RPISEC.

[Offensive Computer Security - Week 6](http://www.cs.fsu.edu/~redwood/OffensiveComputerSecurity/lectures.html) - by W. Owen Redwood and Prof. Xiuwen Liu. 

### Paid

[Offensive Security, Cracking The Perimeter ( CTP ) and Advanced Windows Exploitation ( AWE )](https://www.offensive-security.com/information-security-training/)

[SANS 660/760 Advanced Exploit Development for Penetration Testers](https://www.sans.org/course/advance-exploit-development-pentetration-testers)

[Exodus Intelligence - Vulnerability development master class](https://blog.exodusintel.com/2016/05/18/exodus-intelligence-2016-training-course/)


## Videos

*Videos talking about fuzzing techniques, tools and best practices*


### NYU Poly Course videos
[Fuzzing 101 (Part 1)](https://vimeo.com/5236104) - by Mike Zusman.

[Fuzzing 101 (Part 2)](https://vimeo.com/5237484) - by Mike Zusman.

[Fuzzing 101 (2009)](https://vimeo.com/7574602) - by Mike Zusman.

[Fuzzing - Software Security Course on Coursera](https://www.coursera.org/learn/software-security/lecture/VgyOn/fuzzing) - by University of Maryland.

### Conference talks and tutorials
[Youtube Playlist of various fuzzing talks and presentations ](https://www.youtube.com/playlist?list=PLtPrYlwXDImiO_hzK7npBi4eKQQBgygLD) - Lots of good content in these videos. 

[Browser bug hunting - Memoirs of a last man standing](https://vimeo.com/109380793) - by Atte Kettunen

[Coverage-based Greybox Fuzzing as Markov Chain](https://www.comp.nus.edu.sg/~mboehme/paper/CCS16.pdf)


## Tutorials and Blogs

*Tutorials and blogs which explain methodology, techniques and best practices of fuzzing*

### [2016 articles]

[Effective File Format Fuzzing](http://j00ru.vexillium.org/slides/2016/blackhat.pdf) - Mateusz “j00ru” Jurczyk @ Black Hat Europe 2016, London

[A year of Windows kernel font fuzzing Part-1 the results](http://googleprojectzero.blogspot.in/2016/06/a-year-of-windows-kernel-font-fuzzing-1_27.html) - Amazing article by Google's Project Zero, describing what it takes to do fuzzing and create fuzzers.

[A year of Windows kernel font fuzzing Part-2 the techniques](http://googleprojectzero.blogspot.in/2016/07/a-year-of-windows-kernel-font-fuzzing-2.html) - Amazing article by Google's Project Zero, describing what it takes to do fuzzing and create fuzzers.

[Interesting bugs and resources at fuzzing project](https://blog.fuzzing-project.org/) - by fuzzing-project.org.

[Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) - by @BrandonPrry.

[A gentle introduction to fuzzing C++ code with AFL and libFuzzer](http://jefftrull.github.io/c++/clang/llvm/fuzzing/sanitizers/2015/11/27/fuzzing-with-sanitizers.html) - by Jeff Trull.

[A 15 minute introduction to fuzzing](https://www.mwrinfosecurity.com/our-thinking/15-minute-guide-to-fuzzing/) - by folks at MWR Security.

> **Note:** Folks at fuzzing.info has done a great job of collecting some awesome links, I'm not going to duplicate their work. I will add papers missed by them and from 2015 and 2016.
[Fuzzing Papers](https://fuzzing.info/papers) - by fuzzing.info

[Fuzzing Blogs](https://fuzzing.info/resources/) - by fuzzing.info 

[Root Cause Analysis of the Crash during Fuzzing](
https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - by Corelan Team. 
[Root cause analysis of integer flow](https://www.corelan.be/index.php/2013/07/02/root-cause-analysis-integer-overflows/) - by Corelan Team.

[Creating custom peach fuzzer publishers](http://blog.opensecurityresearch.com/2014/01/creating-custom-peach-fuzzer-publishers.html) - by Open Security Research

[7 Things to Consider Before Fuzzing a Large Open Source Project](https://www.linux.com/blog/7-things-consider-fuzzing-large-open-source-project) - by Emily Ratliff.


##### From Fuzzing to Exploit:
[From fuzzing to 0-day](https://blog.techorganic.com/2014/05/14/from-fuzzing-to-0-day/) - by Harold Rodriguez(@superkojiman).

[From crash to exploit](https://www.corelan.be/index.php/2013/02/26/root-cause-analysis-memory-corruption-vulnerabilities/) - by Corelan Team. 

##### Peach Fuzzer related tutorials

[Getting Started with Peach](http://community.peachfuzzer.com/v2/PeachQuickstart.html)

[Fuzzing with Peach Part 1](http://www.flinkd.org/fuzzing-with-peach-part-1/) - by Jason Kratzer of corelan team


[Fuzzing with Peach Part 2](http://www.flinkd.org/fuzzing-with-peach-part-2-fixups-2/) - by Jason Kratzer of corelan team.

[Auto generation of Peach pit files/fuzzers](http://doc.netzob.org/en/latest/tutorials/peach.html) - by Frédéric Guihéry, Georges Bossert.

##### AFL Fuzzer related tutorials
[Fuzzing workflows; a fuzz job from start to finish](https://foxglovesecurity.com/2016/03/15/fuzzing-workflows-a-fuzz-job-from-start-to-finish/) - by @BrandonPrry.

[Fuzzing capstone using AFL persistent mode](https://toastedcornflakes.github.io/articles/fuzzing_capstone_with_afl.html) - by @toasted_flakes

[RAM disks and saving your SSD from AFL Fuzzing](http://cipherdyne.org/blog/2014/12/ram-disks-and-saving-your-ssd-from-afl-fuzzing.html)

[Bug Hunting with American Fuzzy Lop](https://josephg.com/blog/bug-hunting-with-american-fuzzy-lop/)

[Advanced usage of American Fuzzy Lop with real world examples](http://volatileminds.net/2015/07/01/advanced-afl-usage.html)

[Segfaulting Python with afl-fuzz](http://tomforb.es/segfaulting-python-with-afl-fuzz)

[Fuzzing Perl: A Tale of Two American Fuzzy Lops](http://www.geeknik.net/71nvhf1fp)

[Fuzzing With AFL-Fuzz, a Practical Example ( AFL vs Binutils )](https://www.evilsocket.net/2015/04/30/fuzzing-with-afl-fuzz-a-practical-example-afl-vs-binutils/)

[The Importance of Fuzzing...Emulators?](https://mgba.io/2016/09/13/fuzzing-emulators/)

[How Heartbleed could've been found](https://blog.hboeck.de/archives/868-How-Heartbleed-couldve-been-found.html)

[Filesystem Fuzzing with American Fuzzy lop](http://events.linuxfoundation.org/sites/events/files/slides/AFL%20filesystem%20fuzzing%2C%20Vault%202016_0.pdf)

[Fuzzing Perl/XS modules with AFL](https://medium.com/@dgryski/fuzzing-perl-xs-modules-with-afl-4bfc2335dd90)

[How to fuzz a server with American Fuzzy Lop](https://www.fastly.com/blog/how-fuzz-server-american-fuzzy-lop/) - by Jonathan Foote

##### libFuzzer Fuzzer related tutorials

[libFuzzer Tutorial](http://tutorial.libfuzzer.info)

[libFuzzer Workshop: "Modern fuzzing of C/C++ Projects"](https://github.com/Dor1s/libfuzzer-workshop)


##### Spike Fuzzer related tutorials

[Fuzzing with Spike to find overflows](http://null-byte.wonderhowto.com/how-to/hack-like-pro-build-your-own-exploits-part-3-fuzzing-with-spike-find-overflows-0162789/)

[Fuzzing with Spike](https://samsclass.info/127/proj/p18-spike.htm) - by samclass.info


##### FOE Fuzzer related tutorials

[Fuzzing with FOE](https://samsclass.info/127/proj/p16-fuzz.htm) - by Samclass.info


##### SMT/SAT solver tutorials

[Z3 - A guide](http://rise4fun.com/z3/tutorial/guide) - Getting Started with Z3: A Guide


## Tools

*Tools which helps in fuzzing applications*


### File Format Fuzzers

*Fuzzers which helps in fuzzing file formats like pdf, mp3, swf etc.,*

[MiniFuzz](https://www.microsoft.com/en-sg/download/details.aspx?id=21769) - Basic file format fuzzing tool by Microsoft.

[BFF from CERT](https://www.cert.org/vulnerability-analysis/tools/bff.cfm?) - Basic Fuzzing Framework for file formats.

[AFL Fuzzer (Linux only)]( http://lcamtuf.coredump.cx/afl/) - American Fuzzy Lop Fuzzer by Michal Zalewski aka lcamtuf

[Win AFL](https://github.com/ivanfratric/winafl) - A fork of AFL for fuzzing Windows binaries by Ivan Fratic

[Shellphish Fuzzer](https://github.com/shellphish/fuzzer) - A Python interface to AFL, allowing for easy injection of testcases and other functionality.

[TriforceAFL](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2016/june/project-triforce-run-afl-on-everything/) - A modified version of AFL that supports fuzzing for applications whose source code not available.

[Peach Fuzzer](https://peachfuzz.sourceforge.net/) - Framework which helps to create custom dumb and smart fuzzers.

[MozPeach](https://github.com/MozillaSecurity/peach) - A fork of peach 2.7 by Mozilla Security.

[Failure Observation Engine (FOE)](www.cert.org/vulnerability-analysis/tools/foe.cfm) - mutational file-based fuzz testing tool for windows applications.

[rmadair](http://rmadair.github.io/fuzzer/) - mutation based file fuzzer that uses PyDBG to monitor for signals of interest.

[honggfuzz](https://github.com/google/honggfuzz) - A general-purpose, easy-to-use fuzzer with interesting analysis options. Supports feedback-driven fuzzing based on code coverage. Supports GNU/Linux, FreeBSD, Mac OSX and Android.

[zzuf](https://github.com/samhocevar/zzuf) - A transparent application input fuzzer. It works by intercepting file operations and changing random bits in the program's input.

[radamsa](https://github.com/aoh/radamsa) - A general purpose fuzzer and test case generator.

[binspector](https://github.com/binspector/binspector) - A binary format analysis and fuzzing tool

### Network Protocol Fuzzers

*Fuzzers which helps in fuzzing applications which use network based protocals like HTTP, SSH, SMTP etc.,*

[Peach Fuzzer](https://peachfuzz.sourceforge.net/) - Framework which helps to create custom dumb and smart fuzzers.

[Sulley](https://github.com/OpenRCE/sulley) -  A fuzzer development and fuzz testing framework consisting of multiple extensible components by Michael Sutton.

[boofuzz](https://github.com/jtpereyda/boofuzz) -  A fork and successor of Sulley framework.

[Spike](http://www.immunitysec.com/downloads/SPIKE2.9.tgz) - A fuzzer development framework like sulley, a predecessor of sulley. 

[Metasploit Framework](https://www.rapid7.com/products/metasploit/download.jsp) - A framework which contains some fuzzing capabilities via Auxiliary modules. 

[Nightmare](https://github.com/joxeankoret/nightmare) - A distributed fuzzing testing suite with web administration, supports fuzzing using network protocols.

[rage_fuzzer](https://github.com/deanjerkovich/rage_fuzzer) - A dumb protocol-unaware packet fuzzer/replayer.


### Misc 
*Other notable fuzzers like Kernel Fuzzers, general purpose fuzzer etc.,*


[KernelFuzzer](https://github.com/mwrlabs/KernelFuzzer) - Cross Platform Kernel Fuzzer Framework.

[honggfuzz](http://google.github.io/honggfuzz/) - A general-purpose, easy-to-use fuzzer with interesting analysis options.

[Hodor Fuzzer](https://github.com/nccgroup/hodor) - Yet Another general purpose fuzzer.

[libFuzzer](http://libfuzzer.info) - In-process, coverage-guided, evolutionary fuzzing engine for targets written in C/C++.

[syzkaller](https://github.com/google/syzkaller) - Distributed, unsupervised, coverage-guided Linux syscall fuzzer.

[ansvif](https://oxagast.github.io/ansvif/) - An advanced cross platform fuzzing framework designed to find vulnerabilities in C/C++ code.

### Taint Analysis
*How user input affects the execution*

[PANDA ( Platform for Architecture-Neutral Dynamic Analysis )](https://github.com/moyix/panda)

[QIRA (QEMU Interactive Runtime Analyser)](http://qira.me/)


### Symbolic Execution SAT and SMT Solvers

[Z3](https://github.com/Z3Prover/z3) - A theorem prover from Microsoft Research.

[SMT-LIB](http://smtlib.cs.uiowa.edu/) - An international initiative aimed at facilitating research and development in Satisfiability Modulo Theories (SMT)


### References

I haven't included some of the legends like AxMan, please refer the following link for more information.
https://www.ee.oulu.fi/research/ouspg/Fuzzers 


### Essential Tools

*Tools of the trade for exploit developers, reverse engineers*


#### Debuggers 


[Windbg](https://msdn.microsoft.com/en-in/library/windows/hardware/ff551063(v=vs.85).aspxi) - The preferred debugger by exploit writers.

[Immunity Debugger](http://debugger.immunityinc.com) - Immunity Debugger by Immunity Sec.

[OllyDbg ](http://www.ollydbg.de/) - The debugger of choice by reverse engineers and exploit writers alike.

[Mona.py ( Plugin for windbg and Immunity dbg )](https://github.com/corelan/mona/) - Awesome tools that makes life easy for exploit developers.

[x64dbg](https://github.com/x64dbg/) - An open-source x64/x32 debugger for windows.

[Evan's Debugger (EDB)](http://codef00.com/projects#debugger) - Front end for gdb.

[GDB - Gnu Debugger](http://www.sourceware.org/gdb/) - The favorite linux debugger.

[PEDA](https://github.com/longld/peda) - Python Exploit Development Assistance for GDB.

[Radare2](http://www.radare.org/r/) - Framework for reverse-engineering and analyzing binaries.


#### Disassemblers and some more

*Dissemblers, disassembly frameworks etc.,*


[IDA Pro](https://www.hex-rays.com/products/ida/index.shtml) - The best disassembler

[binnavi](https://github.com/google/binnavi) - Binary analysis IDE, annotates control flow graphs and call graphs of disassembled code.

[Capstone](https://github.com/aquynh/capstone) - Capstone is a lightweight multi-platform, multi-architecture disassembly framework.


#### Others

[ltrace](http://ltrace.org/) - Intercepts library calls 

[strace](http://sourceforge.net/projects/strace/) - Intercepts system calls


## Vulnerable Applications

Exploit-DB - https://www.exploit-db.com
(search and pick the exploits, which have respective apps available for download, reproduce the exploit by using fuzzer of your choice)

PacketStorm - https://packetstormsecurity.com/files/tags/exploit/

[Fuzzgoat](https://github.com/fuzzstati0n/fuzzgoat) - Vulnerable C program for testing fuzzers.


##### Samples files for seeding during fuzzing:

https://files.fuzzing-project.org/

[PDF Test Corpus from Mozilla](https://github.com/mozilla/pdf.js/tree/master/test/pdfs)

[MS Office file format documentation](https://www.microsoft.com/en-us/download/details.aspx?id=14565)

[Fuzzer Test Suite](https://github.com/google/fuzzer-test-suite) - Set of tests for fuzzing engines. Includes different well-known bugs such as Heartbleed, c-ares $100K bug and others.


## Anti Fuzzing

[Introduction to Anti-Fuzzing: A Defence In-Depth Aid](https://www.nccgroup.trust/uk/about-us/newsroom-and-events/blogs/2014/january/introduction-to-anti-fuzzing-a-defence-in-depth-aid/)
> [Fuzzing](https://en.wikipedia.org/wiki/Fuzzing) or fuzz testing is an automated software testing technique that involves providing invalid, unexpected, or random data as inputs to a computer program. The program is then monitored for exceptions such as crashes, failing built-in code assertions, or potential memory leaks. Typically, fuzzers are used to test programs that take structured inputs. 

A curated list of references to awesome Fuzzing for security testing. Additionally there is a collection of freely available academic papers, tools and so on.

Your favorite tool or your own paper is not listed? Fork and create a Pull Request to add it!


## Contents

- [Books](#books)
- [Papers](#papers)
- [Tools](#tools)
- [Platform](#platform)


## Books
- [The Art, Science, and Engineering of Fuzzing: A Survey](https://arxiv.org/abs/1812.00140) (2019) - 
Actually, this document is a paper, but it contains more important and essential content than any other book.
- [Fuzzing for Software Security Testing and Quality Assurance, 2nd Edition](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507/) (2018)
- [Fuzzing: Brute Force Vulnerability Discovery, 1st Edition](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119/) (2007)
- [Open Source Fuzzing Tools, 1st Edition](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950/) (2007)


## Talks
- [Effective File Format Fuzzing](https://youtu.be/qTTwqFRD1H8), Black Hat Europe 2016
- [Adventures in Fuzzing](https://www.youtube.com/watch?v=SngK4W4tVc0), NYU Talk 2018
- [Fuzzing with AFL](https://www.youtube.com/watch?v=DFQT1YxvpDo), NDC Conferences 2018

## Papers
To achieve a well-defined scope, I have chosen to include publications on fuzzing in the last proceedings of 4
top major security conferences and others from Jan 2008 to Jul 2019.
It includes (i) Network and Distributed System Security Symposium (NDSS), (ii) IEEE Symposium on
Security and Privacy (S&P), (iii) USENIX Security Symposium (USEC), and (iv) ACM Conference on Computer and Communications Security (CCS).


### The Network and Distributed System Security Symposium (NDSS)
- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines, 2019](https://daramg.gift/paper/han-ndss2019.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary, 2019](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf)
- [REDQUEEN: Fuzzing with Input-to-State Correspondence, 2019](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing, 2019](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Life after Speech Recognition: Fuzzing Semantic Misinterpretation for Voice Assistant Applications, 2019](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_08-4_Zhang_paper.pdf)
- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing, 2018](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf)
- [IoTFuzzer: Discovering Memory Corruptions in IoT Through App-based Fuzzing, 2018](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices, 2018](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing, 2018](https://lifeasageek.github.io/papers/han:meds.pdf)
- [Vuzzer: Application-aware evolutionary fuzzing, 2017](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/vuzzer-application-aware-evolutionary-fuzzing/)
- [DELTA: A Security Assessment Framework for Software-Defined Networks, 2017](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2017/09/ndss201702A-1LeePaper.pdf)
- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution, 2016](https://cancer.shtech.org/wiki/uploads/2016---NDSS---driller-augmenting-fuzzing-through-selective-symbolic-execution.pdf)
- [Automated Whitebox Fuzz Testing, 2008](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2017/09/Automated-Whitebox-Fuzz-Testing-paper-Patrice-Godefroid.pdf)


### IEEE Symposium on Security and Privacy (IEEE S&P)
- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)
- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)
- [Program-Adaptive Mutational Fuzzing, 2015](https://softsec.kaist.ac.kr/~sangkilc/papers/cha-oakland15.pdf)
- [TaintScope: A checksum-aware directed fuzzing tool for automatic software vulnerability detection, 2010](https://ieeexplore.ieee.org/abstract/document/5504701)



### USENIX Security
- [Fuzzification: Anti-Fuzzing Techniques, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/jung)
- [AntiFuzz: Impeding Fuzzing Audits of Binary Executables, 2019](https://www.usenix.org/conference/usenixsecurity19/presentation/guler)
- [Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/talebi)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)
- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)
- [Protocol State Fuzzing of TLS Implementations, 2015](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/de-ruiter)
- [Optimizing Seed Selection for Fuzzing, 2014](https://softsec.kaist.ac.kr/~sangkilc/papers/rebert-usenixsec14.pdf)
- [Dowsing for overflows: a guided fuzzer to find buffer boundary violations, 2013](http://enigma.usenix.org/sites/default/files/sec13_proceedings_interior.pdf#page=57)
- [Fuzzing with Code Fragments, 2012](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)


### ACM Conference on Computer and Communications Security (ACM CCS)
- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [AFL-based Fuzzing for Java with Kelinci, 2017](https://dl.acm.org/citation.cfm?id=3138820)
- [Designing New Operating Primitives to Improve Fuzzing Performance, 2017](http://iisp.gatech.edu/sites/default/files/images/designing_new_operating_primitives_to_improve_fuzzing_performance_vt.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)
- [Systematic Fuzzing and Testing of TLS Libraries, 2016](https://www.nds.rub.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [Coverage-based Greybox Fuzzing as Markov Chain, 2016](https://ieeexplore.ieee.org/abstract/document/8233151)
- [eFuzz: A Fuzzer for DLMS/COSEM Electricity Meters, 2016](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.817.5616&rep=rep1&type=pdf)
- [Scheduling Black-box Mutational Fuzzing, 2013](https://softsec.kaist.ac.kr/~sangkilc/papers/woo-ccs13.pdf)
- [Taming compiler fuzzers, 2013](https://www.cs.utah.edu/~regehr/papers/pldi13.pdf)
- [SAGE: whitebox fuzzing for security testing, 2012](https://dl.acm.org/citation.cfm?id=2094081)
- [Grammar-based whitebox fuzzing, 2008](https://dl.acm.org/citation.cfm?id=1375607)
- [Taint-based directed whitebox fuzzing, 2009](https://dl.acm.org/citation.cfm?id=1555061)


### ArXiv (Fuzzing with Artificial Intelligence & Machine Learning)
- [A Review of Machine Learning Applications in Fuzzing, 2019](https://arxiv.org/abs/1906.11133)
- [Evolutionary Fuzzing of Android OS Vendor System Services, 2019](https://arxiv.org/abs/1906.00621)
- [MoonLight: Effective Fuzzing with Near-Optimal Corpus Distillation, 2019](https://arxiv.org/abs/1905.13055)
- [Coverage-Guided Fuzzing for Deep Neural Networks, 2018](https://arxiv.org/abs/1809.01266)
- [DLFuzz: Differential Fuzzing Testing of Deep Learning Systems, 2018](https://arxiv.org/abs/1808.09413)
- [TensorFuzz: Debugging Neural Networks with Coverage-Guided Fuzzing, 2018](https://arxiv.org/abs/1807.10875)
- [NEUZZ: Efficient Fuzzing with Neural Program Learning, 2018](https://arxiv.org/abs/1807.05620)
- [EnFuzz: From Ensemble Learning to Ensemble Fuzzing, 2018](https://arxiv.org/abs/1807.00182)
- [REST-ler: Automatic Intelligent REST API Fuzzing, 2018](https://arxiv.org/abs/1806.09739)
- [Deep Reinforcement Fuzzing, 2018](https://arxiv.org/abs/1801.04589)
- [Not all bytes are equal: Neural byte sieve for fuzzing, 2017](https://arxiv.org/abs/1711.04596)
- [Faster Fuzzing: Reinitialization with Deep Neural Models, 2017](https://arxiv.org/abs/1711.02807)
- [Learn&Fuzz: Machine Learning for Input Fuzzing, 2017](https://arxiv.org/abs/1701.07232)
- [Complementing Model Learning with Mutation-Based Fuzzing, 2016](https://arxiv.org/abs/1611.02429)

### The others
- [Ifuzzer: An evolutionary interpreter fuzzer using genetic programming, 2016](https://www.cs.vu.nl/~herbertb/download/papers/ifuzzer-esorics16.pdf)
- [Hybrid fuzz testing: Discovering software bugs via fuzzing and symbolic execution, 2012](https://pdfs.semanticscholar.org/488a/b1e313f5109153f2c74e3b5d86d41e9b4b71.pdf)
- [Call-Flow Aware API Fuzz Testing for Security of Windows Systems, 2008](https://www.computer.org/csdl/proceedings/iccsa/2008/3243/00/3243a019-abs.html)
- [Feedback-directed random test generation, 2007](https://dl.acm.org/citation.cfm?id=1248841)



## Tools
Information about the various open source tools you can use to leverage fuzz testing.
### General-purpose
- [radamsa](https://gitlab.com/akihe/radamsa) - A general-purpose fuzzer.
- [zzuf](https://github.com/samhocevar/zzuf) - A transparent application input fuzzer.
### Binary
- [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - A security-oriented fuzzer that employs a novel type of compile-time instrumentation and genetic algorithms to automatically discover clean, interesting test cases that trigger new internal states in the targeted binary. 
- [WinAFL](https://github.com/googleprojectzero/winafl) - A fork of AFL for fuzzing Windows binaries.
- [libFuzzer](http://llvm.org/docs/LibFuzzer.html) - A library for coverage-guided fuzz testing. [Tutorial from Google.](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
- [Driller](https://github.com/shellphish/driller) - An implementation of the [driller paper](https://www.cs.ucsb.edu/~vigna/publications/2016_NDSS_Driller.pdf). This implementation was built on top of AFL with angr being used as a symbolic tracer.
- [shellphish fuzzer](https://github.com/shellphish/fuzzer) - A Python interface to AFL, allowing for easy injection of testcases and other functionality.
- [Eclipser](https://github.com/SoftSec-KAIST/Eclipser) - A binary-based fuzz testing tool that improves upon classic coverage-based fuzzing by leveraging a novel technique called grey-box concolic testing.
### Web, JavaScript
- [jsfunfuzz](https://github.com/MozillaSecurity/funfuzz) - JavaScript engine fuzzers.
- [IFuzzer](https://github.com/vspandan/IFuzzer) - An Evolutionary Interpreter Fuzzer Using Genetic Programming.
- [domato](https://github.com/googleprojectzero/domato) - DOM fuzzer from [Google Project Zero](https://github.com/googleprojectzero). [Blog Post.](https://googleprojectzero.blogspot.com/2017/09/the-great-dom-fuzz-off-of-2017.html)
- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) - A (coverage-)guided Javascript engine fuzzer, written by Samuel Groß.
- [CodeAlchemist](https://github.com/SoftSec-KAIST/CodeAlchemist) - JavaScript engine fuzzer, written by KAIST SoftSec Lab.
- [test-each](https://github.com/ehmicky/test-each) - Repeat tests using different inputs.
- [gremlins.js](https://github.com/marmelab/gremlins.js) - gremlins.js is a monkey testing library written in JavaScript.
### Network protocol
- [T-Fuzz](https://github.com/HexHive/T-Fuzz) - T-Fuzz leverages a coverage guided fuzzer to generate inputs.
- [TLS-Attacker](https://github.com/RUB-NDS/TLS-Attacker) - A Java-based framework for analyzing TLS libraries.
- [DELTA](https://github.com/nss-lab/DELTA) - SDN Security evaluation framework.
- [boofuzz](https://github.com/jtpereyda/boofuzz) - Network Protocol Fuzzing for Humans. Documentation is available at http://boofuzz.readthedocs.io/, including nifty quickstart guides.
- [LL-Fuzzer](https://github.com/mit-ll/LL-Fuzzer) - An automated NFC fuzzing framework for Android devices.
- [tlsfuzzer](https://github.com/tomato42/tlsfuzzer) - A SSL and TLS protocol test suite and fuzzer.
- [TumbleRF](https://github.com/riverloopsec/tumblerf) - A framework that orchestrates the application of fuzzing techniques to RF systems. 
- [PULSAR](https://github.com/hgascon/pulsar) - A method for stateful black-box fuzzing of proprietary network protocols.
- [SPIKE](https://github.com/guilhermeferreira/spikepp/tree/master/SPIKE) - A fuzzer development framework like sulley, a predecessor of sulley.
- [PROTOS](https://www.ee.oulu.fi/roles/ouspg/Protos) - Security testing of protocol implementations.
### Driver
- [Charm](https://github.com/trusslab/charm) - A system solution that facilitates dynamic analysis of device drivers of mobile systems.
## Platform
- [certfuzz](https://github.com/CERTCC/certfuzz) - It contains the source code for the CMU CERT Basic Fuzzing Framework (BFF) and the CERT Failure Observation Engine (FOE).
- [Peach Fuzzer Platform](https://www.peach.tech/products/peach-fuzzer/) - An automated security testing platform that prevents zero day attacks by finding vulnerabilities in hardware and software systems.
- [Blackhat USA 2018 AFL workshop training materials](https://github.com/wrauner/afl-fuzzing-training) - From @wrauner at Samsung Research.


## Binary

* [angr](https://github.com/angr/angr) - Platform agnostic binary analysis framework from UCSB.
* [TRITON](https://github.com/JonathanSalwan/Triton) - Dynamic Binary Analysis for x86 binaries.
* [DynamoRIO](http://www.dynamorio.org/) - is a runtime code manipulation system that supports code transformations on any part of a program, while it executes.
* [Pin Tools](https://software.intel.com/en-us/articles/pin-a-dynamic-binary-instrumentation-tool) - A dynamic binary instrumentation tool and a platform for creating analysis tools.


## C/C++

* [KLEE](https://github.com/klee/klee) - Symbolic virtual machine built on top of the LLVM compiler infrastructure.
* [tis-interpreter](https://github.com/TrustInSoft/tis-interpreter) - An interpreter for finding subtle bugs in programs written in standard C
* [Valgrind](http://valgrind.org/) - An instrumentation framework for building dynamic analysis tools
* [LDRA](https://ldra.com/) :copyright: - a tool suite incuding dynamic analysis and test to various standards can ensure test coverage to 100% op-code, branch & decsion coverage.
* [LLVM/Clang Sanitizers](https://github.com/google/sanitizers)
    - [AddressSanitizer](https://github.com/google/sanitizers/wiki/AddressSanitizer) - A memory error detector for C/C++
    - [MemorySanitizer](https://github.com/google/sanitizers/wiki/MemorySanitizer) - A detector of uninitialized memory reads in C/C++ programs.
    - [ThreadSanitizer](https://github.com/google/sanitizers/wiki/ThreadSanitizerCppManual) - A data race detector for C/C++

## Java

* [Java PathFinder](https://github.com/javapathfinder/jpf-core) - An extensible software model checking framework for Java bytecode programs.
* [Parasoft Jtest](https://www.parasoft.com/products/jtest) :copyright: - Jtest is an automated Java software testing and static analysis product that is made by Parasoft. The product includes technology for Data-flow analysis Unit test-case generation and execution, static analysis, regression testing, code coverage, and runtime error detection.

## Python

* [typo](https://github.com/aldanor/typo) - Runtime Type Checking for Python 3

## .NET

* [Microsoft IntelliTest](https://docs.microsoft.com/en-us/visualstudio/test/intellitest-manual/getting-started?view=vs-2019) - Generate a candidate suite of tests for your .NET code.
* [Pex and Moles](https://www.microsoft.com/en-us/research/project/pex-and-moles-isolation-and-white-box-unit-testing-for-net/) - Pex automatically generates test suites with high code coverage using automated white box analysis.


## Visual Basic

* [VB Watch](www.aivosto.com/vbwatch.html) :copyright: - Profiler, Protector and Debugger for VB6. Profiler measures performance and test coverage. Protector implements robust error handling. Debugger helps monitor your executables.

## Multiple languages

* [AppScan Standard](https://www.hcltechsw.com/wps/portal/products/appscan/home/!ut/p/z1/04_Sj9CPykssy0xPLMnMz0vMAfIjo8zi_QO8nQ0MnQ0C_F3MnA0CHX2dvYN9woxNvEz0w1EVWDgGuQAVeLpbBvu6Gxl4m-hHUaLfxJQ4_QY4gKMBifZjKojCb3y4fhSqFe6Bpk5AEwIMTNyMfYzdfczQFWAJIrwKQGFAyBUFuaGhoREGmZ7piooAwLgEZw!!/?1dmy&urile=wcm%3apath%3a/wps/wcm/connect/hcl+software+content/products/appscan/offerings/standard) :copyright: - HCL's AppScan is a dynamic application security testing suite ([previously by IBM](https://newsroom.ibm.com/2018-12-06-HCL-Technologies-to-Acquire-Select-IBM-Software-Products-for-1-8B)).
* [Code Pulse](http://code-pulse.com/) - Code Pulse is a free real-time code coverage tool for penetration testing activities by OWASP and Code Dx ([GitHub](https://github.com/codedx/codepulse)).
* [Gcov](https://gcc.gnu.org/onlinedocs/gcc/Gcov.html) - GNU source code coverage program. Code coverage tool and profiling tool which is part of the GCC. Supports C, C++, Fortran.
* [Minded Security BlueClosure](https://www.mindedsecurity.com/index.php/products/blueclosure) :copyright: - Dynamic web application security scanner. It uses dynamic data tainting in order to understand if a DOM XSS is exploitable and uses the browser JavaScript engine for understanding the code.
* [WhiteHat Sentinel Dynamic](https://www.whitehatsec.com/products/dynamic-application-security-testing/) :copyright: - Part of the WhiteHat Application Security Platform. Dynamic application security scanner that covers the OWASP Top 10.
