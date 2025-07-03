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
        *   `XX`: Numero progressivo dell'attività, continuando la sequenza esistente.
        *   `YY,ZZ`: Numeri della prima e dell'ultima pagina che contengono l'attività. Se l'attività è su una sola pagina, usa solo `(YY)`.
    *   **Contenuto del File:** Struttura il file ESATTAMENTE come segue, basandoti sugli esempi esistenti:
        1.  Titolo per la traduzione italiana: `# Attività XX (Italiano) (Pagina YY)` o `(Pagine YY,ZZ)`.
        2.  Testo della traduzione italiana.
        3.  Titolo per la trascrizione cinese: `# 活动 XX (中文) (页 YY)` o `(页 YY,ZZ)`.
        4.  Testo della trascrizione cinese.
    *   **Importante:** NON usare blocchi di codice (```markdown) per racchiudere il contenuto. La formattazione Markdown (tabelle, grassetto, ecc.) deve essere renderizzata direttamente.
