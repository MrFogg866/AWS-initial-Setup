## How to create EC2 server in AWS


### The 15 Steps to follow are: 


1. First login to AWS and select the Region Ireland
2. Then type in EC2 into the Searcher bringing up the Dash board
3. Select orange button “ Launch instance” without template unless you have a template 
4. Create a name for the Instance 
5. select “browse more AMI’S” and find the server UBUNTU 20.04 and hit select
6. then choose the “instance type” t2.micro 
7. then search for “key pair” “tech221”
8. in network settings we then want to create security group and also select “Allow HTTP traffic from the Internet”
9. after these are selected in the same area “Network setting” we can go to edit and rename the security group
10. once this is done we click “launch instance”
11. once the instance is launch go to the dash board and select instances (running)
12. Select your one and go to connect
13. Then in bash goto the .ssh folder and type  - chmod 400 tech221.pem
14. Then copy the example and paste that into bash.
15. It may ask you to approve yes/no type yes then  should see ubuntu ip.
