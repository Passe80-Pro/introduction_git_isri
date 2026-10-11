# Rédigé par Nathan Bonnard et Ishak Haithem Hamadat

![git log final](Screens/Git%20log%20final.png)

Question 1) La commande `git push --force-with-lease` effectue la même action que la commande `git push --force`, à la seule différente que l'option `--force-with-lease` vérifie que la branche distante, qu'on s'apprête à écraser, n'a pas été modifiée par une autre personne, ce qui permet d'éviter d'écraser le travail d'un collègue.

Question 2) La commande `git merge` modifie la branche en créant un commit de merge (sauf si un fast-forward est possible). `git rebase` permet de récupérer les modifications d'une branche source sans la modifier, tout en gardant un historique de commits plus propre.

Question 3) Imposer un squash des commits avant la fusion d'une Pull Request permet dans un premier temps d'obtenir une PR plus lisible pour le reviewer, puisque toutes les modifications seront visibles depuis un seul commit, et dans un second temps de ne garder qu'un commit par feature, ce qui rend l'historique de commits final lui aussi plus lisible, avec un commit par feature.

----

Gitlog Nathan Lasorne :

![Capture git log](./Screens/Gitlog_NLasorne.png)

Git rebase Nathan Lasorne :
![Capture git rebase](./Screens/GitRebase_NLasorne.png)

Git log après git rebase Nathan Lasorne
![Capture git log après rebase](./Screens/GitLog_ApresRebase_NLasorne.png)

image de ishak

![image](./Capture%20d'écran%202026-10-07%20122839.png)

image de ishak

![image](./Capture%20d'écran%202026-10-07%20122951.png)
