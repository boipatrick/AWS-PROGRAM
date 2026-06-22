# ML Development lifecycle
It refers to the end to end process of developing, deploying , and maintaining machine learning models.

The end-to-end ml lifecycle process includes the following phases:
- business goal identification
- ML problem framing
- Data processing(data collection, data preprocessing, and feature engineering)
- model development(training, tuning and evaluation)

- Model deployment
- Model monitoring
- Model retraining

As a company follows these steps, it is necessary to have seamless collaboration among the diverse roles, such as product managers, developers, data scientists and engineers. 

# Developing ML solutions with Amazon Sagemaker AI

## Amazon SageMaker AI

It is a fully managed ML service. In a single unified visual interface, you can perform the following tasks:
- collect and prepare data
- build and train machine learning models
- deploy the models and monitor the performace of their predictions. 


## SageMaker AI environments

Amazon Sagemaker studio is the recommended option to access SageMaker AI.

It is a web-based UI that provides access to all SageMaker AI environments and resources.


### Sources of ML Models

#### Model Implementations

Sagemaker AI supports pre-trained models, built-in algorithms, and custom Docker images.

The following are ways to use SageMaker AI to build your ML model:

- pretrainerd models require the least effort and are models ready to deploy or to fine-tune and deploy using SageMaker jumpstart

- builtin models available in SageMaker AI require more effort and scale if the dataset is large and significant resources are needed to deploy the model

- If there is no built-in solution that works, try to develop one that uses pre-made images for ML and deep learning frameworks for supported framworks such as scikit-learn, TensorFlow, PyTorch etc

- You can build your own custom Docker image that is configured to install the necessary packages or software. 

### SageMaker AI built-in algorithms

There are different types of ML algorithms based on your use case and requirements and the data you have. 

#### SageMakerJumpstart
with SageMaker jumpstart, you can deploy, fine-tune, and evaluate pre-trained models from the most popular model hubs. 

It provides pretrained opensource models from leading providers for a range of problem type to help you get started with ML

You can incrementally train and tune these models before deployment.  It also provides solution templates that setup infrastructure for common use cases and runnable example notebooks for ML with SageMaker AI


# Machine Learning Models Performance Evaluation

## Model Evaluation

We'll look at which metrics can be used for two very common ML algorithms clasification and regression.

### Model evaluation datasets
Evaluation occurs after a model is trained. The data you use is partitioned into three parts
- training set
- validationset
- test set

The training set is used to train the model. The validation and test sets are the ones that you will use to evaluate the trained model performance

Validation set- to begin evaluating how the model responds in non-training environment, start by looking at the data that was set aside as the validation set.  You want to make sure that the model generalizes to data it has not seen.

The model still needs to be improved before determining that it's ready for production. 

Test set- after you've improved the model using that validation data, you're ready to test it one last time to ensure its predictive quality meets your standards

### Model Fit
It is important for understanding the root cause of poor model accuracy. This understanding will guide you  to take corrective steps.

You can determine whether a predictive model is underfitting or overfitting the training data by looking at the prediction error on the training data and the evaluation data. 

- Overfitting - is when the model performs well on the training data but does not perform well on the evaluation data. This is because the model memorized the data it has seen and is unable to generalize to unseen examples. 


- Underfitting - is when the model performs poorly on the training data. This is because the model is unable to capture the relationship between the input examples(often called X) and the target values(often called Y)

- Balanced - the model is balanced when it is not overfit or underfit to the training data. 


### Bias and Variance

when evaluating models, both bias and variance contribute to errors the model makes on unseen data, which affects its generalization. 

In ML, the ideal algorithm has low bias and can accurately model the true relationship. The ideal algorithm also has low variability, by producing consistent predictions across different data sets. 

### Classification and regression problems

How you evaluate a ML model depends on what kind of ML problem you're working with. Here we'll look at both classification and regression metrics

#### Classification Metrics
- Accuracy
- Precision
- Recall
- F1 
- AUC-ROC

#### Regression Metrics
- Mean squared error
- R squared


### Classification Problems


### Confusion matrix
A confusion matrix can help classify why and how a model gets something wrong. It is the building block for running these types of model evaluations for classification problems. 

To calculate the model’s accuracy, also known as its score, add up the correct predictions and then divide that number by the total number of predictions.

### Precision

Precision removes the negative predictions from the picture. Precision is the proportion of positive predictions that are actually correct. You can calculate it by taking the true positive count and dividing it by the total number of positives.

When the cost of false positives are high in your particular business situation, precision can be a good metric. Think about a classification model that identifies emails as spam or not. In this case, you do not want your model labeling a legitimate email as spam and preventing your users from seeing that email. 

### Recall

