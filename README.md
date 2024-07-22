# Steps to create a Githubs Workflow/Pipeline.
 

 

1.Create an Ubuntu server,connect to the Instance,perform necessary updates and ensure Docker is installed on your server. 

 ![image](https://github.com/user-attachments/assets/90ff38dd-d21e-424e-a45e-9b2bd2397e2b)



2. Create a Github account ⇒create a repository and directory for your project. 

    Click on Repository Settings ⇒Actions ⇒Runners ⇒ New self-hosted runner and follow         

    the steps provided below.
   
   ![image](https://github.com/user-attachments/assets/6f1f50c2-cf80-45c4-9e28-e16847e9224e)

 ![image](https://github.com/user-attachments/assets/304538a5-5c43-4187-af1d-b5b54c09204e)



Here the binary is downloaded into the Ubuntu server and Runner is also configured. 
![image](https://github.com/user-attachments/assets/225561ed-21e1-488b-a95a-d54e6b9d627e)
![image](https://github.com/user-attachments/assets/ff7e14b1-23ba-4263-9440-01dab762901a)
![image](https://github.com/user-attachments/assets/42ae307b-6342-4503-ae02-87df59b446eb)
![image](https://github.com/user-attachments/assets/c3114887-4541-4322-b8c6-dcbf5312ebad)


 

 

 

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


 

 

 

