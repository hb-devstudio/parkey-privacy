# Politique de Confidentialité - Parkey

**Dernière mise à jour :** 15 novembre 2025  
**Version :** 1.1

## 1. Introduction

Parkey ("nous", "notre", "nos") s'engage à protéger et respecter votre vie privée. Cette politique de confidentialité explique comment nous collectons, utilisons, stockons et protégeons vos données personnelles lorsque vous utilisez notre application mobile Parkey (l'**Application**).

En utilisant l'Application, vous acceptez les pratiques décrites dans cette politique. Si vous n'acceptez pas cette politique, veuillez ne pas utiliser l'Application.

## 2. Responsable du Traitement

**Nom :** Parkey  
**Contact :** support@parkey.eu  
**Application ID :** com.HBApps.parkey

## 3. Données Personnelles Collectées

### 3.1 Données d'Identification et de Compte

Lors de votre inscription, nous collectons :
- **Adresse email** (obligatoire pour l'authentification)
- **Nom complet**
- **Numéro de téléphone**
- **Mot de passe** (hashé et stocké de manière sécurisée)
- **Identifiant utilisateur unique** (UUID généré automatiquement)
- **Rôle** (propriétaire/locataire/utilisateur)

### 3.2 Données de Géolocalisation

Pour vous permettre de rechercher et de publier des places de parking, nous collectons :
- **Position GPS** (latitude et longitude avec précision fine)
- **Adresse complète** dérivée de la géolocalisation
- **Ville**

**Permissions requises :**
- Accès à la localisation précise (`ACCESS_FINE_LOCATION`)
- Accès à la localisation approximative (`ACCESS_COARSE_LOCATION`)

### 3.3 Données de Réservation

Lors d'une réservation, nous collectons :
- Identifiant de réservation
- Identifiant de la place de parking
- Identifiants du locataire et du propriétaire
- Dates et heures de début et de fin
- Montant total et devise (EUR)
- Caution (si applicable)
- Statut de la réservation
- Notes du locataire et du propriétaire
- Identifiant de transaction Stripe
- Horodatage des actions (création, modification, annulation)

### 3.4 Données de Paiement

**Important :** Nous ne collectons jamais directement vos informations de carte bancaire. Toutes les transactions sont gérées par Stripe, un processeur de paiement certifié PCI-DSS Level 1.

Nous stockons uniquement :
- Identifiant de transaction Stripe (Payment Intent ID)
- Montant et devise de la transaction
- Statut du paiement

Les données de carte bancaire sont traitées exclusivement par Stripe et ne sont jamais stockées dans notre système.

### 3.5 Données d'Annonces de Parking

Lors de la création d'une annonce, nous collectons :
- Titre et description de la place
- Adresse complète et coordonnées GPS
- Prix et type de tarification (minute/heure/jour/mois)
- Jusqu'à 5 photos de la place
- Caractéristiques (couvert, sécurisé, prise électrique, etc.)
- Disponibilité et plages horaires

### 3.6 Données de Messagerie

Lors des conversations entre utilisateurs, nous collectons :
- Contenu des messages échangés
- Horodatage des messages
- Identifiants des participants

### 3.7 Données de Notifications

Pour vous envoyer des notifications push, nous collectons :
- Token de notification push (identifiant unique de l'appareil)
- Préférences de notification

### 3.8 Données Techniques

Nous collectons automatiquement :
- Adresse IP (pour la sécurité)
- Type d'appareil et système d'exploitation
- Version de l'application
- Logs d'erreurs (en cas de problème)
- Données de connexion (horodatage)

## 4. Finalités du Traitement

Nous utilisons vos données personnelles pour :

### 4.1 Exécution du Contrat (Base Légale : Art. 6.1.b RGPD)
- Gérer votre compte utilisateur
- Traiter vos réservations
- Exécuter les transactions de paiement
- Faciliter la communication entre propriétaires et locataires
- Gérer vos annonces de parking

### 4.2 Intérêt Légitime (Base Légale : Art. 6.1.f RGPD)
- Assurer la sécurité de la plateforme et prévenir la fraude
- Améliorer nos services en analysant les logs d'erreurs
- Communiquer avec vous concernant votre compte (emails transactionnels)

### 4.3 Consentement (Base Légale : Art. 6.1.a RGPD)
- Envoyer des notifications push (avec votre consentement)
- Accéder à votre géolocalisation (avec votre autorisation)
- Accéder à votre caméra/galerie pour les photos (avec votre autorisation)
- Afficher des publicités personnalisées (avec votre consentement)

### 4.4 Obligation Légale (Base Légale : Art. 6.1.c RGPD)
- Conserver les données de transaction conformément aux obligations légales
- Respecter les obligations comptables et fiscales

## 5. Partage de Données avec des Tiers

Nous partageons vos données avec les services tiers suivants pour assurer le fonctionnement de l'Application :

### 5.1 Supabase (Backend & Base de Données)
- **Service :** Infrastructure backend et base de données
- **Données partagées :** Toutes vos données personnelles, réservations, annonces, messages, images
- **Politique de confidentialité :** https://supabase.com/privacy
- **Conformité :** RGPD, SOC 2 Type II

### 5.2 Stripe (Paiements)
- **Service :** Traitement des paiements
- **Données partagées :** Informations de paiement (carte bancaire, montants), identifiants de transaction
- **Politique de confidentialité :** https://stripe.com/privacy
- **Conformité :** PCI-DSS Level 1, RGPD

### 5.3 Resend (Envoi d'Emails)
- **Service :** Service d'envoi d'emails transactionnels
- **Données partagées :** Adresses email, contenu des emails de confirmation
- **Politique de confidentialité :** https://resend.com/legal/privacy-policy
- **Conformité :** RGPD

### 5.4 Google Maps (Cartographie)
- **Service :** Affichage de cartes et géolocalisation
- **Données partagées :** Position GPS, adresses recherchées, coordonnées des places
- **Politique de confidentialité :** https://policies.google.com/privacy
- **Conformité :** RGPD

### 5.5 Google AdMob (Publicités)
- **Service :** Affichage de publicités (actuellement en mode test)
- **Données partagées :** Identifiant publicitaire, données d'utilisation pour le ciblage
- **Politique de confidentialité :** https://policies.google.com/privacy
- **Conformité :** RGPD, COPPA

### 5.6 Firebase Cloud Messaging (Notifications)
- **Service :** Envoi de notifications push
- **Données partagées :** Token de notification, contenu des notifications
- **Politique de confidentialité :** https://policies.google.com/privacy
- **Conformité :** RGPD

**Nous ne vendons jamais vos données personnelles à des tiers.**

## 6. Durées de Conservation

### 6.1 Données de Compte
- **Durée :** Pendant toute la durée d'utilisation + 3 ans après la dernière connexion
- **Suppression :** Suppression automatique après 3 ans d'inactivité ou sur demande

### 6.2 Données de Réservation
- **Durée :** 5 ans après la fin de la réservation (obligation légale)
- **Suppression :** Anonymisation après 5 ans

### 6.3 Données de Paiement
- **Durée :** 10 ans (obligation légale française pour les données comptables)
- **Stockage :** Stripe conserve les données conformément à ses obligations légales

### 6.4 Données de Messagerie
- **Durée :** 1 an après la fin de la réservation associée
- **Suppression :** Suppression automatique après 1 an

### 6.5 Images et Photos
- **Durée :** Tant que l'annonce est active + 1 an après suppression
- **Suppression :** Suppression automatique lors de la suppression de l'annonce

### 6.6 Logs et Données Techniques
- **Durée :** 12 mois
- **Suppression :** Rotation automatique des logs

## 7. Sécurité des Données

Nous mettons en œuvre des mesures techniques et organisationnelles appropriées pour protéger vos données :

### 7.1 Mesures Techniques
- **Chiffrement en transit :** Toutes les communications utilisent HTTPS/TLS
- **Chiffrement au repos :** Base de données chiffrée
- **Authentification sécurisée :** Hashage des mots de passe (bcrypt)
- **Contrôle d'accès :** Row Level Security (RLS) au niveau de la base de données
- **Paiements sécurisés :** Stripe conforme PCI-DSS Level 1
- **Stockage sécurisé :** Images stockées dans Supabase Storage avec contrôle d'accès

### 7.2 Mesures Organisationnelles
- Accès restreint aux données (personnel autorisé uniquement)
- Formation du personnel aux bonnes pratiques de sécurité
- Audits réguliers de sécurité

## 8. Vos Droits (RGPD)

Conformément au Règlement Général sur la Protection des Données (RGPD), vous disposez des droits suivants :

### 8.1 Droit d'Accès (Art. 15 RGPD)
Vous pouvez demander une copie de toutes vos données personnelles que nous détenons.

### 8.2 Droit de Rectification (Art. 16 RGPD)
Vous pouvez corriger vos données personnelles directement dans l'Application ou en nous contactant.

### 8.3 Droit à l'Effacement (Art. 17 RGPD)
Vous pouvez demander la suppression de vos données personnelles, sous réserve des obligations légales de conservation.

**Pour demander la suppression de votre compte :** Consultez notre [guide de suppression de compte](https://github.com/hb-devstudio/parkey-privacy/blob/main/ACCOUNT_DELETION.md) qui détaille la procédure complète, les données supprimées, celles conservées et leurs durées de conservation.

### 8.4 Droit à la Limitation du Traitement (Art. 18 RGPD)
Vous pouvez demander la limitation du traitement de vos données dans certains cas.

### 8.5 Droit à la Portabilité (Art. 20 RGPD)
Vous pouvez récupérer vos données dans un format structuré et les transférer à un autre service.

### 8.6 Droit d'Opposition (Art. 21 RGPD)
Vous pouvez vous opposer au traitement de vos données pour des motifs légitimes.

### 8.7 Droit de Retirer le Consentement
Vous pouvez retirer votre consentement à tout moment (notifications, géolocalisation, etc.) via les paramètres de l'Application.

### 8.8 Droit de Déposer une Réclamation
Vous pouvez déposer une réclamation auprès de la CNIL (Commission Nationale de l'Informatique et des Libertés) :
- **Site web :** https://www.cnil.fr
- **Adresse :** 3 Place de Fontenoy - TSA 80715 - 75334 PARIS CEDEX 07

**Pour exercer vos droits :**
- **Email :** support@parkey.eu
- **Délai de réponse :** 30 jours maximum

**Suppression de compte :** Si vous souhaitez supprimer votre compte et toutes les données associées, consultez notre [guide de suppression de compte](https://github.com/hb-devstudio/parkey-privacy/blob/main/ACCOUNT_DELETION.md).

## 9. Transferts de Données Internationaux

Certains de nos partenaires peuvent stocker des données hors de l'Union Européenne :

- **Stripe** : États-Unis (conformité RGPD via Privacy Shield et clauses contractuelles)
- **Google** : États-Unis (conformité RGPD via Privacy Shield et clauses contractuelles)
- **Resend** : États-Unis (conformité RGPD via clauses contractuelles)

Tous nos partenaires sont conformes au RGPD et des garanties appropriées sont en place pour sécuriser ces transferts.

## 10. Cookies et Technologies Similaires

L'Application mobile n'utilise pas de cookies au sens traditionnel, mais utilise :

- **Tokens d'authentification** : Stockés localement pour maintenir votre session
- **Identifiants d'appareil** : Pour les notifications push
- **Cache local** : Stockage temporaire pour améliorer les performances

## 11. Protection des Mineurs

L'Application n'est **pas destinée aux enfants de moins de 18 ans**. Nous ne collectons pas sciemment de données personnelles d'enfants. Si vous êtes parent et que vous pensez que votre enfant nous a fourni des données personnelles, contactez-nous immédiatement à support@parkey.eu.

## 12. Communications Marketing

Nous pouvons vous envoyer des emails promotionnels uniquement si vous avez donné votre consentement. Vous pouvez vous désabonner à tout moment :

- En cliquant sur le lien de désabonnement dans l'email
- En modifiant vos préférences dans l'Application
- En nous contactant à support@parkey.eu

## 13. Modifications de cette Politique

Nous nous réservons le droit de modifier cette politique de confidentialité à tout moment. Les modifications seront publiées dans l'Application et sur cette page. La date de dernière mise à jour sera indiquée en haut du document.

Nous vous encourageons à consulter régulièrement cette page pour rester informé de nos pratiques.

## 14. Contact

Pour toute question concernant cette politique de confidentialité ou pour exercer vos droits :

**Email :** support@parkey.eu  
**Délai de réponse :** 30 jours maximum

---

## 15. Liens Utiles

- **[Suppression de compte](https://github.com/hb-devstudio/parkey-privacy/blob/main/ACCOUNT_DELETION.md)** : Guide complet pour demander la suppression de votre compte et comprendre quelles données sont supprimées ou conservées.


**Dernière mise à jour :** 15 novembre 2025

