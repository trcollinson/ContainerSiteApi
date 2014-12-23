ContainerSiteApi
================

##What is this Container Site all about?

There are a number of solutions available for creating a web site with such things as content management, blogging, email address collection and management, and email marketing systems. However, many of these systems do not use industry leading best practices when it comes to testing, deployment, scaling, and operations management. This set of projects will work together to provide these features with a continual look towards industry best practices. 

###What are some the features that set you apart:

We aren't innovating as much as we are simply showing best practices in a number of key areas:

- Test Driven Development mentality
- Continuous Integration of changes
- Completely separate Front End and Back End API systems
- Containerized server deployments

###What are the projects?

**Container Site API:** This is a pure restful backend api for a content management system, blog, email address collection and management, and email marketing system. There is no front end, display, system tightly tied to this API. The API is built using Ruby and Ruby on Rails. By deploying it you can quickly have a full featured, tested system to handle all of these tasks for yourself. Build your own beautiful front end and connect to this API system or use the Container Site Frontend!

**Container Site Front End:** This is a completely independent front end for a content managed, blog style site which has the functionality needed to collect and manage user email addresses, and an email marketing system. This system is built using AngularJS. It hooks into the Container Site API but could easily use any API system that matches the well documented API signatures. Because the API connections are quite well documented, tested, and are separated from the sites business logic and view logic, they can be quickly changed to call other API systems easily.

**Docker Based Deployments:** We believe in quick, reliable, testable, and scalable deployment models. The Container Site API utilizes Docker to implement this level of deployment and DevOps. Feel free to push the API to any Docker enabled deployment environment, even locally! We'll even show you how to scale it on services like AWS Elastic Beanstalk.

**Compiled, Static Storage Front End Deployments:** Our Container Site Front End can easily be deployed to any static file storage environment for quick, distributed, and low cost distribution to your users. Grab a copy and with a few clicks you'll be able to deploy to storage environments like AWS S3.

**Continuous Integration:** By having our continuous integration environment, utilizing Jenkins, within a Docker container, you can use it as well. Want to make changes to the API or the Front end and quickly test the same way we do? Deploy the continuous integration container, make a few minor configuration changes, and you'll be testing. You can even use it on your own independent projects quickly and easily.


##How to contribute

We love contributors! We actively support anyone who would like to add or update within the Container Site Ecosystem. Check out our ["How to Contribute"](https://github.com/trcollinson/ContainerSiteApi/wiki/How-to-Contribute) section within the wiki to get started.
