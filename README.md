# ModernVedur
This project is for testing out the Veður.is API, and creating a simple web page by using .Net as the base.

# Requirements 
Visual studio version 2022 prefered, any version should work.
.net 9.0 framework installed
- https://aka.ms/dotnet-core-applaunch?framework=Microsoft.NETCore.App&framework_version=9.0.0&arch=x64&rid=win-x64&os=win10
- https://aka.ms/dotnet-core-applaunch?framework=Microsoft.AspNetCore.App&framework_version=9.0.0&arch=x64&rid=win-x64&os=win10

# How to setup
1. Load the project solution into Visual Studio
2. Build the project and add missing nuget packages, if any.
3. Run the project.
4. You may need to accept certifications for using HTTPS, accept them all and a Browser Window should launch in the end with the web page.

# Building the Project
To build a final version of the application/project you will have to publish it, otherwise you would have to have your Visual Studio open and running it from there. Which I would not recommend :D

1. In Visual studio 2022 (or other version) right click your project, this case ModerVedur.
2. Click "Publish"
3. Create a new profile and select where you want to have it running, this case select Folder
4. Then a new profile is created and you can then edit the profile and select "Release", and then click publish.
5. Default destination is /ModernVedur/bin/Release/net9.0/publish, but you can change that.
6. Goto your newly created publish folder, open up your prefered console. My case I used Powershell7.
7. Run the program by setting in .\ModernVedur.exe.
8. And now you have a program running on your computer, through http://localhost:5000. Congratz!

# Further improvements 
Create a custom map for mobile experience, and where we can add all the stations to that custom map - instead of using iFrame from Vedur.is.

# Things learned
Vedur.is API is getting old, and could use an update.
The iFrame.js from them is using HTTP instead of HTTPS, and modern browsers don't like that.
Getting the stations required some web scraping and GPT helped there alot.
