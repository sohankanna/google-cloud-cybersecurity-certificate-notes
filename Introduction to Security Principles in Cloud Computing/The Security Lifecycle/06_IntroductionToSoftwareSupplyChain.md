# What is the Software Supply Chain?
***
The **software supply chain** encompasses all the components, processes, and individuals involved in the development and delivery of software. This includes everything from the code scripts and third-party dependencies (like libraries and plugins) to the people and organizations involved in the process.

### Vulnerabilities of the Software Supply Chain
***
The software supply chain has multiple points of vulnerability that can be exploited by threat actors:
* **People**: Employees, including developers, security analysts, and management, can be a major vulnerability. Human error or malicious intent can lead to breaches.
* **Processes and Policies**: Inadequate security practices, such as insecure code review cycles, ineffective communication, and insufficient access controls, can create weaknesses.
* **Technology and Third-Party Dependencies**: Software often relies on external components. If these dependencies (e.g., open-source libraries, containers) have been tampered with, they can introduce malware or backdoors into your system. 

### Securing the Software Supply Chain
***
Securing the software supply chain is crucial to prevent attacks and protect an organization's data. This involves **security hardening**, which is the process of strengthening a system to reduce its vulnerabilities. Key measures include:

* **Continuous Security Checks**: Implementing regular vulnerability checks throughout the **CI/CD pipeline** helps to find and patch issues early.
* **Software Bill of Materials (SBOM)**: An **SBOM** is a machine-readable list of all software components and their dependencies. It helps organizations track and manage vulnerabilities, and it also demonstrates compliance to stakeholders.
* **Best Practices**: Use secure coding practices, enforce strong access controls (**IAM**), and ensure clear communication and review processes across all teams.
