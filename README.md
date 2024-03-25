# LaunchAgents

A place to put custom LaunchAgents

It's not a great idea to make your ~/Library/LaunchAgents folder a git repo.  System updates will mess with that.  The idea here is to make a separate repo that has the .plist files, and cp commands in those files to copy them to the right place.

With the Sonoma update, .plist files can't be symlinks.
