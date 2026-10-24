---
title: Syllabus
---

# Course Description

Welcome to CPSC 490X — Programming Language Paradigms

We're gonna be exploring functional programming, logic programming, and some
dependent types :)

# Course Staff

Anahita Golshani (she/her) <xa@student.ubc.ca> (student coordinator)

William J. Bowman (any) <wilbowma@cs.ubc.ca> (faculty sponsor)

I (Anahita) am the coordinator for this student directed seminar. Feel free to
reach out to me over email with any questions or concerns about the course
materials or logistics. If you don't feel comfortable discussing your concern
with the coordinator, feel free to send an email to the faculty sponsor,
William Bowman instead.

# Learning Objectives

By the end of the course, you should be able to:

- Compare functional, logic, and dependently typed paradigms and identify when
  applying each one could be beneficial.
- Recognise when to employ advanced type system features to encode structural
  and correctness invariants to catch otherwise difficult to find bugs at
  compile time.
- Explain the correspondence between mathematical objects and programming and
  be able to solve complex mathematical problems by writing programs.
- Design and build a large nontrivial project in a functional or logic paradigm,
  use idiomatic patterns for the language, and communicate design choices in
  formal writing.
- Have fun :)

# Prerequisites and Preparation

The only formal prerequisites are a 3rd or 4th year standing. However, this
course is written with the expectation that students will have a background in
functional programming. Experience in 110 is likely sufficient, but 311 is
preferred.

Class and assessments will also include extensive computer use. For class,
consider bringing (or sharing) a device.

# Evaluation

Your course mark will be based on the following breakdown. The course staff
reserves the right to change this scheme in ways that will not hurt any
student's grade.

| Category             | Weight                                                           |
| -------------------- | ---------------------------------------------------------------- |
| [Assignments]        | 50% (10% Each)                                                   |
| [Term Project]       | 35% (5% Proposal, 5% Demo, 10% Code, 10% Report, 5% Peer Review) |
| [In-Class Exercises] | 10% (1% Each)                                                    |
| [Participation]      | 5%                                                               |

In addition, we have [Bonus Points]. For every power of two you reach in bonus
points, we shift 1% point of weight from the category with your lowest grade to
the category with your highest grade. And there are other **fabulous rewards**
that come with [Bonus Points]!

## Academic Concession and Regrade Requests

If circumstances arise in your life that negatively affect your work, tell us
about it. We guarantee to at least keep a record of your concerns to review at
the end of the term. Remember that communicating sooner (and ideally before
deadlines) is better than later, and anytime is better than never.

While we listen to concerns any time, to get a _regrade_, you must make a clear
and complete request within two weeks of your grade being available, using the
feedback mechanism for that assessment. A good request lays out **all** issues
you have with the grading with clear reference to the question, your solution,
any provided solution and rubric, and the grading to show how you believe your
solution should have been graded differently.

For [PrairieLearn] assessments, submit an "issue" on the individual question.
For in-class participation or the project, contact [Anahita](mailto:xa@student.ubc.ca).
For later assessments, we may reduce the two week period for regrade requests.

For regrades, the course staff will review the marking in context and respond
with a final grade. The grade can go up or down based on review. The reviewed
grade is final, but you are still welcome to communicate further concerns to us.

