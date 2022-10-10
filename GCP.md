## GCP   
### Cloud composer    
Cloud Composer is a managed workflow automation tool that is built on Apache Airflow.
#### Apache Airflow

### Databricks
The integration of lake and warehouse built on cloud platforms to provide python notebooks
- Apache Spark    
Apache Spark (Spark) is an open source data-processing engine for large data sets.
The chief difference between Spark and MapReduce is that Spark processes and keeps the data in memory for subsequent steps    
without writing to or reading from disk—which results in dramatically faster processing speeds. `
- Notebooks    
数据笔记本中，用户可以在每一个“单元格”里跑几行代码，实现一个小功能，并实时给出计算结果。
- Tasks    
每一个任务对应着一个笔记本（实现着一个完整功能），用户们可以指定运行频率、机器数量上限，每隔一段时间自动运行笔记本中的所有单元格，完成对完整数据集的计算。    
对已经有一个基于笔记本的流水线来说，从开发环境到生产环境，几乎只需要按几个按钮。   
这全都仰仗于Spark带来的便利：无论是几个机器上1GB的数据，还是几千机器上数十PB的数据，跑的都是同样一套代码，几乎无需变动。