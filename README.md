# AWSWebsiteProject

1-a) configure security group for ssh, http and https. 
1)launch EC2 Amazon Linux and ssh two instance.
2) update instance
3) install and configure git
4) Install and configure apache2 server
5) save index.html page in /var/www/html
6) search for basic index.html code and hosted
7) copy public ip on instance and paste in browser

=>Commands : sudo yum update -y
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
sudo usermod -a -G apache ec2-user
sudo chmod 777 /var/www/html
cd /var/www/html
touch index.html
sudo nano index.html
cat index.html
history



echo "# AWS-Website-Project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/gitbilal123/AWS-Website-Project.git
git push -u origin main


