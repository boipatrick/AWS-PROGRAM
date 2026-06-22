# Security, Compliance, and governance for AI solutions
AWS provides tools that ensure we build and secure artificial intelligence systems.


## Concepts of security,governance, and compliance in Organizations
Security, governance, and compliance might seem like the same function. The following are examples of the primary goals of each:
- Security: Ensure that confidentiality, integrity, and availability are maintained for organizational data and information assets and infrastructure.

- Governance: ensure that an organization can add value and manage risk in the operation of business.

- Compliance: ensure normative adherence to requirement across the functions of an organization

## Defense in depth for AI on AWS
Most common paradigms that organizations follow to integrate their security, governance and compliance functions while building on AWS. 

Here are some features of a defense in depth security strategy:
- A defense in depth security strategy uses multiple redundant defenses to protect your AWS accounts, workloads, data and assete. If one security control is compromised an additional layer comes in

- Applying adefense in depth security strategy to genAI workloads, data, and information can help create the best conditions to achieve business objectives. 

- You can use a combination of strategies, including AWS and AWS partner services and solutions at each layer to improve the security and resiliency of your genAI workloads


## Developing a high-level strategy for governance and compliance

This is important for ensuring the responsible deployment of these technologies. To begin, you might consider the following:

- Establish an AI governance framework
- Address AI compliance considerations


### Governance framework

The following is an example approach for establishing a governance framework

- Establish an AI governance board or committee
- Define roles and responsibilities
- Implement policies and procedures



# Compliance Standards for AI Systems

The importance of governance and compliance for AI systems

Advantages of governance and compliance
- Managing, optimizing and scaling the organizational AI initiative is at the core of the governance perspective. Incorporating AI governance into an organization's AI strategy is instrumental in building trust.

- Governance and compliance are important for AI systems used in business to ensure responsible and trustworthy AI practices. 

- Governance helps organizations establish clear policies, guidelines, and oversight mechanisms to ensure AI systems align with legal and regulatory requirements, in addition to ethical principles and societal values. 



### AWS Compliance
It empowers customers to understand the robust controls in place at AWS to maintain security and data protection in the AWS cloud.

Typically, customers decide their own tolerance for risk. The following are some specific security standards that might apply to AI systems

- NIST
- ENISA
- ISO
- SOC
- HIPAA
- GDPR
- PCI DSS

## AI standards compliance

These influence how organizations follow established guidelines, rules, and legal requirements that govern the development, deployment, and use of AI technologies. 

There are several key ways in which AI standards compliance differs from traditional software and technology requirements. The followin are some issues to consider:

- Complexity and opacity
AI systems can be highly complex with opaque decision-making processes. This makes it challenging to audit and understand how they arrive at outputs, which is crucial for compliance

- Dynamism and adaptability
AI systems are often dynamic and can adapt and change over time, even after deployment. This makes it difficult to apply static standards, frameworks and mandates

- Emergent capabilities
these refer to unexpected or unintended capabilities that arise as a result of complex interactions within the AI system, in contrast to capabilities tha are explicitly programmed. 

- Unique risks
AI poses novel risks such algorithmic bias, privacy violations, misinfomation, and AI-powered automation displacing human wokers. 

- Algorithm acountability

it refers to the idea that algorithms, especially those used in AI systems, should be transparent, explainable, and subject to oversightand accountability measures. 


## Regulated workloads

Regulated is a common term used to indicate that a workload might need special consideration, because of some form of compliance that must be achieved. 

The term often refers to customers who work in industries with high degrees of regulatory ompliance requirements or high industrial demands.

Some example industries are as follows:

- Financial services
- Healthcare
- Aerospace

Example regulated workloads
- HR workloads
- Safety workloads
- Inspection and regulatory compliance workloads 

Which Indicators tell you that your workload might be regulated
 - when you must comply with regulatory frameworks such as HIPAA, GDPR, PCI DSS and others

 ## AWS Services for Governance and Compliance

 AWS takes a proactive and collaborative approach to governance and compliance when it comes to AI and generative workflows. 

 It has many services and features to assist with the governance and regulation compliance. Here are some:
 1. AWS config - AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past so that you can see how the configurations and relationships change over time.

 2. Amazon Inspector - Amazon Inspector is a vulnerability management service that continuously scans your AWS workloads for software vulnerabilities and unintended network exposure.  

3. AWS Audit Manager- AWS Audit Manager helps you continually audit your AWS usage to streamline how you manage risk and compliance with regulations and industry standards.

4. AWS Artifact - AWS Artifact provides on-demand downloads of AWS security and compliance documents, such as AWS ISO certifications, PCI reports, and SOC Reports. 
 
