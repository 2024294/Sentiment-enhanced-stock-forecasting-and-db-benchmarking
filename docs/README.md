## 🏗️ Big Data Architecture

The following diagram illustrates the end-to-end big data architecture used in this project,
including data storage, distributed processing, database benchmarking, and result analysis.

### Architecture Overview
- Raw stock and tweet data are stored in HDFS
- PySpark performs preprocessing, merging, and sentiment extraction
- Processed datasets are benchmarked using MySQL and MongoDB via YCSB
- Performance metrics are collected and visualized for comparative analysis
