Owning an apk by gitlab exposure

My latest Penetration Testing Project:
I just had a mobile application (apk file) in hand to start.
Starting the Project:
1. Reverse Engineering the apk file.
2. Checking the files (all JavaScript files were encrypted with extension .jsc).
3. Searching for ‘xxtea’ key inside the files, found it and decrypted the jsc files.
4. Reviewing the JS files and source code.
5. Found Interesting IP Address.
6. Port Scanning and Checking Open Source Intelligences.
7. Found Open Port running GitLab.
8. Gitlab allows to Register user with low privileges.
9. Registered and accessed Gitlab with normal user.
10. Found a vulnerability that allowed authenticated user to view all user’s usernames.
11. Found the username of the Administrator.
12. Bypassed Rate Limit and brute forced the password of the Admin Username.
13. Found the password and accessed the Gitlab with High Privileged User.
14. Found all Company Private Projects and Source Code.
15. Downloaded all data from Gitlab.
16. Started reviewing their Source Code of all projects.
17. Found a password.
18. Reviewed technologies that used inside the source code.
19. Found Redis used with it’s port.
20. Tried to connect to redis with the password I found before. Successful connection occurred.
21. Searched inside Redis for any useful information.
22. Found lot of user details.
23. Found a Super Admin user with an encrypted password.
24. Searched for the encryption type on the internet and decrypted the password successfully.
25. Found another open port pointing to the Backend Management Panel.
26. Tried to login with the username and decrypted password.
27. Obtained successful login to the Backend management system.
28. All Application information and user data found in this panel.
29. I used Redis to escalate it into RCE.
30. Successfully obtained Remote Code Execution to the Company Server.
31. I owned the Whole Company 😎
Project finished!
Duration: 5 days (5 hours a day).


# ARWAD
Advanced Reconnaissance and Web Application Discovery.

Dropping here some of my mindset relating to Reconnaissance.
