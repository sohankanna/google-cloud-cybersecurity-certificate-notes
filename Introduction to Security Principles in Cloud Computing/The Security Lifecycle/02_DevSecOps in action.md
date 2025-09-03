# ✍️ The DevSecOps Lifecycle in Action

DevSecOps embeds security throughout the software development lifecycle (SDLC), a concept known as **"shifting left."** This approach ensures that security is a continuous part of the process, rather than a final check. The lifecycle is often depicted as an **infinity loop** ♾️ with seven key phases.

***

### 1. Plan
- **Threat Analysis**: The team identifies potential threats to the software.
- **Security Planning**: They plan which security scans, tools, and tests will be used.
- **IAM (Identity and Access Management)**: Roles and permissions are assigned to team members to ensure proper access.
- **Project Scoping**: Assets, data, and templates are outlined to define the project's scope.

### 2. Code
- **Secure Coding Practices**: Developers write code using secure design principles and conduct peer code reviews.
- **Automated Security Tools**: Development tools use plugins to monitor for bugs and compliance issues as the code is being written.
- **Early Feedback**: Developers receive security scan reports directly in their tools to quickly fix vulnerabilities.

### 3. Build
- **Automated Security**: As the software is built from the source code, the team incorporates automated vulnerability checks and security scans.
- **Early Alerts**: The "shift left" methodology ensures developers are alerted to issues during this phase, well before deployment.

### 4. Test
- **Manual and Automated Testing**: The software undergoes various tests to ensure integrity and functionality.
- **Security & Compliance Checks**: Automated tests specifically verify that all security and compliance requirements are met.

### 5. Release
- **Configuration Review**: The environment's configuration is evaluated against automated security checks to determine if it's ready for production.
- **Final Sign-off**: Source code and software artifacts are reviewed and receive final approval.

### 6. Deploy
- **Automation**: The team uses automated tools to push the software into the production environment for end-users.

### 7. Operate
- **Continuous Monitoring**: After deployment, the system is continuously monitored for any events, alerts, or vulnerabilities that need patching.
- **Feedback Loop**: A constant feedback loop keeps the development, operations, and security teams updated on the software's performance and security posture.


By integrating security into each of these phases, DevSecOps improves collaboration and efficiency, making security a shared responsibility and ensuring vulnerabilities are found and fixed early.

<img width="621" height="356" alt="{BB627F79-070A-4C36-8A3F-D79DB9A5A4EC}" src="https://github.com/user-attachments/assets/31a04fb3-4c57-4af5-9d9e-ef136a7c1b35" />
