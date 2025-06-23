# Home_Assignment_4


CS5720 Neural Networks and Deep Learning - Home Assignment 4

Student Name: Nithish Reddy


Student ID: 700764837


Course: CS5720 Neural Networks and Deep Learning


Semester: Summer 2025

---

Assignment Overview

This assignment covers key concepts from Chapters 11 and 12 of the course, focusing on GAN architectures, AI ethics, basic GAN implementation, data poisoning simulation, and fairness tools in machine learning.

---

Task Summary

1. GAN Architecture
- Discussed the adversarial nature of GANs and how generator and discriminator improve through competition.
- Included a diagram of the GAN structure, showing input noise to the generator and real/fake images evaluated by the discriminator.

2. Ethics and AI Harm
- Topic: Misinformation in generative AI
- Described a scenario of AI-generated fake news.
- Suggested harm mitigation strategies:
  - Implement model usage transparency.
  - Use fact-checking datasets and feedback loops during training.

3. Programming Task: Basic GAN Implementation
- Implemented a simple GAN using PyTorch to generate MNIST digits.
- Included:
  - Generator and Discriminator model architectures.
  - Training loop with alternating updates.
  - Sample output images at epochs 0, 50, and 100.
  - Loss plots for Generator and Discriminator.

4. Programming Task: Data Poisoning Simulation
- Built a basic sentiment classifier (e.g., movie reviews).
- Simulated poisoning by flipping labels for reviews mentioning a specific entity.
- Plotted:
  - Accuracy and confusion matrix before and after attack.
  - Visualization showing drop in model performance due to poisoning.

5. Legal and Ethical Implications of GenAI
- Discussed risks of:
  - Memorizing private data (e.g., names in GPT-2).
  - Reproducing copyrighted text.
- Opinion: Generative models should restrict access to sensitive and copyrighted data during training.

6. Bias & Fairness Tools
- Used Aequitas Bias Audit Tool.
- Metric chosen: False Negative Rate Parity
- Explained:
  - It measures whether different groups have equal rates of false negatives.
  - Important to avoid under-identifying outcomes for minority groups.
  - Example failure case: healthcare model that under-diagnoses certain populations.

---

How to Run the Code

1. Clone the repository:
   git clone https://github.com/yourusername/CS5720-Assignment4.git
   cd CS5720-Assignment4

2. Install dependencies:
   pip install -r requirements.txt

3. To run the GAN:
   python gan_mnist.py

4. To simulate data poisoning:
   python sentiment_poisoning.py

---

Deliverables

- Source Code (GAN and Sentiment Classifier)
- Sample Images and Loss Graphs
- Accuracy/Confusion Matrix Before/After Poisoning
- Completed README
- 2-3 Minute Demo Video

---

Notes

- All code is commented for clarity.
- Please contact me for any questions regarding implementation.
