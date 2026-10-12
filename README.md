# FLUX

Platformer néon nerveux, dans l'esprit de Celeste et Katana Zero : wall run, dash, hyper, corner, blocs qui basculent.
Un seul fichier HTML, sans installation.

**Jouer :** https://axel-dossantos.github.io/flux/

## Contenu

- 3 chapitres (Élan, Friable, Bascule), 22 salles de tailles variées
- Hub où l'on se déplace, entraînement salle par salle avec fantôme du record
- Médailles bronze, argent, or, dev et tête de mort (chapitre sans mourir)
- Jauge de flow et musique adaptative, 11 succès
- Multi jusqu'à 4 joueurs par code de salon
- Manette, remapping des touches, options d'accessibilité

## Contrôles

| Action | Clavier | Manette |
|---|---|---|
| Se déplacer | ZQSD / flèches | Stick ou croix |
| Sauter | Espace | A |
| Dash | Maj | X, B, RB ou RT |
| Recommencer la salle | R | Y |
| Pause | Échap | Start |

Les touches se changent dans *Options › Touches*.

## Multi

1. Un joueur va dans **Multi › Créer un salon** et reçoit un code de 4 lettres.
2. Les autres vont dans **Multi › Rejoindre un salon** et tapent ce code.
3. Dans le salon, entrer dans une porte *Course* lance la course pour tout le monde.

La connexion est directe entre joueurs (WebRTC, via PeerJS). Le salon est fermé si celui qui l'a créé quitte.
