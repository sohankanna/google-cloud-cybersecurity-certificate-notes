# The Shared Responsibility Model 🤝

The **shared responsibility model** is the agreement between a **customer** (an organization or user) and a **Cloud Service Provider (CSP)** that defines who is accountable for different aspects of cloud security. It outlines the division of security responsibilities.

---

## On-Premises vs. Cloud Security

* **On-Premises Model:** The business owns and operates its own data center and servers. The business is **100% responsible** for all security.
* **Cloud Model:** The responsibility for security is shared between the customer and the CSP. The amount of CSP involvement depends on the service model (IaaS, PaaS, SaaS) and other factors.

---

## Security **of** the Cloud vs. Security **in** the Cloud

A key concept of the shared responsibility model is the distinction between what the CSP secures and what the customer secures.

### CSP Responsibilities (Security **of** the Cloud)
The CSP is responsible for the foundational security of the cloud infrastructure itself. This includes:
* **Physical infrastructure:** Maintaining servers, data centers, and other hardware.
* **Network and resource availability:** Ensuring the network is up and running and resources are accessible.
* **Maintenance and updates** of the services they provide (e.g., a firewall service).

### Customer Responsibilities (Security **in** the Cloud)
The customer is responsible for what they put **on** the cloud. This includes:
* **Data security:** Securing all data stored in the cloud.
* **Configuration:** Properly configuring services to meet specific security and compliance requirements.
* **User and access management:** Securing the people and applications using their cloud resources.
* **Monitoring and incident response** for their own services.

**Analogy:** The CSP is like a gymnasium that provides the building and equipment (security **of** the cloud), while the customer is responsible for using the equipment safely and achieving their own fitness goals (security **in** the cloud).

---

## Key Considerations

* **Service Level Agreements (SLAs):** CSPs provide SLAs that quantify service availability (e.g., 99.99% uptime) and outline the terms of responsibility, eliminating guesswork.
* **Workload and Service Type:** The level of shared responsibility changes based on the type of service being used:
    * **Infrastructure as a Service (IaaS):** The customer has the most responsibility.
    * **Platform as a Service (PaaS):** The responsibility is more balanced.
    * **Software as a Service (SaaS):** The customer has the least responsibility, as the CSP manages most of the security.
* **Industry and Location:** Regulatory frameworks (e.g., GDPR, HIPAA) and a business's location dictate specific security requirements and influence how the shared responsibility model is applied. Customers must be aware of their inherited controls and what is required for compliance.
