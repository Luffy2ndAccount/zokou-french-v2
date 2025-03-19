<p align="center"><h1>Zokou-2.0 🚀</h1><br> </p>

![banner](Zokou.jpg)

Zokou est un bot multi-devices conçu pour enrichir vos conversations WhatsApp avec des fonctionnalités utiles et amusantes. Qu'il s'agisse de gérer des fichiers, d'interagir avec des stickers ou de faciliter la gestion de groupe, Zokou est là pour vous aider ! 🎉💬

## Fonctionnalités Principales ✨

- **Téléchargement de Fichiers :** Zokou peut télécharger des fichiers audio et vidéo à partir de liens que vous lui envoyez, pour que vous puissiez les partager facilement avec vos contacts. 🎶📹

- **Exportation de Stickers :** Vous pouvez exporter des stickers de Telegram et les utiliser dans vos conversations WhatsApp en les envoyant simplement à Zokou. 😄✨

- **Gestion de Groupe :** Zokou offre des fonctionnalités de gestion de groupe, comme l'ajout ou la suppression de membres, la configuration de règles et d'autres paramètres. 👥📋

- **Text to Image :** Les meilleurs logos ont été sélectionnés pour votre confort. 🖼️🎨

## Fonctionnalités Ludiques 🎉

- **Blagues et Devinettes :** Zokou est équipé d'une collection de blagues et de devinettes pour égayer vos conversations. 😂🤔

- **Citations Inspirantes :** Recevez des citations inspirantes pour vous motiver au quotidien. 💪🌟

## Obtenir Zokou 🛠️

