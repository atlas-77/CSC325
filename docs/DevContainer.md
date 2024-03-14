# DevContainer Environment
## Introduction - what is a DevContainer? 
A DevContainer is what the name suggests - a container in which the user can develop. It includes whatever the creator specifies, usually a base image for it to run from, and the tools needed for development in a certain language - in our case, Flutter.
## Configuration
I used an Ubuntu image to develop in, and a Docker container to host it. My devcontainer.json file includes the Flutter extension for VSCode, and my Dockerfile includes the Ubuntu image as well as the Flutter SDK.
## Integration with VSCode
As stated above, my devcontainer file includes the Flutter extension for VSCode, and using the Remote Window button in the very bottom left of VSCode the user can work within the DevContainer. It includes the basics needed to work with Flutter.
## Usage
To behonest, I didn't use the DevContainer for the Flutter app creation - I've never really worked with DevContainers before and it was difficult to even get mine working, which I will describe below under Challenges and Solutions
To use my DevContainer - in bash, in the .devcontainer directory, run
 	`$ docker build -t flutterapp .`
then
    `$ docker compose up` 
-this builds the container and runs it.  I used VSCode as an IDE, and used its Flutter extension to create the app.
## Challenges and Solutions
Challenges - to be frank, the whole thing. DevContainers are pretty new to me. In my experience in the workplace, I just took a day or two to setup my dev environment on a laptop and ran with that. So, Solutions - in making this I had to google a lot, and I'm still not entirely sure it works like I want it to.
## Conclusion
The benefits of DevContainer usage are apparent - being able to quickly set up a self-contained development environment anywhere where the container is accessible is obviously very useful, especially if the user is developing from different locations. Insights gained? To be honest, just that I don't really enjoy making DevContainers and will delegate the creation process to other team members wherever possible.