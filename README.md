# DS-505: Big Data Handling & ML Applications

Repository containing code implementations and outputs for practical coursework in big data ingestion, distributed computing, ML pipelines, and NLP transformers[cite: 1].

---

### 📂 Practical Overview

* **Unit 1: Large Dataset Handling & In-Memory Optimization**
  * `P01`: Tabular ingestion, metadata profiling, and summary statistics (`pandas`)[cite: 1].
  * `P02`: Data hygiene—deduplication, `dropna`, `fillna`, and renaming[cite: 1].
  * `P03`: Memory optimization via numeric downcasting and `category` types[cite: 1].
  * `P04`: Out-of-core streaming and aggregations using `pd.read_csv(chunksize=...)`[cite: 1].

* **Unit 2: Big Data Processing with PySpark**
  * `P05`: SparkSession setup, custom `StructType` schemas, and `printSchema()`[cite: 1].
  * `P06`: DataFrame transformations—`select`, `filter`, and `withColumn`[cite: 1].
  * `P07`: Grouped aggregations (`groupBy`, `agg`, `orderBy`) and action execution[cite: 1].
  * `P08`: Columnar serialization and verification using Apache Parquet[cite: 1].

* **Unit 3: ML Preprocessing & Supervised Modeling**
  * `P09`: Imputation (`SimpleImputer`), label encoding, and one-hot encoding[cite: 1].
  * `P10`: Feature scaling (`StandardScaler` vs. `MinMaxScaler`) and train-test splits[cite: 1].
  * `P11`: Regression modeling and metrics (`LinearRegression`, MSE, $R^2$)[cite: 1].
  * `P12`: Classification comparison using `DecisionTreeClassifier` and `KNN`[cite: 1].

* **Unit 4: Text Analytics & Transformers (LLMs)**
  * `P13`: Text normalization, punctuation cleaning, and tokenization[cite: 1].
  * `P14`: Stopword filtering and keyword frequency profiling (`Counter`)[cite: 1].
  * `P15`: Sentiment classification via Hugging Face `pipeline("sentiment-analysis")`[cite: 1].
  * `P16`: Abstractive summarization via Hugging Face `pipeline("summarization")`[cite: 1].

---

### 🛠️ Tech Stack
* **Languages & Core:** Python 3.10+, Java 11/17[cite: 1]
* **Libraries:** `pandas`, `numpy`, `pyspark`, `scikit-learn`, `transformers`, `torch`[cite: 1]