In addition to precision, there is also recall (or sensitivity). In recall, you are looking at the proportion of correct sets that are identified as positive. Recall is calculated by dividing the true positive count by the sum of the true positives and false negatives. By looking at that ratio, you get an idea of how good the algorithm is at detecting, for example, cats.

Formula for precision: tp divided by tp + fn
Calculation for recall

Think about a model that needs to predict whether a patient has a terminal illness or not. In this case, using precision as your evaluation metric does not account for the false negatives in your model. It is extremely important and vital to the success of the model that it not give false negative results. A false negative would be not identifying a patient as having a terminal illness when the patient actually does have a terminal illness. In this situation, recall is a better metric to use.

### AUC-ROC

Area under the curve-receiver operator curve (AUC-ROC) is another evaluation metric. ROC is a probability curve, and AUC represents the degree or measure of separability.


AUC-ROC uses sensitivity (true positive rate) and specificity (false positive rate)

In general, AUC-ROC can show what the curve for true positive compared to false positive looks like at various thresholds. That means that when you calculate the AUC-ROC curve, you plot multiple confusion matrices at different thresholds and compare them to one another to find out the threshold you need for your business use case.

Example: Email spam classification

Take an example of email spam classification. The emails are rank ordered by the classifier’s risk score. In the following graph, high-scoring emails are on the left, and the vast majority of low-scoring emails are on the right. 

To learn more, choose each of the numbered markers.







Regression problem metrics

In case of a regression problem, there are other common metrics you can use to evaluate your model, including mean squared error and R squared. Mean squared error is very commonly used.

## Mean squared error

The general purpose of mean squared error (MSE) is to evaluate regression model performance by measuring prediction accuracy. You determine the prediction from the model and compare the difference between the prediction and the actual outcome.


## Calculation for mean squared error

More specifically, you take the difference between the prediction and actual value, square that difference, sum up all the squared differences for all the observations, and then divide by the total number of observations to get the average.

The smaller the MSE, the better the model's predictive accuracy.

## R squared

R squared is another commonly used metric with linear regression problems. R squared explains the fraction of variance accounted for by the model. It’s like a percentage, reporting a number from 0 to 1. When R squared is close to 1, it usually indicates that a lot of the variance in the data can be explained by the model itself.

MSE focuses on the average squared error of the model's predictions to provide a measure of model performance. R squared provides a measure of the model's goodness of fit to the data. Both are important but provide different perspectives.

## Business metrics

In the previous section, you saw how to evaluate the performance of an ML model. But remember that when initiating a project, business set goals and KPIs are the metrics used to evaluate if the goals are met.

To validate and monitor model performance, establish numerical metrics that directly relate to the KPIs. These KPIs are established in the business goal identification phase. They can include goals such as increasing sales, cutting costs, or decreasing customer churn.

Evaluate whether the performance metrics accurately reflect the business’ tolerance for the error. For instance, false positives might lead to excessive maintenance costs in predictive maintenance use cases. Another example is deciding if acquiring a new customer is more expensive than retaining one. A business should focus on numerical metrics, such as precision and recall, to help differentiate the business requirements and be closer aligned to business value. 

Consider developing custom metrics that tune the model directly for the business objectives. One way is to develop a cost function to evaluate the economic impact of the model. For the cost function, you can specify the cost, or value, of correct predictions and the cost of errors.

By using A/B testing or the canary deployments technique, developers can experiment with two or more variants of a model and help achieve the business goals.



### Model Deployment types
Model deployment is the integration of the model and its resources into a production environment so that it can be used to create predicitions.

Deployment options
- Self-hosted API - Here you deploy and host your ML models on your own infrastructure, either on premises or in the cloudO(using virtual machines or containers) This involves setting up and managing the necessary infrastructure such as web servers, load balancers, and databases to serve your ML models as APIs

- Managed API - here services are cloud based services that provide a fully managed environment for deploying and hosting your ML models as APIs. SageMaker AI is an example. These services abstract away the underlying infrastructure management so you can focus on building and deploying your models. 


Adavantages of Self-hosted APIS
- Greater control over the infrastructure
- potential cost savings depending on the usage
- the ability to customize the deployment environment.
 
However this approach requires more operational overhead and responsibility for managing and maintaining the infrastructure. 

The choice between the two for ML deployment depends on factors such as the specific requirements of your case, the level of control and customization needed, the avaiolable resources and expertise and finally consideration costs. 


### SageMaker AI
It is a fully managed ML service
With it data scientists and developers can quickly and confidently build, train and deploy ML models into a production-ready, hosted environment. 

It provides the following:
Deployment with one click or a single API call
Automatic scaling
Model hosting services
HTTPS endpoints that can host multiple models

You can use it to deploy a model to get predicitions in several ways;

