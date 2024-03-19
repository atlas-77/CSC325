# Source Code Version Control Tools
## Introduction - The Importance of Version Control
Version control is important in software development for multiple reasons. Firstly, when working with a team, it gives a consistent shared environment to deposit and update code. With a VCS like GitHub, multiple users can work within the same code base, while creating different changes which can be pulled into the main branch.  This helps the integrity of the code base in that users within different branches can make pull requests for other team members to review and accept. It helps in the history aspect because the user can look back at different versions of the code base and revert back to an older version if needed. Finally, the collaboration aspect, it allows for simultaneous devlopment within the same code base without interference.
## Version Control System Used
I chose to use Git as a VCS as I've used it before, and I'm somewhat familiar with the basics of GitHub. I've used our GitLab before as well as Azure DevOps, but I'm most familiar with GitHub, which is why I chose it.
## Repository Setup
My repository is constructed of a devcontainer folder, a docs folder, a workspace folder for the build stage of the pipeline, and a folder to contain the flutter app. I don't have a branching strategy, though I probably should and will going forward. I'll create a branch for each task and pull it into main when I am certain each task is complete. As stated in DevContainer.md, I did not really use the DevContainer in my app creation, and the CI/CD pipeline is still in progress as of the time of writing this, though when complete the repository will be the code base used by the stages of said pipeline. I don't have a particular commit message scheme, though I will implement one. Brief descriptions of each commit seem to be the way to go there. Branch naming conventions will begin when I start branching, and will look something like
- goalOfBranch,
that is, the assignment's name or a shorthand version of it.

## Common Commands and Usage
To be honest, I use the very basics of git commands here, that is,
- git add (file or folder to be pushed)
- git commit -m "message" (see Repository Setup for message scheme)
- git push
I haven't reverted to previous branches, nor have I merged branches (see Repository Setup).
## Collaboration Features
Git as a VCS with GitHub, as stated under Introduction, allows teams to work in tandem while not interfering with each other's work. Pull requests are made from a user's branch and may be reviewed by other team members before being accepted and pulled, or pushed into main. The code review step allows other team members to review the pull request and comment on any mistakes or other topics of importance. Conflict resolution must happen when changed have been made to the same files in seperate branches, and those branches are trying to merge. Merge conflicts may occur, and when they do, the user can look through conflicts in order to select the changes they want to keep. GitHub also allows for access to a code base from different machines via the clone command, which makes remote development more accessible.
## Challenges and Solutions
Challenges - not too many. I've used Azure DevOps with my team at work, and it works very similarly to GitHub. Within an IDE, they work identically, from what I can tell. Aside from that, I need to implement more organization, like a commit message scheme and branching with naming conventions (see Repository Setup). Solutions - I will do these things going forward. 
## Conclusion
In conclusion, the benefits of using Git + GitHub for my project are: ease of use primarily, and easy access to older versions of my code base if needed, along with it being a relatively secure place to store my code in the cloud and work with it in different environments/on different machines.
