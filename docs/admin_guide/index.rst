Manuale Amministratore
======================

Homepage
--------
La homepage della piattaforma TrasparenzAI è stata progettata per garantire immediatezza e semplicità nella consultazione dei risultati ottenuti. L'interfaccia mostra chiaramente i dati relativi all’ultima scansione effettuata, fornendo un quadro sintetico del numero di pubbliche amministrazioni analizzate e della conformità riscontrata. È possibile visualizzare la cronologia dettagliata dei controlli precedenti, ciascuno accompagnato da un report scaricabile in formato CSV, e una timeline interattiva che permette di consultare rapidamente l’evoluzione dei controlli nel tempo.

.. _home-img:
.. figure:: https://raw.githubusercontent.com/trasparenzai/ui-service/refs/heads/main/home.png
  :width: 800
  :alt: Home Page

  Homepage - Interfaccia Web

Header (Intestazione)
---------------------
#. Presenta la barra superiore istituzionale con il riferimento al `Protocollo d’intesa tra l’Autorità Nazionale Anticorruzione e il Consiglio Nazionale delle Ricerche del 7 agosto 2023 <https://www.anticorruzione.it/-/protocollo-d-intesa-tra-l-autorit%C3%A0-nazionale-anticorruzione-e-il-consiglio-nazionale-delle-ricerche-7-agosto-2023>`__, e al menu di accesso rapido (credits, documentazione, login).
#. Il menu di navigazione principale è responsive e può essere collassato su dispositivi mobili,
   presenta le seguenti voci:

.. hlist::
    :columns: 4

    * Mappa delle Amministrazioni
    * Regole
    * Grafici e Mappe
    * Esplora Sezioni

Homepage - sezione ultimo controllo
-----------------------------------------------
Layout a griglia con card che illustrano i principali dati dell'ultimo controllo eseguito.
La prima card illustra i dati ragruppati per stato, la card centrale invece
mostra una torta con le percentuali degli stati la cui legenda è esplicitata nell'ultima card a destra.

.. _home-last_scan-img:
.. figure:: images/ui-home-last_scan.png
  :width: 800
  :alt: Home Page - Ultima scansione

  Homepage - Ultima scansione

Homepage - sezione cronologia dei controlli
-----------------------------------------------
La piattaforma offre un riepilogo visivo delle scansioni precedenti, ciascuna con dati sintetici e la possibilità di esportare i risultati.
La sezione è composta da un carousel che permette di scorrere la cronologia dei controlli memorizzati dal sistema. Le informazioni includono data e ora del controllo, numero di amministrazioni analizzate, conformità rilevate. Qualora si abbia il ruolo necessario, è possibile l'esportazione in formato *csv* dei dati.
Il link *"LEGGI DI PIU' ->"* mostra la distribuzione geografica dei dati del singolo controllo.

.. _home-carousel-img:
.. figure:: images/ui_carousel.png
  :width: 800
  :alt: Home Page - Carousel

  Homepage - Carousel

Homepage - sezione timeline
-----------------------------------------------
La sezione in homepage presenta una timeline verticale delle scansioni con il riepilogo dei risultati ottenuti.
Ogni nodo nella linea del tempo consente di consultare nel dettaglio i dati della relativa scansione, fornendo una visione cronologica dell’attività di monitoraggio.
Per ogni nodo è anche presente un link attivo alla distribuzione geografica dei dati del singolo controllo.

.. _home-timeline-img:
.. figure:: images/ui-timeline.png
  :width: 800
  :alt: Home Page - Timeline

  Homepage - Timeline

Menù "Mappa delle Amministrazioni"
----------------------------------
Il menù "Mappa delle Amministrazioni" offre una visualizzazione geografica interattiva dei risultati ottenuti. L'utente può consultare grafici a torta che sintetizzano la conformità delle sezioni “Amministrazione Trasparente” per macro-aree. Zoomando sulla mappa, è possibile arrivare fino al dettaglio delle singole amministrazioni, visualizzando informazioni puntuali sulla conformità normativa di ciascun Ente.

.. _mappa_amministrazioni-img:
.. figure:: images/ui_mappa_amministrazioni.png
  :width: 800
  :alt: Menù - Mappa delle Amministrazioni

  Menù "Mappa delle Amministrazioni" - immagine generale

Attraverso la sezione “Mappa delle Amministrazioni”, l’utente accede a una rappresentazione geospaziale delle PA. Ogni area geografica è rappresentata da un grafico a torta che sintetizza il livello di conformità degli enti pubblici locali. Cliccando sulle aree, è possibile visualizzare i risultati per provincia e comune.
Il sistema consente uno zoom progressivo che, da macro-cluster regionali, permette di arrivare fino al dettaglio delle singole amministrazioni, con accesso diretto alla scheda di ciascun ente e alle sue informazioni specifiche.

.. _mappa_amministrazioni_zoom-1-img:
.. figure:: images/ui_mappa_amministrazioni_zoom-1.png
  :width: 800
  :alt: Menù - Mappa delle Amministrazioni zoom 1

  Menù "Mappa delle Amministrazioni" - zoom 1

.. _mappa_amministrazioni_zoom-2-img:
.. figure:: images/ui_mappa_amministrazioni_zoom-2.png
  :width: 800
  :alt: Menu - Mappa delle Amministrazioni zoom 2

  Menù "Mappa delle Amministrazioni" - zoom 2

Menù "Cerca Amministrazioni"
----------------------------
La piattaforma dispone di un sistema di ricerca avanzata che permette di individuare specifiche pubbliche amministrazioni utilizzando filtri come codice IPA, denominazione dell'ente, codice fiscale, categoria amministrativa, località (comune, provincia, regione). Questa funzionalità semplifica significativamente l’individuazione dell'Amministrazione di cui si ricercano le informazioni e i risultati del monitoraggio.
L’interfaccia di ricerca avanzata consente il filtraggio degli enti pubblici per codice IPA, denominazione ufficiale, codice fiscale, categoria (es. istituti scolastici, ordini professionali), localizzazione geografica (comune, provincia, regione) e criterio di ordinamento. I risultati restituiti sono immediatamente esplorabili.

.. _ricerca_amministrazioni-img:
.. figure:: images/ui-ricerca_amministrazioni.png
  :width: 800
  :alt: Menu - Cerca Amministrazioni

  Menù - Cerca Amministrazioni

Sezioni manuale

.. toctree::
   :maxdepth: 3
   :caption: Manuale Amministratore

   menu_cerca-amministrazioni
   menu_mappa-amministrazioni
