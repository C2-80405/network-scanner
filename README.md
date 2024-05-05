This is the basic Network Scanner

It can check the number of devices connected to your network and print their local IP addresses along with their MAC addresses.




1. Sniff_Tool.py

I have used argparse and scapy to make this basic network scanner.

[Syntax : python <file_name> -ip <ip_address>/<subnet>]

[Use it with root/administrative priviledges]


One needs to have argparse and scapy installed.
They can be installed with :
pip install argparse
pip install scapy


2. Sniff_Tool2.py

I have used sys and scapy to build this basic network scanner.

Call it from the command line using root/admin privileges

[Syntax : python <file_name> <ip_address>/<subnet>]

[Put the ip address of your default gateway(router) to get all the client's ip address.] 
Scapy can be installed with :
pip install scapy
