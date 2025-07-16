# australia-road-crash-graph-analysis
A graph database project using Neo4j to analyze Australian road fatalities. Includes property graph modeling, ETL, Cypher queries and graph algorithms for pattern discovery and insights.

### CITS5504 Graph Database Project – Australian Road Fatalities

This repository contains all files and documentation for the **Graph Database Project** of the unit **CITS5504: Data Warehousing** at The University of Western Australia (Semester 1, 2025). The project focuses on using **Neo4j** to analyze Australian road fatality data through graph modeling and analytics.

---

#### Project Overview

The objective of this project is to:

* Design a **property graph model** to represent entities like crashes, persons, vehicles, LGAs, and roads.
* Perform **ETL** using Python to generate graph-ready CSVs.
* Import data into **Neo4j** and create nodes and relationships using Cypher.
* Run **Cypher queries** to uncover analytical insights and answer business questions.
* Apply **Graph Data Science (GDS)** algorithms such as PageRank and Louvain for community detection and node importance.

---

#### Contents

* data/: Cleaned and structured datasets.
* etl/: Python scripts for transforming tabular data into graph-friendly format.
* cypher/: Cypher scripts for creating and querying the graph.
* gds/: Cypher scripts and results for applying graph algorithms.
* design/: Graph schema design (Arrows App diagram or screenshots).
* screenshots/: Output screenshots from Neo4j Browser or Bloom.
* report/: Final PDF report including design, queries, results, and discussion.

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
