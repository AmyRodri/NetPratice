*This project has been created as part of the 42 curriculum by `amyrodri`[, <amyrodri>].*

# NetPractice

## 🎧 Description

Welcome to **NetPractice**, a project focused on understanding and mastering the
fundamentals of **computer networking**.

In this project, the goal is to configure small virtual networks and ensure that
all devices can communicate correctly. Each level presents a different network
topology where routers, switches, and hosts must be configured properly using
correct **IP addressing**, **subnet masks**, and **routing logic**.

Think of it like this:

> Packets on the road, routers in control  
> Masks defining borders, networks as a whole.  
> If the gateway’s right and the routes align  
> The packet hits the target every single time. 🚀

Through 10 progressively more complex levels, this project trains your ability to:

- Analyze network topology
- Assign valid IP addresses
- Configure subnet masks
- Understand routing paths
- Debug connectivity issues

By completing this project, you gain a **solid foundation in how networks
actually work under the hood**.

---

## 🛠 Instructions

### Running the Training Interface

The NetPractice training interface runs directly in your browser.

1. Download or clone the repository:

```bash
git clone <repository_url>
cd netpractice
```

2. Open the training interface:

Simply open the file:
```bash
index.html
```

in your web browser.

Example (Linux):

```bash
firefox index.html
```

The interface will allow you to solve each networking level interactively.

---

### Solving the Levels

Each level presents a `network diagram` where you must configure:

- IP addresses
- Subnet masks
- Gateways
- Routing paths

Your goal is to make sure that `packets can successfully reach their destination`.

Once a level is solved, you can `export the configuration`.

---

### Exporting Configurations

After solving a level:

1. Click `Export` in the NetPractice interface

2. Save the exported configuration file

Repeat this process for all levels.

---

### Submission Requirements

The final repository must contain:

- `10 exported configuration files`

- `One configuration per level`

They must be placed `at the root of the repository`.

Example structure:

```bash
netpractice/
│
├── level1.json
├── level2.json
├── level3.json
├── level4.json
├── level5.json
├── level6.json
├── level7.json
├── level8.json
├── level9.json
├── level10.json
│
├── index.html
└── README.md
```
---

### 🌐 Networking Concepts Covered

During this project, the following `core networking concepts` are studied:

`TCP/IP Addressing`

Every device in a network must have a `unique IP address` that identifies it.
These addresses allow devices to send and receive data.

Example:

```bash
192.168.1.10
```

---

### Subnet Mask

The `subnet mask` defines which part of an IP address refers to the network
and which part refers to the host.

Example:
```bash
IP:          192.168.1.10
Subnet Mask: 255.255.255.0
```

This determines which devices belong to the `same network`.

---

### Default Gateway

A `default gateway` is the router responsible for sending packets
to `other networks`.

If a device wants to communicate outside its local network, it sends
the packet to the gateway.

---

### Routers

Routers connect `multiple networks together` and determine the
best path for packets to travel.

They use `routing tables` to decide where packets should go.

---

### Switches

Switches operate at the `data link layer` and connect multiple
devices inside the same network.

They allow local communication between hosts.

---

### OSI Model

The project also relates to the `OSI networking model`, which
divides networking into layers:

1. Physical

2. Data Link

2. Network

3. Transport

4. Session

1. Presentation

1. Application

In NetPractice, the main focus is on the `Network Layer` (Layer 3),
where IP addressing and routing occur.

---

### 📚 Resources

These references were used to better understand networking concepts:

#### Documentation

- RFC 791 — Internet Protocol

- RFC 950 — Subnetting

- TCP/IP Networking Basics

#### Articles & Tutorials

- Cisco Networking Fundamentals

- Subnetting Explained

- Introduction to Routing

### AI Usage

Artificial Intelligence tools were used as `learning assistants` during this project.

AI was used for:

- Explaining networking concepts (subnetting, routing, gateways)

- Helping clarify theoretical doubts

- Assisting with documentation structure (README formatting)

> AI was `not used to automatically solve the NetPractice levels`.
All configurations were analyzed and solved manually to ensure a
proper understanding of the networking logic.

---

### 🎤 Final Words

From packets to routers, from masks to routes,
Learning networks by solving the puzzles and routes.

If the IP is clean and the gateway aligned,
The packet goes through — connection defined. 🚀

