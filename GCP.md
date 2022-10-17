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


### API(application programming interface)
APIs essentially help two systems of software or applications talk to each other.
提供接口供外部访问内部代码
e.g.
The Google Maps Geocoding API lets you send a request with an address and returns the geo-coordinates for the address.
get url is only onw way of it, giving the info of endpoint, parameters and key

### Microservices


### Edge AI
Edge AI is a combination of edge computing and AI 
#### Edge computing 
Edge computing is a distributed computing framework that brings enterprise applications closer to data sources such as IoT devices or local edge servers.    
In general, edge AI is used for inferencing, while cloud AI is used to train new algorithms. Inferencing algorithms require significantly less processing capabilities and energy than training algorithms. As a result, well-designed inferencing algorithms are sometimes run on existing CPUs or even less capable microcontrollers in edge devices. In other cases, highly efficient AI chips improve inferencing performance, reduce power or both.
