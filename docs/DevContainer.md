## DevContainer Environment
# Introduction - what is a DevContainer? 
A DevContainer is what the name suggests - a container in which the user can develop. It includes whatever the creator specifies, usually a base image for it to run from, and the tools needed for development in a certain language - in our case, Flutter.
# Configuration
I used an Ubuntu image to develop in, and a Docker container to host it. My devcontainer.json file includes the Flutter extension for VSCode, and my Dockerfile includes the Ubuntu image as well as the Flutter SDK.
# Integration with VSCode
As stated above, my devcontainer file includes the Flutter extension for VSCode, and using the Remote Window button in the very bottom left of VSCode the user can work within the DevContainer. It includes the basics needed to work with Flutter.