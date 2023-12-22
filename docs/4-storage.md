# Design a Storage Solution

You’re designing a greenfield data center. Most workloads will be virtualized; the database servers might be virtualized or running on bare metal. The storage administrators expect these types of storage requirements:

* VM virtual disks (not critical, could be restored from daily backup);
* Databases (mission-critical, must be replicated);
* Tape-based backup (accessible via Fibre Channel only).

Select the optimal:

* Storage solution (or a mix of solutions);
* SAN transport technology (FC, FCoE, or Ethernet);
* Storage access protocol (FC, iSCSI, NFS, SMB, or something else).

Design a SAN access network or a unified leaf-and-spine networking infrastructure based on your selection.

## Need Help?

These webinars will help you complete the assignment:

* [Data Center 3.0](https://my.ipspace.net/bin/list?id=DC30) (the storage sections)
* [Build the private cloud infrastructure](https://my.ipspace.net/bin/list?id=BCloud) (storage and networking sections)
* [Hyper-Converged Infrastructure Deep Dive](https://my.ipspace.net/bin/list?id=HCI)
* [VMware Networking Deep Dive](https://my.ipspace.net/bin/list?id=vSphere6) (VMkernel adapters)

You might find these blog posts useful:

* [Is Fibre Channel Still a Thing?](https://blog.ipspace.net/2022/05/fibre-channel-2022.html)
* [Why I’ve lost interest in hyperconverged](http://chucksblog.typepad.com/chucks_blog/2016/08/why-ive-lost-interest-in-hyperconverged.html) (Chuck Hollis in his Oracle days)
* [Storage networking is different](http://blog.ipspace.net/2010/08/storage-networking-is-different.html)
* [Does dedicated iSCSI infrastructure make sense?](http://blog.ipspace.net/2013/03/does-dedicated-iscsi-infrastructure.html)
* [iSCSI or FCoE?](http://blog.ipspace.net/2014/02/iscsi-or-fcoe-flogging-obsolete-dead.html)
