# Lab: User ID controlled by request parameter with password disclosure

1.  This lab has user account page that contains the current user's existing password, prefilled in a masked input. To solve the lab, retrieve the administrator's password, then use it to delete the user carlos.
2.  You can log in to your own account using the following credentials: `wiener:peter`.
3.  Logged in with wiener's credentials.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/6fa5b192-188d-4ee8-acd0-0e59aa960be6)
5.  Changed the id from wiener to administrator in the URL and hit enter. We can see the masked password now. As we captured the request, we can see the details either there or in page source code.
6.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/47c1d7c0-9e84-441c-b96e-0e5901d9836c)
7.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/7eaf22d1-9d8c-4584-b5e9-d04ef66cc714)
8.  Now we have password for admin user, so let's try to log in using these new credentials.
9.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/5dcaaa9f-4d36-48c3-839f-1007061280d5)
10.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/33354393-9945-4eaa-a899-9714f3cb891c)
11.  We can see that there is `Admin panel` now. Click on that.
12.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/84b483a9-09e8-4efb-bba5-23996b28326f)
13.  Delete the carlos user to complete the lab.
14.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/e9bb9de9-257b-4a0a-a396-d631bf1704a6)







