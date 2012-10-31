==============
 Introduction
==============

Role-based access control (RBAC) models :cite:`ferraiolo:rbac` become popularly used to govern access to critical resources.  In an RBAC model, roles represent a group of users who are involved in a specific job function in an organization. RBAC assigns permissions of specific actions on resources to roles instead of individual users.  Therefore, in order to gain roles' permission on specific resources, users acquire appropriate roles first.

RBAC is a generalized access control approach used for various applications including web services, database applications, and healthcare applications.  RBAC has advantages in maintaining and managing organization's security policies.  For example, if a user is to access manager role's resources within a given organization, security policy administrators simply add the user to be associated with the manager role.

RBAC is first introduced in 1990s, NIST proposed standard RBAC model :cite:`ferraiolo:rbac`
Standard RBAC model considers only role-user association and role hierarchy.
Since standard RBAC model has limitations such as specifying environmental constraints or context information 
Researchers developed extended models of RBAC to overcome the limitations.
However, as researchers often develop their own specialized extended models of RBAC,
their research cannot be generalized or compared with other research work appropriately.
As a result, researchers could take time on reinventing the wheel.    
But how do we, as a community, ensure that a metric is suitable and acceptable for its intended purpose? 

The goal of this work is to synthesize available research results on extended models of RBAC. We analyze their extended features and claimed research contributions to find limitations of current RBAC models and what extent of extended features by
comparing with similar research work. 
We conducted a systematic literature review (SLR) to evaluate and interpret all available research relevant to a particular research question or topic area of interest.

Our research give benefits to a community as follows:
    * Our work summarizes current extended RBAC research work and its contributions. By synthesizing the current results, our work shows a roadmap of current extended RBAC research.	
    * Our work guides a direction for a standard of extended RBAC. Understanding the categorization and the motivation of the existing research results helps decide a standard of extended RBAC.  
    * Our work shows a criteria in comparison among research results.
    * Our work helps identify the research challenges in the ares of security policies and suggest a future extension of RBAC.

------------
 Categories
------------

* Constraint (1)
* Context (8)
* Delegation (1)
* Organizational (1)
* Privacy (1)
* Resource (1)
* Spatial (3)
* Spatio/Temporal (6)
* Task (3)
* Temporal (1)

.. image:: _static/categories_map.png
   :height: 400px
   :width:  600px
   :scale:  100%
   :align: center

.. bibliography:: references.bib
