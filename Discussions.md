# Discussions

## Terminologies
- "Initiator" or "the initiator" or ...? (same as responder) -> Yes
## Connection Setup
- When we think of connection setup rejection, should this be handled in the routing process? Especially, the router and repeater assumed to have sufficient number of resource. 
  - If there is a system error during the process, connection setup rejection could be useful
  - When there are multiple bottleneck, it could be a problem

- What information the connection setup reject contains?
  - Estimated next availble time?

- When the connection setup request goes to different networks, QCap information for subnet is also delivered?
  - I guess not but how do we get QCap of subnet? Statiscal approach?

- Do repeaters have to wait for message arrival from initiator and responder to send LAU?

- What does the LAU look like?
  - Does LAU changes the way to allocate resources as well?
    - e.g. Fair resource allocation to prioritized resource allocation etc.

- Do repeaters know the requirements for the application?
  - If yes, it might be possible to optimize link allocation policy

- Does repeater have to provide estimated fidelity after the purification?
## Connection Teardown
- Do repeaters have to wait for RuleSet termination from both sides?



### Things have to decide
The first RuleSet to be allocated the resource