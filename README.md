# Ram Hemareddy AWS CICD Pipeline Code Deployment to AWS EC2 Instance


<b>User Data for Dependencies installations for ubuntu:-</b>

#!/bin/bash<br />
sudo apt -y update<br />
sudo apt -y install ruby<br />
sudo apt -y install wget<br />
cd /home/ec2-user<br />
wget https://aws-codedeploy-ap-south-1.s3.ap-south-1.amazonaws.com/latest/install<br />
sudo chmod +x ./install<br />
sudo ./install auto<br />
sudo apt install -y python3-pip<br />
sudo pip install awscli<br />
