# Git & Github

## Authentication

To properly deal with multiple github ssh keys, this command works really well:
git config --local core.sshCommand "/usr/bin/ssh -i /home/james/.ssh/personal"

This sets the .ssh/ file which should be used for the current Repo.
