========
Syllabus
========

:title: Syllabus
:url:
:save_as: index.html
:sortorder: 0

Course Description
==================

| ME41055: Multibody Dynamics B
| Faculty of Mechanical, Maritime, and Materials Engineering, Delft University of Technology
| Year: 2021/2022, EC: 4
| Study Guide: https://studiegids.tudelft.nl/a101_displayCourse.do?course_id=59436
| MyTimeTable: https://mytimetable.tudelft.nl/link?timetable.id=2021!module!60F88CC63EE307A9C3BBB11EEDAF38C1
|

After the completion of this class you will have developed the skills to model,
interpret, simulate, and analyze `multibody systems`_, i.e. systems which are
made up of interconnected rigid bodies with arbitrary constraints and applied
loads. Mathematical models of multibody systems are typically very useful at
predicting the motion of macro scale objects. `Newton's laws of motion`_ are
the foundation of developing predictive models of these systems. Examples of
systems you will be able to model are: spacecraft trajectories, human/animal
biomechanics, vehicle motion, robot motion, etc.

.. _multibody systems: https://en.wikipedia.org/wiki/Multibody_system
.. _Newton's laws of motion: https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion

Learning Objectives
-------------------

Students will be able to:

- formulate a model and free body diagram of multibody systems
- incorporate holonomic and nonholonomic constraints into a multibody system
- derive the nonlinear and linear equations of motion of a multibody system
- simulate the motion of a multibody system with a computer
- interpret and analyze the results of motion simulation
- understand and explain notable dynamic phenomena

Prerequisites
-------------

We highly recommend taking TU Delft's "WB2630 Toets 1: Rigid-Body Dynamics"
prior to this course. Otherwise any introductory undergraduate level dynamics
course should suffice. If you haven't had a dynamics course, you can probably
get by if you are motivated and you already know:

- Linear algebra
- Vector calculus
- Calculus based physics
- Statics
- Introductory numerical methods
- Introductory scientific computing

You should also be proficient with at least one scientific programming
language. You will be learning and using Python_ for the class assignments.

.. _Python: http://www.python.org

Instructors
===========

.. list-table::
   :class: table
   :header-rows: 1

   * - Primary Instructor
     - Junior Lecturers
     - Teaching Assistants
   * - | Dr. Jason K. Moore
       | Assistant Professor
       | BioMechanical Engineering Department
       | j.k.moore@tudelft.nl
       | Office Room #: 34 F-1-140
     - | Rosanne Pries, R.A.Pries@tudelft.nl
       | Domas Syaifoel, D.M.Syaifoel@tudelft.nl
     - | Zofia Tyczyńska, Z.A.Tyczynska@student.tudelft.nl
       | Akshath Ram Veeravalli Hari, A.R.VeeravalliHari@student.tudelft.nl

Time and Location
=================

Lecture videos will be posted online for viewing each Friday, starting February
4, 2022. You will be expected to watch the videos before the work sessions on
Tuesdays. Homework work sessions will occur each week on Tuesdays:

- Quarter 3: Tuesdays 13:45-15:45, 3mE-CZ D (James Watt) & Online via MS Teams
- Quarter 4: Tuesdays 15:45-17:45, 3mE-CZ D (James Watt) & Online via MS Teams

The current coronavirus regulations permit 75 students in the lecture hall at
one time. If you want to attend in-person, you must sign up each week for one
of the 75 slots on the appropriate group in Brightspace. All others will have
to join via Microsoft Teams for these sessions. The MS Teams connection
information is available in Brightspace.

.. topic:: Coronavirus update Feb 18
   :class: alert alert-info

   As of Febryary 18th, there are no restrictions on the number of students in
   the classroom so the group signup is no longer needed to join the lecture
   hall. The class will still be offered in hybrid format. As of February 25th,
   masks and social distancing are no longer required at the University.
   Coronavirus is still present, so please take into consideration the health
   of everyone. Self-test regularly and stay home if you have any symptions or
   test positive.

Lecture topics are shown on the `schedule page`_.

Academic Integrity
==================

