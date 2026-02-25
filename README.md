# PhrasNeoLex  

## A Corpus-Based and Computational Approach to French–Chinese Phraseological Neologisms (2015–2025)

---

## Project Overview

**PhrasNeoLex** is a research project dedicated to the identification, description, and modeling of phraseological neologisms in French and Chinese over the period **2015–2025**.

The project combines:

- Phraseology  
- Lexicography  
- Corpus linguistics  
- Computational methods (NLP)  

Its objective is to detect and structure multi-word units (MWUs) that have:

- Recently emerged  
- Undergone semantic shift  
- Experienced pragmatic evolution  

The project contributes to:

- Multilingual lexical innovation studies  
- Contrastive lexicography (FR–ZH)  
- The ENEOLI network  
- NLP approaches to neology  

---

## Main Objectives

- Identify new or evolving phraseological units (PUs)  
- Compare corpus data with reference dictionaries  
- Detect neological variants and semantic shifts  
- Model data in structured formats (JSON / JSON-LD)  
- Produce a pilot bilingual mini-lexicon (FR–ZH)  
- Develop a reproducible extraction methodology  

---

## Repository Structure



PhrasNeoLex/
│
├── Data/
│ ├── raw_corpus/
│ ├── cleaned_corpus/
│ └── reference_dictionaries/
│
├── Step1_scrapping_corpus.ipynb
├── Step1_corpus_PUs.ipynb
├── Step2_fusion_tokenisation.ipynb
├── Step3_identification_fr.ipynb
├── Step3_identification_chi.ipynb
│
├── phrasemes_FR-ZH.json (pilot dataset – forthcoming)
│
└── README.md





---

## Methodological Pipeline

### 1️ Corpus Construction

- Scraping French and Chinese media (2015–2025)  
- Metadata collection (date, genre, source)  
- Cleaning and normalization  

---

### 2️ Pre-Neological Reference Lists

Extraction of phraseological units from:

- French idiomatic dictionaries  
- Chinese chéngyǔ lexicons  

Establishing exclusion criteria (pre-2015 attested units).

---

### 3️ Candidate Extraction

- N-gram extraction  
- Collocation detection (PMI, t-score)  
- Morphosyntactic pattern extraction  
- Dictionary comparison  

---

### 4️ Neologism Detection

- Frequency diachronic comparison  
- Distributional semantic analysis (BERT embeddings)  
- Manual validation  

---

### 5️ Data Modeling

Annotation of:

- Morphosyntactic structure  
- Formal variation  
- Degree of fixedness  
- Semantic evolution  

Export to:

- JSON  
- JSON-LD  

---

## NLP Tools Used

- Python  
- Regex-based extraction  
- N-gram statistics  
- PMI / t-score  
- BERT (CamemBERT / Chinese BERT)  
- Contextual embedding clustering  
- *(Future)* Streamlit visualization interface  

---

## Deliverable (Pilot Phase)

The pilot dataset (planned output):





It contains approximately **50 phraseological neologisms**, including:

- Linguistic annotation  
- FR–ZH alignment  
- Metadata (date, genre, source)  
- Variants and constructional patterns  

---

## Theoretical Framework

The project draws on:

- Mel’čuk (Lexical Functions & Phrasemes)  
- Boulanger (Neology)  
- Cabré (Terminology & Neologisms)  
- Construction Grammar  
- Corpus-based lexicography  

Phraseological units are treated as:

> Non-free multi-lexeme units with lexical or semantic constraints.

---

## Scientific Context

The project is aligned with:

- IZ CoCoLex – FAU Erlangen–Nürnberg  
- ENEOLI – European Network on Lexical Innovation  
- Multilingual lexicography research initiatives  

---

## Current Status

- ✔ Corpus scraping implemented  
- ✔ Tokenization and fusion pipeline  
- ✔ French & Chinese candidate identification scripts  
- ⏳ Pilot dataset finalization  
- ⏳ JSON-LD modeling  
- ⏳ Streamlit visualization interface  

---

## Future Developments

- Larger-scale corpus expansion  
- Automated neologism detection  
- Integration with ENEOLI platform  
- OWL / RDF modeling (OntoLex-Lemon compatible version)  
- API access to dataset  

---

## Author

**Dr. [Your Name]**  
PhD in Linguistics (2021)  
Computational Lexicography & Phraseology  
Master 2 pluriTAL – INALCO  

**Research interests:**

- Phraseological neology  
- Multilingual lexicography  
- Ontology modeling  
- NLP & corpus linguistics  

---

## License

This project is currently for academic research purposes.  
A specific license will be added upon publication of the dataset.
