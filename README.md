# Task14.3

See whether the Configuration file of ansible is properly or not 

**Provides the IP of the instances **

**WebServer** 
A web server is a computer that runs websites. It's a computer program that distributes web pages as they are requisitioned. The basic objective of the web server is to store, process and deliver web pages to the users. This intercommunication is done using Hypertext Transfer Protocol (HTTP). These web pages are mostly static content that includes HTML documents, images, style sheets, test etc. Apart from HTTP, a web server also supports SMTP (Simple Mail transfer Protocol) and FTP (File Transfer Protocol) protocol for emailing and for file transfer and storage.


**SETTING UP THE APACHE HTTP WEB SERVER**

Redhat 

1. A web server is a network service that serves content to a client over the web. This typically means web pages, but any other documents can be served as well. Web servers are also known as HTTP servers, as they use the hypertext transport protocol (HTTP).

2. The Apache HTTP Server, httpd, is an open source web server developed by the Apache Software Foundation.

**Managing the httpd service**
This section describes hot to start, stop, and restart the httpd service.

Prerequisites

The Apache HTTP Server is installed
Procedure

To start the httpd service, enter:

# systemctl start httpd
To stop the httpd service, enter:

# systemctl stop httpd
To restart the httpd service, enter:

# systemctl restart httpd

erification steps

Connect with a web browser to http://server_IP_or_host_name/.


Ubuntu 

Introduction
The Apache HTTP server is the most widely-used web server in the world. It provides many powerful features including dynamically loadable modules, robust media support, and extensive integration with other popular software.

Prerequisites
Before you begin this guide, you should have a regular, non-root user with sudo privileges configured on your server. Additionally, you will need to enable a basic firewall to block non-essential ports. You can learn how to configure a regular user account and set up a firewall for your server by following our Initial server setup guide for Ubuntu 20.04.

When you have an account available, log in as your non-root user to begin.

Step 1 — Installing Apache
Apache is available within Ubuntu’s default software repositories, making it possible to install it using conventional package management tools.

Let’s begin by updating the local package index to reflect the latest upstream changes:

sudo apt update
 
Then, install the apache2 package:

sudo apt install apache2
 
After confirming the installation, apt will install Apache and all required dependencies


