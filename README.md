quran-texts
===========

This repo contains the Quran texts (originals, translations, transliterations,
commentaries or combinations) that are served by the [quran.al](https://quran.al)
application.

In `texts/` each text has it's own directory named `$LANG_ID.$TEXT_NAME/`.
The `$LANG_ID` is a [bcp47]() compliant code (unless the language has not such code).
The `$TEXT_NAME` usually contains some part of the authors name.
Together these two bits define the unique language identifier.

All language codes should have an entry in the `language-details.csv` file.
Most languages already have an entry in that file.


### Copyrights

All text are owned by their respective owners.
