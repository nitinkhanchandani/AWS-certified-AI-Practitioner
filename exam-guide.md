### **Summary of the AWS Certified AI Practitioner (AIF-C01) Exam Guide**

This exam is designed for individuals who need a high-level, foundational understanding of Artificial Intelligence (AI), Machine Learning (ML), and Generative AI concepts and their application using AWS services. It is not intended for deep technical experts who build models from scratch.

---

#### **Target Candidate**

*   **Experience Level:** Up to 6 months of exposure to AI/ML on AWS.
*   **Role:** A user or stakeholder of AI/ML solutions, not necessarily a builder. The focus is on understanding what is possible, identifying use cases, and knowing which AWS services to apply.
*   **Assumed Knowledge:** Familiarity with core AWS services (EC2, S3, IAM), the shared responsibility model, and basic cloud concepts like Regions and Availability Zones.

#### **Key Exam Details**

*   **Total Questions:** 65 questions (50 scored, 15 unscored for future evaluation).
*   **Scoring:** Scored on a scale of 100–1,000, with a **minimum passing score of 700**.
*   **Scoring Model:** Compensatory, meaning you only need to pass the overall exam, not each individual domain.
*   **Question Types:**
    *   Multiple choice (one correct answer)
    *   Multiple response (two or more correct answers)
    *   Ordering, Matching, and Case Study questions.

---

#### **Exam Content Domains (The Core Syllabus)**

The exam is broken down into five domains with different weightings:

**Domain 1: Fundamentals of AI and ML (20%)**
*   **Focus:** Core concepts and terminology.
*   **Key Topics:** Definitions of AI, ML, deep learning, NLP, computer vision. Differentiating between them. Understanding types of ML (supervised, unsupervised, reinforcement) and types of data (labeled, tabular, image, text). Knowing the stages of an ML pipeline (data collection, training, deployment, etc.) and identifying AWS services for each stage (e.g., SageMaker, Transcribe, Comprehend).

**Domain 2: Fundamentals of Generative AI (24%)**
*   **Focus:** The core concepts behind Generative AI.
*   **Key Topics:** Understanding terms like foundation models, LLMs, tokens, embeddings, and prompt engineering. Identifying use cases for GenAI (summarization, chatbots, code generation). Knowing the advantages (adaptability, simplicity) and disadvantages (hallucinations, inaccuracy). Familiarity with AWS services for GenAI like **Amazon Bedrock**, **Amazon Q**, and **SageMaker JumpStart**.

**Domain 3: Applications of Foundation Models (28% - Highest Weighting)**
*   **Focus:** How to use and apply foundation models effectively.
*   **Key Topics:** How to select a pre-trained model based on criteria like cost, modality, and size. Understanding **Retrieval Augmented Generation (RAG)** and its business value. Knowing which AWS services can be used as vector databases (e.g., OpenSearch, Aurora, Neptune). Understanding prompt engineering techniques (zero-shot, few-shot, chain-of-thought) and the basics of fine-tuning.

**Domain 4: Guidelines for Responsible AI (14%)**
*   **Focus:** The ethical and practical considerations of using AI.
*   **Key Topics:** Understanding and identifying AI features like fairness, bias, inclusivity, robustness, and safety. Recognizing legal and business risks (e.g., intellectual property infringement, biased outputs). Knowing about tools to detect and monitor bias, such as **Amazon SageMaker Clarify**, and the importance of transparency through tools like **SageMaker Model Cards**.

**Domain 5: Security, Compliance, and Governance for AI Solutions (14%)**
*   **Focus:** Securing AI systems and adhering to regulations.
*   **Key Topics:** Using standard AWS security services (IAM, Macie, PrivateLink) to secure AI workloads. Understanding AI-specific security risks like **prompt injection**. Knowing about data governance, source citation, and compliance standards (e.g., ISO, SOC). Identifying AWS services that assist with compliance (e.g., AWS Artifact, CloudTrail, Config).

---

#### **Important Scope Boundaries**

It is critical to know what you are **NOT** expected to do on this exam.

**Out-of-Scope (You DON'T need to know how to do these):**
*   Write code for AI/ML models or algorithms.
*   Perform complex data engineering or feature engineering.
*   Perform hyperparameter tuning or model optimization.
*   Build and deploy complex AI/ML pipelines or infrastructure.
*   Conduct deep mathematical or statistical analysis of models.

**In-Scope AWS Services (You SHOULD be familiar with what these do):**
*   **Core AI/ML:** Amazon SageMaker, Amazon Bedrock, Amazon Comprehend, Amazon Rekognition, Amazon Transcribe, Amazon Lex, Amazon Polly, Amazon Kendra, Amazon Q.
*   **Supporting Data/Analytics:** S3, Glue, OpenSearch Service, Redshift, Aurora, Neptune.
*   **Security & Governance:** IAM, Macie, CloudTrail, Config, AWS Artifact.
*   **Core Infrastructure:** EC2, Lambda, VPC.