*********
 Spatial
*********

Definition.
    of or relating to facility in perceiving relations in space    

Papers
    * `GEO-RBAC: a spatially aware RBAC <http://dl.acm.org/citation.cfm?id=1063985>`_
    * `LRBAC: A location-aware role-based access control model <http://www.springerlink.com/index/4N6XK46321M574UH.pdf>`_
    * `Spatial role-based access control model for wireless networks <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=1285394>`_

----------------------------------------------------

**GEO-RBAC: a spatially aware RBAC**

    Inspired by a real example? Scenarios or examples.
        Hospital based examples of activating roles, allowing doctors to only see patient records while in the department of the patient
        Extended example section that discusses how a hospital setting with some typical actors would perform simple patient access
        
    What reasons and evidence do researchers claim RBAC needs extension?
        Lack of contextual information with roles, users and permissions
        Role needs a schema which allows specification of more attributes of the role

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        Shows that this model can be be represented by first-order logic and that they can be evaluated in PTIME ?

    Does this model extend the core model?
        - Introduces the concept of a spatial role
        - Extends the base model at each of the 4 levels
        - Specify mutual exclusion constraint for separation of duty
        - Split model into a model without constraints and an extensive model with constraints

    Notes.

----------------------------------------------------

**LRBAC: A location-aware role-based access control model**

    Inspired by a real example? Scenarios or examples.
        Some brief real world concepts with regards to intricate security scenarios based on location of user or object

    What reasons and evidence do researchers claim RBAC needs extension?
        - Allowing for different security scenarios based on location
        - Role activation based on location of object or user
        - Add objects to define physical or logical with location data
        - Attaches an operation to a permission

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        Describes in full definition each object and it's role in the graph
        Describes a number of specific operations that would be performed and how the model handles them with respect to locations
        Description of how the core RBAC is related to each piece of their model
        No evaluation
        Minor scenarios

    Does this model extend the core model?
        - Extension adding operation, object and role enabling based on a constraint

    Notes.

----------------------------------------------------

**Spatial role-based access control model for wireless networks**

    Inspired by a real example? Scenarios or examples.
        Provide an application scenario of where this would be needed and used

    What reasons and evidence do researchers claim RBAC needs extension?
        - standard RBAC cannot handle location based constraints and attributes

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        Mathematical specification of each aspect
        Definitions of each element in their model

    Does this model extend the core model?
        - extension at every level of RBAC
        - includes separation of duty and heiarchry concerns specifically

    Notes.
