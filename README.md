# LLM Lab

This project fine‑tunes a small language model (OPT‑350M) on a short transcript extracted from an online video. The transcript file is not included in the repository. The goal was to explore how fine‑tuning affects model behavior, prompt responses, and text generation quality.

## What I Did
- Pulled a transcript using `youtube_transcript_api`
- Converted the transcript into a training text file
- Tokenized and prepared the dataset with HuggingFace `datasets`
- Fine‑tuned `facebook/opt-350m` using the Transformers Trainer API
- Generated new text using the fine‑tuned model

## Key Files
- `notebooks/` — training and generation workflow

## Notes
- The transcript used for training is not included due to copyright.
- The fine‑tuned model and tokenizer are saved locally after training.
