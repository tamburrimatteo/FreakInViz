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

Ogni cartella contiene il codice del grafico, un dataset di esempio e un'anteprima. Nel README trovi
i campi da mappare e le note specifiche di quel grafico.

1. Apri la cartella del grafico che vuoi usare
2. Copia il contenuto del file `.json` che trovi dentro
3. Incollalo nell'editor del visual Deneb in Power BI
4. Per i primi test carica il CSV di esempio dalla cartella `data/`, poi sostituiscilo con i tuoi campi

Se prima di aprire Power BI vuoi vedere il grafico in funzione e metterci le mani, ogni scheda del
sito ha un pulsante che lo apre direttamente nell'editor online di Vega, già pronto con i suoi dati.

---

## Requisiti

- Power BI Desktop
- Custom visual **Deneb** (disponibile gratuitamente su AppSource)

---

# FreakInViz

Power BI's built-in visuals are great for standard analysis, but showing the data is often not enough: it has to communicate effectively.

**FreakInViz** is an open-source collection of charts written in **Vega-Lite and Vega**, ready to use through the **Deneb** visual in Power BI. The goal is a simple one: give Power BI developers the tools to raise the user experience and the visual impact of their reports, going past the limits of the native charts.

Every chart is flexible, tuned for performance and meant as a starting point that works out of the box and can be reshaped as you like.

---

## Available charts

### Funnel
Well suited to conversion tracking, sales processes and user flows.

- **`classic/`** — The base chart, centred, with a minimal design and standard tooltips.

---

## How to use them

Each folder holds the chart code, a sample dataset and a preview. Its README lists the fields to map
and anything specific to that chart.

1. Open the folder of the chart you want
2. Copy the contents of the `.json` file inside
3. Paste it into the Deneb editor in Power BI
4. For your first test load the sample CSV from the `data/` folder, then swap in your own fields

If you'd like to see a chart running and play with it before opening Power BI, every page on the site
has a button that opens it straight in the online Vega editor, already loaded with its data.

---

## Requirements

- Power BI Desktop
- The **Deneb** custom visual (free on AppSource)

---

Matteo Tamburri
