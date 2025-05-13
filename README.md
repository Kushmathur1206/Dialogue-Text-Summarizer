# Dialogue Text Summarizer
This project is an abstractive dialogue summarization system that utilizes PEGASUS, a state-of-the-art transformer model from Google, originally trained on large-scale datasets like CNN/DailyMail, and further fine-tuned on the SAMSum dataset to better handle informal and conversational text formats.

Project Highlights
- Transfer Learning: Leveraged the pretrained PEGASUS model (trained on CNN/DailyMail) and fine-tuned it on the SAMSum dataset to improve summarization performance on multi-turn dialogues.
- Transformers: Utilized the Hugging Face transformers library for easy integration and deployment of large pretrained models.

## Workflow
1. Update config.yaml
2. Update params.yaml
3. Update entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipline
7. Update the main.py
8. Update the app.py
