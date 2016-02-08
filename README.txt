1) Instructions to evaluate the published work done(e.g. AWS  account credentials)

URL :-    https://moingodil.signin.aws.amazon.com/console
username :- Viewer
Password :- p0*Dj*OgRFK* 

2)Assumptions you have made - it is good to explain your thought process and the assumptions you have made

-> This template assumes you have created an EC2 Keypair for SSH Access
-> We are not using route53 for creating failover in case of ELB failure as it requires a domain name
-> We are going to use Amazon linux and Mysql for this template


3) Requirements that you have not covered in your submission,

-> Data Recovry should pe part of the requirement

4) Issues you have faced while completing the assignment, if any

-> Applying NetworkACLEntry to DB Subnet it says non numeric value for port. but i have given correct value same can be viewed in /design/dbnetworkAcls.json

5) Constructive feedback for improving the assignment

-> There are many ways to solve this project. One ways is code on github the way i implemented, other ways are using Codecommit or S3. We can also build a customAMI and have a code on S3 but as it ways said "empty AWS account to start" so i didnt created any AMI. The constructive Feedback is guide us which way shall we go public repository like github, private like codecommit or combination of custom AMI + s3 or S3.
  