### Networking Fundamentals 🌐

Traditional networking uses hardware devices like **routers** and **switches**. Routers connect multiple networks, while switches connect specific devices within a network. In the cloud, these concepts are virtualized using software.

---

### Software-Defined Networking (SDN)

**Software-Defined Networking (SDN)** is the practice of managing networking components through software. This means that routers and switches are no longer physical devices you configure. Instead, they're implemented using software and are hosted in data centers.

* **Virtualization:** SDN **abstracts** networking components from the physical hardware. You can configure them through a cloud provider's console or by using an **API (Application Programming Interface)**.
* **Benefits:**
    * **Reduced Maintenance:** The CSP manages the physical devices, so you can focus on applications.
    * **Scalability:** You can add or remove networking resources on demand.
    * **Security:** SDN allows for network monitoring to detect threats like Distributed Denial of Service (DDoS) attacks and unauthorized scans.

---

### Load Balancing

**Load balancing** is used to distribute user traffic across multiple cloud servers. This prevents any single server from becoming overwhelmed, ensuring high performance and availability.

* **Application Load Balancers:** These operate at **Layer 7** (the Application Layer) of the **OSI model**. They handle **HTTP/HTTPS** traffic and direct users to the appropriate webpage or application.
* **Network Load Balancers:** These operate at **Layer 4** (the Transport Layer) of the **OSI model**. They handle **UDP** and **TCP** traffic, taking information from a router and forwarding it to the correct server.

---

### The OSI Model

The **Open Systems Interconnection (OSI) model** is a conceptual framework that describes the seven layers computers use to communicate and send data over a network. Security professionals use this model to identify and pinpoint the source of security threats. 
<img width="3998" height="2999" alt="image" src="https://github.com/user-attachments/assets/c4cd33f9-8a87-46c0-9746-837add21e597" />
