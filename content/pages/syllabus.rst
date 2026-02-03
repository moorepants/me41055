========
Syllabus
========

:title: Syllabus
:url:
:save_as: index.html
:sortorder: 0

Course Description
==================

| ME41056: Multibody Dynamics
| Faculty of Mechanical Engineering, Delft University of Technology
| Year: 2025/2026, EC: 5
| Study Guide: https://studiegids.tudelft.nl/courses/study-guide/educations/19254
|

After the completion of this class you will have developed the skills to model,
interpret, simulate, and analyze `multibody systems`_, i.e. systems which are
made up of interconnected rigid bodies with arbitrary constraints and applied
loads. Mathematical models of multibody systems are useful for predicting the
motion of macro scale objects. `Newton's laws of motion`_ are the foundation of
developing predictive models of these systems. Examples of systems you will be
able to model are: spacecraft trajectories, human/animal biomechanics, vehicle
motion, robot motion, etc.

.. _multibody systems: https://en.wikipedia.org/wiki/Multibody_system
.. _Newton's laws of motion: https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion

Learning Objectives
-------------------

Students will be able to:

- derive the equations of motion for a simple planar system, draw free body
  diagrams, set up constraint equations, and demonstrate the uniqueness of the
  solution
- derive the equations of motion for a system of interconnected rigid bodies by
  means of a systematic approach
- derive the equations of motion in terms of generalized independent
  coordinates
- apply the techniques from above to systems having holonomic and nonholonomic
  constraints
- perform various numerical integration schemes on the equations of motion, and
  predict the stability and accuracy of the applied methods
- perform numerical integration on a coupled system of differential and
  algebraic equations (DAEs) with minimal constraint drift
- derive the equations of motion for a general rigid three-dimensional body
  system bound by constraints
- identify the need to describe orientation in 3D space by means of: Euler
  angles and Tait-Bryan angles and derive the angular velocity and
  accelerations in terms of these parameters and their time derivatives
- create accurate, efficient, and documented computer programs that construct
  and simulate multibody systems
- analyze and interpret the resulting motion from a multibody simulation

Prerequisites
-------------

We highly recommend taking TU Delft's "WB2630-T1: Rigid-Body Dynamics" prior to
this course. Otherwise any introductory undergraduate level dynamics course
should suffice. If you haven't had a dynamics course, you can probably get by
if you are motivated and you already know:

- Linear algebra
- Vector calculus
- Calculus based physics
- Statics
- Introductory numerical methods
- Introductory scientific computing

You should also be proficient with at least one scientific programming
language. You will be learning and using Python_ for the class assignments.

Instructors
===========

.. list-table::
   :class: table
   :header-rows: 1

   * - Primary Instructor
     - Co-Instructors
   * - | Dr. Jason K. Moore
       | Assistant Professor
       | BioMechanical Engineering Department
       | j.k.moore@tudelft.nl
       | Office Room #: 34 F-1-140
     - | Dr. Pier de Jong, p.h.dejong@tudelft.nl
       | Christoph Konrad, c.m.schmidt@tudelft.nl
       | Benjamin González, B.GonzalezToledo@tudelft.nl

Time and Location
=================

Lecture videos will be posted online for viewing each Monday, starting February
9, 2026. You will be expected to watch the videos and read the online notes
before the lecture and work sessions on Wednesdays (Q3) and Thursdays (Q4). We
will have a brief in-person lecture followed by homework work sessions each
week on Wednesdays (Q3) or Thursdays (Q4):

- Quarter 3:

  - Lecture: Wednesdays 13:45-14:15 in ME-Lecture Hall B - Isaac Newton
    (34.A-0-720)
  - Work Sessions: Wednesdays 14:15-16:15 in ME-Hall G (34.D-1-010), ME-Hall I
    (34.D-1-200), ME-Hall J (34.D-1-300), ME-Hall M (34.D-1-610)

- Quarter 4:

  - Lecture: Thursdays 10:45-11:15 in ME-Lecture Hall B - Isaac Newton
    (34.A-0-720), except on May 28th in ME-Lecture Hall C - Daniel Bernoulli
    (34.A-0-620)
  - Work Sessions: Thursdays 11:15-13:15 in either Pulse-Hall 1 (33.A0.300) or
    Pulse-Hall 3 (33.AT0.300) (changes each week)

