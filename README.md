Platform-Building Cheat Sheet
=============================

First up, know what is meant by the term **'Platform'** for your organization. The following
ground rules view the platform as the server-side, back-end data and functionality, leaving
the user experience to be crafted, whether mobile, web or other, on top of that business 
functionality.

If your organization defines the 'platform' as a specific user experience or ecosystem,
your ground rules, technology stack and and building endeavor may be decidedly different
than these.

Here are the 10 Commandments or Platform Ground Rules:

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
