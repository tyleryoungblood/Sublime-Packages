Sublime-Packages
================

Provides a way to keep my ST3 packages and plugins in sync across all my computers

- install Sublime Text
- navigate via command prompt to ST3 User Preferences (c:\Users\username\AppData\Roaming\Sublime Text 3\Packages\User\)
- run `git clone https://github.com/tyleryoungblood/Sublime-Packages.git`

This should pull all the files (including the .git directory) into your .../Packages/User directory

If you add a new package to ST3, be sure to run `git status` from the command line and add/commit your changes. Then from other computers run `git pull` to update their .../Packages/User directory to include the new package(s)
