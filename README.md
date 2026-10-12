# Hi, I'm Manel Rahmouni

Machine Learning Engineer, Google Cloud Certified Professional Machine Learning Engineer, currently deepening that foundation through an Applied Master's in Artificial Intelligence and Computer Vision at IU International University.

I'm passionate about turning data into something that creates real value — business or scientific. I work in agile increments: make it work, then make it better, and keep improving through retrospectives rather than chasing a "finished" version before anything ships.

## Featured projects

**[ChronicAI](https://chronic-ai.com)** — an AI-based decision-support system that detects early signs of autoimmune disease (Lupus, rheumatoid arthritis) from lab history, before diagnosis. Designed and built end-to-end: multi-agent backend (LangGraph, FastAPI) on Google Cloud (Vertex AI, BigQuery, Cloud Run, Firestore), a React frontend with full CI/CD, and an ML pipeline comparing logistic regression, decision trees, and gradient boosting. Validated on synthetic data and my own real, fully verified case.

**[ECG Normal/Abnormal Classifier](https://github.com/Manel-Green/ECG_Classifier)** — a ResNet18 fine-tuned in two stages (frozen backbone, then partial unfreezing) on 1,682 photographed 12-lead ECGs, reaching 85.5% accuracy/sensitivity/specificity. Full training notebook included, plus a working upload-and-test demo.

**[RAG Cardiology Assistant](https://github.com/Manel-Green/RAG_Cardiology_Assistant)** — a retrieval-augmented Q&A agent over real cardiology research papers and guidelines, built so every answer traces back to the exact source passage it came from. Document AI OCR → semantic chunking → Vertex AI Vector Search → streaming Gemini generation, with a deterministic code-level gate that refuses to answer when nothing in the corpus is actually relevant, rather than leaving that judgment to the model. React frontend, full CI/CD via Cloud Build.

## Connect

Open to Machine Learning Engineer opportunities — happy to connect on [LinkedIn](https://www.linkedin.com/in/manel-rahmouni-0402a4201/).
