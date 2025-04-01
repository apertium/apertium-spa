[In English](README.md)

# Corpus para el entrenamiento del tagger

Esta carpeta contiene los corpus necesarios para entrenar el tagger estadístico. Están agrupados en dos carpetas, `tagged` y `crp`.

## tagged

Corpus para el [entrenamiento supervisado](https://wiki.apertium.org/wiki/Supervised_tagger_training). Los archivos deben tener la extensión `.tagged` y en cada línea debe haber una unidad léxica de Apertium desambiguada, en [formato de flujo de Apertium](https://wiki.apertium.org/wiki/Apertium_stream_format). Por ejemplo:

```
^Un/Uno<det><ind><m><sg>$
^centenar/centenar<n><m><sg>$
^de/de<pr>$
^familias/familia<n><f><pl>$
^reclaman/reclamar<vblex><pri><p3><pl>$
^indemnizaciones/indemnización<n><f><pl>$
^./.<sent>$
```

Antes del entrenamiento, los archivos de la carpeta se combinan en el archivo `spa.tagged`.

## crp

Corpus para el [entrenamiento no supervisado](https://wiki.apertium.org/wiki/Unsupervised_tagger_training). Los archivos deben tener la extensión `.txt` y deben contener texto **sin formato**.

Antes del entrenamiento, los archivos de la carpeta se combinan en el archivo `spa.crp.txt`.
