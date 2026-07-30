🎯 Objective: Build a small load-balanced Apache web cluster on AWS EC2, capturing a working server as a reusable AMI, deploying a synced replica, and distributing traffic between them with iptables.

🛠️ What was used
- AWS EC2, AMIs, EBS, Security Groups
- Apache HTTP Server (Amazon Linux 2023)
- SSH key-based authentication
- rsync
- cron
- iptables (NAT/DNAT, statistic module)

💡 What was learned: Gained hands-on experience with the mechanics behind horizontal scaling, image-based server provisioning, automated bidirectional content sync, and traffic distribution using iptables NAT rules (The same underlying primitives production load balancers build on).
