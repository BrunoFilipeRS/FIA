Sure, here's an example of a more commercial-like network topology:

Consider a medium-sized business network with the following components:

1. **Devices:**
   - 50 Desktop Computers (PC1, PC2, ..., PC50)
   - 5 Laptops (Laptop1, Laptop2, ..., Laptop5)
   - 10 Printers (Printer1, Printer2, ..., Printer10)
   - 5 Servers (File Server, Email Server, Web Server, Database Server, Backup Server)
   - 3 Network Attached Storage (NAS) Devices

2. **Switches:**
   - 6 Access Switches (Switch1, Switch2, ..., Switch6)
   - 2 Distribution Switches (Distribution Switch1, Distribution Switch2)
   - 1 Core Switch (Core Switch)

3. **Router:**
   - 1 Router (Router)

4. **Wireless Access Points (WAPs):**
   - 10 Wireless Access Points

5. **Connections:**
   - PCs, laptops, printers, and servers are connected to access switches.
   - Access switches are connected to distribution switches.
   - Distribution switches are connected to the core switch.
   - Wireless access points are connected to the distribution switches.
   - NAS devices are connected to the core switch.
   - The router provides connectivity to external networks such as the Internet and connects to the core switch.

Here's a simplified representation of this network:

```
                        +----------------------------------+
                        |           Core Switch            |
                        +-----------------+----------------+
                                         |
                   +---------+    +---------------------+    +-------------+
                   | Router  |----| Distribution Switch1|----|Access Switch|
                   +---------+    +---------------------+    +-------------+
                      |           |                      |    +-------------+
                      |           +----------------------+----|Access Switch|
                      |                                      +-------------+
                      |                 +---------------------+    +-------------+
                      +-----------------| Distribution Switch2|----|Access Switch|
                                        +---------------------+    +-------------+
                                                                 |       ...     |
                                         +---------------------+    +-------------+
                                         |      Access Switch  |----|Access Switch|
                                         +---------------------+    +-------------+
                                                                 |       ...     |
                                                                 +-------------+
                                                                 |Access Switch|
                                                                 +-------------+
                                                                        |
                                                                 +-------------+
                                                                 |  NAS Device |
                                                                 +-------------+
```

In this example:

- Access switches connect end-user devices such as PCs, laptops, and printers.
- Distribution switches aggregate the connections from access switches.
- The core switch provides high-speed connectivity between different parts of the network.
- The router connects the internal network to external networks, such as the Internet.
- Wireless access points provide Wi-Fi connectivity for wireless devices.
- NAS devices provide centralized storage accessible to network users.

This network topology reflects a typical commercial setup with multiple devices, switches, routers, and servers. It can serve as a basis for implementing more complex algorithms and network management strategies in your project.




%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

estado inicial : um server qualquer, vamos dizer que está numa rede fibra e assumimos que o seu funcionamento é sempre a 100%, tal como a rede que o acompanha

estado objetivo : os endereços alvos das mensagens enviadas pelo servidor do estado inicial

criar 3 tipos diferentes de prioridade, low normal high
planear como essa prioridade influencia
talvez uma maior prioridade pegue banda dos menores