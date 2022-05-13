I have created web servers in citycloud using the ssh key-gen such that the Bastion acts as the jump host and the HAproxy acts as the load balancer.The tasks are accomplished using the ansible and further, I have deployed the Flask app and then curl to the devservers from HAproxy is also successful.

The IP addresses for the different servers created are:
bastionNSO:91.106.198.119
HAproxy:103.57.72.253
DevA:10.1.0.178
DevB:10.1.0.189
DevC:10.1.0.34
