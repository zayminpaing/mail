In order to use sendMail method, do the followings.

1. Import sendMail method from python file called mail

from mail import sendMail

2. Call the method with required parameters

sendMail(fromEmail,fromPassword,subject,contentPath,contentFilename,maillistPath,maillistFilename) where
fromEmail = sender's email
fromPassword = sender's password
subject = email's subject
contentPath = file path to email content (shoule be .txt file)
contentFilename = name of the .txt file of content
maillistPath = file path to receivers' email list (shoule be .txt file)
maillistFilename = name of the .txt file of receivers' email list (the emails should be comma seperated in the .txt file)

Please be noted that the sender email used here should be on for allow less secure apps and the google account's reCAPTCHA settings should be off.

For step-by-step guideline, visit https://hotter.io/docs/email-accounts/secure-app-gmail/
