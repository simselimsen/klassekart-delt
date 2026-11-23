# Klassekart

Generator for tilfeldige klassekart som tar hensyn til historikken: elever som har sittet sammen før, havner ikke sammen igjen, og de som har sittet foran, flyttes bakover (og omvendt).

**Bruk verktøyet:** gå til GitHub Pages-adressen for dette repoet, eller åpne `index.html` i nettleseren.

## Last ned og bruk uten nett
Trykk **Last ned** øverst til høyre på nettsiden. Da får du fila `klassekart.html`, som du kan lagre hvor du vil og åpne i nettleseren, også uten nett. Knappen vises bare på nettsiden, ikke i den nedlastede kopien.

Klassene og historikken din følger ikke med av seg selv, fordi nettleseren lagrer dem separat for nettsiden og for den lokale fila. Huk av for «Last ned klassene og historikken min også», så får du en datafil i tillegg. Åpne den lokale fila og hent datafila inn med «Importer fil», eller dra den inn i vinduet.

## Funksjoner
- Makkerpar og makkergrupper med fargekoder
- Pultene kan dras og slippes enkeltvis
- Flere klasser i samme fil, hver med eget rom, elevliste og historikk
- «Snu navnene» for lesing fra kateteret
- Utskrift som plakat i liggende format, med fargene på gruppene
- Eksport og import av historikk som JSON

## Personvern
Elevnavn og historikk lagres bare i nettleseren din (localStorage) og sendes aldri noe sted. Ingenting om elevene ligger i denne filen eller i repoet. Ta jevnlig sikkerhetskopi med eksportknappen.

Ingen eksterne avhengigheter, så verktøyet virker også uten nett.
