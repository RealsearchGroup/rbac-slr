*********
 Context
*********

Definition.
    circumstances in which an event occurs

Papers
    * `A flexible content and context-based access control model for multimedia medical image database systems <http://dl.acm.org/citation.cfm?id=1232473>`_
    * `A Context-Aware Role-Based Access Control Model for Web Services <http://ieeexplore.ieee.org/xpl/login.jsp?tp=&arnumber=1552897&url=http%3A%2F%2Fieeexplore.ieee.org%2Fxpls%2Fabs_all.jsp%3Farnumber%3D1552897>`_
    * `A context-sensitive access control model and prototype implementation <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.102.9126&rep=rep1&type=pdf>`_
    * `A Context, Rule and Role-Based Access Control Model In Enterprise Pervasive Computing Environment <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4079196>`_
    * `A contextual role-based access control authorization model for electronic patient record <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=1229859>`_
    * `A Role and Context Based Access Control Model with UML <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4709140>`_
    * `Designing an agent-based RBAC system for dynamic security policy <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=1376833>`_
    * `An extended RBAC model based on granular logic <http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=4664701>`_
    * `Leveraging Access Control Mechanism of Android Smartphone Using Context-Related Role-Based Access Control Model <http://ieeexplore.ieee.org.prox.lib.ncsu.edu/xpl/articleDetails.jsp?tp=&arnumber=5967517&contentType=Conference+Publications&searchField%3DSearch_All%26queryText%3Dleveraging+access+control+mechanism+of+android+smartphone+using+context-related+role-based+access+control+model>`_
    * `CRBAC: Imposing multi-grained constraints on the RBAC model in the multi-application environment <http://www.sciencedirect.com.prox.lib.ncsu.edu/science/article/pii/S1084804508000520>`_


----------------------------------------------------

**A flexible content and context-based access control model for multimedia medical image database systems**

    Inspired by a real example? Scenarios or examples.  
        Real world inspiration based upon medical image database.  One simple scenario shown where the model is applicable.

    What reasons and evidence do researchers claim RBAC needs extension?
        - What the image is of is important to who can view
        - Domain governs who can see a particular image (e.g. departments in a hospital)
        - Location for determining if user is accessing from secure location or location of importance (e.g. emergency room)
        - Time constraints for validity periods
        - Relationship between images and viewer

    Did they implement the model?
        Provided system architecture for entire medical imaging database with access control system. No implied implementation of model.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No evaluation.  Present proposed situation and hospital structure with scenario where new model would be applicable. No reason for lack of evaluation given.

    Does this model extend the core model?
        - Proposes adding of constraints between the Role-Permission relationship which must be satisfied in order for the holder of said role to be able to use those permissions
    This appears to be an active mechanism during enforcement not assignment
        - Adds user attributes (e.g. company position, location, user name)
        - Adds a decision rule to role-permission relationship
        - Role-perm relationship contains 5 attributes: identifier, subject/role, action, target objects, constraints

    Notes.

----------------------------------------------------

**Context-sensitive access control model and prototype implementation**

    Inspired by a real example? Scenarios or examples.
        Initiates the paper with case scenario "handle an insurance claim" workflow.

    What reasons and evidence do researchers claim RBAC needs extension?
        - points out contrasts between base RBAC and improvements clearly
        - claims that RBAC supports security principles but does not enforce the use of

    Did they implement the model?  
        Prototype created using VB6 and MS Access97.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No.

    Does this model extend the core model?
        - largely using mechanisms prescribed by RBAC specifically SoD and LP see note about how RBAC provides for but not the use of the previous security practices
        - roles are activated whenever a tasks is chosen to be performed and checked if the user can have said role
        - provides more implementation of SoD and LP than additions to model

    Notes.
        - context oriented, provides what appears to be a different spin or implementation of heirarchies

----------------------------------------------------

**A Context, Rule and Role-Based Access Control Model In Enterprise Pervasive Computing Environment**

    Inspired by a real example? Scenarios or examples.
        - Inspired by the needs of access control in pervasive computing environments

    What reasons and evidence do researchers claim RBAC needs extension?
        - "static method of management user-role-permissions"

    Did they implement the model?  
        - Created prototype system to verify model correctness and system architecture
        - Implemented the algorithms proposed by their model
        - Simulated scenarios but the details of the simulations are not in the paper, nor are the results in a consumable manner

    Is there an evaluation? If yes, how did they do one? If no, why?
        No.

    Does this model extend the core model?
        - Claim to be an extension and follow the standard RBAC execution model except by adding two different checks where permissions are re-evaluated by the context of the current user according to the already specific rules
        - context aware rules that dynamically determine permissions
        - constraining the permissions based on a users location
        - assignment/removal of a role based on context information
        - connection of roles, granting a user certain role permissions when another user/role is present
        - Provide mechanism to deal with conflicts

    Notes.

----------------------------------------------------

