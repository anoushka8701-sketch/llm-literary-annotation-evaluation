# Data

The full text of Jack Kerouac's *Mexico City Blues* is not distributed
with this repository because it remains under copyright.

To reproduce the annotation workflow, provide a locally obtained CSV named
`mexico_city_blues_choruses.csv` with the following columns:

- `chorus_id`: chorus number stored as text, including `216-A`, `216-B`
  and `216-C`
- `text`: complete text of the corresponding chorus

The project corpus contained 244 rows with no missing or duplicate chorus
identifiers. Line breaks and original punctuation were preserved.

`annotations_labels_only.csv` contains derived model labels and evaluation
metadata without the underlying literary text or raw model responses.

