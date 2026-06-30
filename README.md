## ProgettoMobilePrivato
# To-do list:
1. Controllare perché il bilancio delle spese totali non risulta, non conta il costo delle attività
2. ✔️ Controllare lo stato del viaggio (Archiviato, In corso, Futuro e Passato)
    - l'Errore stava nel trips_list_screen.dart che non prendeva il valore di status ma di computedstatus. Controllare bene poi il funzionamento
3. ✔️Controllare l'ordinamento dei viaggi (1: in corso, 2: Futuro, 3:Passato/Archiviato)
    - Modifica in trips_lsit_screen e trip_provider
4. ✔️Cambiare il colore delle cards in base allo stato (che viene calcolato ogni volta che viene caricata la schermata dei viaggi)
    controllare anche il filtro per data in modo che facci aselezionare solo le date del viaggio
    - Modifica trips/trip_form_screen.dart
7. Visualizzare gli archiviati a parte
8. ✔️Si possono aggiungere spese in negativo alle singole trips, alle attività
    - Ho modificato feature/expenses/expense_form_screen.dart, feature/activities/activity_form_screen.dart
9. ✔️Controllare il segmento valigia perché utilizza AI per generare una valigia
    - non usa AI ma un array popolato dai vari oggetti
10. ✔️Le checklist devono apparire chiuse e si aprono al touch della lista
    - Ho modificato features/checklists/checklists_screen.dart
11. Se la checklist "🧳 Valigia " esiste, deve scomparire il pulsante "Genera valigia"
12. Gli elementi della valigia generata deve essere forse più corta
13. Le spese delle attività non compaiono nelle spese totali delle statistics
14. Nei viaggi si possono mettere date prima di oggi sia alla modifica che alla creazione