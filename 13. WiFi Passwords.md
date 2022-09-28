WiFi Password Cracking:

    • WEP passwords are very easy to crack. Strong WPA/WPA2 passwords are difficult to crack.
    • It is usually advisable to get a router’s IP address and attack the router instead of the password since the router probably has far more vulnerabilities than the WPA/WPA2 encryption.
    • It is advisable not to use virtual machines for attacking wireless networks since most hypervisors do not offer near native performance and do not provide wireless interfaces in virtual machines.
    • Some tools used for cracking wireless network passwords: 
            ▪ aircrack-ng(sniffs network traffic and cracks WEP/WPA-PSK keys)
            ▪ reaver(guesses router pins which are used by windows devices to connect without passwords)

    • Most network cards have multiple modes. Two of these are:
            ▪ promiscuous mode: only accepts traffic meant for it and ignores all other traffic
            ▪ monitor mode: accepts and inspects all traffic

    • In order to perform a local DoS attack, two conditions must be met:
            ▪ proximity to network
            ▪ MAC address of the router should be known
