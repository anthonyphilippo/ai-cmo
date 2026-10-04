# Design — AI CMO

Les jetons dans `tokens.css` font foi.

**En une phrase :** hero noir, corps papier froid, rouge belge, titres Syne extra-gras, texte Source Sans 3. Rythme et densité de sprint.pation.io, pas les couleurs ni Inter.

## 1. Couleurs

| Nom | Hex | Jeton | Rôle |
|---|---|---|---|
| Encre | `#080a0f` | `--ink` | Hero, sections sombres, texte. |
| Papier | `#f4f5f7` | `--paper` | Fond clair. Froid, pas crème. |
| Accent | `#c8102e` | `--accent` | Tampon : bouton, filet du hero, formule recommandée. |
| Secondaire | `#2c3640` | `--muted` | Légendes. Contraste ≥ 4,5:1 sur le papier. |

**Règle de l'accent :** deux ou trois fois par écran. Jamais en dégradé, jamais en texte arc-en-ciel.

## 2. Typographie

### Syne (titres, boutons, prix)
- Graisses : 700, 800. Le H1 met `sans vous` en `--accent-on-ink`.
- Licence : SIL OFL · hébergée dans `fonts/`
- Jamais Inter.

### Source Sans 3 (texte)
- Graisses : 400, 600 (boutons)
- Licence : SIL OFL · hébergée dans `fonts/`

## 3. Espacements et formes
- Coins : 14px sur modules et boutons (rythme de la référence). Filets : 1px.
- Largeur de lecture : 65ch.
- Ombres : aucune, sauf le tampon intérieur de la formule Résident.

## 4. Composants
- **Bouton** : fond accent, texte blanc, « Réservez le diagnostic ». Survol : `--accent-hover`.
- **Étiquette** : une seule, dans le hero.
- **Carte** : pas de grille de cartes identiques.

## 5. Règles absolues
1. Une action, un libellé.
2. `sans vous` en rouge clair, sur sa propre ligne.
3. Le rouge ne décore pas : il tamponne.

## 6. Jamais
- Inter, Playfair, DM Sans, crème, dégradé indigo, cartes icône, eyebrows répétées, visage généré.

## 7. Références
- Structure : sprint.pation.io (rôles, pas les mots ni les couleurs).
- Palette : anthonyphilippo.com.
