Hello Sophilaber
================

This is the team’s playbook, your playbook.

You will find here how you and your teammates should run our software consulting
company, and the tools and practices that should guide us to create quality
software products.

This document is in a continuous development process and you are a key player
to make it evolve. Please contribute to it using `this repo
<https://git.sophilabs.io/sophilabs/playbook>`_.

Principles
==========

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

Culture
=======

TBD

Time
====

TBD

Laptop
======

TBD

Technology
==========

TBD

Methodology
===========

The Agile way
-------------

We adhere to the `Agile Manifesto principles
<http://agilemanifesto.org/principles.html>`_, declaring that our highest
priority is to satisfy the customer through early and continuous delivery of
valuable software.
We welcome changing requirements, even late in development as we understand that
agile processes must harness change for the customer's competitive advantage.

We say that working software is the primary measure of progress, and to be
consequent we deliver working software frequently, from a week to a couple of
weeks, with a preference to the shorter timescale.

Agile processes promote sustainable development. The sponsors, developers, and
users should be able to maintain a constant pace indefinitely and must work
together daily throughout the project.

At regular intervals, we reflect on how to become more effective, then
tune and adjust our behavior accordingly. We look for a motivating environment
and culture, where everybody trusts each other to receive constructive feedback
and get the job done.

We strongly believe that continuous attention to details and technical
excellence enhances agility. And Simplicity --the art of maximizing the amount
of work not done-- is essential, at every level.

In our experience we have seen that the best architectures, requirements, and
designs emerge from self-organizing teams that truly understands these
principles, if you believe there are better ways to build good software we would
love to hear from you.

Product Design
==============

TBD by R&I Squad

User Experience
===============

TBD by UX Squad

Interaction Design
------------------

Visual Design
-------------

Software Design
===============

TBD by Software Design Squad

Development
===========

TBD by Code Analysis Squad

Testing
=======

TBD by Testing Squad

Deployment
==========

TBD by Deployment Squad

Monitoring
==========

TBD by Deployment Squad

Product Growth
==============

TBD by R&I Squad

Squads
======

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
------------

Workflow
~~~~~~~~

Every squad follows the same workflow (M.A.P.E.D.):

1. **M** easure teams and projects on different areas
2. **A** nalyze measurements in order to detect the underlying issues and areas of improvements
3. **P** ropose changes and design an action plan considering different scenarios
4. **E** nsure the action plan is executed and help solving stoppers
5. **D** ocument lessons learned and how the plan affected the measurements
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

There are also TVs distributed all around our offices that show the status of
each metric for every project.

This adds true visibility and make everybody feel the responsibility of
improving things.

Code Analysis Squad
-------------------

Principles
~~~~~~~~~~
- **Simplicity** : Minimize the effort required to understand a given source
  code.
- **Consistency** : Apply the same practices along the project and across
  similar projects.
- **Legibility** : The ability to understand the code at a statement level.
- **Scalability** : The activity of writing performant code at a statement-level.
- **Reusability** : The ability of a given piece of code to be reused in other
  projects without modification.

Objectives
~~~~~~~~~~
- Produce knowledge about code quality that can be applied to existing and new
  projects. This knowledge must be documented and only cover programming
  languages being used in Sophilabs. Examples include: guidelines, linting
  rules, workflows, conventions, etc. These documents won’t only refer to code,
  but also to how to ensure code quality (e.g. code reviews).
- Develop a plan or methodology to measure the effectiveness of the generated
  knowledge.
- Develop or improve tools that automate and control the quality of the code
  (linters, conventions, etc). This tools and documents must be Open Source.
- Adjust guidelines, workflows and other procedures to the needs of each project.


Metrics
~~~~~~~

Applicability of conventions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^
- # linter errors per 1000 lines of code

Code complexity
^^^^^^^^^^^^^^^
- avg # of conditionals per method/function
- avg # of LoC per method/function
- avg # of methods per class
- avg # of arguments per function/method
- avg # of nesting levels
- avg # ancestors of a class
- avg # of conditionals (branches)
- avg # of local variables

Modularity
^^^^^^^^^^
- avg # of LoC per module
- avg # of LoC per file

Legibility (Documentation in the code)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
- % of methods with docstring/annotations
- % of classes with docstring/annotations
- % of properties with docstring/annotations

Simplicity
^^^^^^^^^^
- # of modules

Pending: commit messages, code reviews, etc.

Deployment Squad
----------------

TBD

Methodologies Squad
-------------------

Objectives
~~~~~~~~~~

Ensure that the software development processes used on different
projects encourage the following principles.

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

Simplicity
^^^^^^^^^^

Doing only what is needed every time.

Predictability
^^^^^^^^^^^^^^

Estimated tasks were completed on time.


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

We can't measure productivity

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

Simplicity
^^^^^^^^^^

- ▼ **pages/states with a standard deviation on number of visits below 10%**

Predictability
^^^^^^^^^^^^^^

- ▲ ** estimated time / invested time**

Recruitment Squad
-----------------

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
-----------

TBD

Testing Squad
-------------

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

Sales
=====

TBD by Sales Squad

Hiring
======

TBD by Recruitment Squad

Operations
==========

TBD

Community
=========

TBD by Community Squad

Goodbye
=======

We are a group of people who love crafting hight quality software for next-generation products.
Thank you for being a part of it.

License
=======

The original idea comes from `Thoughtbot's playbook
<https://playbook.thoughtbot.com>`_, we took the great work they did and adapted
it to our philosophy.

.. image:: https://licensebuttons.net/l/by-nc/3.0/88x31.png
   :target: ./LICENSE.rst

Creative Commons Attribution-NonCommercial
