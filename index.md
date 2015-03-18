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

### <a name="sub"></a>rel="sub"

When included in a resource representation of an event, the "sub" (subscription) link relation MAY identify a target resource that represents the ability to subscribe to the pub/sub  event-type resource in the link context. 

### <a name="unsub"></a>rel="unsub"

When included in a resource representation of an event, the "unsub" (subscription cancellation) link relation MAY identify a target resource that represents the ability to un-subscribe from the pub/sub event-type resource in the link context. 


### <a name="events"></a>rel="events"

Link to a collection resource representing a list of subscribe-able events.


---

Contents of this page are intended for standardization and are released 
under [CC0 1.0 Universal (CC0 1.0)](https://creativecommons.org/publicdomain/zero/1.0/)
license by Irakli Nadareishvili. 2015.

<br/>
<br/>