1. Cliquez sur **[Fork](https://github.com/Luffy2ndAccount/zokou-french-v2/fork)** afin de copier le repo sur votre compte GitHub. N'oubliez pas d'ajouter une étoile 🌟 pour encourager les développeurs !

2. Obtenez une session du bot :  
   - [Session-1](https://zkscan.onrender.com)  
   - [Session-2](https://zokouscan-din3.onrender.com)

## Déploiement 🚀

- **Déploiement sur Heroku** :
  1. Si vous ne disposez pas de compte **Heroku**, cliquez [**ici**](https://id.heroku.com/login) pour en créer un.
  2. Cliquez [**ici**](https://dashboard.heroku.com/new?template=https://github.com/Luffy2ndAccount/zokou-french-v2) pour déployer le bot sur **Heroku**.

- **Déploiement sur Koyeb** :
  1. Si vous n'avez pas de compte **Koyeb**, cliquez [**ici**](https://dashboard.koyeb.com/signup) pour en créer un.
  2. Cliquez sur le bouton ci-dessous pour déployer sur Koyeb :<br>
     [![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?name=zokouvf&type=docker&image=docker.io%2Fluffy077%2Fzokouvf%3Alatest&env%5BPREFIXE%5D=.&env%5BLECTURE_AUTO_STATUS%5D=oui&env%5BTELECHARGER_AUTO_STATUS%5D=oui&env%5BNOM_BOT%5D=Zokou-MD&env%5BLIENS_MENU%5D=https%3A%2F%2Fwallpapercave.com%2Fuwp%2Fuwp3943464.jpeg&env%5BPM_PERMIT%5D=non&env%5BMODE_PUBLIC%5D=oui&env%5BETAT%5D=1&env%5BSESSION_ID%5D=mettez+votre+session&env%5BNOM_OWNER%5D=Djalega%2B%2B&env%5BNUMERO_OWNER%5D=22891733300&env%5BWARN_COUNT%5D=3&env%5BSTARTING_BOT_MESSAGE%5D=oui&env%5BANTI_VUE_UNIQUE%5D=oui&env%5BPM_CHATBOT%5D=non&env%5BHEROKU%5D=non&env%5BDATABASE_URL%5D=mettez+une+database&env%5BANTI_COMMAND_SPAM%5D=non&ports=8000%3Bhttp%3B%2F)

- **Déploiement sur Render** :
  1. Si vous n'avez pas de compte **Render**, cliquez [**ici**](https://dashboard.render.com) pour vous inscrire.
  2. Créez un nouveau sweb service.  
  3. Choisissez **Public Git Repository**.  
  4. Dans le champ , entrez `https://gitlab.com/bankai421341/senbonzakura.git`.
  5. Cliquez sur **Connect**.  
  6. Sélectionnez le **Free Plan** si vous ne voulez pas payer.  
  7. Dans la section **environemment variable**, cliquez sur **Add from .env** et copiez le contenu suivant :

```env
PREFIXE=.
LECTURE_AUTO_STATUS=non
TELECHARGER_AUTO_STATUS=non
NOM_BOT=alte
LIENS_MENU=LUFFY
PM_PERMIT=non
MODE_PUBLIC=oui
ETAT=1
SESSION_ID='Zokou-MD-WHATSAPP-BOT;;;=>eyJub2lzZUtleSI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoid0pNeGRUMzdNdU5TVVp6WTRwclg4ZnptNkpuN0FWRXJiLzRnOFphN3IyYz0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiUXJvbU40VWpMMWdyc3daS0hselFqc084ZUxuUW1ZUDNaUFozaVI2Wm5Wbz0ifX0sInBhaXJpbmdFcGhlbWVyYWxLZXlQYWlyIjp7InByaXZhdGUiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJRTnNINHZMZGZ5K2twK3JITW9pU1ZwOWpabyt4TFJYTDB4NEpTRURQN1ZvPSJ9LCJwdWJsaWMiOnsidHlwZSI6IkJ1ZmZlciIsImRhdGEiOiJHSXM3TjZYZ3JpUi9icU5LMWlTOHhEbEh6eFV3N3Awalc0V1JPZU9EcG1zPSJ9fSwic2lnbmVkSWRlbnRpdHlLZXkiOnsicHJpdmF0ZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6ImVMRHdKMFVaeWdnbUNvaVlRREVIaU9IbytQR3c3c0ZEMk9kTHl5UXBBSG89In0sInB1YmxpYyI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6Im1JWFFEWmRkaFpsbkFlS3h2YUh6eEhkTFJTNkVKL2JyNFdubS9hSm5vRk09In19LCJzaWduZWRQcmVLZXkiOnsia2V5UGFpciI6eyJwcml2YXRlIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiZ09ZQWQ4VjNrK2t4eVNpbXRqdTdGT3BvYmZnWmVoc1VnSjdGWWs3cnRVOD0ifSwicHVibGljIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiSGZINFBCUU9IUUpqNE50MXFVL1MvY05Wd1VhNkYrdi9za3FFT3VDQmZYYz0ifX0sInNpZ25hdHVyZSI6eyJ0eXBlIjoiQnVmZmVyIiwiZGF0YSI6IkZjMWdqaGVLYmF0a2xJcWpBUnhMR3pnNE1XU2hOV3luTHYyWjZ6UTlNaFZSNG14OHlWYmFZYWN0bUtUT0g0RldqczdlWWJjMS9BY2ZGb0VkMThxVGhnPT0ifSwia2V5SWQiOjF9LCJyZWdpc3RyYXRpb25JZCI6MTY3LCJhZHZTZWNyZXRLZXkiOiIveTIydXFjUGY0QlI1UEc1TU1uR2xHOFJvVDJ1REM4RDh2ZE55clNYUElRPSIsInByb2Nlc3NlZEhpc3RvcnlNZXNzYWdlcyI6W10sIm5leHRQcmVLZXlJZCI6MzEsImZpcnN0VW51cGxvYWRlZFByZUtleUlkIjozMSwiYWNjb3VudFN5bmNDb3VudGVyIjowLCJhY2NvdW50U2V0dGluZ3MiOnsidW5hcmNoaXZlQ2hhdHMiOmZhbHNlfSwicmVnaXN0ZXJlZCI6dHJ1ZSwicGFpcmluZ0NvZGUiOiIyOTQxSDJTVCIsImxhc3RQcm9wSGFzaCI6IjJQMVloZiIsInJvdXRpbmdJbmZvIjp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQ0FJSUNBPT0ifSwibWUiOnsiaWQiOiI1MDk0NDc2NDg3NToxNEBzLndoYXRzYXBwLm5ldCIsImxpZCI6IjI0NzMyMTk1MDQzMzQ5NzoxNEBsaWQifSwiYWNjb3VudCI6eyJkZXRhaWxzIjoiQ0lDV3lOSUdFUDYxNjc0R0dBRWdBQ2dBIiwiYWNjb3VudFNpZ25hdHVyZUtleSI6IkNJMHpsMWdKcEZ5eGhHanFxZmZoMlJJK01xKzRFeVNiTjdrODdEZVJSeE09IiwiYWNjb3VudFNpZ25hdHVyZSI6IlJuWHlyQ2EwR2dlSWVxcjBzV1crOUowSDIzMzlTNzdIWjZNVUNrRlhDai9vMkZ6bWNONGV2YWwySlVoQ0cyTWxnUTF3QjcwVitLQWsxVzB2L3l2TkFBPT0iLCJkZXZpY2VTaWduYXR1cmUiOiJaekdFSWFXUVRldXJvL2Q5RXhBWk5NY0FqUCs1cDZRRHNBaEczUzFXYVJCQWNxVjR5T0Y3eW9ucjVteFQ3azFzcUhvdDZucHJscXhjOER6M3YxNkNqUT09In0sInNpZ25hbElkZW50aXRpZXMiOlt7ImlkZW50aWZpZXIiOnsibmFtZSI6IjUwOTQ0NzY0ODc1OjE0QHMud2hhdHNhcHAubmV0IiwiZGV2aWNlSWQiOjB9LCJpZGVudGlmaWVyS2V5Ijp7InR5cGUiOiJCdWZmZXIiLCJkYXRhIjoiQlFpTk01ZFlDYVJjc1lSbzZxbjM0ZGtTUGpLdnVCTWttemU1UE93M2tVY1QifX1dLCJwbGF0Zm9ybSI6ImFuZHJvaWQiLCJsYXN0QWNjb3VudFN5bmNUaW1lc3RhbXAiOjE3NDIzOTYxNjEsIm15QXBwU3RhdGVLZXlJZCI6IkFBQUFBS1l1In0='
NOM_OWNER=alte
NUMERO_OWNER=50944764875
WARN_COUNT=3
STARTING_BOT_MESSAGE=non
ANTI_VUE_UNIQUE=oui
PM_CHATBOT=non
HEROKU=non
ANTI_COMMAND_SPAM=non
ANTI_DELETE_MESSAGE=oui
AUTO_REACT_MESSAGE=non
```

  8. Cliquez sur **Add env** pour enregistrer, puis modifiez selon vos besoins. N'oubliez pas d'entrer votre session ID.  
  9. Cliquez sur **Deploy service** et profitez-en !


 - **Déploiement GitHub**

  1. **Forkez le dépôt**.
  2. Modifiez le fichier `exemple_de_set.env` en `set.env` et ajoutez-y votre **session_ID**.
  3. Créez un nouveau fichier `.github/workflows/deploy.yml` et mettez-y ce contenu :

```yml
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main
  schedule:
    - cron: '0 */4 * * *'

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install ffmpeg
      run: |
        sudo apt-get update
        sudo apt-get install -y ffmpeg

    - name: Install dependencies
      run: |
        npm install -g pm2
        npm install

    - name: Start application with timeout
      run: |
        timeout 14520s npm run zokou

```


## Contributions 🤝

Les contributions à Zokou sont les bienvenues ! Si vous avez des idées pour de nouvelles fonctionnalités, des améliorations ou des corrections de bogues, n'hésitez pas à ouvrir une issue ou à soumettre une demande de pull. 🙌

### Remerciements :
- **Fatao**, qui a ajouté des commandes (Fancy, GPT, Dall-e, APK)  
- **CrazyPrice**, qui a hébergé un second site web pour les session_id  

## Licence 📜

Le Bot WhatsApp Zokou est publié sous la [Licence MIT](https://opensource.org/licenses/MIT).

Profitez des fonctionnalités variées du Bot WhatsApp Zokou pour améliorer vos conversations et rendre votre expérience WhatsApp plus intéressante ! 🎊💬

## Développeurs :
- [**Djalega++**](https://github.com/djalega8000/Zokou-MD/)
- [**᚛M๏𝓷keℽ D Lบffy᚜**](https://github.com/Faouz995)
