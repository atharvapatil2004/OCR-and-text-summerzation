# OCR-and-text-summerzation
📝 Ink to Insight: OCR and Text Summarization System
This project uses deep learning-based Optical Character Recognition (OCR) to convert handwritten documents into digital text, followed by both extractive and abstractive summarization to distill the content meaningfully.

🚀 Features
📄 Handwritten OCR

Uses Doctr pretrained model to extract text from handwritten documents.

💾 Text Export

Converts extracted text into a .txt or .docx file for saving and sharing.

✂️ Extractive Summarization & 🧠 Abstractive Summarization

Uses spaCy to identify and retain the most important sentences.

🛠️ Tech Stack
OCR: Doctr (Document Tracing)

Extractive Summary & Abstractive Summary: spaCy

Backend: Python

🧾 How It Works
Upload a high-resolution image of a handwritten document.

OCR Module extracts the raw text using Doctr’s pre-trained model.

Save the output as a .txt or .docx file.

Choose between:

Extractive Summary → Key sentences preserved.

Abstractive Summary → Content rewritten concisely in new words.

View or download the final summary.
