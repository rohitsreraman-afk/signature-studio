# Data licenses and attribution

This file identifies third-party data used by Signature Studio. It does not change ownership or licensing of the app code.

## Wiktionary-derived name meanings and etymologies

The lookup in name-meanings.js is a normalized, abbreviated adaptation of the Wiktionary-derived data/meanings.json catalogue maintained by [Baby Name Maker / Lullabyte](https://github.com/suhxnitiwari/baby-name-maker/blob/main/docs/name-sources.md). It contains 5,517 normalized name keys: 4,263 with a recorded meaning and 1,254 with an etymology but no meaning after spelling normalization. Source records are attributed to Wiktionary contributors and the per-name panel links to a relevant Wiktionary entry where available.

Wiktionary text is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). This adapted meaning and etymology data is made available under the same license. Source descriptions and limitations are documented by the dataset maintainer at the linked source notes.

## WIPO name spelling reference

wipo-name-presence.bloom.gz is a compact approximate spelling index derived from the name column of WIPO’s World Gender Name Dictionary 2.0, 2021, [Harvard Dataverse DOI 10.7910/DVN/MSEGSJ](https://doi.org/10.7910/DVN/MSEGSJ), licensed [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). The source file contains 3,491,141 names after conflict filtering. The app uses only normalized spellings; it does not use gender fields or treat the dataset as a population count. The Bloom filter has an approximate 0.1% false-positive rate, so matches are described as possible matches.

## Global frequency estimate

The frequency-based uniqueness estimate uses [Onomaverse Names Datasets v2026.10](https://onomaverse.com/datasets), licensed CC BY 4.0. Attribution: “Names data from Onomaverse (https://onomaverse.com/datasets), licensed CC BY 4.0.” Its country shares are weighted equally by the app and are not population counts.