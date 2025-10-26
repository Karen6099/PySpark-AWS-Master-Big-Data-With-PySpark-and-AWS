# PySpark-AWS-Master-Big-Data-With-PySpark-and-AWS

Learning repository with PySpark examples and notebooks sourced from the Udemy course:
https://www.udemy.com/course/pyspark-aws-master-big-data-with-pyspark-and-aws/

This repo holds example Jupyter notebooks and sample data used while following the course. The README below has been updated to reflect the current files in the workspace.

## Project structure (current)

- `notebooks/` — Jupyter notebooks with PySpark examples and exercises
- `data/` — sample input files used by the notebooks
- `Output_WordCount/` — output directory produced by some wordcount examples
- `README.md` — this file

## Notebooks (what's included)

- `My First Notebook.ipynb` — basic PySpark setup and simple RDD examples
- `Map.ipynb` — examples demonstrating the `map` transformation
- `Map_Quiz.ipynb` — quiz / exercise using `map`
- `FlatMap.ipynb` — examples demonstrating `flatMap` on RDDs
- `Filter.ipynb` — using `filter` to remove unwanted elements from RDDs
- `Filter_Quiz.ipynb` — filter exercises/quizzes
- `GroupByKey.ipynb` — grouping data by key (RDD pair RDD examples)
- `ReduceByKey.ipynb` — aggregation examples using `reduceByKey`
- `WordCount.ipynb` — classic word count example (reads text, counts words)
- `Count.ipynb` — notebooks demonstrating counting operations (e.g., count, countByValue)
- `Distinct.ipynb` — shows how to get distinct elements from an RDD
- `SaveAsTextFile.ipynb` — saving results to text files (e.g., output directory)

## Data files (in `data/`)

- `Sample.txt` — small sample text file used in introductory examples
- `Sample_words.txt` — small word-sample file used in mapping/splitting examples
- `Sample_words2.txt` — additional sample words file
- `Map_Quiz.txt` — sample file used by the `Map_Quiz` exercises
- `Output_WordCount/` — directory (created by notebooks) that contains output from word count
- `Output_WordCount.txt/` — (present in repo) may be an exported or checkpointed output directory; inspect or remove if not needed

If you add or remove files from `data/` or `notebooks/`, update this README or the notebooks that reference them.

## Quick start

1. Install required Python packages (recommended in a virtual environment):

```bash
pip install pyspark
pip install jupyterlab  # optional
```

2. Ensure you have a compatible Java runtime installed (Java 17+ or the version recommended by your PySpark release). On this project we tested with Java 17 and Java 21.

3. Open the notebooks with Jupyter or VS Code and run cells interactively. For example, to open Jupyter Lab from the repo root:

```bash
jupyter lab
```

4. To re-run the WordCount example notebooks, open `WordCount.ipynb` or `SaveAsTextFile.ipynb` and follow the cells. Some examples will write results to `Output_WordCount/`.

## Notes and recommendations

- Use Python 3.11 or 3.12 for best compatibility with PySpark 4.x.
- If you plan to run larger examples on AWS (EMR / Glue / Databricks), adapt the cluster config and dependencies accordingly.
- Remove or archive large output directories (like `Output_WordCount/`) from the repo if you don't want them tracked by git.

## Contributing and next steps

- If you add new notebooks, add a short line to the Notebooks section above describing the purpose.
- Consider adding a `requirements.txt` or `pyproject.toml` if you want to pin dependencies for reproducible runs.

## License

Educational content / personal repo. Use for learning purposes.