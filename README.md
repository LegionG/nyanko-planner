# Nyanko Planner

Tracker e promemoria per gli stage giornalieri di [The Battle Cats](https://battle-cats.club), con orari per giorno della settimana, notifiche del browser e checklist persistente.

## Cosa fa

- Una scheda per ogni giorno della settimana con gli stage che aprono quel giorno
- Ogni stage puo' avere un orario di inizio/fine (facoltativo): quando l'orario corrente rientra nella fascia, la voce si evidenzia come "attivo ora"
- Checklist con progresso giornaliero, si resetta automaticamente a mezzanotte
- Promemoria via notifica del browser a un orario a scelta (funziona solo mentre la pagina resta aperta)
- Tutto salvato tramite l'API di storage dell'artifact: le modifiche restano tra una sessione e l'altra

## Come si usa

La pagina è pubblicata con GitHub Pages: apri il link della repo, oppure apri direttamente `index.html` nel browser. Aggiungi/rimuovi stage con il pulsante "Aggiungi", imposta gli orari con l'icona ⏱ su ogni voce, oppure cerca uno stage specifico con la barra di ricerca in alto (mostra in quale giorno e orario ricorre).

## Aggiornare gli orari

I dati degli stage non sono ricavabili da un'API pubblica (l'endpoint ufficiale richiede una richiesta firmata con una chiave interna al client del gioco). Il modo più pratico è controllare il calendario eventi in gioco e aggiornare gli orari a mano nell'app, oppure incollare lo screenshot/testo del calendario in chat con Claude e farselo aggiornare.

## Licenza

Uso personale, nessuna licenza formale.
