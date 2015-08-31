Platform-Building Cheat Sheet
=============================

First off, we need to understand what is meant by the term **'platform'** for the organization.
In todays world, the term 'platform' is such an overused buzzword that it is largely meaningless.
Platforms exist at many levels in the technology stack: hardware, datacenter, database,
messaging, etc. and can also be used to describe ecosystems of user experiences.

The view presented here is decidedly business focused: the 'platform' is really the method
of exposing and growing the digital business model and its offerings. So, the following ground rules
define the platform as the digital server-side, back-end data and functionality, leaving the user
experiences to be crafted (whether mobile, web or other) on top of that business functionality.

This API-centric definition of 'platform' enables rapid user experience revision, more consistent user
experience across devices, better channel adaptation, faster and cheaper third-party integrations,
and increased innovation capabilities.

Platform Ground Rules
---------------------

0. **Mobile** is a first-class citizen and consumer of the platform.
0. All platform services will expose their data and functionality via a complete set of **RESTful APIs**. 
0. Developers will be able to access all APIs using a **single developer key**.
0. All service interfaces and events will be designed from the ground up to be **public facing**.
0. There is a **single token source** and format for all APIs.
0. The platform will notify interested observers of all resource state changes via **fully-composed events**.
0. All APIs use a **single identity** to represent the consumer / user.
0. All new APIs have a **consistent look and feel**, and are documented at a single, publicly-available location.
0. No private interfaces. **No backdoors**. No shared databases across teams (Observe 'Bounded Contexts').
0. A distributed system (multi-node, multi-zone, and multi-region) requires a discipline towards **resilience**.
