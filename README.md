>NOTE: Here is how to set up git-flow
```bash
    sudo apt update
    sudo apt install git-flow
    git clone https://github.com/<your-username>/ALXprodev-advanced_git.git
    cd ALXprodev-advanced_git

    git checkout -b develop
    git push -u origin develop
    git flow init -d

    touch README.md
    git add README.md
    git commit -m "Add empty README.md"
    git push origin develop
```