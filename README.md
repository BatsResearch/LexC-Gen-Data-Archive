# LexC-Gen (All Data Artifacts)

## Description

This repository stores all the data artifacts of LexC-Gen for both NusaX and SIB-200 tasks. The data artifacts include:
- raw generated English texts data (`.txt` format in `{task}-lexcgen-raw-data/`)
- raw texts converted to csv (`.csv` format in `{task}-lexcgen-processed-data/`)
- filtered data after input-label consistency filtering (`filtered-*.csv`)
- tokenized English data after filtering (`tokenized_filtered-*.csv`)
- translated to respective low-resource languages (`translated-*.csv`)

The file string name is in the format of: `{model_name}-{task_type}-en-{lang}-ctg-total{size}`. Here are their descriptions:
- `model_name`: LLM used to generate lexicon-conditioned data
- `task_type`: `sa` for sentiment analysis and `tm` for topic classification (`tm` because originally we call it topic modeling)
- `lang`: low-resource language code
- `size`: 1K, 10K, 100K generated data size, which refers to the size of LexC-Gen generated data *before* filtering.
