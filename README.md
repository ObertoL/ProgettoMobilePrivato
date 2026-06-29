## ProgettoMobilePrivato
# To-do list:
1. Controllare perché il bilancio delle spese totali non risulta
2. ✔️ Controllare lo stato del viaggio (Archiviato, In corso, Futuro e Passato)
    - l'Errore stava nel trips_list_screen.dart che non prendeva il valore di status ma di computedstatus. Controllare bene poi il funzionamento
3. ✔️Controllare l'ordinamento dei viaggi (1: in corso, 2: Futuro, 3:Passato/Archiviato)
    - Modifica in trips_lsit_screen e trip_provider
4. Cambiare il colore delle cards in base allo stato (che viene calcolato ogni volta che viene caricata la schermata dei viaggi)
5. Constraint sulla data delle tappe rispetto la data dei viaggi a cui le tappe fanno riferimento