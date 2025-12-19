2) Différence entre git fetch et git pull

git fetch on va récuperer les modifications sans modifier ma branche locale.
git pull = on va mettre à jour ma branche locale automatiquement.


3) Différence entre git reset et git revert

git revert crée un nouveau commit qui annule un commit précédent (historique conservé).
git reset déplace HEAD (et potentiellement l’historique), et en --hard modifie aussi le working directory.