## Responsible AI Practices
Responsible AI refers to practices and principles that ensure AI systems are transparent and trustworthy while mitigating potential risks and negative outcomes.

To operate AI responsibly,companies should proactively ensire the following about their system.
1. It is transparent and accountable
2. It is managed by a leadership team accountable for responsible AI strategies.
3. It is developed by teams with epertise in responsible AI principles and practices
4. It is built following responsible AI guidelines

## Generative AI offers business value
Creativity
Productivity
Connectivity

### Responsible AI Challenges in Traditional AI and Generative AI
Biases in AI systems

## Accuracy of models
Bias is one of the biggest challenges a developerfaces in AI systems

Variance refers to the model'ssensitivity to fluctuations or noise in the training data. 

### Bias-variance trade-off
this is when you optimize your model with the right balance between variance and bias.
This means that you need to optimize your model so that it is not underfitted or overfitted. 

The goal is to achieve a trained model with the lowest bias and lowest variance tradeoff for a given data set. 

To help overcome bias and variance errors,you can use the following:
1. Cross validation
2. Increase data
3. Regularization
4. Simpler models
5. Dimension reduction
6. Stop training early


## Challenges of generative AI
Toxicity- generating anything that is offensive, or inappropriate
Hallucinations-
Intellectual Property
Plagiarism and cheating
Disruption of the nature of work

## Core Dimensions of responsible AI
They include:
1. Fairness
It is crucial as AI systems promote inclusion, prevent discrimination, uphold responsible values and legal norms and built trust with society.
2. Explainability
refersto the ability of an AI model to clearly explain or provide justification for its internal mechanisms and decisions so that it is understandable to humans
3. Privacy and security
refers to data that is protected from theft and exposure.
this means that at a privacy level, individuals control when and if their data can be used. At the security level, it verifies that no unauthorized systems or unauthorized users will have access to the individuals data. 
4. Security
5. Robustness
6. Governance
7. Transparency
It communicates info about an AI system so stakeholders can make infomed choices about their use of the system.
8. Safety
9. Controllability

Business benefits of responsible AI
1. Increased trust and reputation
customers are more likely to interact with ai applications if they believe the system is safe and fair
2. Regulatory compliance
As AI regulations emerge, companies with robust ethical AI frameworks are better positioned to comply with guidelines on data privacy, fairness, accountability and transparency.
3. Mitigating risks- responsible AI practices help mitigate risks such as bias,privacy violations,security breaches, and unintended negative impacts on society. This reduces legal liabilities and financial costs.
4. Competitive advantage
companies that prioritize responsible AI can differentiate themselves from competitiors and gain a competitive edge, especially as consumer awareness of AI ethics grows. 
5. Impoved decision-making
ai built with fairness, accountability, and transparency in mind are more reliable and less likely to produce biased or flawed outputs which leads to better data-driven decisions.
6. Improved products and business
responsible AI encourages a diverse and inclusive approach to AI development. Because it draws on varied perspectives and experiences, it can drive more creative and innovative solutions 


### Amazon services and tools for responsible AI
Amazon sagemaker AI and Amazon Bedrock.
These tools cover topics such as foundation model evaluation,safeguards for generative AI, bias detection, model prediction explanations,monitoring and human reviews, and governance improvement

#### Amazon Sagemaker AI
fully managed ML service. 
With it developers can quickly and confidently build, train, and deploy ML models into a production-ready hosted environment. 
It also provides managed ML algorithms to run efficiently against extremely large data in a distributed environment. 
With built  in support for bring your own algorithms and frameworks, Sagemaker  AI offers flexible distributed training options that adjust to your specific workflows. 

#### Amazon bedrock
fully managed service that makes available high performing FMs from leading AI startups and  Amazon for your use through a unified API
It also offers a broad set of capabilites tobuild generative AI applications with security, privacy, and responsible AI.

With the serveless experience of Amazon Bedrock, you can privately customize FMs with your own data and securely integrate and deploy them into youe apps by using AWS tools without having to manage any infrastructure. 


### Responsible Considerations to select a Model

#### Choosing a model based on performance
Model performance varies across a number offactors, including the following:
Level of customization- the ability to change a model's output with new data ranging from prompt-based approaches to full model retraining.
Model size- the amount of info the model has learned as defined by parameter count
Inference options- from self-managed deployment to API calls
Licensing agreements- some agreements can restrict or prohibit commercial use
Context windows - the amount of info that can fit into a single prompt
Latency - the amount of time it takes for a model to generate an output

