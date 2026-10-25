# Network Basics 1

More networking basics: the hosts file, network interfaces, and listening on a port.

## Concepts

- **localhost / 127.0.0.1:** The loopback address that points to the machine itself.
- **0.0.0.0:** Means all IPv4 addresses on the local machine.
- **/etc/hosts:** A local file that maps hostnames to IP addresses before DNS is used.
- **ifconfig:** Displays the network interfaces and their IP addresses.
- **netcat (nc):** A tool to read and write data over network connections.
- **telnet:** A tool to connect to a host on a specific port.

## Files

| File | Description |
|------|-------------|
| `0-change_your_home_IP` | Makes `localhost` resolve to `127.0.0.2` and `facebook.com` to `8.8.8.8`. |
| `1-show_attached_IPs` | Displays all active IPv4 IPs on the machine. |
| `2-port_listening_on_localhost` | Listens on port 98 on localhost. |

## Author

Asim Hamid
