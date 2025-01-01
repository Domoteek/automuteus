<p align="center">
    <a href="https://automute.us/#/" alt = "Lien du site web"><img src="assets/AutoMuteUsBanner_cropped.png" width="800"></a>
</p>
<p align="center">
    <a href="https://github.com/automuteus/automuteus/actions?query=build" alt="Statut de la construction">
        <img src="https://github.com/automuteus/automuteus/workflows/build/badge.svg" />
    </a>
    <a href="https://github.com/automuteus/automuteus/releases/latest">
    <img alt="Version GitHub" src="https://img.shields.io/github/v/release/automuteus/automuteus" >
    </a>
    <a href="https://github.com/automuteus/automuteus/graphs/contributors" alt="Contributeurs">
        <img src="https://img.shields.io/github/contributors/automuteus/automuteus" />
    </a>
    <a href="https://discord.gg/ZkqZSWF" alt="Lien Discord">
        <img src="https://img.shields.io/discord/754465589958803548?logo=discord" />
    </a>
</p>
<p align="center">
    <a href="https://hub.docker.com/repository/docker/automuteus/automuteus" alt="Téléchargements">
        <img src="https://img.shields.io/docker/pulls/denverquane/amongusdiscord.svg" />
    </a>
    <a href="https://automuteus.crowdin.com/automuteus" alt="localisation">
        <img alt="Localisation" src="https://badges.crowdin.net/e/5eb1365b5fd16082e63cc54c33736adc/localized.svg">
    </a>
    <a href="https://goreportcard.com/report/github.com/automuteus/automuteus/v8" alt="Rapport">
        <img src="https://goreportcard.com/badge/github.com/automuteus/automuteus/v8" />
    </a>
</p>

<p align="center">
    <a href="https://add.automute.us" alt="invitation">
        <img alt="Lien d'invitation" src="https://img.shields.io/static/v1?label=bot&message=invite%20me&color=purple">
    </a>
</p>

# AutoMuteUs

<div style="display: flex; align-item: center; justify: center;">
<p style="">
    <a href="https://add.automute.us"/>
        <img src="assets/DiscordBot_Black.gif", width=150>
    </a>
</p>
<div style="margin-left: 2%">
AutoMuteUs est un bot Discord qui exploite les données du jeu Among Us pour couper/rétablir automatiquement le son des joueurs pendant les parties !

