# Big-Data-Data-Pipeline-Infrastructure
Internship project documenting work with Linux-based data infrastructure, distributed systems, storage, data pipelines, and Big Data concepts.
# Big Data & Hadoop Infrastructure

Portfolio project based on a six-month internship in the **NOSiCloud Big Data area**, focused on Big Data architecture, Linux-based distributed systems, Apache Hadoop, data storage technologies, and the technical foundations of data pipelines.

The strongest practical part of the internship was the deployment and troubleshooting of a **four-node distributed Hadoop cluster** after first working through standalone and pseudo-distributed installation modes.

---

## Internship Context

- **Organization:** NOSi
- **Department:** NOSiCloud
- **Area:** Big Data Technology
- **Location:** Praia, Cabo Verde
- **Year:** 2023
- **Duration:** 6 months

The internship combined research, training, technical experimentation, architecture study, and practical infrastructure work.

---

## Main Objective

The internship focused on understanding how a Big Data environment can:

- collect data
- store data
- process data
- analyze data
- support decision-making

The work also explored how different technologies fit together across the stages of a Big Data architecture.

---

## Practical Work Completed

### Apache Hadoop Cluster Deployment

The main practical infrastructure accomplishment was the installation of Apache Hadoop in a distributed environment using four machines.

The installation progressed through three stages:

~~~text
Standalone
    ↓
Pseudo-distributed
    ↓
Fully distributed cluster
~~~

The standalone and pseudo-distributed modes were used for testing and debugging before moving to the full distributed configuration.

The final setup used four machines and demonstrated the basic principles of distributed storage and processing.

---

## Hadoop Components Studied

The internship included study of the core Hadoop components:

- **HDFS** — Hadoop Distributed File System
- **MapReduce** — distributed data processing model
- **YARN** — cluster resource management

The project also included study of how these components fit into the wider Hadoop ecosystem.

---

## Distributed Systems

The internship helped build an understanding of why large-scale data processing relies on distributed computing.

Instead of relying on one increasingly powerful machine, Hadoop distributes storage and processing across multiple systems.

A simplified architecture is:

~~~text
Multiple Machines
       ↓
Distributed Storage
       ↓
Distributed Processing
       ↓
Big Data Workloads
~~~

This introduced practical concepts such as:

- scalability
- distributed storage
- cluster computing
- fault-tolerant architecture
- resource distribution

---

## Linux Administration

Linux command-line administration was an important part of the Hadoop deployment process.

The work included practical exposure to:

- Linux CLI
- remote system administration
- software installation
- configuration files
- troubleshooting
- service setup
- compatibility checks
- cluster preparation

The Hadoop installation required repeated testing and debugging, which strengthened Linux command-line and systems troubleshooting skills.

---

## Big Data Architecture

A major part of the internship focused on understanding the complete Big Data lifecycle.

The architecture can be represented as:

~~~text
Data Sources
     ↓
Data Collection
     ↓
Data Ingestion
     ↓
Data Storage
     ↓
Data Processing
     ↓
Data Analysis
     ↓
Insights / Applications
~~~

Different technologies may be selected depending on:

- data volume
- data velocity
- data format
- performance requirements
- consistency requirements
- availability requirements
- infrastructure constraints

---

## Data Storage Technologies

The internship included research into non-relational databases commonly used in Big Data environments.

Technologies studied included:

- HBase
- MongoDB
- Cassandra

The work also covered:

- relational vs non-relational databases
- distributed storage
- scalability
- partition tolerance
- availability
- consistency
- the CAP theorem

---

## HBase

HBase was studied as a distributed database built on top of HDFS.

Its role within the Hadoop ecosystem helped demonstrate how distributed storage systems can support large-scale structured access to data.

---

## Hive & Data Warehousing

The internship also included study of Hive and data warehousing concepts.

Hive provides a data warehouse layer for large datasets and uses a SQL-like query language called HQL.

This helped connect Big Data infrastructure concepts with analytical querying and structured data access.

---

## Python & Data Analysis

Python was also part of the learning process.

The internship included:

- Python review and practice
- exposure to Pandas
- NumPy
- matplotlib
- participation in a data-analysis activity with the Business Intelligence team

Python was studied because of its importance in data engineering, analysis, automation, and Big Data ecosystems.

---

## Data Pipeline Concepts

The internship explored the role of different technologies in data pipelines.

Examples studied included:

- Kafka
- Flume
- Spark Streaming
- Storm
- Flink
- Hive
- HBase
- Cassandra
- HDFS

These technologies were studied as possible components in systems involving:

~~~text
Collection
   ↓
Ingestion
   ↓
Streaming
   ↓
Storage
   ↓
Processing
   ↓
Analysis
~~~

Not all of these technologies were installed or implemented during the internship.

---

## Architecture Examples Studied

The internship included analysis of example Big Data architectures.

Examples included:

### Real-Time Product Ranking

~~~text
Purchase Data
     ↓
Flume
     ↓
Spark Streaming
     ↓
Cassandra
     ↓
Web Application
~~~

### Daily Session Processing

~~~text
Web Servers
     ↓
Kafka
     ↓
Spark Streaming
     ↓
Oozie
     ↓
Hive
     ↓
HDFS
~~~

### Recommendation Architecture

~~~text
Web Servers
     ↓
Flume
     ↓
Spark Streaming
     ↓
HBase / HDFS
     ↓
Recommendation Service
~~~

These architectures were studied to understand how components are selected according to the specific requirements of a system.

---

## Infrastructure Design Considerations

The internship reinforced that there is no single Big Data architecture that fits every problem.

Important design questions include:

- How much data is being processed?
- Is a cluster actually necessary?
- What infrastructure already exists?
- What are the security requirements?
- How quickly must users receive results?
- Is the workload batch or real-time?
- How much data must be retained?
- Which is more important: consistency, availability, or partition tolerance?
- Which technologies are already used by the organization?

These considerations help guide technology selection instead of choosing tools only because they are popular.

---

## Project Scope

The internship did **not** result in a complete production Big Data pipeline.

The completed work included:

- Big Data fundamentals
- Big Data architecture
- Hadoop study
- Hadoop cluster installation
- Hadoop ecosystem research
- Linux command-line work
- storage technology research
- non-relational database research

Some areas remained in progress or were not implemented during the internship, including:

- full ingestion pipelines
- production streaming systems
- HBase installation
- Hive installation
- Spark installation
- complete production data analysis workflow

This repository documents both the completed work and the architecture concepts studied during the internship.

---

## Skills Demonstrated

- Linux administration
- Apache Hadoop
- HDFS
- MapReduce
- YARN
- distributed systems
- cluster deployment
- infrastructure troubleshooting
- Big Data architecture
- data pipeline concepts
- NoSQL databases
- HBase
- MongoDB
- Cassandra
- Hive
- data warehousing
- Python fundamentals
- Pandas exposure
- technical research
- infrastructure documentation

---

## Internship Report

The full internship report is available in:

~~~text
docs/internship-report.pdf
~~~

The report documents the internship objectives, research, technical work, Hadoop deployment, architecture study, results, and conclusions.

---

## Key Takeaway

The most important outcome of the internship was gaining an understanding of how distributed infrastructure, storage, processing, and data engineering technologies fit together.

The practical milestone was successfully completing a four-machine Hadoop cluster deployment while developing a stronger foundation in Linux administration, distributed systems, troubleshooting, and Big Data architecture.
