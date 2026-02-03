🎸 GP5 Studio Web Player (DeX Optimized)
Un player di tablature Guitar Pro (GP3, GP4, GP5, GPX) basato sul web, ottimizzato per l'uso su dispositivi mobili e ambienti desktop come Samsung DeX. Sviluppato per offrire un'esperienza di studio musicale superiore, senza pubblicità e con funzionalità di looping avanzate.

🚀 Caratteristiche Principali
Core Engine: Basato sulla libreria AlphaTab per il rendering vettoriale della notazione musicale e la sintesi audio in tempo reale (SoundFont Sonivox).

Zero Latency Audio: Utilizza l'API WebAudio per una riproduzione fluida e un metronomo preciso.

Speed Trainer: Algoritmo personalizzato per l'incremento automatico della velocità (BPM) a ogni ripetizione del loop.

Smart Count-In: Sistema di conteggio intelligente che rileva la time signature (es. 3/4, 4/4) e adatta il pre-roll ritmico.

DeX Optimized UI: Interfaccia responsive con layout "Sticky Header" e area di scorrimento isolata, progettata per evitare sovrapposizioni su schermi touch e desktop mode Android.

🛠️ Soluzioni Tecniche Specifiche
Anti-Inversion Rendering: Implementazione di forced-color-adjust: none e gestione manuale dei contesti Canvas per prevenire l'inversione cromatica forzata (Force Dark Mode) tipica dei browser Chromium su Android (il problema delle "note rosse").

Native Dark Theme: L'applicazione forza una palette cromatica scura (#121212 background, #FFFFFF ink) per garantire il massimo contrasto e prevenire il "text dimming" sui display OLED.

PWA Ready: Include manifest e meta-tag Apple Touch Icon per l'installazione come Web App sulla schermata home, con icona vettoriale SVG integrata nel codice (nessuna dipendenza esterna).

Local Storage Persistence: Salvataggio automatico delle preferenze utente (BPM, Zoom, Loop, Impostazioni Trainer) nel browser.

📦 Stack Tecnologico
HTML5 / CSS3 (Flexbox & CSS Variables)

Vanilla JavaScript (ES6+)

AlphaTab Library

FontAwesome (Icons)

Google Fonts (Orbitron & Roboto)
