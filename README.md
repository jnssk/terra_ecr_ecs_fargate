# terra_ecr_ecs_fargate

# Just copy and paste your access_key and secret_key in main.tf then
  1) terraform init
  2) terraform validate
  3) terraform plan
  4) terraform apply
  

this repo contains how to create the ecs,ecr,faragte,alb.

Note: in this terraform , i used provisinor ie Local , so before proceed you have to install 
 1) aws_cli
    1) curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
    2) unzip awscliv2.zip
    3) sudo ./aws/install
 2) Docker 
   1) curl https://get.docker.com/ | bash
   2) sudo systemctl satrt docker
   3) sudo systemctl enable docker
   4) sudo systemctl status docker
   5) sudo usermod -aG Docker ubuntu
 3) iam_role or user
   1) attach ecr and ecs full access
    

--> project file is in /project (contains dockerfile and requried node code)
--> if you want to change port number change in main.tf


< all the best > 

sudeep y
