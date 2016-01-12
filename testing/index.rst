Playbook for Testing
--------------------

Table of Contents
=================

1. `Objectives <#objectives>`__
2. `Metrics <#metrics>`__

Objectives
==========

Encourage that the software built by sophilabs has the necessary
mechanisms to boost the following principles in an execution
environment.

Reliability
-----------

The application should behave as expected.

Robustness
----------

The application should be able to continue operating despite
abnormalities.

Correctness
-----------

The application is compliant with the requirements specification.

Glossary of terms
=================

TBD

Metrics
=======

These are the metrics designed by the squad, classified by principle.
Metrics marked with ▲ increase, the ones marked with ▼ decrease.

Main metric
-----------

Each principle needs to be represented by a summarized value, to do so a primary
metric is defined and identified by a ℗

Reliability
-----------

-  **▲ # lines of code tested / # lines of code ℗**
-  ▲ # unit tests asserts / # lines of code
-  ▲ # integration tests asserts / # lines of code
-  ▲ # validation tests asserts / # lines of code
-  ▼ # tickets tagged with “reliability issue” on a testing session

Robustness
----------

-  **▼ # server side uncatched exceptions ℗**
-  ▼ # tickets tagged with “testing robustness” created on code
   review sessions
-  ▼ # tickets tagged with “robustness issue” on a testing session

Correctness
-----------

-  **▲ # acceptance tests asserts / acceptance criteria conditions ℗**
-  ▼ # tickets tagged with “correctness issue” on a testing session
