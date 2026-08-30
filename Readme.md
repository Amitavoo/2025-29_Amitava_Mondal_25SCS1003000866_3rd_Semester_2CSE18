# AI-Driven Amazon Ads Optimization — Internship

This repository contains my **internship report, presentation, project documentation, and completion credentials** from my internship as a **Gen AI Engineer Intern at Digital Hercules Innovations (CreateAiGenie)**.

The internship focused on a real-world **B2B SaaS platform for Amazon Ads optimization**, with my work primarily involving **API handling and integration**, along with advertising-data processing, feature engineering, and ML-based ad-spend optimization workflows. 

---

## 👤 Student Details

| Field               | Details                                                    |
| ------------------- | ---------------------------------------------------------- |
| **Name**            | Amitava Mondal                                             |
| **Institute**       | IILM University, Greater Noida, U.P.                       |
| **Programme**       | B.Tech CSE (Artificial Intelligence)                       |
| **Batch**           | 2025–2029                                                  |
| **Internship Role** | Gen AI Engineer Intern                                     |
| **Organization**    | Digital Hercules Innovations (CreateAiGenie)               |
| **Domain**          | Generative AI · Machine Learning · Amazon Ads Optimization |
| **Duration**        | April 2026 – [Completion Date]                             |
| **LinkedIn**        | [amitavoo](https://linkedin.com/in/amitavoo)               |
| **GitHub**          | [Amitavoo](https://github.com/Amitavoo)                    |

---

# 📌 About the Internship

The internship involved working on an **AI-driven Amazon Ads optimization platform** designed to process advertising-performance data and support automated campaign optimization.

My primary area of contribution was **API handling and integration**. I worked with API request/response flows and studied how advertising data moves between external services, cloud-based components, and the backend application.

Alongside API-related work, I supported the **AI/ML workflow** through advertising-data preprocessing, feature engineering, and work related to ML model prototypes for ad-spend rule automation. 

The internship provided practical exposure to:

* REST API integration
* Backend systems
* AWS cloud services
* Data ingestion pipelines
* Data preprocessing
* Feature engineering
* Machine Learning
* Generative AI
* Advertising optimization
* Authentication and secure communication

---

# 🎯 Project Objectives

The major objectives of the project were:

* Handle and understand API-based communication between system components
* Establish reliable advertising-data flows
* Work with real advertising-performance data
* Preprocess and structure data for ML workflows
* Perform feature engineering
* Support ML model prototypes
* Support ad-spend rule automation
* Understand secure API communication
* Explore the role of Generative AI in advertising optimization
* Reduce repetitive manual analysis through automation

---

# 🔍 Problem Statement

Amazon advertising generates large amounts of campaign and performance data that must be continuously processed and analyzed.

Manual campaign analysis can be:

* Time-consuming
* Difficult to scale
* Dependent on multiple data sources
* Prone to repetitive work
* Difficult to manage as campaign volume increases

The project therefore addresses the problem of creating an efficient workflow for:

```text
Advertising Data
       ↓
API Integration
       ↓
Data Ingestion
       ↓
Data Processing
       ↓
ML / Rule Analysis
       ↓
Optimization Insights
```

---

# 🏗️ System Architecture

The larger platform consists of multiple interconnected components.

```text
                    Users
                      │
                      ▼
               React Frontend
                      │
                      ▼
                  REST APIs
                      │
                      ▼
                Django Backend
                      │
          ┌───────────┼───────────┐
          ▼           ▼           ▼
         AWS       Amazon APIs   AI / ML
          │           │           │
       SQS/Lambda    OAuth      Agents / LLM
          │           │           │
          └───────────┼───────────┘
                      ▼
              Optimization System
```

### My Contribution

My primary focus was on the **API-handling and integration layer**, while also contributing to the data and ML workflow.

I did not treat the entire architecture as my individual implementation; rather, I worked on specific components within the larger platform.

---

# 🔌 API Handling

API integration was one of the major technical areas of my internship.

The general API workflow was:

```text
API Request
     ↓
Authentication
     ↓
Request Validation
     ↓
Backend Endpoint
     ↓
Business Logic
     ↓
Data Processing
     ↓
API Response
```

### Key concepts

* REST APIs
* HTTP/HTTPS
* Request/response handling
* Authentication
* Validation
* Error handling
* Secure communication
* Backend integration

---

# ☁️ AWS Data Ingestion

The platform uses AWS components for advertising-data ingestion.

A simplified flow is:

```text
Amazon Marketing Stream
          ↓
         SQS
          ↓
       Lambda
          ↓
   Secure HTTP Request
          ↓
     Django Backend
          ↓
    Data Processing
```

### Components

**Amazon Marketing Stream**
Provides advertising-related data.

**Amazon SQS**
Provides asynchronous message queuing.

**AWS Lambda**
Processes incoming messages.

**Backend API**
Receives the processed information for further processing.

The architecture also uses secure request signing mechanisms for relevant API communication.

---

# 🔐 Authentication & Security

Different communication paths use different security mechanisms.

| Mechanism       | Purpose                                       |
| --------------- | --------------------------------------------- |
| **JWT**         | Application authentication                    |
| **OAuth**       | Authorized communication with Amazon services |
| **HMAC-SHA256** | Request signing                               |
| **HTTPS**       | Secure data transmission                      |
| **AWS IAM**     | AWS resource access control                   |

This helped me understand that API integration involves not only sending requests but also ensuring **authentication, authorization, validation, and secure communication**.

---

# 📊 Data Processing & Feature Engineering

Advertising data must be processed before it can be effectively used by ML workflows.

```text
Raw Advertising Data
        ↓
Data Cleaning
        ↓
Transformation
        ↓
Data Preparation
        ↓
Feature Engineering
        ↓
ML-Ready Dataset
```

Potential advertising metrics include:

* Impressions
* Clicks
* Spend
* Sales
* CTR
* CPC
* Conversions
* ROAS / ACOS

My internship work included **dataset preprocessing and feature engineering** for the ML workflow. 

---

# 🤖 Machine Learning & Rule Automation

The platform combines advertising data with rule-based and ML-based approaches.

### Rule-based optimization

```text
Campaign Metrics
       ↓
Rule Evaluation
       ↓
Condition / Threshold
       ↓
Optimization Recommendation
```

Example:

```text
IF ACOS is high
AND conversion rate is low
        ↓
Flag Campaign
```

### ML workflow

```text
Historical Data
      ↓
Feature Engineering
      ↓
ML Model
      ↓
Prediction / Analysis
      ↓
Optimization
```

My internship involved supporting **ML model prototypes for ad-spend rule automation**. 

---

# 🧠 Generative AI — Proposed Extension

A potential extension of the platform is to use **Claude through Amazon Bedrock** as an LLM reasoning layer.

```text
Campaign Data
      ↓
Backend
      ↓
Relevant Metrics
      ↓
Claude on Amazon Bedrock
      ↓
Reasoning
      ↓
Optimization Recommendation
```

Claude could assist with:

* Campaign diagnosis
* Performance interpretation
* Identifying possible causes
* Comparing optimization strategies
* Generating explanations
* Producing structured recommendations

### Safety Principle

```text
Claude
   ↓
Recommendation
   ↓
Backend Validation
   ↓
Human Approval
   ↓
Action
```

The LLM should provide reasoning and recommendations while application logic and human approval remain responsible for executing business-critical actions.

> **Note:** This is a proposed/future extension unless explicitly implemented during the internship.

---

# 🧩 Agentic AI — Future Scope

The platform can potentially be extended into an agentic workflow where an LLM can use controlled tools.

```text
                   Claude
                     │
        ┌────────────┼────────────┐
        ▼            ▼            ▼
 Get Campaign    Get Ad Group   Get Sales
   Metrics         Metrics        Data
        │            │            │
        └────────────┼────────────┘
                     ▼
                AI Reasoning
                     ▼
              Recommendation
```

For example, an agent could:

1. Retrieve campaign metrics
2. Examine ad-group performance
3. Retrieve conversion information
4. Analyze the available data
5. Identify potential issues
6. Generate an optimization recommendation

---

# 🛠️ Technologies & Tools

### Programming

`Python` · `SQL` · `JavaScript`

### Backend & APIs

`Django` · `REST APIs` · `JWT` · `OAuth`

### Cloud

`AWS` · `Azure` · `AWS SQS` · `AWS Lambda`

### AI / ML

`Machine Learning` · `Generative AI` · `LLMs` · `Feature Engineering`

### Security

`HTTPS` · `HMAC-SHA256` · `OAuth` · `JWT` · `IAM`

### Development

`Jupyter Notebook` · `Git` · `GitHub` · `Docker`

These technologies align with the technical skills and internship work described in my resume. 

---

# 🔄 Methodology

The project followed a structured workflow:

```text
1. Understand System Architecture
              ↓
2. Understand API Flow
              ↓
3. Handle API Requests / Responses
              ↓
4. Understand Data Ingestion
              ↓
5. Preprocess Advertising Data
              ↓
6. Perform Feature Engineering
              ↓
7. Support ML / Rule Workflows
              ↓
8. Test and Evaluate
              ↓
9. Generate Optimization Insights
```

### Overall methodology

**API Integration → Data Ingestion → Data Processing → Feature Engineering → ML/Rule Processing → Evaluation**

---

# ⚙️ Challenges & Learnings

### API Complexity

Understanding how multiple services communicate through APIs.

**Learning:** Request/response lifecycle and service integration.

### Authentication

Different services require different authentication approaches.

**Learning:** JWT, OAuth, HMAC and IAM concepts.

### Data Quality

Raw advertising data requires preprocessing.

**Learning:** Data cleaning and feature engineering.

### Continuous Data

Advertising data can arrive continuously.

**Learning:** Asynchronous processing and message queues.

### AI Reliability

AI-generated recommendations should not directly execute critical actions.

**Learning:** Separate AI reasoning from validation and execution.

---

# 🏆 Project Outcomes

Through the internship, I gained practical experience in:

* API integration and handling
* Backend communication
* AWS cloud services
* Data ingestion
* Data preprocessing
* Feature engineering
* Machine-learning workflows
* Ad-spend rule automation
* Generative AI concepts
* Secure API communication
* Production-oriented AI systems

My internship experience included supporting **real advertising-performance data pipelines and ML model prototypes for Amazon Ads optimization**. 

---

# 📚 Key Learnings

The internship helped me understand that developing an AI system involves much more than selecting an AI model.

A reliable production-oriented AI system requires:

```text
Reliable APIs
      +
Quality Data
      +
Cloud Infrastructure
      +
Machine Learning
      +
AI Reasoning
      +
Security
      +
Validation
      ↓
Reliable AI System
```

I also gained practical exposure to working with existing systems, debugging integration problems, understanding data pipelines, and connecting technical solutions with real business requirements.

---

# 🚀 Future Scope

Potential future improvements include:

* Integrating **Claude through Amazon Bedrock**
* Adding agentic AI workflows
* Implementing controlled tool calling
* Predictive campaign optimization
* Automated campaign anomaly detection
* Human-in-the-loop approval
* AI-assisted bid recommendations
* Cost-aware LLM model selection
* Improved campaign-performance forecasting

---

# 📁 Repository Contents

```text
├── Internship_Report.pdf
├── Internship_Presentation.pptx
├── Certificate_of_Internship.png
├── Internship_Offer_Letter.png
└── README.md
```

> Update the filenames above to match the actual files you upload to your repository.

---

# 📄 Report Structure

The internship report follows the academic structure prescribed by **IILM University**:

1. Candidate's Declaration
2. Acknowledgement
3. Internship Completion Certificate
4. Project Description

   * 4.1 Introduction
   * 4.2 Organization Profile
   * 4.3 Problem Statement
   * 4.4 Project Objectives
   * 4.5 Scope of the Project
   * 4.6 Technologies and Tools Used
   * 4.7 System Architecture
   * 4.8 Methodology
   * 4.9 Expected Outcomes / Project Outcomes
   * 4.10 Certificates and Supporting Evidence
5. Bibliography / References

The university template specifies A4 formatting, Times New Roman, 12-point body text, 14-point bold main headings, 1.5 line spacing, justified paragraphs, and centered page numbering. 

---

# 📚 References

* Amazon Web Services — Amazon Bedrock Documentation
* Amazon Web Services — AWS Lambda Documentation
* Amazon Web Services — Amazon SQS Documentation
* Amazon Ads — API Documentation
* Django Documentation
* Python Documentation
* Anthropic — Claude Documentation
* Internal project architecture and technical documentation
* Internship project resources

---

## 🙏 Acknowledgement

I would like to express my gratitude to **Digital Hercules Innovations (CreateAiGenie)** for providing me with the opportunity to work on a real-world AI-driven advertising optimization platform.

I am grateful to the AI/ML team and mentors for their guidance and technical support throughout the internship. I would also like to thank **IILM University, Greater Noida** for providing the academic support and opportunity to gain practical industry experience.

---

### About Me

**Amitava Mondal**
B.Tech CSE — Artificial Intelligence
IILM University, Greater Noida

**Interests:**
`LLMs` · `RAG` · `Agentic AI` · `Generative AI` · `Neural Architecture Design` · `ML Workflow Automation`

My broader projects include **ResearchMind**, a multi-agent AI research assistant, **Video-Agent**, a RAG-based meeting intelligence system, and an **end-to-end ML movie recommendation system**. 
