# operating-systems
documents and resources regarding operating systems

- [Lions UNIX book](https://joshnatis.github.io/readings/comp/Lions%20-%20A%20Commentary%20on%20the%20Sixth%20Edition%20UNIX%20Operating%20System.pdf)
- sel4
  + check out http://gernot-heiser.org/ and his advanced operating systems course http://www.cse.unsw.edu.au/~cs9242/current/, + his research lab and blog posts
- xv6
  + https://pdos.csail.mit.edu/6.828/2011/xv6.html
  + https://pdos.csail.mit.edu/6.828/2014/xv6/book-rev8.pdf
  + https://github.com/guilleiguaran/xv6
- eric raymond
  + maybe copy over links and titles here with short descriptions
- multics
  + find features from multics that didn't make it into UNIX, those that came afterwards, and those that were foundational for UNIX
  + https://multicians.org/multics.html
  + more about bcpl and cpl
  + more about ctss
  + i think rudd canaday ruddcanaday.com had some stuff about bcpl
  + https://www.multicians.org/fjcc1.html
- Plan 9
  + http://doc.cat-v.org/plan_9/
  + http://9front.org/
- Inferno
  + http://doc.cat-v.org/inferno/
- examine and rewrite weiss's demo files (upload them here)
- Andreas Kling [SerenityOS videos](https://www.youtube.com/watch?v=Fa9SwYfH2NI&list=PLMOpZvQB55bczV5_3DxTLDm37v_F6iCKA)
- [MINIX book](https://joshnatis.github.io/readings/comp/tanenbaum_woodhull_operating-systems-design-implementation-3rd-edition.pdf) by Tanenbaum
- Mach Kernel
- GNU Hurd
- Finish Operating Systems Dinosaur Book
- https://ban.ai/multics/doc/
- https://cs.nyu.edu/rgrimm/teaching/readings/
- https://www.cs.utexas.edu/users/dahlin/advice.html
- http://cs.brown.edu/courses/cs167/
- https://www.sigops.org/
- http://csl.snu.ac.kr/courses/4190.568/2020-2/2-systems.pdf
- https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/acrobat-17.pdf

```
Chapter 9 - Main Memory
	- Contiguous Memory Allocation, Paging, Structure of the Page Table, Swapping
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter09.pdf

Chapter 10 - Virtual Memory
	- Demand Paging, Copy-on-Write, Page Replacement, Allocation of Frames, Thrashing, 
	Memory Compression, Allocating Kernel Memory, Other Considerations
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter10.pdf

Chapter 11 - Mass-Storage Structure
	- HDD Scheduling, NVM Scheduling, Error Detection and Correction, Storage Device Management, 
	Swap-Space Management, Storage Attachment, RAID Structure 
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter11.pdf

Chapter 12 - I/O Systems
	- I/O Hardware, Application I/O Interface, Kernel I/O Subsystem,
	Transforming I/O Requests to Hardware Operations, STREAMS
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter12.pdf

Chapter 13 - File-System Interface
	- File Concept, Access Methods, Directory Structure, Protection, Memory-Mapped Files 
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter13.pdf

Chapter 14 - File-System Implementation
	- File-System Structure, File-System Operations, Directory Implementation,
	Allocation Methods, Free-Space Management, Effciency and Performance,
	Recovery, Example: The WAFL File System
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter14.pdf

Chapter 15 - File-System Internals
	- File Systems, File-System Mounting, Partitions and Mounting, File Sharing,
	Virtual File Systems, Remote File Systems, Consistency Semantics, NFS
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter15.pdf

Chapter 18 - Virtual Machines
	- Benefts and Features, Building Blocks, Types of VMs and Their Implementations,
	Virtualization and Operating-System Components, Virtualization Research
  -  http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter18.pdf

Chapter 19 - Networks and Distributed Systems
	- Advantages of Distributed Systems, Network Structure, Communication Structure,
	Network and Distributed Operating Systems, Design Issues in Distributed Systems,
	Distributed File Systems, DFS Naming and Transparency, Remote File Access,
	Final Thoughts on Distributed File Systems
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter19.pdf

Chapter 20 - The Linux System
	- Linux History, Design Principles, Kernel Modules, Process Management,
	Scheduling, Memory Management, File Systems, Input and Output,
	Interprocess Communication, Network Structure, Security
  - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter20.pdf

Chapter 21 - Windows 10
	- History, Design Principles, System Components, Terminal Services and
	Fast User Switching, File System, Networking, Programmer Interface
 - http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci340/slides/chapter21.pdf

Chapter A - Influential Operating Systems
	- Feature Migration, Early Systems, Atlas, XDS-940, THE, RC 4000, CTSS, 
	MULTICS, OS/360, TOPS-20, CP/M and MS/DOS, Macintosh Operating System
	and Windows 16, Mach 16, Capability-based Systems—Hydra and CAP 18

Chapter C - BSD UNIX
	- UNIX History, Design Principles, Programmer Interface, User Interface,
	Process Management, Memory Management, File System, I/O System,
	Interprocess Communication

Chatpter D - The Mach System
	- History of the Mach System, Design Principles, System Components, Process Management,
	Interprocess Communication, Memory Management, Programmer Interface
```

## systems programming
* [Weiss's UNIX Systems Programming Course](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/cs82010_spr13.php)
  - [Chapter 1: Introduction to Systems Programming](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_01.pdf)
  - [Chapter 2: Login Records, File I/O, and Performance](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_02.pdf)
  - [Chapter 3: File Systems and Directories](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_03.pdf)
  - [Chapter 4: Working with the File Hierarchy](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_04.pdf)
  - [Chapter 5: I/O and Terminal Control](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_05.pdf)
  - [Chapter 6: Interactive Programs and Signals](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_06.pdf)
  - [Chapter 7: Event Driven Programming: Timers and Asynchronous I/O](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_07.pdf)
  - [Chapter 8: Process Architecture and Control](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_08.pdf)
  - [Chapter 9: Interprocess Communication](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_09.pdf)
  - [Chapter 10: Threads and the Pthread Library](http://compsci.hunter.cuny.edu/~sweiss/course_materials/unix_lecture_notes/chapter_10.pdf)
  - [Exercise 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/exercise_01.pdf)
  - [Assignment 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_01.pdf)
  - [Assignment 2](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_02.pdf)
  - [Assignment 3](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_03.pdf)
  - [Assignment 4](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_04.pdf)
  - [Assignment 5](http://compsci.hunter.cuny.edu/~sweiss/course_materials/csci493.66/assignments/assignment_05.pdf)
  - [Graduate Assignment 1](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_01.pdf)
  - [Graduate Assignment 2](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_02.pdf)
  - [Graduate Assignment 3](http://compsci.hunter.cuny.edu/~sweiss/course_materials/cs82010/assignments/assignment_03.pdf)
  
* [Command-line Interface Guidlines](https://clig.dev/)

```
If you want to learn to be a systems programmer
then you should follow these steps
● learn the tools
	● strace - to trace system calls
	● ltrace - to trace library calls
	● gdb - to debug and diagnose programs
	● valgrind - to find memory errors
	* test them on common programs, plus on your own code
● build clones of common systems tools
● read books on operating systems internals
	● read a book on operating system design (even though much of the book might be wrong!)
	● read the Linux kernel documentation, particular the
	description of the VM and filesystem interfaces
	● write simple programs to test your knowledge, and use
	tools like strace to watch the behaviour
	● read the POSIX or SUS documentation for important calls
	like open() and mmap()
	● you must understand the principles of locking and race
	conditions
● learn C and at least one scripting language
	● Learn what makes “good” and “bad” style in these
	languages
	● Learn how to avoid common programming errors,
	such a buffer overruns
```
