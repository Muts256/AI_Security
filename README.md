#### AI_Security

AI Security is about making sure AI systems are protected from being attacked, manipulated, or used in unintended or harmful ways.

#### What AI Security protects

AI systems have multiple layers, and each one has risks:

#### 1. Data
Training data
Input data (prompts, user queries)
Sensitive information

#### 2. Model
Machine learning model (weights, logic)
Behaviour and decision-making

#### 3. Infrastructure
APIs
Cloud environments
GPUs / compute resources

#### 4. Outputs
Responses from LLMs
Predictions (fraud detection, malware detection, etc.)

#### Problem Statement

Modern AI-powered applications, particularly Large Language Model (LLM) systems integrated with Retrieval-Augmented Generation (RAG) and external tools, introduce new attack surfaces that traditional cybersecurity controls do not fully address.

These systems are vulnerable to AI-specific threats such as prompt injection, sensitive data leakage, and indirect data exfiltration through retrieval mechanisms or model outputs. Unlike traditional applications, LLM systems process untrusted user input alongside contextual and retrieved enterprise data, increasing the risk of unintended disclosure of confidential information.

This project/write-up explores how attackers can exploit weaknesses across different layers of an AI system, including the LLM agent layer, retrieval layer, and underlying data sources, to extract sensitive information or manipulate model behaviour.

The objective is to simulate real-world AI security threats, analyse attack paths, and demonstrate why layered security controls (input filtering, retrieval restrictions, and output validation) are required to mitigate prompt injection, data leakage, and data poisoning risks in enterprise AI systems.
