# Yuchan Lee

[![GitHub](https://img.shields.io/badge/-lasuillard-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/lasuillard)
[![Email](https://img.shields.io/badge/-lasuillard@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:lasuillard@gmail.com)
[![Blog](https://img.shields.io/badge/-blog.lasuillard.me-FF5722?style=flat-square&logo=blogger&logoColor=white)](https://blog.lasuillard.me)

Experienced backend developer specializing in Python and AWS-based backend systems. Passionate about building scalable backend systems and cloud infrastructure, with a strong focus on improving development efficiency through automated workflows and CI/CD pipelines. Currently learning Infrastructure as Code and DevOps best practices to foster better development culture.

## 🛠️ Skills

### Programming Languages
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)

### Frameworks & Libraries
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/-Django_REST_Framework-A30000?style=flat-square&logo=Django&logoColor=white)
![Django Ninja](https://img.shields.io/badge/-Django_Ninja-092E20?style=flat-square&logo=Django&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)
![Twisted](https://img.shields.io/badge/-Twisted-000000?style=flat-square&logo=Python&logoColor=white)

### Cloud & Infrastructure
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS ECS](https://img.shields.io/badge/-AWS_ECS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Elastic Beanstalk](https://img.shields.io/badge/-AWS_Elastic_Beanstalk-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS RDS](https://img.shields.io/badge/-AWS_RDS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Redshift](https://img.shields.io/badge/-AWS_Redshift-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS DMS](https://img.shields.io/badge/-AWS_DMS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/-Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Pulumi](https://img.shields.io/badge/-Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Windows Server](https://img.shields.io/badge/-Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)

### Development Tools
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

## 💼 Experience

### EarlyPay - Backend Engineer
**December 2023 - June 2025**

Developed and maintained various backend systems to ensure stable operation of early payment services. Handled comprehensive tasks from settlement and crawler service development to infrastructure construction and management.

#### 📝 Key Responsibilities

- **Early Payment Service Development & Maintenance**
  - Maintenance and new feature development of Django-based early payment service
  - Managed overall Celery configuration, optimizing worker and queue configurations, utilizing dynamic routing and task processing speed control to resolve task bottlenecks and improve overall settlement processing speed
  - Improved dependency management and deployment processes, migrated from Elastic Beanstalk to AWS ECS to enhance service availability
  - Migrated complex legacy VPC to new VPC to improve maintainability
  - Zero-downtime upgrade from PostgreSQL 12 to PostgreSQL 15 using blue-green deployment strategy when AWS RDS standard support ended

- **Crawler Development & Maintenance**
  - Configuration and maintenance of FastAPI-based web data collection crawlers, bot detection bypass, and new feature development
  - Migrated crawler from single server to AWS Lambda, then to AWS ECS environment due to increased system resource requirements for bot detection bypass
  - Improved crawler scalability and availability through auto-scaling and efficient cost management
  - Introduced IP rotation functionality to resolve IP blocking issues from some VAN company sites, improving crawler stability
  - Developed crawlers for some VAN companies that couldn't be automated due to site security programs (security keypads) using Windows Server and OpenCV
  - Fully automated sales collection tasks that were previously handled semi-automatically, improving settlement work efficiency

- **Infrastructure Construction & Management**
  - Managed AWS infrastructure configuration as code using Pulumi, improving infrastructure version control, reproducibility, and change tracking
  - Built self-service workflows using GitHub Actions to enable developers to directly manage some infrastructure
  - Enabled developers to easily reconstruct development databases from production database snapshots and perform essential post-processing such as data masking
  - Built data warehouse using AWS Redshift as part of TIPS project
  - Real-time data replication from related databases to Redshift using AWS Database Migration Service (DMS)
  - Established foundation for large-scale data analysis and report generation, built BI dashboards using Grafana
  - Optimized infrastructure costs by identifying and removing unnecessary or excessive resources, reducing operational costs and improving resource efficiency

- **Other Contributions**
  - Introduced code quality improvement tools like Ruff and MyPy for automated testing and code inspection to maintain code consistency and prevent bugs proactively
  - Automated code inspection and testing using GitHub Actions, preventing frequent development mistakes (e.g., Django Migrations) through automated checks
  - Led tech sessions to foster development culture, enhance team technical capabilities, and promote knowledge sharing
  - Shared latest technology trends and best practices within the team and discussed ideas for development process improvement

#### 🛠️ Technologies Used
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/-AWS_Lambda-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS ECS](https://img.shields.io/badge/-AWS_ECS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS RDS](https://img.shields.io/badge/-AWS_RDS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS Redshift](https://img.shields.io/badge/-AWS_Redshift-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![AWS DMS](https://img.shields.io/badge/-AWS_DMS-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django Ninja](https://img.shields.io/badge/-Django_Ninja-092E20?style=flat-square&logo=Django&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Pulumi](https://img.shields.io/badge/-Pulumi-8A3391?style=flat-square&logo=pulumi&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)
![Windows Server](https://img.shields.io/badge/-Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white)

### AIZEN Global - Backend Engineer
**December 2022 - August 2023**

Participated in Woori Card FDS advancement project and performed maintenance and development tasks for high-volume data processing systems.

#### 📝 Key Responsibilities

- **Woori Card FDS Advancement**
  - Maintenance and new feature development of Python Twisted-based FDS scoring server processing approximately 7 million requests daily
  - Managed ClickHouse used for score calculation while processing and analyzing large-scale data

#### 🛠️ Technologies Used
![ClickHouse](https://img.shields.io/badge/-ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![Docker Compose](https://img.shields.io/badge/-Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Twisted](https://img.shields.io/badge/-Twisted-000000?style=flat-square&logo=Python&logoColor=white)

### EarlyPay - Backend Engineer
**June 2021 - December 2021**

Participated as an early member of EarlyPay startup and built the foundation for offline sales early payment services.

#### 📝 Key Responsibilities

- **Offline Early Payment Service Development**
  - Web server development using Django framework
  - PostgreSQL database construction and management, used Redis as cache server
  - API server development using Django REST Framework for frontend communication
  - Asynchronous and periodic task processing using Celery and Celery Beat
  - Collection of sales and various settlement data and settlement work execution, used Redis as message broker
  - Periodic task management using Celery Beat and task monitoring using Flower
  - Server deployment using AWS Elastic Beanstalk and deployment automation using GitHub Actions

- **Web Crawler Development for Card Sales Data Collection**
  - Crawler server development for collecting card sales and various settlement data
  - Data collection from various sites including approximately 10 VAN companies, CFA, and card company merchant information
  - Implementation of HTTP-based and Selenium-based web browser crawlers
  - Performance improvement by rewriting existing Flask-based crawler implementation to FastAPI

#### 🛠️ Technologies Used
![AWS Elastic Beanstalk](https://img.shields.io/badge/-AWS_Elastic_Beanstalk-FF9900?style=flat-square&logo=amazon-aws&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=Celery&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=Django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/-Django_REST_Framework-A30000?style=flat-square&logo=Django&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=Redis&logoColor=white)
![Selenium](https://img.shields.io/badge/-Selenium-43B02A?style=flat-square&logo=Selenium&logoColor=white)

## 🎓 Education

### Seoul National University of Science and Technology
**March 2014 - February 2020**

- Bachelor's degree in Computer Engineering
- GPA: 4.11/4.5

## 📜 Certificates

- **Engineer Information Processing** - HRD Korea (August 28, 2020)
- **TOEIC** - ETS (September 15, 2018) - Score: 935/990
- **Craftsman Information Equipment Operation** - HRD Korea (December 5, 2016)
- **Craftsman Information Processing** - HRD Korea (February 5, 2015)

---

<div align="center">

_Updated with assist of AI at 2025-07-03T10:32:02Z_

</div>
