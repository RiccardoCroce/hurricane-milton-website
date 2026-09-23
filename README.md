# hurricane-milton-website
Interactive website built with HTML, CSS, and JavaScript detailing Hurricane Milton's path and impact.

## Overview
This is a static, single-page website (`index.html`) that documents Hurricane Milton, one of the most intense Atlantic tropical cyclones of 2024. The page walks through the storm's formation in the Gulf of Mexico, its landfall in Florida on October 9–10, 2024, and the subsequent relief and reconstruction efforts.

## Structure
- **`index.html`** — main page, with four sections:
  1. **Storm explanation** — background on formation, rapid intensification to Category 5, and impact on Florida.
  2. **Impact and destruction** — flooding, wind damage, tornadoes, and evacuations, including an embedded video of the hurricane.
  3. **Aftermath and reconstruction** — debris removal, relief efforts, and long-term rebuilding.
  4. **Path map** — an interactive Leaflet.js map plotting the storm's track from formation to landfall to exit into the Atlantic.
- **`css/styles.css`** — page styling.
- **`js/slider.js`** — vanilla JS logic powering the image sliders/carousels in each section (previous/next navigation between slides).
- **`video/VideoUraganoMilton.mp4`** — video clip of the hurricane.
- **`docx_work/`, `docx_verify/`** — extracted contents of Word (.docx) working/verification documents related to the project (unzipped OOXML files).

## Technologies used
- Plain HTML/CSS/JavaScript (no build step required).
- [Leaflet.js](https://leafletjs.com/) (loaded via CDN) for the interactive map, using Esri World Street Map tiles.
- Images sourced from Wikimedia Commons.

## How to run
No installation needed — simply open `index.html` in a web browser. For the map tiles and images to load correctly, an internet connection is required (Leaflet library and images are fetched from external CDNs/Wikimedia).

---

# hurricane-milton-website
Sito web interattivo realizzato in HTML, CSS e JavaScript che illustra nel dettaglio il percorso e l'impatto dell'uragano Milton.

## Panoramica
Questo è un sito web statico a pagina singola (`index.html`) che documenta l'Uragano Milton, uno dei cicloni tropicali atlantici più intensi del 2024. La pagina ripercorre la formazione della tempesta nel Golfo del Messico, il landfall in Florida tra il 9 e il 10 ottobre 2024, e i successivi interventi di soccorso e ricostruzione.

## Struttura
- **`index.html`** — pagina principale, suddivisa in quattro sezioni:
  1. **Spiegazione dell'uragano** — formazione, rapida intensificazione fino alla categoria 5 e impatto sulla Florida.
  2. **Impatto e distruzione** — allagamenti, danni da vento, tornado ed evacuazioni, con un video incorporato dell'uragano.
  3. **Conseguenze e ricostruzione** — rimozione dei detriti, soccorsi e ricostruzione a lungo termine.
  4. **Mappa del percorso** — una mappa interattiva realizzata con Leaflet.js che traccia il percorso della tempesta dalla formazione al landfall fino all'uscita nell'Atlantico.
- **`css/styles.css`** — foglio di stile della pagina.
- **`js/slider.js`** — logica JavaScript (vanilla) che gestisce gli slider/caroselli di immagini in ogni sezione (navigazione avanti/indietro tra le slide).
- **`video/VideoUraganoMilton.mp4`** — video dell'uragano.
- **`docx_work/`, `docx_verify/`** — contenuti estratti di documenti Word (.docx) di lavoro/verifica relativi al progetto (file OOXML decompressi).

## Tecnologie utilizzate
- HTML/CSS/JavaScript puro (nessun processo di build necessario).
- [Leaflet.js](https://leafletjs.com/) (caricato via CDN) per la mappa interattiva, con tile della Esri World Street Map.
- Immagini reperite da Wikimedia Commons.

## Come eseguirlo
Non è richiesta alcuna installazione: basta aprire `index.html` in un browser web. Per il corretto caricamento della mappa e delle immagini è necessaria una connessione internet (la libreria Leaflet e le immagini vengono caricate da CDN esterni e da Wikimedia).
