1)Expliquez, en quelques phrases, la structure actuelle du projet Git après toutes les opérations (branches, merges, commits).

Alors notre projet Git contient une branch main qui a recue des pull request des collaborateur
Chaque collaborateur à une branch et ils ont communiqué ensemble via des merge de branch et des rebases 





PS C:\Users\Arsha\OneDrive\Documents\Tp-git\TP-Git-2025> git log --graph
* commit 748725159867c25066d6909c6763680d954fae06 (HEAD -> arshaad, origin/arshaad)
| Author: Aboo-Dany <arshaadjkhan97400@gmail.com>
| Date:   Fri Dec 19 12:29:58 2025 +0100
|
|     revert/arshaad : Annulation tp.md
|
*   commit e6bc14b5a9544b41a11c9aba30758ea56ff7368d
|\  Merge: 9dfb13d 49e4414
| | Author: Aboo-Dany <arshaadjkhan97400@gmail.com>
| | Date:   Fri Dec 19 11:56:35 2025 +0100
| |
| |     Merge branch 'reangsey' of https://github.com/Aboo-Dany/TP-Git-2025 into arshaad
| |
| * commit 49e4414c415a3df9a5730baeb2f6244f2ca6385d (reangsey)
| | Author: In Reangsey <in.reangsey@gmail.com>
| | Date:   Fri Dec 19 11:47:08 2025 +0100
| |
| |     readme modif reangsey
| |
* | commit 9dfb13d377da91496948ab179bd8e041a49bf3b7
|/  Author: Aboo-Dany <arshaadjkhan97400@gmail.com>
|   Date:   Fri Dec 19 11:33:11 2025 +0100
|
|       ajout tp.md arshaad
|
* commit 0a73267cd34828c5dc7a977cabcd3a7af45ace01 (master)
| Author: Sarah Schlegel <sschlegel@myges.fr>
| Date:   Wed Nov 12 22:01:27 2025 +0100
|
|     Instructions TP Final
|
*   commit 767f380a5bb96234debe23e6eb9cc6e3ccda2e43
|\  Merge: a8be53b e2dd662
| | Author: Sarah Schlegel <sschlegel@myges.fr>
| | Date:   Wed May 25 18:39:15 2022 +0200
| |
| |     Merge pull request #1 from SarahSch19/develop
:'




'



2) Différence entre git fetch et git pull

git fetch récupère les mises à jour du remote (branches, commits) sans modifier ma branche locale.
git pull = git fetch + merge (ou rebase selon config) pour mettre à jour ma branche locale automatiquement.


3) Différence entre git reset et git revert

git revert crée un nouveau commit qui annule un commit précédent.
git reset déplace HEAD  et en --hard modifie aussi le working directory.