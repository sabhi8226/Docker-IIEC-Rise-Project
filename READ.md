#@ DOCKER_IIEC_RISE_PROJECT

Introduction :

Docker project on laucnching owncloud in our system by using docker container over rhel 8 
and u can put your gb's of data here which will be safe and easy for us and i have created 
this project only because of iiec_rise campaign 1.0 under the great mentor and the world 
record holder Mr.Vimal Daga https://www.linkedin.com/in/vimaldaga/ 

And i would like to thank Mr.Vimal Daga Sir and Preeti Mam for such an great initiative iiec_rise

 I have used rhel 8(host  os) on the top of windows(base os) by virtualization using tool virtual box
 - before runnning any docker container you may need to off firewall and SELinux security 
   for firewall systemctl stop firewalld
   for SELinux  setenforce 0
For running this project u can follow steps shown in my Docker_Project.docx file with screenshot
or u can u can just do dew things i.e. 
install owncloud image
docker pull ownlcloud:latest
install mysql image
setup mysql as shown in Docker_Project.docx file
install docker-compose and inside any dir create ur docker-compose.yml
and paste the code of my docker-compose.yml
Then , run the cmd docker-compose up -d inside the directory
and then run docker ps  and see the IP of owncloud container running their by docker insoect
(id of owncloud contaner) | grep IP & that;s all guy's put this IP in firefox their will be 
owncloud home page in front of you where u can upload your data and enjoy.

used things in this project :
:- docker contaniner

:- owncloud:latest image

:- mysql database

:- rhel 8

:- yml file

