# AWS-SecureWebAppViaVPC
Securing Web Application via VPC, Firewalls, Submets, ACLs 


It consists a private subnet for web servers and one public subnet for proxy servers. The proxy servers absorb most of the traffic by responding with the latest version of the page they have in their cache, and they forward traffic to the private web servers. 

Network ACLs restrict traffic that goes from one subnet to another which works as a firewall. That’s an additional layer of security on top of security groups, which control traffic to and from a virtual machine.


![Secure Web App](arch.png)
