# Slabs brand

The visual identity of Slabs and of its open source projects: logotype, project marks, palette,
typefaces and templates.

S stands for Security, Standards, Solid, and Slabs: the slab, the thing you build on. The monogram is
a cut S followed by an orange terminal cursor. The `S_labs` logotype sets that monogram next to the
word *labs*. The tagline is **Security you can build on.**

The full guidelines, 50 pages in English, are not in this repository: ask brand@spomky-labs.com for
them. French notes on the kit itself are in [LISEZMOI.md](LISEZMOI.md).

## Project marks

Ready for a README, in light and dark. Each mark is served from this repository.

| Project | Mark |
|---|---|
| WebAuthn Framework | `4-Web/svg/marques-de-projet/marque-webauthn-framework-*.svg` |
| COSE | `4-Web/svg/marques-de-projet/marque-cose-*.svg` |
| JWT Framework | `4-Web/svg/marques-de-projet/marque-jwt-framework-*.svg` |
| OTPHP | `4-Web/svg/marques-de-projet/marque-otphp-*.svg` |
| CBOR PHP | `4-Web/svg/marques-de-projet/marque-cbor-php-*.svg` |
| PKI Framework | `4-Web/svg/marques-de-projet/marque-pki-framework-*.svg` |
| Access Control Framework | `4-Web/svg/marques-de-projet/marque-access-control-framework-*.svg` |
| PWA Bundle | `4-Web/svg/marques-de-projet/marque-pwa-bundle-*.svg` |
| Web Push Framework | `4-Web/svg/marques-de-projet/marque-web-push-framework-*.svg` |

Four variants each: `couleur` for light backgrounds, `inverse` for dark ones (it keeps the orange
cursor), `mono-anthracite` and `mono-calcaire` for single colour work.

To put one at the top of a README, pair the two variants so it follows the reader's theme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)"
          srcset="https://raw.githubusercontent.com/Spomky-Labs/brand/main/4-Web/svg/marques-de-projet/marque-cose-inverse.svg">
  <img alt="COSE" width="141" height="48"
       src="https://raw.githubusercontent.com/Spomky-Labs/brand/main/4-Web/svg/marques-de-projet/marque-cose-couleur.svg">
</picture>
```

Set `width` and `height` from the mark's own ratio so it does not stretch. At a height of 48 px:
WebAuthn Framework 418, COSE 141, JWT Framework 316, OTPHP 162, CBOR PHP 217, PKI Framework 296,
Access Control Framework 489, PWA Bundle 251, Web Push Framework 407.

## On a website

The SVG files under `4-Web/` are decorative by default: they carry no `title`, `role` or `aria-label`,
so the accessible name belongs on whatever uses them.

```html
<!-- Logo alone inside a link: the link carries the name -->
<a href="/" aria-label="Slabs, home"><svg aria-hidden="true">…</svg></a>
<!-- Logo as an image -->
<img src="/slabs-logotype-couleur.svg" alt="Slabs" width="72" height="32">
<!-- Logo next to a label that already says Slabs -->
<img src="/slabs-monogramme-couleur.svg" alt="">
```

The icon set and a sample manifest are in `4-Web/icones/`, the default sharing image in `4-Web/partage/`,
the colours, sizes and typefaces as CSS variables and W3C Design Tokens in `4-Web/tokens/`.

```html
<link rel="icon" href="/favicon.ico" sizes="any">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">
<link rel="apple-touch-icon" href="/apple-touch-icon.png">
<link rel="manifest" href="/site.webmanifest">
<meta property="og:image" content="https://[site]/og-slabs-1200x630.png">
```

## Colours

Brand colours, defined in CMYK (FOGRA39) then converted for the screen.

| Name | Hex | RGB | CMYK | Pantone C / U | Use |
|---|---|---|---|---|---|
| Anthracite | `#333334` | 51 51 52 | 70 60 55 75 | Black 7 C / Neutral Black U | logo, text, dark backgrounds |
| Béton | `#B3AEA6` | 179 174 166 | 30 25 30 10 | Warm Gray 4 C / Warm Gray 4 U | secondary text on dark, secondary areas |
| Calcaire | `#F5F1E8` | 245 241 232 | 5 5 10 0 | none: the paper, or process | light backgrounds, logo on dark |
| Orange signal | `#ED6A20` | 237 106 32 | 0 70 100 0 | 7578 C / 152 U | the cursor, the slab, the primary action |

Supporting colours, small areas only (under 10 % between the three), always with a word or a label:
Acier `#4A5D6E` for information, Patine `#3E7268` for success, Brique `#A6452C` for errors.

Utility colours, never in the logo and never as a printed area: Schiste `#5E5B56`, Calcaire clair
`#FBF9F4`, Calcaire ombré `#ECE7DD`, Plâtre `#DCD5C6`, Sable `#E8C9A8`.

Orange signal has no variant. Never orange text on a light background (2.8:1).

## Typefaces

Space Grotesk for text, IBM Plex Mono for code and the tagline, Yanone Kaffeesatz for the logotype.
All three are under the SIL Open Font License 1.1 and ship in `Fonts/`, each with its `OFL.txt`.

On the web IBM Plex Mono is served in Regular 400 and SemiBold 600 only. The tagline, which is
Medium 500, is drawn as an SVG instead.

Coverage: Latin, Vietnamese included. IBM Plex Mono also covers Cyrillic. For Greek or Cyrillic body
text use IBM Plex Sans, for Greek in code Noto Sans Mono, and for other scripts the matching Noto family.

## The rules that matter

- Clear space: at least X around the logo, X being the stroke width of the S.
- Minimum size: S height of 20 px or 6 mm, 40 px or 12 mm with the tagline, favicon below 32 px.
- On any surface the mark is the logo: a heading says what Slabs does and never writes its name.
- One slab per page at most, under the title.
- Colour never encodes a category: write it out.

## What is in here

```
1-Source files/          vector masters: SVG (sRGB), PDF and EPS in CMYK, project marks included
2-Images/                PNG with transparency (S/M/L/XL), JPG on background, avatars, favicons
3-Supports/              PowerPoint template and sample deck, GitHub and social templates, email
                         signature template, security advisory template, stickers ready to print
4-Web/                   the set to put online: SVG, icons, tokens, sharing images, no metadata
Fonts/                   Space Grotesk, IBM Plex Mono, Yanone Kaffeesatz (OFL 1.1)
email/                   the logo the HTML email signature loads
```

The guidelines document and the filled in stationery (a named email signature, the letterhead, the
finished business card) are kept out of this repository on purpose, so nothing here carries personal
contact details. No file here carries a provenance manifest either.

## Using these files

The typefaces are under the SIL Open Font License 1.1; each family folder carries the licence text,
which is what governs them.

The Slabs logotype, the monogram and the project marks identify Slabs and its projects. Use them to
refer to these projects, unmodified and with the clear space above. They are not a licence to brand
anything else.

## Questions

About the brand: brand@spomky-labs.com, or an issue on this repository. Anything else:
bonjour@spomky-labs.com. On social networks: @spomky-labs, the same everywhere.
