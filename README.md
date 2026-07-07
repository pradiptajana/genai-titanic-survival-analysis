# Generative AI: Titanic Survival Analysis & Automated Reporting Pipeline 🚢🤖

## 📌 Project Overview
This project reimagines the classic Titanic survival dataset by transforming raw statistical data analysis into a automated, stakeholder-ready reporting engine. 

Using **Python (Pandas, NumPy)**, the pipeline performs rigorous exploratory data analysis (EDA) and calculates multi-variable statistical survival probabilities (isolating impacts of socio-economic class, gender, age, and familial networks). The pipeline then feeds these structured data matrices into an **optimized Generative AI prompting framework** to automatically synthesize data-driven executive briefs—eliminating the manual friction of translating code outputs into narrative reports.

---

## 🛠️ Tech Stack & Tooling
*   **Data Exploration & Parsing:** Python, Pandas, NumPy (Data cleaning, statistical feature grouping, multi-variable isolation).
*   **AI Automation:** Advanced Framework-driven Prompt Engineering (System role constraints, structured output enforcement, few-shot contextual logic).
*   **Reporting Architecture:** Dynamically generated Markdown structures for executive stakeholder delivery.

---

## ⚙️ Core Pipeline Architecture

### 1. Python Exploratory Data Analysis (EDA) Layer
*   **Data Scrubber:** Handled missing data anomalies (such as tracking age metrics and engineering localized deck structural values from cabin numbers).
*   **Multi-Variable Modeling:** Segmented raw survival tracking data across intersecting dimensions (e.g., calculating the precise compound survival probability shifts between female passengers in 1st class vs. male passengers in 3rd class).
*   **Matrix Export:** Structured code blocks to aggregate complex statistical survival tables into clear, clean string matrices ready for language model ingestion.

### 2. Generative AI Narrative Engine
*   **Persona & Guardrail Constraints:** Authored specialized system prompts enforcing an expert corporate risk-analyst persona, ensuring 100% adherence to data constraints and eliminating hallucinations.
*   **Few-Shot Prompt Engineering:** Programmed example templates within the text block to guide the model on formatting tone, structured headers, and analytical narrative styles.
*   **Automated Translation:** Automated the transformation of raw, dense statistical logs into concise executive briefing notes containing business-focused key takeaways.

---

## 📂 Repository Structure
```text
├── datasets/
│   ├── train.csv                      # Raw historical passenger survival data
│   └── test.csv                       # Evaluation passenger dataset
├── notebooks/
│   └── titanic_eda_modeling.ipynb     # Python notebook executing EDA and statistical isolation
├── prompts/
│   └── executive_brief_prompts.txt    # Engineered system and user prompts for the LLM pipeline
├── outputs/
│   └── sample_executive_briefing.md   # Final, AI-generated stakeholder reporting output
└── README.md                          # Production-grade project documentation
