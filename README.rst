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

Our main objective is to be an outstanding team of designers and engineers so
we will eliminate or simplify any policy that makes us diverge from that goal.
Most of the time you won’t find a policy, we encourage you to "use your best
judgement".

We avoid departments and prefer just a few hierarchies. We like composition of
roles necessary for projects and company objectives over inheritance of bosses
and direct reports.

We avoid having private conversations about each other or clients. Instead, we
talk in person, and use tools such as Slack, JIRA and GitLab to communicate
openly within a project, within sophilabs, and publicly.

We prefer open offices where everyone sees each other encouraging people to
collaborate spontaneously but keeping always a quiet environment, we say “work
comfortably but keeping the stillness of a library”. There are many places for
entertainment when you need to rest your head without disturbing your teammates.

Our standards are very high, and bringing on a new team member requires a "yes"
from everyone who participated in the interview process. Therefore, we expect
the best from each other, give each other the benefit of the doubt, and
encourage each other to take initiative to improve ourselves and the company.

Except for a few roles with pure management responsibilities, everybody at
sophilabs must dedicate at least part-time on programming software, on a
customer project, on internal tools or for the Research and Innovation
working group.

Time
====

We work a `sustainable pace<http://www.extremeprogramming.org/rules/overtime.html>`_.
From March to December we dedicate two days per
month as “investment days”, and one day during January and February. We
typically distribute investment days in the team in order to have at least one
member dedicated to the project everyday.
If a team member is absent from client work because of illness or study
holidays, we'll use investment days as extra client days to avoid slipping
behind schedule.

When taking time off during client work, we discuss how it will impact the
schedule with other team members.
Sending off-hours communication may create an unintended sense of urgency with
the recipients of your message. Try to avoid creating that urgency when
possible.
Unless actually urgent, you may ignore off-hours messages which you receive and
handle them once you are back at work.

Consulting
----------

Our main business is consulting projects. Those projects start with sales and
go through a normal flow of designing, developing, shipping, monitoring, and
iterating. We should do such a good job for our clients that they will want to
poach us, and be such a great place to work that we can be confident our
teammates won't leave.

Investment
----------

Investment days are days for investment in ourselves, our company, and our
community. Primarily this means doing something that interests us like
defining best practices, investigating a new framework, contributing to open
source, writing a blog post, attending community events, or reading an
educational book. The goal is to encourage individuals to improve and share
their knowledge with the rest of the team.

The time you invest during these days must generate value, in different forms:

- Pick from or contribute back to guidelines and playbook
- Completing squads’ pre-defined tickets
- Contributing or creating open source software
- Writing a blog post
- Explore change to tools and processes on the "R&I" JIRA project
- Work on conference and meetup talks and proposals
- Work on Sophia or other internal projects

There is a difference between a normal investment day, and extended downtime
between client projects (being “on bench”).

Extended periods of time between client projects should skew heavily towards
revenue generating activities. This could be working on existing revenue
generating products and services, networking and sales, or creating something
new that will generate revenue.

Because this extended time period will go away when you resume client work, and
because we can't sustain non-revenue generating activities for long, approach
this extended time between client projects with a sense of urgency.
Validating ideas, shipping, and getting to revenue generation as quickly as
possible should be a priority. We shouldn't go weeks without results to show,
and we should impose the same constraints and process as we do on client
projects.

Laptop
======

MacBook Pro
-----------

Every person that joins Sophilabs receives a MacBook Pro latest generation.
These laptops are known for their performance, robustness, great look & feel
and battery life, but for us, the most important feature is that they allow us
building and testing apps on any platform: OSX, Linux and Windows.

Text Editor/IDE
---------------

Plain text won't become obsolete. It helps leverage your work and simplifies
debugging and testing. The editor should be an extension of your hand; make
sure your editor is configurable, extensible, and programmable. -The Pragmatic
Programmer

We encourage everyone to be an expert using his favorite programming tool. Know
every shortcut and automate repetitive tasks to gain more productivity so you
can focus on building the software the way we want.

Technology
==========

Early in a project, we have to decide which platforms we'll use.
Which platform depends on our ideas for solving the users' problems. For
example, if they're construction workers on a job site, a mobile or tablet
interface might be the best choice.

