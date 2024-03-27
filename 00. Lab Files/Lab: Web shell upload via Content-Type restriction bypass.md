# Lab: Web shell upload via Content-Type restriction bypass

1.  This lab contains a vulnerable image upload function. It attempts to prevent users from uploading unexpected file types, but relies on checking user-controllable input to verify this.
2.  To solve the lab, upload a basic PHP web shell and use it to exfiltrate the contents of the file `/home/carlos/secret`. Submit this secret using the button provided in the lab banner. You can log in to your own account using the following credentials: `wiener:peter`.
3.  Let's try to upload basic php webshell.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/04c8b8f2-8fa4-4f79-b81c-d03ed44db1b6)
5.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/885d2eec-b2a0-4aa3-9455-22764f02c3c8)
6.  Capture that request in burp and send it to repeater.
7.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/7bdd7ab8-ef3c-4235-8798-74810a7fc60f)
8.  Just change the `Content-Type` in the request from `application/x-php` to `image/png`.
9.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/cdb29d22-888f-4fe6-90d6-10bf03fcc293)
10.  This tells that file is uploaded.
11.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/3320cfde-6df5-491c-ba55-d8c9c16e064b)
12.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/bb8cb84e-b649-40ec-9cb4-d8afe5cad2be)





