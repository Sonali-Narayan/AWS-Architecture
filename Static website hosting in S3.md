#  React App Static Website Hosting in AWS with Cloudfront distribution

##  Why hosting static website in S3.

Amazon S3 provides easy-to-use management features so onecan organize the data and configure finely-tuned 
access controls to meet the desired business needs. Amazon S3 is designed for 99.999999999% (11 9’s) of durability and
99.99%(4 9's) availability over a given year

Among other reasons the top two are...

Ease set-up : Deploying static files requires a lot less moving parts than an app with a server. There’s less to set up and less to maintain.
Cost- optimized:  Because there’s less to set up and maintain, the cost of deploying a static application can be dramatically cheaper.

## Below is the Architecture diagram that I designed with and without cloudfront distribution

### Why do we need a three tier architecture? 
* The key benefit of three-tier architecture is that because each tier runs on its own infrastructure, each tier can be developed simultaneously by a separate development team, and can be updated or scaled as needed without impacting the other tiers.

* The de-coupling between the tiers help the teams to focus on specific tiers and make changes as quickly as possible. It brings ease of maintenance and also helps to quickly recover from an unexpected failure by focusing only on the faulty module.

* It also strengthens the overall security of any modern application by exposing the web servers to the internet traffic while the application servers with business logic are isolated and can only be accessed by the web servers internally. Similarly the data persistence layer is also separated and can only be accessed by the application servers.

#### Below is the diagram that I designed to create the three-tier architecture in AWS Management console
