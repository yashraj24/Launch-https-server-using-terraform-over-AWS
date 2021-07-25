This repo contains code to launch a Apache webserver over AWS ec2 instance.
We have also launched a EBS volume and attached it to the launched AWS ec2 instance.
We have stored our very basic "php" on the above created EBS volume. This will give more data security to the page. Even if the EC2 instance shuts down or terminates we will not lose our datas of php page.
We have also written code to clone a github repo into the mounted EBS volume. 
