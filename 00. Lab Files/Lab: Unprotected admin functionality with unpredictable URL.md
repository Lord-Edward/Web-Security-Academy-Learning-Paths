#  Lab: Unprotected admin functionality with unpredictable URL

1.  This lab has an unprotected admin panel. It's located at an unpredictable location, but the location is disclosed somewhere in the application. Solve the lab by accessing the admin panel, and using it to delete the user `carlos`.
2.  Let's access the website.
3.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/e08325b2-e134-4d4b-a014-7860e08e17ed)
4.  Let's try to access the `robots.txt` file.
5.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/4b7f7c32-a7dd-4704-bbe9-ea493fc0af00)
6.  Looks like we don't have `robots.txt` file.
7.  Let's try to log in using `admin:admin` credentials.
8.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/e796372b-87e2-4858-bbb0-36cb04652102)
9.  That did not work. Let's try to check the source code of this page by right clicking on the `login` page and then selecting `View Page Source`.
10.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/2d68caba-b246-4742-be42-a866b3b78359)
11.  Let's check the code.
12.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/ff821533-2bbe-46a8-98c5-b83120e8a34d)
13.  We can see the code which checks if `admin` is trying to log in or not. We can see the custom URL for admin is `/admin-o8hqeg`. Let's try to access that.
14.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/8dab6272-eefc-437a-9708-d995cf505d29)
15.  Let's delete the user to solve the lab.
16.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/b28eb4f1-a942-4f98-a622-8e2132d928fb)






