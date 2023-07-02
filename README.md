# MS SQL Database Management System

## Introduction

This repository contains the work I've done for the AWS EC2 project. The project involved various tasks related to AWS services, including creating and managing VPCs, EC2 instances, EBS snapshots, RDS databases, and setting up auto scaling with load balancing.

## Project Description

The AWS Labs project was a comprehensive exercise designed to provide hands-on experience with various AWS services. The project was divided into four labs, each focusing on different aspects of AWS.

Throughout the project, I had to interact with various AWS services and perform tasks such as resizing instances, testing termination protection, and interacting with databases. The project provided a practical understanding of how to work with AWS services and how to manage cloud resources effectively.

## Steps Involved

1. Add user-1 to the S3-Support Group: This was the first step in setting up the environment for the project. I added a user to the S3-Support Group to manage the S3 resources.

2. Add user-2 to the EC2-Support Group: I added another user to the EC2-Support Group. This user was responsible for managing the EC2 instances.

3. VPC: I created a VPC (Virtual Private Cloud) to provide a secure environment for the AWS resources that I was going to use in the project.

4. Additional Subnets: After creating the VPC, I created additional subnets. This was necessary to ensure that the resources were distributed across different Availability Zones for high availability and fault tolerance.

5. Amazon EC2 Instance: I launched an EC2 instance within the VPC. This was a bit challenging as I had to ensure that the security group rules allowed HTTP traffic to the web server.

6. Monitor: I monitored the EC2 instance to ensure it was working correctly and to understand its performance characteristics.

7. New EBS Volume: I created an EBS volume. This was necessary to provide persistent block storage for the EC2 instance.

8. Attach: I attached the EBS volume to the EC2 instance. This allowed the instance to use the volume for storage.

9. Connect: I connected to the EC2 instance to verify that it was working correctly.

10. Auto Scaling: I created an Amazon Machine Image (AMI) from an existing EC2 instance. This AMI was used to launch new instances when scaling out.

11. Load Balancer: I set up a load balancer to distribute incoming application traffic across multiple EC2 instances. It was a bit tricky to get the health checks configured correctly, but after a few tries, I got it working.

12. Launch Configuration and an Auto Scaling Group: I created a launch configuration with the AMI and instance type that the auto scaling group uses to launch instances. I then created an auto scaling group to ensure that the number of instances scales in or out depending on the load.

13. Verify: I verified that the load balancing was working correctly by checking the distribution of traffic across the instances.

## Challenges
The project was quite challenging, especially when it came to configuring the security groups and setting up the load balancer. However, with some trial and error, I was able to overcome these challenges. The project was a great learning experience and helped me understand the practical aspects of working with AWS services.

## Future Work
In the future, I plan to explore more AWS services and apply the knowledge gained from this project to real-world applications. I also plan to improve my understanding of auto scaling and load balancing as these are crucial for building scalable and highly available applications.

## Acknowledgements
I would like to thank my professors and peers for their guidance and support throughout this project. I would also like to thank AWS for providing the resources needed to complete this project.

## Disclaimer
Please note that this project was done as part of my university coursework and is not intended for production use. Always follow best practices when working with AWS services in a production environment.

## License
This project is licensed underthe MIT License. See the LICENSE file for details.

## Contact
If you have any questions or feedback, feel free to reach out to me. You can also raise an issue in this repository.

## Contributions
Contributions are welcome! If you have any ideas or improvements, feel free to make a pull request.

Remember, this project was a part of my learning journey, and I encourage you to use it as a part of yours.
