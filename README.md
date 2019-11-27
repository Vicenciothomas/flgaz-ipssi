## Que propose le site PythonAnywhere.com ?

Pythonanywhere est un PAAS en Cloud, ce qui signifie que vous pouvez simplement vous soucier du codage et laisser l'hébergement de la plate-forme, de la DB et des considérations PAAS sur pythonanywhere.

PythonAnywhere est utilisé pour faire la plupart des choses que vous pouvez faire sur votre ordinateur avec Python. 
  - Démarrer une console interactive Python (depuis l'onglet "Consoles")
  - Editer un fichier python et l'exécuter (depuis l'onglet "Files")
  - Héberger une application Web ("Web") 
  - Programmer des tâches à exécuter à intervalles réguliers ("Tasks"). 
  - Creer et gérer des base de données ("Databases")
Si vous passez à un compte premium, vous pouvez également utiliser "Jupyter Notebooks", qui sont populaires dans la communauté scientifique.

## Qu'est ce que FLASK ? Quels sites connus utilisent Flask ?

Flask est un framework/application web Python inspiré du framework Sinatra ruby et disponible sous licence BSD.

C'est un outil qui permet de créer des sites plus rapidement. Flask accélère le développement en offrant du code pour toutes sortes de processus comme l'interaction avec les bases de données ou l'activité des fichiers.

Il a un noyau simple, avec un grand nombre d'extensions qui aident à bien l'intégrer.

Liste de site utilisant Flask :
 - Netflix
 - PythonAnywhere
 - Lyft
 - Reddit
 - Mozilla
 - Patreon
 - Uber
 - Samsung
 
Ce framework est développée et entretenue de façon active.
 
# Description des actions réalisées 
## Quelles étapes avez-vous suivi ?
 
1. Création des comptes sur github et Pythonanywhere
2. Création d'un repository github flgaz-ipssi
3. git clone du repository sur mon poste
4. Sur mon terminal : git init sur le dossier que je veux mettre sur le github > git commit > git push
5. Retour sur Pythonanywhere, ouverture d'un site web Flask à partir de l'onglet "Web"
6. Ouverture d'une console > cd mysite/ > git clone https://github.com/Vicenciothomas/flgaz-ipssi.git 
7. Cliquer sur l'onglet Web, changer le WSGI configuration file: /var/www/juantacos_pythonanywhere_com_wsgi.py 
  > Modifier la ligne 16 afin de faire tourner le app.py au lieu de flask_app.py
8. Modifier dans l'onglet Web le Working depository : /home/juantacos/mysite 
9. Teste du site web : http://juantacos.pythonanywhere.com/gaz || http://juantacos.pythonanywhere.com/timeline
 
## Quelles difficultés avez-vous rencontrées ?

- Découverte de Github et de ses fonctions
- Découverte de la navigation sur Pythonanywhere mais intuitif en général

# Réflexions sur le projet 
## Quels sont, selon vous, les aspects techniques limitants du projet FLGAZ dans l'état initial ?
 
- Pas de compte afin de créer un poste
- Pas de limite de caractères par poste
- Pas sécurisé contre le spam
- Impossible de mettre des images / vidéos
 
## Quelles sont, selon vous, les menaces auxquelles un tel projet peut être soumis ?

- Problème de message insultants
- Discriminations
- Usurpation d'identité
- Fake news
