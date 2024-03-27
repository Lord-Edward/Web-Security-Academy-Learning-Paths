# Lab: Basic SSRF against another back-end system

1.  This lab has a stock check feature which fetches data from an internal system. To solve the lab, use the stock check functionality to scan the internal `192.168.0.X` range for an admin interface on port 8080, then use it to delete the user carlos.
2.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/d1390706-f928-4f9d-972e-b8f53d5780dd)
3.  Capture this request in burp.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/1c5377d5-83cf-4cf5-a2bd-9256978a5350)
5.  Send this request to intruder and change the stoclAPI URL. Apparently we need to find the IP for admin URL.
6.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/4ff082a7-b35c-4ce0-8e1e-93a0a3aa56db)
7.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/30ae707e-851c-4f0b-91d5-958b9a0d4546)
8.  Start the attack.
9.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/afbb4f9c-7f9c-423e-bb58-e9a8982ae38f)
10.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/45e1df18-c629-428c-aa4c-134b81bc72ff)




