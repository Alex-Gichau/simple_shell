#CREATE A NEW REPOSITORY ON THE COMMAND LINE
echo "# simple_shell" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Alex-Gichau/simple_shell.git
git push -u origin main

#PUSH AN EXISTING REPOSITORY FROM THE COMMAND LINE
git remote add origin https://github.com/Alex-Gichau/simple_shell.git
git branch -M main
git push -u origin main
