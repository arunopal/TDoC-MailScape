# MailScape

## About the project:

MailScape is an email client build in Java. It is a full stack project which makes use of JavaMail API for sending and receiving mails, Java Swing for the GUI and MySQL database for starring emails.

## Project Architecture:
![architecture](images/architecture.jpg)

## Tech stacks used:

- Java
- JavaMail API
- Java Swing
- MySQL

## Aim:

- To send mails to multiple recipients with attachment.
- To view received mails.
- To star emails for future reference.
## How to use:

 1. Fork the repository onto your local machine.
 2. Go to the account settings for the email account that you want to use and generate an app password for it. For Gmail, follow these steps:
 
	 i)		Go to "**Manage Your Google Account**".

	 ii)	Select "**Security**".

	 iii)	Click on "**2-step Verification**", then scroll down and click on "**App Passwords**."

	 iv)	Click on "**Select App**" -> "**Other**" and enter the name of the repository (or any other name).
	 ![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_apppassword1.png?raw=true)

	 v)	Click on "**GENERATE**".
	 ![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_apppassword2.png?raw=true)

	 vi)	Copy the generated password to a text file.
 3. Go to the cloned repository on your machine.
 4. Go to the folder `dist` and open `Mailscape.jar`.
 5. You will see the login page.![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_login.png?raw=true)

 6. Enter your email address and the app password you previously created in step 2. Click on "**Log In**".
 7. You will see the main window with facility to send mail, view received mails and starred mails.![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_sendmail.png?raw=true)

 8. To send a mail, type in the email address of the receiver, the subject and the body of the email and click "**Send**".
 9. You can also attach files using "**Attach**" button.
 ![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_attach.png?raw=true)

 10. To view last 30 mails in your inbox, click on "**Search Inbox**". 
 11. Click on a mail to view it. You will get an option to star it or download any attachments from it.![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_receivedmail.png?raw=true)
 
 12. You can also view starred emails by clicking the "**View Starred Emails**" button.![enter image description here](https://github.com/arunopal/TDoC-MailScape/blob/master/images/mailscape_starredmail.png?raw=true)
