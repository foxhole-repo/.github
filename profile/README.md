We are currently actively working on a custom TCP / HTTP-based transport layer designed to make protocol behavior closer to regular application traffic.
The goal is to improve connection stability in restricted networks where simple censorship systems block or degrade known VPN protocols.
Planned work:
* Design a custom TCP / HTTP-based transport layer
* Make protocol behavior closer to regular application traffic
* Add adaptive transport behavior for unstable or filtered networks
* Use local ML / heuristic logic to evaluate network conditions
* Dynamically select the transport mode based on network signals
* Perform all classification and decision-making locally on the device
* Do not use telemetry, external scoring services, or centralized traffic analysis
* Build reproducible tests against simulated censorship and poor network conditions.

## Disclaimer

> Android application development is not our primary focus.
> Our core focus is in backend systems, security, machine learning, and cryptography.
