# DataBase
Progetto di Basi di Dati e Laboratorio Basi di Dati (Università Parthenope)

![image](https://user-images.githubusercontent.com/93930204/204033176-a2711403-916b-4332-b533-8cba2c7ede15.png)

Si vuole realizzare una base di dati per la nota multinazionale Ikea, una catena specializzata nella produzione e vendita di svariate tipologie di articoli, principalmente quelli di arredamento.

Il Database deve contenere informazioni relative alla gestione completa della multinazionale, quindi vengono trattati i dati circa: Il personale, la fornitura, la fabbrica dove vengono prodotti gli articoli, i vari punti vendita, gli articoli e la relativa suddivisione tra esposti ed immagazzinati, gli ordini fatti dai clienti con relativo finanziamento concesso dalla finanziaria e le modalità di ritiro o spedizione dell’ordine.
La gestione del personale deve comprende un “calendario” dove vi sono i turni effettuati e i turni programmati di ogni dipendente, del relativo punto vendita, identificati da un numero tesserino che timbra l’orario di ingresso e di uscita, inoltre i turni effettuati non potranno essere inseriti se non vi è un turno programmato coincidente.

Per ogni dipendente sarà specificato il salario percepito, che dovrà rispettare dei range di salario minimo e massimo, nel caso in cui il dipendente in questione abbia più di 40 anni il salario minimo sarà maggiore.  Inoltre, non potrà essere registrato personale con età inferiore a 18. Il processo di fornitura del punto vendita deve essere trattato in maniera completa, specificando il fornitore della fabbrica, la materia prima in questione compresa nella fornitura da inviare al complesso produttivo il quale costruirà il prodotto finale, al fine di indicare che articolo e in quale quantità arrivi al punto vendita, tracciando in maniera analitica le date degli spostamenti della merce.

Ogni punto vendita deve avere un orario di apertura e un orario di chiusura in linea con gli standard dell’azienda, con reperibilità telefonica.
Per quanto riguarda gli articoli identificati da un codice, bisogna stabilire in che quantità vengono approvvigionati al punto vendita e quali vengono esposti e quali immagazzinati. L’articolo, se disponibile, sarà poi presente in un ordine, al quale si può applicare una promozione, se presente. Le promozioni avranno un data di inizio, una data di termine e una percentuale da scontare sull’ordine.

Gli ordini comprendono l’articolo e la quantità acquistata con relativo totale, essi sono visualizzabili dal cliente e pagabili tramite finanziamento concesso dalla finanziaria, inoltre si deve rendere possibile sia il ritiro nel punto vendita che la spedizione all’abitazione del cliente con informazioni sul corriere e date di consegna.

All’interno del database dovranno essere conservate anche le generalità di ogni cliente identificati dall’indirizzo e-mail, inoltre, sarà possibile memorizzare più numeri di telefono e diversi tipi di pagamento.

Realizzato da:
Gianfranco Terrazzano
Ilaria Scuotto
Giuseppe Orlando
