# Sterrenweg

Een vriendelijk arcadespelletje in de browser. Je stuurt een raketje over een neonweg door de ruimte en maakt slapende planeetjes wakker met sterrenstof. Elke treffer geeft vuurwerk.

Alles zit in één bestand (`index.html`): HTML, CSS en JavaScript met een canvas. Er zijn geen plaatjes en geen bibliotheken nodig. Alleen de lettertypes komen van Google Fonts.

## Spelen

- **Mac/pc:** ← → sturen, spatie schieten (vasthouden mag), P pauze, M geluid aan/uit
- **iPhone/iPad (liggend):** sleep met je vinger om te sturen. Zolang je vinger op het scherm staat, schiet je. Via Deel → *Zet op beginscherm* krijg je een eigen icoon en speel je op het volledige scherm.

## Regels

- Glipt er een slapend planeetje langs, dan ben je een hartje kwijt.
- Een gouden ster is 50 punten waard.
- Elke 5 treffers op rij gaat de vermenigvuldiger omhoog. Tien op rij geeft een supernova.
- Bij 5.000 punten begint **level 2**: andere kleuren, bochten in de weg, een hoger tempo, meer wiebelende planeetjes en power-ups:
  - **Drieling** (mint): drie stralen tegelijk
  - **Snelvuur** (goud): sneller schieten
  - **Vertraging** (blauw): alles gaat langzamer
  - **Extra hartje** (roze): één hartje erbij, tot maximaal vijf
  - **Hartjes vol** (magenta): weer drie hartjes, alleen als je er minder hebt
- Bij 15.000 punten begint **level 3**, de Groene Nevel:
  - **Kristalblokken** op de weg: niet tegenaan botsen, want dat kost een hartje. Je sterrenstof ketst erop af, dus ontwijken is de enige manier. Er blijven altijd twee plekken naast elkaar vrij.
  - **Kiemplaneetjes** (met blaadjes): raak je er een, dan komen er twee kleintjes uit. Een gemist kleintje kost geen hartje, wel je reeks.
  - **Schild** (lila, nieuwe power-up): één keer dwars door een blok heen.
- Elk nieuw level begin je met volle hartjes.

Zet `#level2` of `#level3` achter het adres om meteen in dat level te beginnen.

## Lokaal openen

```bash
open index.html
```