#### Consider a model based on performance with test dataset
A common mistake when choosing a model is to assumee that the model in and of itself is either good or bad.

Performance is a function of the model and a test dataset, not just the model. So, when you are assessing a model you need to determine how well a model performs on a particular dataset. 

#### Choosing a model based on sustainability concerns
Sustainability in the context of responsible AI refers to the ability of AI systems to be developed and deployed in a manner that is socially, environmentally, and economically sustainable over the long term. 

#### Responsible agency considerations for selecting a model

This refers to an AI system's capacity to make good judgements and act in a socially responsible manner. The following are key aspects of moral agency for AI

##### Value Alignment
- being able to understan, evaluate, and make decisions based on moral principles rather than pure utility maximization. This requres value alignment between the AI system's goals and values and the responsible human values. 

##### Responsible reasoning skills
this is being able to logically think through moral dilmmas and weigh various responsible considerations when making decisions. The AI needs logic and reasoning capabilities to apply responsible principles to novel situations. 

##### Appropriate level of autonomy
The AI system should have the appropriate level of autonomy, with clear boundaries and mechanisms for human oversight and intervention, particularly in high stakes or sensitive domains. 

##### Transparency and accountability
The AI system should be transparent about its decision-making process. It should allow external oversight and accountability to ensure its actions are responsibly justified. 


### Environmental considerations when selecting a model
The following are key environmental challenges and solutions to consider when choosing a model

1. Energy consumption- training large AI models can consume significant amounts of energy and contributes to greenhouse gas emissions and environmental impact. The solution is to optimize energy efficiency in AI systems, use renewable energy resources where possible

2. Resourcesutiliation- ai systems require substantial computational resources, including specialized hardware. The manufacture and disposal of these resourcces can have environmetal impaccts

The solution is to aom to maximize resource efficiency, promote hardware reusability and recyclability and minimize electronic waste

3. Environmental Impact assessment
before deployin AI systems it is important to assess both the direct and indirect effects on the environment, Environmental impact asessments should be conducted and mitigation strategies should be implemented if necessary. 

### Economic considerations for selecting a model

Economic considerations in responsible AI include the potential benefits and costs of AI technologies and the impact on jobs and the economy. 



### Responsible Preparation for Datasets
An essential requirement of responsibleAI is to prepare your data sets responsibly. This means thet you need to have balanced datasets to train your models.


Remember that you can use SageMaker AI Clarify and SageMaker Data Wrangler to help balance your datasets. 

#### Balancing datasets
They are important for creating responsible AI models that do not unfairly iscriminate or exhibit unwanted biases.
 

Balanced datasets should represent all groups of people or data topics. This means that the dataset should contain an adequate number of examples or instances of each group to ensure that the moel is not biased towards any particular group or factor

The concept of balanced datasets is particularly important in applications like hiring

To achieve balanced datasets, the data collected needs to be inclusive and diverse, and the data aslo needs to be curated to optimize it for training. 


### Inclusive and diverse data collection

Inclusiveness and diversity in data collection ensure that data collection processes are fair and unbiased.

Data collection should accuratelyreflect the diverse perspectives and esperiences required for the use case of the AI system. 

This includes a diverse range of sources, viewpoints, and demographics. By doing this the AI aystem can work to ensure decisions are unbiased in their performance. 

Inclusiveness and diversity in data collection is a primary concern for data that focuses on people.

This is because alienating groups of people in the training data can lead to societal harms and legal repercussions. However, inclusiveness and diversity in data collection hould be a primary focus regardless of the topic. For instance, collection of data for people, scientific research,geography, weather, products, and other topics should be collected with a focus on the diverse range for each topic. 

### Data curation
This is the process of labelling, organizing, and preprocessing the data so that it can perform accurately on the model.

The curation can help to ensure that the data is representative of the problem at hand and free of biases or other issues that can impact the accuracy of the AI model.

Curation helps ensure that the AI models are trained and evaluated on high-quality, reliable data that is relevantto the task they're intended to perform.The main steps of curating data include data preprocessing, data augmentation, and regular auditing.

- Data Preprocessing- this is to ensure the data is accurate, complete and unbiased. Techniques such as data cleaning, normalization, and feature selection can help to eliminate biases in the data set. 

- Data augmentation - use data augmentation techniques to generate new instances of underrepresented groups. This can help to balance the dataset and prevent biases towards more represented groups

- Regular auditing- regularly audit the dataset to ensure it remains baanced and fair. Check for biases and take corrective actions if necessary

