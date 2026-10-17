# DGMPIA public information pages

Solo pagine informative pubbliche. Nessun sorgente DGMPIA o segreto.

## Caricamento
1. Estrarre lo ZIP e caricare index.html, privacy.html e .nojekyll nella radice del repository pubblico dimagic5/dgmpia-info. README.md è facoltativo.
2. GitHub: Settings → Pages → Source: Deploy from a branch → main → / (root) → Save.
3. Attendere il deployment e verificare entrambi gli URL in una finestra privata:
   - https://dimagic5.github.io/dgmpia-info/
   - https://dimagic5.github.io/dgmpia-info/privacy.html
4. Google Auth Platform → Branding:
   - Nome: DGMPIA
   - Email assistenza: il proprio indirizzo monitorato
   - Homepage: https://dimagic5.github.io/dgmpia-info/
   - Privacy: https://dimagic5.github.io/dgmpia-info/privacy.html
   - Dominio autorizzato: dimagic5.github.io (verificarne l'accettazione nella console).
5. Salvare e riprovare la pubblicazione. Se Google richiede la verifica del dominio, seguire la procedura indicata; questi file da soli non garantiscono l'approvazione.

Il callback resta http://127.0.0.1:18080/api/watchlist/oauth/callback/google.

Prima di pubblicare, verificare che le dichiarazioni della privacy corrispondano alla versione installata e all'ambiente effettivo. Il testo è basato sul flusso OAuth descritto nella conversazione; i sorgenti correnti non sono stati ispezionati per questa consegna. Se l'account GitHub o il repository cambiano, aggiornare link e URL. Non caricare lo ZIP come unico file nel repository: estrarlo prima.
