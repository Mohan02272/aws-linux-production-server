## Architecture Overview

This project deploys a secure Linux server on AWS using a single EC2 instance.

### Components
- AWS EC2 (Ubuntu 22.04)
- AWS Security Group for network-level firewall
- Linux UFW firewall for host-level security
- Nginx web server

### Traffic Flow
User requests pass through AWS Security Group, then reach the EC2 instance where Nginx serves the application.
