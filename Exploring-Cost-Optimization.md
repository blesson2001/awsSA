AWS cost optimization:-
This is one of the five pillers in the well architected framework and it is the ability to run systems to deliver 
business values at the lowest price.

AWS provide multiple service 

AWS Budgets
AWS Cost and Usage Reports
AWS cost explorer
Reserved instance reporting


Spot instances
Reserved instances
Amazon simple storage service
Amazon s3 glacier
AWS lambda 
Autoscaling

AWS trusted advisor
AWS cost and usage
AWS cost explorer

What are the five pillars of Cost Optimization?

Five pillers of the cost optimization

1)Right sizing
Right sizing is the picking the correct instance for our current resources as well as resources we plan to use.
So may be we are using a larger ec2 instance size when all we need to cover our demand is a small instance size.
We can save money by right sizing and choosing the correct instance type, but also cheapest instance type that meets 
our performance requirements.

2) Elactisity:-

Increaseing elasticity means using autoscaling  to only use resources when those resources are needed,and not using resources
when they are not needed. This gives us a pay-for-what-you-use model.


autoscaling+horizotalscaling

verticalscaling=increases instance size
horizoltalscaling=use more smaller instances

3)Choose the right pricing model:-

AWS offers several different pricing models,reserved instances,on-demand instances, and spot instances

On-demand instance:-
You can choose when it needed.

Reserved instances:-
You can save money chooseing reserved instances
The reserved instances come with 3 year or 4 year commitment within that commitment you can receive instances at lower price.

Spot-instances:-
This is better when we have a flexible start and in time.

AWS trusted advisor:-

This will monitor our instance and recommand how to make our infrastucture more optimized.

AWS cost explorer:-

To monitor the cost.

4)Match storage to Usage:-
Reducing out storage can save money beacuse we can match our storage usage to a certain storage class 
AWS offers multiple storage classes and we need to make sure we pick the correct one.

AWS multiple storage options:-

S3 - simple storage service
EBS- Elastic block storage
Amazon storage Gateway
EFS - Amazon Elastic File storage
AWS snowmobile
AWS snowball 
AWS backup


5)Measure,monitor and Improve
The infrastucture will most likily change so we need measure in place to monitor and track our usage and costs.
this mainly used to monitor the CPU,memory
For this purpose amazon use like

a)Amazon cloudwatch
This allow us to set alarms
we can immediatly take actions in the prodution environment.

b)AWS Trusted advisor
c)AWS cost explorer
We have to use cost allocation tags


AWS cost optimization piller: Design principles
i) Adopt a consumption model
pay for what you consume

ii)Measure overall efficiency
Define and track your metrics and goals

iii)Stop spending money on data centers.

iV) Analyze and attribute expenditure

v) Use AWS -managed services
Reduce overall cost of ownership



AWS cost optimization: Best practices:-
Tagging stratagy -- see what resource are costing more

Define your account structure -- To know your goals, and define metrics to track progress

Ownership of costs:-

How do we hold engineers resposible?


