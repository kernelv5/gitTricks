#### Git Clear History

##### Remove the history from
    rm -rf .git`
##### Recreate the repos from the current content only
    git init
    git add .
    git commit -m "Initial commit"
    git remote add origin git@github.com:kernelv5:Gr*******ub/BlockOne-Test.git
    git remote set-url origin https://github.com/kernelv5/BlockOne-Test
    git push -u --force origin master

##### Note
    Reset git all settings rm ~/.gitconfig
    git config --global --remove-section user
    git config --global --unset-all user.name
    git config --global --unset-all user.email
    git config --global --unset-all user.password
