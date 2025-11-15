# 🗑️ Suppression de Compte - Parkey

**Application :** Parkey  
**Développeur :** Parkey  
**Contact :** support@parkey.eu

---

## 📋 Comment Demander la Suppression de Votre Compte

Si vous souhaitez supprimer votre compte Parkey et toutes les données associées, veuillez suivre la procédure suivante :

### Méthode 1 : Via Email (Recommandé)

1. **Envoyez un email** à **support@parkey.eu** avec les informations suivantes :
   - **Objet :** "Demande de suppression de compte"
   - **Contenu de l'email :**
     - Votre nom complet
     - L'adresse email associée à votre compte Parkey
     - Une confirmation que vous souhaitez supprimer votre compte et toutes les données associées
     - Optionnel : La raison de votre demande de suppression

2. **Vérification de votre identité :**
   - Pour des raisons de sécurité, nous vous demanderons de confirmer votre identité en répondant à quelques questions de sécurité.
   - Cette vérification peut inclure :
     - La confirmation de l'adresse email de votre compte
     - La date approximative de création de votre compte
     - Des informations sur vos dernières transactions

3. **Confirmation et traitement :**
   - Vous recevrez une confirmation par email dans les **48 heures** suivant votre demande.
   - Le traitement de la suppression commencera dans les **7 jours** suivant la confirmation.
   - Une notification finale vous sera envoyée une fois la suppression terminée.

### Méthode 2 : Via l'Application

1. Ouvrez l'application Parkey sur votre appareil
2. Allez dans **Profil** (icône en bas à droite)
3. Accédez aux **Paramètres**
4. Sélectionnez **Supprimer mon compte**
5. Confirmez votre demande en suivant les instructions affichées

**Note :** Cette fonctionnalité sera disponible dans une prochaine mise à jour de l'application.

---

## ⏱️ Délai de Traitement

- **Temps de réponse initial :** 48 heures maximum
- **Temps de traitement :** 7 jours maximum après confirmation
- **Notification finale :** Dans les 30 jours suivant votre demande

---

## 📊 Données Supprimées

Lors de la suppression de votre compte, **toutes les données personnelles suivantes seront supprimées définitivement** :

### ✅ Données Supprimées Immédiatement

1. **Données de Compte :**
   - Nom complet
   - Adresse email
   - Numéro de téléphone
   - Mot de passe (hashé)
   - Identifiant utilisateur unique (UUID)
   - Profil utilisateur (rôle, avatar, etc.)

2. **Données de Réservation Actives et Futures :**
   - Réservations en attente (`pending`)
   - Réservations acceptées mais non payées (`accepted`)
   - Réservations refusées (`refused`)
   - Réservations annulées (`cancelled`)

3. **Annonces de Parking :**
   - Toutes vos annonces de parking publiées
   - Photos associées aux annonces
   - Coordonnées GPS et adresses des places
   - Disponibilités et plages horaires

4. **Messages et Conversations :**
   - Toutes les conversations in-app
   - Tous les messages échangés
   - Historique de communication

5. **Données de Notification :**
   - Tokens de notification push (Firebase Cloud Messaging)
   - Préférences de notification
   - Historique des notifications

6. **Données Techniques :**
   - Cache local de l'application
   - Tokens d'authentification
   - Identifiants d'appareil (pour notifications)

---

## 🔒 Données Conservées (Conformément aux Obligations Légales)

Certaines données doivent être conservées pour des durées spécifiques conformément aux obligations légales (RGPD Art. 6.1.c, obligations comptables et fiscales) :

### 📝 Données de Réservation Historiques

**Durée de conservation :** **5 ans** après la fin de la réservation

**Données conservées (anonymisées) :**
- Identifiant de réservation (sans lien avec votre compte)
- Date et heure de début et de fin
- Montant total de la réservation
- Statut de la réservation (uniquement pour réservations terminées : `completed` ou `paid`)
- **Votre identité sera supprimée** : Le lien entre votre compte et ces données sera rompu

**Finalité :** Obligations légales de conservation des transactions commerciales

### 💰 Données de Paiement

**Durée de conservation :** **10 ans** après la transaction (obligation légale française pour les données comptables)

**Données conservées (anonymisées) :**
- Identifiant de transaction Stripe (Payment Intent ID)
- Montant et devise de la transaction
- Date de la transaction
- Statut du paiement
- **Votre identité sera supprimée** : Le lien entre votre compte et ces données sera rompu

**Finalité :** Obligations comptables et fiscales légales

**Note :** Les données de carte bancaire complètes sont stockées par Stripe (processeur de paiement certifié PCI-DSS Level 1) et ne sont jamais dans notre système. Vous devrez contacter Stripe directement si vous souhaitez demander la suppression de ces données, conformément à leur politique de confidentialité : https://stripe.com/privacy

### 📸 Photos et Images

**Durée de conservation :** **1 an** après la suppression de l'annonce associée

