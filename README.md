This project builds a pipeline to ingest, preprocess, and extract entities from Amharic e-commerce messages on Telegram to support fine-tuning a Named Entity Recognition (NER) model.

🔹 Workflow:
Scrape messages (text + media) from ≥5 Ethiopian Telegram e-commerce channels using Telethon.

Preprocess Amharic text (normalization, tokenization, metadata separation).

Label entities (Product, Price, Location, optional: Delivery_Fee, Contact_Info).

Fine-tune transformer models (e.g., XLM-R, mBERT) on labeled data.

Evaluate using F1-score, precision, recall.

Interpret predictions with SHAP/LIME for model trust and selection.

🔹 Output:
Structured, machine-readable data (JSON/CSV) for integration into EthioMart's centralized platform.