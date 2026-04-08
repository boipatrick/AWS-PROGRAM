## ML FUNDAMENTALS

Building a ML Model involves data collection and preparation, selecting an appropriate algorithm, training the model on the prepared data, and evaluating its performance through testing and iteration. 


Training data-----ML algorithm----Model

The process starts with collecting anf processing training data. The ML model is only as good as the data it was trained on. 

Although data preparation and processing are someties a routine process, it is the most critical stage in making the whole model work as intended or ruining its performance.

Labelled data- in an image classification task, labeled data would consist of images along with their corresponding class labels eg cat dog rat

Unlabeled data- dataset where the instances or examples do not have any associated labels or target variables. E.g a collection of images without any labels or annotations. 

Main types of data used in training are structured and unstructured data. 

### Structured Data
refers to data that is organized and formatted in a predefined manner, typically in the form of tables or databases with rows and columns. This type of data is suitable for ML algorithms that require well-defined features and labels. Types of structured data include tabular data stored in spreadsheets,dbs or csv files

Time series data:consists of sequences of values measured at successive points in time such as stock prices, sensor readings or weather data

### Unstructured data
data that lacks a predefined structure or format such as text,images, audio and video, It requires more advanced ML techniques to extract meaningful patterns and insights. 

Text data: documents, articles, social media posts and other textual data

Image data: this includes digital images, photos and videoframes.


Going back to the ML process -- the compiled training data is fed into machine learning algorithms. The ML learning process is traditionallydivided into three broad categories: supervised learning, unsupervised learning and reinforcement learning. 

In supervised learning- the algorithms are trained on a labeled data. The goal is to learn a mapping function that can predict the output for new, unseen input data.

Unsupervised Learning- refers to algorithms that learn from unlabelled data. The goal is to discover inherent patterns, structures or relationships within the input data.

In reinforcement learning, the machine is given only a performance score as guidance and semi-supervised learning, where only a portion of training data is labelled. Feeback is provided in the form of rewards or penalties for its actions, and the machine learns from the feedback to improve its decision making over time. 

## Inferencing
Training Data-----ML algorithm------Model

After the moel has been trained, it is time to begin the process of using the info that a model has learned to make predictions or decisions. This is called inferencing

There are two main types of inferencing in ML: batch inferencing and real-time inferencing. 

Batch inferencing- computer takes in a large amount of data such as images and text and analyzes it all at once to provide a set of results. It is used for tasks like data analysis

Real Time Inferencing- when a computer has to make decisions quickly in response to new info coming in. Itis important where decision-making is critical, such as in chatbots or self-driving cars. The computer has to process the incoming data and make a decision  almost instantaneously, w/out taking the time to analyze a large dataset.  


## Deep Learning Fundamentals
The field involves the use of artificial neural networks, which are computational models that are designed to mimic the way the human brain processes info. 

## Neural Networks
They are at the core of deep learning. Neural networks have lots of tiny units called nodes that are connected together just like the neurons in our brains. 

These nodes are organized in layers. The layers include an input layer, one or more hidden layers and an output layer. 

When we show a neural network many examples, like data about customers who bouht certain products or used certain devices, it figures out how to identify patterns by adjusting the connections between its nodes. It's like the nodes are talking to each other and slowly figuring out that patterns that separate different types of customers.

When a neural network learns to recognize these patterns from the examples, it can then look at data for completely new customers that it has never seen before and still make predictions about what they might buy or how they might behave. 

### AI Branches where deep learnin is used to enhance results
1. Computer Vision- a field that enables computers to interpret and understand digital images and videos. Deep learning has revolutionized computer vision by providing powerful techniques such as image classification, object detection, and image segmentation.
2. Natural Language Processing- this is a branch that deals with the interaction betweeen computers and human languages. Deep learning has made significant strides in NLP, making it possible tasks such as text classification, sentiment analysis, machine translation and language generation.




## Generative AI Fundamentals

Foundation Models

Generative AI is powered by models that are pretrained on internet-scale data, and these models are called foundational models.

With FMs instead of gathering labelled data for eachmodel and training multiple models as in traditional ML, you can adapt a single FM to perform multiplr tasks. 

These tasks include text generation, text summarization, information extraction, image generation, chatbot integrations and question answering. FMs can also serve as a starting point for developing more specilaized models.

The FM Lifecycle
1. Data Selection
unlabelled data is commonly used
2. Pre-training
trained via self-supervised learning
3. Optimization
techniques such as prompt engineering, retrieval-augmented generation(RAG), and fine-tuning on task specific data. 
4. Evaluation-An FM's performance can be measured using appropriate metrics and benchmarks. Evaluation of model performance and its ability to meet business needs is important. 
5. Deployment when the FM meets the desired performance criteria, it can be deployed in the target production environment. Deployment can mean integrating the model into apps, APIs or other software systems. 
6. Feedback and continous improvement
after deployment the models performance is continously monitored and feedback is collected from users, domain experts or other stakeholders. this feedback along with model monitoring data is used to identify areas for improvement, detect potential biases or drift, and inform future iterations of the model.


A few types of FMs that are essential to understanding generative AI's capabilities. 

### Large Language Models.

## Amazon Models
A mazon comprehend- uses ML and NLP tohelp you uncover the insights and relationships in your unstructured data. 

## Advantages and benefits of AWS AI Solutions
Aws provides a secure and compliant infrastructure for building AI applications.
Aws uses robust security features, industry-specific compliance attributes, and a shared responsibility model.

It also provides services and tools that can support the responsible and safe development and deployment of traditional and generative AI solutions.


