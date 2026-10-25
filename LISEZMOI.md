# Slabs, identité visuelle v2.0

Octobre 2026. Remplace la v1.0, l'identité Spomky Labs. La v2.0 introduit Slabs : le logotype S_labs, la palette béton et calcaire, et une charte de 50 pages dont les règles pour le web ont été éprouvées par l'intégration du site spomky-labs.com.

S comme Security, Standards, Solid, et Slabs : la dalle, ce sur quoi on construit. Le monogramme est un S taillé suivi d'un curseur de terminal orange. Le logotype « S_labs » associe ce monogramme au mot labs, en Yanone Kaffeesatz Bold à 78 % de la hauteur du S. La signature « Security you can build on. » est en IBM Plex Mono Medium.

La charte complète (50 pages, en anglais) n'est pas dans ce dépôt : la demander à brand@spomky-labs.com.

Questions sur la marque : brand@spomky-labs.com, ou une issue sur github.com/Spomky-Labs/brand. Contact général, sur la lettre et la carte : bonjour@spomky-labs.com. Pseudo sur les réseaux : @spomky-labs, partout le même.

## Contenu du dossier

La charte (Charte Graphique.pdf), sa version texte (Charte Graphique.md) et l'index pour les agents (llms.txt) sont absents de ce dépôt : ils portent l'adresse, le téléphone et le SIRET, et restent dans le kit privé.

1-Source files/
- SVG/ : fichiers vectoriels maîtres pour l'écran (sRGB), texte vectorisé. Sous-dossier Marques de projet : les neuf marques de projet (WebAuthn Framework, COSE, JWT Framework, OTPHP, CBOR PHP, PKI Framework, Access Control Framework, PWA Bundle, Web Push Framework) en couleur, inversé, mono anthracite, mono calcaire, noir et blanc.
- PDF (CMJN)/ : PDF vectoriels 100 % CMJN (FOGRA39) pour l'imprimeur, marques de projet comprises (couleur, inversé, noir).
- EPS (CMJN)/ : les mêmes en EPS.

2-Images/
- PNG (Transparency)/ : toutes les déclinaisons à fond transparent, en S 400, M 800, L 1600 et XL 3200 px de large, marques de projet comprises.
- JPG/ : logotype, signature et monogramme sur leur fond, avec la zone de protection.
- Avatar/ : 400, 500 et 1000 px. slabs-avatar sert pour l'organisation GitHub Spomky-Labs, Packagist et les réseaux ; slabs-avatar-web-auth et slabs-avatar-web-token pour les organisations GitHub web-auth et web-token (le monogramme et le nom de l'organisation) ; slabs-avatar-<projet> pour chacun des neuf projets, sur le même modèle avec la forme courte du nom (WebAuthn, COSE, JWT, OTPHP, CBOR PHP, PKI, ACF, PWA, Web Push). Les dépôts n'ont pas d'avatar propre : GitHub affiche celui de leur organisation.
- Favicon/ : favicon.svg, favicon.ico, PNG 16, 32, 48, apple-touch-icon 180 px, icônes 192 et 512 px.

3-Supports/
- Présentation/Slabs-Modele.potx : le modèle PowerPoint 16:9. L'ouvrir crée une nouvelle présentation ; Nouvelle diapositive propose 33 dispositions Slabs, en cinq familles :
  - ouverture et parties : titre, titre avec photo, agenda, partie, partie avec photo, partie sur fond sombre ;
  - contenu : contenu, deux colonnes, comparaison, photo à droite, photo à gauche, photo sur la moitié, code, titre seul, vierge ;
  - photos : plein écran, deux, trois et quatre photos ;
  - données : chiffres clés, chiffre avec photo, chiffre sur fond sombre, graphique, tableau, étapes en trois, quatre et cinq colonnes ;
  - moments : citation, affirmation, contenu, deux colonnes et titre seul sur fond sombre, clôture.
