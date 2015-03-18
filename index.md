---
layout: home
title: Linke Relations
---

# Link Relations


## 1. Supporting: Saga Workflows

Link Relations for Long-Lived Compensating Transactions (Sagas)

@See:

- <http://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf>
- <http://www.enterpriseintegrationpatterns.com/RoutingTable.html>
- <http://vasters.com/clemensv/2012/09/01/Sagas.aspx>

### <a name="routing-slip"></a>rel="routing-slip"

Link to a resource representing 
a [Routing Slip](http://www.enterpriseintegrationpatterns.com/RoutingTable.html) 
coordinating a 
[Long-Lived Compensating Transaction](http://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf)

### <a name="compensatingtx"></a>rel="compensatingtx"

Link to a resource representing information about a compensating transaction for
 each member transaction a
[Long-Lived Compensating Transaction](http://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf)

<br/>
<br/>

## 2. Supporting: Event-Driven Workflows 

Link Relations for an Even-Driven (E.g. Pubsubhubbub) Hypermedia Workflow

@See:

- <http://en.wikipedia.org/wiki/PubSubHubbub>
- [Registered `hub` relation](http://www.iana.org/assignments/link-relations/link-relations.xhtml)

### <a name="sub">rel="sub"

Link to a resource allowing subscription to an event in the context

### <a name="unsub">rel="unsub"

Link to a resource allowing subscription cancellation for an event in the context

### <a name="events">rel="events"

Link to a collection resource representing a list of subscribe-able events.