**Données conservées :**
- Photos des places de parking que vous avez publiées
- **Votre identité sera supprimée** : Les photos seront déliées de votre compte et conservées uniquement si elles sont encore liées à des réservations en cours ou futures

**Finalité :** Conservation nécessaire pour les réservations en cours et obligations légales de conservation

### 🔍 Logs et Données Techniques

**Durée de conservation :** **12 mois** maximum

**Données conservées (anonymisées) :**
- Logs d'erreurs et diagnostics techniques
- Adresses IP (anonymisées)
- **Votre identité sera supprimée** : Les logs ne seront plus associés à votre compte

**Finalité :** Amélioration du service et sécurité de la plateforme

---

## ⚠️ Conséquences de la Suppression de Compte

Avant de demander la suppression de votre compte, veuillez prendre en compte les conséquences suivantes :

### ❌ Ce que vous perdrez immédiatement :

1. **Accès à votre compte :** Vous ne pourrez plus vous connecter à l'application Parkey
2. **Vos annonces :** Toutes vos annonces de parking seront supprimées
3. **Réservations actives :** Si vous avez des réservations en cours :
   - **En tant que locataire :** Les réservations non payées seront annulées
   - **En tant que propriétaire :** Les réservations acceptées mais non payées seront annulées
4. **Historique de communication :** Toutes vos conversations seront supprimées
5. **Profil et préférences :** Tous vos paramètres et préférences seront perdus

### 🔄 Ce qui sera conservé temporairement :

1. **Réservations payées et terminées :** Conservées pendant 5 ans (anonymisées)
2. **Données de paiement :** Conservées pendant 10 ans (anonymisées)
3. **Photos liées à des réservations en cours :** Conservées jusqu'à la fin des réservations + 1 an

### 💡 Recommandations avant la suppression :

1. **Annulez vos réservations actives** si vous le souhaitez (via l'application)
2. **Supprimez vos annonces** si vous le souhaitez (via l'application)
3. **Exportez vos données** si vous souhaitez conserver certaines informations (voir section "Portabilité des Données" ci-dessous)
4. **Vérifiez vos réservations à venir** et assurez-vous qu'elles sont bien terminées ou annulées

---

## 📤 Portabilité des Données (Droit à la Portabilité - RGPD Art. 20)

Avant la suppression de votre compte, vous pouvez demander une copie de vos données personnelles dans un format structuré et lisible par machine.

### Comment demander vos données :

1. **Envoyez un email** à **support@parkey.eu** avec :
   - **Objet :** "Demande d'export de données"
   - Votre nom complet
   - L'adresse email associée à votre compte

2. **Format des données :**
   - Format JSON ou CSV (selon votre préférence)
   - Contenant toutes vos données personnelles :
     - Profil utilisateur
     - Annonces de parking
     - Réservations
     - Messages et conversations
     - Historique des transactions

3. **Délai de traitement :** 30 jours maximum

**Note :** Cette demande peut être faite indépendamment d'une demande de suppression de compte.

---

## 🔄 Récupération de Compte après Suppression

**Important :** Une fois votre compte supprimé, **il ne peut pas être récupéré**.

- Toutes vos données personnelles seront supprimées définitivement
- Vous devrez créer un nouveau compte si vous souhaitez utiliser à nouveau l'application Parkey
- L'historique de vos transactions passées sera perdu (bien que certaines données anonymisées soient conservées pour obligations légales)

Si vous avez des doutes, nous vous recommandons de :
- **Désactiver temporairement votre compte** au lieu de le supprimer définitivement (fonctionnalité à venir)
- **Nous contacter** à support@parkey.eu pour discuter de vos préoccupations

---

## 📧 Contact et Support

Pour toute question concernant la suppression de compte ou pour exercer vos droits RGPD :

**Email :** support@parkey.eu  
**Délai de réponse :** 30 jours maximum

### Autres droits RGPD :

Vous disposez également des droits suivants (voir notre [Politique de Confidentialité](https://github.com/hb-devstudio/parkey-privacy/blob/main/PRIVACY.md)) :

- **Droit d'accès** (Art. 15 RGPD) : Obtenir une copie de vos données
- **Droit de rectification** (Art. 16 RGPD) : Corriger vos données
- **Droit à la limitation du traitement** (Art. 18 RGPD) : Limiter l'utilisation de vos données
- **Droit d'opposition** (Art. 21 RGPD) : Vous opposer au traitement de vos données
- **Droit de retirer le consentement** : Retirer votre consentement pour certaines utilisations

---

## 📄 Informations Complémentaires

- **[Politique de Confidentialité Complète](https://github.com/hb-devstudio/parkey-privacy/blob/main/PRIVACY.md)**
- **[Contact Support](mailto:support@parkey.eu)**

---

**Dernière mise à jour :** 15 novembre 2025  
**Version :** 1.0

