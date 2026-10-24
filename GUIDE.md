# Solid Geeks — Guide d'usage du logo

## 1. Le logo
**Idée :** une barre de muscu dont les disques sont des crochets `[ ]`. Le code qui soulève de la fonte : *solide* et *geek* en un coup d'œil.

**Versions :**
- **Horizontale** (principale) : `sg-horizontal-*.svg`
- **Empilée** : `sg-stacked-*.svg`
- **Symbole seul** : `sg-symbol-*.svg`
- **Nom seul** : `sg-wordmark-ink.svg`
- **Petite taille** (16–24 px) : `sg-symbol-small.svg` et `sg-favicon-tile.svg`, dessinés au pixel.

Le symbole est construit sur une grille de 4 unités, symétrique sur les deux axes. Disques : 36 × 176. Bras des crochets : 24 × 28. Barre : 16. Colliers : 12 × 48.

## 2. Zone de protection
Autour du logo, garde un espace libre égal à **la largeur d'un disque** (un montant vertical du crochet). La zone grandit avec le logo.

## 3. Tailles minimales
| Version | Écran | Impression |
|---|---|---|
| Horizontale | 120 px de large | 30 mm |
| Symbole (master) | 32 px | 8 mm |
| Symbole (petite taille) | 16 px | 5 mm |

## 4. Couleurs
| Nom | HEX | RGB | CMJN (approx.) | Usage |
|---|---|---|---|---|
| **Volt** | `#C8FF2E` | 200 255 46 | 22 0 82 0 | Le symbole sur fond sombre. La signature. |
| **Encre** | `#0D0F0C` | 13 15 12 | 75 60 70 90 (noir riche) | Fonds, texte, logo sur fond clair. |
| Blanc | `#FFFFFF` | 255 255 255 | 0 0 0 0 | Nom sur fond sombre. |

Le Volt n'a pas d'équivalent Pantone exact. Pour l'impression (stickers, t-shirts), il faut valider sur nuancier un vert fluo de type 802 C.

**Associations autorisées :**
- Symbole Volt et nom blanc sur Encre (avatars, README sombre, t-shirt).
- Logo tout Encre sur fond blanc ou clair.
- Logo tout blanc sur photo sombre.
- Logo tout Encre sur fond Volt.

**Interdit :** le Volt sur fond blanc. Le contraste est d'environ 1,1:1, donc illisible.

## 5. Typographie
- **Nom :** DejaVu Sans Mono Bold, vectorisée, avec l'espace entre les mots réduit à 60 %. Ne pas retaper le nom au clavier : toujours utiliser les fichiers.
- **Site et docs :** titres en DejaVu Sans Mono ou JetBrains Mono, texte en Inter.
- **Licences :** DejaVu (licence Bitstream Vera), JetBrains Mono et Inter (SIL OFL). Toutes sont libres, y compris pour un logo.

## 6. Avatars et web
- **GitHub (organisation) et Discord (serveur) :** `png/sg-avatar-1024.png`. Il est prévu pour résister au recadrage rond.
- **Aperçu social GitHub** (Settings → Social preview) : `png/sg-social-preview-1280x640.png`.
- **Site :** copie le contenu de `web/` à la racine du site et colle `web/head-snippet.html` dans le `<head>`.
- **README GitHub** (bascule automatique clair/sombre) :

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="sg-readme-dark.svg">
  <img alt="Solid Geeks" src="sg-readme-light.svg" width="480">
</picture>
```

## 7. À ne pas faire
- Ne pas étirer, écraser ni pivoter le logo.
- Ne pas recolorer hors palette.
- Ne pas ajouter d'ombre, de contour, de dégradé ni d'effet néon.
- Ne pas séparer, déplacer ni redimensionner les éléments d'une déclinaison.
- Ne pas poser le logo sur un fond chargé sans aplat.
- Ne pas utiliser le symbole master en dessous de 32 px : prendre la version petite taille.

## 8. Notes
- Aucune recherche d'antériorité n'a été faite. Avant de déposer la marque, il faut une recherche sur les bases INPI, EUIPO et WIPO, plus une recherche d'image inversée.
- `board.html` est la planche de présentation, avec des mockups README, terminal, sticker, t-shirt, profil social et onglet.
