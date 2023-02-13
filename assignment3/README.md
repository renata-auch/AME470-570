Directions on how I hosted my resume
URL: http://44.200.211.29:1234/index.html

1. set up your lab by going to the sandbox, clicking Start Lab and then waiting until the AWS dot turns green the click open
2. go to EC2, go to instances and then go to Launch Instances
3. set this up with ubuntu with "Ubuntu Server 20.04 LTS" as the setting, no key value pair, and set the configure storage to be 28 instead of 8, then click launch instance button
4. Go into security, open the security groups link then create a new inbound rules with type:"All traffic" and leave the rest as is
5. once instance is running, open it up
6. copy and paste this into the console 
	> curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
7. Then this
	> nvm install 16
8. Check the git version with 
	> git --version
9. Now clone the github repository, in this case it's 
	> git clone https://github.com/renata-auch/AME470-570.git
10. Time to get into the right directory, so do 
	> cd AME470-570/ 
then do 
	> cd assignment2/
11. Lastly, do 
	>node server
