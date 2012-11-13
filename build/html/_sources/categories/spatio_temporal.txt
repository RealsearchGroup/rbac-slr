*****************
 Spatio-Temporal
*****************

Definition.
    combining space and time

Papers
    * `STARBAC: Spatiotemporal role based access control <http://www.springerlink.com/index/tq15n88122v63754.pdf>`_
    * `On spatio-temporal constraints and inheritance in role-based access control <http://dl.acm.org/citation.cfm?id=1368341>`_
    * `A framework for specification and verification of generalized spatio-temporal role based access control model <https://www.cerias.purdue.edu/tools_and_resources/bibtex_archive/archive/2007-08.pdf>`_
    * `LoT-RBAC: A Location and Time-Based RBAC Model <http://www.springerlink.com/index/77j0j540004585wv.pdf>`_
    * `A spatio-temporal role-based access control model <http://www.springerlink.com/index/C3T50338535HX115.pdf>`_
    * `Role Based Access Control with Spatiotemporal Context for Mobile Applications <http://www.springerlink.com/index/r1n6j114g5431174.pdf>`_

----------------------------------------------------

**STARBAC: Spatiotemporal role based access control**

    Inspired by a real example? Scenarios or examples.
        Similar reasoning as other location based models, No formal evaluation, scenarios or real world examples.

    What reasons and evidence do researchers claim RBAC needs extension?
        Extension of RBAC and of SRBAC by combining spatial and temporal

    Did they implement the model?

    Is there an evaluation? If yes, how did they do one? If no, why?
        Mathematical explanations, definitions
        Includes descriptions and math behind the semantics

    Does this model extend the core model?

    Notes.

----------------------------------------------------

**On spatio-temporal constraints and inheritance in role-based access control**

    Inspired by a real example? Scenarios or examples.
        Believe that previous models focus on syntax and not semantics

    What reasons and evidence do researchers claim RBAC needs extension?
        - pervasive computing environments requirement for spatial and temporal awareness
        - previous spatio-temporal do nt address interaction between these constraints and inheritance
        - makes 4 claims about how existing models do not handle the above
        - trusted entities to override restrictions
        - attempt to show compatibility with standard model and claim others do not

    Did they implement the model?

    Is there an evaluation? If yes, how did they do one? If no, why?
        - Examine previous models and point out deficiencies, use of graphs to show off relationships
        - Evaluation includes a mathematical examination of the role graphs, and ordering
        - authors note that there is added complexity in their method, but that is the price to pay to get user  and user-role application constraints
        - trade-off between complexity of policies and complexity of constraints
        - authors do comparisons of complexity for the various models
        - authors note that SoD should be considered in the future

    Does this model extend the core model?
        Additions to the specification for constraints with a specific look at how to do spatial and temporal

    Notes.

----------------------------------------------------

**A framework for specification and verification of generalized spatio-temporal role based access control model**

    Inspired by a real example? Scenarios or examples.
        Based off hospital example with mobile devices inspiring combining location and time based models
        Provides an example hospital access control policy that requires space and time - based on the layout of the floor of a hospital and the various users and entitie sthat might exist such as nurse, doctor and surgeons

    What reasons and evidence do researchers claim RBAC needs extension?
        Need to be able to handle add attributes that location and spatial specification requires
        Add context mechanisms

    Did they implement the model?
        No

    Is there an evaluation? If yes, how did they do one? If no, why?
        To some degree, an example, and some analysis of developing policy and how to deal with conflicts

    Does this model extend the core model?
        Builds on GTRBAC, extends at all 4 levels
        Adds role activation/deactivation
        Provides conflict resolution
        Includes a GSTRBAC policy specification model using Alloy

    Notes.

----------------------------------------------------

**LoT-RBAC: A Location and Time-Based RBAC Model**

    Inspired by a real example? Scenarios or examples.
        Inspired by growing needs of mobile, peer-to-peer devices with regards to activating and specifying permissions and roles based on time and location
        Detailed scenario of a person having a medical emergency, and a doctor on site needing to request patient data, as well as the progression through the ambulance, to hospital and citing such location based clues to help know if the doctor should be granted privileges such as being in or near his own car

    What reasons and evidence do researchers claim RBAC needs extension?
        Previous location and time based RBAC models did not incorporate location for both the user and role
        In-depth, detailed location heirarchies and specifications are needed
        Physical, logical, and hybrid location

    Did they implement the model?
        No

    Is there an evaluation? If yes, how did they do one? If no, why?
        No

    Does this model extend the core model?

    Notes.

----------------------------------------------------

**A Spatio-temporal Role-Based Access Control Model**

    Inspired by a real example? Scenarios or examples.
        Growth of wireless networks, mobile devices, the move towards pervasive computing

    What reasons and evidence do researchers claim RBAC needs extension?
        Claim that previously examined models of spatial, temporal, or spatio-temporal lack needed aspects
        Role assignment should be dependent on space and time
        Permissions need to be dependent on space and time not just roles

    Did they implement the model?
        No. Authors acknowledge need to implement.

    Is there an evaluation? If yes, how did they do one? If no, why?
        No.  Best they do is provide a detailed scenario with an examination of how such a scenario would be represented in their model. Author acknowledge detailed analysis is needed.

    Does this model extend the core model?
        Defines for Space - physical location, logical location and mapping functions and relationship definitions
        Defines for Time - time instant, time interval
        Adds objects to Core model, object can be physical or logical (computer or files e.g.)
        Defines a number of potential role hierarchy strategies
        Examines impact on both static and dynamic separation of duties for new attributes and mechanisms

    Notes.

----------------------------------------------------

**Role Based Access Control with Spatiotemporal Context for Mobile Applications**

    Inspired by a real example? Scenarios or examples.
        Need and desire to put spatio-temporal context and constraint on roles and permissions - such as students at a university or hospital facilities

    What reasons and evidence do researchers claim RBAC needs extension?
        Needs enhancements to be able to handle space and time attributes on roles and permissions

    Did they implement the model?
        Yes.  Integrated an access control system into iMedik - a telemedicine application in India that is web-based and allows mobile access
        Their implementation is a bolt-on solution, that intercepts calls and verifies their authorization
        Provide detailed architecture and implementation details

    Is there an evaluation? If yes, how did they do one? If no, why?
        Include section that discusses differences between their model and STRBAC and STARBAC
        Incorporate algorithms for determining whether a particular authorization is granted and use time-complexity arguments to discuss the effectiveness of each algorithm and to attempt to display that the added complexity of their model over traditional RBAC does not impace performance significantly

    Does this model extend the core model?
        Extends at all 4 levels
        Adds "extents" which are design to extend the base entities such as a role, multiple RoleExtents can belong to a single role based off constraint or context

    Notes.
