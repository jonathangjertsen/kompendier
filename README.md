# Kompendier

Dette repoet har LaTeX-kode for kompendiene jeg skrev på studiet.

**PDFs ligger her: http://random.timini.no/jonathrg/kompendier**

# Last ned

Hvis du ikke vil bruke git kan du laste ned en kopi ved å klikke på "Source code (zip)" her: https://github.com/jonathangjertsen/kompendier/releases/latest

# Hvordan lage et kompendium

"Template"-mappa kan brukes som utgangspunkt for et nytt kompendium.
Hoved-fila som skal kompileres er `template.tex`, og hvis du har satt det opp riktig
skal den kompilere til noe som ligner på `template.pdf` i samme mappe.

`template.tex` importerer en konfigurasjonsfil som heter `config.tex`. Her er det
en del konfigurasjon som kan slås av og på, f.eks om vektorer skal skrives som
tykke bokstaver eller som bokstaver med pil over.

Det importeres også noen ting fra mappa som heter `lib`, denne mappa har kommandoer
som er felles for flere kompendier.

Hvert kapittel er sin egen fil (`chapter1.tex` og `chapter2.tex`), disse samles til
én fil i `fetchchapters.tex` som igjen inkluderes i `template.tex`.

# Inkluderte kompendier

* `bioteknologi` - TBT41790 Bioteknologi
* `elektromagnetisme` - TFE4120 Elektromagnetisme
* `nanomaterialer` - TMT4320 Nanomaterialer
* `statistisk_termodynamikk` - TKJ4215 Statistisk termodynamikk i kjemi og biologi
