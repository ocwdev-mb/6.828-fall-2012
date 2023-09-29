---
content_type: page
description: This section provides the schedule of lecture topics along with the lecture
  notes, readings, and handouts used for each lecture.
learning_resource_types: []
ocw_type: CourseSection
title: Lecture Notes and Readings
uid: 918acd06-aca5-1088-ed18-7978df900929
---

Some of the readings require the {{% resource_link dccce9be-65c1-ba7f-80a5-bb0c6d585ca7 "xv6 code (PDF)" %}}, as well as the {{% resource_link 3def8fcd-3979-33eb-b846-fb479bdcf556 "xv6 book (PDF - 1.3MB)" %}}, which are provided courtesy of Frans Kaashoek, Robert Morris, and Russ Cox and are used here with permission.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
LECTURE TOPICS AND NOTES
{{< thclose >}}
{{< thopen >}}
READINGS AND HANDOUTS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 88f52c27-6432-929a-08eb-5a09a8765054 "Operating Systems (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Chapter 0: Operating System Interfaces" of xv6 book
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 703cd534-061a-2870-9219-5cd7b59773bc "PC Hardware and x86 Programming (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Appendix A: PC Hardware" and "Appendix B: The Boot Loader" of xv6 book, and the related xv6 source files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link ecc911a7-b40e-9bab-b1c0-2f9e8ae37e1b "Overview of Major Internals, System Call Interface (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Chapter 1: The first process" and the related xv6 source files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link d3fd2385-4be9-5985-fec9-d1f86d4b84d4 "Virtual Memory (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}


"Chapter 2: Page Tables"

{{% resource_link 59fb2d93-2e77-57e2-8c78-3892a789d27c "Page Table Translation and Registers (PDF)" %}}


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link f69dc55b-35df-e9d5-e083-ab15d443a906 "Interrupts, Exceptions (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}


"Chapter 3: Traps, interrupts, and drivers" and the related xv6 source files

{{% resource_link 177eb051-1275-9833-dde8-3720f615d689 "IDT (PDF)" %}}


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 005e7575-c97a-d42a-9e77-9d777442a191 "Multiprocessors and Locking (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Chapter 4: Locking" with spinlock.c and skim mp.c
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 4cc50138-63ff-38ab-10d3-8c6b994036f3 "Processes and Switching (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Chapter 5: Scheduling" up to "Sleep and wakeup" with proc.c, setjmp.S, and sys\_fork (in sysproc.c)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link c34ee127-dcb4-2c58-4d0b-8e23cb532b9d "Sleep & Wakeup (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Read remainder of "Chapter 5: Scheduling"; read remainder of proc.c and sys\_wait, sys\_exit, sys\_kill
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link d5f27426-1488-04c2-3010-be61a49667d7 "File Systems (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
"Chapter 6: File system" and bio.c, fs.c, sysfile.c, file.c, except for the logging sections
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 722fff0f-4c27-ecf6-0b63-d583daf499bf "Crash Recovery (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Read log.c and the logging sections of "Chapter 6: File system"
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 6976b258-b566-bd5d-ebf4-a4469cf36ed9 "File System Performance and Fast Crash Recovery (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Tweedie, Stephen C. "[Journaling the Linux ext2fs Filesystem](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.307.9137)." \[Paper Presented at LinuxExpo 1998\].
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Project Introduction and Discussion
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 8513bdcc-f925-3ca1-eb98-252d67481db3 "OS Organization (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Engler, Dawson R., M. Frans Kaashoek, and James O'Toole Jr. "[Exokernel: An Operating System Architecture for Application-Level Resource Management](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.52.2893)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
In-class Hacking Session
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Project Conferences
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Project Conferences (cont.)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link a83f1d0b-7b78-7d79-8801-a85e26057961 "Language / OS Co-design (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Hunt, Galen C., and James R. Larus. "[Singularity: Rethinking the Software Stack](http://dx.doi.org/10.1145/1243418.1243424)." _Microsoft Research Redmond_ 41, no. 2 (2007): 37–49.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Quiz
{{< tdclose >}}
{{< tdopen >}}
Quiz (Open Book and Notes)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 61aeb500-c947-c106-349f-e64a58af954f "Scalable Locks (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Boyd-Wickizer, Silas, M. Frans Kaashoek, et al. "[Non-Scalable Locks are Dangerous](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.261.196)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Project Conferences
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Project Conferences (cont.)
{{< tdclose >}}
{{< tdopen >}}
Boyd-Wickizer, Silas, Austin T. Clements, et al. "[An Analysis of Linux Scalability to Many Cores](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.174.5191)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link d8d03983-cf03-1d08-000a-c92e1ddc395e "Lock-free Coordination (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
{{% resource_link 8570fc98-8e90-20ad-0689-a6aa380792bb "Virtual Machines (PDF)" %}}
{{< tdclose >}}
{{< tdopen >}}
Adams, Keith, and Ole Agesen. "[A Comparison of Software and Hardware Techniques for x86 Virtualization](http://dx.doi.org/10.1145/1168857.1168860)." _ACM Digital Library_ 34, no. 5 (2006): 2–13.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
No lecture; work on final projects
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}
Demos in class
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
25
{{< tdclose >}}
{{< tdopen >}}
Demos in class (cont.)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}