After considering what's best for users, what's best for us?

- The tools are open source with a strong community
- The tools make us happy
- The tools help us create and iterate quickly

Web Apps
--------

In our experience, teams using the `Django framework<https://www.djangoproject.com/>`_
can bring products to market more quickly and with a lower total cost of
ownership than other tools. There's also strong overlap between the agile and
Python communities, which means (among things) that Python developers tend to
write adaptable modules, write tests and avoid repeated code.

In addition to Python, we use other open source software and web standards such
as HTML, CSS, JavaScript, UNIX and Postgres because they:

- Are high quality.
- Avoid vendor lock-in.
- Provide flexibility to switch components.
- Work on many devices.
- Are battle-tested.
- Have few bugs when seen by many eyes.

Django comes with features that decrease the burden on the programmer to protect
against security attacks such as:

- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)
- SQL injection
- Header injection

Django helps us do the right thing with regards to security but we are still
required to be diligent, knowledgeable, and test comprehensively.
We support Internet Explorer 10+ and the latest versions of Firefox, Chrome, and
Safari. We do not support Internet Explorer 6, 7, 8, or 9. Those browsers are
`losing market share<https://en.wikipedia.org/wiki/Internet_Explorer#Market_adoption_and_usage_share>`_,
they have `security issues<https://en.wikipedia.org/wiki/Internet_Explorer_6#Security_issues>`_,
and they are time-consuming to design for, develop for, and support.
On mobile devices, we support iOS Safari 7.1+, Android Browser 4.4+, and the
latest version of Chrome for Android.
In limited special cases, user demographics will dictate that supporting an
older version of Internet Explorer is required. Those special cases should be
identified early on so we can plan for additional time and expense in order to
support the version.

Mobile Apps
-----------

"Mobile" refers to the user, not the device.
Everything about how we design a mobile application has to be in the context of that idea. It raises questions like:

- Are they moving?
- Are they relaxed on a couch?

We try to start with the most usable platform first. If the device needs the
camera, calendar, or address book, an “hybrid” app for iPhone, iPad or Android
may be the right choice. If the app is targeted for a massive audience and/or
the app performance is critical we recommend developing two separate “native”
apps for iOS and Android.

For other products, especially content-only products such as text, images,
videos, and landing pages, a mobile web app makes sense because:

- All modern smartphones can render HTML.
- We can create and iterate quickly.
- We can deploy new versions multiple times a day.

Our mobile engineers expertise is with the Ionic Framework to create multi
platform apps and Swift when we want to create platform specific apps for
iPhones, iPads or Apple Watches.

Programming Languages
---------------------

Examples of languages we typically use are:

- Python, NodeJS: our server-side preferences
- Javascript: our client-side preference for web and mobile hybrid apps

Frameworks
----------

Examples of frameworks we typically use are:

- Django
- Flask
- Express
- HapiJS
- Loopback
- Angular
- Ember
- React
- Ionic

A framework is a library that makes performing a particular task in a
programming language easier. Like the framework of a house, it is there when we
begin programming and is always there giving the program structure and support.

Databases
---------

For data that must be saved and stored correctly, we use `PostgreSQL<http://www.postgresql.org/>`_
(we usually refer to it as "Postgres").
It's a 30 year old open source database that is highly respected, well supported
by documentation and hosting providers, and used by any developer who knows the
SQL standard.

In recent years, a movement called `NoSQL<https://en.wikipedia.org/wiki/NoSQL>`_
has gained popularity. Best translated
as "not only SQL", tremendous effort has been made to create different kinds of
databases for different use cases, often based off `academic or industry
research<http://nosqlsummer.org/papers>`_.

Our most frequently used NoSQL database are `Redis<http://redis.io/>`_, which we
use for storing
transient, high quantity read/write data such as activity feeds, tags,
background jobs, sessions, tokens, and counters; `Cassandra<http://cassandra.apache.org/>`_
which we use for storing time series.

Redis and Cassandra are reliable, open-source, and simple. They offer high
performance and reliable predictions of its performance.
When we need to do full-text search on documents, we use `Solr<http://lucene.apache.org/solr/>`_.
Its major features include hit highlighting, faceted search, real-time indexing,
dynamic clustering, database integration, and rich text documents handling.

