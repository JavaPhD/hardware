|name|desc|fault tolerance|notes
|---|---|---|---|
|RAID0|data striped across multiple disks|no|very fast|
|RAID1|data copied in more than 1 disks|yes|n.a.|
|RAID5|3 or more disks <br /> data striped across multiple disks with parity|yes|the equivalent of an entire disk is used to store parity <br /> Example: <br /> an array of 4 disks totaling 4 TB,only 3TB will be used for actual data storage|
|RAID10|combine of RAID0+RAID1<br />minimum 4 disks|yes|good: benefits from fault tolerance of RAID1 and speed of RAID0<br /> downside:can only use 50% for data storage|
