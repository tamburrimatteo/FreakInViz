# Funnel Classic

Grafico funnel centrato, scritto in Vega per Deneb. Ogni stage mostra il valore assoluto, il tasso di
conversione rispetto allo stage precedente e la percentuale sul vertice del funnel.

![Funnel Classic](preview.png)

## Come si usa

Copia il contenuto di `classic.json` nell'editor di Deneb. Come sorgente dati carica
`data/classic-sample.csv` nel report e mappa i due campi che il grafico si aspetta: `Step`, l'etichetta
dello stage, e `Value`, il valore da rappresentare.

Non serve un campo per l'ordinamento. Gli stage vengono disposti automaticamente dal valore più alto
al più basso, quindi la larghezza di ogni fascia resta sempre coerente con la forma del funnel.

Quando il grafico funziona con i dati di esempio, sostituiscili con i tuoi mantenendo gli stessi nomi
di campo. Se preferisci usare i nomi del tuo modello, cambia i riferimenti a `Step` e `Value` dentro
la spec.

---

# Funnel Classic

A centred funnel chart, written in Vega for Deneb. Each stage shows its absolute value, the conversion
rate from the previous stage and the percentage against the top of the funnel.

## How to use it

Copy the contents of `classic.json` into the Deneb editor. Load `data/classic-sample.csv` as a data
source in your report and map the two fields the chart expects: `Step`, the stage label, and `Value`,
the figure to plot.

You don't need a field for sorting. Stages are ordered automatically from the highest value to the
lowest, so the width of each band always matches the shape of the funnel.

Once it works with the sample data, replace it with your own, keeping the same field names. If you'd
rather use the names from your model, change the references to `Step` and `Value` inside the spec.

---

Matteo Tamburri