Licenses
--------

In contrast with a proprietary license, the source code of an open source
program is made available for review, modification and redistribution. The
difference between open source licenses is what we can and can't do with the
source code.
Open source licenses can be divided in two categories: permissive and copyleft.
Permissive examples include:

- `Berkeley Software Distribution (BSD) licenses<https://en.wikipedia.org/wiki/BSD_licenses>`_
- `MIT license<https://en.wikipedia.org/wiki/MIT_License>`_
- `Apache license<http://en.wikipedia.org/wiki/Apache_License>`_

A copyleft example is the `General Public License (GPL)<https://en.wikipedia.org/wiki/GNU_General_Public_License>`_.
Both categories have the purpose of establishing the copyright holder for the
software, granting users the right to copy, modify and redistribute it,
protecting the copyright holder from any potential guarantees that the software
may provide (software is provided as-is), and optionally imposing some
restrictions.

Permissive licenses let us modify a program, redistribute it, and even sell it.
We can embed or link code with other programs without restriction or explicit
permission by the copyright holder.
Copyleft licenses only allow us to link or distribute code with other code that
has the same license. It also forces modifications to be released under the same
license. Combining anything with the GPL makes it GPL.

Non-copyleft licenses do not enforce derivative works to also be open source.
Some software is released under a dual license: both a permissive and copyleft
license. This provides developers who use the dual licensed code to apply the
license that better suits their needs.

Most of the software we use has a permissive license:

- PostgreSQL, PostgreSQL License (BSD based)
- Redis, BSD
- Solr, Apache License 2.0
- Python, Python Software Foundation License (PSFL) (BSD based)
- Django, Django license (BSD based)
- AngularJS, MIT

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
principles.

Project kick off
----------------

When a project starts a kick off meeting is set up, please use this document to
guide the presentation.

After that, the following stuff is set up:

- Project mailing-list: project@sophilabs.com, which includes the client and project-dev@sophilabs.com, which include only the technical team
- JIRA tracker (provided by client)
- Gitlab or Github repositories (provided by client)
- Jenkins project (provided by client)
- Access to cloud service (security groups and roles)
- Google docs folder (ask client for a documents repository or use docs.sophilabs.io instead)

Standups
--------

During the morning, every project team get together for 15 minutes.
We say what we did yesterday, what we're going to do today, and expose blockers.
We immediately resolve blockers together or help the person after standup.

We do this in order to:

- See each other face-to-face.
- Learn what others are doing so you can help them.
- Build accountability and trust.

Tasks
-----

We have used Redmine, JIRA, Pivotal Tracker, Asana, Trello and other task
management systems over the years. The following section details a process
using JIRA but the overall process remains relatively similar across different
systems.
No two products are the same, so flexibility in the product development process
is important. JIRA responds well to changing the structure of the process
"on the fly."

In any task management system, it's important to have a view into the product
development process. The Current Sprint is the single prioritized list to which
the product team refers in order to know what to work on next. It represents
two weeks of work.
A story represents a job story, bug fix, engineering task, or general todo.
They start out as a simple idea, 1-2 sentences long. Detail is added,
explaining why (from a business perspective) we're focusing on it, descriptive
wireframes and maybe notes on suggested implementation, sometimes is good idea
including the acceptance criteria of the story.

Once the stories in the Sprint have been prioritized and vetted, they are ready
for design and development. A designer or developer "puts their face on it" by
assigning it to themselves and pulling it into the In Progress column.
The stories in the In Progress column are actively being designed or developed.
You should never have your face on more than two stories at a time.
Work is done in a feature git branch. When a designer or developer creates a
pull request for their feature branch, they move the story to the Code Review
column. Any reviewers "put their face on it" while reviewing.

Biweekly Retrospective
----------------------

Once every 2 weeks, everyone in the project meets in-person or via video
conference. This is an opportunity for the entire team to discuss achievements,
hurdles, and concerns with the goal of everyone leaving excited and empowered
for the week of work to come.

The agile buddy runs this meeting aiming to:

