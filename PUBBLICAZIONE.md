# Pubblicazione GitHub Pages

Questa cartella contiene soltanto i materiali pubblici di Officina 3D. Il codice dell'applicazione non deve essere caricato nel repository della pagina.

Indirizzo predisposto: `https://rvisc.github.io/officina3d/`, ricavato dalla struttura delle altre pagine Vis-K. Prima dell'invio allo Store verificare che il repository pubblico si chiami `officina3d` e che questi indirizzi rispondano correttamente. Nessuna pubblicazione remota è stata eseguita da questi script.

1. Estrarre `setup/pacchetti/Officina3D-0.1.36-Pagine-GitHub.zip` nella radice del repository della pagina, oppure copiarvi il contenuto di questa cartella includendo `.nojekyll`. Lo ZIP contiene solo i 79 file pubblici verificati, senza codice o dati dell'app.
2. Abilitare GitHub Pages sulla cartella pubblicata. `index.html` è autonomo e non richiede un tema Jekyll, dipendenze JavaScript o servizi esterni.
3. Verificare `privacy.html`, `eula.html`, i selettori delle sei lingue, i documenti e le 36 schermate.
4. Inserire nel Partner Center gli URL privacy/EULA della pagina pubblicata; caricare il MSIX, le schede e gli screenshot corrispondenti alle lingue.

`README.md` presenta lo stesso prodotto in sei lingue. `style.scss` corrisponde alla sorgente CSS fornita; la pagina statica carica direttamente `style.css`. Logo dell'app e logo Vis-K sono quelli esistenti; `sfondo.png` è il nuovo sfondo specifico Officina 3D.

Verifica del 10 novembre 2026: il repository pubblico `https://github.com/rvisc/officina3d` risponde 404. Confermare il nome o creare il repository dedicato prima di usare gli URL nello Store. Un repository privato può risultare non visibile al controllo pubblico: il dato non prova che non esista nell'account dell'editore.
