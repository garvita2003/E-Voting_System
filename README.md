# E-Voting_System
Here, the client establishes a connection with the server, this implies that the TCP protocol is being used. The Server should allocate a new thread for every new
incoming Client, to accomplish this feature we took care of concurrent thread, that is , when the number of connections are made with the server, that time each
thread doesn’t interfere with one another. Therefore, we synchronized the threads.
1. Admin Login :
   1. Admin ID : Admin
   2. Password : admin

2. Voter Login: Server should be running for voters to be able to login.
   1. Already registered voter I.Ds : 10001 to 10005
   2. Password (for already registered voters) : abcd

# Technology Used :
1. Python
2. Pandas - Data Update
3. Tkinter - Interface
4. Socket Programming - Connection, TCP Protocol
5. Subprocess - OS Calls

# Overview :
1. Home Page :

![Screenshot 2025-02-03 231014](https://github.com/user-attachments/assets/fd2e6408-ac79-43cb-a775-b13e07b1f8ae)

2. Admin Login :

![Screenshot 2025-02-03 231359](https://github.com/user-attachments/assets/3c6fe602-2df6-429b-bdc8-b95c6d188b76)

3. Admin Home :

![Screenshot 2025-02-03 231115](https://github.com/user-attachments/assets/075b5e1f-1e04-44a2-bb63-f937f1a39642)

4. Register Voter :

![Screenshot 2025-02-03 231213](https://github.com/user-attachments/assets/b40aba90-53b1-4c4a-8cf8-4fbf3faead8c)

5. Register Successful :

![Screenshot 2025-02-03 231221](https://github.com/user-attachments/assets/87a0d9b8-5521-48e3-8900-9843a8b4cbb0)

6. Voter Login :

![Screenshot 2025-02-03 231255](https://github.com/user-attachments/assets/2ecbaeba-2481-4b4c-88e4-35cd8cdd369a)

7. Voting Page :

![Screenshot 2025-02-03 231317](https://github.com/user-attachments/assets/8ca85bb3-ba5c-439f-a5ac-7dafc588f242)

8. Vote Cast Successful :

![Screenshot 2025-02-03 231334](https://github.com/user-attachments/assets/8230a325-ae62-4949-bd16-4a1283aad7e8)

9. Show Votes :

![Screenshot 2025-02-03 231411](https://github.com/user-attachments/assets/d8f0bb6d-03f2-4b44-bcb4-f3e8659253bb)

10. Error Handling :

   1. One user can only vote once :

   ![Screenshot 2025-02-03 231437](https://github.com/user-attachments/assets/679a4076-e2f2-40c2-a058-f714cd24f332)
   
   2. Voter not regsiter or invalid :

   ![Screenshot 2025-02-03 231519](https://github.com/user-attachments/assets/a5832afc-7a57-497a-bf67-97baded5472e)

11. Server Output :

![Screenshot 2025-02-03 231628](https://github.com/user-attachments/assets/15d8a4c4-2e6f-46fb-b05f-978b5f9e0dc8)

![Screenshot 2025-02-03 231720](https://github.com/user-attachments/assets/db657829-136f-4bd8-aa50-903f11c136a6)

12. Database :
    
    1. Voter List :

    ![Screenshot 2025-02-03 232559](https://github.com/user-attachments/assets/7beceaa5-5dac-4f1b-99de-14d4801dae43)

    2. Candidate List :

    ![Screenshot 2025-02-03 232546](https://github.com/user-attachments/assets/ae62b9c4-7ec2-47e3-9873-61d94bc61d42)

