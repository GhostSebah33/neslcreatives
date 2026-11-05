# NESLCreatives

Hjemmeside for NESLCreatives: AI-effektivisering, marketing og markedsmapping for danske virksomheder.

## Opbygning
- Én statisk side: `index.html` (HTML, CSS og JS i samme fil, ingen build-trin).
- Hostes på Netlify (neslcreatives.netlify.app). Netlify Forms bruges ikke.
- Markedsmapping-formularen sendes med `fetch` til Web3Forms (`FORM_ENDPOINT` og `ACCESS_KEY` i scriptet), som videresender den som mail. `_honey` er et spamfelt.
- Møder bookes via en indlejret Cal.com-kalender (`#cal-inline`, link `sebastian-lund-mhi1he/moede-med-neslcreatives`).
- Al tekst på siden er på dansk.

## Design
- Farver er defineret som CSS-variabler i `:root` med lyst og mørkt tema. Brug altid variablerne, aldrig faste farver.
- Skrifttyper: Bricolage Grotesque (overskrifter) og Figtree (brødtekst) fra Google Fonts.
- Siden skal virke på mobil (ca. 390px bredde) uden vandret scroll.

## Når du ændrer noget
- Åbn siden i en browser på mobil- og desktopbredde og tjek, at intet flyder over.
- Feltnavnene (`name`) bliver til overskrifterne i de mails, der sendes, så hold dem korte og på dansk.
