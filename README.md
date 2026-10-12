# Hendelseslogg

Mobilvennlig nettapp for å logge hendelser per dag for to barn. Alt lagres lokalt i nettleseren på telefonen (ingen server, ingen konto).

## Legge ut på GitHub Pages
1. Opprett et nytt repo på github.com (f.eks. `hendelseslogg`). Gjør det gjerne privat hvis planen din tillater Pages for private repoer, ellers offentlig. Appen inneholder ingen data.
2. Last opp alle filene fra denne mappen (inkludert mappen `icons`) til rotmappen i repoet.
3. Gå til Settings > Pages. Velg «Deploy from a branch», branch `main`, mappe `/ (root)`, og trykk Save.
4. Etter et minutt eller to er appen tilgjengelig på `https://<brukernavn>.github.io/hendelseslogg/`.

## Installere på Android
Åpne adressen i Chrome, trykk på menyen (tre prikker) og velg «Installer app» eller «Legg til på startskjermen». Appen virker da også uten nett.

## Viktig om data
- Loggen ligger i nettleseren på den enkelte telefonen og kommer ikke med mellom enheter.
- Tømmer du nettleserdata for siden, forsvinner loggen. Bruk Oppsett > «Kopier sikkerhetskopi» av og til, og lim teksten inn i et notat.
- Data fra prøveversjonen i Claude følger ikke med til ny adresse. Kopier sikkerhetskopi derfra og lim den inn under «Gjenopprett» i den nye appen.
- Oppdaterer du filene senere, øk `CACHE`-navnet i `sw.js` (f.eks. `hendelseslogg-v2`) slik at telefonen henter ny versjon.
