# 🧠 Professional Overview

## 👩‍💻 Technical Expertise
Sushma is an experienced Technical Lead and Developer with **8.6+ years** of hands-on experience in developing web services using **Agile methodologies**, enabling continuous delivery across diverse client portfolios.

- Specialized in **API web service development and scaling** using the **Entity Framework** for top-tier Life Sciences clients.
- Designed and implemented a **reusable framework** for consuming and providing complex **REST APIs**.

## 🧭 Leadership & Team Enablement
Sushma has demonstrated strong leadership and cross-functional collaboration across multiple initiatives:

- Resolved **50+ critical and escalated issues** across UDAP teams.
- Renewed **200+ SPNs** as posted by the Director.
- Partnered with the Lead Cloud Architect to:
  - Automate onboarding processes using **APIs** and **post-validation pipelines**.
  - Suggest resource import strategies during **repo migration**, preventing deployment delays in Terraform.
  - Integrate **Terramate auto-generated tooling** using `plattera` commands to dynamically add data based on new requests.

## 🌐 Cross-Team Collaboration & Infrastructure Optimization
- Engaged with **150+ business team members** over a month to resolve **subnet exhaustion** across clusters in multiple regions.
- Coordinated with networking teams to:
  - Enable **Private Endpoint creation** for accessing resources from **Databricks 3.0** to **Azure Storage Account 1.0**.
  - Resolve infrastructure issues including **cluster policies**, **memory allocation**, and **ACLs**.
- Unblocked dependent requests by:
  - Creating **scheduled pipelines**.
  - Adding **cost optimization tags** via **Unravel scripts** in workspaces.

## 🚀 Recent Achievements & Certifications
- Reworked **Skin Analysis data** using Python for cleaning, transformation, and ML reporting on cancer predictions. Delivered refreshed **Power BI dashboard** ahead of a presentation at **Auckland University**.
- Trained **10+ team members** on Databricks workspace onboarding, peer reviews, and infrastructure best practices in **Prefect**, **Git Actions**, **Azure CI/CD**, and **REST API automation**.
- Resolved repo folder permission issues over a week, identifying RCA and implementing fixes.
- Earned **8 Databricks certifications**, including:
  - Cloud Native Spark Migration
  - Data & AI Governance (Unity Catalog)
  - Databricks Fundamentals & Platform Administrator
  - Generative AI Fundamentals
  - Multi-cloud exposure across Azure, AWS, and GCP
  - Databricks Platform Architect
  - Databricks Certified Data Engineer Professional (July 2025)
- Independently handled strategic infrastructure automation:
  - Daily PR creation
  - ACL post-request validation
  - JFrog token issue resolution in Terraform (~4,000 resources)
  - Automated owner schema tagging for **2,000+ schemas**
- Delivered all major deployments across **4 workspaces** with high stakeholder satisfaction and zero remarks.
- Documented all work via **SOPs and wiki pages**, added as **Acceptance Criteria** for team stories.
- Completed **AI prompt engineering training** using internal tools and **Windsurf AI in VSCode**, reducing debugging time.

