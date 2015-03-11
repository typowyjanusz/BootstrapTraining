# Fork upstream

# Clone origin (the forked repo)

    git clone https://github.com/xxx/....
    git remote set-url origin https://blabno@github.com...

# Add upstream

    git remote add upstream http://....
    git remote -v

# Start new feature branch

    git checkout -b feature/jumbotron

# Commit

    git add ...
    git commit -m "..."

# Push branch changes to origin

    git push origin feature/jumbotron

# Create Pull request





# When request cannot be merged

You have 2 options.

Ugly) Merge upstream/master to your feature branch

    git fetch upstream
    git merge upstream/master

Elegant) Rebase your feature branch agains upstream/master

    git fetch upstream
    git rebase upstream/master
