# Modifica Controllata

Applica solo la modifica minima approvata nel piano.

Se durante la modifica scopri che il piano approvato non è più valido, fermati e richiedi una nuova approvazione prima di continuare.

Prima di modificare, conferma in una frase:

- task;
- file da toccare;
- prova di controllo;
- cosa resta fuori scope;
- strategia prompt usata: zero-shot o few-shot.
- Usa zero-shot come scelta predefinita. Utilizza few-shot solo se un breve esempio (massimo 1-2) aiuta a chiarire il formato dell'output senza anticipare la soluzione.

Confini:

- non cambiare layout globale;
- non aggiungere nuove feature;
- non fare refactor non richiesti;
- non modificare routing o configurazione;
- fermati se devi toccare file fuori scope.
- preferisci la soluzione più semplice che risolve il task senza introdurre cambiamenti collaterali.

Dopo la patch:

- mostra il diff;
- spiega cosa e' cambiato;
- indica la prova di controllo.
- riporta solo evidenze brevi: assunzioni principali, criterio usato, verifica proposta.
- eventuali limiti o dubbi residui.

Se non puoi modificare file direttamente:

- non simulare di averli modificati;
- indicami il blocco di codice da cambiare;
- dimmi dove inserirlo;
- spiega perche' la modifica e' minima;
- indicami come controllarla in VS Code.

Non mostrare chain-of-thought estesa e non aggiungere esempi o alternative fuori scope.
