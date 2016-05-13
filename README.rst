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

Every person that joins sophilabs receives a MacBook Pro latest generation.
These laptops are known for their performance, robustness, great look & feel
and battery life, but for us, the most important feature is that they allow us
building and testing apps on any platform: OSX, Linux and Windows.

Text Editor/IDE
---------------

    *Plain text won't become obsolete. It helps leverage your work and simplifies debugging and testing. The editor should be an extension of your hand; make sure your editor is configurable, extensible, and programmable.*
    - The Pragmatic Programmer

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

We could be called "aggressive" with our approach cutting features, budgets, and
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

Test-Driven Development
-----------------------

`Test-Driven Development<http://www.extremeprogramming.org/rules/testfirst.html>`_
(TDD) is one of the most important Extreme Programming
(XP) rules, but we need to be very careful how to apply it as it may add an
important amount of code that could make us move slower.
One of the great benefits of TDD is that it enforces the design of testable
components, it is a great practice to create clean and maintainable code, and
we have some suggestions to encourage the creation components
interfaces tests and not for implementation details:

- Don’t test private methods.
- Test the more generalist method that is closer to the user instead of each one responsible for the smaller tasks.

Acceptance Tests
----------------

Acceptance tests are code created from stories’ acceptance criteria. This code
is run against the application. When executed for the first time, the test will
fail. The developer writes application code until the test passes.
When the test passes, the developer commits the code into version control with
a message such as:

*Author creates post*

The code is then run on the Continuous Integration server to make sure the
acceptance test still passes in an environment that matches the production
environment.
Everytime the code is pushed to the dev branch, the staging environment is
automatically updated so anyone can see the current status of the project.

When the acceptance test is green for the CI server and you and any other
designers, developers, or clients are satisfied that the jobs story is complete
on staging, the feature can be deployed to production at will. This can result
in features being pushed to production very frequently, and therefore more
value is being delivered to customers sooner.

Continuous Delivery
-------------------

Martin Fowler has an `extensive description<http://martinfowler.com/articles/continuousIntegration.html>`_
of Continuous Integration. The basics are:

- We have a test suite that each developer runs on their own machine.
- When they commit their code to a shared version control repository, the tests are run again, "integrated" with code from other developers.

This helps ensure there's nothing specific to the developer's machine making
the tests pass. The code in version control needs to run cleanly in production
later so before the code is allowed to be deployed to production, it is run on
a CI server or service.
When a build fails, we get alerts in Slack and via email. Click the alert and
we see a backtrace that gives us a hint of how to "fix the build."
When we write the fix and commit to version control again, we'll get a "passing
build" alert in Slack and via email. Click the alert and we see the passing
build.

*Green is good.*

A solid test suite is an absolute requirement for a web application in our
opinion. However, one major problem with test suites is that they get slow as
they get large.
CI can ease the pain by distributing the test runs in parallel.
We've used Bamboo, Hudson (now called Jenkins), and other CI libraries that we
manage ourselves.
We use `Travis CI<https://travis-ci.org/>`_ for open source projects. We use
`Jenkins<http://ci.sophilabs.com>`_ for private repositories.
CI test runs are triggered by GitLab post-receive hooks.

Deployment
==========

We focus on the client's product as much as possible and outsource operations
as much as possible to external services. This saves time and money.

Checklist
---------

- We have found that a short checklist is valuable when setting up a new production environment or preparing for a launch:
- Are we using a concurrent web server? See how to set up Nginx.
- Are long-running processes such as email delivery being run in background jobs? See how to set up delayed Job.
- Are there redundant (at least two) web and background processes running?
- Are we using SSL? See "SSL Certificates" section below.
- Are API requests being made via a separate subdomain (api.example.com)? Even if the same app, this gives us architectural flexibility in the future.
- Are deploys done manually at a scheduled time when teammates are fresh and available if something goes wrong?
- Do deploys follow a well-documented script?
- Are we sending logs to a remote logging service? See How to integrate Sentry.
- Are we using a AWS RDS service? See AWS production databases.
- Are we monitoring performance and uptime? See `New Relic<https://newrelic.com/>`_.

Domain Names
------------

We suggest to use `Domize<https://domize.com/>`_ to see what's available.
Use `DNSimple<https://dnsimple.com/>`_ to buy and
maintain domain names If the client doesn’t have a domain registered yet.

SSL Certificates
----------------

