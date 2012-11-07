******
 Task
******

Definition.
    a usually assigned piece of work often to be finished within a certain time

Papers
    * `A Task-Role Based Access Control Model with Multi-Constraints <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4623993>`_
    * `Team and Task Based RBAC Access Control Model <http://en.cnki.com.cn/Article_en/CJFDTOTAL-TXJS200911047.htm>`_
    * `Task–role-based access control model <http://www.sciencedirect.com/science/article/pii/S0306437902000297>`_

----------------------------------------------------

**A Task-Role Based Access Control Model with Multi-Constraints**

    Inspired by a real example? Scenarios or examples.
        Not much reasoning or evidence as to the 'why'

    What reasons and evidence do researchers claim RBAC needs extension?
        RBAC can't handle large enterprises with multiple applications and a single user base

    Did they implement the model?
        - Discussion of the applications of the model, mentions of real companies using the implementation, and a mention of a system that exists

    Is there an evaluation? If yes, how did they do one? If no, why?
        - Unclear, as their examples and applications didn't contain much data

    Does this model extend the core model?
        - rigorous constraints definitions, mathematical specification of additional model elements
        - Attempts to combine TBAC and RBAC by placing a task between a role and a permission
        - not really extending the base RBAC model 

    Notes.

----------------------------------------------------

**Team and Task Based RBAC Access Control Model**

    Inspired by a real example? Scenarios or examples.
        - Real world scenarios - hospital
        - Applications of TT-RBAC in an imaginary hospital scenario

    What reasons and evidence do researchers claim RBAC needs extension?

    Did they implement the model?
        - Prototype system

    Is there an evaluation? If yes, how did they do one? If no, why?

    Does this model extend the core model?
        - Covers all 4 levels of RBAC, provides mathematical definitions of entities
        - Extension to RBAC at all four levels
        - Introduces teams that map to users, roles and tasks
        - Introduces tasks that map to teams and permissions

    Notes.

----------------------------------------------------

**Task–role-based access control model**

    Inspired by a real example? Scenarios or examples.
        Define a set of security requirements for access control in an enterprise environment

    What reasons and evidence do researchers claim RBAC needs extension?
        8 security requirements for enterprise environments

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        - No implementation, not enough envidence other than the security requirements, the requirements are based off a few thought scenarios that seem based on a 'typical' enterprise organizational setup

    Does this model extend the core model?
        - extension by adding Task notion to connect with roles and users

    Notes.
        Task has constraints, task sits between permission and roles, tasks used to compose workflows, and are more mutable than roles - task can be used for defining set of actions and help when the specific data objects are less known at creation time
