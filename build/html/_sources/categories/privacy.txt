*********
 Privacy
*********

Definition.
    freedom from unauthorized intrusion

Papers
    * `Privacy-aware role-based access control <http://dl.acm.org/citation.cfm?id=1266848>`_

----------------------------------------------------

**Privacy-aware role-based access control**

    Inspired by a real example? Scenarios or examples.
        - inspired by conventional RBAC's inability to handle privacy
        - extra attributes are needed to support the intricacies of privacy

    What reasons and evidence do researchers claim RBAC needs extension?
        due to the lack of basic components required by privacy regulations, especially purpose binding (i.e., data collected for one purpose should not used for another purpose without user consent), conditions, and obligations.  Despite its limitations, existing access control technology can be used as a starting point for managing personal identiﬁable information

    Did they implement the model?
        No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        Evaluated the performance of assigning permissions and checking authorization for various permission size bases as well as variety in number of context variables

    Does this model extend the core model?
        - Defines additions to each level of the base RBAC model
        - Adds objects, purposes, actions, obligations and conditions to core
        - Includs context variables that can be very general, from space to time to other
        - Conflict detection and resolution mechanisms

    Notes.