**A contextual role-based access control authorization model for electronic patient record**

    Inspired by a real example? Scenarios or examples.
        - Traditional RBAC does not support emergency overrides based on the situation
        - Inspired by the needs of an EHR application in practice

    What reasons and evidence do researchers claim RBAC needs extension?
        Claim RBAC is static and cannot handle the dynamic authorization and definitions needed by EHR application complexity

    Did they implement the model?
        - Implemented using Java and LDAP on InCor EHR system
        - They quote number of users and rules, but provide no evidence of comparison or any observation data of the system in use

    Is there an evaluation? If yes, how did they do one? If no, why?
        Showed some discussion evidence for the requirement for these extensions to RBAC, and they implemented it, however, they provided little evidence as to the effectiveness

    Does this model extend the core model?
        - Claim to be a context based extension
        - Focused on the authorization aspect of permissions for a given role
        - Contains both positive and negative permission authorizations
        - Provides for overriding of authorizations based on inheritance

    Notes.

----------------------------------------------------

**A Role and Context Based Access Control Model with UML**

    Inspired by a real example? Scenarios or examples.
        - Describes a scenario whereby a supermarket could not effectively use RBAC to encapsulate all the various access scenarios they need
        - Propose a model that adds attributes and system context

    What reasons and evidence do researchers claim RBAC needs extension?
        - RBAC ignores context
        - RBAC is too simple and unilateral and does not align with real world
        - Role granularity is not well controlled
        - Roles should depend on the resources not vice-versa
        - Roles should e assigned to one resource instead of resources being assigned to one role

    Did they implement the model?
        - Prototype system created using XML container to contain roles and conditionals

    Is there an evaluation? If yes, how did they do one? If no, why?
        - No evidence as to the comparison of the model in terms of the need over traditional RBAC other than conjecture around a scenario
        - The performance test is really only valid for their implementation and shows no grounded re-worldness
        - performed a performance analysis of traditional RBAC and C-RBAC based off their prototype

    Does this model extend the core model?
        Extension of the traditional model adding context and maps roles to context and contex to resources with authorization and verification mixed in

    Notes.

----------------------------------------------------

**Designing an agent-based RBAC system for dynamic security policy**

    Inspired by a real example? Scenarios or examples.
        - users and application sbecoming larger
        - many applications have dynamic attributes and defining scenarios for all of them is difficult

    What reasons and evidence do researchers claim RBAC needs extension?
        - For their project manage system, traditional RBAC cannot handle the dynamic nature of multiple projects with multiple tasks that different users may be managing in one and not in another

    Did they implement the model?
        Talks about some weird web based API for the agent

    Is there an evaluation? If yes, how did they do one? If no, why?
        Discuss a fake project management system claiming this type of system is the target for this type of access control

    Does this model extend the core model?
        Defines model clearly
        Extension that defines an Abstract Role, Context Rules and Context Information and the actual role is decided upon based off the context inputs and the rules

    Notes.

----------------------------------------------------

**An extended RBAC model based on granular logic**

    Inspired by a real example? Scenarios or examples.
        Inspired by a muli-level user environment with a complicated authorization management - power load forecasting system

    What reasons and evidence do researchers claim RBAC needs extension?
        - traditional RBAC does not provide context
        - RBAC is too simple for large dyanmic environments

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No evidence, applied in theory to a conceptual situation, no comparison

    Does this model extend the core model?
        Additions to specification, and rules around whether a user is authorized to perform an action based on their role and the context within the role

    Notes.

----------------------------------------------------

**Leveraging Access Control Mechanism of Android Smartphone Using Context-Related Role-Based Access Control Model**

    Inspired by a real example? Scenarios or examples.
        - Access control needs of smart phones
        - Installation of third party applications that a user needs to trust
        - User must grant device privileges to the application
        - Parents want to limit the amount of time kids use phone
        - User might can to limit accessbility to friends and admins
        - Companies want to limit data access by employee phones
        - User loses company phone in admin mode, context to prevent leakage

    What reasons and evidence do researchers claim RBAC needs extension?
        - smartphone is centralized, user-centric system where identities are known in advance
        - smartphone has lots of contextual info
        - 

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No.

    Does this model extend the core model?
        - Adds objects, environmental context, policies and decisions to model
        - Object is an accessible entity
        - a property of the system at the moment of interaction
        - policy is the formal specification of the access control

    Notes.
        - precedential order of access privileges to prvent policy bugs


----------------------------------------------------

**CRBAC: Imposing multi-grained constraints on the RBAC model in the multi-application environment**

    Inspired by a real example? Scenarios or examples.
        - proliferation of distributed applications
        - example of limited disk space when a database read and update are performed to resolve which operation to give preference to

    What reasons and evidence do researchers claim RBAC needs extension?
        - need flexible and dynamic authorization constraints
        - authorization differs between and within applications
        - Users may be granted access to the application and entities or may be granted access to objects with the application depending on context
        - role and permission constraints are also possible

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        - analysis of example scenario, comparison of constraint vs other models, 

    Does this model extend the core model?
        - adds object sets, entities, status and set of authorization attributes
        - permissions on objects with constraints
        - user and user constraints mapped to roles with permission attribute constraints

    Notes.
        - classification of constraints as either users eligibility to to use a resource/service or constraints on the users actual use of a resource (limiting what they can do)
