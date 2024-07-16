# Sample Exam Questions - Part 1 - From Oracle Learning 

**Q1. How does the temperature setting in a decoding algorithm influence the probability distribution over the vocabulary?**
- A) Increasing temperature removes the impact of the most likely word.
- B) Decreasing temperature broadens the disribution, making less likely words more probable.
- C) Increasing temperature flattens the distribution, allowing for more varied word choices.
- D) Temperature has no effect on the probability distribution; it only changes the speed of decoding. 

**Q2. In which scenario is soft prompting especially appropriate compared to other training styles?**
- A) When there is significant amount of labeled, task-specific data available.
- B) When the model needs to be adapted to perform well in a different domain it was not originally trained on.
- C) When there is a need to add learnable parameters to a large language model (LLM) without task-specific training.
- D) When the model requires continued pre-training on unlabeld data. 

**Q3. An LLM emits intermediate reasoning steps as part of its responses. Which of the following techniques is being utlized?**
- A) In-context learning
- B) Step-Back Prompting
- C) Least-to-Most Prompting
- D) Chain-of-thought 

**Q4. How does a presence penality function in language model generation when using OCI Generative AI Service?**
- A) It penalizes all tokens equally, regardless of how often they have appeared.
- B) It only penalizes tokens that have never appeared in the text before
- C) It applies a penality only if the token has appeared more than twice
- D) It penalizes a token each time it appears after the first occurance

**Q5. What is the characteristic of T-Few Fine-Tuning for Large Language Models (LLMs)?**
- A) It updates all weights of the model uniformly.
- B) It selectively updates only a fraction of weights to reduce the no. of parameters.
- C) It selectively updates only a fraction of weights to reduce computational load and avoid overfitting.
- D) It increases the training time as compared to Vanilla fine tuning. 

**Q6. You create a fine-tuning dedicated AI cluster to customize a foundational model with your custom training data. How many unit hours are required for fine-tuning if the cluster is active for 10 days?**
- A) 480 Unit hours
- B) 240 Unit Hours
- C) 744 unit hours
- D) 20 unit hours

**Q7. An AI development company is working on an AI assisted chatbot for a customer which happens to be an online retail company. The goal is to create an assistant that can best answer queries regarding the company policiees as well as retain the chat history throughout a session. Considering the capabilities, which type of model would be the best?**
- A) A keyword search-based AI that responds based on specific keywords identified in customer queries.
- B) An LLM enhanced with Retrieval-Augmented Generation (RAG) for dynamic information retrieval and response generation.
- C) An LLM dedicated to generating text responses without external data integration.
- D) A pre-trained LLM model from Cohere or OpenAI. 

**Q8. How does the structure of vector databases differ from traditional relational databases?**
- A) It stores data in a linear or tabular format
- B) It is not optimized for high-dimensional spaces
- C) It uses simple row-based storage
- D) It is based on and similarities in a vector space

**Q9. When does a chain typically interact with memory in a run within the LangChain framework?**
- A) Only after the output has been generated.
- B) Before user input and after chain execution.
- C) After user input but before chain execution, and again after core logic but before output
- D) Continuously throughout the entire chain execution process.

**Q10. What do prompt templates use for templating in language model applications?**
- A) Phython's class and object structures
- B) Phython's str.format syntax
- C) Phython's list comprehension syntax
- D) Phyton's lambda functions

**Q11. Which statement is true about Fine-tuning and Parameter-Efficient Fine-Tuning (PEFT)?**
- A) Both Fine-tuning and PEFT require the model to be trained from scratch on new data, making them equally data and computationally intensive.
- B) Fine-tuning and PEFT do not involve model modification; they differ only in the type of data used for training, with Fine-tuning requiring labeled data and PEFT using unlabeled data.
- C) PEFT requires replacing the entire model architecture with a new one designed specifically for the new task, making it significantly more data-intensive than Fine-tuning.
- D) Fine-tuning requires training the entire model on new data, often leading to substantial computational costs, whereas PEFT involves updating only a small subset of parameters, minimizing computational requirements and data needs.

**Q12. What does a cosine distance of 0 indicate about the relationship between two embeddings?**
- A) They are unrelated
- B) They are completely dissimilar
- C) They are similar in direction
- D) They have the same magnitude

**Q13. Why is it challenging to apply diffusion models to text generation?**
- A) Because text is not categorical
- B) Because diffusion models can only produce images
- C) Because text generation does not require complex models
- D) Because text representation is categorical unlike images

**Q14. When is fine-tuning an appropriate method for customizing a Large Language Model (LLM)?**
- A) When the LLM already understands the topics necessary for text generation
- B) When the LLM requires access to the latest data for generating outputs
- C) When the LLM does not perform well on a task and the data for prompt engineering is too large
- D) When you want to optimize the model without any instructions

