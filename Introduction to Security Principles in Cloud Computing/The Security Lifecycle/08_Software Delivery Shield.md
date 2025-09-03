# What is Software Delivery Shield (SDS)?
**Software Delivery Shield (SDS)** is a fully managed service from Google Cloud designed to strengthen the security of the **software supply chain** throughout its lifecycle. It combines Google's best practices, security dashboards, and alignment with the SLSA framework to provide a comprehensive view of an application's security health.

### Key Features of SDS 🛡️
SDS offers several features to help organizations secure their supply chain:

* **Cloud Workstations**: This feature provides secure, fully managed development environments that developers can access directly from a web browser. This reduces the risk of insecure local code storage and inconsistent configurations, while improving visibility through shared repositories. 
* **Automated SBOMs**: SDS automatically generates a **Software Bill of Materials (SBOM)**, which is a machine-readable list of all software components. This provides a detailed overview for security and compliance purposes.
* **Assured Open Source Software (OSS)**: SDS includes a collection of open-source packages that have been vetted, scanned, and improved by Google. This allows organizations to use trusted dependencies and reduce the risk of supply chain attacks.

### SDS and the "Shift Left" Principle ⬅️
SDS supports the **"shift left"** security approach by integrating security practices at the earliest stages of the software development lifecycle. By helping to secure **CI/CD pipelines**, SDS reinforces the DevSecOps workflow. It provides guidance on:

* **IAM (Identity and Access Management) Policies**: SDS suggests policies to provide granular access control over resources.
* **VPC (Virtual Private Cloud) Guidance**: It offers best practices for securing network environments.
* **Cloud-Native Development Environments**: It supports using secure, centralized development environments that align with **SLSA** standards.

These practices help enforce security at different stages of the pipeline, leading to more efficient and secure software updates and deployments. Understanding services like SDS is vital for a cloud security professional aiming to secure an organization's software supply chain.
