---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Data Mining and Machine Learning
markdown: kramdown
course:
    semester: Spring 2025
---

# Syllabus
{:.no_toc}

Jump to:
* TOC
{:toc}

<br>

<a name = 'about'></a>

## About CSC 4220/5220

This course begins by exploring the basics of data science using python to understand the role of modeling. The relevant portion of the world can range from simple to outrageously complex. So, we must learn various types of models and explore how to evaluate and choose models, based on task type, complexity, and available data. We will delve into: Simple linear regression (with and without input transformations), multiple linear regression, logistic regression, PCA, KNN clustering, decision trees, support vector machines, the perceptron, multi-layer perceptron, auto-encoders, and large language models. Additionally, we will discuss ensemble learning, reinforcement learning, and machine learning ethics. 

### Goals

- Prepare students for advanced courses in machine learning or data science by exploring the foundational models and context.
- Enable students to start careers as data scientists by providing experience working with real-world data, tools, and techniques.
- Empower students to apply computational and inferential thinking to address real-world problems.

<a name = 'prereq'></a>
### Prerequisites

- **Design of Algorithms and Computing**: The rigorous design and analysis of algorithms is covered in CSC 2400. This is important to understanding the time and space complexity of various models. Additionally, this requirement ensures a sufficient background in practical programming.

- **Statistics**: Machine Learning and Data Science are fields that hail from statistical analysis. To understand **why** we do what we do, the underlying statistical processes are indispensable. We will review the relevant statistics but depend upon a basic understanding acquired in previous courses like Math 3070 (or 3470 or 4470 or 5470).

- **Math**: Linear Algebra (Math 2010). We will need some basic concepts like linear operators, projections, and optimization to analyze and derive new prediction algorithms. 

Please consult the [Resources](../resources) page for additional resources for reviewing prerequisite material and diving deeper.


**Textbook**: This course has two official texts. Both texts are available for free online (legally) at the provided links.

