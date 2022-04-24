#  React App Static Website Hosting in AWS with Cloudfront distribution

##  Why hosting static website in S3.

Amazon S3 provides easy-to-use management features so onecan organize the data and configure finely-tuned 
access controls to meet the desired business needs. Amazon S3 is designed for 99.999999999% (11 9’s) of durability and
99.99%(4 9's) availability over a given year

Among other reasons the top two are...

Easy set-up : Deploying static files requires a lot less moving parts than an app with a server. There’s less to set up and less to maintain.

Cost- optimized:  Because there’s less to set up and maintain, the cost of deploying a static application can be dramatically cheaper.

## Below is the Architecture Diagram that I designed with and without cloudfront distribution to deploy the static website;

![AWS S3 Static Website Hosting drawio](https://user-images.githubusercontent.com/75151805/164999689-dd29fd37-6842-4cf8-a5f9-4fac8abb1c08.png)

## AWS Services I used :
* S3 Bucket
* Route 53
* Certificate Manager
* Cloudfront Distribution

### Steps to deploy the React-App through Cloudfront distribution using windows desktop
 1. Download NodeJS application
 2. Create React-app using (create-react-app) command from a windows terminal
 3. Once a new application kicked off , (npm run build) command will optimize, compile, and dump the static files required to serve the application in a build directory.
 4. 
