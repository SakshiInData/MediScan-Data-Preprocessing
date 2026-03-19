# MediScan: Data Preprocessing Pipeline 🏥

This repository focuses on the core data engineering and preprocessing stage of the **MediScan** project—an AI-driven system designed to interpret and structure medical reports.

## 📌 Project Overview
The goal of this module is to transform raw, unstructured medical data (images/text) into a clean, structured format (CSV/Parquet) ready for NLP model training.

## 🛠️ Key Features
* **OCR Extraction:** Converting textual medical reports into machine-readable strings.
* **Text Normalization:** Handling medical abbreviations, noise removal, and case folding.
* **Structured Output:** Exporting processed data into optimized formats for high-performance training.
* **Data Validation:** Ensuring dataset consistency across `final_dataset.csv`.

## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, OpenCV (for image handling), Tesseract/EasyOCR.
* **Environment:** PyCharm / Jupyter Notebooks.

## 📂 Repository Structure
* `/data`: Contains raw and processed datasets (ignored by Git for privacy).
* `sample.ipynb`: Exploratory Data Analysis (EDA) and pipeline prototyping.
* `requirements.txt`: List of dependencies needed to run the scripts.

## 🚀 Future Roadmap
- [ ] Integration with SQL database for automated report storage.
- [ ] Implementation of Named Entity Recognition (NER) for medical terminology.
- [ ] Expanded support for handwritten prescription OCR.
