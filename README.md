# Deploy a Static Web Application on AWS with Docker, ECR and ECS

## A fully functional EXAMPLE cloud project deployed on AWS to practice implementing containerization tools and services  


This project is an example that was built along with a tutorial series from AOSNOTE (www.aosnote.com) that teaches you how to use Docker, Docker Hub, and AWS specific container services such as Amazon ECS and Amazon ECR to deploy a simple static website on AWS. In particular, this project shows how to do the following:


- Create a Dockerfile
- Build the Container Image
- Push the image to your Docker Hub account
- Create an Amazon ECR Repository to store your image
- Push the Image to your ECR Repository
- Creating a custom VPC in AWS (including Public/Private Subnets, NAT Gateways, Application Load Balancer, and Security Groups)
- Create an ECS Cluster
- Deploy the ECS Cluster within the VPC
- Use Route 53 and AWS Certificate Manager to customize DNS route and secure the website

## Architectural Diagram:
![Alt text](project-architecture.jpeg)

## Learning Outcomes 

- This project helped understand some keys concepts regarding containers, and constainerization tools and services. By utilizing Docker, you gain experience in containerizing applications, creating Docker files, and building container images
- Pushing the image to Docker Hub and creating an Amazon ECR repository teaches you about image registries and how to securely store and manage container images in AWS
- Creating a custom VPC with public and private subnets, NAT Gateways, Application Load Balancers, and Security Groups enables you to learn about networking and infrastructure setup in AWS, ensuring secure communication and access control for your application. 
- Deploying an ECS Cluster within the VPC allows you to understand container orchestration, scaling, and load balancing, as well as leveraging AWS services for managing containers. 
- Utilizing Route 53 and AWS Certificate Manager for DNS customization and website security helps you gain skills in domain management and SSL certificate integration
- Overall, this project equips you with practical knowledge in containerization, image management, networking, infrastructure design, container orchestration, scaling, load balancing, DNS management, and website security, providing valuable expertise in cloud architecture and application deployment.