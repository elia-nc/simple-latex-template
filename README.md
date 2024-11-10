# simple-latex-template
Si tratta di un template molto basilare per relazioni di progetti universitari basato sul template "report" integrato in latex adattato alle esigenze, in particolare è stato adoperato per report dell'Università degli Studi di Firenze.

Questo template è stato creato durante l'apprendimento di latex stesso, sia quindi allo scopo di impararlo sia per far fronte al problema della (relativa) comnplicatezza dei template che si trovano ad esempio su OverLeaf, e che risultano difficili da capire per chi è alle prime armi. Per quanto detto il template non sarà perfetto ma risulta molto adattabile alle esigenze. Il template vuole infatti essere solo un riferimento da cui partire molto semplice in cui l'utente può modificare tutto in modo molto semplice e capendo cosa e come lo sta facendo.

# struttura
Il template è concepito per dividere i vari capitoli del report in file a se stanti consentendo una migliore organizzazione. A ogni capitolo corrisponde una cartella al cui interno sono presenti il file .tex e le risorse relative al capitolo (immagini, pdf, ...). Vi è poi una cartella per le appendici ed una per le immagini di riferimento del template (loghi e dummy image).

Si arriva dunque ai 3 file principali del template:
- main.tex: in cui avviene la composizione del documento richiamando gli altri file, si possono aggiungere ulteriori pacchetti e altro
- settings.tex: in cui si hanno le info sui pacchetti utilizzati dal template, le impostazioni base del documento, della sua geometria e la formattazione di titoli, header e footer
- frontmatter.tex: in cui si ha la generazione del frontmatter composto da title page + abstract + indici + simboli

# note finali
I file .tex sono ben commentati in modo da far capire qualsiasi istruzione a cosa serva e cosa modificare per ottenere un certo risultato. Nella cartella è presente anche la versione compilata del template nella quale vengono mostrati i risultati di istruzioni di base riutlizzabili per immagini, tabelle e equazioni.
