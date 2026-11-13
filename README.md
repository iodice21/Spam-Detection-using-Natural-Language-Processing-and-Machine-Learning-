# Spam-Detection-using-Natural-Language-Processing-and-Machine-Learning-
Pipeline di Machine Learning in Python per il rilevamento dello spam tramite NLP e vettorizzazione TF-IDF. Confronto tra Naive Bayes, SVM e Random Forest, con analisi della matrice di confusione e test in tempo reale.

# Spam-Detection-NLP / Rilevamento Spam con NLP

[English Version](#english-version) | [Versione Italiana](#versione-italiana)

---

<a name="english-version"></a>
## English Version

# Spam Detection using Natural Language Processing and Machine Learning

Official repository for the Spam Classification and Text Mining project in Python.

## Project Overview
This project focuses on the development of a machine learning pipeline to classify messages as legitimate (ham) or spam. By implementing a robust Natural Language Processing (NLP) preprocessing workflow, including noise removal, stop-word elimination, and TF-IDF vectorization, three distinct classifiers were trained and compared: Naive Bayes, Support Vector Machines (SVM), and Random Forest.

## Methodology and Models
1. **Preprocessing and TF-IDF:** Text cleaning removes punctuation and stop-words using NLTK, followed by term weighting via TfidfVectorizer to highlight predictive keywords.
2. **Classifier Evaluation:**
   - **Naive Bayes:** Serves as the probabilistic baseline model.
   - **Support Vector Machine (SVM):** Employs a linear kernel, achieving superior performance with high accuracy and minimal false positives.
   - **Random Forest:** Ensemble method evaluating non-linear tree-based pattern recognition on sparse matrices.

## Main Results
* **Performance Leaderboard:** SVM achieved the highest overall accuracy (98.16%), outperforming Random Forest (96.71%) and Naive Bayes (96.03%).
* **Real-world Viability:** The confusion matrix analysis confirms a negligible number of false positives, making the model highly reliable for practical anti-spam deployment.


<a name="versione-italiana"></a>
#Versione Italiana
# Rilevamento Spam tramite Elaborazione del Linguaggio Naturale e Machine Learning

Repository ufficiale per il progetto di Classificazione dello Spam e Text Mining in Python.

## Panoramica del Progetto
Questo progetto descrive lo sviluppo di una pipeline di machine learning per classificare i messaggi in legittimi (ham) o spam. Implementando un robusto flusso di preprocessing di Natural Language Processing (NLP), che include rimozione del rumore, eliminazione delle stop-word e vettorizzazione TF-IDF, sono stati addestrati e confrontati tre diversi classificatori: Naive Bayes, Support Vector Machines (SVM) e Random Forest.

## Metodologia e Modelli
1. **Preprocessing e TF-IDF:** La pulizia del testo rimuove punteggiatura e stop-word tramite NLTK, seguita dalla ponderazione dei termini con TfidfVectorizer per evidenziare le parole chiave predittive.
2. **Valutazione dei Classificatori:**
   - **Naive Bayes:** Utilizzato come modello probabilistico di base (baseline).
   - **Support Vector Machine (SVM):** Sfrutta un kernel lineare, ottenendo prestazioni superiori con un'elevata accuratezza e falsi positivi minimi.
   - **Random Forest:** Metodo d'ensemble basato su alberi per valutare il riconoscimento di pattern non lineari su matrici sparse.

## Risultati Principali
* **Classifica delle Prestazioni:** L'SVM ha raggiunto la massima accuratezza complessiva (98.16%), superando Random Forest (96.71%) e Naive Bayes (96.03%).
* **Affidabilità Pratica:** L'analisi della matrice di confusione conferma un numero trascurabile di falsi positivi, rendendo il modello altamente affidabile per l'implementazione reale in filtri anti-spam.


## Repository Structure
```text
├── docs/                # Technical project report (PDF)
├── data/                # Dataset file (spam.csv)
├── scripts/             # Python ML pipeline script (spam_detection.py)
└── README.md            # Project documentation
