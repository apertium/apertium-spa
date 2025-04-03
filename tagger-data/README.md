[En castellano](README_spa.md)

# Corpora for tagger training

This folder contains the corpora required to train the statistical tagger. They are grouped in two folders, `tagged` and `crp`.

## tagged

Corpora for [supervised training](https://wiki.apertium.org/wiki/Supervised_tagger_training). Files must have the extension `.tagged` and each line must contain a disambiguated Apertium lexical unit, in [Apertium stream format](https://wiki.apertium.org/wiki/Apertium_stream_format). For example:

```
^Un/Uno<det><ind><m><sg>$
^centenar/centenar<n><m><sg>$
^de/de<pr>$
^familias/familia<n><f><pl>$
^reclaman/reclamar<vblex><pri><p3><pl>$
^indemnizaciones/indemnización<n><f><pl>$
^./.<sent>$
```

Before training, files from the folder are merged into a file named `spa.tagged`.

## crp

Corpora for [unsupervised training](https://wiki.apertium.org/wiki/Unsupervised_tagger_training). Files must have the extension `.txt` and contain **plain (raw)** text.

Before training, files from the folder are merged into a file named `spa.crp.txt`.
