## Clave pública
ssh-keygen -t ed25519 -C "1000014829@studium.unict.it"
eval "$(ssh-agent -s)"
ssh-add C:/Users/matte/.ssh/id_ed25519
cat ~/.ssh/id_ed25519.pub
Set-Service -Name ssh-agent -StartupType Manual
Start-Service ssh-agent

## Identidad 
git config --global --list
git config --global user.name "Matteo"
git config --global user.email "1000014829@studium.unict.it"

