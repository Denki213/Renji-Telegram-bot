<img src="https://i.ibb.co/6ZswV6d/21a7c6d3-8316-48c2-86d4-579c05ae5a41.webp" alt="banner">
<h1 align="center"><img src="![received_1106676897823577](https://github.com/user-attachments/assets/c25d3249-5962-4126-92b4-347e874b7bf5)
" width="22px"> Telegram Bot V1</h1>

### Telegram Bot V1
dossier pour les Bots télégram version 1 créer par <a href="https://www.facebook.com/profile.php?id=61557674704673" target="_blank">Renji Starfall</a>

### TUTORIEL

## Étape 1 : Créer et obtenez le token de votre bot Telegram
 **Créer un bot Telegram:**
   - ouvrez Telegram et créer un bot grâce à deux bots Telegram
     - **Bot 1:** `many chat`
     - **Bot 2:** `BotFather`
   - Tutoriels de la création d'un bot telegram:
     - <a href="https://www.facebook.com/share/v/15ca2B7At6/" target="_blank">Vidéo de la création d'un bot telegram</a> ☺️

## Étape 2 : Configuration des fichiers
**remplissez les fichiers**
- Ouvrez le fichier `account.dev.txt` et remplacer `VOTRE_API_TOKEN` par votre token.
- Ouvrez le fichier `config.dev.json` et remplacer `VOTRE_ID_TELEGRAM` par votre `ID` Telegram.

## Étape 3 :Obtenez votre ID Telegram 🆔

- Ouvrez Telegram et vous obtenez votre ID grâce à <a href="https://t.me/chat_id_echo_bot" target="_blank">ID CHAT BOT</a>

### Déployer
déployer votre bot sur ```render.com``` le déploiement est simple et facile vous n'aurai rien à modifier déployer le bot comme celle d'un goatbot Facebook 😎

### moniteur 
- créer votre moniteur sur `betterstack.com` ou `uptimerobot.com`
### ℹ️info 
# Comment installer les commandes
- installer votre commande dans le fichier `commands`
   - modifié la commande `help`
   - ajouter
 ```javascript
{ command: '/COMMAND_NAME', description: 'DESCRIPTION' },
  ```
 - changez `COMMAND_NAME` par le nom de la commande et `DESCRIPTION` par la description de la commande.
   - modifié la commande `index.js`
   - ajouter
 ```javascript
require('./commands/COMMAND_NAME')(bot);
  ```
 - changez `COMMAND_NAME` par le nom de la commande
