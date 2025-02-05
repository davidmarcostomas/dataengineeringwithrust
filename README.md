### Week 3-Rust Data Engineering Libraries and Tools

#### Suggested Exercises

- **CSV Data Processing**: A tool for processing large CSV files, showcasing efficient data reading, filtering, and aggregation capabilities of Rust.
- **Database Interaction**: An application that interacts with a SQL database (like PostgreSQL) using Diesel, demonstrating CRUD operations, migrations, and complex queries.
- **Data Visualization**: A CLI tool that generates graphs and charts from input data using plotters.
- **Web Scraper**: A multi-threaded web scraper that fetches and parses data from several web pages concurrently.
- **REST API Consumer**: An application that interacts with a REST API to fetch, process, and visualize data.
- **Log Parser**: A tool to parse and analyze server log files. It can extract meaningful information and statistics and provide insights about the server performance.
- **File System Analyzer**: An application that provides insights about disk usage, like the `du` command in Unix.
- **Real-Time Twitter Analysis**: A real-time tweet analysis tool that uses Twitter Stream API to fetch tweets and analyze them (for example, performing sentiment analysis).
- **Stock Market Analyzer**: An application that fetches stock market data from a free API and performs various analyses.
- **Text Analytics**: A text analytics library that provides functionalities like sentiment analysis, named entity recognition, etc.
- **Delta Lake Interaction**: A project demonstrating interaction with Delta Lake for processing large amounts of data.
- **AWS SDK usage**: A project demonstrating the use of AWS SDK in Rust for tasks such as accessing S3 buckets, performing operations on DynamoDB, etc.
- **Data Processing with Polars**: A project demonstrating how to perform large-scale data processing with the Polars library in Rust.
- **Kafka Producer/Consumer**: An application that produces and consumes messages from Kafka.
- **gRPC Microservices**: A basic microservices setup using gRPC, demonstrating how Rust can be used for backend development.
- **Apache Arrow usage**: A project demonstrating how to use Apache Arrow for columnar data processing in Rust.
- **Parquet File Processing**: An application that reads and writes Parquet files, demonstrating how Rust can be used for efficient data engineering tasks.
- **Data Engineering with TiKV**: A project demonstrating how to use TiKV, a distributed transactional key-value database built in Rust.



- **Rust-based ETL Pipeline**: Develop an ETL (Extract, Transform, Load) pipeline using various Rust libraries to process and transfer data between different storage systems.

- **Web Scraper with Rust**: Build a concurrent web scraper that can efficiently scrape large amounts of data from web pages.

- **Rust REST API Server**: Design a REST API server in Rust that serves data from a database. Use the Diesel ORM for database interactions.

- **Real-time Data Streaming with Rust**: Implement a real-time data streaming application, processing streams of data in a concurrent manner.

- **Rust-based Data Lake**: Use the Delta Lake Rust API to create a data lake solution. Implement CRUD operations on the data lake.

- **Big Data Processing with Rust and Apache Arrow**: Use Apache Arrow to perform efficient in-memory big data processing.

- **Rust and AWS SDK**: Use the AWS SDK for Rust to interact with AWS services such as S3 and DynamoDB.

- **gRPC Service in Rust**: Implement a gRPC service in Rust that performs CRUD operations on a database.

- **Log Analyzer**: Create a log analyzer that can process large log files concurrently and provide useful insights from logs.

- **Distributed Systems with Rust**: Create a simple distributed system using Rust's concurrency features. This could be a simple key-value store or a message-passing system.

- **Rust and GraphQL**: Implement a GraphQL API in Rust using libraries like Juniper.

- **Data Serialization with Rust**: Use libraries like serde to perform data serialization and deserialization in various formats (JSON, XML, etc.)

- **Rust and Kafka**: Use Rust to interact with Kafka, implementing a producer and consumer system.

- **Data Validation Service**: Create a service that validates input data based on predefined rules. This could be a web service or a library that other services can use.

- **Rust and Machine Learning**: Use Rust machine learning libraries to implement a simple prediction model. You could use the data processed in the ETL pipeline or the data lake for this.
## Makefile

Each subdirectory project uses this style to make it easy to test and run

```
format:
	cargo fmt --quiet

lint:
	cargo clippy --quiet

test:
	cargo test --quiet

run:
	cargo run 

all: format lint test run
```
