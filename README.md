# Web Security Academy Learning Paths

This repo covers the `notes` created for learning purposes. This should cover notes and labs hopefully.

## All learning paths

1.  [Server-side vulnerabilities (Level - APPRENTICE).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/01.%20Server-side%20vulnerabilities.md)
2.  [SQL injection (Level - PRACTITIONER).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/02.%20SQL%20injection.md)
3.  [API testing (Level - PRACTITIONER).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/03.%20API%20testing.md)
4.  [Web LLM attacks (Level - PRACTITIONER).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/04.%20Web%20LLM%20attacks.md)
5.  [Cross-site request forgery (CSRF) (Level - PRACTITIONER).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/05.%20Cross-site%20request%20forgery%20(CSRF).md)
6.  [File upload vulnerabilities (Level - PRACTITIONER).](https://github.com/Lord-Edward/Web-Security-Academy-Learning-Paths/blob/main/06.%20File%20upload%20vulnerabilities.md)

## Things which should be checked always

1.  Always check `robots.txt` file for any website.
2.  Always check the source code of the website. You might find some java scripts in code which might reveal the sensitive URLs.
3.  Always check the URL string parameters and see changing them changes anything. Ex. `https://insecure-website.com/login/home.jsp?admin=true` **OR** `https://insecure-website.com/login/home.jsp?role=1`.
4.  If you find any credentials, log in using that and check if any `cookies` are set specific to defining access.
