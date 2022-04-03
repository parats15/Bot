# PlaceFR Bot
Fork de PlaceDE Bot.
Le bot pour PlaceFR ! Ce bot récupère automatiquement [plans](https://github.com/parats15/pixel) toutes les quelques minutes pour empêcher les bots d'entrer en collision les uns avec les autres.

## Instructions d'installation

Vérifiez que de nouveaux pixels peuvent être placés et que ce n'est pas sur le temps de recharge

1. Installez l'extension de navigateur [Tampermonkey](https://www.tampermonkey.net/) ou [Violentmonkey (Firefox)](https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/) .
2. Cliquez sur ce lien : [https://github.com/parats15/Bot/raw/main/placedebot.user.js](https://github.com/PlaceDE/Bot/raw/main/placedebot.user .js). Si tout se passe bien, Tampermonkey vous proposera d'installer un script utilisateur. Cliquez sur **Installer**.
3. Rechargez l'onglet **r/place**. Si tout s'est bien passé, vous devriez voir "Demander un jeton d'accès..." en haut à droite de l'écran. Le bot est maintenant actif et utilisera ces notifications en haut à droite pour des informations en cours.

## Faiblesses des bots

- Le bot ne met pas à jour le message de temps de recharge, il semble donc qu'il reste encore un pixel à placer. Cependant, le bot a déjà placé le pixel et attend maintenant le temps de recharge.
- Le bot ne tient pas compte d'un temps de recharge existant et suppose donc que vous pouvez placer un pixel immédiatement lorsque vous ouvrez **r/place**. Dans le pire des cas, 5 minutes sont perdues 
