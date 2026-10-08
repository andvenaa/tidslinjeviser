# Tidslinjeviser

En enkel nettside for å se gjennom Google Maps-tidslinjen (posisjonslogg) på PC.
Alt skjer i nettleseren – tidslinjefilen lastes aldri opp noe sted.

## Bruk

1. Eksporter tidslinjen fra Android: **Innstillinger → Posisjon → Posisjonstjenester → Tidslinje → Eksporter tidslinjedata**.
2. Flytt `Timeline.json` til PC-en.
3. Åpne `index.html` (eller GitHub Pages-adressen) og last inn filen.

Støtter også iPhone-eksport og eldre Google Takeout-filer (`Records.json` og *Semantic Location History*).

## Funksjoner

- Dag-for-dag-visning med kart, besøk og forflytninger farget etter transportmiddel
- Flere kartlag: Esri, Kartverket, satellitt og OpenTopoMap
- Valgfritt oppslag av stedsnavn og adresser (Esri og Kartverket) – sender da koordinater for besøkte steder
- Egne navn på steder (lagres lokalt i nettleseren)
- Eksport til GPX (per dag) og CSV (alt)

## Personvern

Ikke legg tidslinjefiler i dette repoet. `.gitignore` stopper `*.json`, `*.gpx`, `*.csv` og `*.kml`.