- Understand how the team feels about last week's progress and what's to come. Ask each team member from both sophilabs and the client, "How did you feel about last week? How do you feel coming into this week?" This is less a recap of the completed work (a better place being during daily standup) and more a pulse of how each person feels. Take notes.
- Have each member of the team voice any risks or concerns; after everyone has had the opportunity to bring these up, work together as a group to mitigate these concerns. Encourage everyone to voice the same concerns even if they've already been mentioned; it helps prioritize what the team is most concerned about and should spend the most time fixing. This is an opportunity to discuss how to improve the process and product we're building together. Note who had which concerns and track how we'll be addressing these concerns.
- Celebrate success. Review the work that shipped last week, showing the actual product, and congratulate those who made it happen.
- After the retro is done, share the notes with the team and ensure anything actionable from the retro is captured. This allows teammates to view progress, understand how feelings on the project change over time, and accomplish anything we set out to do given the outcomes of the retro.

Based on the answers to these questions, we record our plans in the task
management system:

- Archive the two-week previous sprint.
- Review product design priorities. Pull what we estimate to be an appropriate amount for this week into the Backlog.
- Review bugs. Pull any important bugs into the Backlog and prioritize them at the top of the queue before everything else. We want to always be fixing what's broken first.
- Review engineering and refactoring tasks. Pull stories into the Backlog based on what the designers and developers believe is appropriate given the previously stated product design and bug tasks.
- Re-sort the entire Backlog according to priority.

The task management system is the canonical repository for plans.
When things are only said on the phone, in person, in emails that don't include
the whole group, or in one-on-one chats, information gets lost, forgotten, or
misinterpreted. The problems expand when someone joins or leaves the project.

We've been called "aggressive" with our approach cutting features, budgets, and
schedules. It's hard to say "no." "No" is usually not well-received. There's a
reason someone requested the feature.
We have to battle sometimes in the face of "yes". We do so armed with knowledge
of `the history of software success and failure<http://blog.codinghorror.com/the-long-dismal-history-of-software-project-failure/>`_:
in 2004, only 34% of software
projects were considered successes. The good news is that was 100% better than
the stats in 1994. "The primary reason is the projects have gotten a lot
smaller."
Few software projects fail because they aren't complicated enough. Saying "no"
means keeping the software we're building as simple as possible. Every line of
code we write is an asset and a liability.

Simple software, once launched, is better suited to meeting the demands of
customers. Complex software, if it ever launches, is not as able to respond to
customer demands quickly.

Product Design
==============

Wireframes
----------

It is crucial to keep the design of the application ahead of the development.
Focus should be placed on wireframing usability, user experience, and flows.
We find it important to keep the design and development cycle adequately tight.
We do not wireframe one month out because as we approach certain areas of the
product, we often decide to cut or change features.
Those changes are an expected part of the iterative process and feedback loop
between the client, the sophilabs team, and users. It would be wasteful to
spend time wireframing features that never get built or building features that
won't be used.
The designer will refine the sketches into HTML and CSS wireframes.
HTML and CSS wireframes are built on `moqups<https://moqups.com/>`_. It also allows developers to start
implementing features within the wireframes.

User Experience
===============

User Interface
--------------

In the context of our software, the user interface is the individual views that
provide for goal completion.

We evaluate interfaces on the following criteria:

- Puts outcomes first
- Provides users with affordances
- Congruent with surrounding platform
- Consistent across entire application

We put the users goals first. No one is using our software exclusively because
of how beautiful it is. There's a reason they sought our solution out. Making
that outcome easily attainable and desirable is our highest priority.
We make software easy to comprehend. It's not enough to be functional, users
must know capabilities exist and be able to anticipate how the software is
going to react to their inputs. Our software should be as intuitive as possible.
We remain consistent with platform guidelines. Interfaces look and feel best
when in congruence with their context, rather than being strictly branded
across all platforms. We prefer common patterns when designing.
We retain consistency. Usable interfaces work as expected across the entire
application.

Interaction Design
------------------

Interaction gives users the ability to change the canvas, to directly
manipulate. Designing those interactions is what makes our software come to
life. Interactions should provide affordance — `animation<http://medium.com/p/926eb80d64e3>`_,
for examples, can
be used as a powerful metaphor for helping a user understand an interface.
Interactions help guide a user from the beginning of a task through it's
completion.