Buy a `wildcard certificate from DNSimple<https://dnsimple.com/ssl-certificate>`_.
The wildcard (*) lets you use the
same certificate on www., staging., api., and any other future subdomains.
SSL and DNS are tightly coupled. If we're doing any work with SSL, we need
to make sure we have access to make DNS changes, like adding a CNAME record.
If we're working with a client who has a department that handles DNS, schedule
time during off-peak hours to pair program with the DNS person to make sure
everything goes well. We can accidentally take down a site that is all SSL if
this work isn't done methodically.

Hosting
-------

We use `Amazon Web Services<https://aws.amazon.com/>`_.
The cloud and the services it enables will empower our clients' businesses to start and operate in a manner that has never been possible before without significant upfront investment.
If we offer file uploads for features like user avatars, we upload them to
`Amazon S3<https://aws.amazon.com/s3/>`_.

Transactional Email
-------------------

We use `Amazon SES<https://aws.amazon.com/ses/>`_ and `SparkPost<https://www.sparkpost.com/>`_
(supports templates) to have our application
deliver email to users, known as transactional email.

Examples of transactional email are:

- Confirmations
- Follow ups after the first 3 days of use
- Free trial is expiring
- Message another user in the system

Payment Processing
------------------

For collecting payments from users via credit or debit card, we use `Stripe<https://stripe.com/>`_.
It is a payment gateway and merchant account. We also use it for recurring
billing.
Charges for Stripe will vary depending on usage.
Successful charges are 2.9% + 30 cents. There are no setup fees, monthly fees,
or card storage fees.

Monitoring
==========

We use `New Relic<https://newrelic.com/>`_ to monitor performance of production
applications.
Debugging performance might be the best part of a developer's job.
There's a clear, numeric problem. When we fix it, that number improves.
We can say things like "We made this 175% better."

There's many established techniques for fixing performance problems.

- Amazon server clusters
- gzipping
- Asset pipeline
- SQL query caching
- ORM queries improvements

A number of them require developer thought:

- Database indexing
- Eager loading
- HTTP caching

Page caching is the heaviest handed technique we have, but if we can cache an
entire page and push it into a CDN, that will be the fastest option.

Communications
==============

Everyone who works at sophilabs has a responsibility to engage professionally
with clients.
As a developer or designer, we undoubtedly are involved in emails, phone calls,
or chats with clients. In these interactions, we always demonstrate respect and
professionalism.

E-mails
-------

All emails are archived and not deleted, so that a paper trail exists on any
internal conversation or client facing communications.

Also for the purpose of maintaining a paper trail, we ensure that a record of
all sophilabs emails remain in the google apps sophilabs site. This means
that if we forward emails or use an email client, all emails are recorded in
google apps as well.

We use an appropriate `email signature<https://git.sophilabs.io/sophilabs/playbook/blob/master/communication/email-signature.html>`_
to maintain a professional tone with clients at all times.

Protecting confidential information via email is also extremely important for
us. As such, we do not send passwords by email, and we are very careful in
sending confidential documents by email as well. All email can be easily
intercepted by third parties. No confidential information should ever be sent
to someone who is not “need to know”.

Slack
-----

We are logged in Slack during work hours. This decreases feedback loops for
team communication. Our slack account is under sophilabs.slack.com.

Data Security
-------------

We have some security guidelines to keep confidential information safe.

- We set passwords on computer for boot up and sleep
- We never send passwords using email
- We create safe passwords
- We do not leave our laptop, computer, phone, or papers lying around unprotected
- We limit access to sophilabs networks and communication channels, email and phones

Sales
=====

We're designers and developers. We want to design and develop software.
Before we can do that, we need clients to hire us. The following section
details how our sales process works and answers commonly asked questions by
potential clients.

The overall process is:

- Someone contacts us.
- We have a skype call.
- Qualify/disqualify: are we a good fit for the client?
- Qualify/disqualify: is the client a good fit for us?
- Understand the client's vision.
- Agree to the outcomes we're trying to achieve.
- Estimate iterations.
- Schedule people for iterations.
- Sign the contract.
- Pay a security deposit
- We start working.

Leads
-----

Our leads often come from referrals from clients and Google searches.
We track each lead on `sophia<https://panel.sophilabs.io>`_.

A salesperson will get assigned to the card for the incoming lead but anyone
in the sales team can take responsibility for that lead. The person responsible
qualifies or disqualifies the lead, often with a quick intro email or skype
call with the potential client.
We prefer to pair on sales calls, having at least one designer and one
developer on the call. This enables us to get multiple opinions on how good or
bad of a fit the client and project might be for us, it gives us the ability
to answer both design and development questions to the best of our ability,
and it allows us to train and improve our process during sales calls.

