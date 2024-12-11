#Automated Multi-VM Web Application Deployment Project
Overview.

This project demonstrates the deployment of a Java and JavaScript-based web application in a local environment using Oracle VirtualBox, Vagrant, Ansible, and several supporting technologies. The goal is to automate the provisioning and configuration of multiple virtual machines (VMs) to host the application and its dependencies, ensuring efficient setup and scalability.

Architecture Diagram
The architecture includes:

Load Balancer: NGINX
Application Server: Apache Tomcat
Database: MySQL
Caching: Memcached
Messaging Queue: RabbitMQ
Each component is hosted on separate VMs, created and provisioned using Vagrant and automated shell scripts.

Technologies Used
Vagrant: For creating and managing VMs
Oracle VirtualBox: VM provider
Ansible: For automation and configuration management
NGINX: Load balancing and reverse proxy
Apache Tomcat: Hosting the Java-based application
MySQL: Database for persistent storage
RabbitMQ: Messaging queue
Memcached: Caching service
CentOS Stream 9 / Ubuntu: Operating systems for the VMs
Shell Scripts: Automating setup processes for each service
