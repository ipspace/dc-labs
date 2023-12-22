# Extend a Leaf-and-Spine Fabric

The customer is building a new data center and wants to extend the existing fabric in the current data center to the new data center. The data centers are 10 kilometers[^M] apart and will be linked with two 100GE links (the customer is buying lambdas from a metro SP and trying to push as much as possible on a single lambda).

[^M]: Or miles if you don't believe in the metric system.

The existing fabric is a reasonably large leaf-and-spine fabric with four spine nodes using 100GE leaf-to-spine links and 25GE server-facing ports. The fabric in the new data center will be smaller – initially, it will have two spine nodes, potentially expanding to four spine nodes as the data center workload grows.

The customer asked you to design the data center interconnect that should use the minimum amount of links (because they don’t own the fiber) and ideally require no additional equipment.

When designing the solution, evaluate all potential failure scenarios. The amount of traffic between data centers will be significant, so you must ensure that link or node failures don’t result in overloaded leaf-to-spine links within the data center fabrics.
