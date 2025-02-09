# Connect-A-Web-App-with-Aurora
To Develop a web application connected to Amazon Aurora to manage high-traffic user data. Designed and optimized database schema, implemented secure APIs, and ensured scalability with Aurora's auto-scaling features.

#   Brief : 

![image](https://github.com/user-attachments/assets/7dcbff79-a945-48b2-9879-6df13cb3b789)


🧱 Create an Aurora MySQL Database.



🌐 Build and connect a web app.



🔗 Connect your database to the web app!!


# step 1 : Login with your IAM user

Head to your AWS Account as the root user.



Open the AWS IAM console.



From the left hand navigation panel, choose Users.



Choose Create user.



For the User name, use Yourname-IAM-Admin‍



Make sure to select the checkbox next to Provide user access to the AWS Management Console - optional.‍



This does not apply to all accounts, but if you're prompted with a pop up panel that says Are you providing access to a person?, choose I want to create an IAM user.

For the console password, choose Custom password.



Type in a password that you will be able to remember/access in the future.

Choose Next.



In the permissions set up page, choose Attach policies directly.



From the list of Permissions policies, select AdministratorAccess.



Choose Next.



Choose Create user.



Voilà - you've just created your new user! Stay on this page.



Choose Download .csv file.



Copy the Console sign-in URL.



Now you're ready to start using your IAM user. 🏁



Log out of your root user's AWS Account.



Paste and go to your copied console sign-in URL.



Open your downloaded .csv file containing your user's access instructions.



Log in using your IAM user's username and password in the .csv file.


# Step 2 : Launch an EC2 instance for your web app
Work in progress
