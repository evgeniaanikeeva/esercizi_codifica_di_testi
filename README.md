# codifica_di_testi
Codifica di testi-2021
Repository che contiene gli esercizi ed il progetto per l'esame Codifica di testi dell'Università di Pisa


PS a volte scrivo i commenti anche nella mia madre lingua per la chiarezza.

1. 
Creare un file .xml ed inserire un prologo con la dichiarazione XML e un commento con le vostre informazioni.

2. 
Scrivere e fare il check di un xml non opportunamente annidato.

3. 
Aprire il file XML non ben formato presente nel repository github:

validarlo con un parser XML,
correggerlo (commentando gli errori e le modifiche),
aggiungere un figlio (child) ad un elemento,
aggiungere un fratello (sibling) ad un elemento.

4. 
Inserire all’interno di un tag un frammento di codice HTML.

5. 
Definire i seguenti elementi:

elemento root: TEI
elementi figli:
header (obbligatorio una occorrenza)
facsimile (opzionale una occorrenza)
text (obbligatorio almeno una occorrenza)
Gli elementi header, facsimile e text hanno tutti un content model testuale.

6. 
root: TEI

Figli:

header(obbligatorio una volta sola)
facsimile(opzionale una volta sola)
testo(obbligatorio una o più volte)
testo è un mixed content con possibile elemento < seg >
Attributi:

header: type: (fixed, CDATA “intestazione”); lang (opzionale, NMTOKEN)
facsimile: source: (obbligatorio); ref (optionale, IDREFS)
testo: id (obbligatorio, ID) type (opzionale contenuto testuale)

7. 
includere all’interno di un documento XML la dichiarazione del tipo, definire internamente gli elementi e gli attributi e validare.
inserire nel prologo di un documento XML la dichiarazione del tipo di documento e validare.
Creare un file esterno con estensione .dtd prima di includerlo nel prologo XML.

8. 
Marcare un testo plain text di circa 3000 caratteri a piacere.
inserire prologo XML
marcare la struttura usando gli elementi fin qui descritti, in particolare marcare tutti i paragrafi usando < p > e la struttura editoriale usando < div >
verificare che sia ben formato con xmllint
salvare il file XML su github

9. 
Utilizzare puntatori, note, lista, glossario marcare nomi, rs, term.

10. 
codificare usando gli opportuni elementi TEI un articolo di rivista
codificare usando gli opportuni elementi TEI una cartolina

11. 
Trascrivere e codificare un frammento di lettera di Bellini. (Vincenzo Bellini a Carlo Pepoli, in Puteaux, 26 giugno 1834)

12. 
Codificare lettera Bellini utilizzando il tagset facsimile e il collegamento completo testo-immagine.
