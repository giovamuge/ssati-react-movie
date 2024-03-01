# Corso SSATI React e Typescript

Esercitazione in React con [Next.js](https://nextjs.org/) o semplicemente una Single Page App vuota aggiungendo personalmente tutti i pacchetti necessari per il raggiungimento del progetto.

## Introduzione

Qui potrai mettere in pratica tutte le tue conoscenze ed esprimerti creativamente nella realizzazione di un catalogo web di film. Next.js è un framework per React che offre tutti gli strumenti necessari per realizzare qualsiasi tipo di sito web o web app. Utilizza al massimo tutte le sue funzionalità aiutandoti con la [documentazione](https://nextjs.org/docs).

## Tasks

- [ ] Creare un progetto con `npx create-next-app@latest` (se desideri usare Next) oppure `npx create-react-app my-app`(se desideri utilizzare uno starter React app)
- [ ] Utilizza typescript, quindi ogni props, funzione e ogni oggetto devono essere tipizzati. Prendi subito confidenza con il typing, in funturo tornerà utile!
- [ ] Se non utilizzate Next e il suo tool per il routing adoperate [react-router-dom](https://reactrouter.com/en/main)
- [ ] Configurare [OMDb API](https://www.omdbapi.com/) (è un database aperto di film con 1k richieste possibili al giorno) oppure il proprio servizio backend sviluppato nel modulo ASP.NET Core
- [ ] Scegli come scrivere la tua UI, puoi farlo utilizzando una libreria CSS di tuo gradimento, ne esistono tantissime, tra le più famose [Tailwind CSS](https://tailwindcss.com/) (se desideri puoi considerare anche tutte le librerie che usano Tailwind come [DaisyUI](https://daisyui.com/), [Preline](https://preline.co/), [Bootstrap](https://getbootstrap.com/) e [Bulma](https://bulma.io/), insomma c'è l'imbarazzo della scelta, ma se scrivi il tuo _stile manualmente_ sarà altrettanto gradito)
- [ ] Home Page
  - [ ] Costruire un layout come da [immagine](images/home.png).
  - [ ] Implementare la ricerca dei film e la visualizzazione di un film
  - [ ] Scrivi un custom Hook per la ricerca dei film
  - [ ] Implementa la logica necessaria per la paginazione
  - [ ] La paginazione e la ricerca per testo dovranno essere gestiti come [query string](https://en.wikipedia.org/wiki/Query_string)
- [ ] Poster Page
  - [ ] Costruire un layout come da [immagine](images/poster.png).
  - [ ] L'identificativo del film dovrà essere passato come parametri nell'URL, quindi poi letto e fatta la richiesta con l'id specifico
  - [ ] Visualizza i dati del film selezionato


## Tasks v2

Qui introdurremo uno state manager come [Redux](https://redux.js.org/) e aggiungeremo funzionalità come gestione (fittizia) del catalogo film, gestione dei film preferiti, quelli già visti e in fine una gestione della lista del catalogo film per ottimizzare le richieste. 

- [ ] Home Page
  - [ ] Quando ottieni dalla ricercha la lista dei film implementa una gestione di stato per garantine una persistenza del dato senza dover effetture una nuova ricerca quando ricarichi la pagina o navighi tra le pagine 

- [ ] Poster Page 
  - [ ] Aggiungere dei bottoni su ogni card film per salvare l'informazione film preferito e film già visto

- [ ] Backoffice Page
  - [ ] Se sei qui, stai accedendo alla sezione "avanzata", ben fatto! Qui potrai esercitarti a costruire un'applicazione web gestionale. Qui potrai usare solo il tuo applicativo backend con le operazioni CRUD necessarie
  - [ ] Realizza una pagina di Login (anche fittizia)
  - [ ] Come nel layout realizzato fino ad ora, ne crea uno in cui è possibile visualizzare, modificare e aggiungere nuovi dati al tuo catalogo di film.

## Home UI
![home movie](images/home.png)

## Poster UI
![poster](images/poster.png)