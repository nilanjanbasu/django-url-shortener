#Django-url-shortener
##Features:
Website hosted in Google App Engine with following features-

1. Users can **shorten an arbitrary web-url** and **publicly be able to share** it.
2. Users can **log-in** to the website with social-auth with minimal permissions or standard registration - **verification of account** should be done.
3. Users can **make the url private**- only those who are shared with will be able to view where the url points to(Similar to Google Docs sharing feature). This requires a user to be logged in.
4. Logged-in users can make **a group of emails** to facilitate sharing.
4. As of now website would not give any guarantee how long the urls would be stored as per GAE limitations. So, **users should store it for short term sharing**. A minimum guarantee must be given like 3 days or 10 days.
5. The site should **look good** from UI/UX point of view.
6. **Check for if the web-url actually exist** may be performed although is unnecessary for intial purposes.

---- 