Academic dishonesty will not be tolerated. All homework assignments turned in
for a grade must be your (or you and your partner's) unique work. You may base
your answers off of external materials, but not your classmate's work. You will
have to include a contribution explanation with each homework submission. This
contribution explanation should explain the contributions each of the partner's
made and any help you received from people other than the instructors.

If you make use of code found in other materials that you did not write
yourself, either directly or in a modified form, you must follow the copyright
licenses associated with that material. If there is no copyright license
present, then you must obtain a written and signed permission from the author
of the materials and provide that with your assignment submission. If there is
a copyright license present in the materials you use (e.g. GPL, MIT, BSD,
CC-BY), then you must follow the terms of that license. Most licenses, at
minimum, require you to include the license with your work submission. This
mirrors what you will have to do, by law, in your future work.

All code and written answers will be checked for plagiarism amongst student
submissions and against external materials. Unattributed plagiarized materials
will be marked with a 0 grade. Multiple offenses will result in no grade for
the course.

Course Text and Materials
=========================

The course will be based primarily on these online lecture notes which will be
provided incrementally as we proceed through the course:

   Jason K. Moore. Learn Multibody Dynamics, 2020.
   https://moorepants.github.io/learn-multibody-dynamics

The primary principles and notation are based on this freely available book:

   Thomas R. Kane, and David A. Levinson. Dynamics, Theory and Application.
   McGraw Hill, 1985. http://hdl.handle.net/1813/638.

Note that the book is out of print, but you can download a PDF copy from
Cornell's eCommons digital repository for personal use.

Additionally, some topics will be derived from the following books:

   Heike Vallery and Arend L. Schwab, "Advanced Dynamics", 3rd edition, Delft
   University of Technology, 2020, ISBN/EAN 978-90-8309-060-3

   Thomas R. Kane, Peter W. Likins, and David A. Levinson. Spacecraft Dynamics.
   McGraw Hill, 1983. http://hdl.handle.net/1813/637.

Software
========

We will be making extensive use of the computer aided algebra software SymPy_
along with NumPy_ and SciPy_ to model and simulate multibody systems. These
packages are written in the open source Python programming language and
leverage the scientific Python ecosystem of scientific and engineering
computing tools. You will have access to these through Vocareum in Brightspace.
You may also install the software on your own computer. It is recommended that
you bring your laptop to the work sessions. See the `software page`_ on this
website for more information.

.. _SymPy: http://sympy.org
.. _NumPy: http://numpy.org
.. _SciPy: http://scipy.org

Assignments & Grades
====================

*Grade calculation statement updated on Feb, 11 2022.*

The average of your best 10 of 12 homeworks will be counted for 60% of the
course grade and the exam will count for 40% of the course grade. You must
score at least a 3 of 10 (30%) on the exam to pass the course when the grade is
in combination with your homework score. If the exam grade is better than the
average homework grade or if you are taking a resit exam, then the course grade
is 100% from the exam.

Homework
   There will be 12 computational homework assignments. Homeworks will be made
   available via Brightspace-Vocareum one week before they are due. You may
   turn in homework as a pair or as an individual. To submit as a pair, you
   must invite your partner within the Vocareum interface for each homework.
   All homework submissions should be the unique work of the individual or the
   pair. You must provide a contribution statement for each homework explaining
   any help you have received and any copyright licenses for materials you have
   used. See the `schedule page`_ for homework deadlines.
Exam
   The exam will have a 3 hour duration. You will be able to bring any physical
   printed resources available to you, e.g. books, Jupyter notebooks, websites.
   Effective use of the computational tools taught in class will give you the
   best chance at succeeding, but they are not necessarily required to succeed.
   No help from other people during the exam is permitted.

Brightspace
===========

We will be using several features in Brightspace:

Announcements
   This will be the instructor's primary communication avenue to you. These
   announcements can be forwarded to your TU Delft email address. You are
   expected to read these when shared.
Content -> Vocareum (Jupyter Notebook Server)
   You will access the homework Jupyter notebook assignments here. You can edit
   and execute the notebooks in the Vocareum interface that is linked via each
   assignment. The "Sandbox" assignment gives access to a Vocareum Jupyter
   instance where you can practice and explore the software.
Collaboration -> Discussions
   All questions for the instructors (or fellow classmates) that are not of a
   private nature should be asked in Brightspace discussions. If you need to
   discuss something of a private nature with the instructor(s), use email.
Grades
   Homework grades will be posted to Vocareum and/or Brightspace throughout the
   duration of the course.
Groups
   To attend the work sessions in-person, you must sign up for that week's
   group. It is first come, first serve for the 75 open slots. *As of February
   18th, this is no longer required. See note above.*

.. _schedule page: {filename}/pages/schedule.rst
.. _software page: {filename}/pages/software.rst
