# FreakInViz

I visual predefiniti di Power BI sono ottimi per analisi standard, ma spesso mostrare i dati non basta: è necessario farli comunicare in modo efficace.

**FreakInViz** è una raccolta open-source di grafici scritti in **Vega-Lite e Vega**, utilizzabili tramite il visual **Deneb** in Power BI. Il progetto nasce con un obiettivo chiaro: fornire agli sviluppatori Power BI strumenti avanzati per elevare la User Experience e l'impatto visivo dei propri report, superando i limiti dei grafici nativi.

Ogni grafico è flessibile, ottimizzato per le performance e pensato per essere un punto di partenza pronto all'uso, ma completamente personalizzabile.

---

## Grafici disponibili

### Funnel
Ideale per tracciare conversioni, processi di vendita o flussi utente.

- **`classic/`** — Grafico base, centrato con design minimale e tooltip standard.

---

## Come utilizzarli

### In Power BI
1. Apri la cartella del grafico che vuoi usare
2. Copia il contenuto del file `.json`
3. Incollalo nell'editor del visual Deneb in Power BI
4. Per i primi test usa il dataset di esempio in `data/`, poi sostituiscilo con i tuoi campi

### Nell'editor online
Puoi testare e modificare i grafici direttamente nell'editor online di Vega, senza aprire Power BI. È utile per esplorare il codice e capire come funziona prima di portarlo nel report.

---

## Requisiti

- Power BI Desktop
- Custom visual **Deneb** (disponibile gratuitamente su AppSource)