- Real-time - real time inference is ideal for inference workloads where you have real-time, interactive, and low latency requirements. 

- Batch transform - use batch transform when you need to get inferences from large datasets and dont need a persistent endpoint. YOu can also use it when you need to preprocess datasets to remove noise or bias that interferes with training or inference from your dataset.

- Asynchronous - this is a capability in SageMaker AI that queues incoming requests and processes them asynchronously. it is ideal for requests with large payload sizes, long processing times and near real-time latency requirements

- Serverless - ondemand serveless inference is ideal for workloads that have idle periods between traffic spurts and can tolerate cold starts. It is a purpose-built inference option that you can use to deploy and scale ML models without configuring or managing any of the underlying infrastructure. 


# MLOps
MLOps combines people, technology, and processses to deliver collaborative ML solutions  

It refers to the practice of operationalizing and streamlining the end-to-end machine lifecycle from model developmnt and deployment to monitoring and maintenance.

 It helps ensure that models are not just developed but also deployed, monitored, and retrained systematically and repeatedly.

 It is an extension of the DevOps principles and practces to the specific domain of ML systems

 Just like Devops, MLOps relies on a collaborative and streamlined approach to the ML development lifecycle. It is the intersection of people, process, and technology that optimizes end to end activities required to develop, build, and operate machine learning workloads.

 ## Using MLOps
 Apps that expose trained models might have differet hosting requirements and strategies than standard apps.

 Trained models are sensitive to changes in data; therefore, a model-based app that works well when first implemented might not perform as well days,weeks,or months after being implemented.

 To account for these differences, you need different processes and procedures for applications that are based in managing ML

 MLOps accouns for the unique aspects of AI and ML projects in project management, CI/CD, na quality assurance.

 With it, you can improve delivery time, reduce defects, and make data science more productive.

 ## Goals of MLOps

 get ML workloads into production and keep them operating.
 To meet this goal, MLOps adopts many DevOps principles and practices for the development, training, deployment, monitoring, and retraining of ML models. The aim is to use MLops to do the following:
 - increase the pace of the model development lifecycle via automation.
 - improve quality metrics via testing and monitoring
 - promote a culture of collaboration between data scientists, data engineers, SE and IT operations
 - provide transparency, audibility and security of models by using model governance.


 ## Benenfits of MLOps
 - productivity
 - Reliability
 - Repeatability
 - Auditability
 - Data and Model Quality. 


 ## Key principles of MLOps
 The key principles of MLOps include:
 - version control
 - automation
- CI/CD
- Model governance

## ML Lifecycle and MLOps
Most ML workloads involve the management of code, data, and models.

Managing code, data, and models throughout the ML lifecycle requires the following touchpoints:
- processing code in data preparation
- training data and training code in model building
- candidate modesl, test and validation data in model evaluation.
- metadata during model selection
- deployment-ready models and inference code during deployment
- production code, models and data for monitoring

## Implementing MLOps
- Data Preparation
- Model build - the model building pipeline creates new modelsupon initiation, for instance when new data becomes available
- Model evaluation - when the moel building pipeline completes, you can implement quality control measures at the model redistration step. The quality control step can be either manual or automated. If a model meets baseline performance metrics, it can be registered with a model registry. 

- model approval- you can use the registry to approve or reject model versions. The model approval acion can act as an initiation to start the deployment pipleline.

- Model deployment - the deployment pipeline is most similar to traditional CI/CD systems. This pipeline includes steps such as the following:
Source
Build
Deployment to staging environment
Testing
Promotion to production environment

- model in production - as soon as the model is in production, you should get feedback from the live system. For ML solutions, monitor the hosting infrastructure, data quality, and model performance.

## Evaluate Results

To determine whether a foundational model meets business objectives, it is essential to align the model's capabilities with the specific requirements and goals of the organization

Types of Evaluation Models
Human evaluation
It can be time consuming and expensive

2. Benchmark datasets:
curated collections of data designed specifically for evaluating the performance of language models or other AI systems. 

Some popular benchmark datasets for natural language processing tasks include the following:

- The General Language Understanding Evaluation (GLUE) benchmark is a collection of datasets for evaluating language understanding tasks like text classification, question answering, and natural language inference.

- SuperGLUE is an extension of GLUE with more challenging tasks and a focus on compositional language understanding.
- Stanford Question Answering Dataset (SQuAD) is a dataset for evaluating question-answering capabilities.
- Workshop on Machine Translation (WMT) is a series of datasets and tasks for evaluating machine translation systems.

3. Automated metrics


## Deploying the Application
This phase of the gen AI lifecycle ensures that the trained model is successfully integrated into the target environment for practical use. 

## Key considerations
Cost
Regions
Quotas
Security