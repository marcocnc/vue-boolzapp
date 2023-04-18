Vue Boolzapp
===
<strong>Milestone 1</strong> <br>
Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto <br>

### Logica Milestone 1
1. Creare tutto il markup;
2. Creare l'array di oggetti contenente nome, immagine, una flag e i messaggi (che a sua volta è un array di oggetti contenente la data, il messaggio e lo status se sent o received);
3. Ora la lista che abbiamo stampato a mano sul file HTML le andremo a stampare dinamicamente con una direttiva v-for: questa direttiva andrà assegnata alla singola "card" del contatto, in cui stamperemo tutti gli indici delle immagini, i nomi e l'ultimo messaggio inviato (che sarà uguale alla lunghezza dell'array messages nell'array contact -1.message che sarà la chiave che ci serve)


<strong>Milestone 2</strong> <br>
Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione <br>
Click sul contatto mostra la conversazione del contatto cliccato
### Logica 2



<strong>Milestone 3</strong> <br>
Aggiunta di un messaggio: l’utente scrive un testo nella parte bassa e digitando “enter” il testo viene aggiunto al thread sopra, come messaggio verde <br>
Risposta dall’interlocutore: ad ogni inserimento di un messaggio, l’utente riceverà un “ok” come risposta, che apparirà dopo 1 secondo. <br>
### Logica 3

<strong>Milestone 4</strong> <br>
Ricerca utenti: scrivendo qualcosa nell’input a sinistra, vengono visualizzati solo i contatti il cui nome contiene le lettere inserite (es, Marco, Matteo Martina -> Scrivo “mar” rimangono solo Marco e Martina) <br>

<strong>Milestone 5 - opzionale</strong> <br>
Cancella messaggio: cliccando sul messaggio appare un menu a tendina che permette di cancellare il messaggio selezionato

Visualizzazione ora e ultimo messaggio inviato/ricevuto nella lista dei contatti


