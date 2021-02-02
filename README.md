# Projet de design I

Le rapport est sur Overleaf.

### Workflow git

Si vous voulez modifier le diagramme de Gantt ou tout autre fichier du dépôt:

1. Clone le projet sur ton ordi si c'est pas déjà fait:
   ```
   git clone https://github.com/nimal27/gel-1001
   ```
   Si c'est déjà fait alors fait juste pull:
   ```
   git pull
   ```

2. Change le fichier que tu veux changer et après fait un commit:
   ```
   git add <fichier>
   git commit -m "<message descriptif svp>"
   ```

3. Push. La première fois tu vas devoir faire:
   ```
   git push origin -u master
   ```
   Les autres fois juste:
   ```
   git push
   ```

4. S'il y a des conflits, soit tu dois pull, résoudre les conflits, faire un
   autre commit, et push encore:
   ```
   git pull
   # s'il y a des conflits, les résoudre, puis:
   git merge --continue
   <entrer le message du commit et quitter>
   git push
   ```
   Merci de ne *jamais* force-push. Si vous avez des questions posez les moi.
