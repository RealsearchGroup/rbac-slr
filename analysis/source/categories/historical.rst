************
 Historical
************

Definition.
        based on or reconstructed from an event, custom, style, etc., in the past

Papers
    * `HRBAC: Historical Role-Based Access Control <http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.182.8833&rep=rep1&type=pdf>`_

----------------------------------------------------

**HRBAC: Historical Role-Based Access Control**

    Inspired by a real example? Scenarios or examples.
        - a need to incorporate information of the past to make access control decisions
        - for example, ensuring a user had a set of previous roles before being granted a higher responsibility role (e.g. "chief" role needs to have once had a manager role)

    What reasons and evidence do researchers claim RBAC needs extension?
        - in order to store and express historical entities of each base entity in order to apply constraints of current assignments and roles and permissions based off the past

    Did they implement the model?
        - No

    Is there an evaluation? If yes, how did they do one? If no, why?
        - No, only examples of mechanisms

    Does this model extend the core model?
        - Yes, extends each of the 4 levels of RBAC
        - incorporates new entities to represent historical version of each core entity
        - provides various historical constraints
        - provides algorithms for performing constraint resolution
        - highly defined model and entities

    Notes.
