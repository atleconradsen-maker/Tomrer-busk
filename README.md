# Nettside for Tømrer Busk AS

Enkel statisk nettside (ingen byggesteg). Åpne `index.html` i en nettleser for å se den.

## Filer
- `index.html` – alt innhold (forside, om oss, tjenester, kontakt)
- `style.css` – utseende (valgt design: A – Arbeidsklær)
- `assets/` – logo (SVG), bilder av Vidar


## Kontaktinfo
Telefon, e-post, adresse og org.nr. er lagt inn i `index.html` (kontaktseksjonen og bunnteksten).

## Legge til tidligere prosjekter
Seksjonen `#prosjekter` ligger klar i `index.html`, men er skjult.
1. Fjern `hidden` fra `<section id="prosjekter">`.
2. Fjern kommentaren rundt «Prosjekter» i menyen.
3. Legg bilder i `assets/prosjekter/` og kopier én `<article class="project">` per prosjekt.

## Logo
- `logo-hvit-tekst.svg` – til mørk bakgrunn
- `logo-mork-tekst.svg` – til lys bakgrunn
- `logo-merke.svg` – bare TB-merket (brukes også som favicon)

## Søk (SEO) og AI
- Tittel, beskrivelse, Open Graph og strukturerte data (schema.org, JSON-LD) ligger i `<head>` i `index.html`.
- `sitemap.xml`, `robots.txt` og `llms.txt` ligger i rotmappen.
- Domene: https://tomrerbusk.no/ (satt i `CNAME`). Bytter dere domene, oppdater `CNAME` og adressen i alle disse filene.
