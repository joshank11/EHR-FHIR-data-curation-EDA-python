# Multimodal AI in Healthcare

This repository contains the code and resources for a project series on building multimodal AI systems for healthcare. We will explore how to integrate different types of biomedical data—such as Electronic Health Records (EHR), medical images, genomics, and more—to create more comprehensive and accurate AI models.

This project is designed to be accessible and can be run on a local machine.

## 📖 Class 1: EHR Data Curation & EDA

In our first class, we focus on the foundational principles of data curation and Exploratory Data Analysis (EDA) using synthetic Electronic Health Record (EHR) data. This step is crucial for understanding the structure of unimodal data before we attempt to combine different modalities.

### What's Inside?

- **`ehr_data_generation.py`**: A Python script to generate synthetic patient data that mimics real-world EHR formats (FHIR and OMOP).
- **`ehr_eda.ipynb`**: A Jupyter Notebook demonstrating how to perform EDA on the generated EHR data, including data profiling, statistical summaries, and visualizations.

### 🚀 Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/multimodal-ai-healthcare.git](https://github.com/your-username/multimodal-ai-healthcare.git)
    cd multimodal-ai-healthcare
    ```

2.  **Install dependencies:**
    This project requires `pandas`, `json`, `datetime`, and `matplotlib`. You can install them using pip:
    ```bash
    pip install pandas matplotlib
    ```

3.  **Run the code:**
    You can run the script directly or follow along with the Jupyter Notebook to generate and analyze the synthetic data.

    ```bash
    python ehr_data_generation.py
    ```

### ⏭️ What's Next?

In our upcoming classes, we will build upon this foundation by:

- **Moving to real-world EHR data**: We will use a public dataset to train a simple machine learning model.
- **Introducing new modalities**: We will add other data types, such as genomics, medical imaging, and biosignals (e.g., ECG).
- **Developing multimodal models**: We will learn how to combine and fuse these different data types to build a single, powerful AI system for patient data stratification.

Stay tuned for updates!

---
## 📄 License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
