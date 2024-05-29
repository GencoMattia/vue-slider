# vue-slider

Descrizione:
Partendo dal markup della versione consegnata, creare uno slider usando Vue.
Usate i dati presenti, modificandone la posizione, in modo che siano utilizzabili nell'istanza di Vue in uso.
Bonus:
1 - Aggiungere le thumbnails che si illuminano quando la relativa immagine e' attiva
2-  Aggiungere un evento di click sulle thumbnails per rendere attiva l'immagine relativa
Consigli del giorno:
regola d'oro: riciclare ovunque possibile!
il riciclo spesso va a braccetto con le funzioni! Sapendole sfruttare bene, l'esercizio si riduce a poche righe :occhiolino:


----- PASSAGGI -----
- aggiungere struttura base di vue in js
- inserire l'array di oggetti contenente le immagini tra i data di vue
- stampare le immagini in pagina usando un v-for
- creare una funzione che assegni la classe active ad un solo elemento in base all'index
- creare due bottoni, uno aggiunge l'altro sottrae 1 dal valore index
- creare una classe active che metta in display-block l'elemento. Tutti gli altri sono in display none.

------
gli ultimi passaggi si potrebbero fare attraverso un template per il v-for e usare il v-show su un elemento solo della lista e muovere lo show attraverso index e bottoni. (Non sono sicuro della fattibilità)
------

