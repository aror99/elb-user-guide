# What is Elastic Load Balancing?<a name="what-is-load-balancing"></a>

Elastic Load Balancing automatically distributes your incoming traffic across multiple targets, such as EC2 instances, containers, and IP addresses, in one or more Availability Zones\. It monitors the health of its registered targets, and routes traffic only to the healthy targets\. Elastic Load Balancing scales your load balancer as your incoming traffic changes over time\. It can automatically scale to the vast majority of workloads\.

## Features of Elastic Load Balancing<a name="elb-features"></a>

Elastic Load Balancing supports the following load balancers: Application Load Balancers, Network Load Balancers, Gateway Load Balancers, and Classic Load Balancers\. 


## Accessing Elastic Load Balancing<a name="elb-access-methods"></a>

You can create, access, and manage your load balancers using any of the following interfaces:
+ **AWS Management Console**
+ **AWS Command Line Interface \(AWS CLI\)**
+ **AWS SDKs**
+ **Query API**— Provides low\-level API actions that you call using HTTPS requests\. Using the Query API is the most direct way to access Elastic Load Balancing\. However, the Query API requires that your application handle low\-level details such as generating the hash to sign the request, and error handling\. For more information, see the following:
  + Application Load Balancers and Network Load Balancers — [API version 2015\-12\-01](https://docs.aws.amazon.com/elasticloadbalancing/latest/APIReference/)
  + Classic Load Balancers — [API version 2012\-06\-01](https://docs.aws.amazon.com/elasticloadbalancing/2012-06-01/APIReference/)

## Related services<a name="elb-related-services"></a>

Elastic Load Balancing works with the following services to improve the availability and scalability of your applications\.
+ **Amazon EC2**
+ **Amazon EC2 Auto Scaling**
+ **AWS Certificate Manager** — When you create an HTTPS listener, you can specify certificates provided by ACM\. The load balancer uses certificates to terminate connections and decrypt requests from clients\.
+ **Amazon CloudWatch**
+ **Amazon ECS**
+ **AWS Global Accelerator** — Improves the availability and performance of your application\. Use an accelerator to distribute traffic across multiple load balancers in one or more AWS Regions\.
+ **Route 53**
+ **AWS WAF** — You can use AWS WAF with your Application Load Balancer to allow or block requests based on the rules in a web access control list \(web ACL\)\. 

## Pricing<a name="load-balancer-pricing"></a>

For more information, see [Elastic Load Balancing pricing](https://aws.amazon.com/elasticloadbalancing/pricing/)\.
