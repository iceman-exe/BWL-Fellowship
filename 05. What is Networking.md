What is Networking:


A network is a group of connected devices. Devices may include laptops,phones, IoT devices, cameras etc. The internet consists of a large number of smaller networks connected together. These smaller networks are private networks, connected to each other through public networks.

Devices use labels to identify themselves on a network. These labels are of 2 kinds:
	-IP(Internet Protocol) Addresses: which can be changed
	-MAC(Media Access Control) Addresses: generally, theoretically unique.

IP Address:

    • For a period of time, an IP address can be used as an identifier for a host on a network. After a period of time, the same IP address may be associated with some other device.
    • IP addresses can change but one address can’t be active simultaneously more than once within same network(all IP addresses within a network must be unique).
    • IP addresses and networks follow standards known as protocols. Protocols force different devices and networks to communicate in the same language.
    • Depending on the network(if it is public or private), a device may have a public or private IP address. The public address is used to identify a device on the internet, while a private address is used to identify it among others devices on the same network.
    • Devices can use private IP addresses to identify each other on a local network. All communication with public networks(such as the internet) happens through the same public IP assigned to a router by the ISP(Internet Service Provider). This public IP can be static or dynamic.
    • Internet Protocol version 4(IPv4) addresses are limited to over 4 billion devices. It is estimated that over 50 billion devices have connected to the internet by the end of 2021. Internet Protocol version 6(IPv6) is a newer addressing scheme which can provide addresses for over 300 trillion device.


MAC Address:

    • All network connected devices have a physical network interface, which is a microchip found on the motherboard, which has a unique address. The first part of this address identifies the manufacturer of the device, while the last part is unique to the device.
    • MAC addresses can be spoofed. Spoofing occurs when a device pretends to be another device which it is not. When this happens, it can break/bypass poorly implemented security controls.


Ping:

    • Uses ICMP(internet control message protocol) packets to determine the performance of a connection between different devices for example to check if a connection exists or is reliable.
    • Measures the time taken for packets to travel between devices. 
    • Can be used against other devices on the network or resources like websites.