### Baklance your data for the intended use case
The use case for the AI system will etermine how the data needs to be balanced. For instance, if you are creating an AI system about cancer in children, you would collectt the data and curate it to focus on children and not include datasets on adults.


## Transparent and Explainable Models

### Models need to be transparent and explainable

AI systems ican be found in many fields such as healthcare and security. There must be trust and accountability in these AI systems. Therefore, including transparent and explainable models is fundamental for developing these AI systems

Transparency answers the question HOW(a model makes decisions) this helps to provide accountability and builds trust in the AI system. It also makes auditing a system much easier., and explaianbility answers the question WHY(the model made the decision that it made)it gives insights into the limitations of a model. This helps developers with debugging and troubleshooting the model. It also allows users to make informed decisions on how to use the model. 

 Both aspects are needed to build responsible AI systems. 


 ### Transparent and explainable models compared to black box models

 black box modelsare models that lack transparency and explainability.

 theyuse complex algorithms and numerous layers of neural networks to makepredictions, but they do not provide insight into their internal workings.

 Transparent and explainable models have several advantages over bb models
 1. Increased trust
 2. Easier to ddebug and optimize for improvements
 3. better understanding of the data and the model's decision-making process

 Here are some potential solutions for increasing transparency and explainability in AI systems to help ensure responsible AI development

 - Explainability frameworks
 - transparent documentation
 - monitoring and auditing
 - human oversight and involvement
 - counterfactual explanations
 - user inerface explanations

 ### Risk of transparent and explainable models
 Some of the risks include:
 increasing the complexity of the development and maintenance of the model can increase the costs

creating vulnerabilities of the model, data, and algorithms can be exploited by bad actors

presenting unrealistic expectations that the model is perfectly transparent and explainable. In some situations, this may not be achieved or even intended

providing too much info c crereate privacy and security concerns.

### AWS tools for transparency
to help with transparency Amazon offers AWS AI service cards and Amazon SageMaker Model cards. the difference between them is that with AI service cards, amazon provides transparent documentation on Amazon services that help oyu build your AI services. 

with sagemaker model cards, you can catalog and provide documentation on models that you create or develop yourself.


### AWS tools for explainability
#### SageMaker AI clarify
 It is integrated with SageMaker AI experiments to provide scores detailing which features contributed the most to your model prediction on a particular input for tabular, NLP, and computer vision models. 

 For tabular datasets, Sagemaker AI clarify can also output an aggregated feature importance chart which provides insights into the overall prediction process of the model.

 These details can help determine if a particular model  input has more influence than expected on overall model behavior

 #### SageMaker Autopilot
 uses tools provided by sagemaker AI clarify to help provide insights into how ML models make predictions.
 These tools can help ML engineers, product managers, and other internal stakeholders understand model characteristics.

 To trust and interpret decisions made on model predictions, both consumers and regulators rely on transparency in ML 

 The SageMaker Autopilot explanatory functionality determines the contribution of individual features or inputs to the model's output and provides insights into the relevance of different features. You can use it to understand why a model made a prediction after training or use it to provide per-instance explanation during inference. 

# Model Trade-offs
## Interpretability trade-offs
it is a feature of model transparency. Interpretability is the degree to which a human can understand the cause ofa decision. 

### Interpretability
is the access into a system so that a human can interpret the model's output based on the weights and features. E.g if a business wants high model transparency and wants to understand exactly why and how the model is generating predictions, they need to observe the inner mechanics of the AI/ML method

### Explainability
It is how to take an ML model and explain the behavior in human terms.

With complex models e.g black boxes you cannot fully understand how and why the inner mechanics impact the prediction.

However, through model agnostic methods e.g partial dependence plots you can discover meaning between input data attributions and model outputs.

Interpretability example
An economist might want to build a multi-variate regression model to predict an inflation rate. They can view the estimated parameters of the model’s variables to measure the expected output given different data examples. In this case, full transparency is given, and the economist can answer the exact why and how of the model’s behavior.

### Safety and transparency trade-offs
#### Model Safety
this is the ability of an AI system to avoid causing harm in its interaction with the world. This includes avoiding socil harm, such as bias in decision-making algorithms, and avoiding privacy and security vulnerability exposures.

Model safety is important for ensuring that AI systems aare used in ways that benefit society and do not cause harm to individuals or groups

#### Model safety and model transparency trade-offs
with model safety focusing on protecting info, and model transparency focusing on exposing info, you can understand that there is a delicate balance needed between them.

