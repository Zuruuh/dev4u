# User stories

## Contexte:
Un visiteur est une personne qui n'a pas encore de compte.
Un membre a un compte mais n'est pas connecté.
Un utilisateur a un compte et est connecté
Un enseignant est un utilisateur qui est un enseignant
Un étudiant est un utilisateur qui est un étudiant

## Authentification

Fonctionnalité: Connexion
En tant que: membre
Je veux: me connecter en utilisant mon e-mail et mon mot de passe.
Pour que je puisse: accéder au reste de l'application
Fonctionnalité validée si: Je peux accéder au reste de l'application

Fonctionnalité: Inscription
En tant que: visiteur
Je veux: m'inscrire en utilisant mon adresse électronique, mon mot de passe et mon nom complet.
Pour que je puisse: me connecter
Fonctionnalité validée si: Je peux me connecter avec les mêmes identifiants.

Fonctionnalité: Déconnexion
En tant que: utilisateur
Je veux: me déconnecter
Pour que je puisse: me connecter avec un autre compte
Fonctionnalité validée si: Je ne peux pas accéder au reste de l'application

Fonctionnalité: Réinitialiser le mot de passe
En tant que: membre
Je veux: réinitialiser mon mot de passe
Pour que je puisse: me reconnecter
Fonctionnalité validée si: Je reçois un e-mail avec un lien pour réinitialiser mon mot de passe, et je peux me connecter avec ce mot de passe.

Fonctionnalité: Supprimer mon compte
En tant que: utilisateur
Je veux: supprimer mon compte
Fonctionnalité validée si: Je ne peux plus me connecter en utilisant mes anciens identifiants.

## Calendrier

Fonctionnalité: Afficher tous les événements pour une période donnée
En tant que: utilisateur
Je veux: afficher tous les événements prévus dans mon calendrier pour cette semaine.
Pour que je puisse: organiser mon planning de la semaine
Fonctionnalité validée si: Je peux voir les événements

Fonctionnalité: Créer un nouvel événement pour moi-même
En tant que: utilisateur
Je souhaite: créer un nouvel événement pour moi-même
Pour que je puisse: ne pas l'oublier
Fonctionnalité validée si: Je peux créer un événement et je peux le voir. 

Fonctionnalité: Créer un nouvel événement pour mon élève
En tant que: enseignant
Je souhaite: créer un nouvel événement pour un de mes élèves
Pour que je puisse: rencontrer mon élève lorsqu'il est disponible.
Fonctionnalité validée si: lors de la création d'un nouvel événement, je peux choisir un élève à qui assigner cet événement, et il peut voir l'événement dans son calendrier.

## Tâches

Fonctionnalité: Créer une nouvelle tâche pour moi-même
En tant que: utilisateur
Je veux: créer une nouvelle tâche pour moi-même
Pour que je puisse: ne pas l'oublier
Fonctionnalité validée si: Je peux créer une tâche et je peux la voir. 

Fonctionnalité: Créer une nouvelle tâche pour mon élève
En tant que: enseignant
Je veux: créer une nouvelle tâche pour l'un de mes élèves.
Pour que je puisse: assigner à mon élève un travail à faire pour la prochaine session
Fonctionnalité validée si: lors de la création d'une tâche, je peux choisir un élève à qui assigner cette tâche, et il peut voir la tâche dans son tableau de bord.

## Chat

Fonctionnalité: Afficher mes chats
En tant que: utilisateur
Je veux: voir toutes mes discussions ouvertes
Pour que je puisse: en choisir une et parler avec mon interlocuteur
Fonctionnalité validée si: Je peux cliquer sur un chat et voir les précédents messages échangés.

Fonctionnalité: Envoyer un message
En tant que: utilisateur
Je veux: envoyer un message à quelqu'un d'autre
Pour que je puisse: Discuter avec lui de mes études
Fonctionnalité validée si: Je peux envoyer un message à quelqu'un et il reçoit une notification et peut le lire.

## Tableau de bord

Fonctionnalité: Afficher le résumé des tâches
En tant que: utilisateur
Je veux: voir toutes les tâches qui me sont attribuées.
Pour que je puisse: m'organiser pour les terminer
Fonctionnalité validée si: Je peux voir toutes les tâches qui me sont assignées et qui ne sont pas marquées comme étant terminées.

Fonctionnalité: Voir le résumé des événements
En tant que: utilisateur
Je souhaite: voir tous les événements auxquels je participe
Pour que je puisse: ne pas les oublier et être présent à l'heure.
Fonctionnalité validée si: Je peux voir tous les événements auxquels je participe et qui n'ont pas encore eu lieu.

