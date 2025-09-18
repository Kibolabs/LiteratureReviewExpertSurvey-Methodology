# LiteratureReviewExpertSurvey-Methodology
# 🎮 Educational Games SLR: Mapping Learning Elements to Game Mechanics

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Research Repo](https://img.shields.io/badge/Research-Open%20Data-green.svg)](#)

This repository hosts the data and methodology for the study:

> *Toward Prescriptive Design of Educational Games: Mapping Game Mechanics to Learning Elements through Literature and Expert Review*.

It contains the **systematic literature review (SLR)** dataset, coding procedures, and integration with an **expert survey (N=17)**.  
The aim is to provide transparent, reusable resources for the serious games community.

---

## 📑 Methodology

### 1. Search & Selection
- **Databases searched**: Scopus, Web of Science, IEEE Xplore, ACM DL, SpringerLink.  
- **Query string**:  ("Game mechanic" OR "Game element") AND "learning" NOT "gamification"

- **Inclusion criteria**:
- Peer-reviewed (2014–2020), digital educational games, English.
- **Exclusion criteria**:
- Books, theses, posters, abstracts-only, non-digital games.

✅ **72 articles** were included. Each is identified by a **Paper ID** (e.g., PID2).

---

### 2. Coding Procedure
- **Coder**: One researcher manually coded all 72 articles.  
- **Approach**:  
- *Deductive*: categories from prior frameworks (e.g., Arnab et al. 2015; Callaghan et al. 2017).  
- *Inductive*: new categories from close reading.  
- **Multiple assignment**: Each article could have >1 learning dimension and >1 game mechanic.  
- **Passes**: Two coding passes for consistency and refinement.

📊 **Results**:  
- Avg. **1.62 learning dimensions** per paper.  
- Avg. **2.71 game mechanics categories** per paper.  

---

### 3. Consolidation with Expert Survey
- **17 experts** from 9 countries.  
- Roles: 13 researchers, 3 game designers, 1 interaction designer.  
- Avg. experience: 47% > 10 years.  
- Captured perspectives on learner modeling, instructional elements, and constraints.

🔗 Findings from SLR and survey were **triangulated**:  
- Convergences = strong evidence.  
- Divergences = opportunities for further study.  
- No numerical weighting applied.

---

### 4. Data & Reproducibility
- [`data/Selected StudiesDataRAW.xlsx`](data/Selected%20StudiesDataRAW.xlsx): Raw coding dataset (Sheet: `DataSet`).  
- [`data/02GM-LM-Relationships Data.xlsx`](data/02GM-LM-Relationships%20Data.xlsx): List of 72 included studies (Paper IDs). 
- [`data/ExpertSurvey-RawData.xlsx`](data/ExpertSurvey-RawData.xlsx): Raw respondents dataset (anonymized) (Sheet: `DataSet`).
- [`docs/survey_instrument.pdf`](docs/survey_instrument.pdf): Full survey instrument.  
- All resources are provided under **[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)**.

---

## 📂 Repository Layout

LiteratureReviewExpertSurvey-Methodology/
│

├── README.md # Project overview & methodology

├── LICENSE # Open license (CC BY 4.0)

│

├── data/

│ ├── 02GM-LM-Relationships Data.xlsx # Coding dataset

│ └── included_studies.csv # 72 included papers (IDs)

│

├── docs/

│ ├── methodology.md # Full detailed methodology

│ └── survey_instrument.pdf # Survey instrument



