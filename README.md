mkdir new-project
cd new-project
git init -b main
echo "init text" > README.md
git add README.md
git commit -m "init"
git checkout -b development