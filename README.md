# Funzioni

Web app didattica di matematica sulle **funzioni**, per la scuola secondaria di secondo grado.
Tutto in un unico file (`index.html`): basta aprirlo nel browser, funziona anche offline e da
mobile. Nessuna dipendenza esterna (KaTeX e i font sono caricati da CDN quando disponibili).

Stessa struttura dell'app [equazioni-disequazioni-sistemi](https://github.com/ventilii-gif/equazioni-disequazioni-sistemi):
navigazione a sezioni, tema chiaro/scuro, grafici su canvas e motore quiz con correzione immediata.

## Struttura

- **Nota storica comune** — la nascita e l'evoluzione del concetto di funzione, da Oresme e Descartes
  a Leibniz ed Euler, fino alla definizione moderna di Dirichlet e a quella insiemistica di Bourbaki.
- **Sei sotto-sezioni**, ciascuna organizzata in quattro schede:
  **Teoria** (schede richiudibili), **Simulazione** grafica interattiva, **Prova tu** (esercizi
  guidati + esercizi generati con correzione) e **Quiz** di sezione (10 domande).
  1. **Che cos'è una funzione** — dominio, codominio, immagine; grafico; test della retta verticale.
  2. **Iniettività** — immagini distinte per elementi distinti; test della retta orizzontale.
  3. **Suriettività** — immagine uguale al codominio; dipendenza dal codominio scelto.
  4. **Biiettività** — iniettiva e suriettiva insieme; condizione di invertibilità.
  5. **Composizione** — macchina composta g∘f e f∘g; l'ordine conta.
  6. **Funzione inversa** — invertibilità, simmetria rispetto alla retta y = x, calcolo dell'inversa.
- **Quiz riepilogativo** — 20 domande su tutti gli argomenti.

In totale: 6 × 10 + 20 = **80 domande** a risposta chiusa con spiegazione, oltre agli esercizi
interattivi della scheda «Prova tu».

## Utilizzo

- In locale: aprire `index.html` con un qualsiasi browser moderno.
- Online: pubblicata con GitHub Pages (dominio personalizzato indicato nel file `CNAME`).

## Accessibilità

- Nessuna coppia di colori rosso/verde per indicare giusto/sbagliato: si usano blu e arancione con
  icone ✓/✗ come codifica ridondante.
- Tema chiaro e scuro, con rispetto delle preferenze di sistema e interruttore manuale.
- Formule matematiche rese con KaTeX; grafici ridisegnati al cambio di tema e di dimensione.
