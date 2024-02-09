# Projekt: Textanalyse und Themenextraktion

Dieses Projekt verwendet Latent Dirichlet Allocation (LDA), Latent Semantic Analysis (LSA) mit Bag-of-Words (BoW) und Term Frequency-Inverse Document Frequency (TF-IDF) sowie Word2Vec zur Extraktion von Themen aus einer Textsammlung.  

## Dateien:
* **nlp_themenextraktion.ipynb**: Jupyter Notebook mit dem Code für die Textanalyse und Themenextraktion
* **nlp_themenextraktion_P2.ipynb**: Jupyter Notebook mit dem Code für die Textanalyse und Themenextraktion ohne Word Embeddings
* **requirements.txt**: TXT-Datei mit den erforderlichen Abhängigkeiten
* **meldungen.json**: JSON-Datei mit den Textdaten für die Themenextraktion

## Verwendung:
1. Klone das Repository auf deinen lokalen Rechner. `git clone https://github.com/laurafranz/NLP-Techniken-in-Python-`
2. Installiere die Abhängigkeiten.
   `pip install -r requirements.txt`
3. Öffne das Jupyter Notebook **nlp_themenextraktion.ipynb**.
4. Führe die Zellen im Notebook nacheinander aus, um die Themenextraktion mit LDA, LSA (BoW und TF-IDF), und Word2Vec durchzuführen.
5. Analysiere die Ergebnisse und extrahiere dominante Themen aus der bereitgestellten Textsammlung (**meldungen.json**).

## Inhalt von **nlp_themenextraktion.ipynb**:
1. Datenvorbereitung: Lade die Textdaten und bereite sie vor.
2. LDA-Modell: Trainiere ein LDA-Modell mit BoW und TF-IDF.
3. LSA-Modell: Trainiere ein LSA-Modell mit BoW und TF-IDF.
4. Vergleiche die Modelle und extrahiere Themen.
5. Word2Vec: Trainiere Word Embeddings mit Word2Vec.
6. Visualisiere die Themen für eine bessere Interpretierbarkeit.

## Hinweise:
* Passe den Dateipfad für die Textdaten entsprechend deiner Daten an.
* Passe bei Bedarf die Parameter der Modelle an, um optimale Ergebnisse für deine Textsammlung zu erzielen.
* Berücksichtige die Sprache der Textdaten, um die Textdaten in geeigneter Weise vorzuverarbeiten.  
