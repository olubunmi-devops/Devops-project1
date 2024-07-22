# Steps to create a Githubs Workflow/Pipeline.
 

 

1.Create an Ubuntu server,connect to the Instance,perform necessary updates and ensure Docker is installed on your server. 

 ![image](https://github.com/user-attachments/assets/90ff38dd-d21e-424e-a45e-9b2bd2397e2b)



2. Create a Github account ⇒create a repository and directory for your project. 

    Click on Repository Settings ⇒Actions ⇒Runners ⇒ New self-hosted runner and follow         

    the steps provided below.
   
   ![image](https://github.com/user-attachments/assets/6f1f50c2-cf80-45c4-9e28-e16847e9224e)

 ![image](https://github.com/user-attachments/assets/304538a5-5c43-4187-af1d-b5b54c09204e)


![image](https://github.com/user-attachments/assets/1f7646c1-1b09-42ae-b920-bc14d7db0a2d)


Here the binary is downloaded into the Ubuntu server and Runner is also configured. 
![image](https://github.com/user-attachments/assets/33af7b2b-46b6-49e5-a749-f146c03970d1)

![image](https://github.com/user-attachments/assets/bc7bec22-b07f-4336-90ce-172b3f1e4c8c)



 

 

3.Create .github/workflows/trigger.yaml 
![image](https://github.com/user-attachments/assets/20d82894-9405-482b-8803-87935fc0f187)
![image](https://github.com/user-attachments/assets/1be9c09c-93fc-4536-8d14-1541b0d07e8e)

 

 

 

 

 

 

 

 

 

 

 

4.Create Repository Secret for access to Docker hub  
![image](https://github.com/user-attachments/assets/d06bf182-3e66-4ef8-8b8f-4a1c23299e36)

 

5. Start your Runner using  this command. ./run.sh 
![image](https://github.com/user-attachments/assets/f19a9c2a-22e7-4c4c-b4cd-0056fb401c9a)

 

 

6.Workflow triggered below. 
![image](https://github.com/user-attachments/assets/12ec3243-bc9a-4ee6-9cfe-01b1225982c0)
![image](https://github.com/user-attachments/assets/fbee1e59-9197-4f71-ad6f-af0b33c1bc40)
![image](https://github.com/user-attachments/assets/19fae682-b36c-4d9c-9118-e08014a3a727)


 

 

 

