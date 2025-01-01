# Confidentialité
AutoMuteUs prend votre confidentialité au sérieux. Nous ne distribuerons *jamais* vos données à d'autres parties, et les données utilisateur ne sont explicitement pas à vendre ou à redistribuer.

L'utilisation d'AutoMuteUs dans votre serveur Discord (ou en tant qu'utilisateur général) relève de "l'intérêt légitime" dans [l'article 6(1)(f) du Règlement général sur la protection des données](https://eur-lex.europa.eu/legal-content/FR/TXT/?qid=1528874672298&uri=CELEX:02016R0679-20160504) (RGPD).

1. Nous utilisons la collecte de données pour afficher et agréger des statistiques sur les parties qu'un utilisateur Discord a jouées dans Among Us. (`/privacy showme`)
2. Nous n'utilisons que la quantité minimale de données/PII nécessaire pour générer et traiter ces statistiques.
3. Les utilisateurs peuvent se désinscrire de la collecte de données à tout moment s'ils ne souhaitent pas qu'AutoMuteUs recueille ces données. (`/privacy optout`)

# Quelles données AutoMuteUs collecte-t-il ?
AutoMuteUs collecte une très petite quantité d'informations utilisateur pour les statistiques. Votre UserID Discord, et tous les noms en jeu que vous avez utilisés sont les seules informations personnellement identifiables (PII) que le bot nécessite pour recueillir des statistiques. Toutes les autres données collectées par AutoMuteUs sont des données de jeu non identifiables, telles que la couleur du joueur, le rôle d'équipier/imposteur, etc. Un exemple d'enregistrement de données de jeu enregistré par AutoMuteUs est présenté ci-dessous :
```
{
    "color": 11,
    "name": "Soup",
    "isAlive": true
}
```

AutoMuteUs utilise une correspondance entre les UserIDs Discord et des IDs numériques arbitraires, qui sont utilisés pour corréler les événements de jeu. Si vous choisissez de supprimer les données qu'AutoMuteUs stocke à votre sujet (avec `/privacy optout`), la correspondance avec votre User ID est supprimée, et l'historique complet de vos parties précédentes est effacé. Pour cette raison, se réinscrire à la collecte de données avec AutoMuteUs (`/privacy optin`) signifie que vos parties et événements de jeu passés **ne sont pas récupérables**. Veuillez bien considérer ceci avant de vous désinscrire, si vous prévoyez de consulter vos statistiques de jeu à un moment donné dans le futur !

Les questions et préoccupations concernant votre collecte de données et votre confidentialité peuvent être adressées à gdpr@automute.us
