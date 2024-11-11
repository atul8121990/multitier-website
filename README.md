i declare all the steps in my doc file. Deploying a Multi-Tier Website Using AWS EC2
Steps include 
Problem Statement: 
Company ABC wants to move their product to AWS. They have the following things set up right now: 
1.	MySQL DB 
2.	Website (PHP) 

                 The Company wants high availability on this product, therefore wants Auto Scaling to be enabled on this website. 
Steps To Solve: 
1. Launch an EC2 Instance 
2. Enable Auto Scaling on these instances (minimum 2) 



3.	Create an RDS Instance 


4. Create Database & Table in RDS instance: 
      a. Database name:  Intel
      b. Table name: data
      c. Database password: intel123

4.	Change hostname in website.


5.	Allow traffic from EC2 to RDS instance.



6.	Allow all-traffic to EC2 instance.