Understanding Product Vision
----------------------------

Our goal is to begin thinking about the client's product and working as a team
to plan it even before we officially start working together. Some example
questions to ask:

- What big benefit does the product provide?
- Who currently buys this product?
- Who do you want to buy this product?
- What do customers love about your product?

We distribute the sales process throughout the team. Potential clients should
be able to talk to the people they'll work with. We should be able to handle
spikes in incoming leads that make it unreasonable for the sales team to
respond in a timely fashion.

Customer Availability
---------------------

Tools like Slack, Gitlab, and Jira have made remote work much easier over the
years, and we work remotely every day with our customers.
An ideal consulting project for us is one where a member of the client team is
available every time. Failing that, we want to find out during the sales
process how available they will be.
If it seems like they won't be available very often, we should seriously
consider declining the project.

NDAs
----

If the NDA is important to the client, ask them to tell us enough about the
business to evaluate whether there's a conflict with our existing or past
clients. If we determine there's no conflict, the project is a good fit, we
sign it.

Roles
-----

Technical team
~~~~~~~~~~~~~~

We offer some combination of designers, Python developers, and Javascript
developers. An agile buddy assists the team for a few hours a week.
The designer is responsible for designing interactions between users and the
product. They write user interface code.
The developers make it work. They write the code that makes the app "smart."
They aim to make the product error-free. They monitor performance because speed
is a feature of every application.
Developers keep it running. They make architectural decisions and interact with
modern-day hosting companies.
The developers also implement. They write and maintain HTML, SASS, Javascript,
Python, SQL, and lots of other code. They set and meet development standards,
keep the `Continuous Integration<http://www.extremeprogramming.org/rules/integrateoften.html>`_ build passing, and review each other's code.
The agile buddy adds an impartial perspective. They run weekly meetings so that
there is consistency in week-to-week communication. They keep an eye on the
high-level goals of the project, which should be easier for them because they
are not in the weeds of the project day-to-day. They express enthusiasm when
the team is in a groove and help problem-solve when things get off track.
When appropriate, they should work with the client to either reduce or increase
team size to correctly serve the project.

Agile buddy
~~~~~~~~~~~

The agile buddy is not a project manager. The rest of the team does not report
to them. The agile buddy is also not a technical or design lead. Agile buddies
need not be Managing Directors or CXOs, but typically are due to flexibility
in schedule. Anyone at sophilabs should be able to advise a project. If the
primary salesperson is not also the agile buddy, there should be a smooth
hand-off from one to the other.

While each person plays a role, a team needs to be a team.
Everyone takes responsibility every day for delivering high quality work,
for staying true to the vision for the product, for communicating their
schedule and intentions, for making hard decisions, for delegating to others
when they don't have the time or skill to accomplish a task, for keeping
team morale up, and for being consistent.

No Fixed Bids
-------------

Some consulting relationships start with a requirements document. The
requirements are often extremely detailed.
The probability of this document containing the optimum feature set is
extremely low. The right features are better learned through user interviews,
prototyping, releasing actual software, and getting feedback from real users.
Based on that document, clients expect consultants in the industry to submit
an exact timeframe and bid. This contract style sets the client and consultant
working against each other right from day one. Instead of focusing on designing
the product experience or evaluating what assumptions were wrong, they spend
time negotiating about what was meant in a document written a long time ago or
focusing on arbitrary deadlines. But it's worse than negotiating; it's
retroactively discussing something that no one remembers the same way.
As you might have guessed, we don't do fixed-bid, fixed-feature-set proposals.

Budget
------

We `do need to know clients' budget<https://medium.com/what-i-learned-today/a61ec864c898>`_.
This is often uncomfortable for them but
their budget helps determines what scope is possible. It saves time. If they
don't know their budget, we discuss different options.
We talk about breaking product rollout into stages and try to improve the
product's chances of success at each stage by:

- Focusing on a small subset of features.
- Designing a valuable user experience.
- Developing a meaningful relationship with users.

Rate
----

We price projects at a per person, per hour rate. We consult a minimum of 32
hours per week. We use the same rate for designers and developers. The work
required for each week dictates which skills are needed. The number of people
needed determines the cost and how much gets done.
During the process of explaining our billing, we sometimes tell potential
clients "time and materials" is the same as hiring an employee for their annual
time except there's less risk to them because:

