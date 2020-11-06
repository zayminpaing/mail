In order to use sendMail method, do the followings.

1. Download mail.py and put it in the same directory as your python file.

2. Import sendMail method from python file called mail

For Windows,
from mail import sendMail

For Linux,
from mail import sendMailLinux

3. Call the method with required parameters

For Windows,
sendMail(fromEmail,fromPassword,subject,contentPath,contentFilename,maillistPath,maillistFilename,attachmentPath,attachmentFilename)

For Linux,
sendMailLinux(fromEmail,fromPassword,subject,contentPath,contentFilename,maillistPath,maillistFilename,attachmentPath,attachmentFilename) where

fromEmail = sender's email
fromPassword = sender's password
subject = email's subject
contentPath = file path to email content (shoule be .txt file)
contentFilename = name of the .txt file of content
maillistPath = file path to receivers' email list (shoule be .txt file)
maillistFilename = name of the .txt file of receivers' email list (the emails should be comma seperated in the .txt file)
attachmentPath = file path to the attachment
attachmentFilename = name of the attachment file

Please be noted that the sender email used here should be on for allow less secure apps and the google account's reCAPTCHA settings should be off.

For step-by-step guideline, visit https://hotter.io/docs/email-accounts/secure-app-gmail/
