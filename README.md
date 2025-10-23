# 0xroadmap

This roadmap is meant to help guide me to becoming competent (and eventually master) the following skills:
- Binary Exploitation
- Reverse Engineering
- Systems Programming
- Vulnerability Research

## Table of Contents

1. [Fundamentals](#fundamentals)
2. [Reverse Engineering](#reverse-engineering)
3. [Binary Exploitation](#binary-exploitation)
4. [Vulnerability Research](#vulnerability-research)
5. [Systems Programming](#systems-programming)
6. [Toolbox](#toolbox)
7. [Contributing & Feedback](#contributing--feedback)

## Mindset  & Methodology

- [Process of mastering a skill](https://azeria-labs.com/the-process-of-mastering-a-skill/)
- [The importance of deep work and the 30-hour method for learning a new skill](https://azeria-labs.com/the-importance-of-deep-work-the-30-hour-method-for-learning-a-new-skill/)
- [Paradox of choice](https://azeria-labs.com/paradox-of-choice/)
## Fundamentals

- Computer Architecture and Assembly
	- [x86-64](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1001_x86-64_Asm+2021_v1/about)
	- [RISC-V](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Arch1005_IntroRISCV+2024_v1/about)
	- [ARM](https://azeria-labs.com/writing-arm-assembly-part-1/)
- Programming
	- C
	- C++
	- Python (scripting / pwntools)
- **Operating Systems**
	 - Linux internals (processes, memory management, syscalls)  
		 - [Julia's Drawings](https://drawings.jvns.ca/)
	- Basic Windows internals (PE format, WinAPI) — learn as needed for targets
---
## Reverse Engineering

### Resources
- [Symbolic Analysis](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+RE3201_symexec+2021_V1/about)
	- Learn to analyze programs and determine which inputs cause which specific part of a program to execute.
- Debugging
	- GDB
		- [Intro to gdb](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Dbg1012_IntroGDB+2024_v1/about)
	- Binary Ninja
		- [Intro to binja](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Dbg1103_Intro_Binja+2025_v1/about)
	- WinDbg
		- [Intro to windbg](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Dbg1011_WinDbg1+2024_v1/about)
- [Reversing C++ binaries](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+RE3011_re_cpp+2022_v1/about)
- [Reverse Engineering 101 From malwareunicorn](https://malwareunicorn.org/workshops/re101.html#0) 
	- Introduction to windows malware reverse engineering
- [Reverse Engineering For Everyone](https://0xinfection.xyz/reversing/)

### Challenges

-  [Flare On series](https://flare-on.com/)
	- Solutions can be found on the website.
-  [Crackmes](https://crackmes.one/)
	- A website for reverse engineering challenges.

---
## Binary Exploitation

Each week do the following:
1. Pick a new exploit technique.
2. Learn the theory behind the exploit technique.
3. Read and follow CTF writeups that use that technique.
4. Play and solve 2 - 4 CTFs that use that technique.
5. Write a blog post and explain the technique, and also provide clear examples.
### Resources

- [Pwn College](https://pwn.college/)
- [Nightmare](https://guyinatuxedo.github.io/)
- [lectures from University of Delaware on software exploitation](https://capture.udel.edu/channel/Sec%2BSoft%2B2022%2B%2528x86%2BExploitation%2529/246660612)
- [Lectures from  UMass CyberSecurity Club](https://pwn.umasscybersec.org/index.html)
- [https://www.lazenca.net/](https://www.lazenca.net/)
	- Explanation of exploit techniques
#### Articles / Blog Posts

- [low level exploitation by 0xdevil](https://syst3mfailure.io/)
- [https://connormcgarr.github.io/](https://connormcgarr.github.io/)
- [voidsec.com](https://voidsec.com/)

##### Heap

- [how2heap](https://github.com/shellphish/how2heap)
- [ir0nstone's notes on heap exploitation](https://ir0nstone.gitbook.io/notes/binexp/heap)
##### Kernel

- [ir0nstone's notes on kernel exploitation]()
- [Linux kernel exploitation series](https://r1ru.github.io/categories/linux-kernel-exploitation/)
- [how2kernel](https://github.com/R3x/How2Kernel)
### Challenges

1. **Pwn Adventure Series by Vector35**
	- [PwnAdventure Sourcery (In Browser)](https://sourcery.pwnadventure.com/)
	- [PwnAdventure 2](http://ghostintheshellcode.com/#pwnadventure2)
	- [PwnAdventure 3](http://pwnadventure.com/)
	Solution Videos  
	https://www.youtube.com/playlist?list=PLhixgUqwRTjzzBeFSHXrw9DnQtssdAwgG
2. Exploit Eduction
	- [Phoenix](https://exploit.education/phoenix/)
	- [Nebula](https://exploit.education/nebula/)
	- [Fusion](https://exploit.education/nebula/)
3. [Rop Emporium](https://ropemporium.com/)  
	- Practice Return Oriented Programming
4. PhrackCTF from Chompie/xforeced
	- [Linux Userland](https://github.com/xforcered/PhrackCTF/tree/master/linux_userland)
	- [Windows Kernel](https://github.com/xforcered/PhrackCTF/tree/master/windows_kernel)

---
## Vulnerability Research
### Resources

- Vulnerabilities
	- [Vuln 1001](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Vulns1001_C-family+2023_v1/about)
	- [Vuln 1002](https://p.ost2.fyi/courses/course-v1:OpenSecurityTraining2+Vulns1002_C-family+2023_v1/about)
- [CVE North Stars](https://cve-north-stars.github.io/)
	- Use freely available CVE information to learn become proficient in vulnerability analysis. This tutorial walks through practical CVE analysis, binary patch diffing, and root cause analysis.
- [Off by one](https://www.youtube.com/@OffByOneSecurity/)
	- Youtube channel with streams discussing vulnerability research, exploit development and reverse enginering.

#### Articles/Blog Posts

- [Project zero](https://googleprojectzero.blogspot.com/)
- [Zero Day Initiative](https://www.zerodayinitiative.com/blog/) 
- [Star Labs](https://starlabs.sg/blog/)

### Real world case studies

## FUZZING

- [fuzzing.io](https://fuzzing.io/)


### Challenges

- Pick a old software and find vulnerabilities.

---
## Systems Programming
- coming soon

### Resources

### Projects
---

## Toolbox

| Category                    | Tools I'm Learning                        |
| --------------------------- | ----------------------------------------- |
| **Disassembler/Decompiler** | Binary Ninja                              |
| **Debugger**                | GDB (with GEF) and Radare2                |
| **Exploitation**            | Pwntools                                  |
| **RE Frameworks**           | angr (for symbolic execution) and Radare2 |
## Contributing & Feedback

This is a personal roadmap. If you have an excellent resource or spot an inaccuracy, feel free to open an Issue. Let's learn together.

