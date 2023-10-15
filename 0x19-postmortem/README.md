ISSUE SUMMARY

Duration of outage: 15th of October, 2023. 6:00am WAT till 16th of October, 2023. 4:32pm Impact: The web server was down and not receiving requests. All requests were sent to the other servers. Root cause: Nginx was not listening on port 80 Resolution: edited the nginx configuration file correctly to listen on port 80. 

TIMELINE 16th of October,2023. 6:00am – Issue detected. A monitoring alert was received. 16th of October , 2023. 3:39pm – using netstat tool to check if nginx was listening on port 80, checking permissions of the firewall. 15th of October l, 2023. 2:58pm – disabled firewall and re-enabled it. Restart nginx 16th of October, 2023. 3:08pm – discovered nginx was not listening on port 80 16th of October, 2023. 4:02pm – edited nginx.conf file and corrected the listening port. 16th of October, 2023. 4:20pm – restarted nginx. Incident was resolved. 

