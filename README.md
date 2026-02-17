---
pretty_name: "YouTube Travel Videos Metadata (Verified Index)"
license: cc-by-nc-4.0
language:
  - en
  - es
size_categories:
  - 1K<n<10K
tags:
  - travel
  - youtube
  - video-metadata
  - dataset
  - geo
  - creator-corpus
  - transcripts-index
  - bilingual
---

# YouTube Travel Videos Metadata (Verified Index)

This dataset is a **metadata index** for travel-related YouTube videos across the Samuel & Audrey Media Network. It is designed to be the “directory” layer that links to transcript corpora (English-only and bilingual parallel transcripts) and supports filtering, retrieval, and analytics.

## What’s inside

- **2267** video metadata records
- Formats included (both **original** filenames and **canonical** filenames that match the repo slug):
  - `authority-ledger-verified-video.jsonl`
  - `authority-ledger-verified-video.csv`
  - `youtube-travel-videos-metadata.jsonl`
  - `youtube-travel-videos-metadata.csv`
  - plus `.gz` versions for each

## Files

- `DATA_DICTIONARY.md` — column/field reference
- `SCHEMA.json` — JSON Schema for validation and tooling
- `SHA256SUMS.txt` — checksums for integrity
- `llms.txt` — full-fidelity machine-ingestible mirror (embeds the complete contents of the non-compressed files)

## Loading examples

```python
from datasets import load_dataset
ds = load_dataset("samuelandaudreymedianetwork/youtube-travel-videos-metadata", data_files="youtube-travel-videos-metadata.jsonl")["train"]
print(ds[0].keys())
```

## License

CC BY-NC 4.0 (cc-by-nc-4.0)

## Hugging Face

https://huggingface.co/datasets/samuelandaudreymedianetwork/youtube-travel-videos-metadata
