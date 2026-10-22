# Data Engineering Interview Questions

A curated list of **129 data engineering interview questions** plus **248 DSA problems**, with worked answers, grouped by topic and
ordered from easy to hard: SQL, Python, PySpark, Spark internals, data modeling, system design, Kafka, Airflow,
Delta Lake, Databricks, Snowflake, AWS and DSA for data engineers.

Every answer is on [DataDank](https://datadank.com/), a free Data Engineering learning site. Each one has a short
answer, a detailed explanation, runnable code that was executed before publishing, common mistakes and follow-up
questions.

**Start here:** the [90-day Data Engineering interview plan](https://datadank.com/planner/90-day-plan/) and the
[Data Engineering glossary](https://datadank.com/glossary/).

## Top-N question lists

- [Top 50 Apache Airflow Interview Questions and Answers](https://datadank.com/airflow/airflow-interview-questions/)
- [18 Behavioral Interview Questions for Data Engineers (with STAR Answers)](https://datadank.com/career/behavioral-interview-questions/)
- [Top 100 Data Engineering Interview Questions and Answers](https://datadank.com/career/data-engineering-interview-questions/)
- [50 Scenario-Based Data Engineering Interview Questions and Answers](https://datadank.com/career/scenario-based-data-engineering-interview-questions/)
- [Top 50 Databricks Interview Questions and Answers](https://datadank.com/databricks/databricks-interview-questions/)
- [Top 50 dbt Interview Questions and Answers](https://datadank.com/dbt/dbt-interview-questions/)
- [Top 40 Apache Kafka Interview Questions and Answers](https://datadank.com/kafka/kafka-interview-questions/)
- [Top 50 PySpark and Spark Interview Questions and Answers](https://datadank.com/pyspark/pyspark-interview-questions/)
- [Top 50 Python Interview Questions for Data Engineers](https://datadank.com/python/python-interview-questions/)
- [Top 50 Snowflake Interview Questions and Answers](https://datadank.com/snowflake/snowflake-interview-questions/)
- [Top 50 SQL Interview Questions and Answers for Data Engineers](https://datadank.com/sql/sql-interview-questions/)

## Contents

- [SQL](#sql) (29)
- [Python](#python) (9)
- [PySpark](#pyspark) (2)
- [Apache Spark](#apache-spark) (6)
- [Data Modeling and Warehousing](#data-modeling-and-warehousing) (8)
- [Data Engineering and System Design](#data-engineering-and-system-design) (18)
- [Apache Kafka](#apache-kafka) (15)
- [Apache Airflow](#apache-airflow) (12)
- [Delta Lake](#delta-lake) (8)
- [Databricks](#databricks) (3)
- [Snowflake](#snowflake) (8)
- [AWS](#aws) (11)
- [DSA for Data Engineers](#dsa-for-data-engineers) (248)

## SQL

| # | Question | Level |
|---|---|---|
| 1 | [Explain INNER JOIN vs LEFT JOIN with a practical example.](https://datadank.com/interview/sql/inner-vs-left-join/) | Easy |
| 2 | [Find customers who never placed an order, and explain NOT IN vs NOT EXISTS.](https://datadank.com/interview/sql/customers-without-orders-anti-join/) | Easy |
| 3 | [How do window functions differ from GROUP BY?](https://datadank.com/interview/sql/window-functions-vs-group-by/) | Easy |
| 4 | [In what order is a SQL query evaluated, and what is the difference between WHERE and HAVING?](https://datadank.com/interview/sql/sql-execution-order-where-vs-having/) | Easy |
| 5 | [Average Order Value: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/average-order-value-sql-case-study/) | Medium |
| 6 | [Calculate month-over-month and year-over-year revenue growth in SQL.](https://datadank.com/interview/sql/month-over-month-growth/) | Medium |
| 7 | [Compute a running total and a 3-day moving average of daily revenue in SQL.](https://datadank.com/interview/sql/running-total-moving-average/) | Medium |
| 8 | [Customer Lifetime Value: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/customer-lifetime-value-sql-case-study/) | Medium |
| 9 | [Daily Active Users: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/daily-active-users-sql-case-study/) | Medium |
| 10 | [Find the second-highest salary without using a simple MAX approach.](https://datadank.com/interview/sql/second-highest-salary/) | Medium |
| 11 | [How would you detect and remove duplicate records safely?](https://datadank.com/interview/sql/remove-duplicate-records/) | Medium |
| 12 | [Lead Scoring: SQL Case Study with 7 Approaches](https://datadank.com/interview/sql/lead-scoring-sql-case-study/) | Medium |
| 13 | [New vs Returning Customers: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/new-vs-returning-customers-sql-case-study/) | Medium |
| 14 | [Refund Analysis: SQL Case Study with 7 Approaches](https://datadank.com/interview/sql/refund-analysis-sql-case-study/) | Medium |
| 15 | [Return the top three salaries in each department, including ties.](https://datadank.com/interview/sql/top-n-per-group-department-salaries/) | Medium |
| 16 | [Revenue doubled after you joined a second table. What happened and how do you fix it?](https://datadank.com/interview/sql/join-fan-out-double-counting/) | Medium |
| 17 | [Session Duration: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/session-duration-sql-case-study/) | Medium |
| 18 | [Subscription Renewals: SQL Case Study with 7 Approaches](https://datadank.com/interview/sql/subscription-renewals-sql-case-study/) | Medium |
| 19 | [There is an index on the column, but EXPLAIN shows a sequential scan. Why?](https://datadank.com/interview/sql/index-not-used-explain/) | Medium |
| 20 | [Top Selling Products: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/top-selling-products-sql-case-study/) | Medium |
| 21 | [A/B Test Results: SQL Case Study with 7 Approaches](https://datadank.com/interview/sql/a-b-test-results-sql-case-study/) | Hard |
| 22 | [Churn Rate: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/churn-rate-sql-case-study/) | Hard |
| 23 | [Conversion Funnel: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/conversion-funnel-sql-case-study/) | Hard |
| 24 | [Employee Hierarchy: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/employee-hierarchy-sql-case-study/) | Hard |
| 25 | [Fraud Pattern Detection: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/fraud-pattern-detection-sql-case-study/) | Hard |
| 26 | [How would you optimize a slow analytical SQL query?](https://datadank.com/interview/sql/optimize-slow-query/) | Hard |
| 27 | [Inventory Turnover: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/inventory-turnover-sql-case-study/) | Hard |
| 28 | [Monthly Revenue: SQL Case Study with 8 Approaches](https://datadank.com/interview/sql/monthly-revenue-sql-case-study/) | Hard |
| 29 | [Write an SCD Type 2 upsert in SQL that closes old versions and inserts new ones.](https://datadank.com/interview/sql/scd-type-2-merge-sql/) | Hard |

## Python

| # | Question | Level |
|---|---|---|
| 1 | [Explain shallow copy vs deep copy.](https://datadank.com/interview/python/shallow-vs-deep-copy/) | Easy |
| 2 | [List vs tuple vs set: when would you use each in a data pipeline?](https://datadank.com/interview/python/list-tuple-set/) | Easy |
| 3 | [What is a generator and why can it help with large datasets?](https://datadank.com/interview/python/generators-large-datasets/) | Easy |
| 4 | [Why are mutable default arguments dangerous in Python?](https://datadank.com/interview/python/mutable-default-arguments/) | Easy |
| 5 | [How should exceptions be handled in production data pipelines?](https://datadank.com/interview/python/exceptions-in-pipelines/) | Medium |
| 6 | [How would you add retries with backoff to API ingestion in Python?](https://datadank.com/interview/python/api-retries-backoff/) | Medium |
| 7 | [How would you process a 50 GB CSV file on a machine with 8 GB of RAM?](https://datadank.com/interview/python/process-large-csv-limited-memory/) | Medium |
| 8 | [When would you not use pandas in a data pipeline?](https://datadank.com/interview/python/when-not-to-use-pandas/) | Medium |
| 9 | [Why are dict and set lookups O(1) in Python, and when are they not?](https://datadank.com/interview/python/dict-set-complexity/) | Medium |

## PySpark

| # | Question | Level |
|---|---|---|
| 1 | [When should you avoid Python UDFs in PySpark?](https://datadank.com/interview/pyspark/avoid-python-udfs/) | Medium |
| 2 | [When would you use a broadcast join in Spark?](https://datadank.com/interview/pyspark/broadcast-join/) | Medium |

## Apache Spark

| # | Question | Level |
|---|---|---|
| 1 | [What is the difference between a transformation and an action in Spark?](https://datadank.com/interview/spark/transformation-vs-action/) | Easy |
| 2 | [Explain Spark jobs, stages and tasks.](https://datadank.com/interview/spark/jobs-stages-tasks/) | Medium |
| 3 | [How does partition count affect Spark performance?](https://datadank.com/interview/spark/partition-count-performance/) | Medium |
| 4 | [What causes a shuffle in Spark?](https://datadank.com/interview/spark/what-causes-a-shuffle/) | Medium |
| 5 | [How does Spark Structured Streaming handle late data with watermarks?](https://datadank.com/interview/spark/streaming-watermarks-late-data/) | Hard |
| 6 | [What is data skew and how can you mitigate it?](https://datadank.com/interview/spark/data-skew/) | Hard |

## Data Modeling and Warehousing

| # | Question | Level |
|---|---|---|
| 1 | [Design a star schema for a business process. What is the grain?](https://datadank.com/interview/data-warehousing/design-star-schema-grain/) | Medium |
| 2 | [Kimball vs Inmon vs Data Vault: which would you choose for a new warehouse?](https://datadank.com/interview/data-warehousing/kimball-vs-inmon-vs-data-vault/) | Medium |
| 3 | [One big table or a star schema: how do you decide?](https://datadank.com/interview/data-warehousing/one-big-table-vs-star-schema/) | Medium |
| 4 | [Surrogate keys vs natural keys: which should a dimension use, and why?](https://datadank.com/interview/data-warehousing/surrogate-vs-natural-keys/) | Medium |
| 5 | [Transaction, periodic snapshot or accumulating snapshot: which fact table would you build?](https://datadank.com/interview/data-warehousing/fact-table-types/) | Medium |
| 6 | [What are conformed and role-playing dimensions, and how do you use them?](https://datadank.com/interview/data-warehousing/conformed-and-role-playing-dimensions/) | Medium |
| 7 | [How do you implement an SCD Type 2 dimension and query it with as-of joins?](https://datadank.com/interview/data-warehousing/scd-type-2-as-of-joins/) | Hard |
| 8 | [How do you model late-arriving dimensions and late-arriving facts in a star schema?](https://datadank.com/interview/data-warehousing/late-arriving-dimensions-and-facts/) | Hard |

## Data Engineering and System Design

| # | Question | Level |
|---|---|---|
| 1 | [ETL vs ELT: what factors decide the choice?](https://datadank.com/interview/data-engineering/etl-vs-elt-factors/) | Easy |
| 2 | [Batch or streaming: how do you choose for a use case?](https://datadank.com/interview/data-engineering/batch-vs-streaming-choice/) | Medium |
| 3 | [Data lake vs warehouse vs lakehouse: when would you choose each?](https://datadank.com/interview/data-engineering/lake-warehouse-lakehouse/) | Medium |
| 4 | [How do you backfill a pipeline safely?](https://datadank.com/interview/data-engineering/backfill-safely/) | Medium |
| 5 | [How do you handle PII in a data pipeline?](https://datadank.com/interview/data-engineering/handle-pii-in-pipelines/) | Medium |
| 6 | [How do you handle late-arriving data?](https://datadank.com/interview/data-engineering/late-arriving-data/) | Medium |
| 7 | [How do you handle schema changes from upstream sources in a pipeline?](https://datadank.com/interview/data-engineering/schema-evolution-in-pipelines/) | Medium |
| 8 | [How do you test a data pipeline?](https://datadank.com/interview/data-engineering/test-a-data-pipeline/) | Medium |
| 9 | [How would you choose a partitioning strategy for a large table?](https://datadank.com/interview/data-engineering/partition-large-table/) | Medium |
| 10 | [How would you choose an orchestrator for data pipelines?](https://datadank.com/interview/data-engineering/choose-an-orchestrator/) | Medium |
| 11 | [How would you design an idempotent batch pipeline?](https://datadank.com/interview/data-engineering/idempotent-batch-pipeline/) | Medium |
| 12 | [How would you design an incremental load for a large table?](https://datadank.com/interview/data-engineering/design-incremental-load/) | Medium |
| 13 | [How would you investigate a suddenly slower data pipeline?](https://datadank.com/interview/data-engineering/investigate-slow-pipeline/) | Medium |
| 14 | [How would you monitor pipeline freshness and data SLAs?](https://datadank.com/interview/data-engineering/monitor-pipeline-freshness-slas/) | Medium |
| 15 | [What are the most important data-quality checks in production?](https://datadank.com/interview/data-engineering/data-quality-checks/) | Medium |
| 16 | [What does CI/CD look like for data pipelines?](https://datadank.com/interview/data-engineering/cicd-for-data-pipelines/) | Medium |
| 17 | [Exactly-once vs effectively-once: what can a pipeline really guarantee?](https://datadank.com/interview/data-engineering/exactly-once-vs-effectively-once/) | Hard |
| 18 | [How would you design a CDC pipeline?](https://datadank.com/interview/data-engineering/design-cdc-pipeline/) | Hard |

## Apache Kafka

| # | Question | Level |
|---|---|---|
| 1 | [Consumer lag keeps growing. How do you diagnose and fix it?](https://datadank.com/interview/kafka/consumer-lag-causes-fixes/) | Medium |
| 2 | [Explain Kafka partitions and consumer groups.](https://datadank.com/interview/kafka/partitions-and-consumer-groups/) | Medium |
| 3 | [How do acks, replication factor and min.insync.replicas decide Kafka durability?](https://datadank.com/interview/kafka/acks-min-insync-replicas-durability/) | Medium |
| 4 | [How do you choose retention and size disk for a Kafka topic?](https://datadank.com/interview/kafka/retention-sizing/) | Medium |
| 5 | [How do you choose the number of partitions for a Kafka topic?](https://datadank.com/interview/kafka/choose-partition-count/) | Medium |
| 6 | [How do you evolve Kafka message schemas safely with a Schema Registry?](https://datadank.com/interview/kafka/schema-evolution-schema-registry/) | Medium |
| 7 | [How do you handle poison messages and dead-letter topics in Kafka?](https://datadank.com/interview/kafka/poison-messages-dlq/) | Medium |
| 8 | [How does Kafka guarantee message ordering, and where can ordering break?](https://datadank.com/interview/kafka/kafka-ordering-guarantees/) | Medium |
| 9 | [Kafka vs Kinesis vs a message queue: how do you choose?](https://datadank.com/interview/kafka/kafka-vs-kinesis-vs-queues/) | Medium |
| 10 | [What causes consumer group rebalances, and how do you reduce their impact?](https://datadank.com/interview/kafka/rebalancing-problems/) | Medium |
| 11 | [What is KRaft, and why did Kafka 4.0 remove ZooKeeper?](https://datadank.com/interview/kafka/kraft-vs-zookeeper/) | Medium |
| 12 | [What is Kafka log compaction, and when would you use it?](https://datadank.com/interview/kafka/log-compaction-use-cases/) | Medium |
| 13 | [What is at-least-once delivery and what problems can it create?](https://datadank.com/interview/kafka/at-least-once-delivery/) | Medium |
| 14 | [How would you stream database changes into Kafka with Debezium?](https://datadank.com/interview/kafka/cdc-with-debezium/) | Hard |
| 15 | [What does exactly-once mean in Kafka, and how is it achieved?](https://datadank.com/interview/kafka/exactly-once-semantics/) | Hard |

## Apache Airflow

| # | Question | Level |
|---|---|---|
| 1 | [How do you handle task failures and alerting in Airflow?](https://datadank.com/interview/airflow/failure-handling-and-alerting/) | Medium |
| 2 | [How do you make one Airflow DAG depend on another?](https://datadank.com/interview/airflow/cross-dag-dependencies/) | Medium |
| 3 | [How do you test Airflow DAGs before they reach production?](https://datadank.com/interview/airflow/testing-airflow-dags/) | Medium |
| 4 | [How should Airflow retries and idempotency work together?](https://datadank.com/interview/airflow/retries-and-idempotency/) | Medium |
| 5 | [How would you process a variable number of files each day in Airflow?](https://datadank.com/interview/airflow/dynamic-task-mapping/) | Medium |
| 6 | [Poke, reschedule or deferrable: how should an Airflow sensor wait?](https://datadank.com/interview/airflow/sensors-and-deferrable-operators/) | Medium |
| 7 | [What are the logical date and data interval in Airflow, and what changed in Airflow 3?](https://datadank.com/interview/airflow/logical-date-and-data-interval/) | Medium |
| 8 | [What is the difference between catchup and backfill in Airflow 3?](https://datadank.com/interview/airflow/catchup-and-backfill/) | Medium |
| 9 | [When should Airflow tasks pass data through XCom, and when through external storage?](https://datadank.com/interview/airflow/xcom-vs-external-storage/) | Medium |
| 10 | [Airflow is slow and tasks sit in scheduled or queued. How do you find the bottleneck?](https://datadank.com/interview/airflow/slow-scheduler-stuck-tasks/) | Hard |
| 11 | [How do you choose an Airflow executor: Local, Celery, Kubernetes or several?](https://datadank.com/interview/airflow/choosing-an-executor/) | Hard |
| 12 | [What changed in Airflow 3, and how would you migrate Airflow 2 DAGs?](https://datadank.com/interview/airflow/airflow-2-to-3-migration/) | Hard |

## Delta Lake

| # | Question | Level |
|---|---|---|
| 1 | [What is Delta Lake time travel good for, and what are its limits?](https://datadank.com/interview/delta-lake/time-travel-use-cases-limits/) | Easy |
| 2 | [What problems does Delta Lake solve?](https://datadank.com/interview/delta-lake/what-delta-lake-solves/) | Easy |
| 3 | [Delta Lake vs Apache Iceberg vs Apache Hudi: how do they differ?](https://datadank.com/interview/delta-lake/delta-vs-iceberg-vs-hudi/) | Medium |
| 4 | [How does Delta Lake MERGE work, and why do concurrent MERGEs fail?](https://datadank.com/interview/delta-lake/delta-merge-internals-conflicts/) | Medium |
| 5 | [How is a Parquet file organised, and how does that speed up queries?](https://datadank.com/interview/delta-lake/parquet-internals/) | Medium |
| 6 | [OPTIMIZE, Z-ORDER or liquid clustering: which would you use on a Delta table?](https://datadank.com/interview/delta-lake/optimize-zorder-vs-liquid-clustering/) | Medium |
| 7 | [What does VACUUM do in Delta Lake, and what can go wrong?](https://datadank.com/interview/delta-lake/vacuum-retention-risks/) | Medium |
| 8 | [What is schema evolution and when is it safe?](https://datadank.com/interview/delta-lake/schema-evolution-safety/) | Medium |

## Databricks

| # | Question | Level |
|---|---|---|
| 1 | [What is Unity Catalog used for?](https://datadank.com/interview/databricks/unity-catalog/) | Easy |
| 2 | [Auto Loader vs COPY INTO: how would you ingest files on Databricks?](https://datadank.com/interview/databricks/auto-loader-vs-copy-into/) | Medium |
| 3 | [Which Databricks compute should you use for each workload?](https://datadank.com/interview/databricks/choose-databricks-compute/) | Medium |

## Snowflake

| # | Question | Level |
|---|---|---|
| 1 | [What are Snowflake virtual warehouses?](https://datadank.com/interview/snowflake/virtual-warehouses/) | Easy |
| 2 | [What caches does Snowflake use, and when does each one help?](https://datadank.com/interview/snowflake/caching-layers/) | Easy |
| 3 | [What is the difference between Snowflake Time Travel and Fail-safe?](https://datadank.com/interview/snowflake/time-travel-vs-fail-safe/) | Easy |
| 4 | [What is zero-copy cloning in Snowflake, and how would you use it?](https://datadank.com/interview/snowflake/zero-copy-clone-uses/) | Easy |
| 5 | [How do micro-partitions affect Snowflake query performance?](https://datadank.com/interview/snowflake/micro-partitions-performance/) | Medium |
| 6 | [How do you build an incremental pipeline with Snowflake streams and tasks?](https://datadank.com/interview/snowflake/streams-tasks-incremental-pipeline/) | Medium |
| 7 | [Should you scale a Snowflake warehouse up or out?](https://datadank.com/interview/snowflake/warehouse-sizing-vs-multi-cluster/) | Medium |
| 8 | [When should you define a clustering key on a Snowflake table?](https://datadank.com/interview/snowflake/when-to-use-clustering-keys/) | Medium |

## AWS

| # | Question | Level |
|---|---|---|
| 1 | [AWS Glue vs Amazon EMR vs EMR Serverless: which would you use for Spark?](https://datadank.com/interview/aws/glue-vs-emr-vs-emr-serverless/) | Medium |
| 2 | [How do you build reliable event-driven ingestion from S3 when events can be duplicated or late?](https://datadank.com/interview/aws/s3-event-driven-ingestion/) | Medium |
| 3 | [How do you choose Redshift distribution styles and sort keys?](https://datadank.com/interview/aws/redshift-distribution-sort-keys/) | Medium |
| 4 | [How do you give a data pipeline least-privilege IAM access, including cross-account?](https://datadank.com/interview/aws/iam-least-privilege-cross-account/) | Medium |
| 5 | [How do you reduce Amazon Athena query cost and make queries faster?](https://datadank.com/interview/aws/athena-cost-performance-tuning/) | Medium |
| 6 | [How would you cut the AWS bill of a data platform without breaking SLAs?](https://datadank.com/interview/aws/aws-data-platform-cost-optimization/) | Medium |
| 7 | [How would you design the S3 layout and partitioning for a data lake?](https://datadank.com/interview/aws/s3-data-lake-layout/) | Medium |
| 8 | [Kinesis Data Streams or Amazon MSK: which would you pick for streaming on AWS?](https://datadank.com/interview/aws/kinesis-data-streams-vs-msk/) | Medium |
| 9 | [Step Functions or Airflow on MWAA: how do you choose an orchestrator on AWS?](https://datadank.com/interview/aws/step-functions-vs-airflow-mwaa/) | Medium |
| 10 | [When is AWS Lambda a good fit for ETL, and what limits push you to Glue or containers?](https://datadank.com/interview/aws/lambda-for-etl-limits/) | Medium |
| 11 | [Lake Formation permissions vs IAM and S3 bucket policies: how do they work together?](https://datadank.com/interview/aws/lake-formation-vs-iam-s3-policies/) | Hard |

## DSA for Data Engineers

| # | Question | Level |
|---|---|---|
| 1 | [Backspace String Compare: Read Both Strings Backwards With Skip Counters](https://datadank.com/interview/dsa/backspace-string-compare/) | Easy |
| 2 | [Balanced Binary Tree: Height Check with Early Exit](https://datadank.com/interview/dsa/balanced-binary-tree/) | Easy |
| 3 | [Best Time to Buy and Sell Stock: Maximum Profit From One Trade](https://datadank.com/interview/dsa/best-time-to-buy-and-sell-stock/) | Easy |
| 4 | [Binary Search: Find a Target in a Sorted Array in O(log n)](https://datadank.com/interview/dsa/binary-search/) | Easy |
| 5 | [Ceil in Sorted Array: Lower-Bound Binary Search](https://datadank.com/interview/dsa/ceil-in-a-sorted-array/) | Easy |
| 6 | [Climbing Stairs: Count Ways with a Fibonacci-Style DP](https://datadank.com/interview/dsa/climbing-stairs/) | Easy |
| 7 | [Complement of Base 10 Integer: Flip Bits With an All-Ones Mask](https://datadank.com/interview/dsa/complement-of-base-10-integer/) | Easy |
| 8 | [Contains Duplicate: Detect Whether Any Value Appears Twice](https://datadank.com/interview/dsa/contains-duplicate/) | Easy |
| 9 | [Convert Sorted Array to BST: Pick the Middle, Recurse on Halves](https://datadank.com/interview/dsa/convert-sorted-array-to-bst/) | Easy |
| 10 | [Counting Bits: Set-Bit Counts for 0 to n with a One-Line DP](https://datadank.com/interview/dsa/counting-bits/) | Easy |
| 11 | [Diameter of Binary Tree: Longest Path via Post-Order Heights](https://datadank.com/interview/dsa/diameter-of-binary-tree/) | Easy |
| 12 | [Find All Numbers Disappeared in an Array: Cyclic Sort and In-Place Marking](https://datadank.com/interview/dsa/find-all-numbers-disappeared-in-an-array/) | Easy |
| 13 | [Find Pivot Index: Balance Left and Right Prefix Sums](https://datadank.com/interview/dsa/find-pivot-index/) | Easy |
| 14 | [Find Rotation Count: The Index of the Minimum Is the Answer](https://datadank.com/interview/dsa/find-rotation-count/) | Easy |
| 15 | [Find if Path Exists in Graph: Reachability with BFS or Union-Find](https://datadank.com/interview/dsa/find-if-path-exists-in-graph/) | Easy |
| 16 | [First Unique Character in a String: Count, Then Scan Again](https://datadank.com/interview/dsa/first-unique-character-in-a-string/) | Easy |
| 17 | [Flood Fill: Repaint a Connected Region with DFS or BFS](https://datadank.com/interview/dsa/flood-fill/) | Easy |
| 18 | [Happy Number: Detect a Cycle in a Digit-Square Sequence](https://datadank.com/interview/dsa/happy-number/) | Easy |
| 19 | [Implement Queue using Stacks: FIFO With Two Stacks in Amortised O(1)](https://datadank.com/interview/dsa/implement-queue-using-stacks/) | Easy |
| 20 | [Implement Stack using Queues: LIFO Behaviour From FIFO Parts](https://datadank.com/interview/dsa/implement-stack-using-queues/) | Easy |
| 21 | [Invert Binary Tree: Recursive and Iterative Mirror Solutions](https://datadank.com/interview/dsa/invert-binary-tree/) | Easy |
| 22 | [Island Perimeter: Count Land Edges Without a Traversal](https://datadank.com/interview/dsa/island-perimeter/) | Easy |
| 23 | [Kth Largest Element in a Stream: Size-k Min-Heap](https://datadank.com/interview/dsa/kth-largest-element-in-a-stream/) | Easy |
| 24 | [Last Stone Weight: Simulating Smashes with a Max-Heap](https://datadank.com/interview/dsa/last-stone-weight/) | Easy |
| 25 | [Linked List Cycle: Floyd's Fast and Slow Pointers](https://datadank.com/interview/dsa/linked-list-cycle/) | Easy |
| 26 | [Longest Common Prefix: Shared Start of a List of Strings](https://datadank.com/interview/dsa/longest-common-prefix/) | Easy |
| 27 | [Longest Palindrome: Pair Up Letter Counts and Keep One Centre](https://datadank.com/interview/dsa/longest-palindrome/) | Easy |
| 28 | [Majority Element: Find the Value That Fills More Than Half the Array](https://datadank.com/interview/dsa/majority-element/) | Easy |
| 29 | [Max Sum Subarray of Size K: The Fixed-Size Sliding Window](https://datadank.com/interview/dsa/max-sum-subarray-of-size-k/) | Easy |
| 30 | [Maximum Depth of Binary Tree: Recursive DFS, Iterative DFS and BFS](https://datadank.com/interview/dsa/maximum-depth-of-binary-tree/) | Easy |
| 31 | [Meeting Rooms: Check Whether One Person Can Attend Every Meeting](https://datadank.com/interview/dsa/attend-all-meetings/) | Easy |
| 32 | [Merge Two Sorted Lists: Dummy Head Iteration and Recursion](https://datadank.com/interview/dsa/merge-two-sorted-lists/) | Easy |
| 33 | [Middle of the Linked List: Find It in One Pass With Fast and Slow Pointers](https://datadank.com/interview/dsa/middle-of-the-linked-list/) | Easy |
| 34 | [Min Cost Climbing Stairs: Cheapest Path to the Top with 1D DP](https://datadank.com/interview/dsa/min-cost-climbing-stairs/) | Easy |
| 35 | [Missing Number: Find the One Value Absent From 0 to n](https://datadank.com/interview/dsa/missing-number/) | Easy |
| 36 | [Move Zeroes: Shift Zeros to the End While Keeping Order](https://datadank.com/interview/dsa/move-zeroes/) | Easy |
| 37 | [Next Greater Element I: First Larger Value to the Right](https://datadank.com/interview/dsa/next-greater-element-i/) | Easy |
| 38 | [Number of 1 Bits: Count Set Bits in an Integer](https://datadank.com/interview/dsa/number-of-1-bits/) | Easy |
| 39 | [Number of Occurrence: Count a Value with Two Boundary Searches](https://datadank.com/interview/dsa/number-of-occurrence/) | Easy |
| 40 | [Number of Recent Calls: Count Requests in a Sliding Time Window](https://datadank.com/interview/dsa/number-of-recent-calls/) | Easy |
| 41 | [Palindrome Linked List: Find the Middle, Reverse the Back Half, Compare](https://datadank.com/interview/dsa/palindrome-linked-list/) | Easy |
| 42 | [Ransom Note: Check Letter Supply Against Demand With a Counter](https://datadank.com/interview/dsa/ransom-note/) | Easy |
| 43 | [Remove All Adjacent Duplicates In String: Cancel Pairs With a Stack](https://datadank.com/interview/dsa/remove-all-adjacent-duplicates-in-string/) | Easy |
| 44 | [Remove Duplicates from Sorted Array: Compact Unique Values In Place](https://datadank.com/interview/dsa/remove-duplicates-from-sorted-array/) | Easy |
| 45 | [Reverse Bits: Mirror the 32 Bits of an Unsigned Integer](https://datadank.com/interview/dsa/reverse-bits/) | Easy |
| 46 | [Reverse Linked List: Iterative and Recursive Solutions](https://datadank.com/interview/dsa/reverse-linked-list/) | Easy |
| 47 | [Reverse String: Reverse a Character Array in Place](https://datadank.com/interview/dsa/reverse-string/) | Easy |
| 48 | [Same Tree: Comparing Two Binary Trees Recursively and Iteratively](https://datadank.com/interview/dsa/same-tree/) | Easy |
| 49 | [Segregate 0s and 1s: Partition a Binary Array in One Pass](https://datadank.com/interview/dsa/segregate-0s-and-1s/) | Easy |
| 50 | [Set Mismatch: Find the Duplicate and the Missing Number With Cyclic Sort](https://datadank.com/interview/dsa/set-mismatch/) | Easy |
| 51 | [Single Number: Find the Value That Appears Only Once Using XOR](https://datadank.com/interview/dsa/single-number/) | Easy |
| 52 | [Squares of a Sorted Array: Merge From Both Ends Without Sorting](https://datadank.com/interview/dsa/squares-of-a-sorted-array/) | Easy |
| 53 | [Subtree of Another Tree: Brute-Force Matching and Linear Serialisation](https://datadank.com/interview/dsa/subtree-of-another-tree/) | Easy |
| 54 | [Two Sum: Find Two Indices That Add Up to a Target](https://datadank.com/interview/dsa/two-sum/) | Easy |
| 55 | [Valid Anagram: Check Whether Two Strings Use the Same Letters](https://datadank.com/interview/dsa/valid-anagram/) | Easy |
| 56 | [Valid Palindrome II: Palindrome After Deleting at Most One Character](https://datadank.com/interview/dsa/valid-palindrome-ii/) | Easy |
| 57 | [Valid Palindrome: Check a Phrase While Ignoring Case and Punctuation](https://datadank.com/interview/dsa/valid-palindrome/) | Easy |
| 58 | [Valid Parentheses: Check That Every Bracket Closes in the Right Order](https://datadank.com/interview/dsa/valid-parentheses/) | Easy |
| 59 | [0 - 1 Knapsack Problem: Take or Skip Each Item Once](https://datadank.com/interview/dsa/0-1-knapsack-problem/) | Medium |
| 60 | [132 Pattern: Find a Low, High, Middle Subsequence in One Pass](https://datadank.com/interview/dsa/132-pattern/) | Medium |
| 61 | [3Sum Closest: Sort, Fix One Value, and Squeeze Two Pointers](https://datadank.com/interview/dsa/3sum-closest/) | Medium |
| 62 | [3Sum: Find All Unique Triplets That Sum to Zero](https://datadank.com/interview/dsa/3sum/) | Medium |
| 63 | [4Sum: Two Fixed Indices, Two Pointers and Careful Duplicate Skipping](https://datadank.com/interview/dsa/4sum/) | Medium |
| 64 | [Add Two Numbers: Digit-by-Digit Addition on Linked Lists](https://datadank.com/interview/dsa/add-two-numbers/) | Medium |
| 65 | [Aggressive Cows: Maximise the Minimum Gap with Binary Search](https://datadank.com/interview/dsa/aggressive-cows/) | Medium |
| 66 | [Best Time to Buy and Sell Stock with Cooldown: State-Machine DP](https://datadank.com/interview/dsa/best-time-to-buy-sell-with-cooldown/) | Medium |
| 67 | [Binary Tree Level Order Traversal: BFS with a Queue, Level by Level](https://datadank.com/interview/dsa/binary-tree-level-order-traversal/) | Medium |
| 68 | [Binary Tree Right Side View: Last Node of Each Level](https://datadank.com/interview/dsa/binary-tree-right-side-view/) | Medium |
| 69 | [Capacity To Ship Packages Within D Days: Binary Search on Capacity](https://datadank.com/interview/dsa/capacity-to-ship-packages-within-d-days/) | Medium |
| 70 | [Car Fleet: Count the Groups of Cars Arriving at a Destination](https://datadank.com/interview/dsa/car-fleet/) | Medium |
| 71 | [Cheapest Flights Within K Stops: Bounded Bellman-Ford for Limited Hops](https://datadank.com/interview/dsa/cheapest-flights-within-k-stops/) | Medium |
| 72 | [Circular Array Loop: Fast and Slow Pointers on Index Jumps](https://datadank.com/interview/dsa/circular-array-loop/) | Medium |
| 73 | [Clone Graph: Deep-Copy a Connected Graph with a Hash Map and BFS or DFS](https://datadank.com/interview/dsa/clone-graph/) | Medium |
| 74 | [Coin Change II: Count Combinations That Make an Amount](https://datadank.com/interview/dsa/coin-change-ii/) | Medium |
| 75 | [Coin Change: Fewest Coins with Bottom-Up DP](https://datadank.com/interview/dsa/coin-change/) | Medium |
| 76 | [Combination Sum II: Use Each Value Once and Avoid Duplicate Answers](https://datadank.com/interview/dsa/combination-sum-ii/) | Medium |
| 77 | [Combination Sum: Reach a Target with Reusable Values via Backtracking](https://datadank.com/interview/dsa/combination-sum/) | Medium |
| 78 | [Construct Binary Tree from Preorder and Inorder Traversal](https://datadank.com/interview/dsa/construct-tree-from-preorder-and-inorder/) | Medium |
| 79 | [Container With Most Water: Maximise Area Between Two Lines](https://datadank.com/interview/dsa/container-with-most-water/) | Medium |
| 80 | [Contiguous Array: Longest Balanced 0/1 Subarray via Prefix Sums](https://datadank.com/interview/dsa/contiguous-array/) | Medium |
| 81 | [Copy List with Random Pointer: Hash Map and Interleaving Solutions](https://datadank.com/interview/dsa/copy-list-with-random-pointer/) | Medium |
| 82 | [Count Good Nodes in Binary Tree: DFS Carrying the Path Maximum](https://datadank.com/interview/dsa/count-good-nodes-in-binary-tree/) | Medium |
| 83 | [Count Subsets with Sum: Add Up the Ways, Not Just True or False](https://datadank.com/interview/dsa/perfect-sum-problem/) | Medium |
| 84 | [Course Schedule II: Return a Valid Course Order with Topological Sort](https://datadank.com/interview/dsa/course-schedule-ii/) | Medium |
| 85 | [Course Schedule: Detect a Cycle in a Prerequisite Graph with Kahn's Algorithm](https://datadank.com/interview/dsa/course-schedule/) | Medium |
| 86 | [Daily Temperatures: Days Until a Warmer Day With a Monotonic Stack](https://datadank.com/interview/dsa/daily-temperatures/) | Medium |
| 87 | [Decode Ways: Count Digit-to-Letter Decodings with Prefix DP](https://datadank.com/interview/dsa/decode-ways/) | Medium |
| 88 | [Delete Node in a BST: Leaf, One Child and Two Children Cases](https://datadank.com/interview/dsa/delete-node-in-a-bst/) | Medium |
| 89 | [Design Add and Search Words: Trie Search with Wildcards](https://datadank.com/interview/dsa/design-add-and-search-words/) | Medium |
| 90 | [Design Circular Queue: A Fixed-Capacity Ring Buffer](https://datadank.com/interview/dsa/design-circular-queue/) | Medium |
| 91 | [Design Twitter: News Feed with a K-Way Heap Merge](https://datadank.com/interview/dsa/design-twitter/) | Medium |
| 92 | [Edit Distance: Levenshtein Distance with a 2D DP Table](https://datadank.com/interview/dsa/edit-distance/) | Medium |
| 93 | [Encode and Decode Strings: Serialise a List of Strings Safely](https://datadank.com/interview/dsa/encode-and-decode-strings/) | Medium |
| 94 | [Evaluate Reverse Polish Notation: Compute a Postfix Expression](https://datadank.com/interview/dsa/evaluate-reverse-polish-notation/) | Medium |
| 95 | [Extra Characters in a String: Dynamic Programming over a Trie of Words](https://datadank.com/interview/dsa/extra-characters-in-a-string/) | Medium |
| 96 | [Find All Anagrams in a String: Fixed Window With Letter Counts](https://datadank.com/interview/dsa/find-all-anagrams-in-a-string/) | Medium |
| 97 | [Find All Duplicates in an Array: Cyclic Sort and Sign Marking in O(1) Space](https://datadank.com/interview/dsa/find-all-duplicates-in-an-array/) | Medium |
| 98 | [Find First and Last Position of a Value: Lower and Upper Bound Binary Search](https://datadank.com/interview/dsa/find-first-and-last-position/) | Medium |
| 99 | [Find K Closest Elements: Binary Search for the Best Window](https://datadank.com/interview/dsa/find-k-closest-elements/) | Medium |
| 100 | [Find Minimum in Rotated Sorted Array: Binary Search Against the Right End](https://datadank.com/interview/dsa/find-minimum-in-rotated-sorted-array/) | Medium |
| 101 | [Find Peak Element: Follow the Uphill Side with Binary Search](https://datadank.com/interview/dsa/find-peak-element/) | Medium |
| 102 | [Find the Duplicate Number: Cycle Detection on an Array](https://datadank.com/interview/dsa/find-the-duplicate-number/) | Medium |
| 103 | [Fruit Into Baskets: Longest Window With at Most Two Distinct Values](https://datadank.com/interview/dsa/fruit-into-baskets/) | Medium |
| 104 | [Gas Station: Find the Start of a Circular Route in One Greedy Pass](https://datadank.com/interview/dsa/gas-station/) | Medium |
| 105 | [Generate Parentheses: List Every Balanced String of n Pairs](https://datadank.com/interview/dsa/generate-parentheses/) | Medium |
| 106 | [Graph Valid Tree: Check Edge Count, Connectivity and Cycles with Union-Find](https://datadank.com/interview/dsa/graph-valid-tree/) | Medium |
| 107 | [Group Anagrams: Bucket Words That Share the Same Letters](https://datadank.com/interview/dsa/group-anagrams/) | Medium |
| 108 | [Hand of Straights: Group Cards into Consecutive Runs Greedily](https://datadank.com/interview/dsa/hand-of-straights/) | Medium |
| 109 | [House Robber II: Non-Adjacent Maximum Sum When Houses Form a Circle](https://datadank.com/interview/dsa/house-robber-ii/) | Medium |
| 110 | [House Robber: Maximum Non-Adjacent Sum with Take-or-Skip DP](https://datadank.com/interview/dsa/house-robber/) | Medium |
| 111 | [Implement Trie (Prefix Tree): Insert, Search and Prefix Lookup](https://datadank.com/interview/dsa/implement-trie-prefix-tree/) | Medium |
| 112 | [Insert Interval: Add a Range to a Sorted List and Merge Overlaps](https://datadank.com/interview/dsa/insert-interval/) | Medium |
| 113 | [Insert into a BST: Walk Down to the Empty Spot](https://datadank.com/interview/dsa/insert-into-a-bst/) | Medium |
| 114 | [Interleaving String: Can Two Strings Merge into a Third? 2D DP](https://datadank.com/interview/dsa/interleaving-string/) | Medium |
| 115 | [Interval List Intersections: Two Pointers over Sorted Ranges](https://datadank.com/interview/dsa/interval-list-intersections/) | Medium |
| 116 | [Is Graph Bipartite?: Two-Colour Every Component](https://datadank.com/interview/dsa/is-graph-bipartite/) | Medium |
| 117 | [Jump Game II: Fewest Jumps to the End with Greedy Level-by-Level BFS](https://datadank.com/interview/dsa/jump-game-ii/) | Medium |
| 118 | [Jump Game: Can You Reach the Last Index? Greedy Furthest Reach](https://datadank.com/interview/dsa/jump-game/) | Medium |
| 119 | [K Closest Points to Origin: Bounded Max-Heap and Quickselect](https://datadank.com/interview/dsa/k-closest-points-to-origin/) | Medium |
| 120 | [Koko Eating Bananas: Binary Search on the Answer](https://datadank.com/interview/dsa/koko-eating-bananas/) | Medium |
| 121 | [Kth Largest Element in an Array: Heap, Quickselect and Counting](https://datadank.com/interview/dsa/kth-largest-element-in-an-array/) | Medium |
| 122 | [Kth Smallest Element in a BST: Inorder Traversal with Early Stop](https://datadank.com/interview/dsa/kth-smallest-element-in-a-bst/) | Medium |
| 123 | [Kth Smallest Element in a Sorted Matrix: Binary Search on Values](https://datadank.com/interview/dsa/kth-smallest-element-in-a-sorted-matrix/) | Medium |
| 124 | [LRU Cache: Hash Map Plus Doubly Linked List for O(1) Operations](https://datadank.com/interview/dsa/lru-cache/) | Medium |
| 125 | [Letter Case Permutation: Branch Twice on Every Letter](https://datadank.com/interview/dsa/letter-case-permutation/) | Medium |
| 126 | [Letter Combinations of a Phone Number: Cartesian Product by Backtracking](https://datadank.com/interview/dsa/letter-combinations-of-a-phone-number/) | Medium |
| 127 | [Linked List Cycle II: Find Where the Cycle Starts With Floyd's Algorithm](https://datadank.com/interview/dsa/linked-list-cycle-ii/) | Medium |
| 128 | [Longest Common Subsequence: The Classic Two-String DP Table](https://datadank.com/interview/dsa/longest-common-subsequence/) | Medium |
| 129 | [Longest Consecutive Sequence: Longest Run of Consecutive Integers in O(n)](https://datadank.com/interview/dsa/longest-consecutive-sequence/) | Medium |
| 130 | [Longest Increasing Subsequence: O(n^2) DP and O(n log n) Patience Sorting](https://datadank.com/interview/dsa/longest-increasing-subsequence/) | Medium |
| 131 | [Longest K Unique Characters Substring: A Window Bounded by a Distinct Count](https://datadank.com/interview/dsa/longest-k-unique-characters-substring/) | Medium |
| 132 | [Longest Palindromic Substring: Expand Around Centres or Interval DP](https://datadank.com/interview/dsa/longest-palindromic-substring/) | Medium |
| 133 | [Longest Repeating Character Replacement: Window With At Most k Changes](https://datadank.com/interview/dsa/longest-repeating-character-replacement/) | Medium |
| 134 | [Longest Substring Without Repeating Characters: Sliding Window](https://datadank.com/interview/dsa/longest-substring-without-repeating-characters/) | Medium |
| 135 | [Lowest Common Ancestor of a BST: Follow the Split Point](https://datadank.com/interview/dsa/lowest-common-ancestor-of-a-bst/) | Medium |
| 136 | [Lowest Common Ancestor of a Binary Tree: One Post-Order Search](https://datadank.com/interview/dsa/lowest-common-ancestor-of-binary-tree/) | Medium |
| 137 | [Max Area of Island: Largest Connected Land Region with Flood Fill](https://datadank.com/interview/dsa/max-area-of-island/) | Medium |
| 138 | [Max Consecutive Ones III: Longest Window With at Most K Zeros](https://datadank.com/interview/dsa/max-consecutive-ones-iii/) | Medium |
| 139 | [Maximum Absolute Sum of Any Subarray: Run Kadane for Max and Min](https://datadank.com/interview/dsa/maximum-absolute-sum-of-any-subarray/) | Medium |
| 140 | [Maximum Candies Allocated to K Children: Binary Search on the Share](https://datadank.com/interview/dsa/maximum-candies-allocated-to-k-children/) | Medium |
| 141 | [Maximum Length of Pair Chain: Greedy by Earliest End](https://datadank.com/interview/dsa/maximum-length-of-pair-chain/) | Medium |
| 142 | [Maximum Product Subarray: Track Both the Largest and Smallest Product](https://datadank.com/interview/dsa/maximum-product-subarray/) | Medium |
| 143 | [Maximum Subarray Sum with One Deletion: Kadane With Two States](https://datadank.com/interview/dsa/maximum-subarray-sum-with-one-deletion/) | Medium |
| 144 | [Maximum Subarray: Largest Sum of a Contiguous Slice with Kadane's Algorithm](https://datadank.com/interview/dsa/maximum-subarray/) | Medium |
| 145 | [Maximum Sum Circular Subarray: Kadane Plus Total Minus Minimum](https://datadank.com/interview/dsa/maximum-sum-circular-subarray/) | Medium |
| 146 | [Maximum Sum Combination: The K Largest Pair Sums with a Max-Heap](https://datadank.com/interview/dsa/maximum-sum-combination/) | Medium |
| 147 | [Meeting Rooms II: Count the Rooms with a Min-Heap or a Sweep Line](https://datadank.com/interview/dsa/attend-all-meetings-ii/) | Medium |
| 148 | [Merge Intervals: Combine Every Overlapping Range](https://datadank.com/interview/dsa/merge-intervals/) | Medium |
| 149 | [Merge Triplets to Form Target: Keep Only Triplets That Never Overshoot](https://datadank.com/interview/dsa/merge-triplets-to-form-target/) | Medium |
| 150 | [Min Cost to Connect All Points: Minimum Spanning Tree with Prim or Kruskal](https://datadank.com/interview/dsa/min-cost-to-connect-all-points/) | Medium |
| 151 | [Min Cost to Connect Ropes: Always Join the Two Shortest](https://datadank.com/interview/dsa/minimum-cost-of-ropes/) | Medium |
| 152 | [Min Stack: A Stack That Returns Its Minimum in Constant Time](https://datadank.com/interview/dsa/min-stack/) | Medium |
| 153 | [Minimum Add to Make Parentheses Valid: Count Unmatched Brackets in One Pass](https://datadank.com/interview/dsa/minimum-add-to-make-parentheses-valid/) | Medium |
| 154 | [Minimum Height Trees: Trim Leaves Until the Centre Remains](https://datadank.com/interview/dsa/minimum-height-trees/) | Medium |
| 155 | [Minimum Number of Days to Make m Bouquets: Binary Search on the Day](https://datadank.com/interview/dsa/minimum-number-of-days-to-make-m-bouquets/) | Medium |
| 156 | [Minimum Size Subarray Sum: Grow Until Valid, Then Shrink](https://datadank.com/interview/dsa/minimum-size-subarray-sum/) | Medium |
| 157 | [My Calendar I: Accept Bookings Only When They Do Not Overlap](https://datadank.com/interview/dsa/my-calendar-i/) | Medium |
| 158 | [Network Delay Time: Single-Source Shortest Paths with Dijkstra's Algorithm](https://datadank.com/interview/dsa/network-delay-time/) | Medium |
| 159 | [Next Greater Element II: Monotonic Stack Over a Circular Array](https://datadank.com/interview/dsa/next-greater-element-ii/) | Medium |
| 160 | [Non-overlapping Intervals: Fewest Removals to Eliminate Overlaps](https://datadank.com/interview/dsa/non-overlapping-intervals/) | Medium |
| 161 | [Number of Closed Islands: Sink the Border, Then Count](https://datadank.com/interview/dsa/number-of-closed-islands/) | Medium |
| 162 | [Number of Connected Components in an Undirected Graph with Union-Find](https://datadank.com/interview/dsa/number-of-connected-components/) | Medium |
| 163 | [Number of Islands: Count Connected Land Cells with BFS, DFS or Union-Find](https://datadank.com/interview/dsa/number-of-islands/) | Medium |
| 164 | [Number of Provinces: Count Components in an Adjacency Matrix](https://datadank.com/interview/dsa/number-of-provinces/) | Medium |
| 165 | [Pacific Atlantic Water Flow: Reverse Multi-Source BFS from Both Oceans](https://datadank.com/interview/dsa/pacific-atlantic-water-flow/) | Medium |
| 166 | [Palindrome Partitioning: Split a String into Palindromes by Backtracking](https://datadank.com/interview/dsa/palindrome-partitioning/) | Medium |
| 167 | [Palindromic Substrings: Count Every Palindrome by Expanding Around Centres](https://datadank.com/interview/dsa/palindromic-substrings/) | Medium |
| 168 | [Partition Equal Subset Sum: 0/1 Knapsack on Half the Total](https://datadank.com/interview/dsa/partition-equal-subset-sum/) | Medium |
| 169 | [Partition Labels: Split a String So Each Letter Stays in One Part](https://datadank.com/interview/dsa/partition-labels/) | Medium |
| 170 | [Path With Minimum Effort: Minimise the Largest Step on a Grid](https://datadank.com/interview/dsa/path-with-minimum-effort/) | Medium |
| 171 | [Peak Index in a Mountain Array: Binary Search on the Slope](https://datadank.com/interview/dsa/peak-index-in-a-mountain-array/) | Medium |
| 172 | [Permutation in String: Does One String Contain a Rearrangement of Another?](https://datadank.com/interview/dsa/permutation-in-string/) | Medium |
| 173 | [Permutations: Every Ordering of Distinct Values with Backtracking](https://datadank.com/interview/dsa/permutations/) | Medium |
| 174 | [Product of Array Except Self: Prefix and Suffix Products Without Division](https://datadank.com/interview/dsa/product-of-array-except-self/) | Medium |
| 175 | [Redundant Connection: Find the Edge That Closes a Cycle with Union-Find](https://datadank.com/interview/dsa/redundant-connection/) | Medium |
| 176 | [Remove All Adjacent Duplicates in String II: Stack of Character Counts](https://datadank.com/interview/dsa/remove-all-adjacent-duplicates-in-string-ii/) | Medium |
| 177 | [Remove Duplicate Letters: Smallest Order with a Greedy Monotonic Stack](https://datadank.com/interview/dsa/remove-duplicate-letters/) | Medium |
| 178 | [Remove K Digits: Smallest Number With a Greedy Monotonic Stack](https://datadank.com/interview/dsa/remove-k-digits/) | Medium |
| 179 | [Remove Nodes From Linked List: Keep Nodes With Nothing Larger to Their Right](https://datadank.com/interview/dsa/remove-nodes-from-linked-list/) | Medium |
| 180 | [Remove Nth Node From End of List: One Pass with a Gap of n](https://datadank.com/interview/dsa/remove-nth-node-from-end-of-list/) | Medium |
| 181 | [Reorder List: Find the Middle, Reverse, Then Interleave](https://datadank.com/interview/dsa/reorder-list/) | Medium |
| 182 | [Reorganize String: Place the Most Frequent Character First, Never Twice in a Row](https://datadank.com/interview/dsa/reorganize-string/) | Medium |
| 183 | [Reverse Linked List II: Reverse a Sublist in One Pass With a Dummy Node](https://datadank.com/interview/dsa/reverse-linked-list-ii/) | Medium |
| 184 | [Rotate Image: Turn a Square Matrix 90 Degrees Clockwise in Place](https://datadank.com/interview/dsa/rotate-image/) | Medium |
| 185 | [Rotate List: Close the Ring, Then Cut It at the New Tail](https://datadank.com/interview/dsa/rotate-list/) | Medium |
| 186 | [Rotting Oranges: Minutes to Spread via Level-by-Level Multi-Source BFS](https://datadank.com/interview/dsa/rotting-oranges/) | Medium |
| 187 | [Search Suggestions System: Autocomplete with a Trie or Sorted Binary Search](https://datadank.com/interview/dsa/search-suggestions-system/) | Medium |
| 188 | [Search a 2D Matrix II: Staircase Search from the Top-Right Corner](https://datadank.com/interview/dsa/search-a-2d-matrix-ii/) | Medium |
| 189 | [Search a 2D Matrix: Binary Search over a Flattened Sorted Grid](https://datadank.com/interview/dsa/search-a-2d-matrix/) | Medium |
| 190 | [Search in Rotated Sorted Array: One-Pass Binary Search](https://datadank.com/interview/dsa/search-in-rotated-sorted-array/) | Medium |
| 191 | [Set Matrix Zeroes: Zero Out Rows and Columns in Place](https://datadank.com/interview/dsa/set-matrix-zeroes/) | Medium |
| 192 | [Shortest Unsorted Continuous Subarray: Find the Boundaries With Running Max and Min](https://datadank.com/interview/dsa/shortest-unsorted-continuous-subarray/) | Medium |
| 193 | [Simplify Path: Canonical Unix Paths With a Stack of Directory Names](https://datadank.com/interview/dsa/simplify-path/) | Medium |
| 194 | [Single Number III: Split Two Unique Values With One XOR Bit](https://datadank.com/interview/dsa/single-number-iii/) | Medium |
| 195 | [Sort Characters By Frequency: Count, Then Order by a Heap or Buckets](https://datadank.com/interview/dsa/sort-characters-by-frequency/) | Medium |
| 196 | [Sort Colors: One-Pass Three-Way Partition of 0s, 1s and 2s](https://datadank.com/interview/dsa/sort-colors/) | Medium |
| 197 | [Spiral Matrix: Read a Grid in Clockwise Spiral Order](https://datadank.com/interview/dsa/spiral-matrix/) | Medium |
| 198 | [String to Integer (atoi): Parse a Signed 32-bit Integer by Hand](https://datadank.com/interview/dsa/string-to-integer-atoi/) | Medium |
| 199 | [Subarray Product Less Than K: Count Windows Ending at Each Index](https://datadank.com/interview/dsa/subarray-product-less-than-k/) | Medium |
| 200 | [Subarray Sum Equals K: Count Contiguous Slices With a Given Sum](https://datadank.com/interview/dsa/subarray-sum-equals-k/) | Medium |
| 201 | [Subarray Sums Divisible by K: Count Matching Prefix Remainders](https://datadank.com/interview/dsa/subarray-sums-divisible-by-k/) | Medium |
| 202 | [Subset Sum Problem: Track Every Reachable Total](https://datadank.com/interview/dsa/subset-sum-problem/) | Medium |
| 203 | [Subsets II: Power Set Without Duplicates When Values Repeat](https://datadank.com/interview/dsa/subsets-ii/) | Medium |
| 204 | [Subsets: Generate the Power Set with Include/Exclude Backtracking](https://datadank.com/interview/dsa/subsets/) | Medium |
| 205 | [Sum of Two Integers: Add Without the Plus or Minus Operator](https://datadank.com/interview/dsa/sum-of-two-integers/) | Medium |
| 206 | [Surrounded Regions: Capture Enclosed Cells by Flood-Filling from the Border](https://datadank.com/interview/dsa/surrounded-regions/) | Medium |
| 207 | [Swap Nodes in Pairs: Rewire Every Two Nodes With a Dummy Head](https://datadank.com/interview/dsa/swap-nodes-in-pairs/) | Medium |
| 208 | [Target Sum: Count Sign Assignments with Subset-Sum DP](https://datadank.com/interview/dsa/target-sum/) | Medium |
| 209 | [Task Scheduler: Cooldowns with a Max-Heap or a Counting Formula](https://datadank.com/interview/dsa/task-scheduler/) | Medium |
| 210 | [Time Based Key-Value Store: Versioned Lookups with Binary Search](https://datadank.com/interview/dsa/time-based-key-value-store/) | Medium |
| 211 | [Top K Frequent Elements: Return the k Most Common Values](https://datadank.com/interview/dsa/top-k-frequent-elements/) | Medium |
| 212 | [Topological Sort: Order a DAG with Kahn's Algorithm or DFS](https://datadank.com/interview/dsa/topological-sort/) | Medium |
| 213 | [Triplets with Smaller Sum: Count Many Pairs at Once With Two Pointers](https://datadank.com/interview/dsa/count-triplets-with-sum-smaller-than-x/) | Medium |
| 214 | [Two Sum II: Find a Pair With a Target Sum in a Sorted Array](https://datadank.com/interview/dsa/two-sum-ii-input-array-is-sorted/) | Medium |
| 215 | [Unique Paths: Count Grid Routes with 2D DP or a Binomial Coefficient](https://datadank.com/interview/dsa/unique-paths/) | Medium |
| 216 | [Valid Parenthesis String: Track a Range of Open Counts Greedily](https://datadank.com/interview/dsa/valid-parenthesis-string/) | Medium |
| 217 | [Valid Sudoku: Check Rows, Columns and Boxes for Repeated Digits](https://datadank.com/interview/dsa/valid-sudoku/) | Medium |
| 218 | [Validate Binary Search Tree: Bounds Recursion and Inorder Check](https://datadank.com/interview/dsa/validate-binary-search-tree/) | Medium |
| 219 | [Word Break: Can a String Be Split into Dictionary Words? Prefix DP](https://datadank.com/interview/dsa/word-break/) | Medium |
| 220 | [Word Search: Trace a Word Through a Letter Grid with DFS Backtracking](https://datadank.com/interview/dsa/word-search/) | Medium |
| 221 | [Alien Dictionary: Derive a Letter Order from Sorted Words with Topological Sort](https://datadank.com/interview/dsa/alien-dictionary/) | Hard |
| 222 | [Binary Tree Maximum Path Sum: Post-Order Gains with a Global Best](https://datadank.com/interview/dsa/binary-tree-maximum-path-sum/) | Hard |
| 223 | [Burst Balloons: Interval DP by Choosing the Last Balloon to Burst](https://datadank.com/interview/dsa/burst-balloons/) | Hard |
| 224 | [Find Median from Data Stream: Two Heaps Kept in Balance](https://datadank.com/interview/dsa/find-median-from-data-stream/) | Hard |
| 225 | [First Missing Positive: Cyclic Sort Into Home Slots in O(n) Time, O(1) Space](https://datadank.com/interview/dsa/first-missing-positive/) | Hard |
| 226 | [IPO: Maximise Capital by Picking the Best Affordable Project Each Round](https://datadank.com/interview/dsa/ipo/) | Hard |
| 227 | [Largest Rectangle in Histogram: Biggest Area Under the Bars](https://datadank.com/interview/dsa/largest-rectangle-in-histogram/) | Hard |
| 228 | [Maximum Frequency Stack: Pop the Most Frequent Value in O(1)](https://datadank.com/interview/dsa/maximum-frequency-stack/) | Hard |
| 229 | [Median of Two Sorted Arrays: Partition Binary Search in O(log min(m, n))](https://datadank.com/interview/dsa/median-of-two-sorted-arrays/) | Hard |
| 230 | [Merge k Sorted Lists: Min-Heap and Divide-and-Conquer Solutions](https://datadank.com/interview/dsa/merge-k-sorted-lists/) | Hard |
| 231 | [Minimum Window Substring: Shortest Slice Containing Every Required Character](https://datadank.com/interview/dsa/minimum-window-substring/) | Hard |
| 232 | [N-Queens: Place Non-Attacking Queens Row by Row with Backtracking](https://datadank.com/interview/dsa/n-queens/) | Hard |
| 233 | [Partition Into 2 Subsets with Min Sum Diff: Subset Sum Up to Half the Total](https://datadank.com/interview/dsa/minimum-sum-partition/) | Hard |
| 234 | [Reconstruct Itinerary: Eulerian Path with Hierholzer's Algorithm](https://datadank.com/interview/dsa/reconstruct-itinerary/) | Hard |
| 235 | [Regular Expression Matching: Dot and Star with a 2D DP Table](https://datadank.com/interview/dsa/regular-expression-matching/) | Hard |
| 236 | [Reverse Nodes in k-Group: In-Place Group Reversal on a Linked List](https://datadank.com/interview/dsa/reverse-nodes-in-k-group/) | Hard |
| 237 | [Serialize and Deserialize Binary Tree: Preorder with Null Markers](https://datadank.com/interview/dsa/serialize-and-deserialize-binary-tree/) | Hard |
| 238 | [Shortest Subarray with Sum at Least K: Prefix Sums and a Monotonic Deque](https://datadank.com/interview/dsa/shortest-subarray-with-sum-at-least-k/) | Hard |
| 239 | [Sliding Window Maximum: Max of Every Window With a Monotonic Deque](https://datadank.com/interview/dsa/sliding-window-maximum/) | Hard |
| 240 | [Sliding Window Median: Two Heaps with Lazy Deletion](https://datadank.com/interview/dsa/sliding-window-median/) | Hard |
| 241 | [Smallest Range Covering Elements from K Lists: K-Way Merge with a Min-Heap](https://datadank.com/interview/dsa/smallest-range-covering-elements-from-k-lists/) | Hard |
| 242 | [Split Array Largest Sum: Binary Search on the Largest Part](https://datadank.com/interview/dsa/split-array-largest-sum/) | Hard |
| 243 | [Substring with Concatenation of All Words: Word-Sized Sliding Windows per Offset](https://datadank.com/interview/dsa/substring-with-concatenation-of-all-words/) | Hard |
| 244 | [Sudoku Solver: Backtracking with Constraint Sets and Smart Cell Choice](https://datadank.com/interview/dsa/sudoku-solver/) | Hard |
| 245 | [Swim in Rising Water: Minimax Path with a Modified Dijkstra](https://datadank.com/interview/dsa/swim-in-rising-water/) | Hard |
| 246 | [Trapping Rain Water: Total Water Held Between Elevation Bars](https://datadank.com/interview/dsa/trapping-rain-water/) | Hard |
| 247 | [Word Ladder: Shortest Word Transformation with BFS and Wildcard Buckets](https://datadank.com/interview/dsa/word-ladder/) | Hard |
| 248 | [Word Search II: Find Many Words in a Grid with a Trie and Backtracking](https://datadank.com/interview/dsa/word-search-ii/) | Hard |

## Contributing

Found a mistake or want a question covered? Open an issue here, or email the address on the
[DataDank contact page](https://datadank.com/contact/).

The question list is licensed under [CC BY 4.0](LICENSE). Answers are © DataDank.
