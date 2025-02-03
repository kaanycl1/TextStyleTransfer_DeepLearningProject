# Text Style Transfer Between Barack Obama and Donald Trump

This project explores text style transfer between the distinct rhetorical styles of Barack Obama and Donald Trump. Using **VT-STOWER**, a model that leverages **variational autoencoders (VAEs), style embeddings, and attention mechanisms**, we aim to transform text while preserving its original content. Additionally, we implement an **autoencoder model with transformer blocks** and a **style classifier at the latent space level** to enhance performance.

## 📌 Project Overview
- **Objective**: Transfer text between the speaking styles of Barack Obama and Donald Trump.
- **Approach**:
  - VT-STOWER (style embeddings, VAEs, pivot words)
  - Transformer-based autoencoder with a latent-space style classifier
- **Challenges**:
  - Capturing stylistic nuances across complex, real-world speeches
  - Preserving content while ensuring effective style transformation

## 📂 Dataset
- Speeches from **Barack Obama** and **Donald Trump** were collected from the **Miller Center** using web scraping (`BeautifulSoup`).
- More details on dataset preprocessing are provided in the report.
