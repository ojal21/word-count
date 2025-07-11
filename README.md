# Named Entity WordCount Analysis using Databricks

**Databricks Notebook Link:** [View Project](https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2750839131378492/2665272599082127/8689822275567822/latest.html)

---

### 📌 Overview

A Named Entity Recognition (NER) WordCount pipeline built using **PySpark**, **NLTK**, and **Databricks** to process and analyze large text corpora from the **Gutenberg Project**.

---

### 🔧 Tools & Technologies

* **Platform:** Databricks
* **Processing:** PySpark, MapReduce
* **NLP:** NLTK (Named Entity Chunking)
* **Dataset:** Project Gutenberg (plain text)

---

### ⚙️ Key Features

* Developed a scalable **NER + WordCount pipeline** using PySpark on Databricks.
* Used **NLTK** to extract named entities from unstructured text.
* Applied **MapReduce-style logic** to compute frequency counts of named entities.
* Output a **ranked list** of top entities across multiple large documents.

---

### 🚀 Optimization Highlights

* Integrated NLP within the ETL flow for **real-time named entity categorization**.
* Improved entity recognition accuracy and text processing efficiency at scale.

---

### 📈 Output Sample (Top Entities)

| Entity       | Frequency |
| ------------ | --------- |
| Holmes       | 892       |
| Watson       | 514       |
| London       | 421       |
| Baker Street | 190       |

