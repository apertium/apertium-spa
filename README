Spanish (`apertium-spa`)
===============================================================================

This is an Apertium monolingual language package for Spanish. What
you can use this language package for:

* Morphological analysis of Spanish
* Morphological generation of Spanish
* Part-of-speech tagging of Spanish

Requirements
===============================================================================

You will need the following software installed:

* lttoolbox (>= 3.3.0)
* apertium (>= 3.3.0)
* vislcg3 (>= 0.9.9.10297)

If this does not make any sense, we recommend you look at: www.apertium.org

Compiling
===============================================================================

Given the requirements being installed, you should be able to just run:

```
$ ./configure
$ make
```

You can use `./autogen.sh` instead of `./configure` if you're compiling
from GitHub.

If you're doing development, you don't have to install the data, you
can use it directly from this directory.

If you are installing this language package as a prerequisite for an
Apertium translation pair, then do (typically as root / with sudo):

```
# make install
```

You can give a `--prefix` to `./configure` to install as a non-root user,
but make sure to use the same prefix when installing the translation
pair and any other language packages.

Testing
===============================================================================

If you are in the source directory after running make, the following
commands should work:

```
$ echo "Voy a la playa" | apertium -d . spa-morph
^Voy/ir<vblex><pri><p1><sg>$ ^a/a<pr>$ ^la/el<det><def><f><sg>/lo<prn><pro><p3><f><sg>$ 
^playa/playa<n><f><sg>$^./.<sent>$

```

```
$ echo "Voy a la playa" | apertium -d . spa-tagger
^ir<vblex><pri><p1><sg>$ ^a<pr>$ ^el<det><def><f><sg>$ ^playa<n><f><sg>$^.<sent>$
```

Files and data
===============================================================================

* `apertium-spa.spa.dix`            - Monolingual dictionary
* `spa.prob`                        - Tagger model
* `apertium-spa.spa.rlx`            - Constraint Grammar disambiguation rules
* `apertium-spa.post-spa.dix`       - Post-generator
* `modes.xml`                       - Translation modes

For more information
===============================================================================

* http://wiki.apertium.org/wiki/Installation
* http://wiki.apertium.org/wiki/apertium-spa
* http://wiki.apertium.org/wiki/Using_an_lttoolbox_dictionary

Help and support
===============================================================================

If you need help using this language pair or data, you can contact:

* Mailing list: apertium-stuff@lists.sourceforge.net
* IRC: `#apertium` on `irc.freenode.net`

See also the file AUTHORS included in this distribution.

