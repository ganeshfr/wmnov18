# github

git init
git add README.md
touch .gitignore // Créer un fichier gitignore (facultatif)
git commit -m "first commit"
git remote add origin https://github.com/nomuser/nomprojet.git
git push -u origin master

Configuration
  git config --global user.name "votre_user_name"
  git config --global user.email "votre_email_id"

Status des fichiers
  git status

COLLABORATORS :
  git clone https://github.com/nomuser/nomprojet.git
  git pull origin master  //Mettre à jour le dépôt local

Créer une branch
  git checkout -b ma_branch
  git add fichier.extension
  git commit -m "texte"
  git remote add origin https://github.com/nomuser/nomprojet.git
  git push -u origin ma_branch

Changer de branch
  git checkout master

Supprimer la branche
  git branch -d ma_branch
