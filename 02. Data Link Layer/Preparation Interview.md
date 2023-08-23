1. **What is the purpose of the Data Link Layer in the OSI model?**
   - The Data Link Layer provides error detection and correction, as well as framing and addressing of data. It ensures reliable point-to-point communication over a physical link.

2. **Explain the concept of MAC address.**
   - A MAC (Media Access Control) address is a unique identifier assigned to a network interface card (NIC) at the hardware level. It's used to uniquely identify devices on a local network.

3. **What is Ethernet? How does it work?**
   - Ethernet is a widely used LAN technology. It defines the wiring and signaling standards for the physical layer and the framing of packets at the data link layer. Ethernet frames include source and destination MAC addresses.

4. **Differentiate between a switch and a hub.**
   - A switch operates at the data link layer and uses MAC addresses to forward data to specific devices, creating separate collision domains. A hub operates at the physical layer and broadcasts data to all devices, creating a single collision domain.

5. **Explain the role of ARP (Address Resolution Protocol).**
   - ARP is used to resolve IP addresses to MAC addresses in a local network. When a device wants to communicate with another device, it sends an ARP request to find the MAC address associated with the IP address.

6. **What is VLAN (Virtual Local Area Network)?**
   - A VLAN is a logical grouping of devices within a physical network, allowing devices to communicate as if they are on the same physical network, even if they are not physically connected to the same switch.

7. **Describe the process of frame forwarding in a switch.**
   - When a switch receives a frame, it examines the destination MAC address. It checks its MAC address table to determine which port the destination MAC address is associated with and forwards the frame only to that port.

8. **Explain the purpose of CRC (Cyclic Redundancy Check) in the Data Link Layer.**
   - CRC is used for error detection in the Data Link Layer. The sender computes a CRC value based on the data being sent and appends it to the frame. The receiver computes its own CRC value and compares it to the received CRC value to check for errors.

9. **What is Flow Control? How is it managed in the Data Link Layer?**
   - Flow control is the mechanism to ensure that the sender and receiver of data are operating at compatible speeds. In the Data Link Layer, flow control is often managed using techniques like sliding window protocols.

10. **Discuss the differences between Stop-and-Wait ARQ and Go-Back-N ARQ.**
    - Stop-and-Wait ARQ is a simple protocol where the sender sends a single frame and waits for an acknowledgment before sending the next frame. Go-Back-N ARQ allows the sender to send multiple frames before waiting for acknowledgments but requires retransmission of all unacknowledged frames if any are lost.
