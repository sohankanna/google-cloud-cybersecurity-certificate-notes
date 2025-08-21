# Virtualization and Virtual Machines 🖥️

**Virtualization** is the core technology that enables cloud computing. It creates a software-based, or virtual, version of physical infrastructure components like servers, storage, and networks. This technology uses **virtual machines (VMs)** to simulate a physical computer.

A VM is an isolated computing environment that contains its own operating system (like Windows or Linux) and runs on a portion of the underlying physical computer's resources.

---

### The Role of a Hypervisor

A **hypervisor** (or virtual machine monitor) is the software layer that manages the relationship between the physical hardware and the virtual machines. It is responsible for distributing resources and ensuring that each VM remains isolated from the others.

There are two types of hypervisors:

* **Type 1 (Bare-Metal)**: This hypervisor replaces the entire operating system of the physical computer and has direct access to the hardware. It is more secure and streamlined due to this direct access. Type 1 is the most common hypervisor used by cloud service providers.
* **Type 2 (Hosted)**: This hypervisor runs as an application on top of the host computer's existing operating system. While easier to install, it has more overhead and is less secure than a Type 1 hypervisor because it relies on the underlying OS. 

---

### Advantages of Virtual Machines

VMs offer several key advantages that make them a fundamental part of cloud computing:

1.  **Portability**: VMs are isolated entities that can be easily moved and relocated throughout a network, which is especially useful in hybrid cloud environments.
2.  **Scalability**: Unlike physical servers with fixed hardware, VMs can be scaled up or down to provide more or fewer resources (CPU, memory, storage) as a development team's needs change.
3.  **Testing Environments**: VMs provide a safe, isolated environment for developers to test code without affecting existing infrastructure or other users. After testing, the VMs can be easily deleted.

<img width="740" height="346" alt="{4C03BEBD-AC3E-428E-BAA7-F7A14F6A2B64}" src="https://github.com/user-attachments/assets/b5fe2b22-3e87-483d-adfc-22e5642c4cbf" />
