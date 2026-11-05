# NESLCreatives

Hjemmeside for NESLCreatives: AI-effektivisering, marketing og markedsmapping for danske virksomheder.

## Opbygning
- Én statisk side: `index.html` (HTML, CSS og JS i samme fil, ingen build-trin).
- Hostes på Netlify. Formularerne `markedsmapping` og `booking` bruger Netlify Forms (`data-netlify="true"`).
- Al tekst på siden er på dansk.

## Design
- Farver er defineret som CSS-variabler i `:root` med lyst og mørkt tema. Brug altid variablerne, aldrig faste farver.
- Skrifttyper: Bricolage Grotesque (overskrifter) og Figtree (brødtekst) fra Google Fonts.
- Siden skal virke på mobil (ca. 390px bredde) uden vandret scroll.

## Når du ændrer noget
- Åbn siden i en browser på mobil- og desktopbredde og tjek, at intet flyder over.
- Ændr ikke formularernes `name`-attributter uden at sige det, da Netlify gemmer felterne under de navne.
