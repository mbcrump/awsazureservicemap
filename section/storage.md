## Storage

| Service                               | AWS                                                | Azure                                                                                                                                                                                                                                                                                                                 | Description                                                                                                                                                                                                                                                                                         |
|------------------------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Object storage                     | Simple Storage Services (S3)                              | [Storage-Block Blob (Standard-Hot)](/rest/api/storageservices/fileservices/understanding-block-blobs--append-blobs--and-page-blobs#about-block-blobs)                                                                                                        | Object storage service, for use cases including cloud applications, content distribution, backup, archiving, disaster recovery, and big data analytics.                                                                                                                                             |
| Virtual server disk infrastructure | Elastic Block Store (EBS)                                 | [Disk Storage -Page Blobs (for VHDs or other random-write type data)](/rest/api/storageservices/fileservices/understanding-block-blobs--append-blobs--and-page-blobs#about-page-blobs) <br/><br/>[Disk Storage -Premium Storage](http://azure.microsoft.com/services/storage/disks/) | SSD storage optimized for I/O intensive read/write operations.                                                                                                                                                                           |
| Shared file storage                | Elastic File System                                       | [Files](https://azure.microsoft.com/services/storage/files/)                                                                                                                                                                                                                     | A simple interface to create and configure file systems quickly as well as share common files.  |
| Archiving-cool storage             | S3 IA Glacier                                             | [Storage-Hot, Cool & Archive Tier](/azure/storage/storage-blob-storage-tiers)                                                                                                                                                                                                                     | A lower cost tier for storing data that is infrequently accessed and long-lived.  |
| Backup                             | None                                                      | [Backup](https://azure.microsoft.com/services/backup/)                                                                                                                                                                                                                                                           | Backup and archival solutions allow files and folders to be backed up and recovered from the cloud, and provide off-site protection against data loss.  |
| Hybrid storage                     | Storage Gateway                                           | [StorSimple](https://azure.microsoft.com/services/storsimple/)                                                                                                                                                                                                                                                         | Integrates on-premises IT environments with cloud storage. Automates data management and storage, plus supports disaster recovery.                                                                                                                                                               |
| Bulk data transfer                 | Import/Export Disk                                    | [Import/Export](https://azure.microsoft.com/documentation/articles/storage-import-export-service/)                                                                                                                                                                                                                     | A data transport solution that uses secure disks and appliances to transfer substantial amounts of data.    |
| **&nbsp;**                         | Import/Export Snowball<br/><br/>Snowball Edge<br/><br/>Snowmobile | [Data Box](https://azure.microsoft.com/services/storage/databox/)                                                                                                                                                                                                                                                                                                                         | Petabyte- to Exabyte-scale data transport solution.                                                                     |
| Disaster recovery                  | None                                                      | [Site Recovery](https://azure.microsoft.com/services/site-recovery/)                                                                                                                                                                                                                                                   | Automates protection and replication of virtual machines with health monitoring, recovery plans, and recovery plan testing.                                                                                                                                                                      |