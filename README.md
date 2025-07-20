📚 Automatic Essay Scoring System using RoBERTa
This repository presents an Automatic Essay Scoring (AES) system built on the RoBERTa language model. Designed to evaluate essays with near-human consistency, our system achieved a Cohen’s Kappa score of 0.51, indicating a reasonable level of agreement with expert human raters. A live demo is included as part of the project presentation.

📂 Repository Contents
README.md – Project documentation

demo/AES_Demo.pptx – PowerPoint presentation with embedded demo video

data/ – Directory for dataset (user-provided)

Code files and training notebooks

📊 Dataset
We used the official dataset from the
Kaggle: Learning Agency Lab - Automated Essay Scoring 2 competition.

📌 Note: You must accept the competition rules on Kaggle to download and use the dataset.

Once downloaded, place the data files inside the data/ folder following the expected structure provided in the codebase.

🧪 Model Performance
Model: RoBERTa (fine-tuned using Hugging Face Transformers)

Scoring Metric: Quadratic Weighted Kappa (QWK)

Achieved Score: 0.51

This score demonstrates a moderate level of alignment between the model’s predictions and human annotations.

Detailed results and visualizations are included in the Jupyter notebooks.

🎬 Demo
A live demonstration video is included within the presentation file:

File: demo/AES_Demo.pptx

Shows model prediction flow, sample outputs, and UI interaction

🤝 Contributing
We welcome your contributions to improve the AES system!
To contribute:

Fork this repository

Create a new feature branch

Submit a pull request with a description of your changes

🧾 Requirements
The project uses the following core technologies:

Python (with Flask for backend)

PyTorch and Hugging Face Transformers

Pandas, TQDM, and other standard libraries

Details can be found in requirements.txt.

🙏 Acknowledgments
Hugging Face Transformers – for providing the pre-trained RoBERTa model

Kaggle Learning Agency Lab – for hosting the AES2 dataset and competition

The open-source community – for ongoing support and development inspiration

👩‍💻 Project By
Chaithra Lokasara Mahadevaswamy
LinkedIn Profile
🧠 AI Enthusiast | 📊 Data Alchemist | 🎓 Graduate Researcher
🚀 Innovation Seeker | 🌟 AI Tools Research Intern @ Unicorn Tutor AI
"Building Tomorrow with Intelligence Today"

