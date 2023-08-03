# IP SUBNET CALCULATOR
#### Video Demo: https://youtu.be/Lu3rDSoLNPI
#### Description:

This is an IPv4 subnetting calculator that helps you calculate the following:

- network address
- broadcast address
- total number of hosts
- IP class
- Private or Public IP

When you run this program, it welcomes you with a text: IP Subnet Calculator in an ASCII format. Underneath the ASCII, you must enter an IPv4 address in a CIDR format e.g. 192.168.10.1/24. Output of this program will provides you the network address, broadcast address, total number of hosts in DINOSAY module and IP class & if it's a private or public IP address in COWSAY module.

Results(network address, broadcast address, total number of hosts, IP class, private/public IP) will be stored in a .csv file named "project.csv". Alternatively, you may see the data using the command line by entering the command below:

##### python project.py project.csv

This will show you the results in a tabulated data table. All of the test have passed by running "pytest" on my "test_project.py". That's all about my Python project. Hope you enjoy!