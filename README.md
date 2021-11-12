# Interlogica
Interlogica

Lo zip INTERLOGICA contiene la struttura di tabelle per il flusso e alcuni file di input per popolare le tabelle e far girare il flusso. La cartella Interlogica deve essere ripristinata sul disco c:

Lo zip interlogica_db contiene il backup del database, la versione di sql utilizzata è la 12.0.2000.8

Prima di eseguire il flusso occorre modificare la store procedure "Flusso" andando a impostare il nomeserver\istanzasql nella parte evidenziata:

![image](https://user-images.githubusercontent.com/94203633/141595308-2e9d1001-cc23-4dba-9a1e-4e3656e13c69.png)

Si trova alla fine della store procedure.
Una volta salvata la store procedure sarà possibile eseguirla all' occorrenza o schedularla.

