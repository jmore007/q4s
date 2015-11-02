# q4s
Quality for Service Protocol (Q4S) provides a mechanism for latency, jitter and bandwidth negotiation and monitoring, alerting whenever one of the negotiated conditions is violated.

This is an implementation of a modified version of The Quality for Service Protocol draft (https://tools.ietf.org/html/draft-aranda-dispatch-q4s-03)

In order to avoid the use of plugins to use UDP, this implementation will use TCP to perform measures, so no packet loss will not be available.

...
