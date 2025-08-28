## Identity and Access Management (IAM) 🔒

IAM is a security framework that ensures the right people and services have the appropriate access to resources. Key components of IAM include roles, principals, and policies.

---

### Principals and Roles

* **Principals:** These are the **identities** that can be granted access. They can be **end users** (like a person with a Google account) or **service accounts** (non-human identities for applications and services).
* **Roles:** A role is a **collection of permissions** that define the actions a principal can take. When a principal is assigned a role, they inherit all the permissions associated with it.
* **Least Privilege:** A key security best practice is to apply the **principle of least privilege**. This means you only grant a principal the minimum level of access needed to perform their job.
* **Groups:** To simplify management for large organizations, **groups** are used to combine multiple principals (users or service accounts) together. This makes it easier to assign access controls to a whole team instead of to each individual.

---

### Policies

* **Policies:** These are rules that **allow or deny** principals access to resources. Policies are attached to roles to set constraints on permissions.
* **Allow Policies:** These policies grant a principal a certain type of access and may set conditions on that access.
* **Deny Policies:** These policies are **constraints** that explicitly prevent principals from performing certain actions, overriding any allow policies.
* **Best Practice:** It's more efficient to create **allow policies for groups** rather than for multiple individual accounts. For example, you can create a single policy for an entire engineering team rather than for each person on the team.