- [Learning Data Science](https://learningds.org/intro.html) by Sam Lau, Joey Gonzalez, and Deb Nolan
- [Deep Learning: Foundations and Concepts ](https://www.bishopbook.com) by Christopher Bishop and Hugh Bishop

Additionally, the course material will be supplemented by instructor notes as well as notes based on the course notes provided in the Berkeley Data 100 course.


## Course Culture
We hope to foster an inclusive and supportive learning environment based on curiosity rather than competition. All members of the course community — the instructors, students, and TAs — are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.

### Be Aware of Your Actions
Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat”: research finds that simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be Respectful
Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.


### Communicate Issues with Course Staff and/or the Department

**We take all complaints about unprofessional or discriminatory behavior seriously.** Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors in particular welcome any comments or concerns regarding conduct of the course and the staff. See [below](#office-hours-and-communication) for how to best reach us.

As course staff, we are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.


## Course Components

Below is a high-level “typical week in the course” for {{page.course.semester}}.

|  Mo | Tu | We | Th | Fr |
| --- | --- | --- | --- | --- | --- |
| <span style="color:Green">Lecture</span> | | <span style="color:Green">Lecture</span> |  | |
| Office Hours | | Office Hours | | | 
| <span style="color: #c91d1d">**Lab N-1 due**</span> | | <span style="color: #c91d1d">**Homework N-1 due**</span> | <span style="color:#c91d1d">Homework and Lab N released</span> |  | 

- **All deadlines are subject to change.**
- The Office Hours schedule is on the [Calendar page](../calendar).
- Lectures, assignments, projects, and exams are scheduled on the [Home page](..).


### Lecture

Lecture attendance is mandatory. 

Please refer to [Grading Scheme](#grading-scheme) for a comprehensive grade breakdown.

### Homework and Projects

**Homeworks** are week-long assignments that are designed to help students develop an in-depth understanding of both the theoretical and practical aspects of ideas presented in lecture. **Projects** are 2-week assignments (with a weekly checkpoint) that synthesize multiple topics.

- All homeworks and projects must be submitted to Ilearn by their posted deadlines. 
- Homeworks and projects are graded by the TAs and developed test cases. 
- The primary form of support students will have for homeworks and projects are **office hours**.
- Homeworks and projects must be completed individually, without the usage of any unauthorized resources (CourseHero, ChatGPT, code on the internet). See the [Collaboration Policy](#collaboration-policy-and-academic-honesty) for more details.

### Lab

**Labs** are shorter, weekly programming assignments designed to give students familiarity with new ideas and to act as a comprehension check. They are meant to be completed prior to homework.
- All lab assignments must be submitted to Ilearn by their posted deadlines.
- All labs are intended to take about an hour.
- Lab submissions are mandatory.
- Labs are graded by the TAs based on completion and effort.
- Labs are optional for 5220

### Exams

There will be two exams in this course:

{: .important}
> - **Midterm** on **Wednesday, March 12** 1-2:15 PM CST.
- **Final** on **Tuesday, May 6** 1-3 PM CST.

### Graduate Course

Students in the graduate version of the course will complete 3 additional assignments. 

- A modern book on machine learning approved by the instructor (ie. Genius Makers, The Alignment Problem, Human Compatible) 
- A group discussion based on research paper reading
- A culminating group project 


## Office Hours and Communication

We encourage you to discuss course content with your friends, classmates, and course staff throughout the semester, particularly during **office hours**! 

- All office hours will be updated on the Office Hours Calendar.
- Instructor office hours are by appointment and will be in office or on teams.
- TA office hours are drop-in and will be held in (TBD).

Course Communication:

- **Ilearn**, is our course forum this semester. **_All course announcements will be through Ilearn._** Please check out [Ilearn](https://elearn.tntech.edu). It's best to set Ilearn so that announcements are sent as emails - that way none will be missed.

- **Email** is the primary way to contact the instructor or TAs outside of class and office hours. Typically, you will receive a response within 24 hours. 

## Policies

### Grading Scheme

| Category | 4220 | 5220 | Details |
| --- | --- | --- | ---  |
| Homeworks | 30% | 20% | Drop 1 |
| Projects | 20% | 20% | |
| Labs | 5% |  | Drop 2 |
| Midterm Exam | 20% | 20% | |
| Final Exam | 25% | 20% | |
| Graduate Reading and Discussion | Bonus 5% | 10% | |
| Graduate Final Project | |10% | |

### On-Time Submission

All assignments are due at **_11:59 PM Central Time_** on the due date specified on the [Home / Schedule](..) page. The date and time of this deadline are firm. Submitting even a minute past is considered late.

### Slip Days

Each student gets an extension budget of **12** total slip days for the 12 homeworks and projects (so use them wisely). You can apply these slip days to homework and projects only (not labs) during the semester.

Slip days are automatically applied based on the additional hours you take to submit any assignment after its given deadline. Slip days are rounded up to the next day. For instance, 1 minute late counts as 1 day late. We will use the submission time as displayed on Gradescope. 

{: .note }
> If all 12 slip days are used for the first three homework assignments (for example), you are out of slip days and cannot ask us to not consider one of the slip days previously used. 

Each project or homework can have a maximum of **4** slip days applied. After 4 days of the assignment due date, it is unlikely that we will be able to accept your submission unless you have additional accommodations. Slip days should be reserved for unforeseen circumstances. You should not plan to use your slip days regularly.



### Collaboration Policy and Academic Honesty

If you misrepresent work as your own disciplinary action will be taken, including a failing grade in the course.

**Assignments.** Data science is a collaborative activity. While you may talk with others about the homework and projects, we ask that you write your solutions individually in your own words. **If you do discuss the assignments with others please include their names at the top of your notebook.** Restated, you and your peers are encouraged to discuss course content and approaches to problem-solving, but you are not allowed to share your code nor answers with other students, nor are you allowed to post your assignment solutions publicly. Doing so will be considered academic misconduct. 

**Use of AI-assisted methods, such as ChatGPT, to generate written or code solutions to assignments is prohibited. Usage of past assignment solutions is also prohibited.**

The benefit to completing the work in this course is similar to the benefit one gets from running laps. If someone else does it for you, you don't get the benefit. The value is in the doing, and not in having a completed assignment.

**Exams.** Students caught cheating on any exam will fail the course. No exceptions.

Plagiarism on any assignment, as well as other violations to TnTech’s [Student Handook](https://www.tntech.edu/handbooks/student/index.php){:target="_blank"}, will be reported. Additionally, we reserve the right to give you an F in the course. It’s just not worth it!

Rather than copying, ask for help. You are not alone! The instructor and TAs are here to help you succeed. We expect that you will work with integrity and with respect for other members of the class, just as the course staff will work with integrity and respect for you.


### Student Academic Integrity Policy  
Maintaining high standards of academic integrity in every class is critical to the reputation of Tennessee Tech, its students, faculty, alumni, and the employers of Tennessee Tech graduates. Academic integrity is at the foundation of the educational process and key to student success. Students with academic integrity are committed to honesty, ethical behavior, and avoiding academic integrity violations. All students must read and understand Policy 216: Student Academic Integrity. Please see the Academic Integrity [website](https://www.tntech.edu/provost/academicintegrity/) for more information.


## Disability Accommodation 

Students with a disability requiring accommodations should contact the accessible education center (AEC). An accommodation request (AR) should be completed as soon as possible, preferably by the end of the first week of the course. The AEC is located in the Roaden University Center, room 112; phone 931-372-6119. For details, view Tennessee Tech's policy 340 – services for students with disabilities at [policy central](https://tntech.policytech.com/docview/?docid=1131&public=true).


## Additional Resources 

### Technical Help 
If you are experiencing technical problems, visit the myTech IT [Helpdesk](https://its.tntech.edu/display/MON/Help+Desk) for assistance. 

If you are having trouble with one of the instructional technologies (i.e. Zoom, Teams, Qualtrics, Respondus, or any technology listed [here](https://www.tntech.edu/citl/tech-services/index.php)) visit the Center for Innovation in Teaching and Learning (CITL) [website](https://www.tntech.edu/citl/index.php) or call 931-372-3675 for assistance. 

For accessibility information and statements for our instructional technologies, visit the CITL's Learner Success Resource [webpage](https://www.tntech.edu/citl/learner-success-resources.php). 

### Tutoring 
The university provides free tutoring to all Tennessee Tech students. Tutoring is available for any class or subject, as well as writing, test prep, study skills, and resume support. Appointments are scheduled, so contact the Learning Center [website](https://www.tntech.edu/library/learning-center.php) for more information. 



## Health and Wellness 

### Counseling Center 
The Counseling Center offers brief, short-term, solution-focused therapeutic interventions for Tennessee Tech University students. The staff of the Counseling Center is available to assist students with their personal and social concerns in hopes of helping them achieve satisfying educational and life experiences. To learn more or schedule an appointment, visit the Counseling Center [website](https://www.tntech.edu/counsel/index.php). 


### Health Services 
Health Services offers high-quality, affordable care that is accessible and promotes the health and wellness of our Tennessee Tech community. Visit the Health Services [website](https://www.tntech.edu/healthservices/) to learn more. 


### Pandemic Protocols

Each student must take personal responsibility for knowing and following any University protocol related to pandemics and other public health events. Students are expected to follow all directives published by Tennessee Tech on its official webpage. As conditions related to the COVID-19 pandemic change, the University's COVID-19 protocols are also likely to change. Students are expected to monitor the University's official webpage to stay up to date on public health protocols.


## Acknowledgements

This syllabus is adapted from the syllabus provided by the TnTech office of the provost and the Berkeley Data 100 course syllabus.


