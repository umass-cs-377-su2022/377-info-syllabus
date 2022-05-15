# COMPSCI 377 Operating Systems Syllabus

Summer 2022

![](https://user-images.githubusercontent.com/348202/168497262-d4f1388c-b04d-4639-9ecb-4a9b68ef940c.png)

## Course Overview

In this course we examine the important problems in operating system design and implementation. The operating system provides a well-known, convenient, and efficient interface between user programs and the bare hardware of the computer on which they run. The operating system is responsible for allowing resources (e.g., disks, networks, and processors) to be shared, providing common services needed by many different programs (e.g., file service, the ability to start or stop processes, and access to the printer), and protecting individual programs from one another. The course will start with a brief historical perspective of the evolution of operating systems over the last fifty years, and then cover the major components of most operating systems. This discussion will cover the tradeoffs that can be made between performance and functionality during the design and implementation of an operating system. Particular emphasis will be given to three major OS subsystems: process management (processes, threads, CPU scheduling, synchronization, and deadlock), memory management (segmentation, paging, swapping), file systems, and operating system support for distributed systems. 4 credits.

## Prerequisites

COMPSCI 230. This course assumes a solid understanding of the C programming language, command line, basic Unix skills, the ability to learn new programming languages, how to compile programs, how to build programs using make, and general use of typical Unix commands.

## Required Text

[Operating Systems: Three Easy Pieces](http://pages.cs.wisc.edu/~remzi/OSTEP), Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dussea. This is a free textbook available online. While the entire textbook is available for free from this site, if you so wish, a hard copy may be purchased for a nominal charge from this site or from the UMass textbook store run by Amazon.

## Other Material

It is assumed that you have a computer to use for assignments in this course. You should make sure to save and backup your work frequently (e.g., Dropbox, Google Drive, GitHub). We will not accept excuses for missing or accidental deletion of work. You may only use GitHub for storing your work on individual assignments if you are using a private repository. Use of public repositories to store assignment solutions on GitHub is considered academic dishonesty/cheating and will result in a failure for this course.

## Course Objectives

The objectives of this course are to learn and understand operating system concepts including:

- Processes and Process API
- System Calls
- Direct Execution
- CPU Scheduling
- Concurrency and Threads
- Locks and Event-based Concurrency
- Condition Variables, Semaphores, and Monitors
- I/O Devices, Disks, Files and Directories, and File System Implementation
- Address Spaces and the Memory API
- Address Translation and Segmentation
- Free Space Management and Paging
- Translation Lookaside Buffers and Page Tables

## Course Format

This course will be conducted entirely online with both synchronous and asynchronous components. Generally, the material will be released at the start of each week and include recorded lessons, a unit exam, a project assignment, and other possible activities. You will work through the provided materials completing each required task. The instructor will hold synchronous sessions on Zoom to discuss the material and provide an opportunity for questions and answers. You are not required to attend the synchronous sessions, however, they will be recorded and made available to you as a resource in case you would like to review them at a time that is convenient to you.

## Course Schedule

This course runs in a 6-week summer intensive format. All the material covered in the regular 13-week semester will be covered in this course. It is assumed that you have more time to dedicate to this course than you would during a regular semester. It is also assumed that you may have a job or other activities that you are participating in during the summer. The following is the approximate schedule for this course:

- Week 0 (5/19 – 5/21): Course Introduction and Setup
- Week 1 (5/22 – 5/28): Introduction to OS & Processes
- Week 2 (5/29 – 6/4): CPU Scheduling & Concurrency
- Week 3 (6/5 – 6/11): Concurrency & Synchronization
- Week 4 (6/12 – 6/18): Address Spaces, Segmentations, & Free Space Management
- Week 5 (6/19 – 6/25): Paging
- Week 6 (6/26 – 7/1): I/O & File Systems

Each week will have material and assignments released. Our goal will be to release each week early to allow you to move through the course material at a quicker pace if your schedule allows and if you are able to complete the course work for a previous week earlier.

## Rules for Success

**Student Responsibilities:**

If you follow these rules, your odds of learning the material and achieving a good grade in this course will improve greatly.

- Read the assignment documentation early and carefully.
- Do your work on time, submit your work on time, and make sure you submitted the correct work.
- Communicate with other students in the course, the professor, and other course staff for help.
- Be honest in the work you do and the submissions you make.
- Communicate with me and others in the course with respect and understanding.
- Do not ask to submit assignments after the due date.

**Instructor Responsibilities:**

You can expect from us:

- Timely release of course assignments.
- Timely release of scores achieved on course assignments.
- To respond to questions in the discussion forums in a reasonable amount of time during the week and normal working hours.
- Be respectful of your ideas and value the diversity you bring to the virtual classroom.
- Be open to dialogue that challenges me.
- Be present during my stated office hours.
- Ensure the proper running of the course in the online format.

## Grading Policy

The anticipated breakdown of course grades is as follows; this is subject to change.

- Project Assignments (40%) (6 projects)
- Weekly Exams (30%) (6 weekly exams)
- Cumulative Final Exam (30%) (1 final exam)

**Grading Notes:**

- The numerical cutoff for final course letter grade assignment will be made after all grading is completed. As a rough guide, expect to require at least a 93 to get an A, a 90 to get an A-, an 87 to get a B+, an 83 to get a B, an 80 to get a B-, etc.
- Individual projects/assignments/labs will not be scaled (curved).
- The instructor may or may not choose to scale final grades.
- Final grades are assigned based on the overall weighted average as defined by the grading policy. Grades will be rounded up. For example, if you achieve an 89.93 then the final letter grade will be (for example) an A-, not a B+.

**Final Grades:**

To evaluate your understanding of the course content, we will use scores achieved on each of the above assessment components. Your final grade will convey what you know from the course and how well you know it. Missing assignments can have a dramatic impact on your final grade so it is important that you are attentive to submission deadlines and avoid any missing work. The typical breakdown of percentages and final grades for this course are A (93-100), A- (90-92), B+ (87-89), B (83-86), B- (80-82), C+ (77-79), C (73-76), C- (70-72), D+ (67-69), D (60-66), F (0-59). This grading scheme may be adjusted based on the overall performance of students in the course.

## Assignments

**Project Assignments:**

There are 6 projects that are hands on with programming as it relates to the material. You will be provided a “starter” project, but will require additions, modifications, or tasks to complete it. Most projects come with some tests (but not all) to guide you. You submit your projects to Gradescope which will run our autograder and apply additional private tests.

**Weekly Exams:**

Weekly exams will test your knowledge of the material. There will be approximately 6 of these assessments. They will be multiple choice, true/false, and open response questions. They will be available online during a 48-hour period. Once you start a weekly exam you will have 60 minutes to complete it. These exams are open book and open notes.

**Final Exam:**

There is 1 final exam that will be released at the end of the course. The exam will be multiple choice, true/false, and open response questions. It will be available online during a 48-hour period. Once you start the exam you will have 120 minutes to complete it. This exam is open book and open notes.

## Assignment Submission and Lateness

Assignments will be submitted electronically. You are responsible for submitting your assignments by the assigned due date. The due dates for assignments will be clearly indicated on the schedule and it is your responsibility to update your own calendar, so you are aware of due dates. If you are unable to submit by the due date you must contact the instructor in advance to explain your circumstance. It will be determined if the late submission will be accepted, when it will be accepted, and if any late penalties will be applied.

**Lateness General Guidelines**

Lateness is defined as any assignment that is outside of the stated due date requirements. It is your responsibility for maintaining your own schedule and being prompt with your submissions. We expect that you become familiar with the course submission software and verify that your submission has been properly uploaded. We will not accept late submissions due to lack of checking on this. We assume:

- You are an adult and can check and verify your work has been received properly.
- You can use GitHub, DropBox, Google Drive, or some other backup software to ensure that your work is not lost in the event of a computer failure.
- You have a back-up plan in place if your computer fails, or your internet connection is unavailable. Make sure you have a plan B and C if your computer crashes or your internet is unavailable. This is your responsibility.
- To ensure that you submit projects on time you should begin them early and not wait until the last minute to submit. You will be able to submit multiple times so submit early and often to ensure you have something in before the deadline.

If there are extenuating circumstances beyond your control that prevent you from completing an assignment by the posted deadline you must contact the instructor immediately.

Please email lateness requests to: richards@cs.umass.edu
