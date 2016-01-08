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

Metrics
=======

Metrics are going to be measured taking one month of work. These are the
metrics designed by the squad, classified by principle.

Reliability
-----------

-  # lines of code tested / # lines of code
-  # unit tests asserts / # lines of code
-  # integration tests asserts / # lines of code
-  # validation tests asserts / # lines of code
-  1 / (# tickets tagged with “reliability issue” on a testing session +
   1)

Robustness
----------

-  1 / (# server side uncatched exceptions + 1)
-  1 / (# tickets tagged with “testing robustness” created on code
   review sessions + 1)
-  1 / (# tickets tagged with “robustness issue” on a testing session +
   1)

Correctness
-----------

-  # acceptance tests asserts / acceptance criteria conditions
-  1 / (# tickets tagged with “correctness issue” on a testing session +
   1)

