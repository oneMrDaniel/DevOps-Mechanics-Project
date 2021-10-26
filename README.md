# DevOps-Mechanics-Project

Write a python program for a simple task (maybe a web app or preferably a web scraper which is most common in DevOps), regardless of what it is and deploy to the cloud (you can fork a project from github as well if you dont want to build). 

The website/application/scraper would be accessible on HTTP and HTTPS servers over the public internet. Ensure to push the application to GitHub with clear/concise commit messages with of course a standard readme file. The servers should all be Linux servers and should be tagged for proper billing follow-up. Your application should be highly available on different AZs. 

## Expectations

- Draw an architecture for deployments (you can use draw.io or something you prefer)
- It should be a full-stack application or a web scraper.
- IAM roles must be clearly defined and privileges not dashed around. 
- Use an EC2 instance with Linux distro so we can check logs at any time 
- Make the instances available on at least two AZs so if one goes down, the other is available.
- Setup alerting with cloudwatch so in case an instance fails, we will get an alert via email/slack - you can use lambda functions, sns topics and the likes
- Github must have a clear README on how to replicate the application and process. You can check my GitHub for some directives.
- All AWS resources must be set up manually and correct ports exposed (this is on purpose and to help appreciate phase 2 of this training).
- Collect logs from cloudwatch to s3 buckets at intervals.
- Finally, security must be taken seriously as I’d have some security checks. 
- If there are other things you think would make the project more interesting then add it up; testing and others.  
- I’d like to track your changes so everyone should setup github projects. 
- SECURITY: For security purposes, ensure that your VPC is only accessible within the VPC (you can use VPN trunking and many other ways). Also, do some nice stuff with security groups (inbound/outbound rules), gateways, static IPs and proper IAM permissions. 

## Note

Finally, you must do documentation via GitHub gist, Notion or Wiki page of everything you did (this is aside from the GitHub readme). Also, your architecture must be scalable and reliable with industry-standard rules thrown around every part of the project. 

I wish you the best. 
