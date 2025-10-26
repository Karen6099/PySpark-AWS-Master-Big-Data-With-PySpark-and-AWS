# Databricks notebook source
print("Hello World")

# COMMAND ----------

from pyspark.sql import SparkSessionspark = SparkSession.builder.config(conf=conf).getOrCreate()

text = sc.textFile("/FileStore/tables/sample.txt")
words = text.flatMap(lambda line: line.split(" "))
wordCounts = words.countByValue()