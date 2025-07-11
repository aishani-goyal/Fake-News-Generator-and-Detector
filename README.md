# 🧠 AI-Powered Fake News Generator & Detector

The project builds an AI system that generates fake news headlines using GPT-2 and detects them using a text classification model like BERT. It demonstrates both the power and ethical responsibility of generative AI in combating misinformation.

---

## 🚀 Features

- 🎯 **Fake News Generator**  
  Generate synthetic news headlines by specifying:
  - A news category (e.g., Politics, Technology, Sports)
  - A subject or entity (e.g., Apple, Government, Bitcoin)
  - The number of headlines to generate

- 🔍 **Fake News Detector**  
  Input a news snippet to check whether it is likely to be **fake or real**, using a **fine-tuned BERT model** trained on labeled fake/real news datasets.

---

## 🛠️ Technologies Used

- **Frontend:** Gradio (for user interface)
- **Backend:** Python
- **Machine Learning Models:**  
  - Headline Generation: GPT-based text generation  
  - News Classification: Fine-tuned BERT model
- **Key Libraries:**  
  - `transformers`  
  - `scikit-learn`  
  - `pandas`  
  - `gradio`  
  - `torch`

---

## 🎓 Purpose & Learning Goals

- Demonstrate the dual use of AI in generating and detecting fake news
- Encourage critical analysis of digital content
- Showcase real-world use of NLP techniques in misinformation detection
