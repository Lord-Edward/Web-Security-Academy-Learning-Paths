# Lab: 2FA simple bypass

1.  This lab's two-factor authentication can be bypassed. You have already obtained a valid username and password, but do not have access to the user's 2FA verification code. To solve the lab, access Carlos's account page.
2.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/1fb19695-1774-4dae-bf5a-83b9281bc777)
3.  Following are the requests sent for proper log in with MFA provided.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/89a184c1-7902-42fc-a439-4b9d886e3801)
5.  First request (Given user `wiener:peter`):
6.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/1ee31ae0-791a-41cf-bd92-935f176ce797)
7.  Second request:
8.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/778f0c17-f33e-4327-9e50-5658c9fd3acd)
9.  After successful log in:
10.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/a4792dc9-423d-4abe-8ed5-3ee9b9a964b8)
11.  Now in order to access `carlos` account, we will use session cookie created for user `wiener` and send the requests to repeater.
12.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/828efc9f-7dec-475d-9d6e-d732d7875c80)
13.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/14253378-f9bd-48eb-99d7-1bb81076be3b)
14.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/2c072924-9cab-4bd1-b69d-7b3b3d59ed0d)







