---
layout: page
title: Upgrade Mac mini (Mid 2011) con SSD esterno
permalink: /progetti/MacMini/
---
  
  

#### Elenco del materiale necessario per l'upgrade
  
  
* [SanDisk Extreme SSD Portatile 500 GB](https://amzn.to/2Mgch1b)
* [Apple Adattatore da Thunderbolt 3 (USB-C) a Thunderbolt 2](https://amzn.to/2T207LZ)
* [Cavo Thunderbolt Apple (0.5 m)](https://amzn.to/2FOBTB5)
  
  
- - -
  
#### Procedura
  
  
1. Eseguire un back-up completo con Time Machine

2. Scaricare tramite App Store l'installer della versione desiderata di MacOS. La versione più recente supportata da questo modello di Mac mini è macOS High Sierra (10.13)

3. Collegare il disco esterno SSD al Mac mini utilizzando gli adattatori: Mac mini --> cavo Thunderbolt --> adattatore da Thunderbolt 2 a Thunderbolt 3 (USB-C) --> SSD

4. Aprire l'applicazione *Utility Disco* e selezionare nella colonna a sinistra il disco SSD. ATTENZIONE: il disco vero e proprio è la prima linea del gruppo, nella sezione dei dischi esterni. Le voci raggruppate sotto sono invece le partizioni o i contenitori

5. Cliccare su *Inizializza* e dal pop-up che si apre selezionare:
    * nome: a scelta, ad esempio MacOS SSD
    * formato: preferibilmente *APFS*, altrimenti *Mac OS esteso (journaled)*
    * schema: *Mappa partizione GUID*
    
6. Cliccare su *inizializza* per confermare e procedere

7. Terminata la procedura di inizializzazione, occorre lanciare l'*installer del sistema operativo* appena scaricato, che si trova nella catella Applicazioni

8. Arrivati alla schermata di scelta del disco su cui effettuare l'installazione, premere su *Mostra tutti i dischi* e selezionare il nuovo SSD esterno

9. Suggerisco di non ripristinare dal back-up di Time Machine durante l'installazione. È più efficace effettuare un'installazione pulita e procedere successivamente al recupero dei dati necessari

10. Terminata l'installatione del sistema operativo, il Mac dovrebbe avviarsi automaticamente dal disco esteno. Se ciò non avviene, occorre riavviare il Mac e tenere premuto il tasto *Opzione* durante la fase di riavvio. Si apre la schermata di selezione del disco di avvio ed è sufficiente cliccare sul disco esterno. Una volta avviato il sistema, conviene controllare le impostazione dell'ordine di avvio. Apire *Preferenze di Sistema*, selezionare *Disco di Avvio*, cliccare sul lucchetto in basso a sinistra per sbloccare le modifiche, e selezionare l'SSD come disco di avvio predefinito.

    Se ci sono dubbi, la pagina del supporto Apple spiega dettagliatemente quest'ultima operazione: https://support.apple.com/it-it/HT202796
  
  
*In qualità di Affiliato Amazon io ricevo un guadagno dagli acquisti idonei*
