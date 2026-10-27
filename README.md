# 🛡️ Expert Assur'IA - Analyseur de Contrat Intelligent

Expert Assur'IA est une application Web de **RAG (Retrieval-Augmented Generation)** qui permet d'interroger un contrat d'assurance (PDF) en langage naturel. L'outil combine la puissance de **Haystack** pour la recherche documentaire et de **Groq (Llama 3.3)** pour générer des explications simplifiées.

## 🚀 Fonctionnalités
- **Lecture Intelligente** : Extraction du texte et des tableaux complexes via `Docling`.
- **Analyse Précise** : Identification du paragraphe exact et du numéro de page correspondant.
- **Vulgarisation IA** : Transformation du jargon juridique en explications claires pour l'assuré.
- **Interface Duale** : Affichage côte à côte de l'avis de l'expert et de la preuve contractuelle.



## 🛠️ Stack Technique
- **Backend** : Python, Flask
- **Extraction PDF** : Docling (IBM)
- **Orchestration RAG** : Haystack (Deepset)
- **LLM (IA)** : Groq API (Llama-3.3-70b-versatile)
- **Frontend** : HTML5, CSS3 (Design Premium)

## 📦 Installation

1. **Cloner le dépôt** :
   ```bash
   git clone https://github.com/benji705/expert-assuria.git
   cd expert-assuria
   ```

2. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   ```

3. **Configurer la clé Groq** :
   ```bash
   export GROQ_API_KEY="votre_clé"
   ```

4. **Lancer l'application** :
   ```bash
   python app.py
   ```
   Puis ouvrir http://localhost:5000
