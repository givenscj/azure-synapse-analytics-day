# Azure Synapse Analytics Lab

Lab time: 90 minutes

## Wide World Importers

Wide World Importers (WWI) is a wholesale novelty goods importer and distributor operating from the San Francisco bay area.

As a wholesaler, WWI's customers are mostly companies who resell to individuals. WWI sells to retail customers across the United States including specialty stores, supermarkets, computing stores, tourist attraction shops, and some individuals. WWI also sells to other wholesalers via a network of agents who promote the products on WWI's behalf. While all of WWI's customers are currently based in the United States, the company is intending to push for expansion into other countries.

WWI buys goods from suppliers including novelty and toy manufacturers, and other novelty wholesalers. They stock the goods in their WWI warehouse and reorder from suppliers as needed to fulfil customer orders. They also purchase large volumes of packaging materials, and sell these in smaller quantities as a convenience for the customers.

Recently WWI started to sell a variety of edible novelties such as chilli chocolates. The company previously did not have to handle chilled items. Now, to meet food handling requirements, they must monitor the temperature in their chiller room and any of their trucks that have chiller sections.

## Lab context

Wide World Importers is designing and implementing a Proof of Concept (PoC) for a unified data analytics platform. Their soft goals is to bring siloed teams to work together on a single platform.

In this lab, you will play the role of various persona: a data engineer, a business analyst and a data scientist. The workspace is already setup so you can focus on some of the core development capabilities of Azure Synapse Analytics.

By the end of this lab, you will have performed a non-exhaustive list of operations that combine the strength of Big Data and SQL analytics into a single platform.

## Solution architecture

The diagram below provides a unified view of the exercises in the lab and their estimated times for completion.

![Azure Synapse Analytics Lab Exercises](./media/exercises.png "Solution architecture")

## Exercise 1 - [Explore the data lake with SQL Analytics on-demand and Spark](./01-explore-data-lake.md)

In this exercise you will explore data using the engine of your choices (SQL or Spark).

Understanding data through data exploration is one of the core challenges faced today by data engineers and data scientists as well. Depending on the underlying structure of the data as well as the specific requirements of the exploration process, different data processing engines will offer varying degrees of performance, complexity, and flexibility.

In Azure Synapse Analytics, you have the possibility of using either the on-demand SQL engine, the big-data Spark engine, or both.

## Exercise 2 - [Build Modern Data Warehouse pipelines](./02-build-modern-dw-pipelines.md)

In this exercise you will use a pipeline with parallel activities to bring data into the Data Lake, transform it and load it into the SQL Pool. You will also monitor the progress of the associated tasks.

Once data is properly understood and interpreted, moving it to the various destinations where processing steps occur is the next big task. Any modern data platform must provide a seamless experience for all the typical data wrangling actions like extractions, parsing, joining, standardizing, augmenting, cleansing, consolidating, and filtering.

Azure Synapse Analytics provides two significant categories of features - data flows and data orchestrations (implemented as pipelines). They cover the whole range of needs, from design and development to triggering, execution, and monitoring.

## Exercise 3 - [Power BI integration](./03-power-bi-integration.md)

In this exercise you will build a Power BI report in Synapse.

The visual approach in data exploration, analysis, and interpretation is one of the essential tools for both technical users (data engineers, data scientists) and business users. Having a highly flexible and performant data presentation layer is a must for any modern data platform.

Azure Synapse Analytics integrates natively with Power BI, a proven and highly successful data presentation and exploration platform. The Power BI experience is available inside Synapse Studio.

## Exercise 4 - [High Performance Analysis with SQL Analytics pool](./04-high-performance-analysis.md)

In this exercise you will try to understand customer details using a query and chart visualizations. You will also explore the performance of various queries.

SQL data warehouses have been for a long time the centers of gravity in data platforms. Modern data warehouses are capable of providing high performance, distributed, and governed workloads, regardless of the data volumes at hand.

The SQL Analytics pool in Azure Synapse Analytics is the new incarnation of the former Azure SQL Data Warehouse. It provides all the modern SQL data warehousing features while benefiting from the advanced integration with all the other Synapse services.

## Exercise 5 - [Data Science with Spark](./05-data-science-with-spark.md)

In this exercise you will play the role of a Data Scientist that based on the <TBD> dataset, using Synapse Notebook, creates a model to predict <TBD>.

Modern era data environments must handle in a performant and seamless way any data an organization might have. In almost all cases, this means a combination of relational SQL-style capabilities and big data ones. In the world of massively distributed big data processing platforms, Spark is almost an implicit choice.

Azure Synapse Analytics provides Apache Spark pools to support data science workloads. They enable data scientists to perform all their specific tasks while benefiting from the integration with the other Synapse services.
