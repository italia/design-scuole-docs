.. _architettura-dellinformazione:

Definizione dell'architettura informativa
=========================================

L’architettura dell’informazione del modello di sito istituzionale per le scuole è presentata nella :numref:`Tabella %s <ai>`. I contenuti sono organizzati in 4 sezioni più un'area personale accessibile tramite login, implementata nel modello solo per docenti e personale ATA.

La fase di progettazione del modello, inoltre, ha evidenziato l’utilità di un’ulteriore sezione, “La mia classe”, dove far convergere le esigenze didattiche degli alunni. La sezione non è stata implementata nel modello, ma viene messa a disposizione come prototipo a media definizione (mid-fi) come esempio di buone pratiche. La progettazione del modello, infatti, ha preso in considerazione aspetti più ampi rispetto a quelli effettivamente sviluppati, a partire, ad esempio, dagli scenari d’uso. 

.. table:: Architettura dell'informazione del sito delle scuole.
   :name: ai

   +----------------+-----------------------+-------------------------------+
   | Sezioni        | Descrizione           | Contenuti                     |
   +================+=======================+===============================+
   | Scuola         | Area di presentazione | - Presentazione               |
   |                | della scuola come     |                               |
   |                | istituzione e come    | - Organizzazione e            |
   |                | punto di riferimento  |   strutture                   |
   |                | culturale.            |                               |
   |                |                       | - Contatti                    |
   +----------------+-----------------------+-------------------------------+
   | Servizi        | Area in cui vengono   | - Adesione a progetti e gite  |
   |                | presentati i servizi  |                               |
   |                | ciascuno con una      |                               |
   |                | scheda che descrive   | - Iscrizione mensa            |
   |                | le modalità di        |                               |
   |                | fruizione (digitale   | - Iscrizione a scuola         |
   |                | e/o "sportello").     |                               |
   |                |                       | - Richiesta                   |
   |                |                       |   assistenza                  |
   |                |                       |                               |
   |                |                       | - Prenotazione                |
   |                |                       |   colloquio                   |
   |                |                       |                               |
   |                |                       | - Delega per ritiro figli     |
   |                |                       |                               |
   |                |                       | - Prestito bibliotecario      |
   |                |                       |                               |
   |                |                       | - Corsi di recupero           |
   |                |                       |                               |
   |                |                       | - Andamento scolastico        |
   |                |                       |                               |
   |                |                       | - Orientamento scolastico     |
   |                |                       |                               |
   |                |                       | - Bisogni educativi speciali  |
   |                |                       |                               |
   |                |                       | - Openday                     |
   |                |                       |                               |
   |                |                       | - Convenzioni                 |
   |                |                       |                               |
   |                |                       | - Agevolazioni                |
   |                |                       |                               |
   |                |                       | - Permessi e congedi          |
   |                |                       |                               |
   |                |                       | - Formazione                  |
   |                |                       |                               |
   |                |                       | - MAD Messa a Disposizione    |
   |                |                       |                               |
   +----------------+-----------------------+-------------------------------+
   | Notizie        | Le circolari in forma | - Circolari                   |
   |                | digitale e scritte    |                               |
   |                | con la lingua del web | - News                        |
   |                | come motore delle     |                               |
   |                | informazioni          | - Albo pretorio               |
   |                | all'interno e         |                               |
   |                | all'esterno della     | - Eventi (calendario          |
   |                | scuola.               | scuola)                       |
   +----------------+-----------------------+-------------------------------+
   | Didattica      | L'organizzazione in   | - Gli indirizzi e le classi   |
   |                | indirizzi e in        |                               |
   |                | classi. I syllabus    |                               |
   |                | dei corsi, le schede  | - I syllabus dei corsi        |
   |                | didattiche di         |                               |
   |                | specifici argomenti,  |                               |
   |                | i risultati dei       | - Le schede                   |
   |                | progetti e dei        |   didattiche degli            |
   |                | laboratori della      |   insegnanti                  |
   |                | scuola.               |                               |
   |                |                       | - Le schede dei               |
   |                | E un blog che         |   progetti della scuola       |
   |                | racconta la vita      |   e delle classi              |
   |                | della scuola          |                               |
   |                |                       | - Il blog della               |
   |                |                       |   scuola                      |
   |                |                       |                               |
   |                |                       | - Libri e materiali didattici |
   +----------------+-----------------------+-------------------------------+
   | La mia classe  | Il punto di partenza  | - Voti, note e                |
   | (solo come     | di tutte le attività  |   pagelle                     |
   | esempio di     | della classe.         |                               |
   | buone pratiche)|                       | - Calendario/registro         |
   |                |                       |   (assenze/attività)          |
   |                |                       |                               |
   |                |                       | - Rubrica                     |
   |                |                       |                               |
   |                |                       | - Link a didattica            |
   |                |                       |   digitale                    |
   +----------------+-----------------------+-------------------------------+
   | Area personale | Centro di invio       | - Messaggi                    |
   | (solo per      | messaggi con          |                               |
   | personale ATA  | richieste di attività | - Attività                    |
   | e docenti)     | (autorizzazioni,      |                               |
   |                | pagamenti, adesioni). | - Preferiti                   |
   |                | Archivio delle        |                               |
   |                | attività svolte       | - Preferenze                  |
   |                | (pagamenti e altro).  |                               |
   +----------------+-----------------------+-------------------------------+

Il progetto prevede una chiara identificazione e caratterizzazione dei modelli
di pagina (*content type*) in modo da ridurre il numero di template e strutturare
il contenuto. 

Il progetto prevede che tutti i contenuti della scuola siano in relazione tra
loro attraverso un sistema di etichette (tag) da inserire in fase di
pubblicazione dei contenuti. In occasione di migrazione del sito verso il nuovo
modello, sarà utile applicare questa classificazione anche ai principali
contenuti “storici”. 

`Vai al documento di architettura dell'informazione (ODS 337KB) <https://designers.italia.it/files/resources/modelli/scuole/adotta-il-modello-di-sito-scolastico/definisci-architettura-e-contenuti/Architettura-informazione-sito-scuole.ods>`_
