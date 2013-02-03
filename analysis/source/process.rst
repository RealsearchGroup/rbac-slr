============================
 2. Methodology and Process
============================

For the first phase of our systematic literature review, an automated comprehensive search of multiple academic search engines was performed. The list of search engines were:

* Google Scholar - http://scholar.google.com
* IEEExplore     - http://ieeexplore.ieee.org
* ACM Portal     - http://dl.acm.org
* CiteSeerX      - http://http://citeseerx.ist.psu.edu/index

For each of the criteria below, a search was performed on each of the search engines for a total of 12 data sets.  The criteria used were:

* role based access control
* RBAC
* role-based access control

The search performed was done in an automated way using a set of scripts to query and collect data from each search engine with the criteria string as input.  For each criteria for each search engine, the results were captured until a stopping criteria was met.  Each run was performed as follows:

1. Remote call to search engine with current search start position and the current search criteria.
2. Parse results and extract paper title, authors and year of publication.
3. Compare results against stopping criteria.
 * If stopping criteria met, stop search.
 * If stopping criteria not met, increase search position by number of results and return to step 1.

The stopping criteria used was either after the first 1000 results, a limitation imposed by some of the search engines, or if ten consecutive results did not contain the search criteria phrase within the title.  After gathering all 12 data sets, the data was combined into a master list by systematically comparing the bibliographic information for each.  After producing a master list, a series of assessment rounds were performed to narrow the paper list and identify primary sources.  

There were a total of three elimination rounds.  The first round was based solely on title, the second on reading of the abstract and the last round was based on a full read of the paper and comparison to the research questions outlined.  Each round was performed as follows:

* Each reviewer independently classified papers as relevant, irrelevant or uncertain.  
* Those papers marked as relevant by both reviewers were kept and those marked irrelevant by both were thrown out.  
* Papers marked as relevant, or irrelevant by a single reviewer were combined with all papers marked as uncertain and discussed by both reviewers.  From this discussion, papers were either thrown out or kept until the next round of the review.  Ties were broken by an indepedent party.

The results of the searches is summarised below:

============== ==== ========================= ========================= ========
Search Engines RBAC role based access control role-based access control  Total
============== ==== ========================= ========================= ========
Google Scholar 651  213                       435                       1299
ACM Portal     500  20                        720                       1240
IEEExplore     200  40                        230                       470
CiteSeerX      100  100                       150                       350
-------------- ---- ------------------------- ------------------------- --------
-------------- ---- ------------------------- ------------------------- --------
Totals         1451 373                       1535                      3359
-------------- ---- ------------------------- ------------------------- --------
Combined                                                                **1716**
============== ==== ========================= ========================= ========
    

--------------------
 Research Questions
--------------------

Based on our intial intent for the systematic literature review, and notes taken during the third phase of elimination, we have identified the following research questions:

  * RQ1. What are the deficiencies in current RBAC model to propose extended RBAC models?
  * RQ2. What are the motivations behind RBAC extensions? 
  * RQ3. What are the categorizations of RBAC model proposed?
  * RQ4. For each categorization, what are the extended features of RBAC model proposed?
  * RQ5. Do these models have corresponding implementations in practice?
  * RQ6. How are extended RBAC models evaluated in theory and in practice?
  * RQ7. Are there any commonalties or generalizations across all categorizations?
  * RQ8. What domains or scenarios serve as inspiration for these extensions?