5. AWS Cloudtrail - AWS CloudTrail helps you perform operational and risk auditing, governance, and compliance of your AWS account. Actions taken by a user, role, or an AWS service are recorded as events in CloudTrail. Events include actions taken in the AWS Management Console, AWS Command Line Interface (AWS CLI), and AWS SDKs and APIs. 

6. AWS Trusted Advisor - AWS Trusted Advisor helps you optimize costs, increase performance, improve security and resilience, and operate at scale in the cloud. 

## Data governance strategies
They involve an approach to managing the data lifecycle, from data collection and storage, to data usage and security. Key datagovernance strategies that organizations can consider:

1. Data quality and integrity - To ensure the quality and integrity of your data, follow these steps:

- Establish data quality standards and processes to ensure the accuracy, completeness, and consistency of data used for AI and generative AI models.
- Implement data validation and cleansing techniques to identify and address data anomalies and inconsistencies.
- Maintain data lineage and provenance to understand the origin, transformation, and usage of data.
 Data lineage and provenance are concepts that describe the origins, history, and transformations of data as it flows through an organization.

2. Data protection and privacy

To ensure data protection and privacy, implement the following steps:

- Develop and enforce data privacy policies that protect sensitive or personal information.
- Implement access controls, encryption, and other security measures to safeguard data from unauthorized access or misuse.
- Establish data breach response and incident management procedures to mitigate the impact of any data security incidents.


3. Data lifecycle management
Some steps for data lifecycle management include the following:

- Classify and catalog data assets based on their sensitivity, value, and criticality to the organization.
- Implement data retention and disposition policies to ensure the appropriate storage, archiving, and deletion of data.
- Develop data backup and recovery strategies to ensure business continuity and data resilience.

4. Responsible AI
Some steps to ensure responsible AI include the following:

- Establish responsible frameworks and guidelines for the development and deployment of AI and generative AI models, addressing issues like bias, fairness, transparency, and accountability.
- Implement processes to monitor and audit AI and generative AI models for potential biases, fairness issues, and unintended consequences.
- Educate and train AI development teams on responsible AI practices.

5. Governance structure and roles

Follow these steps to establish governance structures and roles:

- Establish a data governance council or committee to oversee the development and implementation of data governance policies and practices.
- Define clear roles and responsibilities for data stewards, data owners, and data custodians to ensure accountable data management.
- Provide training and support to artificial intelligence and machine learning (AI/ML) practitioners and data users on data governance best practices.

6. Data sharing and collaboration

You can manage data sharing and collaboration as follows:

- Develop data sharing agreements and protocols to facilitate the secure and controlled exchange of data across organizational boundaries.
- Implement data virtualization or federation techniques to enable access to distributed data sources without compromising data ownership or control.
- Foster a culture of data-driven decision-making and collaborative data governance across the organization.



## Concepts in data governance

Data management concepts

These concepts help ensure the quality, integrity, and governance of the data that underpins the development, training, and deployment of AI models.

- Data Lifecycles
Data lifecycles refer to the management of data throughout its entire lifespan, from creation to eventual disposal or archiving. In the context of AI workloads, the data lifecycle encompasses the following stages in the lifecycle of data used to train and deploy AI models:

Collection
Processing
Storage
Consumption
Disposal or archiving


- Data logging
Data logging involves the systematic recording of data related to the processing of an AI workload. This can include the following: 

Tracking inputs
Tracking outputs
Model performance metrics
System events

Effective data logging is necessary for debugging, monitoring, and understanding the behavior of AI systems.

- Data residency
Data residency refers to the physical location where data is stored and processed. In the context of AI workloads, data residency considerations might include the following:

Compliance with data privacy regulations
Data sovereignty requirements
Proximity of data to the compute resources used for training and inference

- Data monitoring
Data monitoring involves the ongoing observation and analysis of data used in AI workloads. This can include the following: 

Monitoring data quality
Identifying anomalies (An anomaly is an unexpected data point that significantly deviates from the norm.)
Tracking data drift (Data drift is observed when the distribution of the input data changes over time.)
Monitoring also helps to ensure that the data being used for training and inference remains relevant and representative.

- Data analysis
Data analysis methods are used to understand the characteristics, patterns, and relationships within the data used for AI workloads.



These methods help to gain insights into the data. They include the following: 

Statistical analysis
Data visualization
Exploratory data analysis (EDA): EDA is a task to discover patterns, understand relationships, validate assumptions, and identify anomalies in data.


- Data retention 
Data retention policies define how long data should be kept for AI workloads. This can be influenced by factors such as the following: 

