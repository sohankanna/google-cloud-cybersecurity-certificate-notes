### IAM in the Cloud ☁️

Identity and Access Management (IAM) is a fundamental cloud security tool that controls who has access to which resources. Organizations configure IAM settings within a cloud service provider's (CSP) console to manage identities and their permissions.

---

### Key IAM Identities

* **Principals:** In Google Cloud and other platforms, principals are the entities that can access cloud resources. They can be **users** (like a person with an account), **groups**, or **service accounts** (non-human identities).
* **Groups:** A group is a collection of principals. Using groups is a security best practice because it makes it easier to assign the correct permissions to a large number of users at once, helping to enforce the **principle of least privilege**. When a person's role changes, you can simply change their group membership to update their access.
* **Service Accounts:** These are **non-human identities** used by applications, services, or virtual machines to access cloud data. For example, you would grant a service account an IAM role to allow an application to run code and access necessary resources.

---

### Federation

* **Federation** is a method that allows **external identities** to access your cloud environment without needing to create new credentials for them.
* A common example is using **Single Sign-On (SSO)**, where a user's identity from one organization (like their company) is used to access resources in your cloud environment. This is often used for partners, contractors, or vendors.
* Service accounts for external workloads also use federation. This allows them to use **short-term credentials** to securely access your CSP's resources.
* To enhance the security of federated identities, you can enforce **Multi-Factor Authentication (MFA)**, which requires users to verify their identity in more than one way.
