# 0x0F. Load balancer
# Done by : Temesgen Abdissa
# project overview 
In the world of DevOps and SysAdmin, the task of configuring and managing load balancers is crucial for ensuring the scalability and reliability of web applications. In this particular project, we are presented with the opportunity to enhance our web stack by introducing redundancy for our web servers. The addition of two new servers, gc-[STUDENT_ID]-web-02-XXXXXXXXXX and gc-[STUDENT_ID]-lb-01-XXXXXXXXXX, allows us to double the number of web servers, thereby increasing our capacity to handle incoming traffic and ensuring high availability. Load balancers play a pivotal role in this setup, distributing incoming requests efficiently between the web servers. The use of Bash scripts for automation is essential, as they will enable us to configure brand new Ubuntu servers to meet the project's requirements seamlessly. These scripts, when executed, will ensure that our load balancer and web servers are set up correctly, creating a robust and redundant infrastructure that can handle traffic spikes and recover from server failures. This project exemplifies the intersection of DevOps and SysAdmin roles in maintaining a highly available and scalable web application infrastructure.

# Requirements
# General
Allowed editors: vi, vim, emacs
All your files will be interpreted on Ubuntu 16.04 LTS
All your files should end with a new line
A README.md file, at the root of the folder of the project, is mandatory
All your Bash script files must be executable
Your Bash script must pass Shellcheck (version 0.3.7) without any error
The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
The second line of all your Bash scripts should be a comment explaining what is the script doing
