# Levels Of the Software Supply Chain  🎶
**SLSA (Supply-chain Levels for Software Artifacts)** is a security framework that organizations use to harden the software supply chain. Its goal is to improve the integrity and security of **artifacts** (digital objects like files or images) used in software development. SLSA prioritizes trusting secure build platforms and processes over individuals.

SLSA's framework is built on three core **trust boundaries**:
* **Build Integrity**: Ensures that the software uses the correct, original dependencies and that the build process is unmodified.
* **Source Integrity**: Confirms that the source code reflects the developer's intentions and that all modifications can be traced.
* **Dependencies**: Requires that any external dependencies used in an artifact are thoroughly examined with security checks.

### SLSA Levels and Tracks 🪜
SLSA's security levels are structured like a pyramid, with organizations progressing from the bottom up. The framework is divided into **tracks**, allowing teams to address specific security concerns separately. The **build track** focuses on establishing **provenance**—a record of the processes and tools used to build an artifact.

* **L0 (Base Level)**: The artifact does not meet any SLSA requirements.
* **L1 (Document Provenance)**: The minimum requirement is to document the artifact's provenance, including its dependencies and build process. This is the first step toward improving integrity.
* **L2**: Requires using a hosted build platform to manage builds, providing a more controlled environment.
* **L3**: Requires the build platform to offer protection against tampering with the artifact's provenance, ensuring a high level of security.

<img width="1261" height="941" alt="{AD0FEE05-1AE4-4E52-A52B-7D48574D1A24}" src="https://github.com/user-attachments/assets/d38a0bee-139f-4348-ad86-f545fbbfb399" />


Organizations must meet the requirements of each level before advancing. Achieving higher levels can take years, depending on the size of the organization.

### Technical Controls and Limitations
In addition to the levels and boundaries, SLSA recommends incorporating technical controls to further secure the supply chain. These controls include:
* **Version control**
* **Vulnerability scanning**
* **Build verification**
* **Deployment policies**
* **Artifact management**

It is important to note that SLSA does not:
* Assess the integrity of a developer's individual coding practices.
* Offer security recommendations for companies that intentionally create malicious software.

By implementing SLSA's levels, boundaries, and controls, organizations can make their artifacts more resilient and reduce the risk of software supply chain attacks.
