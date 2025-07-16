# australia-road-crash-graph-analysis
A graph database project using Neo4j to analyze Australian road fatalities. Includes property graph modeling, ETL, Cypher queries and graph algorithms for pattern discovery and insights.


#### Project Overview

The objective of this project is to:

* Design a **property graph model** to represent entities like crashes, persons, vehicles, LGAs, and roads.
* Perform **ETL** using Python to generate graph-ready CSVs.
* Import data into **Neo4j** and create nodes and relationships using Cypher.
* Run **Cypher queries** to uncover analytical insights and answer business questions.
* Apply **Graph Data Science (GDS)** algorithms such as PageRank and Louvain for community detection and node importance.

---

#### Contents

* csv_files/: Cleaned and structured datasets.
* scripts_codes/etl.py: Python scripts for transforming tabular data into graph-friendly format.
* scripts_codes/all_scripts.txt: Cypher scripts for creating and querying the graph.
* Project_2_report.pdf: Final PDF report including design, queries, results, and discussion.

---

#### Tools and Technologies

* **Neo4j** (Desktop or Aura)
* **Cypher Query Language**
* **Python** (Pandas, CSV, os)
* **Neo4j Graph Data Science Library**
* **Arrows App** for graph schema modeling

---

#### Key Features

* **Property Graph Design**: Modeling complex relationships between crashes, people, and locations.
* **Custom Cypher Queries**: Business insights such as LGA-level analysis, crash chains, and vehicle involvement.
* **GDS Algorithms**:

  * **PageRank** – Identify influential LGAs or crash clusters.
  * **Louvain** – Detect community structure in crash networks.
* **Efficient ETL**: Python-based script transforms flat files into structured CSVs for Neo4j import.

---

#### 📄 Author

Aparna Nair
