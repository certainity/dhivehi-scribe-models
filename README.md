# Dhivehi Scribe optional OCR models

Model data downloads for the free Dhivehi Scribe Windows app by SimpleworldApps.

The `models-v1` release contains the same OCR weight bytes distributed with Dhivehi Scribe's first Microsoft Store release. No retraining or weight conversion was performed. Download only the variants you need; the app checks the pinned SHA-256 values before installing and loading them. Recognition happens on your computer. Audio, images and transcripts are not uploaded to this repository.

- v4: Stable
- v6: Vast (the app's default)
- v8: Curated (testing)
- v9: Public mix (testing)

Each ZIP contains only model.safetensors and five JSON configuration/tokenizer files. The release catalog records archive and individual-file sizes and SHA-256 checksums. No application code, training recordings, private correction transcripts or user documents are included.

These are the owner's MVBIGAI Dhivehi TrOCR checkpoints, based on `microsoft/trocr-base-printed`. The upstream Microsoft TrOCR/UniLM license is included in `TrOCR-MIT.txt`. This attribution does not imply endorsement or change the licensing of other project files.

Store: https://apps.microsoft.com/detail/9P51SL3742JJ

Privacy: https://certainity.github.io/ahmedd.github.io/dhivehi-scribe/privacy.html

Support: simpleworld603@gmail.com
