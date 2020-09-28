HybridSharedServices
====================

The **Hybrid Shared Services** model makes use of a traditional hub & spoke
Azure vNet design by leveraging a **Shared Services** environment in Azure and
separate **Prod** & **Non-Prod** environments. Both **Prod** & **Non-Prod** can
talk **to Shared Services**, but **Prod** & **Non-Prod** are completely isolated
from one another.

![](media/d61846d23ee193871149d742b34f1ddb.jpg)

From on-prem there's separate & isolated access to each of the 3 routing
domains.

Redundancy is within region, leveraging the two separate ExpressRoute peering
locations in Sydney.

Deployment
----------