- Our team is experienced. We've interviewed hundreds candidates in order to find the talented group of people we work with today.
- We've worked together on projects before. We have "a way" of doing things.
- Short projects require less money.
- Our time is predictable (32 hours/week) and consistent.
- We can quickly rotate in a new team member if someone gets sick, leaves the company, or is ready to rotate to a new project.

Clients always know what is happening via access to the project management
system (JIRA), chat room (Slack), version control system (Gitlab), and ongoing
communication with our teammates.

Contract
--------

We store contracts in Google Drive and have a series of folders for pending,
current, past, and lost clients.

The consulting proposal and contract contains:

- A one-page summary of the expected work.
- Our hourly rate.
- Security deposit covering two weeks of work is required to start working.
- Invoices will go out once a month.
- Agreement that both parties won't use materials which break someone else's copyright.
- Agreement that both parties won't publish things to the web hosting provider which are abusive or unethical.
- Agreement that the contract is mutually "at-will" and either side can decide to stop work with a prior notice of 15 days.

Hiring
======

Recruitment
-----------

We've met our future teammates via:

- `GitHub<http://github.com/>`_
- `Python<http://www.meetup.com/py-mvd/>`_ and `Javascript<http://www.meetup.com/mvd-js/>`_ Meetups
- `Python<http://uy.pycon.org>`_ and `Javascript<http://jsconf.uy>`_ Conferences
- `Buscojobs<http://www.buscojobs.com.uy/>`_

Many of us are regulars at Python and Javascript events.
A nice thing about those meetings are that they happen naturally.
We know what we'll get when we hire in the above ways. We know their
personality and energy level from the user group. We know their coding style
from their open source work. We know they'll take initiative because they
voluntarily contributed to the community.

Interviewing
------------

We create a new record on Sophia for each candidate.
The recruitment team ensures that everyone gets a response and make sure
that one of the directors speak with a candidate before is hired.
Anyone can do an initial review of the candidate's application. In particular,
they review the candidate's code sample or portfolio. If necessary, they may
ask someone else (like a designer or Javascript developer) for another pair of
eyes on the code or portfolio.
The recruitment team will pull the managing director, designers, or developers
into subsequent discussions, putting their faces on the Sophia candidate to
ensure we always know who is responsible.

We have standard questions for Python developers, NodeJS developers, DevOps
and designers for the technical interview. We like to talk to respondents about
design process, architecting systems, and writing code; the same thing we do
for work every day.
Aside from technical skill, during the entire interview process, we look for
`character strengths<http://www.kipp.org/our-approach/strengths-and-behaviors>`_ like:

