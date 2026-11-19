# Mattekraft

Morsom matte for 1.–6. trinn (LK20) med Kubo: forklaringer, oppgaver, kroner, pokaler, dagens oppdrag, lynrunde i gangetabellen og premier per trinn.

Appen er én HTML-fil uten server. Fremgangen lagres i nettleseren på telefonen.

## Legge ut på GitHub Pages
1. Lag et nytt repository på github.com (f.eks. `mattekraft`). Det må være **Public** for gratis GitHub Pages.
2. Trykk **Add file → Upload files**, og dra inn alle filene i denne mappen: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png` og `README.md`. Trykk **Commit changes**.
3. Gå til **Settings → Pages**. Under *Build and deployment* velger du **Deploy from a branch**, branch **main** og mappe **/ (root)**. Trykk **Save**.
4. Etter 1–2 minutter ligger appen på `https://<brukernavn>.github.io/mattekraft/`.

## På iPhone
1. Åpne adressen i **Safari**.
2. Trykk **Del → Legg til på Hjem-skjerm**.
3. Lag en daglig påminnelse i **Snarveier → Automatisering → Tidspunkt** med handlingene «Vis varsel» og «Åpne URL».

## Oppdatere
Kjør `build-web.ps1` på nytt og last opp den nye `index.html` og `sw.js` (erstatt de gamle).
