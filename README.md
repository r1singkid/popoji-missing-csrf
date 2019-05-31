# popoji-missing-csrf


## Proof of Concept :

### Missing CSRF token at Popoji CMS
￼
![CSRF Token](https://s3.amazonaws.com/com.twilio.prod.twilio-docs/original_images/el0otNMnu_Py7VYSUmd3KfC2f58jVjIAX24ff6e8DnY2qrh3Jw9pKYyGN4qQIIg2Dnl39evUcD.png)


Missing CSRF token in CMS is so dangerous because attackers might have access to one’s source code. By using simple  social engineering, the attackers can inject harmful code, he/she might do any post/get request which have a really wide scope, like file upload lead to backdoor, user add/delete, etc.

In this POC, I use simple html + js to make a one site page, which if the admin of site execute it… Boom! Site is injected and we have administrator access to the site.



In this source code, i use csrf injection to gain access to administrator rule. You can get the source-code in the resiptory above
The javascript will force whoever open the html file to commit some action.
