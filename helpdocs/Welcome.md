# VNTribe

## Note: VNTribe is under development and is not production-ready

VNTribe - is a service for your business to create and manage network-based flat company model without personal links, to allow smooth insert of software/AI tools inside all the steps and processes.

## Key terms

* service - function/operation/service you, other people and microservice deliver to other people, you or microservices
* bot - application/microservice application (external service or server/container with application) which supports one or many services/functions/operaions
* request - message created to operation owners (people or microservices) with request to do this service/function/operation and with needed for it information

## Key concepts

Every user or bot this is Node in the network
<img src="/w1.png" alt="Users"
title="Users" width="60%" />

Nodes join to groups. Inside group nodes have full connectivity:
<img src="/w2.png" alt="Groups"
title="Groups" width="60%" />

When two groups should be connected - one Node becames to be a member of two groups. All the
communications between two groups go via this Node. This Node is Communicator now:
<img src="/w3.png" alt="Connector"
title="Connector" width="60%" />

You can see organization structure in "VNT map", you will see list of groups and nodes
plus connections map:
<img src="/w3.1.png" alt="VNTmap1"
title="VNTmap1" width="16%" /><img src="/w3.2.png" alt="VNTmap2"
title="VNTmap2" width="43%" />

Every node can start announcing service which this node can provide to other nodes (node this is people or bot). Communicators (nodes which are members of 2 or more groups) allow or block services announcement distribution between groups. If node is receiving service announce - service became to be visible in the "Services" list for this node:
<img src="/w4.png" alt="Service"
title="Service" width="60%" />

If user does mouse click to service from the "Services" list, new request form will be open. On the top of request user will see path of this request to destination service. In most cases it will be Connectors. Every Connector should allow this request on it's way to service owner. Request goes backwards to service owner follows path of service announce:
<img src="/w5.png" alt="Service"
title="Service" width="60%" />

To manage VNT several pre-defined services created supported by adm bots: manage users, manage groups, manage services, manage bots:
<img src="/w6.png" alt="Service"
title="Service" width="30%" />

User can see requests, see status of own requests, approve or reject through requests in the "Requests" part:
<img src="/w7.png" alt="Service"
title="Service" width="60%" />
