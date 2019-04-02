# Mise en ligne d'un site sur github

Les differents étapes:

- créer un repo pour accueillir les différentes pages(fichiers) de ton site
le fichier readme.md est la page par defaut du site pour definir une autre il faut faire une redirection depuis cette page vers une autre 
exemple [rapportjour1](rapportjour.md)


- choisir un theme et le forker ie faire une copie pour tavailler dessus

- modifier le fichier config.yml en faisant remote_theme nom du theme ou on a forker le theme il se trouve sur notre repertoire github
dont on on le verra ici  pseudogithub/nomtheme

- cloner le theme en local pour le modifier ou le modiffier directement sur github:
soit on le fait via un editeur de code comme visual on va dans view->pallette et on tape >clone et ensuite lien vers dossier a cloner
soit on le fait depuis git via les commandes
-dans le dossier sass on a les fichier de style 
et dans l'assets on a les import des fichiers defini dans le sass

- les differents fichiers qui representent les pages sont cree dans notres repo de site avec l'extension markdown
- important :pour commiter et voir un changement il faut modifier le fichier de la page a mis en ligne
