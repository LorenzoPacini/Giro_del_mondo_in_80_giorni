# Giro_del_mondo_in_80_giorni

Il progetto si basa sul dataset di città `worldcities.xlsx`, che contiene 26569 città in tutto il mondo.

Partendo da `Londra` e sapendo che da ogni città ci possiamo spostare solo verso le tre città più vicine ad Est e che il tempo di percorrenza è di:
- 2 ore per la città più vicina
- 4 ore per la seconda città più vicina
- 8 ore per la terza più vicina

e inoltre richiede:
- 2 ore aggiuntive se la città di destinazione si trova in un altro stato
- 2 ore aggiuntive se la città di destinazioneha più di 200.000 abitanti

Dobbiamo riuscire a trovare, se esiste, una strada che possa riportarci a Londra, che sia la più breve possibile e caloclare quanto tempo ci impiegherà.
