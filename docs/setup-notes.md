## EC2 Setup
- Launched Ubuntu 22.04 EC2 
- Configured Security Groups
- Connected via SSH using key-based authentication
- Disabled root login
- Enabled UFW firewall
  
## User & Sudo Configuration
- Created a non-root user for administration
- Added user to wheel group 
- Verified sudo access using least-privilege approach

## SSH Hardening
- Disabled root login
- Disabled password authentication

## Firewall Configuration
- Amazon Linux default firewall (firewalld) not available
- Installed iptables-services
- Configured rules to allow SSH(22), HTTP(80), HTTPS(443)
- Default policy: drop all other inbound traffic
