Repérez les fichiers ou dossiers suivants (selon votre environnement) :
```
__pycache__/
.venv/
venv/
*.pyc
```
. Répondez par écrit :
**À quoi servent ces fichiers ?**
Ces fichiers servent soit à accélérer le démarrage de Python (cache compilé), soit à isoler les librairies du projet.

**Pourquoi ces fichiers ne devraient-ils pas être versionnés dans un dépôt Git ?**

Ils ne doivent pas être versionnés car ils sont générés automatiquement, souvent lourds.

**les fichiers sont-ils toujours visibles sur GitHub ?**

Non

**apparaissent-ils encore dans VS Code ?**

Oui

**À quel moment faut-il créer un .gitignore ?**

Dès le début du projet, idéalement avant le tout premier commit.

**Que fait exactement lʼoption --cached ?**

Elle retire le fichier du suivi de Git mais le garde intact sur le disque dur.

**Que se passerait-il sans --cached ?**

Le fichier est supprimé de Git et effacé physiquement de l'ordinateur.

