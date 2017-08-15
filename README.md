# backupberg
Repurposed Hitachi SAN components as custom backup solution

After decommissioning some gear, we still had about 250x Seagate 3TB SAS hard drives, and the accompanying enclosures. 
The enclosures were once badged as Xyratex, BlueArc, Hitachi. 
The real manufacturer is probably an anonymous company in China, but rumor is that Seagate provided the engineering.
IBM / Lenovo also sells a very similar looking enclosure as part of their current DSS solution.
We stopped paying warranty coverage on the actual Hitachi technology. (which converted SAS to Fiber channel RAID LUNs, and converted Fiber Channel raw commands up to easy-to-use NFS / CIFS over 10G ethernet).
But the actual drive carriages and cabinets speak raw SAS.
Can we just hook those SAS trays up to Linux and talk to them, and roll-our-own backup solution?
Probably.

This repo is about how we did it.
