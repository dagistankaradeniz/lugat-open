# Attributions

Lügat is built on the following openly licensed works. Thank you to all their authors
and contributors.

| Component | Authors | License | Used for |
|---|---|---|---|
| [Wiktionary](https://en.wiktionary.org/) | Wiktionary contributors | [CC BY-SA 4.0](licenses/CC-BY-SA-4.0.txt) | Dictionary entries, senses and translations |
| [Wiktextract](https://github.com/tatuylonen/wiktextract) / [kaikki.org](https://kaikki.org/) | Tatu Ylonen | — (extraction of Wiktionary data) | Machine-readable Wiktionary data |
| [Tatoeba](https://tatoeba.org/) | Tatoeba contributors | [CC BY 2.0 FR](https://creativecommons.org/licenses/by/2.0/fr/) | Example sentences |
| [Zemberek-NLP](https://github.com/ahmetaa/zemberek-nlp) | Ahmet A. Akın, Mehmet D. Akın | [Apache-2.0](licenses/Apache-2.0.txt) | Turkish word-form analysis (used to build the database; not shipped in the app) |
| [Firefox Translations models](https://github.com/mozilla/translations) | Mozilla | [MPL-2.0](licenses/MPL-2.0.txt) | On-device Turkish ↔ English translation models |
| [bergamot-translator](https://github.com/browsermt/bergamot-translator) | The Bergamot Project | [MPL-2.0](licenses/MPL-2.0.txt) | On-device translation engine |
| [Inter](https://rsms.me/inter/) 4.001 | The Inter Project Authors | [SIL OFL 1.1](licenses/Inter-OFL-1.1.txt) | App typeface (unmodified) |

## Text recognition (Android)

The Android app reads text in photos (Scan Text in Translate) with Tesseract; the iOS app uses Apple's
built-in Vision framework instead.

| Component | Version | License |
|---|---|---|
| [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) | 5.5.1 | [Apache-2.0](licenses/Apache-2.0.txt) |
| [Tesseract4Android](https://github.com/adaptech-cz/Tesseract4Android) | 4.9.0 | [Apache-2.0](licenses/Apache-2.0.txt) |
| [tessdata_fast](https://github.com/tesseract-ocr/tessdata_fast) Turkish + English models | commit 8741641 | [Apache-2.0](licenses/Apache-2.0.txt) |
| [Leptonica](https://github.com/DanBloomberg/leptonica) | 1.85.0 | [BSD-2-Clause](licenses/Leptonica-BSD-2-Clause.txt) |
| [libpng](https://github.com/pnggroup/libpng) | 1.6.48 | [PNG Reference Library License v2](licenses/libpng-LICENSE.txt) |
| IJG libjpeg | 9f | [IJG license](licenses/IJG-libjpeg-LEGAL.txt) |

This software is based in part on the work of the Independent JPEG Group.

## Translation engine components

The apps statically link Mozilla's Bergamot inference engine, built **unmodified** (MPL-2.0 files are
not changed) from [mozilla/translations @ 8eada038](https://github.com/mozilla/translations/tree/8eada038fd45bbf6fa58a412b22f80c79887fabc/inference).
That link is the source code form of the MPL-2.0 components we distribute.

| Component | License |
|---|---|
| Bergamot translator | [MPL-2.0](licenses/MPL-2.0.txt) |
| Marian NMT, intgemm, yaml-cpp, spdlog, faiss, phf, cnpy, zstr, mio, sse2neon | MIT |
| ssplit-cpp (code), SentencePiece, ruy, abseil (subset) | [Apache-2.0](licenses/Apache-2.0.txt) |
| cpuinfo, simd_utils, pathie-cpp, darts-clone | BSD-2-Clause |
| CLI11, half_float, protobuf-lite, [PCRE2 10.49](https://github.com/PCRE2Project/pcre2) | BSD-3-Clause |
| zlib | Zlib |

Citation for Wiktextract:
Tatu Ylonen. 2022. *Wiktextract: Wiktionary as Machine-Readable Structured Data.*
In Proceedings of the 13th Language Resources and Evaluation Conference (LREC 2022), pages 1317–1325.

Exact versions, the changes made to each source, and links to the corresponding source code are
listed per release.
