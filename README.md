Ce programme est une application de gestion de comptes bancaires utilisant une liste chaînée de structures NoeudCompte. Voici un résumé de ses fonctionnalités :

Structures et Fonctions
Struct. NoeudCompte :

Compte bancaire avec numéro, nom client, solde, et lien au compte suivant.
Fonc. ouvrirCompte :

Crée un nouveau compte avec numéro, nom, et solde initial.
Fonc. afficherInfosCompte :

Affiche les détails d'un compte par son numéro.
Fonc. mettreAJourInfosCompte :

Met à jour le nom du client ou le solde d'un compte spécifique.
Fonc. transfertInterne :

Transfère un montant entre deux comptes.
Fonc. fermerCompte :

Ferme un compte spécifique.
Fonc. afficherListeClients :

Affiche la liste des clients.
Fonc. effectuerDepot et effectuerRetrait :

Effectue un dépôt ou un retrait sur un compte.
Fonc. donnerRating :

Requiert une évaluation de l'application.
Flux Principal
Menu interactif proposant les actions suivantes :

Ouvrir un compte
Afficher détails d'un compte
Mettre à jour infos d'un compte
Fermer un compte
Afficher liste des clients
Gestion transactions bancaires (dépôt, retrait)
Transfert entre comptes
Donner un rating à l'application
Quitter
Stockage des Données
Les infos des comptes sont sauvegardées dans un fichier (comptes.txt) pour persistance entre sessions.
