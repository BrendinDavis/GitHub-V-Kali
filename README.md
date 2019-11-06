# GitHub-V-Kali
Attack 1
XSS 
version 4.2
Summary - Wordpress allows you to execute JS on your browser when creating or editing pages or posts
how to recreate - Start a new page, put in any title you want ant then insurt this code into the main text box : TEST!!![caption width="1" caption='<a href="' ">]</a><a href="http://onMouseOver='alert(1)'">XSS 💀</a>
Attack 2
User Enumeration
Version 4.2
Summary - based on what messages we recieve from the website when we enter credentials we are able to tell if the user is real or not.
recreate In Kali terminal run: wpscan --url http://wpdistillery.vm --enumerate uinal run: wpscan --url http://wpdistillery.vm --enumerate u
