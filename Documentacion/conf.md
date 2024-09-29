## Clave pública

ssh-keygen -t ed25519 -C "1000014829@studium.unict.it"
eval "$(ssh-agent -s)"
ssh-add C:/Users/matte/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
Set-Service -Name ssh-agent -StartupType Manual
Start-Service ssh-agent

## Identidad 

git config --global user.name "Matteo"
git config --global user.email "1000014829@studium.unict.it"

## Repository

echo "# Urban-Traffic" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/MatteoImbrosciano/Urban-Traffic.git
git push -u origin main

## Creación del branch objetivo-0

git add README.md
notepad LICENSE
git add LICENSE.txt
notepad .gitignore
git add gitignore
git commit -m "create readme, gitignore, documentacion"
git branch
git push -u origin Objetivo-0
