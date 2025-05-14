# Dialogue Text Summarizer

This project implements an abstractive dialogue summarization system using PEGASUS, a cutting-edge transformer model developed by Google. Originally pretrained on large-scale datasets such as CNN/DailyMail for news summarization, PEGASUS was further fine-tuned on the SAMSum dataset—a dataset tailored for informal, multi-turn conversations—to better adapt it for summarizing real-world dialogues.

🔍 Project Highlights
- Transfer Learning for Conversational Texts
Adapted the PEGASUS model via fine-tuning on the SAMSum dataset, significantly enhancing its ability to summarize informal, chat-style conversations.

- Hugging Face Transformers Integration
Employed the Hugging Face transformers library for streamlined access to PEGASUS and simplified model training, inference, and deployment workflows.

- Abstractive Summarization
Unlike extractive methods that pull sentences verbatim, this model generates new, coherent summaries that capture the intent and context of the original conversation.

🛠️ Tech Stack
- Python
- Hugging Face Transformers
- PEGASUS
- SAMSum Dataset


💡 Use Cases
- Customer Support Logs
  Automatically generate concise summaries of long chat transcripts between customers and support agents to help supervisors monitor and improve service quality.
- Meeting Assistants
  Convert transcribed team conversations into brief meeting minutes, improving productivity and documentation.
- Messaging App Integrations
  Summarize WhatsApp or Slack group chats to help users quickly catch up on missed conversations.
- CRM/Helpdesk Tools
  Integrate summarization into CRMs to help sales and support teams quickly review client communications.
- Call Center Transcripts
  Summarize long phone call transcripts for call center analytics and reporting.

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