**Q15. Which statement is true about string prompt templates and their capability regarding variables?**
- A) They can only support a single variable at a time
- B) They require a minimum of two variables to function properly.
- C) They are unable to use any variables.
- D) They support any number of variables, including the possibility of having none.

**Q16. What does the Loss metric indicate about a model's predictions?**
- A) Loss is a measure that indicates how wrong the model's predictions are.
- B) Loss describes the accuracy of the right predictions rather than the incorrect ones.
- C) Loss measures the total number of predictions made by a model.
- D) Loss indicates how good a prediction is, and it should increase as the model improves.

**Q17. Accuracy in vector databases contributes to the effectiveness of Large Language Models (LLMs) by preserving a specific type of relationship. What is the nature of these relationships, and why are they crucial for language models?**
- A) Semantic relationships; crucial for understanding context and generating precise language
- B) Linear relationships; they simplify the modeling process
- C) Hierarchical relationships; important for structuring database queries
- D) Temporal relationships; necessary for predicting future linguistic trends

**Q18. What does accuracy measure in the context of fine-tuning results for a generative model?**
- A) How many predictions the model made correctly out of all the predictions in an evaluation
- B) The proportion of incorrect predictions made by the model during an evaluation
- C) The depth of the neural network layers used in the model
- D) The number of predictions a model makes, regardless of whether they are correct or incorrect

**Q19. What is the purpose of Retrievers in LangChain?**
- A) To break down complex tasks into smaller steps
- B) To train Large Language Models
- C) To combine multiple components into a single pipeline
- D) To retrieve relevant information from knowledge bases

**Q20. In the context of generating text with a Large Language Model (LLM), what does the process of greedy decoding entail?**
- A) Choosing the word with the highest probability at each step of decoding
- B) Picking a word based on its position in a sentence structure
- C) Selecting a random word from the entire vocabulary at each step
- D) Using a weighted random selection based on a modulated distribution

**Q21. Which LangChain component is responsible for generating the linguistic output in a chatbot system?**
- A) LLMs
- B) Vector Stores
- C) Document Loaders
- D) LangChain Application

**Q22. What is the purpose of Retrieval Augmented Generation (RAG) in text generation?**
- A) To store text in an external database without using it for generation
- B) To retrieve text from an external source and present it without any modifications
- C) To generate text using extra information obtained from an external data source
- D) To generate text based only on the model's internal knowledge without external data

**Q23. In the simplified workflow for managing and querying vector data, what is the role of indexing?**
- A) To convert vectors into a nonindexed format for easier retrieval
- B) To compress vector data for minimized storage usage
- C) To map vectors to a data structure for faster searching, enabling efficient retrieval
- D) To categorize vectors based on their originating data type (text, images, audio)

**Q24. What does the RAG Sequence model do in the context of generating a response?**
- A) For each input query, it retrieves a set of relevant documents and considers them together to generate a cohesive response.
- B) It retrieves relevant documents only for the initial part of the query and ignores the rest.
- C) It retrieves a single relevant document for the entire input query and generates a response based on that alone.
- D) It modifies the input query before retrieving relevant documents to ensure a diverse response.

**Q25. What is LangChain?**
- A) A Python library for building applications with Large Language Models
- B) A JavaScript library for natural language processing
- C) A Java library for text summarization
- D) A Ruby library for text generation  

**Q26. How can the concept of "Groundedness" differ from "Answer Relevance" in the context of Retrieval Augmented Generation (RAG)?**
- A) Groundedness measures relevance to the user query, whereas Answer Relevance evaluates data integrity.
- B) Groundedness pertains to factual correctness, whereas Answer Relevance concerns query relevance.
- C) Groundedness refers to contextual alignment, whereas Answer Relevance deals with syntactic accuracy.
- D) Groundedness focuses on data integrity, whereas Answer Relevance emphasizes lexical diversity.

**Q27. Given the following code block:**
```
history = StreamlitChatMessageHistory(key="chat_messages")
memory = ConversationBufferMemory(chat_memory=history)
```
**Which statement is NOT true about StreamlitChatMessageHistory?**
- A) A given StreamlitChatMessageHistory will NOT be persisted.
- B) A given StreamlitChatMessageHistory will not be shared across user sessions.
- C) StreamlitChatMessageHistory can be used in any type of LLM application.
- D) StreamlitChatMessageHistory will store messages in Streamlit session state at the specified key.

**Q28. How are documents usually evaluated in the simplest form of keyword-based search?**
- A) According to the length of the documents
- B) By the complexity of language used in the documents
- C) Based on the presence and frequency of the user-provided keywords
- D) Based on the number of images and videos contained in the documents
