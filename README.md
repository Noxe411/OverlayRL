# OverlayRL

Overlay de session pour Rocket League : victoires, défaites, série en cours, rank actuel, rank suivant, MMR et MMR restant. Seuls les matchs classés sont comptés. Fonctionne avec Epic Games et Steam.

**Version actuelle : 1.4**

## Télécharger

Télécharge [`OverlayRL.zip`](OverlayRL.zip) (Windows 64 bits), décompresse-le, puis suis le guide [`LISEZ-MOI.txt`](LISEZ-MOI.txt) : installation, paramètres, skins, logos de rank, MMR, dépannage.

## En bref

- Démarre avec Windows, apparaît quand Rocket League se lance, disparaît à sa fermeture.
- Le jeu doit être en mode « Fenêtré sans bordure ».
- N'injecte rien dans le jeu et ne lit pas sa mémoire : il écoute la Stats API officielle de Psyonix et lit le journal texte du jeu.
- La session repart de zéro quand on change de mode classé (2v2 -> 3v3...), désactivable.
- Raccourcis clavier utilisables pendant la partie : `Ctrl+Alt+V` ajoute une victoire, `Ctrl+Alt+D` une défaite, `Ctrl+Alt+R` remet le score à zéro. Combinaisons modifiables dans les paramètres.
- Le programme n'est pas signé : Windows peut afficher un avertissement au premier lancement (voir le guide).

## Logos de rank

Les logos officiels des ranks appartiennent à Psyonix et ne sont pas distribués ici : OverlayRL dessine ses propres écussons. Pour utiliser les vrais, dépose tes images dans le dossier qu'ouvre le bouton « Dossier des logos de rank » des paramètres (détails dans le guide).

## Nouveautés de la 1.4

Remise à zéro de la session au changement de mode classé, et les trois raccourcis clavier ci-dessus.
