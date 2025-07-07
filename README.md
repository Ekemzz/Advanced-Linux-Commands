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

Group management.
<img width="426" alt="image" src="https://github.com/user-attachments/assets/07e4cec5-0877-49b8-b301-2151f52f0ae3" />
<img width="959" alt="image" src="https://github.com/user-attachments/assets/23733660-dd33-44a7-bc7c-6afccce6f80b" />



