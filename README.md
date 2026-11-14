# OverlayRL

Overlay de session pour Rocket League : victoires, défaites, série en cours, rank actuel, rank suivant, MMR et MMR restant. Seuls les matchs classés sont comptés. Fonctionne avec Epic Games et Steam.

**Version actuelle : 1.4**

## Télécharger

Télécharge [`OverlayRL.exe`](OverlayRL.exe) (Windows 64 bits), puis suis le guide [`LISEZ-MOI.txt`](LISEZ-MOI.txt) : installation, paramètres, skins, logos de rank, MMR, dépannage.

## En bref

- Démarre avec Windows, apparaît quand Rocket League se lance, disparaît à sa fermeture.
- Le jeu doit être en mode « Fenêtré sans bordure ».
- N'injecte rien dans le jeu et ne lit pas sa mémoire : il écoute la Stats API officielle de Psyonix et lit le journal texte du jeu.
- La session repart de zéro quand on change de mode classé (2v2 -> 3v3...), désactivable.
- Raccourcis clavier utilisables pendant la partie : `Ctrl+Alt+F9` ajoute une victoire, `Ctrl+Alt+F10` une défaite, `Ctrl+Alt+F11` remet le score à zéro. Combinaisons modifiables dans les paramètres.
- Le programme n'est pas signé : Windows peut afficher un avertissement au premier lancement (voir le guide).

## Nouveautés de la 1.4

Remise à zéro de la session au changement de mode classé, et les trois raccourcis clavier ci-dessus.