Regulatory requirements
Maintaining historical data for model retraining
Cost of data storage
Effective data retention strategies can help organizations manage the lifecycle of data used in their AI systems.


Approaches for Implementing Governance Strategies

## Governance Strategies
When working with genAi solutions, it is important to establish and follow governance strategies to ensure responsible development and deployment. 
1. Policies - develop clear and comprehensive policies that outline the organization's approach to generative AI, including principles, guidelines, and responsible AI considerations
2. Review cadence
Implement a regular review process to assess the performmance, safety and responsible AI implications of the gen AI solutions

3. Review Strategies
Develop comprehensive strategies that cover both technical and non-technical aspects of the GenAI solutions

- Technical reviews should focus on model performance, data quality, and the robustness of the underlying algorithms.
- Non-technical reviews should assess the solutiuons' alignment with organizational policies, responsible AI principles, and regulatory requirements. 

- Incorporate testing and validation procedures to validate the outputs of the genAI solutions before deployment.

- Establish clear decision-making frameworks to validate the outputs of the GenAI solutions before deployment. 

- 
4. Transparency standards
 commit to maintaining high standards of transparency in the development and deployment of genAI solutions by ensuring

 - Include publishing info about the AI models, their training data, and the key decisions made during the development process

 - Provide clear and accessible documentation on the capabilities, limitations, and intended use cases for the genAI solutions.

 - Establish channels for stakeholders, including end-users, to provide feedback and raise concerns about the solutions.


 5. Team training requirements
 Ensure that all team members involved in the development and deployment of genAI solutions are adequately trained on relevant policies, guidelines, and best practices

 Some suggestions for team training include the following:
 - Provide comprehensive training on bias migration, and responsible AI practices

 - Encourage cross-functional collaboration and knowledge-sharing to foster a culture of responsible AI development.

 - Consider implementing ongoing training and certification programs to keep team members up to date with the latest advancements and regulatory changes. 


 ### Monitoring an AI system
 - Monitoring
 It is necessary to ensure its performance, reliability, and compliance with the intended use case. Effective monitoring can help in identifying issues, optimize system performance, and maintain overall system health.

 The following are some key aspects to consider when monitoring an AI system
 1. Performance metrics
 2. Infrastructure monitoring
 3. Monitoring for bias and fairness
 4. Monitoring for compliance and responsible AI



 # Security and Privacy Considerations for AI Systems

 ## Security considerations
 1. Threat detection
 To detect threats to your AI systems do the following:
 - Identify and monitor for potential security threats, such as malicious actors attempting to exploit vulnerabilities in AI systemsor using GenAI for malicious purposes

- Developing and deploying AI-powered threat detection systems. 
 
 2. Vulnerability management
 To help manage vulnerability, do the following:
 - identify and address vulnerabilities in AI and generative AI systems,including software bugs, model weaknesses and potential attack vectors

 - Regularly conduct security assessments, penetration testing and code reviews to uncover and address vulnerabilities

 - Implement robust patch management and update processes to ensuer that AI systems are kept up to date and secure

3. Infrastructure Protection
to ensure that your infrastuture is protected, do the following:
- secure the underlying infrastucture that supports AI  and generative AI systems
- Implement strong access controls, network segmentation, encyrption and other security measures to protect infrastucture from unauthorized access and attacks
- Ensure that the AI infrastructure is resilient and can withstand failures, attacks, or other disruptions. 

4. Prompt Injection
In these attacks, adversaries attempt to manipulate the input prompts of gen AI models to generate malicious or undesirable content. To reduce the risk, do the following:
- Employ techniques such as prompt filtering, sanitization, and validation, to ensure that the input prompts are safe and do not contain malicious content.

- Develop robust models and training procedures that are resistant to prompt injection attacks.


5. Data encryption
to protect the confidentiality and integrity of the data used to train and deploy AI and gen AI models, do the following:
- Implement strong encryption mechanisms to secure both data at rest and data in transit. 

- Ensure that the encryption keys are properly managed and protected from unauthorized access. 



The OWASP Top 10 for LLMs

The Open Web Application Security Project (OWASP) Top 10 is the industry standard list of the top 10 vulnerabilities that can impact a generative AI LLM system. These vulnerabilities are as follows:

1. Prompt injection: Malicious user inputs that can manipulate the behavior of a language model

2. Insecure output handling: Failure to properly sanitize or validate model outputs, leading to security vulnerabilities

3. Training data poisoning: Introducing malicious data into a model's training set, causing it to learn harmful behaviors

4. Model denial of service: Techniques that exploit vulnerabilities in a model's architecture to disrupt its availability