- Présentation/Slabs-Presentation.pptx : une présentation d'exemple de 33 diapositives, une par disposition, avec les photos de la bibliothèque Images libres et des notes.
- Lettre/ et Carte de visite/ : absents de ce dépôt. Le modèle de lettre A4 et la carte de visite portent l'adresse et le SIRET ; ils restent dans le kit privé.
- GitHub/ : aperçus sociaux 1280 × 640 px des dépôts et leur modèle.
- Réseaux sociaux/ : bannière 1500 × 500 px, modèles de posts 1200 × 675 px.
- Signature e-mail/ : le modèle (signature.html, signature.txt) et le logo PNG. La ligne légale et le nom y sont des champs à remplir ; la signature nominative reste dans le kit privé. Le logo est lu en ligne depuis ce dépôt, dossier email/, déjà en place.
- Avis de sécurité/modele-avis-securite.md : le modèle d'avis de sécurité GitHub de la page 49, avec la note de version et le message pour les réseaux.
- Stickers/ : cinq formes (carré et rond avec le monogramme, rectangle avec la signature, coins droits ou arrondis), en version sombre et claire, en deux jeux : Vistaprint (12 × 12 cm, 15 × 7,5 cm) et Formats charte (50 mm, 60 mm, 80 × 35 mm). PDF CMJN prêts à imprimer avec fond perdu et ligne de coupe CutContour, SVG modifiables et PNG 600 dpi. Détails dans Stickers/LISEZMOI.md.

4-Web/ : le jeu à mettre en ligne. Mêmes dessins que les maîtres, sans métadonnées.
- svg/ : logotypes, signatures, monogrammes et favicon, sans title, role ni aria-label (voir plus bas). Sous-dossier marques-de-projet : les marques de projet en couleur, inversé, mono anthracite et mono calcaire.
- icones/ : favicon.ico, favicon.svg, PNG 16, 32, 48, apple-touch-icon, icon-192, icon-512, et site.webmanifest d'exemple.
- tokens/ : slabs-tokens.css (variables CSS) et slabs-tokens.json (format W3C Design Tokens), les valeurs de la charte pour le code.
- partage/ : image de partage par défaut du site (og-slabs-1200x630.png, 1200 × 630 px, Open Graph) et son modèle modele-partage-defaut-1200x630.svg, avec la signature en dessin ; modele-partage-1200x630.svg pour les images des pages, avec l'emplacement de la date pour les contenus datés.

Fonts/ : Space Grotesk, IBM Plex Mono et Yanone Kaffeesatz, graisses statiques et variables, licence SIL Open Font License 1.1.

À côté du dossier v2.0, dans Design :
- Icones/ : la bibliothèque d'icônes Slabs, 59 icônes sur une grille de 24 px, trait de 2 px, accent orange derrière les traits ; SVG, sprite, PNG et catalogue.html.
- Images libres/ : la bibliothèque de photos libres de droits, avec leur registre de provenance.

## Fichiers maîtres et jeu Web

Les fichiers de ce dépôt ne portent aucun manifeste de provenance : ils ont été retirés avant publication. Les dessins sont identiques au pixel et les profils ICC sont conservés. Le kit privé garde ses manifestes.

Les SVG de 4-Web sont décoratifs par défaut. Le nom accessible se porte à l'usage :

```html
<!-- Logo seul dans un lien : le lien porte le nom -->
<a href="/" aria-label="Slabs, accueil"><svg aria-hidden="true">…</svg></a>
<!-- Logo en image -->
<img src="/slabs-logotype-couleur.svg" alt="Slabs" width="72" height="32">
<!-- Logo accompagné d'un intitulé qui dit déjà Slabs -->
<img src="/slabs-monogramme-couleur.svg" alt="">
```

