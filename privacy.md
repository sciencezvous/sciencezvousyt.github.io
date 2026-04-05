# Politique de Confidentialité — Recall

**Dernière mise à jour : avril 2026**

---

## 1. Éditeur de l'application

Recall est éditée par :

**[TON NOM COMPLET]**
[TON ADRESSE COMPLÈTE]
France
Email : [TON EMAIL]

---

## 2. Données collectées

### 2.1 Données traitées localement sur votre appareil

Les données suivantes sont stockées **uniquement sur votre appareil**, chiffrées avec AES-256 :

| Donnée | Finalité | Durée de conservation |
|---|---|---|
| Alias vocaux | Raccourcis vers vos contacts | Jusqu'à suppression manuelle |
| Mémoire contacts | Mémorisation de vos préférences d'envoi | Jusqu'à suppression manuelle |
| Historique des messages | Consultation de vos envois passés | 90 jours maximum |
| Messages reçus (Inbox) | Affichage dans l'interface | 7 jours maximum |

**Recall ne collecte, ne vend et ne partage aucune de ces données avec des tiers.**

### 2.2 Données transmises à des sous-traitants

Lorsque vous utilisez les modes **PRO** ou **DRAGUE**, le texte de votre message dicté est transmis à :

**OpenAI (via Cloudflare Workers)**
- Finalité : Reformulation intelligente du message
- Données transmises : Texte dicté uniquement (anonymisé, sans identifiant personnel)
- Politique d'OpenAI : [openai.com/privacy](https://openai.com/privacy)
- Politique de Cloudflare : [cloudflare.com/privacy](https://www.cloudflare.com/privacypolicy/)

**Le mode NORMAL ne transmet aucune donnée à des serveurs externes.**

### 2.3 Permissions Android utilisées

| Permission | Finalité |
|---|---|
| `RECORD_AUDIO` | Reconnaissance vocale pour dicter vos messages |
| `READ_CONTACTS` | Résolution du destinataire depuis vos contacts |
| `SEND_SMS` | Envoi de SMS directement depuis l'app |
| `BIND_NOTIFICATION_LISTENER_SERVICE` | Lecture des messages reçus dans l'Inbox unifiée |
| `BLUETOOTH_CONNECT` | Détection de la connexion à un autoradio (mode voiture) |
| `INTERNET` | Communication avec le serveur de reformulation IA |

---

## 3. Base légale du traitement (RGPD)

Conformément au Règlement Général sur la Protection des Données (RGPD) :

- **Consentement (Art. 6.1.a)** : Vous consentez expressément au traitement lors de l'acceptation de cette politique au premier lancement.
- **Exécution du service (Art. 6.1.b)** : Le traitement est nécessaire à la fourniture du service de messagerie vocale.
- **Intérêt légitime (Art. 6.1.f)** : Amélioration de l'expérience utilisateur via la mémoire des contacts.

---

## 4. Vos droits (RGPD Art. 15 à 22)

Conformément au RGPD, vous disposez des droits suivants :

- **Droit d'accès** : Consulter toutes vos données via l'écran "À propos" → "Mes données"
- **Droit à l'effacement** : Supprimer toutes vos données via "À propos" → "Supprimer mes données"
- **Droit à la portabilité** : Vos données sont stockées localement et vous appartiennent
- **Droit d'opposition** : Vous pouvez désactiver la transmission IA en utilisant uniquement le mode NORMAL
- **Droit de retrait du consentement** : À tout moment via les paramètres de l'app

Pour exercer vos droits : **[TON EMAIL]**

---

## 5. Sécurité des données

- Toutes les données locales sont chiffrées avec **AES-256 GCM**
- La clé de chiffrement est stockée dans le **Android Keystore** (matériel)
- La sauvegarde ADB est désactivée (`allowBackup=false`)
- Les communications avec nos serveurs sont chiffrées via **HTTPS/TLS 1.3**

---

## 6. Transfert hors UE

Vos messages dictés (modes PRO et DRAGUE uniquement) transitent par des serveurs d'OpenAI situés aux États-Unis. Ce transfert est encadré par les **Clauses Contractuelles Types (CCT)** de la Commission Européenne, conformément à l'Art. 46 du RGPD.

---

## 7. Mineurs

Recall est destinée aux personnes âgées de **13 ans et plus**. Nous ne collectons pas sciemment de données concernant des enfants de moins de 13 ans.

---

## 8. Modifications

Toute modification substantielle de cette politique vous sera notifiée via l'application. La date de dernière mise à jour figure en haut de ce document.

---

## 9. Contact & Réclamation

**[TON NOM COMPLET]**
Email : **[TON EMAIL]**

Vous pouvez également adresser une réclamation à la **CNIL** :
Site : [cnil.fr](https://www.cnil.fr)
Téléphone : 01 53 73 22 22
