# Microservice Deployment on Virtual Machines using VirtualBox

## Overview
This project involves creating and configuring multiple Windows 10 Virtual Machines (VMs) using VirtualBox, establishing a network connection between them, and deploying a microservice-based application. The setup consists of a RESTful API built with Node.js and a MongoDB database running on separate VMs, simulating a distributed system.

## System Requirements
- VirtualBox (with Extension Pack)
- Two Windows 10 VMs
- Node.js (for API development)
- MongoDB (for database storage)
- Postman (for API testing)

## Setup Steps
1. Install VirtualBox and create two Windows 10 VMs.
2. Configure Networking: Set both VMs to use a Host-Only Adapter.
3. Install Node.js on VM1 and set up an Express.js API.
4. Install MongoDB on VM2 and configure remote access.
5. Deploy the Application: Connect the API to MongoDB and start the service.

## Testing
- Verify the API by sending a request to `http://<VM1-IP>:3000/`
- Use Postman or `curl` to test connectivity.
- Check MongoDB connection from VM1.

## Conclusion
This setup successfully demonstrates the use of VirtualBox for hosting microservices, providing practical experience in VM networking, backend service deployment, and distributed application management.
