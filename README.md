# Milestone1_KnowledgeMap


# 🌐 Mini Knowledge Graph Builder  

### 📘 Overview  
The **Mini Knowledge Graph Builder** is a small-scale version of the AI-KnowMap project developed as part of my **Infosys Springboard Internship (Milestone 1)**.  
This project focuses on extracting meaningful information from unstructured text and visually representing how entities are connected through relationships.  

It covers the core concepts of:  
- Text Preprocessing  
- Named Entity Recognition (NER)  
- Relation Extraction  
- Graph Construction and Visualization  

---

### 🧠 Objective  
The objective of this project is to build a mini knowledge graph system that can:  
1. Load and process a text dataset  
2. Extract key entities and their relationships  
3. Represent the extracted knowledge as subject–relation–object triples  
4. Visualize these connections as an interactive knowledge graph  

---

### 🗂️ Dataset Description  
The project uses the **cross_domain_article.csv** dataset containing articles from multiple domains such as science, technology, health, and culture.  
After preprocessing (tokenization, stop word removal, stemming, and lemmatization), entities and relationships were extracted and stored in `tripless.csv`.  
This file was then used to build the knowledge graph using **NetworkX** and **PyVis** libraries.  

---

### 🧩 Methodology  
1. **Text Preprocessing:**  
   Tokenization, stop-word removal, stemming, and lemmatization to clean and normalize the text.  
2. **Entity Extraction:**  
   Used spaCy’s NER model to identify people, organizations, locations, and key terms.  
3. **Relation Extraction:**  
   Extracted relations between entities to form meaningful triples (Subject → Relation → Object).  
4. **Graph Building:**  
   Constructed a directed graph using **NetworkX**.  
5. **Visualization:**  
   Created an interactive graph using **PyVis** to explore relationships visually.  

---

### 📊 Knowledge Graph Outputs  
- **Graph 1:** Generated using `tripless.csv`, which appears dense due to a large number of entities and connections.  
- **Graph 2:** Generated using sample data directly in the code for a clearer understanding of entity relationships.  

---

### ⚙️ Technologies Used  
- **Python**  
- **spaCy** (for NLP and NER)  
- **pandas** (for data handling)  
- **NetworkX** (for graph creation)  
- **PyVis** (for interactive visualization)
