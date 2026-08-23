# Router, Hub and Server

## 1. Router

### Definition

A **router** is a networking device that connects different networks and forwards data between them.

It checks the destination IP address and chooses where the data should go.

### Example

At home, you have:

**Mobile + Laptop → Wi-Fi Router → Internet**

The router connects your home network to the Internet.

For example, when you open YouTube on your laptop:

**Laptop → Router → Internet → YouTube Server**

The router forwards the network traffic toward its destination.

### Main Functions

* Connects different networks
* Forwards packets
* Provides network access
* Often provides Wi-Fi
* Can provide DHCP in home networks
* Can provide basic firewall features

### Easy Definition

**Router = Connects networks and forwards data.**

---

# 2. Hub

### Definition

A **hub** is a simple networking device that connects multiple devices in the same network.

When a hub receives data, it sends the data to **all connected ports**.

It does not normally check which device is the intended destination.

### Example

Suppose four computers are connected to a hub:

```text id="w9q2p7"
PC 1 ──┐
PC 2 ──┤
PC 3 ──┼── Hub
PC 4 ──┘
```

If PC 1 sends data to PC 3, the hub sends the signal to all connected devices.

**PC 1 → Hub → PC 2, PC 3, PC 4**

PC 3 accepts the data, while the other devices ignore it.

### Disadvantages

* Sends traffic to all ports
* Creates unnecessary network traffic
* Less efficient than a switch
* Provides very little traffic control
* Rare in modern networks

### Easy Definition

**Hub = Sends incoming data to all connected ports.**

---

# 3. Server

### Definition

A **server** is a computer or software system that provides services, data, or resources to other computers called **clients**.

The client requests something, and the server provides it.

### Example: Website

When you open a website:

**Your Browser (Client) → Web Server**

The browser requests the webpage.

The server processes the request and sends the webpage back:

**Web Server → Your Browser**

### Other Examples of Servers

#### Web Server

Provides websites and web content.

**Example:** Your browser requests a webpage from a web server.

#### File Server

Stores and shares files with users on a network.

**Example:** Employees access company documents from a file server.

#### Database Server

Stores and manages data for applications.

**Example:** A banking application communicates with a database server to retrieve account information.

#### Mail Server

Handles sending and receiving email.

---

# Router vs Hub vs Server

| Device | Main Function                     | Example           |
| ------ | --------------------------------- | ----------------- |
| Router | Connects different networks       | Home Wi-Fi router |
| Hub    | Sends data to all connected ports | Small/old LAN     |
| Server | Provides services or resources    | Web server        |

---

# Real-Life Example

Imagine a university network.

### Router

The **router** connects the university's internal network to the Internet.

**University Network → Router → Internet**

### Hub

If an old computer lab uses a **hub**, it can connect multiple computers in the same network.

**PCs → Hub → Network**

### Server

The university may have a **server** that stores student information or provides websites and other services.

**Student Computer → Network → University Server**

---

# Easy Way to Remember

**Router → Connects Networks**

**Hub → Sends Data to All Ports**

**Server → Provides Services/Data**

### Viva Answer

**Router:** A device that connects different networks and forwards data.

**Hub:** A device that sends incoming data to all connected ports.

**Server:** A computer or system that provides services or resources to clients.