- Accuracy
Complex models like large neural networks tend to be more accurate but less interpretable than simpler linear models, which are more transparent.

- Privacy
Privacy-preserving techniques like differential privacy can improve safety but make models harder to inspect. This can make models less transparent.

- Safety
Constraining or filtering model outputs for safety can reduce transparency into the original model reasoning. 

- Security
Highly secured air-gapped train models (models that are trained on networks that are private and do not have access to external data) might be less open to external auditing. 


### Model Controllability

#### Model control
a controllable model is one where you can influence the model's predictions and behavior by changing aspects of the training data.

Higher controllability provides more transparency into the model and allows correcting undesired biases and outputs.

It is measured by how much control you have over the model by changing the input data.

Models that are more controllable are easier to steer towards desired behaviors. This is important for fairness because you want to be able to understand and control bias in the model. Controllability of a model is also important for transparency and debugging in a model.

Controllability depends on the model architectre. Linear models tend to be more  controllabble than complex neural networks. 

You can test for controllability by evaluating if the manipulating the data, such as adding or removing examples, causes expected changes in the models outputs and predictions.

Controllability can be improved through data augmentation techniques and by adding constraints to the model training process. 

# Principles of Human-Centered Design for Explainable AI

HCD is an approach to creating products and services that are intituitive, easy to use, and meet the needs of people who will be using them.

When applied to explainable AI, HCD helps ensure that the explanations and interfaces provided are clear, understandable, and useful to the people they are intended to serve. This includes being accurate and fair.

The following are key principles of HCD for explainable AI:

- Design for amplified decision-making
- Design for unbiased decision-making
- Design for human and AI learning

### Design for amplified decision-making
supports decision-makers in high stakes situations. this principle seeks to maximize the benefits of using technology while minimizing potential risks and errors, especially risks and errors that can occur when humans make decisions under stress or in high-pressure environments.

This can lead to better outcomes for individuals, organizations, and society as whole. 

#### Key aspects for designing for amplified decision making
- clarity
- simplicity
- usability
- reflexivity
- Accountability


### Design for unbiased-decision making
this one aims to ensure that the design of decision-making processes, systems, and tools is free from biases that can influence the outcomes.

This can have significant impacts on decision-making outcomes and help promote fairness and efficient use of resources. 

Design for unbiased decision-making involves the following steps
- identify and assess potential biases
- design decision making processes and tools that are transparent and fair.

- Train decision-makers to recognize and mitigate biases


Key aspects for designing for unbiased decision making:
- transparency
- fairness
- training

### Design for human and AI learning
it is a process that aims to create learning environments and tools that are beneficial and effective for both humans and AI.

It encompasses a range of strategies and approaches that take into account the unique strengths and limitations of each learner and the goals and purposes of the learning experience.

#### Key aspects of designing for human and AI Learning
Cognitive apprenticeship- refers to the process in which humans learn new skills and knowledge by observing and interacting with more skilled and knowlegable individuals. 

In AI learning, this inolves creating learning environmetns where AI systems learn from human instructors and experts and gain experience and expertise through simulated or real-world scenarios

personaization- refers to the process of tailor-making learning experiences and tools to meet the specifiv needs and preferences of individual learners

user-centered design - involves designing learning environments and tools that are intuitive and accessible to a wide range of learners, including those  with disabilities or language barriers.

By prioritizing user experience and usability, designers can ensure that learning environments are effective and engaging for all users. 

#### Reinforcement learning from human feedback

RLHF is an ML technique that uses human feedback to optimize ML models to self-learn more efficiently.

RL techniques train software to make decisions that maximize rewards, which makes their outcome more accurate.

RLHF incorporates human feedback in the reward function, so the ML model can perform tasks aligned with human goals, wants, and needs. RLHF is used in both traditional AI and generative AI apps

Benefits of RLHF
some of the benefits of RLHF include the following:
Enhances AI performance
Supplies complex training parameters
Increases user satisfication

#### Amazon SageMaker Ground Truth

It offers the most comprehensive set of human-in-the-loop capabilities for incorporating human feedback across the ML lifecycle toimprove model accuracy and relevancy.

SageMaker Ground Truth includes a data annotator for RLHF capabilities.

You can give direct feedback and guidance on output that a model has generated by raking, classifying,or doing both for its responses for RL outcomes.

The data, referred to as comparison and ranking data, is effectively a reward model or reward function that is then used to train the model. 

You can use comparison and ranking data to customize an existing model for your use case or fine tune a model that you build from scratch.