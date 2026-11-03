# RawState

Anteprima del sito RawState, versione grafica 96 del 3 novembre 2026.

Sito: https://itavel96.github.io/rawstate/

Include palco 3D, RawState Radio, Virtual Festival, mappa e calendario degli eventi, News, Community e concept Merch.

È un’anteprima per revisionare grafica e navigazione: eventi e post sono snapshot; la radio non contiene ancora un archivio pubblico e le funzioni account e multiplayer non hanno un server attivo. Informative e contatti sono ancora da completare.

## File

- index.html: pagina iniziale e importmap.
- assets/: JavaScript, stili, immagini e font.
- vendor/three/: moduli Three.js e licenza.
- data/: snapshot del feed Instagram.
- links/: pagina separata dei collegamenti RawState.

Pubblicazione GitHub Pages dal branch main, cartella radice. Gli URL delle risorse usano il prefisso /rawstate/. Dopo modifiche ai file JavaScript occorre aggiornare i rispettivi hash SRI nell’HTML; dopo modifiche agli script inline va aggiornato anche l’hash CSP.

Per un’anteprima locale, servire la cartella che contiene rawstate con un server HTTP e aprire /rawstate/; l’apertura diretta di questi file HTML non equivale all’anteprima offline monolitica usata durante lo sviluppo.

Logo e identità RawState appartengono al progetto. Le librerie e i materiali di terze parti mantengono le rispettive licenze e diritti.
