# backupberg
Repurposed Hitachi SAN components as custom backup solution

After decommissioning some gear, we still had about 300x 3TB SAS hard drives, and the accompanying enclosures. 
We stopped paying warranty coverage on the actual Hitachi technology, which converted SAS to Fiber channel RAID LUNs, and converted Fiber Channel raw commands up to nice-to-use NFS / CIFS.
But the actual drive carriages and cabinets speak raw SAS.
Can we just hook those SAS trays up to Linux and talk to them, and roll-our own backup solution?
Probably.

This repo is about how we did it.
