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
git push -u origin main

//ADD CHANGES THAT WERE MADE TO THE README FILE
git add README.md

//ADD CHANGES THAT WERE MADE IN ALL FILES AND FOLDERS
git add .

//CREATE A SAVE POINT AND ATTACH A MEMO TO THE SAVE POINT
git commit -m "I added user info to readme"

//SYNC TO GITHUB
git push origin main

//VIEW THE VALUE OF ORIGIN
git remote -v

//ASSIGNS A URL TO THE ORIGIN VARIABLE
git remote add origin https://github.com/MSpencer6470

//CHANGE THE VALUE OF THE ORIGIN VARIABLE
git remote set-url origin https://github.com/MSpencer6470