Planned lecture topics are shown on the `schedule page`_.

Course Text and Materials
=========================

The course will be based primarily on chapters from this online book:

**Jason K. Moore. Learn Multibody Dynamics** https://moorepants.github.io/learn-multibody-dynamics

Chapters will be updated each week, so always check for the latest version when
the associated lecture videos are released.

The primary principles and notation are based on this freely available book:

**Thomas R. Kane, and David A. Levinson. Dynamics, Theory and Application.
McGraw Hill, 1985.** http://hdl.handle.net/1813/638.

Note that the book is out of print, but you can download a PDF copy from
Cornell's eCommons digital repository for personal use.

Additionally, some topics will be derived from the following books:

- Heike Vallery and Arend L. Schwab, "Advanced Dynamics", 3rd edition, Delft
  University of Technology, 2020, ISBN/EAN 978-90-8309-060-3
- Thomas R. Kane, Peter W. Likins, and David A. Levinson. Spacecraft Dynamics.
  McGraw Hill, 1983. http://hdl.handle.net/1813/637.
- Stephen H. Crandall, Dean C. Karnopp, Edward F. Kurtz, Jr., and David C.
  Pridmore-Brown, "Dynamics of Mechanical and Electromechanical Systems", 1968.

Assignments & Grades
====================

The average of your best 10 of 12 homeworks will be counted for 40% of the
course grade and the exam will count for 60% of the course grade. You must
score at least a 5 of 10 (50%) on the exam to pass the course when the grade is
in combination with your homework score. If the exam grade is better than the
average homework grade, then the course grade is 100% from the exam. Homework
scores can only be used to supplement your exam grade if the homeworks were
completed in the same academic year as the exam is given. The rounding rules
and grade calculations will follow the TU Delft exam regulations.

Homework
   There will be 12 computational homework assignments (HW00 is not graded).
   Homeworks will be made available via Brightspace-Vocareum one week before
   they are due. You may turn in homework as a pair or as an individual. To
   submit as a pair, you must invite your partner within the Vocareum interface
   for each homework. All homework submissions should be the unique work of
   the individual or the pair. You must provide a contribution statement for
   each homework explaining any help you have received and any copyright
   licenses for materials you have used. See the `schedule page`_ for homework
   deadlines. No homework will be accepted late.
Exam
   The exam will have a 3 hour duration. Effective use of the computational
   tools taught in class will give you the best chance at succeeding, but they
   are not necessarily required to succeed. You will be able to bring reference
   materials to the exam. No help from other people during the exam is
   permitted. Exact exam rules will be shared in Q4.

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
   discuss something of a private nature with the instructor(s), use email or
   talk in person.
Grades
   Homework grades will be posted to Vocareum and/or Brightspace throughout the
   duration of the course.

Software
========

We will be making extensive use of the computer aided algebra software SymPy_
along with NumPy_ and SciPy_ to model and simulate multibody systems. These
packages are written in the open source Python_ programming language and
leverage the scientific Python ecosystem of scientific and engineering
computing tools. You will have access to these through Vocareum in Brightspace.
You may also install the software on your own computer. It is recommended that
you bring your laptop to the work sessions. See the `software page`_ on this
website for more information.

.. _SymPy: http://sympy.org
.. _NumPy: http://numpy.org
.. _SciPy: http://scipy.org
.. _Python: https://www.python.org

Academic Integrity
==================

