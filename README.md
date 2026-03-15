# Behealthy-App
git config --global user.name "g00st-bep"
git config --global user.email "ramess.elguibli@edu.isetcom.tn"
git config --global core.autocrlf true
git config --list
git init
git branch -M main
git remote remove origin 2>$null
git remote add origin https://github.com/nomprenom/BehealthyApp.git
git add
git commit -m "NavigationActivity"
git pull --rebase origin main --allow-unrelated-histories
git push -u origin main
git push
git pull
