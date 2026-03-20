Dette er en README.md skreddersydd for din HTML-kode. Den fokuserer på de tekniske spesifikasjonene, funksjonaliteten i koden din, og inkluderer den strukturerte oversikten (sheet) du ba om.
🥗 MatMester - Avansert Måltidsplanlegger
MatMester er en responsiv Android-optimalisert webapplikasjon bygget med HTML5, Tailwind CSS og Vanilla JavaScript. Appen automatiserer prosessen med å sette opp ukesmenyer basert på kalori-mål og personlige preferanser.
📊 Middagsplanlegger Oversikt (System Sheet)
Denne tabellen beskriver logikken og dataflyten som er implementert i HTML-koden din:
| Modul | Funksjon | Beskrivelse | Data-håndtering |
|---|---|---|---|
| Premium Import | 30 Middagsforslag | Genererer automatisk 30 varierte middagsoppskrifter ved ett klikk. | JSON Array Injection |
| Profil-Logikk | Kalorikontroll | Sammenligner måltidenes totale kcal mot brukerens dagsmål. | LocalStorage Sync |
| Smart-Filter | Kategori-matching | Sorterer mellom Frokost, Lunsj og Middag for riktig plassering i planen. | Array Filtering |
| Ukes-Auto | Full Randomisering | Algoritme som velger tilfeldige retter fra databasen for 7 dager. | Math.random() Logic |
| Logistikk | Handleliste-gen | Aggregerer ingredienser fra alle valgte måltider og teller antall. | Object Mapping |
🚀 Tekniske Funksjoner i Koden
1. Automasjon & Skript
Appen bruker en "Generate-until-perfect" tilnærming. Hvis brukeren ikke er fornøyd med ukesplanen, kan en ny plan regenereres øyeblikkelig med ett trykk. Systemet henter data fra 30 ferdigdefinerte "Premium"-oppskrifter som inkluderer:
 * Navn og Kategori
 * Kaloriinnhold og Tilberedningstid
 * Rating-system (1-5 stjerner)
 * Ingrediensliste og Fremgangsmåte
2. Brukergrensesnitt (UI)
 * Tab-basert navigasjon: Sømløs veksling mellom Oppskrifter, Planlegger, Handleliste og Innstillinger.
 * Responsivt Design: Utviklet med Tailwind CSS for å fungere optimalt på både Android-enheter og desktop.
 * Modale vinduer: Elegante pop-ups for detaljvisning og registrering av nye retter.
3. Lagring
All data lagres lokalt på enheten via localStorage. Dette betyr:
 * Ingen behov for ekstern database eller server.
 * Appen fungerer raskt og beholder data selv etter at nettleseren lukkes.
 * Data-nøkler: mp_recipes_v2, mp_settings, mp_plan.
🛠 Slik bruker du appen
 * Importer Start-data: Trykk på "Hent 30 Premium Middager" for å fylle databasen.
 * Sett Mål: Gå til "Innstillinger" og definer ditt daglige kalorimål.
 * Generer Plan: Naviger til "Måltidsplan" og trykk på "Generer Ny Plan".
 * Handle: Sjekk "Handleliste" for en ferdig sortert liste over alt du trenger for uken.


