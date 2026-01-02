# VPC
Step 1 :
Create a vpc , igw attacthc igw with the vpc.
Step 2:
Create subnets and then associate it to the route tables and route the igw with the route table
Step 3 :
create the instnace, enable the auto asisign ip and add this code for the page purpose :

"
#!/bin/bash
yum update -y
yum install -y httpd
systemctl start httpd
systemctl enable httpd
echo "<h1>Server 1</h1>" > /var/www/html/index.html

"
Later :
when u run the ip address with the http request u can see the page!!!!!!!!!
wohooo!!!!!!!!!!!
