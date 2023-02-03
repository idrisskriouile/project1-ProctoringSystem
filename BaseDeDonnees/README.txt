Liste des tables base de donnée
1.	Il y a une table pour stocker les informations des examens tels que le nom de l'examen, la date de l'examen, la durée de l'examen, etc.
2.	Il y a une table pour stocker les informations des séances d'examen tels que l'identifiant de l'examen, l'identifiant de l'utilisateur, la date de début de l'examen, la date de fin de l'examen, etc.
3.	Il y a une table pour stocker les informations de surveillance vidéo tels que l'identifiant de la séance d'examen, l'URL de la vidéo, les informations de détection de tricherie, etc.
4.	Il y a une table pour stocker les informations de résultats de l'examen tels que l'identifiant de la séance d'examen, les réponses de l'utilisateur, les scores, etc.
5.	Il y a une table pour stocker les informations de détection de tricherie tels que l'identifiant de la séance d'examen, les résultats de la détection de tricherie, les actions prises, etc.
6.	Il y a des relations de clé étrangère pour assurer la cohérence des données entre les différentes tables.
7.	Il y a des index pour améliorer les performances des requêtes de sélection.
8.	Il y a des triggers pour automatiser certaines tâches de la base de données comme l'audit.
9.	Il y a des sauvegardes automatiques pour assurer la disponibilité et la récupération des données.
10.	Table des règles de détection de tricherie : Cette table stockera les règles utilisées pour détecter les comportements suspects lors des examens. Elle pourrait contenir des informations telles que les actions à entreprendre lorsqu'une règle est violée, les critères de détection associés à chaque règle, etc.
11.	Table des événements de surveillance : Cette table stockera les informations relatives aux événements de surveillance, tels que les alertes générées par les règles de détection de tricherie, les actions entreprises pour gérer ces alertes, les détails de l'événement, etc.
12.	Table des paramètres de configuration: Cette table stockera les paramètres de configuration utilisés par le système de proctoring, tels que les paramètres de surveillance vidéo, les paramètres de détection de tricherie, les paramètres de l'interface utilisateur, etc.
13.	Table des utilisateurs administrateurs : Cette table stockera les informations relatives aux utilisateurs administrateurs du système de proctoring, tels que le nom d'utilisateur, le mot de passe, les autorisations, etc.
14.	Table des journaux : Cette table stockera les journaux d'activité du système, tels que les actions effectuées par les utilisateurs, les alertes générées, les erreurs, etc.
15.	Table des statistiques : Cette table stockera les statistiques relatives au système de proctoring, telles que les nombres d'examens, les nombres de sessions d'examen, les scores moyens, etc.
16.	Table des paramètres de sécurité : Cette table stockera les paramètres de sécurité utilisés pour protéger les données du système de proctoring, tels que les informations d'authentification, les politiques de mot de passe, les paramètres de chiffrement, etc.
17.	Table des notifications : Cette table stockera les informations relatives aux notifications envoyées aux utilisateurs, tels que les sujets des notifications, les contenus, les statuts de notifications,
18.	Table des paramètres de l'examen: Cette table stockera les paramètres de chaque examen tels que les questions, les options de réponse, les réponses correctes, les scores, les paramètres de timing, etc.
19.	Table des paramètres d'enregistrement : Cette table stockera les paramètres d'enregistrement utilisés pour enregistrer les sessions d'examen, tels que la résolution de la vidéo, le taux de rafraîchissement, les paramètres audio, etc.
20.	Table des paramètres de surveillance: Cette table stockera les paramètres de surveillance utilisés pour surveiller les sessions d'examen, tels que les paramètres de reconnaissance faciale, les paramètres de reconnaissance d'empreintes digitales, les paramètres de reconnaissance de mouvements, etc.
21.	Table des paramètres de détection de tricherie : Cette table stockera les paramètres de détection de tricherie utilisés pour détecter les comportements suspects lors des sessions d'examen, tels que les paramètres de reconnaissance de codes à barres, les paramètres de reconnaissance de documents, les paramètres de reconnaissance de mouvements, etc.
22.	Table des paramètres de notification: Cette table stockera les paramètres de notification utilisés pour envoyer des notifications aux utilisateurs, tels que les paramètres de notification par courriel, les paramètres de notification par SMS, les paramètres de notification par application mobile, etc.
23.	Table des paramètres de sauvegarde : Cette table stockera les paramètres de sauvegarde utilisés pour sauvegarder les données du système de proctoring, tels que les paramètres de sauvegarde automatique, les paramètres de sauvegarde manuelle, les paramètres de sauvegarde à distance, etc.

