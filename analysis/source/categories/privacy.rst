*********
 Privacy
*********

Definition.
    freedom from unauthorized intrusion

Papers
    * `Privacy-aware role-based access control <http://dl.acm.org/citation.cfm?id=1266848>`_
    * `PuRBAC: Purpose-Aware Role-Based Access Control <http://www.sis.pitt.edu/~amirreza/papers/masoumzadeh2008_purbac.pdf>`_

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

----------------------------------------------------

**PuRBAC: Purpose-Aware Role-Based Access Control**

    Inspired by a real example? Scenarios or examples.
        - Web and companies with privacy policies make it harder to follow said policies and protect user data

    What reasons and evidence do researchers claim RBAC needs extension?
        - privacy policies include purposes under which collected data can be used
        - current RBAC model does not include a entity or relationships to incorporate purpose
        - authorization requests should include a purpose for performing the intended action

    Did they implement the model?
        - No.

    Is there an evaluation? If yes, how did they do one? If no, why?
        - No evaluation, conclusion includes note that further analysis needs to be done
        - Discusses entities added by this model, the way they were added and why this method is the best way to add purpose and support privacy

    Does this model extend the core model?
        - extends the base and heirarchy portion of the model, adds in a hybrid heirarchy
        - connects purposes to permissions

    Notes.
        - claim to reduce policy complexity by associating a purpose with only a permission and not with roles and users as well
        - locks down the users ability to declare purpose, by putting authorization controls around the purposes
