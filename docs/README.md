### Architecture Overview
- Raw stock and tweet data are stored in HDFS
- PySpark performs preprocessing, merging, and sentiment extraction
- Processed datasets are benchmarked using MySQL and MongoDB via YCSB
- Performance metrics are collected and visualized for comparative analysis
