# Discussions
## Connection Setup
- When we think of connection setup rejection, should this be handled in the routing process? Especially, the router and repeater assumed to have sufficient number of resource. 
  - If there is a system error during the process, connection setup rejection could be useful

- What information the connection setup reject contains?
  - Estimated next availble time?

- When the connection setup request goes to different networks, QCap information for subnet is also delivered?
  - I guess not but how do we get QCap of subnet? Statiscal approach?

## Connection Teardown
- Do repeaters have to wait for RuleSet termination from both sides?