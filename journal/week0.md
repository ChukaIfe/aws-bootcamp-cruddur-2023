# Week 0 — Billing and Architecture

https://lucid.app/documents/view/6499e91b-b8a6-4aea-b474-ea971bcf804c


![Page 1](https://user-images.githubusercontent.com/105896398/220188484-bfcb9d66-17bd-4313-a7b4-668a263c0aaa.png)
![Page 2](https://user-images.githubusercontent.com/105896398/220188579-28f2f7d7-4454-4c04-ae4c-76e85faf8eac.png)

#Created a new User and Generate AWS Credentials
Go to (IAM Users Console](https://us-east-1.console.aws.amazon.com/iamv2/home?region=us-east-1#/users) andrew create a new user
Enable console access for the user
Create a new Admin Group and apply AdministratorAccess
Create the user and go find and click into the user
Click on Security Credentials and Create Access Key
Choose AWS CLI Access
Download the CSV with the credentials

#Set Env Vars
We will set these credentials for the current bash terminal

export AWS_ACCESS_KEY_ID=""
export AWS_SECRET_ACCESS_KEY=""
export AWS_DEFAULT_REGION=us-east-1

#We'll tell Gitpod to remember these credentials if we relaunch our workspaces

gp env AWS_ACCESS_KEY_ID=""
gp env AWS_SECRET_ACCESS_KEY=""
gp env AWS_DEFAULT_REGION=us-east-1