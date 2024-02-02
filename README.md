# Eau Claire's Salon

_by Kim Robinson_

## Independent Project for Epicodus code school to demonstrate Database Basics

#### an MVC web application using MySql database and one to many relationships

###  This app will allow a user to:
    - see a list of all stylists
    - select a stylist, see their details and see a list of all clients that belong to that stylist
    - add new stylists to system
    - add new clients to specific stylist (can not add a client if no stylists exist)

### Technologies Used

* C#
* .Net
* Entity Framework Core
* MySql database
* MySql Workbench
* Git
* CSS
* Bootstrap

## Setup/Installation Requirements

_Currently not viewable on gh-pages. Please follow steps below to set up locally_

1. Navigate to [my github repository](https://github.com/kimmykokonut/HairSalon.Solution) for this project 

2. Click the `Fork` button and  you will be taken to a new page where you can give your repository a new name and description. Choose "create fork".

3. Click the `Code` button and copy the url for HTTPS.

4. On your local computer, create a working directory for my files and name appropriately.

5. On your terminal, type `$ git clone 'url'` (using the url from step 3.)

6. Once you have this on your local directory, if you ever want to push it to GitHub, you need to do these steps first so Git knows to ignore the obj and bin directories:
`$ git init` to initialize Git (if cloning, this step automatically happened)
`$ touch .gitignore` adds .gitignore file in the root directory. 

7. On your terminal, type `$ code .` to open in VS Code.  If you do not have VS Code Editor, you may download [here](https://code.visualstudio.com/)

----------------------------------
**add in appsettings.json HERE***
----------------------------------

8. In the .gitignore file, add `bin` and `obj` and save.
In the Terminal:
`$ git add .gitignore`
`$ git commit -m 'add .gitignore`
`$ git push origin main`

9. While in the terminal, navigate to the project's production directory currently called "HairSalon" and type `$ dotnet build` to compile the application's code.

10.  To use MSTest, you need to use the NuGet package manager to install the packages in the .csproj file.  Navigate to the HairSalon.Tests directory in the terminal and run the command `$ dotnet build`

*** Setupd database HERE IMPORT INFO< FILE> ***

- To see the application on your local server:
1. In the working directory (HairSalon), type `$ dotnet run` to compile and exectute the server.  It will be available at [localhost5001](https://localhost:5001/) and [localhost5000](https://localhost:5000/)

*  Optionally you can use a file watcher so you don't have to restart the server every time the code changes. Run this command `$ dotnet watch run` to make the server automatically update.  If you need to restart the server, you can type `ctrl` + `r`.

2. Enjoy!  You can close the development server at anytime by entering `ctrl` + `c` in the terminal.

* To run tests using MSTest, navigate to the HairSalon.Tests directory in your terminal and type `$ dotnet test`

## Known Bugs
* None known at this time

## License
MIT License. See license.md for further information