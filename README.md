# AWS- Three-Tier Architecture

##  Three-tier Architecture verview  

The three-tier architecture is the most popular implementation of a multi-tier architecture and consists of a single presentation tier, logic tier, and data tier. The following illustration shows an example of a simple, generic three-tier application.

![image](https://user-images.githubusercontent.com/75151805/161612792-71ea1a41-8e3c-483a-ab47-1a12b3539a0a.png)

### Why do we need a three tier architecture? 
* The key benefit of three-tier architecture is that because each tier runs on its own infrastructure, each tier can be developed simultaneously by a separate development team, and can be updated or scaled as needed without impacting the other tiers.

* The de-coupling between the tiers help the teams to focus on specific tiers and make changes as quickly as possible. It brings ease of maintenance and also helps to quickly recover from an unexpected failure by focusing only on the faulty module.

* It also strengthens the overall security of any modern application by exposing the web servers to the internet traffic while the application servers with business logic are isolated and can only be accessed by the web servers internally. Similarly the data persistence layer is also separated and can only be accessed by the application servers.

#### Below is the diagram that I created to create the three-tier architecture in AWS Management console

![](https://github.com/Sonali-Narayan/AWS-Architecture/tree/main/Image/Three-Tier-Architecture-Network.png) 


