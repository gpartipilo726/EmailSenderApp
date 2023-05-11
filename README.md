# EmailSenderApp

This app will allow you to send SMTP email's using SSL in Python. 

*Important* In order to send mail, App password must be generated on email account. For gmail users, please see link below:
https://support.google.com/mail/answer/185833?hl=en-GB


Workflow:
1. App asks user for user's email credentials (email and app password) and message details (sender, reciever, subject, body)
2. Stores this data in a dictionary and passes it to the next function
3. sendEmail function will then create a new EmailMessage() object and assign the data stored from the dictionary
4. Email is sent to address using smtp library over SSL


# Sample Output:
![image](https://github.com/gpartipilo726/EmailSenderApp/assets/26350938/ba48f2f0-00c1-46b1-82b6-97b071039d1a)

# Email Recieved:
![image](https://github.com/gpartipilo726/EmailSenderApp/assets/26350938/b374398f-1ad4-48ce-898b-9a9602b1d125)
