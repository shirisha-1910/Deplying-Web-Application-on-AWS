# Portfolio Deployment on AWS

## Introduction

This project documents the step-by-step process of deploying a portfolio website on AWS EC2 using the Apache HTTP Server. The portfolio consists of a single HTML file named `s-port.html`, which showcases work and skills.

## Features

- Deploy a portfolio website on AWS EC2
- Configure Apache HTTP Server to serve the `s-port.html` file
- Secure the server with appropriate security groups
- Easily accessible portfolio link

## Technologies Used

- AWS EC2
- Apache HTTP Server

## Installation

1. **Launch AWS EC2 Instance**:
   - Choose the desired instance type, operating system, and other configuration options.
   - Allocate appropriate storage and networking resources.
   - Configure security groups to allow inbound traffic on port 80 (HTTP).

2. **Connect to EC2 Instance**:
   - Use SSH to connect to your EC2 instance from your local machine or terminal.

3. **Install Apache HTTP Server**:
   - Update package repositories: `sudo yum update`.
   - Install Apache HTTP Server: `sudo yum install httpd`.

4. **Upload Portfolio Files**:
   - Transfer the `s-port.html` file to the `/var/www/html` directory on the EC2 instance.

5. **Start Apache Server**:
   - Start the Apache server: `sudo systemctl start httpd`.
   - Optionally, enable Apache to start on boot: `sudo systemctl enable httpd`.

## Usage

Once the deployment is complete, we can access our portfolio website by entering the public IP address or domain name of our AWS EC2 instance in a web browser. The portfolio page (`s-port.html`) will be served by the Apache HTTP Server.

- [Link to Portfolio Page](s-port(portfolio)/s-port.html)

## Conclusion

With the completion of this deployment process, our portfolio website is now successfully hosted on AWS EC2. 