En-tête d'un site :

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta property="og:image" content="https://[site]/og-slabs-1200x630.png">
```

## Installer les modèles Office

Copier Slabs-Modele.potx dans le dossier Documents\Modèles Office personnalisés. Il apparaît ensuite dans PowerPoint, sous Fichier > Nouveau > Personnel. Un double clic sur le fichier fonctionne aussi : il crée une nouvelle présentation sans toucher au modèle.

## Polices à installer

Installer les polices du dossier Fonts avant d'ouvrir les modèles PowerPoint et Word et les SVG modifiables. Sans elles, Office remplace Space Grotesk par Arial et IBM Plex Mono par Consolas.

Sur le web, IBM Plex Mono n'est servie qu'en deux graisses, Regular 400 et SemiBold 600 : la signature, en Medium 500, s'affiche par son fichier SVG, y compris sur l'image de partage par défaut. La graisse 500 ne sert plus à rien dans la chaîne du site.

Couverture : alphabets latins, vietnamien compris. IBM Plex Mono couvre aussi le cyrillique. Pour du grec ou du cyrillique en texte courant, utiliser IBM Plex Sans ; pour du grec dans du code, Noto Sans Mono ; pour les autres écritures, la famille Noto correspondante.

## Couleurs

Couleurs de marque, définies en CMJN (FOGRA39) puis converties pour l'écran :

| Nom | Hex | RVB | CMJN | Pantone C / U | Usage |
|---|---|---|---|---|---|
| Anthracite | #333334 | 51 51 52 | 70 60 55 75 | Black 7 C / Neutral Black U | logo, texte, fonds sombres |
| Béton | #B3AEA6 | 179 174 166 | 30 25 30 10 | Warm Gray 4 C / Warm Gray 4 U | texte secondaire sur fond sombre, aplats secondaires |
| Calcaire | #F5F1E8 | 245 241 232 | 5 5 10 0 | aucun : le papier, ou la quadri | fonds clairs, logo sur fond sombre |
| Orange signal | #ED6A20 | 237 106 32 | 0 70 100 0 | 7578 C / 152 U | le curseur, la dalle, la marque de l'action principale |

Les références Pantone sont les plus proches de chaque couleur, par calcul (écart CIEDE2000 de 1,4 à 4,2, sauf Neutral Black U à 7,4 : le noir ne descend pas aussi bas sur papier non couché). C pour le papier couché, U pour le non couché, comme la carte de visite. À valider sur un nuancier Pantone imprimé avant le premier travail en tons directs.

Couleurs complémentaires, petites surfaces seulement (moins de 10 % à elles trois), toujours avec un mot ou une étiquette :

| Nom | Hex | RVB | CMJN | Usage |
|---|---|---|---|---|
| Acier | #4A5D6E | 74 93 110 | 60 35 20 55 | information, notes, série de données |
| Patine | #3E7268 | 62 114 104 | 60 0 40 55 | succès, validation, série de données |
| Brique | #A6452C | 166 69 44 | 25 85 95 20 | erreurs, alertes, valeurs négatives |

Couleurs utilitaires, jamais dans le logo ni en aplat imprimé :

| Nom | Hex | CMJN | Usage |
|---|---|---|---|
| Schiste | #5E5B56 | 45 40 40 55, ou K 80 | texte secondaire, soulignement des liens, bordure des champs |
| Calcaire clair | #FBF9F4 | 0 0 5 0 | cartes, panneaux |
| Calcaire ombré | #ECE7DD | 10 10 15 0 | notes, étiquettes, code en ligne, états désactivés |
| Plâtre | #DCD5C6 | 10 10 20 10 | filets sur fond clair ; types et propriétés dans le code |
| Sable | #E8C9A8 | écran seulement | chaînes et nombres dans le code |

L'orange signal n'a pas de variante. Jamais de texte orange sur fond clair (2,8:1).

Dans le thème PowerPoint, les six couleurs d'accent suivent l'ordre des séries de graphiques de la charte : orange, Anthracite, Acier, Patine, Schiste, puis Brique pour les valeurs négatives. Un graphique inséré prend donc les bonnes couleurs sans réglage.

## Règles essentielles

- Zone de protection : au moins X autour du logo, X étant l'épaisseur du trait du S.
- Taille minimale : hauteur du S de 20 px ou 6 mm ; 40 px ou 12 mm avec la signature ; favicon en dessous de 32 px.
- Sur toute surface, la marque est le logo : un titre dit ce que fait Slabs et n'écrit jamais son nom.
- Une dalle au plus par page, sous le titre.
- La couleur ne code jamais une catégorie : on l'écrit.

## Reste à compléter

- Valider les références Pantone sur un nuancier imprimé, ou avec l'imprimeur.
- Fichiers d'impression, au moment d'une commande : carte de visite remplie, autocollants avec tracé de découpe, kakémono, affiche.
- Côté site : la mention EI sur la page Mentions légales et dans la ligne légale du pied de page.
