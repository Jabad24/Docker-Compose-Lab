# Docker-Compose-Lab





From the list of choices in our instructions, I chose to install Uptime Kuma. To begin, I installed Docker using the bash command sudo pacman -S docker. After enabling the Docker service, I confirmed it was running by using docker --version. Next, I created the application directory with mkdir uptime-kuma and entered it using cd uptime-kuma. I added the Docker Compose file and then started downloading Uptime Kuma by running docker-compose up -d.

Everything worked correctly until I tried accessing Uptime Kuma through my browser. My VM was in NAT mode, which prevented access, so I changed the network setting to Bridged Adapter. After that, I used ip a to find my VM’s new IP address, entered it into my web browser, and the Uptime Kuma admin account setup page appeared.


-Here is this image I began to install the docker 


-The docker is fully installed

-I had some trouble with my compose files here I attempted it but had to restart cause I typed all of it incorrectly 


-The docker is in enabled and being setup 


-Here Kuma is finally activated 
<img width="512" height="284" alt="IM1" src="https://github.com/user-attachments/assets/d88aa671-92a1-4c7d-a103-13f42278c692" />