Academic dishonesty will not be tolerated. All homework assignments turned in
for a grade **must be your (or you and your partner's) unique work**. You will
have to include a contribution explanation with each homework submission even
if you do the homework alone and not as a pair. This contribution explanation
should explain the contributions each of the partners made and any help you
received from people other than the instructors.

If you make use of code found in other sources that you did not write yourself,
either directly or in a modified form, you must follow the copyright licenses
associated with that material. If there is no copyright license present, then
you must obtain a written and signed permission from the author of the
materials and provide that with your assignment submission. If there is a
copyright license present in the materials you use (e.g. GPL, MIT, BSD, CC-BY),
then you must follow the terms of that license. Most licenses, at minimum,
require you to include the license with your work submission. This mirrors what
you will have to do, by law, in your future work.

Generative AI tools are now used widely in the world. Many of these tools can
solve university course learning exercises with little effort or learning by
the student. Submitting any materials that are assessed for feedback or grading
purposes that are generated by AI tools is a violation of academic integrity in
the same way that submitting materials generated by another person are.
Generative AI produced text, code, images, videos, etc. may also violate
copyright laws.

All code and written answers will be checked for plagiarism and generative AI
results. Unattributed plagiarized materials or generative AI produced materials
will be marked with a 0 grade. Multiple offenses will result in no grade for
the course. Homework and contribution statements will be reviewed for integrity
during any grade disputes.

Homework Contribution Statements
--------------------------------

*A single contribution statement with explanations for both sections are
required for each homework whether you submit individually or as a pair.
Homeworks will be graded with a 0 if a sufficient contribution statement is not
included or no statement is included.*

The contribution statement consists of two parts:

1. Descriptions of you or your and your partner's contributions to the work and
   any contributions from other non-instructors to the solution.
2. Copyright permission from the creators of code, text, images, etc. that were
   copied or copied and modified for the solution.

**Section 1**

If you worked as an individual, then state that here.

If you work in a pair, both partners are expected to make intellectual and
coding contributions to the code written for the solutions. Describe who wrote
what code and how each partner contributed to the formulation of the solution.

For solo and partner submissions you may obtain help from others, but you must
explain how any non-instructor contributed to your solution. This includes help
derived from any living or non-living source, including but not limited to
generative AI tools like ChatGPT, Perplexity, or GitHub Copilot.

We expect that the submitters (both you and your partner) formulate, write, and
execute the submitted version of the code.

**Section 2**

If you make use of materials (code, text, images, etc.) that you did not create
yourself, either directly or in a modified form, you must follow the copyright
licenses associated with that material. If there is no copyright license
present, then you must obtain a written and signed permission from the author
of the materials and provide that with your assignment submission. If there is
a copyright license that allows reuse present in the materials you use (e.g.
GPL, MIT, BSD, CC-BY), then you must follow the terms of that license. Most
licenses, at minimum, require you to include the license with your work
submission. This mirrors what you will have to do, by law, in your future work.
For online materials, include URLs to the materials you used and URLs to their
licenses. For other materials, include the creator's permission or their
licenses. It is currently not clear who owns the copyright from code generated
from AI tools like ChatGPT and Copilot and they may generate copyrighted code;
use at your own risk! If you did not use any other code or materials, then say
so.

Example contribution statement:

1. Moses Dinkle and Sandra Dee worked on this homework together as partners. We
   each did problems 1-3 independently first and then compared answers. We
   reworked our solutions together and Sandra typed the final combined answers
   into the notebook. For problem 4, Moses typed the solution while Sandra
   discussed and suggested what to do and made the necessary sketches. For
   problem 5, we struggled with the problem and our classmate Rutger Hauer
   helped talk us through the errors we were making. With Rutger's explanation
   we then typed up the solution the solution together. We used ChatGPT to find
   a coding error in problem 5.
2. All solutions were our original work, except for problem 2 and 5. For
   problem 2 we found an example on Stackoverflow that was similar. We copied
   the Stackoverflow code and then reworked it to solve Problem 2. Here is the
   Stackoverflow post
   https://stackoverflow.com/questions/8739227/how-to-solve-a-pair-of-nonlinear-equations-using-python
   and the copyright license is CC-BY-SA 4.0 which is shown in tiny font at the
   very bottom right of the Stackoverflow page. We even used modified versions
   of two lines from Rutger's code that he showed us and he gave his permission
   to use those lines in our work.

Previous Year Materials
=======================

- Course website fro the 2024-2025 academic year: https://moorepants.github.io/me41055/2025
- Course website fro the 2023-2024 academic year: https://moorepants.github.io/me41055/2024
- Course website fro the 2022-2023 academic year: https://moorepants.github.io/me41055/2023
- Course website fro the 2021-2022 academic year: https://moorepants.github.io/me41055/2022

.. _schedule page: {filename}/pages/schedule.rst
.. _software page: {filename}/pages/software.rst
