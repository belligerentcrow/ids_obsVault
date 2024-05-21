->**Ridurre lunghezza dei metodi**, renderli piu' riutilizzabili
-> Scegliere **nuovi nomi specifici** per metodi piccoli
-> Metodi di alto livello piu' **facili da comprendere** (tramite la sequenza di chiamate a metodi piccoli)
-> **Overriding** piu' semplice

*->Creare un nuovo metodo con un nome che ne specifichi l'utilizzo -> copiare il codice estratto al nuovo metodo-> controllare le corrispondenze con variabili locali, fare diventare quest'ultime parametri del metodo nuovo -> se alcune variabili sono solo presenti nel metodo estratto, farle diventare temporanee del metodo estratto (vedi refact. (2) ) -> se una variabile locale al metodo e' modificata qua dentro, vedere se e' possibile che il metodo sia query e assegnare il risultato alla variabile locale del metodo sorgente -> sostituire nel sorgente il codice estratto con una chiamata al metodo nuovo  *