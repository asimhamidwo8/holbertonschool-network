# Network Basics

An introduction to computer networking: the OSI model, types of networks, MAC and IP addresses, TCP and UDP, ports, and ICMP.

## Concepts

- **OSI model:** A conceptual model with 7 layers, from the physical layer (1) to the application layer (7).
- **LAN / WAN / Internet:** LAN connects local devices, WAN connects LANs, and the Internet connects WANs.
- **MAC address:** The unique identifier of a network interface.
- **IP address:** The address of a device on a network, like a postal address for a house.
- **TCP:** Reliable and ordered data transfer, with acknowledgments.
- **UDP:** Fast data transfer without guarantee of delivery.
- **Ports:** Entry points on a device (22 SSH, 80 HTTP, 443 HTTPS). IP + port = socket.
- **ICMP:** Used by `ping` to check if a host is reachable.

## Files

| File | Description |
|------|-------------|
| `4-TCP_and_UDP_ports` | Displays listening sockets with the PID and program name. |
| `5-is_the_host_on_the_network` | Pings an IP address 5 times, or prints usage if no argument is given. |

## Author

Asim Hamid