Nécessite [amonguscapture](https://github.com/automuteus/amonguscapture) pour capturer et relayer les données du jeu.

Vous avez des questions, des préoccupations, des rapports de bugs ou vous souhaitez simplement discuter ? Rejoignez notre serveur Discord à l'adresse https://discord.gg/ZkqZSWF !

Cliquez sur le badge "invite me" dans l'en-tête pour inviter le bot sur votre serveur, ou cliquez sur le GIF à gauche.

Toutes les illustrations du bot ont été généreusement fournies par <a href=https://aspen-cyborg.tumblr.com/>Smiles</a> !

</div>
</div>

# ⚠️ Prérequis ⚠️

1. Vous **devez** exécuter l'[application de capture](https://github.com/automuteus/amonguscapture/releases/latest) sur votre PC Windows pour que le bot fonctionne ! Toutes les parties d'Among Us sans utilisateur exécutant le logiciel de capture **n'auront pas de capacités de coupure automatique du son** !
2. L'[application de capture](https://github.com/automuteus/amonguscapture/releases) ne supporte actuellement que les versions Steam, Epic Games, itch.io et Microsoft Store du jeu, mais **ne supporte pas** les versions bêta ou crackées.

# Démarrage rapide et démo (cliquez sur l'image) :

[![Démarrage rapide](http://i3.ytimg.com/vi/VYx6kM1O4FM/hqdefault.jpg)](https://youtu.be/VYx6kM1O4FM)

# Utilisation et commandes

Pour démarrer une partie avec le bot dans le canal actuel, tapez la commande suivante dans Discord après avoir invité le bot :

```
/new
# Démarre une partie et permet aux utilisateurs de réagir avec des emojis pour lier leur joueur en jeu
```

Le bot vous enverra une réponse privée avec un lien utilisé pour synchroniser le logiciel de capture à votre partie. Il contiendra également un lien pour télécharger la dernière version du logiciel de capture, si vous ne l'avez pas déjà.

Si vous souhaitez voir l'utilisation des commandes ou les options disponibles, tapez `/help` dans votre canal Discord.

## Commandes

| Commande     | Description                                                                                                            | Exemple                  |
|-------------|------------------------------------------------------------------------------------------------------------------------|--------------------------|
| `/help`     | Affiche les informations d'aide et l'utilisation des commandes                                                         |                          |
| `/new`      | Démarre une nouvelle partie dans le canal texte actuel                                                                 |                          |
| `/refresh`  | Recrée entièrement le message de statut du bot, au cas où il se retrouverait trop loin dans le chat.                   |                          |
| `/pause`    | Met le bot en pause, et ne lui permet pas de couper le son de qui que ce soit jusqu'à ce qu'il soit relâché.            |                          |
| `/end`      | Termine la partie entièrement et arrête le suivi des joueurs. Rétablit le son de tous et réinitialise l'état            |                          |
| `/link`     | Lie manuellement un utilisateur Discord à sa couleur en jeu                                                            | `/link @Soup cyan`       |
| `/unlink`   | Délie manuellement un joueur                                                                                           | `/unlink @Soup`          |
| `/settings` | Affiche et modifie les paramètres du bot, tels que le préfixe des commandes ou le comportement de coupure du son        |                          |
| `/privacy`  | Affiche les informations sur la confidentialité et la collecte de données du bot                                       |                          |
| `/info`     | Affiche des informations générales sur le bot                                                                          |                          |
| `/map`      | Affiche une image d'une carte en jeu dans le canal texte. Fournissez le nom de la carte et si vous voulez la version détaillée | `/map skeld true`        |
| `/stats`    | Affiche des statistiques détaillées sur les parties d'Among Us jouées sur le serveur actuel, ou par un joueur spécifique | `/stats user view @Soup` |
| `/premium`  | Affiche des informations sur AutoMuteUs Premium, et le statut premium actuel de votre serveur                          |                          |

# Confidentialité

Vous pouvez consulter les détails sur la confidentialité et la collecte de données pour le bot officiel [ici](PRIVACY.md).

# Localisation

AutoMuteUs utilise désormais [CrowdIn](https://crowdin.com/) pour la localisation et les traductions (merci @MatadorProBr) !

Aidez-nous à traduire le bot ici :

[![Crowdin](https://badges.crowdin.net/e/5eb1365b5fd16082e63cc54c33736adc/localized.svg)](https://automuteus.crowdin.com/automuteus)

Pour préparer de nouvelles chaînes à la traduction, installez d'abord goi18n v2.1.1 en utilisant la commande suivante :
```
go install -v github.com/nicksnyder/go-i18n/v2/goi18n@v2.1.1
```

Puis exécutez la commande suivante chaque fois que de nouvelles chaînes ou traductions sont ajoutées :

```
goi18n extract -outdir locales
```

# Auto-hébergement

L'auto-hébergement nécessite une connaissance solide et une capacité de dépannage pour Docker/Docker-compose, unRAID, Heroku et/ou toute autre configuration de réseau et de routage spécifique à votre solution d'hébergement.

Par conséquent, **nous recommandons à la majorité des utilisateurs de profiter de notre bot vérifié**. Le lien pour inviter notre bot se trouve ici :

<a href="https://add.automute.us" alt="invitation">
        <img alt="Lien d'invitation" src="https://img.shields.io/static/v1?label=bot&message=invite%20me&color=purple">
    </a>

Si vous êtes certain que vous préférez auto-héberger le bot, veuillez suivre les instructions sur [automuteus/deploy](https://github.com/automuteus/deploy).

# Développement

Veuillez vous référer aux instructions sur [automuteus/deploy](https://github.com/automuteus/deploy).

# Projets similaires

- [Imposter](https://github.com/molenzwiebel/Impostor): Un bot similaire qui utilise des canaux Discord privés au lieu de couper/rétablir le son. Utilise également un joueur factice rejoignant la partie et "spectant" pour obtenir des informations sur le jeu ; aucune capture nécessaire (mais perd la 10ème place de joueur).

- [AmongUsBot](https://github.com/alpharaoh/AmongUsBot): Sans leur programme Python original avec beaucoup de fonctionnalités OCR/Discord, je n'aurais jamais pensé à cette idée ! **N'est plus maintenu actuellement**

- [amongcord](https://github.com/pedrofracassi/amongcord): Un excellent programme pour suivre le statut des joueurs et couper/rétablir automatiquement le son dans Among Us. Leur projet fonctionne comme un bot Discord traditionnel ; installation très facile !

- [Silence Among Us](https://github.com/tanndev/silence-among-us#silence-among-us): Un autre bot très similaire à celui-ci, qui utilise également AmongUsCapture. Maintenant en accès anticipé avec une instance hébergée publiquement !
