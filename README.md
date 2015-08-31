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

This API-centric definition of 'platform' enables:

* Rapid user experience revision
* Consistent user experience across devices
* Better channel adaptation
* Faster and cheaper third-party integrations
* Increased innovation capabilities.

Platform Ground Rules
---------------------

0. **Mobile** applications are a first-class citizen and consumer of the platform.
	* Making mobile a priority increases ease of use and adoption for everyone.
0. The platform exposes its data and functionality via a complete set of **RESTful APIs**. 
	* An API-based strategy maximizes reuse and flexibility.
0. Developers access all APIs using a **single developer key**.
	* Simplifies security and access to all capabilities.
0. All service interfaces and events are designed from the ground up to be **public facing**.
	* Causes design for ease of use, flexibility and reuse.
0. There is a **single token source** and format for all APIs.
	* Assists in ease of use and ensures all functionality is available to consumers.
0. The platform will notify interested observers of all resource state changes via **fully-composed events**.
	* Enables synchronization asynchronously (for all create, update, delete state changes).
0. All APIs use a **single identity** to represent the consumer / user.
	* Enables analytics and reasoning about consumers.
0. All APIs have a **consistent look and feel**, and are documented at a single, publicly-available location.
	* Maximizes reuse and ease of use.
0. No private interfaces. **No backdoors**. No shared databases across teams (Observe 'Bounded Contexts').
	* Ensures the public interfaces are sound.
0. APIs are deployed in a **distributed, always-on** architecture (multi-node, multi-zone, and multi-region) with a discipline towards resilience.
	* Horizontal scale on commodity hardware, global reach. Account for the inevitable failures.
