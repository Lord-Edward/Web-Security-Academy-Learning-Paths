# Lab: User role controlled by request parameter

1.  This lab has an admin panel at `/admin`, which identifies administrators using a forgeable cookie. Solve the lab by accessing the admin panel and using it to delete the user `carlos`.
2.  You can log in to your own account using the following credentials: `wiener:peter`.
3.  As we have credentials, lets log in using those credentials.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/a5b4df82-fbd9-40e4-b4d6-de1d7367ee47)
5.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/7af21a84-1bc5-41b0-8c39-36c0ffe7d7ee)
6.  Capture this request in Burp.
7.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/d0fac82f-4f7e-4d5d-8266-a499276643e9)
8.  Send the captured request to `Repeater`. Change the cookie value from `Admin=false` to `Admin=true` and send the request.
9.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/17af9ba1-89f3-44f2-b978-efb34bc9033e)
10.  Now we know we are admin and have access to `/admin` panel. Let's try to access that panel.
11.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/5bc829db-1dd0-4e64-b005-654453cce283)
12.  Get the URL to delete the `carlos` user.
13.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/a01ac825-a09f-4832-862f-aa27900a42a5)
14.  Now send the request for this URL.
15.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/1ff72b0d-04fe-46e2-81e9-fccb60228240)






