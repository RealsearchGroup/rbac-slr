=======================================================
 RQ2: What are the motivations behind RBAC extensions?
=======================================================

---------------
 Common Themes
---------------

* Roles, users and permissions need context associations
* Location and time constraints as well as contexts needed
* RBAC lacks ability to link in objects
* RBAC does not handle single user base and multiple organizations/applications
* Role enablement based on context
* User granting/revoking of roles based on context

-------------
 By Category
-------------

Constraint
    * No support for partial inheritance
    * Permission assignment constraints
Context
    * Relationship between object and viewer can't be represented
    * Object content matters
    * Location and time constraints on the user
    * Departmental context around access
    * RBAC does not handle many small services to wrap around them
    * RBAC lacks security principle enforcement
    * Lack of specifying context, and permission checks of dynamic evaluation time rules
    * RBAC is static and lacks ability to handle dynamic authorization and definitions
    * RBAC ignores context
    * Role granulatiry not well controlled
    * Roles should depend on the resources
    * RBAC cannot handle multiple projects with multiple tasks and differing roles in each system but the same user
    * Lack of context support
    * Too simple for dynamic environments
Delegation
    * Support cross-domain delegation
Organizational
    * Reduce administrative complexity of RBAC for multi-organizational
Privacy
    * Lack of components, purpose binding, conditions, obligations to handle privacy needs
Resource
    * Need to support multiple securtiy domains
    * Need to support same security with different applications
    * Role heirarchy adds complexity and reduces flexibility
Spatial
    * Lack of contextual information with roles, users and permissions
    * Role needs a schema to allow specification of attributes
    * Location based security scenarios
    * Role activation based on location
    * Support physical and logical locations
    * Attaching operations to permissions
Spatio/Temporal
    * RBAC doesn't inherently support location and time constraints
    * Spatial and temporal awareness of roles, inheritance and permissions
    * Context mechanisms needed
    * Physical and logical locations, hybrids
    * Role assignment based off time and space, as well as permissions
    *
Task
    * RBAC can't handle large enterprises with multiple applications and single user base
    * Security requirements for enterprises (look up these)
Temporal
    * Workflow based organizations need time base constraint for role enablement
