# etlpython

## Docs
- https://blog.panoply.io/top-9-python-etl-tools-and-when-to-use-them
- 
## Python Data
If you're building a data warehouse, you need ETL to move data into that storage. To do that, you first extract data from an array of different sources. Then you apply transformations to get everything into a format you can use, and finally, you load it into your data warehouse. 

There are many ways to do this, one of which is the Python programming language. The Python community has created a range of tools to make your ETL life easier and give you control over the process. If you have the time, money, and patience, using Python will ensure your ETL pipeline is streamlined exactly for your business needs.  

With that in mind, here are the top Python ETL Tools for 2021. Some of these let you manage each step of the ETL process, while others are excellent at a specific step. They are organized into groups to make it easier for you to compare them. Let’s go!

## Workflow management systems (WMS)
- Apache Airflow
- Luigi
- Data processing
- pandas
- Spark
- petl

## ETL frameworks
- Bonobo
- Mara
- Pygrametl


## Small but powerful
- odo
- ETLAlchemy
- Riko
- Locopy
- Inactive tools

##  Data Collector
###  Nifi

NiFi is a data flow tool that was meant to fill the role of batch scripts, at the ever increasing scale of big data. Rather than maintain and watch scripts as environments change, NiFi was made to allow end users to maintain flows, easily add new targets and sources of data, and do all of these tasks with full data provenance and replay capability the whole time.

NiFi encompasses the idea of flowfiles and processors. A flowfile is a single piece of information and is comprised of two parts, a header and content (very similar to an HTTP Request). The header contains many attributes that describe things like the data type of the content, the timestamp of creation, and a totally unique ‘uuid.’ Custom attributes can also be set and operated on in the logic of the flow. The content of a flowfile is simply the raw data that is being passed along. It could be plaintext, JSON, binary, or any other kind of bytes.
### Kafka
