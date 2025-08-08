git init
git config user.name "Juhyeok-Park/Brown"
git config user.email "pjh9561@gmail.com"
echo "# 초기 커밋" > README.md
git add README.md
git commit -m "chore: init"
git branch -M main
git remote add origin https://github.com/Juhyeok-Park/Brown/Brown.git
git push -u origin main