Designers guide these interactions from prototype to implementation. For web
applications we start in the browser. For review, we use gifs to demonstrate
interactions.

Visual Design
-------------

We refer to an application's visual design exclusively as its style.
We use the `universal design principles<https://thoughtbot.com/upcase/design-for-developers-resources/principles>`_
to communicate and bring order to those ideas in our applications.

Those fundamentals include, among others:

- Alignment (often achieved with grids)
- Emphasis (often achieved with size, position, color)
- Consistency (buttons, links, headers typically look alike)
- Whitespace (elegant, timeless, gives eye a rest)

Successful visual designs typically don't draw attention to themselves.
The content will be front-and-center. The workflows through the site will be
obvious. Resist the temptation to aim for a design that is "memorable" or a
design that "pops."

Successful designs are usable.

Development
===========

Our development practices are based on the `Agile Manifesto<http://agilemanifesto.org/principles.html>`_
and a subset of the `XP practices<http://www.extremeprogramming.org/>`_.
We adhere to their principles and found that
applying them improves the quality of our work and happiness of our team.

Version Control
---------------

We always use source code control. It's like a time machine. We can work in
parallel universes of our source code, experimenting without fear of losing
work. Roll back if something goes wrong.
`Git<http://git-scm.com/>`_ is an open source code control system written by
Linus Torvalds.
It's fast and great for working in branches.
We prefer to use `Gitflow<https://github.com/nvie/gitflow>`_ for branches and release management.
We use `GitLab<http://git.sophilabs.io>`_ for hosting our git repositories.

Style Guide
-----------

We write code in a consistent `style<https://guidelines.sophilabs.io>`_ that
emphasizes cleanliness and team communication.

High level guidelines:

- Be consistent.
- Don't rewrite existing code to follow this guide.
- Don't violate a guideline without a good reason.
- A reason is good when you can convince a teammate.

Pair Programming
----------------

Code that is written by two people who sit next to each other at the same
computer is `pair-programmed<http://www.extremeprogramming.org/rules/pair.html>`_ code. That code is considered high quality and
should result in cost savings due to less maintenance.
In the long run, this style of development saves money because fewer bugs are
written and therefore do not need to be fixed later.
An indication that pairing is beneficial and should be done more often is the
following example:
When you are writing an important piece of code, don't you want another person
to look it over before it goes into production?
While we don't pair program all the time, we recognize the difficulty in acting
as a team when we work at a distance from each other. There is no better
collaboration between designers and developers than at the keyboard.

Code Reviews
------------

Here's the flow. Read our `git flow based protocol<https://guidelines.sophilabs.io>`_ for the git commands.

1. Create a local feature branch based on dev.
2. When feature is complete and tests pass, stage the changes.
4. When you've staged the changes, commit them.
5. Write a good commit message.
6. Share your branch.
7. Submit a merge request.
8. Ask for a code review in `Slack<https://chat.sophilabs.io>`_.
9. A team member other than the author reviews the merge request. They follow the `Code Review guidelines<https://guidelines.sophilabs.io>`_ to avoid miscommunication.
10. They make comments and ask questions directly on lines of code in the GitLab web interface or in Slack.
11. When satisfied, they comment on the merge request "Ready to merge."
12. View a list of new commits. View changed files. Merge branch into dev.
13. Delete your remote feature branch.
14. Delete your local feature branch.

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

We can't measure productivity. But the Code Analysis squad can give a picture
about how many lines are added / deleted during a period of time by analyzing
git statistics.

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

- ▲ **estimated time / invested time**

Recruitment Squad
-----------------

Objectives
~~~~~~~~~~

-  Hire great talents with experience or potential.
-  Offer talents to Sophilabs as soon as they are required.
-  Generate an excellent reputation and culture so people will aspire to
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

Communications
==============

It is important to maintain a professional and polished tone with clients
at all times.

E-mail signature
~~~~~~~~~~~~~~~~

Please use the following HTML snippet, adapt it and paste it into the
signature field on the Gmail settings page.

`Sophilabs Signature <https://git.sophilabs.io/sophilabs/playbook/blob/master/communication/email-signature.html/>`_

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
