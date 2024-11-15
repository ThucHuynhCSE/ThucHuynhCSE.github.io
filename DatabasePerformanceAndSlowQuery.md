## Slow queries

Slow queries can have a significant impact on database performance. There are some common causes as below:

- Large data:
  - The query execution time can increase due to complex data scanning and processing.
- Inefficient Query Design:
  - Queries that don't use indexes or have sub-optimal search conditions can slow down query execution
- Indexes:
  - Lack Index:
    - If your table or database lacks indexes or if the existing indexes are not optimized, queries can run slowly.
    - In some cases, we also lack the index in temporary table
  - Many Indexes are not used
    - Consumes resources to store indexes
    - Causes slowness for upsert queries
- Misconfiguration:
  - Incorrect database or application configurations can also affect performance and lead to slow queries.
- Weak hardware:
  - A database system with weak hardware configurations, including CPU, RAM, and storage, can result in slow queries
- Poor network connectivity:
  - The connection to the database will rely on the network
- Inappropriate Technology Choice:
  - Choose wrong database technology for your application
- System Overload:
  - Processing too many requests or queries simultaneously, it can lead to slow queries due to resource contention.
- Background Processes or Complex Workloads:
  - Other background processes or complex workloads running on the system can compete for resources and affect query performance.

## Database performance

We need to ensure our database running efficiently and effectively. Various metrics can help us to assess the health and performance of database. We can follow with the following key metrics (or refer doc)

- Response time
- Throughput
- Resource usage (CPU Utilization & Memory usage)
- Disk I/O
- Cache hit ratio
- Table scans
- Index Utilization
- Error Rate
- Buffer Pool Hit Rate
- Storage Space
- Slow query
