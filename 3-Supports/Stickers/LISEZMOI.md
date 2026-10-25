# Stickers Slabs

Octobre 2026. Cinq formes : carré, carré arrondi, rond, rectangle et rectangle arrondi. Chacune existe en deux versions : sombre (fond Anthracite, logo Calcaire) et clair (fond Calcaire, logo Anthracite). Le curseur reste orange dans les deux.

Le carré et le rond portent le monogramme. Le rectangle porte la signature : le logotype suivi de la phrase « Security you can build on. ».

## Deux jeux de formats

- Vistaprint/ : aux formats proposés par Vistaprint, 12 × 12 cm pour le carré et le rond, 15 × 7,5 cm pour le rectangle. C'est le jeu à commander.
- Formats charte/ : aux formats de la charte, page 42 : carré 50 mm, rond 60 mm, rectangle 80 × 35 mm. Pour un autre imprimeur ou une petite série.

| Forme | Vistaprint | Formats charte | Coins arrondis |
|---|---|---|---|
| carre | 120 × 120 mm | 50 × 50 mm | |
| carre-arrondi | 120 × 120 mm | 50 × 50 mm | rayon 10 mm / 4 mm |
| rond | 120 mm de diamètre | 60 mm de diamètre | |
| rectangle | 150 × 75 mm | 80 × 35 mm | |
| rectangle-arrondi | 150 × 75 mm | 80 × 35 mm | rayon 6 mm / 3 mm |

Le rayon des coins arrondis vaut 8 % du petit côté. Vistaprint applique son propre rayon quand on choisit l'option coins arrondis : le fichier arrondi sert alors d'aperçu, et l'un ou l'autre fichier convient.

## Proportions

Celles de la charte, page 42, à toutes les tailles :
- carré : le monogramme fait 134/240 du côté, comme dans l'avatar ;
- rond : le monogramme fait 50/138 du diamètre ;
- rectangle : la signature (fichier slabs-logotype-signature) fait les trois quarts de la largeur, pour que la phrase reste lisible.

Le logo est centré sur la forme. Dans la version sombre, la phrase est en Béton, comme dans la signature inversée. Les marges respectent la zone de protection de la charte (page 8) : au moins X autour du logo, X étant l'épaisseur du trait du S.

## Les fichiers

Dans chaque jeu, chaque sticker porte un nom de la forme slabs-sticker-[forme]-[format]-[sombre|clair].

- PDF (impression)/ : le fichier à envoyer à l'imprimeur. PDF vectoriel 100 % CMJN (FOGRA39), fond perdu de 2 mm compris, ligne de coupe en ton direct CutContour.
- SVG/ : le maître modifiable, en sRGB, avec deux calques : Artwork (fond perdu compris) et CutContour.
- PNG/ : à 600 dpi. [nom]-fond-perdu.png avec le fond perdu ; [nom]-forme.png découpé à la forme, transparent autour, pour les services qui tracent eux-mêmes la coupe et pour les maquettes.
- planche-stickers.png : les dix stickers du jeu sur une page.

## Commander chez Vistaprint

- Choisir la forme et le format, puis importer le PDF du dossier Vistaprint/PDF (impression). Le PNG -fond-perdu convient aussi : Vistaprint recommande le PDF ou le PNG et déconseille le JPEG ; les PNG sont à 600 dpi.
- Le studio affiche ses propres repères de fond perdu et de sécurité. Les fichiers ont 2 mm de fond perdu de chaque côté et le logo reste loin de la coupe : si le studio demande moins de fond perdu, ajuster l'image au format sans la déformer, le logo n'est pas touché.
- La ligne de coupe CutContour est ignorée pour les formes standard : Vistaprint découpe à la forme choisie.
- Matière : plastique blanc, ou Soft Touch pour un rendu mat, plus proche du vinyle mat de la charte. Pas de plastique transparent ni holographique : le fond Calcaire ou Anthracite doit rester opaque.

## Préparation pour un autre imprimeur

- Fond perdu : 2 mm de chaque côté. Le format du PDF est donc le format de coupe plus 4 mm.
- Zone de sécurité : 3 mm à l'intérieur de la coupe. Le logo en reste toujours à distance.
- Ligne de coupe : tracé de 0,25 pt en ton direct CutContour (100 % magenta en simulation), sans fond, en surimpression. La masquer ou la supprimer si l'imprimeur trace la coupe lui-même.
- Couleurs : Anthracite C70 M60 Y55 K75, Calcaire C5 M5 Y10 K0, Orange signal C0 M70 Y100 K0, Béton C30 M25 Y30 K10 (la phrase sur fond sombre). Pas de transparence.

## Autres formats

Garder les proportions : agrandir ou réduire le SVG d'un bloc et l'exporter à nouveau, ou demander à l'imprimeur une mise à l'échelle homothétique, fond perdu compris. Le S doit rester d'au moins 6 mm de haut, et 12 mm avec la phrase : il ne descend pas sous ces limites avant 11 mm de côté pour le carré, 17 mm de diamètre pour le rond et 57 mm de large pour le rectangle.
