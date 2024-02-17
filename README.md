# LexC-Gen (All Data Artifacts)

## Description

This repository stores all the data artifacts of LexC-Gen for both NusaX and SIB-200 tasks. The data artifacts include:
- raw generated English texts data (`.txt` format in `{task}-lexcgen-raw-data/`)
- raw texts converted to csv (`.csv` format in `{task}-lexcgen-processed-data/`)
- filtered data after input-label consistency filtering (`filtered-*.csv`)
- tokenized English data after filtering (`tokenized_filtered-*.csv`)
- translated to respective low-resource languages (`translated-*.csv`)

The file string name is in the format of: `{model_name}-{task_type}-en-{lang}-ctg-total{generated_data_size}`
