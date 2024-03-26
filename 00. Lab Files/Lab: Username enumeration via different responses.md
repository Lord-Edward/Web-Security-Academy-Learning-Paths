# Lab: Username enumeration via different responses

1.  This lab is vulnerable to username enumeration and password brute-force attacks. It has an account with a predictable username and password, which can be found in the following wordlists:
     -  [Candidate usernames](https://portswigger.net/web-security/authentication/auth-lab-usernames)
     -  [Candidate passwords](https://portswigger.net/web-security/authentication/auth-lab-passwords)
3.  To solve the lab, enumerate a valid username, brute-force this user's password, then access their account page.
4.  Captured the request of login and sent it to intruder. Loaded with only usernames and kept some random password.
5.  If username is wrong, it will show error as `Invalid username` as follows.
6.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/cacefc41-963a-46ef-89f7-8a3eca1aeb8f)
7.  Checked with order by leangth of response received and can see, length is different for once of the username.
8.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/e000f509-6770-4c0b-b3a5-3773bd5e7eb2)
9.  Error message received is different too in case of user `acceso`. We see `Incorrect password` error message, that means this is valid username.
10.  So let's use this usernamd and list of password given.
11.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/8628dea4-7418-407c-984a-19b848e9849f)
12.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/435a9c7a-501e-445f-80bd-97096cce69e3)



