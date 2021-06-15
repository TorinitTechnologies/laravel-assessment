# Laravel assessment

### User Stories: 

- User should be able to sign up, login, forgot password, reset password.
- User should get an email with verification link to activate the account.
- User should be able to sign up / login with social media accounts for example facebook, twitter or linkedin (Any one will do)
- User should be able to update own profile. (Name, Email, Phone Number, Profile Picture, Gender, Date of birth).
- Write a console command to create 50,000 users with fakery including profile picture. (needs to be queued)


### Things to follow:
- Should use repository pattern.
- All the validation requests should maintain their own class.
- TDD approach should be strictly followed.
- Uploading profile picture should be with S3.
- Heavy tasks should be offloaded to queue. And should send a trigger to an email address defined in .env once the process is complete.


### Delivery can be made in one of the following ways
- Push all the code to a public repository and share the link with HR.
- Zip all the code (Excluding node_modules) and send it via email if file size is lower than 20 MB