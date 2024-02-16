# gitTips
here I have all git tips

######################### Git pull on 2nd location
You can't merge with local modifications. Git protects you from losing potentially important changes.

You have three options:

    Commit the change using

    git commit -m "My message"

    Stash it.

    Stashing acts as a stack, where you can push changes, and you pop them in reverse order.

    To stash, type

    git stash

    Do the merge, and then pull the stash:

    git stash pop

    Discard the local changes

    using git reset --hard
    or git checkout -t -f remote/branch
    Or: Discard local changes for a specific file

    using git checkout filename
#######################
