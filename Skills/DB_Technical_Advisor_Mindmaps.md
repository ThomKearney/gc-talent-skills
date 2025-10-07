# Database Technical Advisor — Clickable Mind Maps (Per Branch)

> **How to use internal links:**  
> 1) Pick your LMS search base, e.g. `https://lms.company.com/search?q=`  
> 2) Find/replace **`{{LMS_BASE}}`** with that string across this file.  
> 3) The clicks will then search your LMS for the exact topic or course skill.

## Contents
1. [Database Systems](#1-database-systems)
2. [Database Design](#2-database-design)
3. [Database Programming Tools](#3-database-programming-tools)
4. [Data Security & Recovery](#4-data-security--recovery)
5. [Systems Interoperability](#5-systems-interoperability)
6. [Database Migration](#6-database-migration)
7. [Database Trends & Directions](#7-database-trends--directions)
8. [Mentoring](#8-mentoring)
9. [Advice to Management](#9-advice-to-management)

---

## 1) Database Systems — target: **Advanced**
```mermaid
mindmap
  root((Database Systems — Advanced))
    RDBMS Concepts
    Query Processing & Optimization
    Transactions & Concurrency
    Indexing & Storage
    Intro Admin (backup, roles)
    Course Skills
      Database Systems
      Database Management
      Microsoft SQL Server
      SQL

%% Clickable links (swap {{LMS_BASE}} with your LMS search URL)
click RDBMS Concepts "{{LMS_BASE}}RDBMS%20concepts" "RDBMS overview"
click Query Processing & Optimization "{{LMS_BASE}}query%20processing%20optimization" "Query processing & optimization"
click Transactions & Concurrency "{{LMS_BASE}}database%20transactions%20ACID%20isolation" "ACID & isolation"
click Indexing & Storage "{{LMS_BASE}}database%20indexing%20storage" "Indexing & storage"
click Intro Admin (backup, roles) "{{LMS_BASE}}database%20backup%20roles%20basics" "Admin basics"
click Database Systems "{{LMS_BASE}}Database%20Systems" "Course skill: Database Systems"
click Database Management "{{LMS_BASE}}Database%20Management" "Course skill: Database Management"
click Microsoft SQL Server "{{LMS_BASE}}Microsoft%20SQL%20Server" "Course skill: Microsoft SQL Server"
click SQL "{{LMS_BASE}}SQL" "Course skill: SQL"
```

---

## 2) Database Design — target: **Advanced**
```mermaid
mindmap
  root((Database Design — Advanced))
    Requirements → ER Modeling
    Normalization (1NF→BCNF)
    Logical Schema (relational)
    Physical Design (partitioning, files)
    Constraints & Data Integrity
    Course Skills
      Database Design
      Data Modeling
      Database Architecture
      Database Concepts

click Requirements → ER Modeling "{{LMS_BASE}}ER%20modeling" "ER modeling"
click Normalization (1NF→BCNF) "{{LMS_BASE}}database%20normalization%201NF%202NF%203NF%20BCNF" "Normalization"
click Logical Schema (relational) "{{LMS_BASE}}logical%20schema%20relational" "Logical schema"
click Physical Design (partitioning, files) "{{LMS_BASE}}physical%20database%20design%20partitioning" "Physical design"
click Constraints & Data Integrity "{{LMS_BASE}}database%20constraints%20data%20integrity" "Constraints"
click Database Design "{{LMS_BASE}}Database%20Design" "Course skill"
click Data Modeling "{{LMS_BASE}}Data%20Modeling" "Course skill"
click Database Architecture "{{LMS_BASE}}Database%20Architecture" "Course skill"
click Database Concepts "{{LMS_BASE}}Database%20Concepts" "Course skill"
```

---

## 3) Database Programming Tools — target: **Advanced**
```mermaid
mindmap
  root((Database Programming Tools — Advanced))
    SQL Dev Workflow
      Stored Procedures
      Functions
      Triggers
    Vendor Dialects
      T-SQL
      PL/SQL
    Tooling
      Database Developer Tools
      Version Control
      Unit/Integration Testing
    Course Skills
      SQL Development
      SQL Programming
      T-SQL Programming
      PL/SQL Programming
      Database Developer Tools

click Stored Procedures "{{LMS_BASE}}stored%20procedures%20best%20practices" "Stored procedures"
click Functions "{{LMS_BASE}}user%20defined%20functions%20SQL" "UDFs"
click Triggers "{{LMS_BASE}}database%20triggers" "Triggers"
click T-SQL "{{LMS_BASE}}T-SQL" "T-SQL"
click PL/SQL "{{LMS_BASE}}PL%2FSQL" "PL/SQL"
click Database Developer Tools "{{LMS_BASE}}database%20developer%20tools" "Dev tools"
click Version Control "{{LMS_BASE}}database%20schema%20version%20control%20migrations" "DB versioning"
click Unit/Integration Testing "{{LMS_BASE}}database%20unit%20testing%20integration%20testing" "DB testing"
click SQL Development "{{LMS_BASE}}SQL%20Development" "Course skill"
click SQL Programming "{{LMS_BASE}}SQL%20Programming" "Course skill"
click T-SQL Programming "{{LMS_BASE}}T-SQL%20Programming" "Course skill"
click PL/SQL Programming "{{LMS_BASE}}PL%2FSQL%20Programming" "Course skill"
```

---

## 4) Data Security & Recovery — target: **Advanced**
```mermaid
mindmap
  root((Data Security & Recovery — Advanced))
    Access Control & IAM
    Encryption (at rest, in transit)
    Auditing & Monitoring
    Backup & Restore Strategy
    Disaster Recovery & HA
    Incident Response Playbooks
    Course Skills
      Database Security
      Identity and Access Management (IAM)
      Encryption Concepts
      Backup and Recovery
      Disaster Recovery
      Incident Response

click Access Control & IAM "{{LMS_BASE}}database%20IAM%20access%20control" "IAM"
click Encryption (at rest, in transit) "{{LMS_BASE}}database%20encryption%20at%20rest%20in%20transit" "Encryption"
click Auditing & Monitoring "{{LMS_BASE}}database%20auditing%20monitoring" "Auditing"
click Backup & Restore Strategy "{{LMS_BASE}}database%20backup%20strategy%20restore%20testing" "Backup strategy"
click Disaster Recovery & HA "{{LMS_BASE}}database%20disaster%20recovery%20high%20availability" "DR & HA"
click Incident Response Playbooks "{{LMS_BASE}}database%20incident%20response%20playbook" "IR playbooks"
click Database Security "{{LMS_BASE}}Database%20Security" "Course skill"
click Identity and Access Management (IAM) "{{LMS_BASE}}Identity%20and%20Access%20Management%20(IAM)" "Course skill"
click Encryption Concepts "{{LMS_BASE}}Encryption%20Concepts" "Course skill"
click Backup and Recovery "{{LMS_BASE}}Backup%20and%20Recovery" "Course skill"
click Disaster Recovery "{{LMS_BASE}}Disaster%20Recovery" "Course skill"
click Incident Response "{{LMS_BASE}}Incident%20Response" "Course skill"
```

---

## 5) Systems Interoperability — target: **Advanced**
```mermaid
mindmap
  root((Systems Interoperability — Advanced))
    Integration Patterns
      ETL / ELT
      Change Data Capture
      Event-Driven (streams)
    APIs & Services
      REST / gRPC
      Web Services
      SDKs & Drivers
    Data Formats & Contracts
      JSON / Avro / Parquet
      Schema Registry
    Cloud & Hybrid Connectivity
    Course Skills
      Integration
      API Development
      Web Services
      Data Integration
      Cloud Services

click ETL / ELT "{{LMS_BASE}}ETL%20ELT" "ETL/ELT"
click Change Data Capture "{{LMS_BASE}}change%20data%20capture%20CDC" "CDC"
click Event-Driven (streams) "{{LMS_BASE}}event%20driven%20data%20streaming" "Event streaming"
click REST / gRPC "{{LMS_BASE}}REST%20gRPC" "APIs"
click Web Services "{{LMS_BASE}}Web%20Services" "Course skill"
click SDKs & Drivers "{{LMS_BASE}}database%20drivers%20ODBC%20JDBC%20SDK" "Drivers/SDKs"
click JSON / Avro / Parquet "{{LMS_BASE}}JSON%20Avro%20Parquet" "Formats"
click Schema Registry "{{LMS_BASE}}schema%20registry" "Schema registry"
click Cloud & Hybrid Connectivity "{{LMS_BASE}}hybrid%20cloud%20database%20connectivity" "Hybrid connectivity"
click Integration "{{LMS_BASE}}Integration" "Course skill"
click API Development "{{LMS_BASE}}API%20Development" "Course skill"
click Data Integration "{{LMS_BASE}}Data%20Integration" "Course skill"
click Cloud Services "{{LMS_BASE}}Cloud%20Services" "Course skill"
```

---

## 6) Database Migration — target: **Advanced**
```mermaid
mindmap
  root((Database Migration — Advanced))
    Assessment & Planning
      Inventory & Dependencies
      Compat/Feature Gaps
      Downtime/Rollback Plan
    Move Strategies
      Backup/Restore
      Log Shipping / Replication
      Online (CDC/Sync)
    Platform Targets
      Azure SQL Databases
      Oracle Cloud Infrastructure
      Hybrid / Multicloud
    Validation & Cutover
      Data Reconciliation
      Performance Baselines
      Runbooks
    Course Skills
      Database Migration
      Cloud Deployment
      Migrating to Azure
      Azure SQL Databases
      Oracle Cloud Infrastructure

click Inventory & Dependencies "{{LMS_BASE}}database%20migration%20assessment%20inventory" "Assessment"
click Compat/Feature Gaps "{{LMS_BASE}}database%20migration%20feature%20compatibility" "Compatibility"
click Downtime/Rollback Plan "{{LMS_BASE}}database%20migration%20downtime%20rollback" "Rollback"
click Backup/Restore "{{LMS_BASE}}backup%20restore%20database%20migration" "Backup/restore"
click Log Shipping / Replication "{{LMS_BASE}}database%20replication%20log%20shipping" "Shipping/replication"
click Online (CDC/Sync) "{{LMS_BASE}}online%20database%20migration%20CDC%20sync" "Online migration"
click Azure SQL Databases "{{LMS_BASE}}Azure%20SQL%20Databases" "Course skill"
click Oracle Cloud Infrastructure "{{LMS_BASE}}Oracle%20Cloud%20Infrastructure" "Course skill"
click Hybrid / Multicloud "{{LMS_BASE}}hybrid%20multicloud%20database" "Hybrid/multicloud"
click Data Reconciliation "{{LMS_BASE}}database%20migration%20data%20validation%20reconciliation" "Validation"
click Performance Baselines "{{LMS_BASE}}database%20performance%20baseline" "Baselines"
click Runbooks "{{LMS_BASE}}database%20migration%20runbook" "Runbooks"
click Database Migration "{{LMS_BASE}}Database%20Migration" "Course skill"
click Cloud Deployment "{{LMS_BASE}}Cloud%20Deployment" "Course skill"
click Migrating to Azure "{{LMS_BASE}}Migrating%20to%20Azure" "Course skill"
```

---

## 7) Database Trends & Directions — target: **Advanced**
```mermaid
mindmap
  root((Database Trends & Directions — Advanced))
    Cloud-Native DB (serverless, autoscale)
    Distributed SQL & NewSQL
    NoSQL & Multi-model
    Data Lakehouse & ELT
    AI/ML in Databases
    DevOps for Data (DB DevOps)
    Course Skills
      Cloud Computing
      AWS Cloud
      Azure
      Big Data
      AI/ML Fundamentals
      DevOps

click Cloud-Native DB (serverless, autoscale) "{{LMS_BASE}}cloud-native%20serverless%20database" "Cloud-native DB"
click Distributed SQL & NewSQL "{{LMS_BASE}}Distributed%20SQL%20NewSQL" "Distributed SQL"
click NoSQL & Multi-model "{{LMS_BASE}}NoSQL%20multi-model%20databases" "NoSQL"
click Data Lakehouse & ELT "{{LMS_BASE}}data%20lakehouse%20ELT" "Lakehouse"
click AI/ML in Databases "{{LMS_BASE}}machine%20learning%20databases" "AI/ML in DB"
click DevOps for Data (DB DevOps) "{{LMS_BASE}}database%20DevOps" "DB DevOps"
click Cloud Computing "{{LMS_BASE}}Cloud%20Computing" "Course skill"
click AWS Cloud "{{LMS_BASE}}AWS%20Cloud" "Course skill"
click Azure "{{LMS_BASE}}Azure" "Course skill"
click Big Data "{{LMS_BASE}}Big%20Data" "Course skill"
click AI/ML Fundamentals "{{LMS_BASE}}AI%2FML%20Fundamentals" "Course skill"
click DevOps "{{LMS_BASE}}DevOps" "Course skill"
```

---

## 8) Mentoring — target: **Advanced**
```mermaid
mindmap
  root((Mentoring — Advanced))
    Coaching Methods
    Feedback Models
    Shadowing & Pairing
    Learning Plans & Goals
    Measuring Progress
    Course Skills
      Mentoring
      Coaching
      Teaching
      Leadership Development
      Team Leadership

click Coaching Methods "{{LMS_BASE}}technical%20mentoring%20coaching%20methods" "Coaching methods"
click Feedback Models "{{LMS_BASE}}feedback%20models%20SBI%20COIN%20mentoring" "Feedback models"
click Shadowing & Pairing "{{LMS_BASE}}shadowing%20pair%20programming%20mentoring" "Shadowing/pairing"
click Learning Plans & Goals "{{LMS_BASE}}individual%20development%20plan%20IDP" "Learning plans"
click Measuring Progress "{{LMS_BASE}}mentoring%20measurement%20rubrics" "Measurement"
click Mentoring "{{LMS_BASE}}Mentoring" "Course skill"
click Coaching "{{LMS_BASE}}Coaching" "Course skill"
click Teaching "{{LMS_BASE}}Teaching" "Course skill"
click Leadership Development "{{LMS_BASE}}Leadership%20Development" "Course skill"
click Team Leadership "{{LMS_BASE}}Team%20Leadership" "Course skill"
```

---

## 9) Advice to Management — target: **Advanced**
```mermaid
mindmap
  root((Advice to Management — Advanced))
    Translating Tech→Business
    Options & Tradeoffs
    Risk & Cost Implications
    Roadmaps & Prioritization
    Exec Communication (briefs, decks)
    Course Skills
      Strategic Thinking
      Business Strategy
      Strategic Planning
      Presentation
      Technical Writing
      Stakeholder Engagement

click Translating Tech→Business "{{LMS_BASE}}technical%20to%20business%20value" "Tech→Business"
click Options & Tradeoffs "{{LMS_BASE}}decision%20analysis%20tradeoff%20frameworks" "Tradeoffs"
click Risk & Cost Implications "{{LMS_BASE}}IT%20risk%20management%20cost%20benefit" "Risk & cost"
click Roadmaps & Prioritization "{{LMS_BASE}}product%20roadmap%20prioritization%20frameworks" "Roadmaps"
click Exec Communication (briefs, decks) "{{LMS_BASE}}executive%20communication%20briefing%20decks" "Exec comms"
click Strategic Thinking "{{LMS_BASE}}Strategic%20Thinking" "Course skill"
click Business Strategy "{{LMS_BASE}}Business%20Strategy" "Course skill"
click Strategic Planning "{{LMS_BASE}}Strategic%20Planning" "Course skill"
click Presentation "{{LMS_BASE}}Presentation" "Course skill"
click Technical Writing "{{LMS_BASE}}Technical%20Writing" "Course skill"
click Stakeholder Engagement "{{LMS_BASE}}Stakeholder%20Engagement" "Course skill"
```
