
# Procédure – Configuration SMTP Gmail avec EasyE4

## Objet
Décrire la procédure permettant d’utiliser le serveur SMTP Gmail avec EasyE4.

## Résumé
Les tests réalisés montrent que l’envoi d’emails via Gmail avec EasyE4 fonctionne correctement **à condition d’utiliser un mot de passe d’application Gmail**.
Cette contrainte est liée à l’activation obligatoire de la double authentification (2FA) chez Gmail.

## Prérequis
- Un compte Gmail valide
- Accès à la gestion du compte Google
- Validation en deux étapes (2FA) activée

## Procédure de création du mot de passe d’application Gmail
1. Se connecter au compte Gmail concerné
2. Aller dans **Gestion du compte Google**
3. Ouvrir l’onglet **Sécurité**
4. Activer la **Validation en deux étapes** (si ce n’est pas déjà fait)
5. Une fois la validation activée, accéder à **Mots de passe des applications**
6. Créer un nouveau mot de passe pour l’application (exemple : EasyE4)
7. Copier le mot de passe généré

⚠️ Ce mot de passe doit être utilisé à la place du mot de passe Gmail classique.

## Paramètres SMTP Gmail à configurer dans EasyE4
- Serveur SMTP : smtp.gmail.com
- Port : 465
- Sécurité : SSL / TLS
- Login : adresse Gmail complète (ex. prenom.nom@gmail.com)
- Mot de passe : mot de passe d’application Gmail

## Résultat
Avec cette configuration :
- Les emails sont envoyés correctement
- Les tests sont concluants vers des adresses Gmail et autres

## Remarque importante
Sans mot de passe d’application, l’authentification SMTP Gmail échouera.
