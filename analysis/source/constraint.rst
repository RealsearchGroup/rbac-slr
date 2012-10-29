************
 Constraint
************

Definition
    a limitation or restriction

Papers
    * `A constraint based role based access control in the SECTET a model-driven approach <http://dl.acm.org/citation.cfm?id=1501451>`_

-----------------------------------------------------------

**A constraint based role based access control in the SECTET a model-driven approach**

    Inspired by a real example?
        SECTECT is a framework that provides workflow for Service oriented Architectures and is the primary target.

    Scenarios or examples.
        Presented generic scenarios from the medical domain as examples to describe how mechanisms worked.

    What reasons and evidence do researchers claim RBAC needs extension?
        * The claim is that with respect to Service Oriented Architecture, and the execution of web services, RBAC lacks needed features.
        * RBAC does not support partial inheritance
        * "total inheritance of permissions in RBAC is against the principle of least privilege"
        * ability for some sub-role permissions not be available to super role
        * "permission assignment constraints"

    Did they implement the model?
        No evidence of use in a real system.

    Is there an evaluation? If yes, how did they do one? If not, why?
        No.

    Does this model extend the core model?
        * Presents a modification to a core aspect of RBAC
        * Allow partial inheritance at the permission level by a superrole instead of treating the role as an atomic entity

    Notes.
        Apply a restricted status to a permission which prevents a superrole from inheriting that permission
