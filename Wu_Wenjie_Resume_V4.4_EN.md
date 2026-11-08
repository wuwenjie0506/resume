# Wu Wenjie

Phone: +86 18268849018  |  Email: wuwenjie0506@163.com

## Summary

- **Agentic enablement & application building**: As a solo full-stack "super individual," optimized and iterated 8 modules of a baseline managed system within 3 weeks, covering front-end, back-end, and Agent full-stack development. Agentic end-to-end risk analysis combined with real-time data reduced diagnosis time to minutes; delivered 10+ self-healing scenarios and cut monthly risk incidents by 1,000+.
- **Business practice**: Senior experience in application development, construction, and architecture; proficient in rapid application building and iteration, R&D schedule control, product requirements management, and stability assurance. Supported business scenarios at 10,000-level QPS and led Double 11 (Singles' Day) stability assurance.
- **Technical depth**: Years of experience building highly available, maintainable, and scalable applications; years of big data development and stability assurance experience.
- **Team management**: Years of team management experience, combining business development with team building; skilled at cultivating highly cohesive and high-delivery teams. Completed technical manager training and Scrum agile project development training; proficient in agile development and rapid iterative delivery.

## Professional Skills

- Java ecosystem for high-concurrency and microservice architecture; design, development, and maintenance of large, complex systems centered on Spring/Spring Cloud; database/table sharding for user requests and message middleware to decouple time-consuming requests; end-to-end traffic architecture (Gateway → microservice nodes) covering security, stability, and monitoring.
- Development, testing, iteration, and maintenance of high-concurrency QPS systems; led standardization of the development process and DevOps adoption, integrating the full pipeline from development, testing, and delivery to operations.
- Hadoop-ecosystem big data development, optimization, and data quality assurance; proficient in Hadoop, Spark, HBase, Kafka, and other big data components, including their optimization and best practices.

## Work Experience

| Period | Company | Title |
| --- | --- | --- |
| 2024.11 – present | Ant Group | Data Stability Assurance Expert |
| 2024.05 – 2024.10 | Mashang Consumer Finance | Senior Big Data Architect |
| 2023.09 – 2024.03 | Shanghai Yingxinhui | Staff Engineer |
| 2021.09 – 2023.07 | Shanghai Botong | Architect |
| 2018.01 – 2021.08 | Didi Chuxing | Expert Engineer |
| 2016.01 – 2017.12 | Cainiao Network | Senior Development Engineer |
| 2012.04 – 2015.12 | Taobao | Development Engineer |

## Education

| Period | University | Major | Degree |
| --- | --- | --- | --- |
| 2009.09 – 2012.03 | Huazhong University of Science and Technology | Computer Applied Technology | Master of Engineering |
| 2005.09 – 2009.06 | Changsha University of Science and Technology | Civil Engineering (Road Engineering) | Bachelor of Engineering |

## Project Experience

### Big Data Platform Technology Dept. (2024.11 – present, Ant Group — Platform Engineering & Technology Risk)

- Defined data baseline specifications, whitepaper, entry & exit criteria, stability assurance standards, and the data GOC standard emergency response system; drove baseline risk governance, reducing average nightly on-call incidents from 10+ to 3 and annual risk incidents by 60,000.
- Delivered an Agentic-based baseline assurance managed system; implemented Agent diagnostic jobs plus baseline-level real-time risk identification, diagnosis, and self-healing, landing a managed system that assures company-wide baseline stability.
- Built baseline-level real-time and offline data lineage capabilities, empowering baseline migration, upgrades, risk insight, and diagnosis, cutting risk detection time from hours to minutes.
- End-to-end risk analysis and governance; dual-link assurance and data-center-level drills; promoted and governed the engine high-availability (HA) scheme, covering Lindorm isolation, Light HA migration and switchover, SLS HA cloud migration and shard switchover, and Flink version upgrades.

### Big Data Platform Technology Dept. (2024.05 – 2024.10, Mashang Consumer Finance)

- Responsible for the architecture, capability building, and operations of the data development platform; improved the data development experience; planned and delivered the unification and convergence of multiple data applications.

### Web Middle/Back Office (2023.09 – 2024.03, Shanghai Yingxinhui)

- Streamlined and optimized the trade price data flow; leveraged Kafka, xxl-job, and offline data processing to aggregate trade information, decoupling business from offline processing to support trade price queries and downstream processing.

### Big Data One-stop Platform (2021.09 – 2023.08, Shanghai Botong)

- Built a big data query platform from scratch, supporting extensible development of data query, security, watermarking, and log monitoring modules, and landing new query engines.
- Delivered a multi-tenant, multi-site architecture for the data query platform, supporting multiple BU business scenarios via a logically unified / physically isolated design.
- Upgraded and unified the One-stop middle platform, improving overall query performance and supporting both real-time and offline query data; integrated Airflow ETL scheduling and data security components.
- Refactored and unified query and download capabilities, consolidating all download logic and improving configurability and SDK integration; designed and implemented Databike to support synchronous and asynchronous querying, serving high-QPS multi-tenant scenarios through a FaaS approach.
- Optimized download speed and cost, improving the order and wallet data download experience; reduced user download time from 30 minutes to under 5 seconds, saving ~$100,000 per month.
- Delivered the Open Data Center, standardizing user data pre-processing, aggregation, and production flows with configurable, extensible, high-QPS support for user data downloads.
- User asset P&L system: built real-time and offline PNL data, unified user asset analysis and interfaces, improved user asset analysis capabilities, and ensured high-QPS and dual-link HA for data.

### Data Development Platform (2018.01 – 2021.08, Didi Chuxing)

- **Data Development**: Online intelligent data development platform covering the full ETL data development process, supporting task development (Shell, Hive, Spark, MapReduce, etc.), visual table creation, and submission, testing, and release of files and functions. Separated development and production environments and introduced a submit & release concept for engineered management of the data development process. Integrated data test runs, data quality, and monitoring/alerting, while providing analysis and rapid OLAP query capabilities.
- **Scheduling System**: Event-driven intelligent task scheduling engine that orchestrates task priorities on a baseline basis, improving overall assurance for data warehouse and core pipeline tasks. Led multiple refactorings of the scheduling system, delivering resource isolation, data quality, monitoring/alerting, strong & weak task dependencies, DAG/Flow, and internationalization. Abstracted task execution into an independent offline execution engine module, using K8s/Docker for resource isolation and job execution control, and built a multi-dimensional resource monitoring and intelligent auto-scaling system for high utilization and stability.
- **Data Quality**: Table-, field-, and SQL-based data quality rule validation with monitoring and subscription to ensure overall data quality stability. Distinguished strong vs. weak rule mechanisms — strong rules trip the task circuit breaker, while weak rules only raise alerts — for multi-level data quality assurance.
- **Monitoring & Alerting**: Monitored the correctness and timeliness of data production, including task errors, data quality errors, delays, and baseline alerts; applied rule-based alerting according to baseline & task priority to ensure data quality and timeliness.
- **Project Management**: Data resource governance platform managing data assets at tenant and project granularity, including the scheduling system's Gateway queue, YARN queue, permissions, and data assets (databases, tables, HDFS); provided RBAC (roles, members) management and role-based permission approval flows. Designed HDFS storage rules and production/development separation rules to ensure stable, available big data assets.

### Cainiao Cloud Printing (2016.01 – 2017.12, Cainiao Network)

- Responsibilities: system application architect, leading project development and implementation; led Double 11 stability assurance and high-traffic stability support; responsible for ISV integration and BD & operations promotion.

### Data Application Platform (2012.04 – 2015.12, Taobao)

- Responsibilities: module development, testing, and maintenance; business separation and refactoring; report/marketplace permission management. Focused on improving data query & display efficiency, enhancing Double 11 data & knowledge navigation and search, and improving users' precise and fast data retrieval experience. Participated in the 1688 data warehouse development, construction, and maintenance, including: (1) data warehouse migration, development, testing, and refactoring; (2) ETL task development, optimization, and maintenance; (3) middle-layer construction, model refactoring, optimization, and reusability improvement; (4) data requirement support for the offer, transaction, search & BD lines, including data development and reporting; (5) creation, development, maintenance, promotion, Q&A, and usage of data products.
