# monitoring-project

This project is an effort to build a better monitoring tool.

There are lots of bright engineers at Hangops Ru community, and we believe that together we can build a suitable solution.

Proposed feature set:

* Written for the 21-st century: with containers, configuraiton management and autodiscovery in mind
* Fault tolerant: multiple servers must co-exist, check each other and send alerts at least once for failed service (in split-brain scenario, alerts may be duplicated)
* Push-based approach: collectors send events to servers
* Relays: monitoring servers as dumb retranslators
* Ability to handle large streams of events
* Support of elastic server groups (e.g. alert, when 5% servers are down)
* Support of service groups
* Flexible and hierarchical configuration on server and agent side
* Stateless or signal-processing approach to alerting, with minimum history
* Forwarding to other tools, like Bosun for historical or anomaly analysis
