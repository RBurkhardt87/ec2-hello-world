# Hello World from EC2

This is a simple HTML "Hello World" page I created to practice launching and configuring an EC2 instance on AWS.

## What I Learned

- How to launch a Windows EC2 instance
- How to configure security groups
- How to connect via Remote Desktop
- How to install and use IIS (Windows web server)
- How to deploy a basic web page to the server

## Tools Used

- AWS EC2 (Windows Server 2025 Base, t3.micro)
- IIS (Internet Information Services)
- Visual Studio Code (local)
- Git & GitHub


## Deployment and Updating

- I deployed this page on a Windows EC2 instance using IIS (Internet Information Services).
- I cloned the project from GitHub directly onto the EC2 instance using Git.
- To update the site, 
        1. I push changes from my local machine to GitHub
        2. Connect to the EC2 instance via Remote Desktop
        3. Run "git pull" to sync the latest code.


## Next Steps

- Try uploading more complex sites
- Automate deployment from GitHub to EC2
- Explore using Amazon Linux EC2 with NGINX or Apache
