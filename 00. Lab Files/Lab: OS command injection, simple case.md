# Lab: OS command injection, simple case

1.  This lab contains an OS command injection vulnerability in the `product stock checker`. The application executes a shell command containing user-supplied product and store IDs, and returns the raw output from the command in its response.
2.  To solve the lab, execute the `whoami` command to determine the name of the current user.
3.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/6dd5ecff-e3a6-46a1-ac45-50481d8c4562)
4.  Capture the request and send it to repeater.
5.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/9a0787c9-09dc-4aa8-9839-1ac77798fff8)
6.  Use `|` operator to append the command.
7.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/1e56bdb4-1c61-47db-a406-affad37786db)