5. Supply chain vulnerabilities: Weaknesses in the software, hardware, or services used to build or deploy a model

6. Sensitive information disclosure: Leakage of sensitive data through model outputs or other unintended channels

7. Insecure plugin design: Flaws in the design or implementation of optional model components that can be exploited

8. Excessive agency: Granting a model too much autonomy or capability, leading to unintended and potentially harmful actions

9. Overreliance: Over-dependence on a model's capabilities, leading to over-trust and failure to properly audit its outputs

10. Model theft: Unauthorized access or copying of a model's parameters or architecture, allowing for its reuse or misuse


The AWS Shared Responsibility Model

The shared model helps relieve the customer's operational burden. AWS operates, manages, and controls the host operating system and virtualization layer down to the physical security of the facilities in which the service operates. 

The customer assumes responsibility and management of the guest operating system. This includes updates, security patches, and other associated app software in addition to the configuration of the AWS provided security group firewall.

### AWS services for securing AI systems
- Defense in depth security
The goal of this strategy is to provide multiple layers of security around your data and workloads. 

If one layer is compromised, the other layer will isolate, slow down, or stop a threat actor. The multiple layers prevent the threat actor from moving laterally, escalating privileges, exfilrating or manupulating data, and so on. 

### Getting started with defense in depth

There are four foundational AWS security services recommended for any workload, any customer, and any industry. 

1. Security Hub
2. AWS KMS
3. GuardDuty
4. AWS Shield Advanced

Each service provides protection in one of the core security domains of incident response, data protection, threat detection, and network and application protection 





### Understanding Data and Model Lineage
Data and model lineage refer to the detailed record of origin, transformation, and evolution of data models used in AI and generative AI systems. 

This info is crucial for understanding the origin, reliability and potiental biases or limitations of the data and models used in these systems.

### What is source citation and data origins documentation

- citing sources and documenting origins

Source citation and documenting data origins are essential tasks that contribute to securing your AI systems. These tasks help ensure the transparency, traceability, and accountability of the data and information used in the AI system.

This is important for maintaining the integrity and trustworthiness of the system. These tasks involve providing info about the sources of the data used to train the generative AI model and the provenance of the data.

## Source CITATION
refers to the act of properly attributing and acknowledging the sources of the data used to train the model

It is necessary to identify the sources from which the training data was collected, such as the following:

- Datasets
- Databases
- Other sources

In addition it is necessary to identify the licenses, terms of  use, or permissions associated with the data

Accurate source citation helps users and stakeholders understand the origins of the information used to generate the AI-produced content. 

### Documenting Data Origins

In the context of generative AI it involves providing detailed info about the provenance, or the place of origin of the data used to train the model

This includes the following:
- Details about the data collection process
- The methods used to curate and clean the data
- Any preprocessing or transformations applied to the data

Documenting the data origins is important for understanding the potential biases, limitations, or quality issues that might be present in the training data. This can ultimately impact the performance and reliability if the gen AI model.

## Tools and techniques

by the use of these tools and techniques, gen AI systems can effectively document the sources and origins of the data used in their development. 

This promotes transparency, accountability, and reproducibility.
The following describes some of the common techniques and tools

- Data lineage technique used to track the history of data including its origin, transformation, and movement through different systems

In gen AI it can be used to document the journey of the training data, from its initial sources to final model.

This info can be used to provide detailed source citations and data origin documentation for transparency and reproducibility.

- Cataloging involves the sytematic organization and documentation of the datasets, models and other resources used in the development of a Gen AI system

A well maintained catalog can serve as a comprehensive repository of information about the components of the AI system. In addition, this information can include sources, licenses and metadata associated with the training data.

Cataloging facilitates the effective management and communication of data origins and source citations to users and stakeholders


- Model cards are standardized format for documenting the key details about an ML model, including its intended use, performance characteristics, and potential limitations. 

In Gen AI, model cards can be used to provide source citations and data origin documentation. This helps users understand the provenance(lineage) of the data used to train the model. 

Model cards can include details about the datasets ued, their sources, licenses and any known biases or quality issues in the training data. 

### Amazon SageMaker Model Cards

You can use AMazon SageMaker Model Cards to document critical details about your ML models in a single place for streamlined governance and reporting.

They can contain catalog details, such as the intended use and risk rating of a model, training details and metrics, evaluation results and observations

It also catalogs additional call-outs such as considerations, recommendations, and custom information. By creating model cards, you can do the following:
- Provide guidance on how a model should be used
- Support audit activities with detailed descriptions of model training and performance. 
- Communicate how a model is intended to support business goals. 

## Best Practices for Secure Data Engineering

