# Databricks 14 Days AI Challenge

## Day 1 – Databricks Basics

### What I did
- Created Databricks Community Edition account
- Created first PySpark DataFrame
- Applied filter using Spark DataFrame API

### Code used
```python
data = [("iPhone", 999), ("Samsung", 799), ("MacBook", 1299)]
df = spark.createDataFrame(data, ["product", "price"])
df.show()

df.filter(df.price > 1000).show()