For other concerns, see [UBC’s Review of Assigned Standing policy](https://vancouver.calendar.ubc.ca/campus-wide-policies-and-regulations/review-assigned-standing).

# Important Dates

Also see our [Schedule].

| Date | Description                                       |
| ---- | ------------------------------------------------- |
| W1   | A1 Out                                            |
| W3   | Add/Drop deadline; A1 Due; A2 Out; Team Formation |
| W5   | A2 Due; A3 Out                                    |
| W6   | Project Proposal Due                              |
| W7   | A3 Due; A4 Out                                    |
| W9   | A4 Due; A5 Out                                    |
| W11  | A5 Due                                            |
| W13  | Project Showcase                                  |
| EXAM | Report Due                                        |

# Schedule

Here is a tentative schedule of topics. Depending on our progress and interests,
we may move faster or slower through some parts and add or drop topics.

| Week | Session                                         |
| ---- | ----------------------------------------------- |
| W1A  | Course Logistics + FP Review                    |
| W1B  | Haskell: Higher-Order Functions + Lazy Eval     |
| W2A  | Haskell: Parametricity                          |
| W2B  | Haskell: Functor + Foldable + Recursion Schemes |
| W3A  | Haskell: Monad                                  |
| W3B  | Haskell: Monad                                  |
| W4A  | Haskell: Applicative + Comonad                  |
| W4B  | Haskell: Monad Transformers                     |
| W5A  | Haskell: Property-Based Testing                 |
| W5B  | Haskell: Profiling + Strictness                 |
| W6A  | Haskell: TDD + `DataKinds` + Proxy Types        |
| W6B  | Haskell: Type Families + GADTs                  |
| W7A  | Haskell: `LogicT` + Logic Programming           |
| W7B  | Prolog: Unification + Horn Clauses              |
| W8A  | Prolog: Box Model                               |
| W8B  | Prolog: DCGs                                    |
| W9A  | Prolog: Relational Programming                  |
| W9B  | Datalog                                         |
| W10A | Datalog: Borrow Checker + Pointer Analysis      |
| W10B | Idris: Intro to Dependent Types                 |
| W11A | Idris: Vector                                   |
| W11B | Idris: Curry-Howard Isomorphism                 |
| W12A | Idris: Zipper                                   |
| W12B | Idris: RBTrees                                  |
| W13A | Project Showcases                               |
| W13B | Project Showcases                               |

# Communication

Outside of lecture time, most communication with the course staff should go
through discussion in [Piazza], or sometimes via issues on [PrairieLearn]. For
private matters you're not comfortable sharing there, definitely feel free to
[e-mail us](#course-staff). In terms of [online systems](/resources.html#course-systems), we will use this website, [Piazza],
and [PrairieLearn].

# Assignments

Our series of short assignments will focus on hands-on practice with the course
material. The assignments are primarily for your practice and learning. We will
design grading for each assignment to reflect that: allowing full credit even
before you reach a fully correct solution. Assignments will be submitted on
[PrairieLearn]. In each assignment, look for the "maximum points" on a question
to see how many of the available points you need to earn for full credit. Each
assignment (except possibly the last) will also list a late submission deadline
for 75% credit.

Assignments are to be completed and submitted individually, but _with some
caveats_ you may collaborate with anyone and any resource. Refer to the
[Academic Conduct] guidelines **right away** for the caveats. (Roughly
speaking: acknowledge any person/resource that helps you and take a short
break before writing up your own solution on your own.)

# In-Class Exercises

In-class exercises will also be completed as "homework" on [PrairieLearn]. Each
set of in-class exercises scales your mark so that earning 90% of the available
points on the exercise is worth a 100% mark. As with assignments, each exercise
set (except possibly the last) lists a late submission deadline for 75%. If
lecture runs faster than expected, we will leave in-class exercise deadlines
unchanged. If lecture runs slower than expected, we will extend in-class
exercise deadlines.

You may work freely with others on in-class exercises.

# Participation

In-class participation includes asking and answering questions in class and on
Piazza, volunteering to solve problems in class, and posting interesting
course-related pointers to Piazza.

# Term Project

Outside of lecture and assignments, a majority of the time spent in this course
will be dedicated to a course project completed in teams of 2 (or 3 if the
amount of students is odd). You will have substantial freedom in the topic of
your project, but it must use either one of: Haskell, Prolog, or Idris (or
another similar language you clear with the course staff at the project proposal
stage).

There will be three major stages to the project:

1. Submitting a 2-page typeset proposal detailing the project scope, the course
   concepts applied, the extensions past the course context expected, and a
   feasibility plan.
2. Complete a working prototype at a level of polish acceptable to share with
   your peers, then present it (with a slideshow or video).
3. A typeset report (4-8 pages) and a complete, well documented repo
   (with testing!)

# Academic Conduct

Collaboration enhances the learning experience. We encourage collaboration in
various ways throughout the course, subject to the rules stated here.

**Course staff:** You can ask us for help and show us solutions regardless of
any limits below.

**In-Class Exercises:** We welcome collaborative work and use of resources on
in-class exercises (even if you're working on them outside of class!). Do try
problems yourself first! It helps with learning.

**In-Class Participation:** When the course staff isn't addressing the class or
specifically asking you to work alone, we welcome you discussing participation
questions with your neighbors. In the end, you have to participate for yourself,
however!

**Assignments:** Assignments are your individual work. You may also work with
any person or resource subject to these rules:

- Spend 15 minutes trying each problem yourself first.
- Collaboration with others is for planning, experiments, discussion, and
  brainstorming. Take no record away from the session (no files, notes, stone
  tablets, etc.), except your collaborators' names, which you'll need below.
- After collaborating, do something else for 30 minutes that is so distracting
  that you must have learned anything you can then reconstruct. (Have fun!)
- Write up your own solution independently, using your own words and code.
  (Where you copy/quote from resources, cite and acknowledge as always!)
- Acknowledge all collaborators and resources in your submission except the
  course staff.

Our [Piazza] site is a bit of a special case. To encourage discussion, we _are_
allowing posting assignment solution snippets there in questions, but keep them
short and to the point.

**Projects:** Projects are group work. Within your project group, you may
collaborate however you wish. You may also work with any person outside your
group or any resource _subject to the rules for assignments above_ with the
addition that you may use packages/libraries and adapt existing code (both
_with clear citation_) as needed.

Violation of any of these rules constitutes academic misconduct and is subject
to penalties ranging from a grade of zero on a particular assignment to
indefinite suspension from the University. If you are uncertain as to what is
or is not reasonable collaboration, or you’re having problems understanding or
keeping up, please contact the instructor or a TA. Don’t cheat! It sucks the
soul from the course.

## Generative AI Policy

For the purposes of this course, LLMs (i.e. ChatGPT, Claude, etc.) are
considered non-group-members and are _subject to the rules for assignments_.
LLM-assisted codegen (i.e. Cursor, Claude Code, etc.) is expressly prohibited.

[prairielearn]: https://us.prairielearn.com/pl/course_instance/XXXXXX
[piazza]: https://piazza.com/ubc.ca/XXXXXX
[bonus points]: /bonus.html
[schedule]: /schedule.html
[resources]: /resources.html
