# Topic Modeling of Taylor Swift's Lyrics Using SVD and NMF

**Course:** APPM 3310 — Matrix Methods  
**Dataset:** Taylor Swift Lyrics (custom CSV feature set)  
**Techniques:** Singular Value Decomposition (SVD), Non-Negative Matrix Factorization (NMF)

---

## Overview
This project explored the use of **linear algebra techniques** for topic modeling in natural language processing. We analyzed **Taylor Swift’s lyrics** using **Singular Value Decomposition (SVD)** and **Non-Negative Matrix Factorization (NMF)** to uncover latent structures and themes in her songs.

The work involved both **theoretical derivations** and **practical implementations** in Python. Our final deliverable included a written report, CSV dataset, and Jupyter notebooks.

---

## Repository Contents
.
├── FinalProject.pdf # full project report
├── TaylorSwiftLyricsFeatureSet.csv# Preprocessed lyric dataset
├── taylorSVD.ipynb # jupyter notebook applying SVD
├── taylorNMF.ipynb # jupyter notebook applying NMF
└── README.md

---

## Methods
- **Preprocessing**  
  - Lyrics were collected and transformed into a document-term matrix.  
  - Stop words removed; TF-IDF applied for weighting.  

- **Singular Value Decomposition (SVD)**  
  - Reduced high-dimensional term space into latent semantic dimensions.  
  - Compared cosine similarity between songs in reduced topic space.  

- **Non-Negative Matrix Factorization (NMF)**  
  - Factorized the document-term matrix into additive, interpretable topic components.  
  - Extracted the top words per topic to characterize lyrical themes.  

---

## Results
- **SVD** captured broad latent structures but produced abstract, less interpretable components.  
- **NMF** generated more intuitive topics, grouping songs by recurring themes such as:  
  - ❤️ Love and heartbreak  
  - 🌆 Nostalgia and growing up  
  - 🌟 Fame and self-reflection  

- Cosine similarity revealed clusters of songs aligned with different **albums/eras**, reflecting lyrical shifts over time.

For complete details, see the [Final Report](FinalProject.pdf).

---

## Tools & Libraries
- [Python](https://www.python.org/)  
- [pandas](https://pandas.pydata.org/)  
- [numpy](https://numpy.org/)  
- [scikit-learn](https://scikit-learn.org/)  
- [matplotlib](https://matplotlib.org/)  
- [Jupyter](https://jupyter.org/)  

---

## How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/taylorswift-topic-modeling.git
   cd taylorswift-topic-modeling
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebooks:
   ```bash
   jupyter notebook taylorSVD.ipynb
   jupyter notebook taylorNMF.ipynb
   ```

## Lessons Learned
* Gained hands-on experience with linear algebra techniques for text data.
* Understood tradeoffs between SVD (efficient, less interpretable) and NMF (more interpretable, additive topics).
* Integrated math theory, Python implementation, and visualization into one project.

## Acknowledgments
* University of Colorado Boulder — APPM 3310 (Matrix Methods)
* Lyrics dataset collected and preprocessed for educational use only.

