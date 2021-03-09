VPC--- Virtual private cloud

you will get 5-6 question in the exam

It is the logically isolated sections of aws.

We can have complete control over the virtual private environment.

we can provide the ip ranges,configure subnets with our routetables.

There is a NACL and security group which determines who or what is allowed to access to the VPC.

We can create a VPN to the on- permise datacenter and the VPC
This is a extention of the current datacenter.

This is mentioned as the hybrid cloud environment.

We can see there is an internet gateway attached to the VPC.
this allow the connections to the routetable.

Then it will go to the NACL this is first sign of defends. The NACL is stateless which means you have to add an inbound
and outbound rules for your VPC.

stateless means they only view the roles in one way. Which is if you add a inbound rule then you have to add a outbound rule to
match the inbound rule.

We can add allow rules and deny rules to block certain ip addresses to the network.

Securitygroups :-
This is the second line of defends. and it is statefull which means if we create a inbound rule it will automatically allow in the outbound.
no need to add addtional rule in the outbound.

We cant block specific ip address with security groups we can only block specific ip addresses with NACL only.

We can have a private and public subnet 

We can connect to the private subnet to the public subnet.

internet------> internetgateway ------------> routetable -----------> NACL -----------------> subnet ------------> security group ------------> instances

Inorder to set the VPC ip address range we have to set the we can use the cidr.xyz for the ip address confirmation.


There is mainly two types of VPC which are default VPC and custom VPC.

VPC can peer together this is called VPC peering.

VPC peering communicate with private addresses

We can peer VPCs in different regions and other aws accounts and other VPCs in the same account.

it is not transitive. we need to configure each VPC to peer with other VPC.

We have to configure individual connection between them for the peering connections.

1 subnet = 1 AZ




