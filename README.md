# Industrial Power Supply Reliability Test & Analytics Platform

An automated **industrial reliability testing and data analytics platform** designed to monitor power-supply performance in real time, acquire test data, store measurements in a SQL database, analyze test results, and automatically determine **Pass/Fail** outcomes based on predefined acceptance criteria.

## Project Overview

The system integrates **industrial test automation, real-time data acquisition, database management, analytics, and automated decision-making** into a single workflow.

Instead of manually monitoring test parameters and evaluating results, the platform automates the complete data lifecycle:

**Test Equipment → Data Acquisition → Real-Time Monitoring → Data Pipeline → SQL Database → Analytics → Decision Engine → Pass/Fail**

This approach improves **test consistency, traceability, data integrity, and operational efficiency**.

## System Architecture

┌──────────────────────────────┐
│     Industrial Power Supply  │
│        Under Test (DUT)      │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│     Test & Instrumentation   │
│      Data Acquisition        │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│    Real-Time Monitoring      │
│         Dashboard            │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│      Automated Data          │
│        Pipeline              │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│        SQL Database          │
│   Test Data & Measurements   │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│       Data Analytics         │
│  Threshold & Trend Analysis  │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│     Decision Engine          │
│      Automated Pass/Fail     │
└──────────────┬───────────────┘
               │
               ▼
┌──────────────────────────────┐
│    Test Result / Report      │
└──────────────────────────────┘
```

## Key Features

### 1. Real-Time Data Acquisition

* Automated acquisition of electrical and performance parameters.
* Continuous monitoring during reliability testing.
* Real-time visualization of test measurements and equipment status.

### 2. Test Automation

* Automated execution and monitoring of reliability test sequences.
* Reduced dependency on manual measurements and operator intervention.
* Consistent application of predefined test conditions and acceptance criteria.

### 3. Data Pipeline

Implemented an automated data flow from **test instrumentation to persistent storage and analytics**, enabling structured processing of test measurements throughout the testing lifecycle.

### 4. SQL Data Management

Test measurements and test metadata are stored in a **relational SQL database**, enabling:

* Historical test-data analysis
* Test traceability
* Structured querying
* Result tracking
* Long-term data retention

### 5. Data Analytics

Test data is analyzed against predefined specifications and acceptance limits to identify:

* Parameter deviations
* Out-of-specification measurements
* Performance trends
* Test failures
* Reliability issues

### 6. Automated Decision Engine

A **rule-based decision engine** evaluates analytical results and automatically generates the final:

**PASS / FAIL **

classification.

This eliminates manual interpretation of large volumes of test measurements and provides consistent result evaluation.

### 7. Test Traceability & Reporting

Maintains historical test results and measurements to support:

* Reliability analysis
* Failure investigation
* Test traceability
* Performance comparison
* Engineering reporting

---

## 🔄 Data Flow

Acquire
   ↓
Validate
   ↓
Visualize
   ↓
Store
   ↓
Analyze
   ↓
Evaluate
   ↓
Pass / Fail
   ↓
Report
```

The workflow represents an **end-to-end industrial data pipeline**, transforming raw test measurements into actionable engineering decisions.

---

## 🧠 Analytics & Decision Logic

The platform uses predefined engineering specifications and acceptance criteria to evaluate test measurements.

Conceptually:

Raw Measurement
       ↓
Data Validation
       ↓
Parameter Analysis
       ↓
Specification Check
       ↓
Decision Logic
       ↓
PASS / FAIL
```

Example:

Measured Voltage → Compare with Specification
Measured Current → Compare with Specification
Temperature      → Compare with Limit
Performance Data → Evaluate Trend
                         ↓
                  Decision Engine
                         ↓
                    PASS / FAIL
```

---

## 🛠️ Technology & Domain

**Industrial Automation**

**Test & Measurement**

**Data Acquisition**

**Real-Time Monitoring**

**SQL / Relational Databases**

**Data Analytics**

**Data Visualization**

**Test Automation**

**Rule-Based Decision Systems**

**Reliability Engineering**

**Automated Reporting**

---

## What This Project Demonstrates

This project demonstrates an end-to-end understanding of how **industrial operational data can be converted into actionable insights**.

### Engineering

* Test-system design
* Instrumentation integration
* Automated reliability testing
* Real-time monitoring

### Data

* Data acquisition
* Data pipelines
* SQL data management
* Data validation
* Historical data analysis

### Analytics

* Threshold analysis
* Trend analysis
* Rule-based classification
* Automated decision-making

### Business / Operational Value

* Reduced manual intervention
* Improved test consistency
* Improved data traceability
* Faster result evaluation
* Centralized test history
* Automated Pass/Fail reporting

---

##  Project Objective

The primary objective was to build a system that moves reliability testing from a **manual, measurement-centric workflow** toward an **automated, data-driven testing and decision-making workflow**.

> **From raw industrial test data → to structured data → to analytics → to an automated engineering decision.**

---


##  Skills Demonstrated

`Industrial Automation` `Test Automation` `Data Acquisition` `SQL` `Data Analytics` `Real-Time Monitoring` `Data Visualization` `Reliability Testing` `Decision Analytics` `Database Integration` `Engineering Analytics`
## Contact
https://www.linkedin.com/in/sarita-bhat-b2a85b14

## Github
https://www.github.com/Saritabhat22
