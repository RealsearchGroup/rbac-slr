************
 Delegation
************

Definition.
    the act of empowering to act for another

Papers
    * `Capability-based delegation model in RBAC <http://dl.acm.org/citation.cfm?id=1809861>`_

----------------------------------------------------

**Capability-based delegation model in RBAC**

    Inspired by a real example? Scenarios or examples.
        - inspired by large-scale and cross domain networks as seen potentially by electronic health record systems
        - two "case studies" that are really just two scenario thought experiments that the authors apply their model to

    What reasons and evidence do researchers claim RBAC needs extension?
        - need to support cross-domain delegation in large-scale networked systems

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No.

    Does this model extend the core model?
        - this appears to be taking elements present in RBAC and giving them a special name in certain circumstances
        - tries to capture the ability to apply a role for a limited time which sounds more like context
        - adds constraints
        - their version of a capability appears to do nothing more than encompass constraints, context and temporary roles that a user can delegate to another
        - is this really an extension or just a complex description of an action?

    Notes.
