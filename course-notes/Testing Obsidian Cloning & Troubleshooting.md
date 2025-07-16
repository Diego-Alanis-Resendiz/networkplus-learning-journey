This is a test to see if I am able to sync my obsidian notes to this github repo using a personal access token and the git community plugin for obsidian.

Using following Git Community plugin command: 
- Git: Commit-and-Sync

Important to note that at first I was getting an error ("cannot read properties of undefined reading clone obsidian") that was resolved by installing git on my device and then restarting the obsidian application

Then I received another error ("cloning into fatal protocol https is not supported") and I was able to resolve this by restarting the application and checking the remote url and realizing I had added an additional blank space before the url (e.g " https://")

Now I am getting an author identity unknown error. 

To get rid of this error I opened up git and followed the instructions. The used the command "git config --list" to ensure my new user.email and user.name changes were made. Then I restarted git and attempted to run  Git: Commit-and-Sync

Yippee this time we were successful 