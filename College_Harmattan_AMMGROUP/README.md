# Collège L’Harmattan — AMMGROUP Digital

Site public et prototype de plateforme scolaire. Devise : Travail, Maîtrise, Droiture.

## Lancer le projet

Aucune installation de dépendances n’est nécessaire. Depuis la racine :

```sh
python3 -m http.server 8080 --directory dist
```

Ouvrir http://localhost:8080 dans le navigateur.

## Contenu

- Site public : présentation, sections, actualités, galerie, règlement et contacts.
- Admissions : parcours par section et classe, fiche familiale imprimable.
- Administration : élèves, enseignants, horaires, résultats et démonstration de paiements.
- Espace parents : enfants rattachés, bulletins publiés, horaires, communications, punitions et convocations ; réponses et accusés de réception.
- Cahier des charges : docs/Cahier_des_charges_College_Harmattan_AMMGROUP.docx.

## État du prototype

Les rôles sont sélectionnables à des fins de présentation. Les données fictives sont enregistrées dans le localStorage du navigateur (clé harmattan-demo-v2). Elles ne sont pas partagées entre appareils. Il n’existe pas encore de serveur, de base de données, d’authentification sécurisée ni de contrôle d’accès serveur. Les formulaires d’admission ne transmettent aucune demande. Les confirmations de paiement et les communications sont simulées dans l’interface ; aucun SMS ni e-mail réel n’est envoyé. Les bulletins présentés sont des exemples non officiels.

Pour une utilisation réelle : développer le serveur, les comptes et permissions, la gestion des données, les sauvegardes et les notifications ; faire valider les règles scolaires et financières par le collège.

## Organisation

Le dossier dist contient les fichiers statiques directement exécutables. Le fichier .openai/hosting.json correspond au rattachement à l’hébergement Sites existant. Les provenances des images sont indiquées dans dist/assets/college/sources.json ; leur utilisation pour la présentation reste soumise à validation éditoriale. Aucune licence de redistribution des contenus du collège n’est accordée par ce dépôt.
