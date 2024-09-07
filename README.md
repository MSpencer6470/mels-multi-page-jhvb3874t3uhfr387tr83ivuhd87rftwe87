echo "# mels-multi-page-jhvb3874t3uhfr387tr83ivuhd87rftwe87" >> README.md
git init
git add README.md
git config user.name "MSpencer6470"
git config user.email "ladysqueek647@gmail.com"
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MSpencer6470/mels-multi-page-jhvb3874t3uhfr387tr83ivuhd87rftwe87.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push --set-upstream origin main

//PUSHES CHANGES TO THE ORIGIN'S MAIN BRANCH AND SAVES THE PARAMETERS
git push -u origin main

//ADD CHANGES THAT WERE MADE TO THE README FILE
git add README.md

//ADD CHANGES THAT WERE MADE IN ALL FILES AND FOLDERS
git add .

//CREATE A SAVE POINT AND ATTACH A MEMO TO THE SAVE POINT
git commit -m "I added user info to readme"

//SYNC TO GITHUB
git push

//VIEW THE VALUE OF ORIGIN
git remote -v

//ASSIGNS A URL TO THE ORIGIN VARIABLE
git remote add origin https://github.com/MSpencer6470

//CHANGE THE VALUE OF THE ORIGIN VARIABLE
git remote set-url origin https://github.com/MSpencer6470

//ACTIVATE OR INITIALIZE GIT SOURCE CONTROL
git init

//RENAMES THE CURRENT BRANCH TO MAIN
git branch -M main

//GET THE CURRENT VERSION OF GIT
git --version