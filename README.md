# NaChi Nutrition — Personal Edition v2

PWA autonoma, offline-first, per uso personale. Non è collegata a NaChi Performance.

## Avvio e installazione

Dalla cartella `nachi-nutrition` esegui `python3 -m http.server 8000` e apri `http://localhost:8000`. Per installarla su smartphone, pubblica **il contenuto** della cartella su un sito HTTPS (GitHub Pages, Netlify o Vercel). Android: Chrome → Installa app / Aggiungi a schermata Home. iPhone: Safari → Condividi → Aggiungi alla schermata Home.

## Funzioni

- Giorni Judo, Pesi e Riposo; menù indicativi con personalizzazione delle voci giornaliere
- Spunta pasti, registro peso con grafico, idratazione e recupero con note
- Profilo, date gara/pesata, segnalazione obiettivi di perdita peso troppo rapidi
- Esportazione e importazione JSON con verifica basilare dei dati e conferma di sostituzione
- Dati locali nel browser, uso offline dopo la prima visita

## Limiti importanti

**Logo ufficiale non incluso**: non era disponibile come file sorgente in questa sessione. Le icone PNG incluse sono provvisorie, con palette nero/verde acqua, da sostituire con il logo ufficiale quando fornito. Non è stata effettuata una verifica visiva sui telefoni.

La PWA non ha autenticazione, cifratura locale dedicata, sincronizzazione cloud o backup automatico: la privacy dipende dalla sicurezza del dispositivo e del browser. Il backup JSON contiene informazioni personali in chiaro; custodiscilo in modo sicuro. Eliminare dati del browser può cancellare il diario. Il piano alimentare è indicativo e non sostituisce un dietista sportivo. Non usare per tagli di peso rapidi o disidratazione.
