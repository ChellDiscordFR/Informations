# 📋 Gestion de la Sécurité & Système de Blacklist — Chell

> [!IMPORTANT]
> Le système de Blacklist globale de Chell est un outil de protection collective conçu pour sécuriser les serveurs Discord contre les utilisateurs malveillants récurrents ou dangereux.

---

## 🛡️ 1. Fonctionnement Automatique

Par défaut, tout serveur intégrant l'application Chell bénéficie d'une couche de sécurité contre les profils à risque :
* **Détection Instantanée :** Dès qu'un utilisateur rejoint un serveur ou y envoie un message, Chell interroge instantanément sa base de données centrale.
* **Sanction Immédiate :** Si le profil est répertorié dans la liste noire globale (Blacklist), le bot procède à son **expulsion immédiate** afin de préserver l'intégrité de la communauté.

### Configuration des Alertes (Logs)
Les équipes de modération locales peuvent configurer un salon dédié au suivi de ces détections. Deux modes opératoires sont alors possibles :
1. **Protection Activée (Recommandé) :** L'utilisateur indésirable est exclu automatiquement, et un rapport détaillé est transmis dans le salon de logs.
2. **Surveillance Seule (Désactivation de l'expulsion) :** En exécutant la commande `/blacklist-admin protection OFF`, l'expulsion automatique est débrayée. Le bot se contentera d'alerter les modérateurs du serveur par un message d'avertissement contenant les informations de l'utilisateur détecté.

---

## 🔍 2. Outils de Vérification et de Signalement

### Vérification Manuelle
À tout moment, vous pouvez auditer le statut d'un compte d'un simple clic ou via une commande :
* **Commande :** `/infos membre`
* **Disponibilité :** Opérationnelle sur tous les serveurs disposant du bot, mais également utilisable directement au sein de vos **messages privés** si vous avez installé l'application Chell sur votre compte personnel.

### Procédure de Signalement (Report)
Si vous constatez des agissements graves ou malveillants enfreignant nos règles de sécurité, vous pouvez soumettre un dossier à notre équipe de sécurité :
1. Utilisez la commande **/signaler-utilisateur** (accessible sur serveur ou en message privé).
2. Fournissez les détails requis. Un ticket d'instruction sera généré, et notre équipe interne pourra, si nécessaire, vous recontacter directement afin d'approfondir les vérifications.
3. Si le signalement aboutit à une sanction effective, vous recevrez une confirmation automatique par message privé.

> [!CAUTION]
> **Authentification des Modérateurs Officiels :** Si un utilisateur prétend faire partie de l'équipe de sécurité ou de modération globale de Chell, exigez qu'il exécute la commande `!staff-preuve` ou `/infos membre` devant vous. Sa fiche de profil officielle affichera distinctement son badge ou son statut au sein du projet.

---

## ⚖️ 3. Règlement Général de la Blacklist

### Conditions Fondamentales d'Éligibilité
L'inscription d'un identifiant Discord dans la Blacklist globale de Chell exige la réunion de conditions strictes pour éviter tout abus :
* L'infraction doit correspondre précisément à l'un des motifs officiels listés ci-dessous.
* **Administration des Preuves :** * *Signalement Externe :* Nécessite impérativement un élément matériel indiscutable (capture d'écran non tronquée, enregistrement audio, élément vidéo probant, ID ou liens contextuels).
  * *Constat Interne :* Observation flagrante et documentée par un membre vérifié de l'équipe du projet Chell.

### Cycle de Vie et Confidentialité des Éléments de Preuve
* **Accès Restreint :** Les pièces justificatives liées à un dossier de sanction sont confidentielles et exclusivement consultables par l'équipe de sécurité de Chell ainsi que par l'utilisateur incriminé (sur demande).
* **Rétention des données :** L'intégrité des preuves est contractuellement garantie pendant une durée de **14 jours** après l'application de la sanction. Passé ce délai légal, les éléments peuvent être archivés ou supprimés.
* **Droit à l'oubli :** Tout utilisateur dont la sanction a été levée ou annulée peut formuler une demande explicite visant à détruire définitivement l'intégralité des preuves liées à son ancien dossier.

---

## 🗂️ 4. Nomenclature des Motifs de Sanction

| Icône | Motif de Blacklist | Définition & Seuil d'Application |
| :---: | :--- | :--- |
| 🧨 | **Raid** | Attaque coordonnée ou destructive visant à vandaliser un serveur (destruction de salons, création massive de rôles, bannissements en masse). |
| 🪓 | **Menace de Raid** | Propos explicites ou préparatifs documentés visant à organiser ou inciter au sabotage d'un espace communautaire. |
| 🕵️‍♂️ | **Cyber-malveillance (Hack)** | Vol de compte, utilisation de scripts malveillants (token grabbing), diffusion de chevaux de Troie, de rançongiciels ou de phishing. |
| 📣 | **Publicité Abusive (Pub)** | Démarchage publicitaire sauvage en masse, par message privé ou sur les salons, non sollicité. *(Note : Une mention dans le statut ou la bio n'est pas un motif de sanction)*. |
| 💾 | **Doxxing (Dox)** | Divulgation malveillante d'informations privées ou d'éléments d'identité réels (adresse, identité, téléphone) sans consentement. |
| 🗃️ | **Menace de Dox** | Chantage, intimidation à base d'informations personnelles ou détention illégitime de bases de données privées. |
| 🥫 | **Spam Intensif** | Inondation massive de salons textuels par des flux répétitifs rendant toute lecture ou modération impossible. |
| 🎭 | **Harcèlement** | Comportements ou propos répétés et ciblés visant à rabaisser, intimider, traquer ou nuire à l'intégrité morale d'un individu. |
| ⚠️ | **Menace de Harcèlement** | Intimidation ou planification d'actions collectives visant à mener des campagnes de dénigrement. |
| 💀 | **Menaces Graves & Auto-destruction** | Menaces de mort explicites, incitation directe ou encouragement aux pratiques suicidaires et à l'automutilation. |
| 💸 | **Escroquerie (Scam)** | Manœuvres frauduleuses, arnaques financières, faux concours ou revente illégale de services visant à spolier les utilisateurs. |
| 🔞 | **Contenus NSFW Illégitimes** | Partage non consenti de contenus pornographiques, violents ou gores en dehors des espaces légalement prévus et balisés à cet effet. |
| 🎃 | **Perturbation Organisée (Troll)** | Actions délibérées et répétées destinées à déstabiliser le fonctionnement d'une communauté en contournant sciemment les directives. |
| 🤬 | **Invectives Répétées (Trash Talk)** | Comportement injurieux, agressif et toxique persistant malgré les avertissements préalables des équipes de modération. |
| ❌ | **Démarchage Prédateur / Sexuel** | Sollicitations insistantes, déplacées ou forcées à caractère sexuel, notamment auprès de publics mineurs. |
| 💣 | **Contenus Extrémistes & Haineux** | Apologie du terrorisme, diffusion d'idéologies haineuses, de thèses suprémacistes, ou incitation à la haine raciale et religieuse. |

---

## 🔄 5. Procédure de Recours (Unblacklist)

Pour contester une inscription sur la liste noire, une procédure unique et réglementée doit être suivie :
* **Canal Unique :** Toute demande d'examen doit s'effectuer en ouvrant un ticket d'appel sur le **[Serveur Support Officiel de Chell](https://discord.gg/wTJZsGPdZt)** ou, en cas d'impossibilité majeure, en contactant par message privé un membre de la **Haute Administration** du bot -> @`joynix28`.
* **Strictement Personnel :** L'appel doit être initié **directement et exclusivement** par le titulaire du compte concerné par la sanction. 
* **Aucun Intermédiaire :** Les requêtes formulées par des tiers (amis, proches, administrateurs de serveurs tiers) seront immédiatement rejetées. L'assistance par un tiers non membre de l'équipe Chell durant l'instruction de l'appel n'est pas autorisée.
