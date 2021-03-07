How does AWS do this?


What is the AWS Global Infrastructure?
This is the smaller groupings of infrastucture connected by a global high speed network. This system allow us to create resilient and highly available services.
AWS offers a lot global resilient services and it offers regional resilient services and zone resilient services.


what is global resilent service?
This is the system which operates globally.
example: A database that replicate across regions. IAM and route 53,S3  are the main global resilient services.

What is regional resilent services?
This is the services which replicate across the multiple availability zone inside a region.

What availabile resilient services?
This are the services which are in the single availablity zones. If that availabily zone fails so that the service as well.

What is a AWS region?
This is a geographical area which consist of two or more availablity zones. There are several regions us region london region,asia region.
each region has specific roles.

The data will stay in the region unless we move the data in to another region.
We can  see some countries has muiltiple region.
Each regions are fault tolarent.


What is availablity zones?
This is the more than one data center with power,Networking connectivity and seperate facilities(switchs,firewalls,servers etc..). These are the isolated compute storage,
network which distribute our infrastucture with multiple availabilty zones inside a region for high availbility.

Thus if one availabilty zone fails then other remains operational. The availabilty zones are isolated from each other and connected with high speed network.
our services can placed in the multiple availability for high resilentcy and high availability.

What is edge locations?
This is the end point of the aws. 

