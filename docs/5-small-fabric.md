# Build a Small Data Center Fabric

The customer is buying new Ethernet fabric infrastructure for their data center. They collected existing connectivity requirements and got these numbers:

* 32 servers with 2 x 25GE ports;
* 40 1GE copper ports used mostly by servers but also for storage and appliance management ports;
* iSCSI-based storage (total of 8 x 10GE ports)
* 4 network appliances (firewalls, load balancers…) with 2 10GE ports each;
* 2 WAN routers with 1 Gbps uplinks and 10GE connection to the fabric.

Design an Ethernet fabric that will be:

* As cost-effective as possible while meeting current connectivity requirements;
* Easy to extend as the connectivity needs grow. They plan to increase the number of servers to 50 in the next three years, and they expect the servers to have 2 x 25GE ports plus 1GE management port;
* Require minimum downtime during the expansions.

You can use data center switching equipment from any vendor you prefer.

Your design should also include a migration plan for unexpected fast-growth scenarios, for example, connecting up to 200 servers.

## Need Help?

You might find these webinars and blog posts helpful:

* [Build Enterprise Data Centers with Two Switches](https://my.ipspace.net/bin/list?id=BCloud#2SWITCHES)
* [Building a Small Data Center Fabric with Four Switches](https://blog.ipspace.net/2021/09/4-switch-fabric.html)
* [Using EVPN in Very Small Data Center Fabrics](https://blog.ipspace.net/2018/02/using-evpn-in-very-small-data-center.html)
* [Do We Need Leaf-and-Spine Fabrics?](https://blog.ipspace.net/2018/09/do-we-need-leaf-and-spine-fabrics.html)
