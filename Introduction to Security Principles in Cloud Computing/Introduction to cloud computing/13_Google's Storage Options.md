# Google Cloud Storage Options 💾

Google Cloud Storage offers a range of options for storing data, categorized by how frequently the data is accessed. This helps users manage costs by matching storage to their specific needs. The key distinction is between **hot data** (frequently accessed) and **cold data** (infrequently accessed). Google's Cloud Storage product for unstructured data uses a system of **buckets** to store objects like emails, images, and videos.

***

## Storage Classes

Google Cloud Storage provides four main classes, each designed for a different level of data access and cost efficiency. As a general rule, the less you need to access your data, the lower the cost of storing it. 

### Standard
* Best for **hot data** that requires frequent access (multiple times a day).
* Data is highly available and can be retrieved in milliseconds.
* Ideal for websites, gaming, streaming media, and medical data for active patients.

### Nearline
* Suitable for data accessed about once a month.
* More cost-effective than standard storage.
* A good option for data backups and records that are accessed less frequently.

### Coldline
* Designed for data accessed roughly once every 90 days.
* Very cost-effective because the data is at rest for long periods.
* Perfect for data that is needed for long-term record keeping but not daily use.

### Archival
* The most cost-effective option for data that is accessed once a year or less.
* Used for disaster recovery, long-term archiving, and permanent backups.
* Data is still available for retrieval but with a lower demand for availability.

  <img width="2800" height="1376" alt="image" src="https://github.com/user-attachments/assets/56c84149-3b4b-40e3-a95c-8f081af539f6" />
