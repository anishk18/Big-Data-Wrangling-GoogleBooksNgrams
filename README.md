 🧠 Big Data Wrangling with Google Books Ngrams

This project demonstrates how to use **Hadoop**, **Spark**, and **AWS EMR** to process large-scale textual data from the [Google Books Ngrams dataset](https://aws.amazon.com/opendata/public-datasets/google-books-ngrams/).  
The analysis focuses on understanding token frequencies across time and comparing the performance and architecture of **Hadoop** and **Spark**.

---

## 📊 Project Overview

### Dataset
The Google Books Ngrams dataset represents about 4% of all published books, spanning from the 1800s to the 2000s.  


### Objectives
1. Set up an **AWS EMR cluster** for distributed computing.
2. Use **Spark** and **HDFS** to:
   - Load and inspect the dataset.
   - Filter tokens for `"data"`.
   - Write filtered results to HDFS and S3.
3. Use **Pandas** and **Matplotlib** locally to:
   - Read the filtered results from S3.
   - Visualize the frequency of the token `"data"` over time.
4. Compare **Hadoop vs Spark**.

---

## ⚙️ Technologies Used
- **AWS EMR**
- **Apache Hadoop**
- **Apache Spark (PySpark)**
- **Amazon S3**
- **Python** (pandas, matplotlib)
- **Jupyter Notebook**

---

## 🧩 Repository Structure

```
Big-Data-Wrangling-GoogleBooksNgrams/
│
├── [README.md](README.md)
├── [.gitignore](.gitignore)
├── [requirements.txt](requirements.txt)
│
└── notebooks/
    ├── [Big Data Wrangling With Google Books Ngrams_Q4.ipynb](<notebooks/Big Data Wrangling With Google Books Ngrams_Q4.ipynb>)
    └── [Big Data Wrangling With Google Books Ngrams_Q6_Q7.ipynb](<notebooks/Big Data Wrangling With Google Books Ngrams_Q6_Q7.ipynb>)
```


---

## 📈 Results

- Filtered data for the token `"data"` successfully extracted and saved to S3.  
- Visualization shows trends in token frequency across years, indicating how the usage of “data” evolved historically.  
- Hadoop and Spark comparison summarized in the report.

---

## 🔍 Key Takeaways

| Framework | Key Advantages |
|------------|----------------|
| **Hadoop** | Reliable distributed file system (HDFS), fault-tolerant storage |
| **Spark**  | In-memory processing, faster computation for iterative tasks |

---

## 📘 How to Run

 Clone this repository:
   ```bash
   git clone https://github.com/anishk18/Big-Data-Wrangling-GoogleBooksNgrams.git
   cd Big-Data-Wrangling-GoogleBooksNgrams
