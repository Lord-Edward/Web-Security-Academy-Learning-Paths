# Lab: User ID controlled by request parameter, with unpredictable user IDs

1.  This lab has a horizontal privilege escalation vulnerability on the user account page, but identifies users with GUIDs. To solve the lab, find the GUID for `carlos`, then submit his API key as the solution.
2.  You can log in to your own account using the following credentials: `wiener:peter`.
3.  Let's log in with given credentials.
4.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/81e16104-804c-4af9-b779-909692aa54bc)
5.  After logging in, we see this.
6.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/ff6b2fad-ff3a-4dfc-beff-d0af39a1ec08)
7.  GUID is difficult for brute forcing. So let's see what else is available on the website. Click `Home` to go back to home.
8.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/99d1c2e7-d75c-42cd-ba35-2b2a28b4620b)
9.  Looks like there are multiple posts done. Let's check them by clicking on `view posts` button.
10.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/f7498558-0e2b-4153-98ee-d36e072ccae6)
11.  We can see that there is username for the person who posted the blog. Let's click on that username and see what happens.
12.  Clicking on the username show the user GUID in URL.
13.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/358fc856-37c4-45e8-8c9d-713819cf9fbe)
14.  Based on this, we just need to find blog written by user `carlos`.
15.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/9d47c368-e88d-4793-a4e1-6ec0ed12bad4)
16.  Clicking `carlos` name gives us the GUID.
17.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/cb15e61d-d7b4-4e05-aab4-7852e3ad7ac9)
18.  Copy carlos's GUID and click on `My Account` button to go back to your accoune.
19.  Just change wiener's GUID to carlos's GUID in the URL and hit enter button.
20.  Wiener's account:
21.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/17d00941-665c-49e6-9391-7c7bdd3747d3)
22.  After replacing GUID:
23.  ![image](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/assets/117797209/d33af743-c2f2-4929-9d40-0b8d88c81e7c)








