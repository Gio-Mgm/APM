# Monitoring d'application APM

## En quoi consiste ce sujet? 

Le monitoring d'application est une forme de surveillance synthétique qui test et vérifie régulièrement le bon fonctionnement d’un site Web lors de la réponse aux entrées de l’utilisateur, comme la connexion ou l’achat.

Une APM charge l’application Web dans un navigateur et, à l’aide d’un script d’automatisation, l’application exécute les interactions utilisateur et rapporte les performances de l’application Web et envoie des alertes en cas d’erreur.

## A quoi cela sert?

Les tests effectués derrière le pare-feu ne permettent pas de détecter les erreurs spécifiques aux emplacements géographique utilisateur, telles que les réponses lentes du serveur et les CDN défaillants (Content Delivery Network).

Les tests d'APM éliminent les points de défaillance introduits par les tests internes en faisant en sorte qu’un réseau mondial d’ordinateurs effectue les tests aussi souvent que toutes les cinq minutes.

## Sur quelle partie d’un projet faut-il le mettre en place? A quel moment du projet faut il le mettre en place?

Lorsque l'application est en production.

Le Monitoring d’Application Web peut répliquer la plupart des interactions de routine, notamment:

+ Naviguer sur un site
+ Connexion à un compte
+ Déconnexion d’un compte
+ Récupération d’ID et de mot de passe
+ Effectuer une recherche
+ Ajouter des objets au panier d’achat
+ Remplir des formulaires
+ Compléter une transaction financière

## Au moins 5 mots de vocabulaires propres à ce domaine qui permettent de mieux le comprendre?

Le Real User Monitoring (RUM) est une approche passive du monitoring de performance de site Web qui collecter et reporte les données de performance tel que vos utilisateurs actuels en font l’expérience.

## Comment le réaliser? quels sont les outils? quels sont les différents étapes?

Pour faciliter la surveillance des applications Web, les services identifient d’abord leurs «parcours de satisfaction».

Le service de surveillance construit un script basé sur le bon chemin. Le service de surveillance utilise le script pour effectuer des tests réguliers afin de s’assurer que les fonctionnalités et les performances répondent aux attentes. 

Par exemple, pour vérifier que le processus de connexion fonctionne correctement, le point de contrôle de l’ordinateur distant va :

+ Accéder à la page de connexion à l’aide d’un navigateur
+ Entrer un identifiant utilisateur
+ Entrer un mot de passe
+ Cliquer sur soumettre
+ Attendre la réponse
+ Signaler les résultats à la société de surveillance des applications Web

Si l’ordinateur du point de contrôle signale un comportement de transaction inattendu, tel qu’un contenu de page manquant ou des réponses en échec ou lentes, le service de surveillance envoie une alerte à l’équipe de support du site Web ou du service Web.


### Quelques outils 

+ Uptime Robot
+ Updown.io
+ StatusCake
+ Uptrends


## Lien vers un tuto jugé pertinent concernant ce sujet.

https://www.youtube.com/watch?v=AOCzoTR_pbc
