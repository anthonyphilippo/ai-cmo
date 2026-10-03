# Design — AI CMO

Les jetons dans `tokens.css` font foi.

**En une phrase :** fond noir ou papier froid, encre presque noire, un rouge tampon, Spectral pour les titres, Source Sans 3 pour le texte, coins carrés, un italique par page.

## 1. Couleurs

| Nom | Hex | Jeton | Rôle |
|---|---|---|---|
| Encre | `#080a0f` | `--ink` | Hero, sections sombres, texte. |
| Papier | `#f4f5f7` | `--paper` | Fond clair. Froid, pas crème. |
| Accent | `#c8102e` | `--accent` | Tampon : bouton, filet du hero, formule recommandée. |
| Secondaire | `#2c3640` | `--muted` | Légendes. Contraste ≥ 4,5:1 sur le papier. |

**Règle de l'accent :** deux ou trois fois par écran. Jamais en dégradé, jamais en texte arc-en-ciel.

## 2. Typographie

### Spectral (titres)
- Graisses : 700, italique 600 pour un seul mot du H1 (`sans vous`)
- Licence : SIL OFL · Google Fonts · hébergée dans `fonts/`
- Jamais en capitales de titre

### Source Sans 3 (texte)
- Graisses : 400, 600 (boutons)
- Licence : SIL OFL · hébergée dans `fonts/`

## 3. Espacements et formes
- Coins : 0. Filets : 1px. Tampon : 3px.
- Largeur de lecture : 65ch.
- Ombres : aucune, sauf le tampon intérieur de la formule Résident.

## 4. Composants
- **Bouton** : fond accent, texte blanc, « Réservez le diagnostic ». Survol : `--accent-hover`.
- **Étiquette** : une seule, dans le hero.
- **Carte** : pas de grille de cartes identiques.

## 5. Règles absolues
1. Une action, un libellé.
2. Un mot en italique dans le H1, pas plus.
3. Le rouge ne décore pas : il tamponne.

## 6. Jamais
- Inter, Playfair, DM Sans, crème, dégradé indigo, cartes icône, eyebrows répétées, visage généré.

## 7. Références
- Structure : sprint.pation.io (rôles, pas les mots ni les couleurs).
- Palette : anthonyphilippo.com.
