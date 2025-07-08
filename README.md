# Advanced-Linux-Commands
Permissions.
Read, write, and execute are permissions with values 4,2,1 respectively. These allow you to know what perrmissions an indivdual user has, a group has , or a resource. Uusually, by the owner of the file, the group and the public. 
Image illustrations would be shown below. The image shows directories and files listed by the ls command with d for directory and - for files. The user group permissions are also very evident. 
<img width="593" alt="image" src="https://github.com/user-attachments/assets/3bad5eb0-7db0-4014-9654-1a106acd969b" />

Change mode (chmod).
This command is used to change the permissions of a file. Lets do an example. See the image below. The read, write and executuion will be changed for the user groups by using the values (4,2,1) for the permissions. Script.sh had the execution permission added to all the user groups. And for keypair.pem, all the permissions were removed, expect the read permission for the owner of the file. See the image below.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/fa1f8f5b-cc64-41c7-8958-58d144fe5cb7" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/d9a43d33-05cb-4da9-bb02-e5d0d7fa44e9" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/9efe57b8-271f-44eb-9d64-e74647f0d986" />

Change owner (chown).
chown [option] owner[:group] file(s). This is used to change ownership of files. In the image below, user 'guest1' was added to a 'developers' group. Change of the ownship of a file owned by ekemini was be executed. Changing ownership is a sudo privilege so you must use sudo along side the chown command. 
<img width="955" alt="image" src="https://github.com/user-attachments/assets/446d0ada-584d-4a08-b85c-d97a388cb717" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/975e8134-a5de-46d7-99a3-9580f7c64e93" />

Super user privilegdes.
In Linux, superuser privileges, often called root privileges, grant a user complete and unrestricted access to the operating system, allowing them to perform any task, modify any file, install software, and manage other users and permissions. In the image below, i swapped users between root and regular user.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/7e386406-1c44-42fb-9f1e-70796ef77016" />


User management on linux. 
First, we learn to create a user and enter his full information, including the group he or she should be in.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/902dca52-8bc5-48a0-9157-f8b4a32d8cc8" />
In the next image, johndoe is added to the sudo group using flag -aG which appends johndoe to the new group as well as point to the group(s) intended for joining.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/410c8772-b76b-45fa-90f4-3bfc4effe1d0" />

TASKS FOR ME
logging out and logging in as johndoe.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/467b16ab-6b87-4751-89b4-46a51a1a2989" />

switching between users and changing passwords via the images below
<img width="959" alt="image" src="https://github.com/user-attachments/assets/54842841-47b6-4489-ae50-e266aee7db29" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/0a7dfda5-0d60-4d5d-909f-2fa23875a7e9" />
<img width="955" alt="image" src="https://github.com/user-attachments/assets/446d0ada-584d-4a08-b85c-d97a388cb717" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/ff1eef4a-f324-4804-baa2-fc49ac734f47" />

Deleting a user. userdel command used in deleting a user in the image below
<img width="959" alt="image" src="https://github.com/user-attachments/assets/0868f82e-8292-496a-80ab-88f06779d0b4" />

Group management.
<img width="426" alt="image" src="https://github.com/user-attachments/assets/07e4cec5-0877-49b8-b301-2151f52f0ae3" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/23733660-dd33-44a7-bc7c-6afccce6f80b" />


Side Hustle

Created a user 'mary', 'mohammed', 'ravi', 'tunji', 'sofia' and added them to the devops group. see images below
<img width="959" alt="image" src="https://github.com/user-attachments/assets/9e5fbed1-4695-44c7-8f8c-d85bd0e3422b" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/12c22643-e8fc-4a00-babe-f9ffb75e7faa" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/215c21c6-5629-466a-8ca9-dda016f56aa6" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/1a484cc9-c77e-4ba2-94cc-d3f299a88c5a" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/a68902da-f616-46ae-bb20-5869eefa7214" />

Change directory into the /home directory and create a folder for all users
<img width="959" alt="image" src="https://github.com/user-attachments/assets/ece42d9a-1671-4771-9ce2-9f4c7567ef15" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/416197f6-0018-4f83-8756-cd0c25ef8816" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/5f59a136-65dd-4aac-b2d1-0b5396d1f319" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/7d9df6ac-8d57-481f-a0fe-bfab76f00dd2" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/a1e152df-4d83-4628-ace1-5ed563f69fdf" />

Folder in Directory must be owned by devops. see images to ascertain this.
<img width="959" alt="image" src="https://github.com/user-attachments/assets/c08288c5-869f-4dfa-816b-a62d72fbdc94" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/d431ce4e-bed9-4974-bc8e-9add0be8b11e" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/cb06b743-6474-4dda-8816-b8580965be55" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/b1347979-80b3-4672-833a-1d787a034f8a" />

<img width="959" alt="image" src="https://github.com/user-attachments/assets/19440baf-b8cc-472e-963a-273fb59fc2cd" />

