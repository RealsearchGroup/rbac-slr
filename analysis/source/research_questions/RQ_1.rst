=======================================================
 RQ1: What are the deficiencies in current RBAC model?
=======================================================

---------------
 Common Themes
---------------

*

-------------
 By Category
-------------

Constraint
    * no support for partial inheritance
    * inability to support permission assignment constraints
Context
    * Missing ability to apply constraints between role and permissions and enforce
    * Missing context that defines if a role can be activated at execution time
    * Role activation on a per object or process execution rather than session based
    * No allowance for context to check permission at execution moment based on context
    * activation of roles based on current context rather than session intiation
    * conflict resolution
    * RBAC cannot handle dynamic authorization and entities
    * Role cannot be resource dependent
    * RBAC is too simple
    * Missing granularity
    * Inability to handle dynamic nature of multiple projects with multiple resources
    * Too simple
    * Lacks context
    * Handling authorization between applications and within can be different
Organizational
    * RBAC cannot handle cross-organizational roles and access in an administratively easy way
Privacy
    * Privacy regulations are complex, with many entities, RBAC lacks ability to handle all of these
    * Context, conflict detection and resolution
    * RBAC lacks ability to define purpose
Resource
    * No support for multiple security domains
    * No support for same security, different applications
    * Lack of flexibility
Spatial
    * Lack of contextual information
    * Role needs a defined schema
    * Role activation based on context
    * Giving a permission an operation
Spatio/Temporal
    *
Task
    * Needs an entity to represent a task and connect a role and a permission through it
    * Need for team and tasks
    * Need for entity between permission and roles to hold constraint and allow for dynamic situations and entities
Temporal
    * RBAC can't handle time based constraints for role enablement
