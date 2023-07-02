# AWS

## Introduction

This repository contains the work I've done for the AWS project. The project involved various tasks related to AWS services, including creating and managing VPCs, EC2 instances, EBS snapshots, RDS databases, and setting up auto scaling with load balancing.

## Project Description

The AWS project was a comprehensive exercise designed to provide hands-on experience with various AWS services. Throughout the project, I had to interact with various AWS services and perform tasks such as resizing instances, testing termination protection, and interacting with databases. The project provided a practical understanding of how to work with AWS services and how to manage cloud resources effectively.

## Project Overview

1. Create a VPC and Additional Subnets: This was the first step in setting up the environment for the project. I created a VPC (Virtual Private Cloud) and additional subnets to provide a secure environment for the AWS resources.

2. Launch an Amazon EC2 Instance: I launched an EC2 instance within the VPC and installed a web server on it. This was a bit challenging as I had to ensure that the security group rules allowed HTTP traffic to the web server.

3. Monitor the EC2 Instance: I monitored the EC2 instance to understand its performance and to ensure that it was functioning as expected.

4. New EBS Volume: I created a new EBS volume and attached it to the EC2 instance. This allowed me to increase the storage capacity of the instance.

5. Security Group and a DB Subnet Group for the RDS DB Instance: I designed a security group and a DB subnet group for the RDS DB instance. This was necessary to ensure the security and proper functioning of the database.

6. Amazon RDS DB Instance: I managed an Amazon RDS DB instance. This was a bit challenging as I had to ensure that the instance was properly configured and that it could connect to the EC2 instance.

7. AMI for Auto Scaling: I retrieved an Amazon Machine Image (AMI) from an existing EC2 instance. This AMI was used to launch new instances when scaling out.

8. Create a Load Balancer: I set up a load balancer to distribute incoming application traffic across multiple EC2 instances. It was a bit tricky to get the health checks configured correctly, but after a few tries, I got it working.

## Challenges
The project was quite challenging, especially when it came to configuring the security groups and setting up the load balancer. However, with some trial and error, I was able to overcome these challenges. The project was a great learning experience and helped me understand the practical aspects of working with AWS services.

## Future Work

In the future, I plan to explore more AWS services and apply the knowledge gained from this project to real-world applications. I also plan to improve my understanding of auto scaling and load balancing as these are crucial for building scalable and highly available applications.

## Conclusion

This project was a fantastic opportunity to delve into the practical aspects of AWS services. It was challenging, yet rewarding, and it provided a solid foundation for understanding how to build and manage cloud resources effectively. The hands-on experience of setting up a VPC, launching and managing EC2 instances, working with EBS volumes, and implementing auto scaling and load balancing was invaluable.

Through the course of this project, I not only learned about the technical aspects of AWS but also about problem-solving and debugging when things didn't go as expected. It was a testament to the fact that real learning happens when you get your hands dirty.

I look forward to applying the skills and knowledge gained from this project to future endeavors in cloud computing. I hope that this repository serves as a useful reference for other students embarking on their journey in AWS.

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
