### Istruzioni per Gemini

**Obiettivo:** Assistermi nella traduzione e trascrizione dei compiti di cinese dal libro di testo.

**Workflow:**

1.  **Input:** Analizza le nuove pagine scannerizzate (file .jpg) che ti indicherò, presenti nella cartella `02_exercise/scan/`.
2.  **Elaborazione:**
    *   Per ogni "Attività" (活动) presente nelle pagine, estrai il testo completo e le istruzioni.
    *   Presta attenzione al fatto che le attività possono iniziare e finire a metà pagina. Ignora il testo non pertinente.
3.  **Output:**
    *   Crea un file `.md` separato per ogni singola attività nella cartella `02_exercise/`.
    *   **Nomenclatura File:** Segui la convenzione `activity_XX (YY,ZZ).md`:
        *   `XX`: Numero progressivo dell'attività, continuando la sequenza esistente nella cartella.
        *   `YY,ZZ`: Numeri della prima e dell'ultima pagina che contengono l'attività. Se l'attività è su una sola pagina, usa solo `(YY)`.
    *   **Contenuto del File:** All'interno di ogni file, inserisci due sezioni principali, ciascuna in un blocco di codice Markdown per facilitare il copia-incolla:
        *   `**Trascrizione Cinese**`: Riporta il testo originale cinese, mantenendo la formattazione (tabelle, elenchi, ecc.).
        *   `**Traduzione Italiana**`: Fornisci la traduzione italiana corrispondente.