1. Created Resource group in US and India Region
2. Created Vnet in both Region
3. Created NSG Inbound port rule for port 80 or 443, so users can access our site
4. Added subnet for application gateway in both region
5. Deployed 2 Linux Web Servers in East US Region
6. Deploy 2 Linux Web Servers in Central Region
7. Installed Apache Web Server on each VM
8. Deleted default web page file and add my web page file ( file path-cd /var/www/html) on all server
9. Copy server public IP and paste in to my web browser and successful open my web page
10. Create Application Gateway in each Region so it can balance my web traffic and ensure high availability.
11. Create and configured Traffic Manager for DNS-based traffic routing and reduce latency for Users who exist in different region 
12. Tested low latency routing
13. Verified application accessibility
