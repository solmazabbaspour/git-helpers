Add my own custom Git helpers

## Setup
1. git clone git@github.com:solmazabbaspour/git-helpers.git ~/github/git-helpers
2. Add `export PATH=$PATH:~/github/git-helpers` to your `~/.bash_profile`
3. Run `source ~/.bash_profile`
4. Now you can run `git clean-branches` and it will ask your permission to delete each branch that doesn't have a remote branch


## Development
To add new commands just follow the same format as the existing files. Make sure you change the file mode to executable.
