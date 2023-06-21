# git-hooks
a collection of git hooks

## Installation

First change directories to the repository where you want to setup these hooks

    cd ../path/to/your/repo

Next download the hooks into the `.git/hooks/` directory, and make it executable:

    curl https://raw.githubusercontent.com/alexcb/git-hooks/main/hooks/pre-commit > .git/hooks/pre-commit && chmod +x .git/hooks/pre-commit
