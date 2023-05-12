# About

This repo contains a set of DynamoDB and a few S3 helper functions to help you use the DynamoDB database in a much more convenient, intuitive and safe manner.

# Demo

```python
successful, item = getItemDDB("your_partition_key", "your_sort_key", "your_table")
```

```python
items = batchGetItemDDB(...)
```