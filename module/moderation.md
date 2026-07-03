# Modération

Gardez un serveur Discord sain avec les commandes de modération.

## Commandes

### `/ban membre: raison?`
Bannir un membre.
- Option *raison* facultative.
- Le membre reçoit un MP (si autorisé) avec le motif.

### `/unban identifiant: raison?`
Débannir un utilisateur par **ID** ou **tag** si disponible.

### `/kick membre: raison?`
Expulser un membre du serveur.

### `/mute membre: durée? raison?`
Rendre muet un membre pour une durée.
- Durées supportées : `10s`, `5m`, `2h`, `3d`…
- Sans durée, applique la valeur par défaut configurée.

### `/unmute membre: raison?`
Rendre la voix à un membre précédemment muet.

## Conseils
- Créez un salon privé *#logs-moderation* pour y envoyer les journaux d’actions.
- Vérifiez la hiérarchie des rôles : le rôle du bot doit être **au-dessus** des rôles des membres ciblés.
