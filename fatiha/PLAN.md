# Al-Fatiha — vidéo verticale (1080×1920)

Récitation seule, sans musique. Texte arabe + français + anglais.
Texte : `texte.json` (sources indiquées dedans). À relire avant tout rendu.

## Principes (adaptés du skill animateur-motion)
- Le son est la récitation : chaque verset apparaît **quand le récitateur le commence**
  et reste entier à l'écran **jusqu'à la fin de sa lecture**. Les secondes viendront
  d'un seul fichier `temps.json` (début/fin de chaque verset), mesuré sur l'audio.
- Mouvements lents et doux, aucun flash, aucune coupe sèche, aucune image d'être vivant.
- Fil conducteur : une fine ligne de lumière dorée qui se trace sous chaque verset,
  et un motif géométrique (étoile à 8 branches) en filigrane qui tourne très lentement.
- Ouverture : dès l'image 0, le titre « سورة الفاتحة » est visible (jamais d'écran noir).

## Mise en page (vertical)
| Zone | Contenu | Police | Taille |
|---|---|---|---|
| Haut (y≈260) | Nom de la sourate + n° du verset | Amiri | 44 px |
| Centre (y≈700–1050) | Verset en arabe, 1 à 3 lignes | Amiri Quran | 84–96 px |
| Sous l'arabe | Ligne dorée | — | — |
| Bas (y≈1250) | Traduction française | Cormorant / Inter | 46 px |
| Bas (y≈1450) | Traduction anglaise | Inter, plus clair | 40 px |

Couleurs : fond bleu nuit `#0B1D2E` → vert profond `#0E2A24` (dégradé lent), or `#D8B56A`,
texte crème `#F4EEDF`, anglais `#B9C2C9`.

## Le plan (les secondes seront remplacées par celles de la récitation)
| # | Moment | Ce qu'on voit | Ce qui bouge |
|---|---|---|---|
| 0 | 0 → début v.1 | Titre « سورة الفاتحة », Al-Fatiha · The Opening | Motif qui s'éclaire, titre qui monte doucement |
| 1 | v.1 | بِسْمِ ٱللَّهِ… + FR + EN | Arabe apparaît par fondu de droite à gauche, ligne dorée se trace, puis FR, puis EN |
| 2–6 | v.2 à v.6 | Un verset par écran | Le verset précédent s'efface vers le haut pendant que le suivant arrive ; le n° du verset change dans un petit médaillon |
| 7 | v.7 (long) | Arabe sur 3 lignes, traductions sur 2–3 lignes | Même entrée ; tailles réduites si besoin pour que tout tienne |
| Fin | après v.7 | « صَدَقَ ٱللَّهُ ٱلْعَظِيمُ » ? *(seulement si vous le voulez)* sinon le titre revient | Motif qui s'éteint lentement |

## Ce qui manque
- Le **fichier audio** de la récitation + nom du récitateur + droit de l'utiliser.
- Votre accord sur ce plan (et sur la carte de fin).
