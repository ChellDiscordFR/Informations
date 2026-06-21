# ⚖️ Documentation Légale Globale — ChellOS
**Conditions Générales d'Utilisation, Protocole de Confidentialité, RGPD & Mentions Légales**

> [!NOTE]
> **Dernière mise à jour :** 21 juin 2026 (Version 2026.04 révisée)
> **Statut :** En vigueur
> **Application :** Site Web (`https://chell.fr`) et Application Discord **Chell** (ID : `1383154920231796736`)
> **Contact légal & DPO :** `contact@chell.fr`

---

## 📋 1. Mentions Légales & Identité du Projet

### Édition du Service
L'application **Chell** ainsi que son site internet vitrine et son tableau de bord sont édités et gérés par l'équipe du **Projet Chell**. Il s'agit d'une initiative communautaire indépendante, bénévole et à but non lucratif. Le projet n'est pas constitué sous forme d'entité juridique enregistrée ; il est propulsé de manière collective par ses fondateurs et ses contributeurs.

* **Co-fondateurs & Responsables de publication :**
  * Joynix (`@joynix28` — ID : `1365989943012229221`)
  * Prime Directive (`@maximedalla` — ID : `537225794372632576`)

### Hébergement et Infrastructure
L'ensemble de l'infrastructure est hébergé sur des **Serveurs Privés Virtuels (VPS) autogérés situés en France**. 
* **Bases de données :** MySQL (InnoDB) avec JSON de secours.
* **Sécurité :** La maintenance technique est supervisée directement par l'équipe interne. L'accès aux serveurs est strictement réservé aux propriétaires du projet.

---

## 🚀 2. Conditions Générales d'Utilisation (CGU)

### Acceptation et Nature du Service
L'installation de Chell sur un serveur Discord, son utilisation en tant qu'application utilisateur (User App), ou la navigation sur son site officiel vaut **acceptation pleine, entière et sans réserve** des présentes conditions et du protocole de confidentialité. 

Le service propose des outils de modération, d'automatisation, des fonctions IA locales et des modules communautaires. Il est fourni **"tel quel" (as-is)** et à titre **intégralement gratuit**, sans garantie de disponibilité continue ou d'absence de bugs. L'équipe se réserve le droit exclusif de modifier, suspendre ou retirer des fonctionnalités sans préavis (pour des raisons de sécurité, de maintenance ou de conformité). Vous êtes libres de retirer le bot de vos serveurs ou Applications si vous n'acceptez pas nos conditions.

### Responsabilité de l'Administrateur
En ajoutant ChellOS sur un espace communautaire, l'utilisateur certifie détenir les permissions nécessaires (*Administrateur* ou *Gérer le serveur*) et l'autorisation d'ajouter le bot. Il s'engage à veiller au respect des présentes CGU au sein de sa communauté et répond des actions de ses membres.

### Propriété Intellectuelle
Le code, le nom "Chell", le logo, les visuels, les fonctionnalités, typographies et les éléments de marque associés sont protégés. Sauf autorisation expresse, nul n'est autorisé à usurper l'identité visuelle de Chell, à reproduire, revendre, republier ou se revendiquer membre de l'équipe officielle.

---

## 🚫 3. Règles de Conduite, Abus & Sanctions

L'utilisation de Chell implique le respect strict des droits d'autrui, conformément aux **[Conditions d'Utilisation de Discord](https://discord.com/terms)** et à la **[Charte de la Communauté Discord](https://discord.com/guidelines)**. Sont formellement interdits notamment (sans toutefois s'y limiter) :

1. **Atteinte aux personnes :** Utiliser le bot pour harceler, menacer, discriminer ou perturber un serveur.
2. **Abus de permissions :** Détourner les droits du bot pour altérer des salons, nuire à une communauté, ou diffuser du contenu illégal ou des secrets/tokens (le contenu NSFW est strictement réservé aux salons configurés comme tels).
3. **Extraction de données :** Le *scraping* massif, automatisé ou non autorisé des données du site ou du bot.
4. **Surcharge :** La tentative de détourner, casser ou surcharger le service et ses API.

> [!WARNING]
> **Interventions & Blacklist :**
> En cas d'abus grave ou répété, les mainteneurs peuvent suspendre ou bloquer définitivement l'accès au bot (Blacklist) pour un utilisateur ou un serveur. Les données d'infraction (ID utilisateur, raison, date) sont conservées jusqu'à 24 mois.
> 
> *Note de sécurité : Les fondateurs du projet, Prime Directive (`537225794372632576`) et Joynix (`1365989943012229221`), sont inscrits sur une liste blanche (WL sécurité) et sont exemptés des sanctions automatiques.*

---

## 🔒 4. Protocole de Confidentialité (Conformité RGPD)

