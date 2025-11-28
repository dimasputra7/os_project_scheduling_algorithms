# Subnetting Operations: IP Subnetting Calculator
To perform Ip subnetting calculations, we have made a python-based tool which allows
uses to split a network either based on the required number of hosts per subnet or the
required number of networks.
The code uses Python’s built-in Ip address module to calculate networks, subnets,
broadcast addresses, and usable host ranges.

##Features
- Get network based on hosts per subnet or number of networks
- Calculates:
  o Subnet mask
  o Network Address
  o Broadcast Address
  o Valid host range
  o Number of usable hosts
- Displays a clear table output
  
##Requirements
- Python 3.8+
- No external libraries required
  
##How to Run the file:
1. Clone repository
2. Run the script
3. Follow the on-screen prompts:
  o Choose a subnetting method:
1. Subnet based on host per subnet
2. Subnet based on number of networks
  o Enter a valid network in CIDR format
  o Enter the required number of hosts or networks
Expected output: The program will display a detailed table which covers all the features
