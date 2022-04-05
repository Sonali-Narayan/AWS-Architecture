# AWS- Three-Tier Architecture

##  Three-tier Architecture verview  

The three-tier architecture is the most popular implementation of a multi-tier architecture and consists of a single presentation tier, logic tier, and data tier. The following illustration shows an example of a simple, generic three-tier application.

![image](https://user-images.githubusercontent.com/75151805/161612792-71ea1a41-8e3c-483a-ab47-1a12b3539a0a.png)

### Why do we need a three tier architecture? 
* The key benefit of three-tier architecture is that because each tier runs on its own infrastructure, each tier can be developed simultaneously by a separate development team, and can be updated or scaled as needed without impacting the other tiers.

* The de-coupling between the tiers help the teams to focus on specific tiers and make changes as quickly as possible. It brings ease of maintenance and also helps to quickly recover from an unexpected failure by focusing only on the faulty module.

* It also strengthens the overall security of any modern application by exposing the web servers to the internet traffic while the application servers with business logic are isolated and can only be accessed by the web servers internally. Similarly the data persistence layer is also separated and can only be accessed by the application servers.

#### Below is the diagram that I created to create the three-tier architecture in AWS Management console

![Three-Tier-Architecture-Network](https://user-images.githubusercontent.com/75151805/161828591-5274b05b-7c14-473a-8882-8fb9db067b45.png)


![Three-Tier-Architecture-App](https://user-images.githubusercontent.com/75151805/161828711-744b7135-8436-46e1-8fee-d8fa57015e8d.png)

### AWS Services I Used 

* VPC
* EC2
* Nat Gateway
* Internet Gateway
* Autoscaling
* Route Table
* Application Load Balancer
* RDS

### How To Create The Three-Tier Architecture In AWS Console
 1. Create a VPC
 2. Create Public and Private Sunbet in multiple availability zones.
 3. Create route tables and open the appropriare route.
 4. Create NAT Gateway in public subnet.
 5. Create Internet Gateway.
 6. Create and Provision EC2 instances in web and app tier with autoscaling groups.
 7. Setting up application load balancer for web and app tier.
 8. Create and provision RDS instance with read replica.
 9. Set up the DNS service with Route 53.
 10. 