## 🧰 Technical Certifications & Skills
- Oracle Certified Professional, Java SE 6 Programmer
- Microsoft Certified C# Specialist
- Strong experience in **Entity Framework** (C#)
- Proficient in **HTML**, **CSS**, **JavaScript**
- Skilled in **Git** and **Azure Repos** for team collaboration
- Experienced in **SOAP UI** for API testing
- Followed best practices using **JavaDoc** for API documentation
- Implemented secure API authentication using **API Key**, **LDAP**, **OAuth**, and **HashiCorp Vault**

### 🛠️ Technical Skill Set

| Category                  | Technologies & Tools                                                                 |
|--------------------------|----------------------------------------------------------------------------------------|
| Web Development          | JavaScript, jQuery, HTML, VueJS                                                       |
| Programming Languages    | Java, C#, Python                                                                       |
| Web Services             | RESTful services                                                                       |
| Frameworks               | Spring Boot, SOAP UI, Node.js                                                          |
| Data Handlers            | Elasticsearch, Solr, MongoDB, SQL, Hive, Impala                                       |
| API Authentication       | JWT, LDAP, OAuth                                                                       |
| Visualization Tools      | Kibana, Zoomdata, Power BI                                                             |
| Version Control          | Git, TFS, SVN                                                                          |
| Cloud Services           | Azure DevOps, Google Cloud Platform                                                    |
| Microsoft Services       | SharePoint, InfoPath, Power Apps, Power Automate                                      |

---

# 📂 Projects

## ADM UI Application
**Client:** Top 5 Life Sciences Company  
**Role:** Technical Lead  

### Description
Developed a web application to configure data movements from Oracle, MySQL, and SFTP sources. Built web services for database interaction and workflow approvals from domain/data owners.

### Key Features
- Automated data movements and ingestion
- Creation of new databases
- Ingestion from external sources to foundation
- Integrated data movements across environments

### Accountabilities
- Developed file-format recognition services for large datasets
- Validated API payloads and encrypted sensitive data
- Created customizable patterns for user requests
- Built navigational APIs and microservices for data scheduling
- Containerized services for scalability
- Implemented REST API versioning
- Delivered sprint releases on time
- Trained team on JavaDoc standards
- Handled API exceptions effectively

---

## Employee 360 Degree
Developed an application to track employee KPIs, timesheets, and performance metrics with feedback integration.

### Accountabilities
- Designed application architecture
- Trained team on dynamic API content retrieval
- Automated exception handling
- Role-based authentication for PMs, Tech Leads, and Developers

---

## GAT (Generic Analysis Tracker)
**Client:** Top 5 Life Sciences Company  
**Role:** Senior Developer  

### Description
A web app for tracking data usage and analysis approvals on a big data platform.

### Accountabilities
- Queried documents from Solr with optimized responses
- Performed complex computations in Solr and Spring
- Developed file upload/download services

---

## GWAS (Genome-Wide Association Studies)
**Client:** Top 5 Life Sciences Company  
**Role:** Senior Developer  

### Description
Built a GUI-based job tracking system for genome data analysis with Spark job submission and matrix computations.

### Accountabilities
- Leveraged **Kahn's algorithm** for job dependency resolution
- Developed Spark job submission services
- Integrated UI with backend databases

# 🌐 Cloud-Based Product Development – Humana

## 🔧 Role: Cloud Engineer  
## ☁️ Platform: Google Cloud Platform (GCP)

### 📌 Project: Event Management – Direct Messaging

**Description:**  
Developed an event-driven messaging product on GCP that consumes Kafka events or direct message objects, applies transformations, and triggers services via Google Cloud Functions. The system integrates with SES services to send emails based on provider lookup, and logs are persisted in MongoDB for monitoring. A feedback loop tracks message delivery status using message IDs.

**Key Accountabilities:**
- Designed feasible solutions and data models for each stage of development.
- Configured Schema Registry to validate Kafka source messages.
- Built Streamsets pipelines for Kafka message transformation.
- Managed Kafka Confluent configuration to trigger GCP Cloud Functions.
- Integrated SES SOAP services for web mailing operations.
- Resolved cloud connectivity issues across services.
- Secured SES authentication using Google Secret Manager and x509 certificates.
- Configured serverless VPC to connect Cloud Functions with MongoDB.
- Persisted logs in Google Cloud Logging and Bigtable for error tracking.
- Scheduled Cloud Function triggers using Google Cloud Scheduler.
- Supported HTML content and image attachments in triggered emails.

---

## 🔧 Role: Cloud Engineer  
## ☁️ Platform: Google Cloud Platform (GCP)

### 📌 Project: Event Management Services

**Description:**  
Built a generic event management product that consumes data from multiple Kafka sources. Applied dynamic filtering using Cloud SQL and streamed processed data to DB2. The system supports dynamic topic creation and filtration logic via Streamsets and Google Cloud Functions.

**Key Accountabilities:**
- Developed Streamsets pipelines with dynamic multi-topic Kafka consumers using REST APIs.
- Created Google Cloud Functions for generic data filtration via MySQL and Kafka Python library.
- Implemented Groovy scripting for event processing based on database filters.
- Built REST APIs for CRUD operations across event management tables.

---

## 🔧 Role: Application Developer  
## ☁️ Platform: Google Cloud Platform (GCP)

### 📌 Project: API Services Development

**Description:**  
Designed and deployed APIs on top of MongoDB to serve data loaded from a warehouse into GCP buckets. The API interacts with downstream services and maps responses to FHIR models. APIs are registered as products for consumer subscription.

**Key Accountabilities:**
- Developed and scheduled Streamsets pipelines for initial and daily data loads.
- Verified MongoDB data integrity post-load.
- Built APIs using .NET and performed mock testing.
- Deployed APIs across environments post-approval.
- Registered APIs as products for consumer subscription and usage tracking.