ChellOS opère dans une logique de minimisation absolue des données. **Aucune donnée n'est vendue, partagée à des tiers ou utilisée à des fins de profilage commercial.**

### Bases Légales du Traitement
Nous traitons vos données sur les bases suivantes : l'**exécution du service** (commandes), l'**intérêt légitime** (sécurité, modération), le **consentement** (modules activés par les administrateurs) et les **obligations légales**.

### 🧠 Intelligence Artificielle (Chell AI) & Automodération
* **Modèle 100% Local :** Chell AI est un modèle expérimental hébergé localement en France. **Aucun transfert de vos messages n'est effectué vers des fournisseurs tiers**.
* **Historique IA :** Limité à 20 messages maximum par serveur pour le contexte. Conservé 30 jours max. Supprimable via `/clear-history`conformément à la RGPD.

### 🛠️ Fonctionnalités Communautaires & Tableau de bord
ChellOS ne lit et ne stocke **aucun contenu textuel persistant**, sauf pour les modules sollicités :
* **Authentification Dashboard (`chell.fr`) :** Collecte de l'ID Discord, du pseudo et de l'URL de l'avatar via OAuth2. Un **unique cookie de session** fonctionnel est utilisé (aucun traceur publicitaire ni analytics).
* **Données traitées selon les modules :** XP/Niveaux, Notes/Rappels, Tickets, Suggestions, Sondages, Giveaways, Compteurs (dernier utilisateur, record), et relais Interserveur.

### 🔌 Services Externes Optionnels
Chell AI est 100% local, mais certaines commandes spécifiques s'appuient sur des API tierces (soumises à leurs propres politiques) uniquement sur demande : *ImgBB / GitHub* (images), *Short.io* (liens courts), *OpenWeatherMap* (météo), *Google Speech* (transcription vocale), et *Twitch GQL* (noms Twitch). *Firebase* n'est utilisé que pour des statistiques globales agrégées.

---

## ⏱️ 5. Durées de Conservation des Données

| Catégorie de données | Durée de conservation | Particularités |
| :--- | :--- | :--- |
| **Avertissements, Notes & Sanctions** | 12 mois maximum | Suppression automatique à expiration. |
| **Données Communautaires (XP, Tickets, Suggestions)** | 12 mois maximum | Conservées par serveur. |
| **Historique IA (Chell AI)** | 30 jours maximum | Supprimable manuellement (`/clear-history`). |
| **Système de Giveaways** | 7 jours après la fin | Permet le relancement (*reroll*) des gagnants. |
| **Strikes Automod** | Variable | Auto-reset configurable par le serveur. |
| **Configuration du Serveur** | Jusqu'au retrait | Effacement lors de l'expulsion du bot. |
| **Snipe (Messages supprimés)** | Volatile | Mémoire RAM, perdu définitivement au redémarrage. |

---

## 🛡️ 6. Vos Droits RGPD & Politique Développeur Discord

### Politique Développeur Discord
ChellOS respecte scrupuleusement les règles de l'API Discord : aucune modification de compte sans permission, pas de DM non sollicités, aucune collecte de mots de passe/tokens, aucun *scraping* du contenu global Discord.

### Exercice de vos droits
Conformément au RGPD, vous disposez des droits suivants :
* **Droit d'accès & Portabilité :** Obtenir une copie ou un export de vos données.
* **Droit de rectification :** Corriger des données inexactes.
* **Droit à l'effacement :** Faire supprimer vos données (sauf obligation légale/sécurité).
* **Droit à la limitation & Opposition :** Suspendre certains traitements. *Note : En rejoignant un serveur où Chell est présent, vous acceptez le traitement inhérent au bot. Pour vous y opposer totalement, il est nécessaire de quitter le serveur.*
* **Autorité de contrôle :** Vous avez le droit d'introduire une réclamation auprès de l'autorité compétente (ex: CNIL en France).

En cas de violation de données engendrant un risque élevé, nous nous engageons à informer les personnes concernées et les autorités compétentes.

---

## ⚠️ 7. Limitation de Responsabilité

Dans la limite permise par la loi, le projet Chell ne pourra être tenu responsable des dommages directs ou indirects liés à l'utilisation ou à l'indisponibilité du service, notamment :
* Les pertes de configuration, logs, historiques ou contenus temporaires.
* Les sanctions prises par des administrateurs de serveurs tiers utilisant le bot.
* Les comportements produits par des modules IA expérimentaux ou des services tiers.

---

## ✉️ 8. Contact & Support

Pour exercer vos droits (suppression, export), signaler un abus, ou pour toute assistance technique, nous nous engageons à vous répondre sous **30 jours maximum** :
* **Serveur Support Discord :** [discord.gg/HxR89qcXrG](https://discord.gg/HxR89qcXrG) 
* **Contact E-mail (DPO) :** `contact@chell.fr`
