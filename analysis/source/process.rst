=========================
 Methodology and Process
=========================

For the first phase of our systematic literature review, an automated comprehensive search of multiple academic search engines was performed. The list of search engines is:

* Google Scholar - http://scholar.google.com
* IEEExplore - http://ieeexplore.ieee.org
* ACM Portal - http://dl.acm.org

For each of the criteria below, a search was performed on each of the search engines for a total of 9 data sets.  The criteria used were:

* role based access control
* RBAC
* role-based access control

The search performed was done in an automated way using a set of scripts to query and collect data from each search engine.  For each criteria for each search engine, the results were captured until a stopping criteria was met.  For a given run was done as follows:

1. Remote call to search engine with current search start position and the current search criteria.
2. Parse results and extract paper title, authors and year of publication.
3. Compare results against stopping criteria.
 * If stopping criteria met, stop search.
 * If stopping criteria not met, increase search position by number of results and return to step 1.

The stopping criteria used was either after the first 1000 results, a limitation imposed by some of the search engines, or if ten consecutive results did not contain any of the search criteria words within the title.  After gathering all 9 data sets, the data was combined into a master list by systematically comparing the bibliographic information for each.  After producing a master list a series of assessment rounds were performed to narrow the paper list and identify primary sources.  

There were a total of three elimination rounds.  The first round was based solely on title, the second on reading of the abstract and the last round was based on a full read of the paper and comparison to the research questions outlined.  Each round was performed as follows:

* Each reviewer independently classified papers as relevant, irrelevant or uncertain.  
* Those papers marked as relevant by both reviewers were kept and those marked irrelevant by both were thrown out.  
* Papers marked as relevant, or irrelevant by a single reviewer were combined with all papers marked as uncertain and discussed by both reviewers.  From this discussion, papers were either thrown out or kept until the next round of the review.

The results of the searches was as follows:

============== ==== ========================= =========================
Search Engines RBAC role based access control role-based access control
============== ==== ========================= =========================
Google Scholar 261  581                       391 
ACM Portal     321  281                       261
IEEExplore     171  221                       201
============== ==== ========================= =========================
    

--------------------
 Research Questions
--------------------

We have following research questions.
    * RQ1. What are the deficiencies in current RBAC model to propose extended RBAC models?
    * RQ2. What are the motivations behind RBAC extensions? 
    * RQ3. What are the categorizations of RBAC model proposed?
    * RQ4. For each categorization, what are the extended features of RBAC model proposed?
    * RQ5. Do these models have corresponding implementations in practice?
    * RQ6. How are extended RBAC models evaluated in theory and in practice?
    * RQ7. Are there any commonalties or generalizations across all categorizations?
    * RQ8. What domains or scenarios serve as inspiration for these extensions?

For RQ1-RQ3, we compare of proposed extended models.
For RQ4, we compare quality of completeness of the proposed models.
Beyond modeling of extended RBAC models, an prototype shows that their models work in practice and improves the quality
of the completeness of research papers. For RQ5, we compare criteria for evaluation of extended RBAC models.
