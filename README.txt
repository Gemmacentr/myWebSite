echo "myWebSite" >> README.md
git init
git config user.name "Gemmacentr"
git config user.email "gemma.centrone@studio.unibo.it"
git commit -m "first commit"

git remote add origin https://github.com/gemmacentr/myWebSite.git
git push -u origin master
