# Essentials of Prompt Engineering

## Understanding Prompts
Using effective prompt strategies can offer you the following benefits:
- Enhance the model's capabilities and bolster its safety measures

- Equip the model with domain-specific knowledge and external tools without modifying its parameters or undergoing fine-tuning

- Interact with language models to fully comprehend their potential

- Obtain higher-quality outputs by providing higher quality inputs

### Elements of a prompt

A prompt's form depends on the task that you are giving to a model.

Some of the prompts we'll look at will contain these elements

- Instructions : This is a task for a large language model to do
- Context: this is external information toguide the model

- Input data : This is the input for which you want a response

- Output indicator: this is the output type or format

## Negative Prompting

Sometimes it's easier to guide a model toward a desired output by including what you don't want included in the output.

It is used to guide the model away from producing certain types of content or exhibiting specific behaviors

It can be used to prevent the model from producing hate speech, explicit content or biased language. By specifying what the model should avoid, negative prompting helps steer the output towards more appropriate content. 


## Modifying Prompts
The outputs of FM are greatly influenced by the prompts provided. 

## Inference parameters
When interacting with FMs, you can often configure inference parameters to limit or influence the model response. 

Inference parameters fit into a range of categories, with the most common being randomness and diversity and length. 


## Randomness and diversity

The most common category of inference parameter.

Randomness and diversity parameters influence the variation in generated responses by limiting the outputs to more likely outcomes or by changing the shape of the probability  distribution of outputs. 
Three of the more common parameters are temperature, top k and top p

- temperature controls the randomness or creativity of the model's output. A higher temperature makes the output more diverse and unpredictable and a lower temperature makes it more focused and predictable. 

- top P is a setting that controls the diversity of the text by limiting the number of words that the model can choose from based on their probabilities.

- top K limits the number of words to the top K most probable words, regardless of their percent probabilities. For instance, if the top K is set to 50, the model will only consider the 50 mostlikely words for the next word in the sequence, even if those 50 words only make up a small portion of the total probability distribution. 


- Adjusting these inference parameters can significantly impact the model's output, so you can fine-tune the level of creativity, diversity and coherence to suit your specific needs.


## length

The length inference parameter category refers to the settings that control the maxi length of the generated output and specify the stop sequences that signal the end of the generation proces

### Best practices for prompting
Tips for designing prompts:
- Be clear and concise
- Include context if needed
- Use directives for the appropriate response type
- consider the output in the prompt
- start prompts with an interrogation
- Provide an example response
- Break up complex tasks
- Experiment and be creative
- Use prompt templates


## Prompt Engineering Techniques

### Zero-shot prompting
technique where a user presents a task to a generative model without providing any examples or explicit training for that specific task. 

The user relies on the model's general knowledge and capabilities to understand and carry out the task without any prior exposure, or shots, of similar tasks.

To optimize zero-shot prompting, consider the following tips:
- the larger and more capable the FM, the higher the likelihood of obtaining effective results from zero-shot prompts
- instruction tuning, a process if fine-tuning models to better align with human preferences,can enhance zero-shot leraning capabilities. 

### Few-shot Prompting
technique that involves providing a large language model with contextual examples to guide its understanding and expected output for a specific task. 

In this approach, you supplement the prompt with sample inputs and their corresponding desired outputs, effectively giving the model a few shots or demonstrations to condition it for the requested task . 

When employing a few-shot prompting technique, consider the following tips:
- Make sure toselect examples that are representative of the task that you want the model to perform and cover a diverse range of inputs and outputs. 
- Experiment with the no. of examples


### Chain-of-thought prompting
technique that divides intricate reasoning tasks into smaller, intermediay steps. Can be emploed using either zero-shot or few-shot prompting techniques

CoT prompts are tailored to specifc problem types. To initiate the chain-of-thought reasoning process in a ML model, you can use the phrase "Think step by step"
- It is recommended to use CoT prompting when the tsk requires multiplt steps or a series of logical reasoning

## Prompt Misuses and Risks
### Poisoning
refers to the intentional intro of a malicious or biased data into the training data set of a model. This can lead to the model producing biased, offensive or harmful outputs either intentionally or uninentionally. 

### Hijacking and prompt injection
They refer to the technique of influencing the outputs of a generative models by embedding specific instructions within the prompts themselves. 

The goal is to hijack the model's behavior and make it produce outputs that align with the attackers's intentions, such as generating misinformation or running malicious code. 


### Exposure and Prompt leaking
- Exposure
refers to the risk of exposing sensitive or confidential info to a generative model during training or inference. An FM can then inadvertently reveal this sensitive data from their training corpus leading to potential data leaks or privacy violations 

### Prompt leaking
refers to the unintentional disclosure or leakage of the prompts or inputs(regardless of whether these are protected data or not) used within a model.

Prompt leaking does not necessarily expose protected data. But it can expose other data used by the model, which can reveal information of how the model works and this can be used against it. 


### Jailbreaking
refers to the practice of modifying or circumventing the contraints and safety measures implemented in a generative model or AI assistant to gain unauthorized access or functionality. 

 Jailbreaking  attempts involve crafting carefully constructed prompts or input sequences that aim to bypass orexploit vulnerabilities in the AI system's filtering mechanisms or constraints. The goal is to break out of the intended model limitations. 