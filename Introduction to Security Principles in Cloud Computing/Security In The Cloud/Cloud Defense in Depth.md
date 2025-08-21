# Cloud Defense in Depth 🛡️

**Defense in depth** is a cybersecurity strategy that uses multiple layers of security controls to protect assets and data, especially critical ones. This layered approach helps to reduce risk and improve an organization's overall **security posture**.

---

## Types of Cloud Security Controls

Security controls are safeguards designed to reduce security risks. In a cloud environment, these controls are used in various layers to build a robust defense-in-depth model.

### Identity Controls
* **Purpose:** Authenticates a user's identity before they can access resources like networks or storage.
* **Example:** **Multi-factor authentication (MFA)**, where a user must provide an additional form of verification (e.g., a code from a phone or a different email) to prove their identity.

### Protective Controls
* **Purpose:** Protects resources and shields them from malicious attacks.
* **Examples:**
    * Antivirus software on virtual machines (VMs).
    * Web application firewalls (WAFs).
    * Policies for infrastructure as code.

### Network Controls
* **Purpose:** Protects access through network paths.
* **Example:** A firewall that monitors and controls incoming and outgoing network traffic.

### Detective Controls
* **Purpose:** Identifies suspicious activity if it occurs.
* **Example:** An **Intrusion Detection System (IDS)** that monitors system activity and alerts security analysts to potential threats. Google Cloud's Security Command Center is an example of an IDS.

### Responsive Controls
* **Purpose:** Uses automation to respond to security events.
* **Example:** An automated system that sends an email or text notification to a security analyst when a threat is detected.

### Recovery Controls
* **Purpose:** Restores access and functionality in the event of a security failure or attack.
* **Example:** Reverting to a system backup after an attack to restore the system to a pre-breach state.

---

## Analogy: A Community Garden 🍅

Think of these controls working together like a security system for a community garden:
* **Identity Controls:** Determines who gets access to the garden.
* **Protective Controls:** A fence around the garden acts as a protective barrier.
* **Network Controls:** A key to the gate only given to authorized people.
* **Detective Controls:** Installing a camera to monitor suspicious activity.
* **Responsive Controls:** Receiving an automatic text message alert about suspicious activity.
* **Recovery Controls:** Mending the fence after a failure to re-establish security.

By combining these layers, you can significantly increase the security of cloud resources and reduce vulnerabilities.
