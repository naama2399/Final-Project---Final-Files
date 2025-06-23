### 📱 Utilizing a Voice Assistant to Aid Older Adults Using Smartphones ###

📝 ** Project Overview **

This repository contains all materials and code for our research project aiming to improve smartphone accessibility for older adults via enhanced voice-assistant interactions. We fine-tune and evaluate Hebrew-language models (AlephBERT, AlephBERT‑Gimel, HeBERT) to recognize and reformulate imprecise commands into Siri-compatible intents, validated through real-world user experiments.

🚀 Experiment Workflow

🧹 Data Cleaning & Augmentation: Remove duplicates, balance intents, translate SLURP.

🏗️ Index Building: Extract entities (dates, names, places) via NER indices.

⚙️ Fine-Tuning: Train three models (AlephBERT, AlephBERT‑Gimel, HeBERT) on the combined Hebrew dataset.

🔄 Cross-Validation: 5‑fold CV with grid search (batch size, learning rate) to log best runs.

✅ Final Evaluation: Test best model on elderly and young user commands; compare against Siri.

✏️ Command Rephrasing: Apply templates to convert raw inputs into Siri‑compatible phrasing.

📊 Evaluation

📈 Metrics: Accuracy, Precision, Recall, Macro‑F1, Response Time.

🤖 Comparison: Compare model predictions vs. Siri’s native intent detection.

📊 Reproduce: Use Evaluation.ipynb to reproduce plots and tables (confusion matrices, success rates).

📞 Contact

📧 Naama Maimon — naamamai@post.bgu.ac.il

📧 Stav Barak — barakst@post.bgu.ac.il

📧 Coral Yagud — yagudcor@post.bgu.ac.il

Advisors: Prof. Mark Last, Dr. Meirav Taieb-Maimon
Seminar Instructor: Prof. Noa Dagan
Based on research thesis by Shai Sitri

