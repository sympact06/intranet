# Intranet V1

## Introduction

> Intranet V1. It is builed by SympactDev and Arcti (Frontend is QBus Framework)



## Installation

> Use the following steps to install your intranet! 
#This instruction is made for DirectAdmin! (You can get a dutch one at servernode for free)

# Step 1
> make a intranet folder in your public_html (if you want another name or just in the main html folder you can do that)

>you will now have mydomain.com/intranet

# Step 2
> Download this repo and upload all the files in that folder!

# Step 3
> Go to your SQL manager and make a sql (save the login credits)

# Step 4
> Open phpmyadmin for sql management with your directadmin login credits

# Step 5
Go to your database and click on "Import" tab. Please select the Intranet.sql in the repo from us. Then click on start!

# Step 6
> Your site is now setted up!
> You can login with the login:

Username: `admin`

Password: `1234`

# How to make someone a admin?
> Go to your database and the table "users" You will see there a group called "roles". Please edit the value to `admin` and not `users`
