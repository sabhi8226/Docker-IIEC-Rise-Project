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

used things in this project :
:- docker contaniner
:- owncloud:latest image
:- mysql database
:- rhel 8
:- yml file