- Enthusiasm (invigorates others)
- Focus (pays attention, resists distractions, remembers directions)
- Composure (remains calm when critiqued, doesn't interrupt)
- Gratitude (shows appreciation)
- Curiosity (eager to explore, asks questions to understand, actively listens)
- Optimism (gets over frustrations quickly)
- Grit (finishes what he or she starts, doesn't get blocked)
- Emotional intelligence (demonstrates respect for others' feelings, knows when and how to include others)
- Appreciation of beauty (notices and appreciates beauty and excellence)

To be hired, the candidate must get a unanimous "yes" from the existing
teammates with whom they interacted.

Offer and Onboarding
--------------------

We make the offer via mail, if it is accepted then a contract is signed by
both parties and a trial work period of three months is agreed. Both parties
are going to use that period to evaluate each other. A feedback meeting is
going to be scheduled between the new team member, his mentor and the agile
buddy 10 weeks after the hiring.

When the offer is accepted, we create the teammate's email address, gives them
access to systems like GitLab and Slack, sends them their Employment Agreement,
notifies Accounting, sends a welcome email to the teammate, receives a welcome
package including a MacBook Pro, stickers, a printed version of this playbook
and a t-shirt; and creates JIRA issues for the hiring manager for any remaining
items that we haven't been able to complete.

Mentors
-------

We assign a mentor to new team members who acts as a guide on their first
three months. The mentor helps them set up their machine, purchase any required
software, and walk them through one turn of the development cycle by getting
their profile added to our website. The mentor also makes them feel comfortable,
answers questions they may have, or points them to the person who can answer
them.

Compensation
------------

We are entirely bootstrapped, with no outside investors, and no debt.
Sustainability of the company is very important to us. We want to bring great
people on at reasonable salaries and reward them as aggressively as possible
for actual performance.
We may never be able to compete dollar for dollar with other tech companies but
we can compete on being a great place to work, with lots of opportunities to
learn, and the freedom to define and execute on our own projects.

Biannual Reviews
----------------

In order to continually improve ourselves and the company, all year round on
every project we're on, we receive regular feedback from clients, managers,
and teammates. We additionally have biannual reviews for more formal review
and potential salary increases.
During onboarding, a "Biannual Review" calendar event is created, set to recur
once every 6 months, starting from the hire date.

The agenda for biannual reviews is roughly:

- Our performance on recent consulting projects
- Our investment days contributions
- Our satisfaction with our work, projects, and the company
- Our questions about sophilabs and our strategy
- Our areas of focus for the next 6 months

Salary increases are the natural result of improvement. Our manager may
increase our salary during biannual reviews in a way that is compatible with
the company's finances and individually appropriate to us based on things
we've done, such as:

- creating great software
- making users and clients happy
- improving ourselves by learning something new
- improving sophilabs by bringing in sales, mentoring a teammate, contributing to an internal tool or research
- improving our community by writing blog posts, contributing to sophilabs open source projects, or attending conferences
- doing the things we didn't think to put on this list

It's important that our manager explains why a raise is being given and what,
if anything, could be done to receive a higher raise next time. We don't get
raises for "just showing up."

Operations
==========

Running a software-based business requires more than beautiful code or a
popular product. Managing cash flow and taxes can feel unimportant or difficult
but getting them right is as vital to our success as product design.

Fortunately, we have decided long time ago to build our own ERP system which
make things like bookkeeping, receipts, signatures, and invoicing much easier,
it is a minimal core system connected with multiple third party services such
as Redmine, Jira, Quickbooks to extract desired information. It’s name is
Sophia and it is living on `panel.sophilabs.io<https://panel.sophilabs.io>`_.

Email
-----

We use `Gmail<https://mail.sophilabs.io>`_ for our email.

Calendar
--------

We use `Google Calendar<https://calendar.sophilabs.io>`_ for our calendars.

Documents
---------

We use `Google Docs<https://docs.sophilabs.io/>`_ for our editable documents.
We prefer Google Docs because they are:

- Easily sharable by URL. Everyone has a browser, not everyone has MS-Office or OpenOffice installed.
- Always up to date with the latest edits.
- Enable real-time collaboration, like group meeting notes.
- Autosaved to the cloud, so no worrying about backup.
- Are as easy to find as Googling something.
- Without document type versioning (e.g. xls vs. xlsx).

These tools are not well-suited for large documents or complicated spreadsheets,
which is great.
We write code and are biased toward minimal documentation and upfront specs so
we shouldn't be writing long documents.
For cases where we are writing large spreadsheets, we find it's faster to snap
together a small app to do the job. This is a good time to ask if such
complicated analysis is really necessary.
When documents are mostly similar with slight variations (like contracts),
we create templates and put them in the Templates folder of our Docs repository.

Meetings
--------

We over-communicate with clients online to avoid having scheduled meetings.
Every problem arises from poor communication.
When we need to meet for a discussion, we aim for 30 minutes.
When working remotely, `Google Hangouts<https://apps.google.com/intx/en/products/hangouts/>`_
is the prefered communication tool,
if not possible `Skype<http://skype.com>`_ works too. They are easy to set up, sharable by URL,
and let us get a look at whoever we're talking to.
Screen-sharing is also very easy, when necessary. We have used Hangouts/Skype
for client meetings, candidate interviews, and company meetings.

Community
=========

We've learned a ton from blog posts, tweets, and newsletters from others in the
community. We should be giving back when we have something to share.

Blog
----

We have an institutional blog called `Journal<https://sophilabs.co/journal>`_,
for sharing important events
and facts related to sophilabs in addition to product design and software
engineering topics.
When you want to write a post, create an Issue on JIRA in the `Community
project<https://sophilabs.atlassian.net/projects/COM/issues/?filter=allopenissues>`_
and assign the Issue to yourself.

Spend time writing and rewriting a `great headline<http://www.copyblogger.com/magnetic-headlines/>`_.
It helps you narrow your
focus, figure out the purpose of the post, and grab people's attention in the
first place.
When you begin writing, move the Issue to the "Drafts" column.
Write the post in `Sophia<https://panel.sophilabs.io>`_, add tags to the post. Tags help our readers find
related blog posts.
When you're ready for feedback from the team, move the issue to "In Review"
column and share the Issue URL with the team in Slack. Make changes based on
their feedback and your judgement.
When the post is ready to publish, give it a published date and change it
status to published.
Our RSS feed, Zapier, Buffer accounts are setup to automatically work together
to link to the post from Twitter, Google+ and LinkedIn.
Link to the post from Hacker News, Reddit or other appropriate sites.
Move the Issue to "Live."

Research
========

Ongoing experiments are managed in our "Research & Innovation" JIRA project.

We rigorously research, discuss, and conclude experiments on new tools and
techniques. Write up these experiments on the blog at your discretion.

Open Source
-----------

We've created a few open source libraries to help us perform common tasks and
give back to the community.
Our open source libraries do better when there's one person that really steps
up to maintain them. Each of our repositories has a leader that tries to keep
the repository moving forward. The leader doesn't necessarily do the bulk of
the actual work; responsibilities include:

- Understand the underlying code and goal of the library
- Review and merge pull requests
- Respond to and close issues
- Push new releases of packages when appropriate
- Encourage people to take on useful tasks for the library
- Blog, tweet, and otherwise advertise new releases and tips

Every sophilaber has commit access to our open source repositories.
Some guidelines:

- You may want to check with the project leader to see what would be most useful, or whether or not they're on board with your idea.
- Send pull requests rather than committing straight to master.
- Try helping out with existing pull requests or bug reports.
- Documentation patches are a great way to get familiar with a project.

Got an idea for a new library? Found something useful in a client project that
you think is reusable? Great! Some guidelines:

- Extractions are more likely to be useful than Brave New World ideas, because you're extracting something that has already proven useful once.
- If you create a new library, you're expected to lead it, at least for the beginning of its life. Make sure you have time to maintain it.
- Try not to duplicate something that's already been done well. Look around to make sure your problem hasn't already been solved.
- Fixing bugs that affect client projects or introducing small features that would really help a client project is fine during client time. Most open source work should be conducted during investment time. Let the client know if you are willing to add the new open source project as a requirement to the client’s project.
- Think about whether your idea makes more sense as a pull request to an existing project.

Squads
======

We realized that we needed to divide our forces in order to build a
great company.

One of our core principles is *always aim high*, and to be consequent we
developed demanding objectives:

* Hire the best people
* Work for the best companies
* Craft the best software
* Build something that people love

We have created specialized workgroups that strive to achieve those goals by
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
  languages being used in sophilabs. Examples include: guidelines, linting
  rules, workflows, conventions, etc. These documents won’t only refer to code,
  but also to how to ensure code quality (e.g. code reviews).
- Develop a plan or methodology to measure the effectiveness of the generated
  knowledge.
- Develop or improve tools that automate and control the quality of the code
  (linters, conventions, etc). This tools and documents must be Open Source.
- Adjust guidelines, workflows and other procedures to the needs of each project.

Methodologies Squad
-------------------

Objectives
~~~~~~~~~~

Ensure that the software development processes used on different
projects encourage the following principles:

- Adaptability: The team's ability to quickly adapt to unexpected changes.
- Productivity: The output rate of the team is above the average.
- Visibility: The team is traceable and all documents and resources are accessible. The team proactively documents and informs to put everyone in the same page.
- Satisfaction: Team, client and stake holders are happy.
- Integration: Team and client are involved in the project.
- Automation: All the repetitive processes and tasks that add overhead are automated.
- Simplicity: Doing only what is needed every time.
- Predictability: Estimated tasks were completed on time.

Recruitment Squad
-----------------

Objectives
~~~~~~~~~~

-  Hire great talents with experience or potential.
-  Offer talents to sophilabs as soon as they are required.
-  Generate an excellent reputation and culture so people will aspire to
   work at sophilabs.

Scope
~~~~~

-  This group will be responsible for the hiring process and the three
   months trial period.
-  Attend to inquiries from the Sales and Operations offices.
-  Ask for tasks to the Meeting and Operation offices.

Testing Squad
-------------

Objectives
~~~~~~~~~~

Encourage that software built by sophilabs has the necessary
mechanisms to boost the following principles in an execution
environment:

- Reliability: The application should behave as expected.
- Robustness: The application should be able to continue operating despite abnormalities.
- Correctness: The application is compliant with the requirements specification.

Goodbye
=======

We are a group of people who enjoy crafting software for next-generation products.
We hope the practices we've shared here will be helpful to you.
Thank you for reading.

License
=======

The original idea comes from `Thoughtbot's playbook
<https://playbook.thoughtbot.com>`_, we took the great work they did and adapted
it to our philosophy.

.. image:: https://licensebuttons.net/l/by-nc/3.0/88x31.png
   :target: ./LICENSE.rst

Creative Commons Attribution-NonCommercial
