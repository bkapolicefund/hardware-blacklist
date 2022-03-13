GIT PUSH
--------------------------

SET UP GIT IN REPO DIR

    dog
    
OR DO THIS TO SET REPO DIR

    echo "# hardware-blacklist" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin git@github.com:bkapolicefund/hardware-blacklist.git
    git push -u origin main

ADD REPO TO GITHUB
    
    git remote add origin git@github.com:bkapolicefund/hardware-blacklist.git
    git branch -M main
    git push -u origin main
    
ADD NEW STUFF TO REPO

    git add .
    git commit -m "."
    git push 
    
SET GIT SSH LOGIN

    git remote set-url origin git@github.com:bkapolicefund/solana.git

NOW PUSHES TO GIT WILL NOT NEED PASSWORD

    git push  git@github.com:bkapolicefund/solana.git
    
