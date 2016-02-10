Hello Sophilaber
----------------

This is the team’s playbook, your playbook.

You will find here how you and your teammates should run our software consulting
company, and the tools and practices that should guide us to create quality
software products.

This document is in a continuous development process and you are a key player
to make it evolve. Please contribute to it using `this repo
<https://git.sophilabs.io/sophilabs/playbook>`_.

Principles
----------

We've learned from our experience that working with people that share the
correct set of principles is the foundation for creating highly productive
teams.

**Aim high** and encourage everyone else to outstand above the average.

**Look into the details**, a great product is the sum of perfectly well thought
details.

**Practice impersonation** helping pursuing other people’s goals as if they
were yours.

**Be Honest**, never sacrifice honesty for politeness.

**Love your craft** and strive to transcend through your creations.

Squads
------

We realized that we needed to divide our forces in order to build a
great company.

One of our core principles is *always aim high*, and to be consequent we
need to have demanding objectives:

* Hire the best people
* Work for the best companies
* Craft the best software
* Build something that people love

We created specialized workgroups that strive to achieve those goals by
defining universal guidelines and ensuring they are always applied.

The current squads -classified by objective- are:

-  Hire the best people
 -  Recruitment squad
-  Work for the best companies
 -  Sales squad
-  Craft the best software
 -  Code Analysis squad
 -  Deployment squad
 -  Methodologies squad
 -  Product Design / UX squad
 -  Testing squad
 -  Security squad
 -  Software Design squad
-  Build something that people love
 -  Research & Innovation squad

In addition, we need to support sophilabs infrastructure and operations:

- Infrastructure squad

How it works
============

Workflow
~~~~~~~~

Every squad follows the same workflow (M.A.P.E.D.):

1. **M**easure teams and projects on different areas
2. **A**nalyze measurements in order to detect the underlying issues and areas of improvements
3. **P**ropose changes and design an action plan considering different scenarios
4. **E**nsure the action plan is executed and help solving stoppers
5. **D**ocument lessons learned and how the plan affected the measurements
6. Go to 1.

Metrics
~~~~~~~

The squads define their own objectives and principles.
In order to measure performance on different projects,
metrics are needed. We use automated tools to measure quantifiable metrics and
quizzes that we distribute periodically to teams and customers to measure
opinionated metrics.

Facing
^^^^^^

There are negative metrics (higher is worst) and positive metrics (higher
is better).
The ones marked with ▲ are positive, the others marked with ▼ are negative.

Types
^^^^^

Some squads define multiple metrics for the same principle/objective. For those
scenarios, primary and secondary metrics are defined, primary metrics are shown
in the dashboard, while secondary metrics are shown in the detailed view of
each project.

Primary metrics are identified in this document in bold text.

Dashboard
~~~~~~~~~

Customers can see the status of their projects by visiting
`dashboard.sophilabs.io <https://dashboard.sophilabs.io>`_

There are also TVs distributed all around our offices that show the status of each
metric for every project.

This adds true visibility and make everybody feel the responsibility of
improving things.

Code Analysis Squad
===================

-  Software quality
-  principles
-  simplicity
-  consistency
-  elegance
-  legibility
-  scalability

Deployment Squad
================

Objectives
~~~~~~~~~~

-  Objective 1

Methodologies Squad
===================

Objectives
~~~~~~~~~~

Ensure that the software development processes used on different
projects meet the following principles.

Adaptability
^^^^^^^^^^^^

The team's ability to quickly adapt to unexpected changes.

Productivity
^^^^^^^^^^^^

The output rate of the team is above the average.

Visibility
^^^^^^^^^^

The team is traceable and all documents and resources are accessible.
The team proactively documents and informs to put everyone in the same
page.

Satisfaction
^^^^^^^^^^^^

Team, client and stake holders are happy.

Integration
^^^^^^^^^^^

Team and client are involved in the project.

Automation
^^^^^^^^^^

All the repetitive processes and tasks that add overhead are automated.

Motivation
^^^^^^^^^^

Team members do want to work in the project.

Simplicity
^^^^^^^^^^

Doing only what is needed every time.

Metrics
~~~~~~~

These are the metrics designed by the squad, classified by principle.

Adaptability
^^^^^^^^^^^^

- ▲ **# releases to staging**
- ▲ # tickets related to process changes closed
- ▲ # retrospective meetings

Productivity
^^^^^^^^^^^^

- ▲ **# estimated time / invested time**
- ▼ # change requests on features released to staging less than a week ago


Visibility
^^^^^^^^^^

- ▲ **total invested hours / invested hours on the project without a ticket**
- ▼ # tickets assigned with size > 8 (enormous) / # total tickets

Integration
^^^^^^^^^^^

- ▲ **# status meetings**
- ▲ # roles and responsibilities documented / # team size
- ▲ # communication channels defined and documented for: What, Organization, Status and Urgent

Satisfaction
^^^^^^^^^^^^

- ▲ **Average of all metrics measured**
- ▲ Adaptability satisfaction
- ▲ Productivity satisfaction
- ▲ Visibility satisfaction
- ▲ Integration satisfaction
- ▲ Automation satisfaction


Automation
^^^^^^^^^^

- ▲ **invested time on automation tasks / total hours invested by the team**
- ▼ invested time on development repetitive tasks / total hours invested by the team


Recruitment Squad
=================

Objectives
~~~~~~~~~~

-  Hire great talents with experience or potential.
-  Offer talents to Sophilabs as soon as they are required.
-  Genrate an excellent reputation and culture so people will aspire to
   work at Sophilabs.

Scope
~~~~~

-  This group will be responsible for the hiring process and the three
   months trial period.
-  Attend to inquiries from the Sales and Operations offices.
-  Ask for tasks to the Meeting and Operation offices.

Sales Squad
===========

Objectives
~~~~~~~~~~

-  Objective 1

Testing Squad
=============

Objectives
~~~~~~~~~~

Encourage that software built by sophilabs has the necessary
mechanisms to boost the following principles in an execution
environment.

Reliability
^^^^^^^^^^^

The application should behave as expected.

Robustness
^^^^^^^^^^

The application should be able to continue operating despite
abnormalities.

Correctness
^^^^^^^^^^^

The application is compliant with the requirements specification.

Glossary of terms
~~~~~~~~~~~~~~~~~

TBD

Metrics
~~~~~~~

These are the metrics designed by the squad classified by principle.

Reliability
^^^^^^^^^^^

-  **▲ # lines of code tested / # lines of code**
-  ▲ # unit tests asserts / # lines of code
-  ▲ # integration tests asserts / # lines of code
-  ▲ # validation tests asserts / # lines of code
-  ▼ # tickets tagged with “reliability issue” on a testing session

Robustness
^^^^^^^^^^

-  **▼ # server side uncaught exceptions**
-  ▼ # tickets tagged with “testing robustness” created on code review sessions
-  ▼ # tickets tagged with “robustness issue” on a testing session

Correctness
^^^^^^^^^^^

-  **▲ # acceptance tests asserts / acceptance criteria conditions**
-  ▼ # tickets tagged with “correctness issue” on a testing session

License
-------

The original idea comes from `Thoughtbot's playbook
<https://playbook.thoughtbot.com>`_, we took the great work they did and adapted
it to our philosophy.

.. image:: https://licensebuttons.net/l/by-nc/3.0/88x31.png
   :target: ./LICENSE.rst

Creative Commons Attribution-NonCommercial
