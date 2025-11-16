# Docker-Compose-Lab





From the list of choices in our instructions, I chose to install Uptime Kuma. To begin, I installed Docker using the bash command sudo pacman -S docker. After enabling the Docker service, I confirmed it was running by using docker --version. Next, I created the application directory with mkdir uptime-kuma and entered it using cd uptime-kuma. I added the Docker Compose file and then started downloading Uptime Kuma by running docker-compose up -d.

Everything worked correctly until I tried accessing Uptime Kuma through my browser. My VM was in NAT mode, which prevented access, so I changed the network setting to Bridged Adapter. After that, I used ip a to find my VM’s new IP address, entered it into my web browser, and the Uptime Kuma admin account setup page appeared.

<img width="512" height="284" alt="IM1" src="https://github.com/user-attachments/assets/219d3959-be5a-460e-b1b7-997f64cedbdc" />

-Here in this image I began to install the docker 

<img width="512" height="206" alt="IM2" src="https://github.com/user-attachments/assets/e2b908e9-1667-4196-a19f-f8111c9eda35" />

-Here in The docker is fully installed

<img width="512" height="323" alt="IMG3" src="https://github.com/user-attachments/assets/fa01e955-cbc6-4cd3-a023-b09acbd81f20" />

-I had some trouble with my compose files here I attempted it but had to restart cause I typed all of it incorrectly 
<img width="512" height="164" alt="IMG4" src="https://github.com/user-attachments/assets/c0e038e6-2a8f-480b-8fe5-ed0edcb0a7b9" />


-The docker is in enabled and being setup 


<img width="512" height="291" alt="IM5" src="https://github.com/user-attachments/assets/509d0f78-2a27-4fe2-8256-5959f6ccefd2" />

-Here Kuma is finally activated 

<img width="512" height="227" alt="IMG6" src="https://github.com/user-attachments/assets/13c16b58-e614-4703-b0ff-0defb19d4b9e" />

-This is the Kuma admin interface after signing up and creating an account 


