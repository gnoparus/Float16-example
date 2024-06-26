# Float16 Example Project

This is an example project for [Float16](https://float16.cloud)

We have included a few examples to help you get started with Float16.

## Available models.
| Model Name | Model Size | Description |
|------------|------------|-------------|
| OpenThaiGPT-70b | 70b | A Thai language model|
| OpenThaiGPT-13b | 13b | A Thai language model|
| OpenThaiGPT-7b | 7b | A Thai language model|
| SQLCoder-7b-2 | 7b | A model for converting natural language to SQL queries|
| SeaLLM-7b-v2 | 7b | A South East Asia (SEA) languages model|
| SeaLLM-7b-v2.5 | 7b | A South East Asia (SEA) languages model|

Pricing for each model is available on the [Float16.Cloud](https://float16.cloud) website.

## Latest News
- [2024-04-15] Added brand new SeaLLM-7b-v2.5 model.

- [2024-04-08] Added an example for Bare-metal request. (OpenThaiGPT-70b)
  - [SentimentAnalysis](https://github.com/vultureprime/Float16-example/tree/main/bare_metal/SentimentAnalysis)

- [2024-03-31] Added an example for Bare-metal request. (SQLCoder-7b-2)
  - [TextToSQL](https://github.com/vultureprime/Float16-example/tree/main/bare_metal/TextToSQL)

- [2024-03-05] Added an basic tutorial for LlamaIndex.
  - [Basic](https://github.com/vultureprime/Float16-example/tree/main/llamaindex/Basic)

- [2024-02-04] Added an example for LlamaIndex Streaming. (SeaLLM-7b-v2)
  - [RAGStreaming](https://github.com/vultureprime/Float16-example/tree/main/llamaindex/RAGStreaming)

- [2024-02-02] Added an example for Bare-metal request. (SeaLLM-7b-v2)
  - [Streaming](https://github.com/vultureprime/Float16-example/tree/main/bare_metal/Streaming)

- [2024-01-10] Added an example for Bare-metal request. (SeaLLM-7b-v2)
  - [SentimentAnalysis](https://github.com/vultureprime/Float16-example/tree/main/bare_metal/SentimentAnalysis)

- [2024-01-05] Added an example for LlamaIndex. (SeaLLM-7b-v2)
  - [RAG](https://github.com/vultureprime/Float16-example/tree/main/llamaindex/RAG)
  
- [2023-12-18] Added an example for Langchain. (SeaLLM-7b)
  - [Text Summarization.](https://github.com/vultureprime/Float16-example/tree/main/langchain/summarize)
  - [Machine Translation.](https://github.com/vultureprime/Float16-example/tree/main/langchain/translation)

## How to use this project
You can visit other directories to see how to use Float16 with various models.

## The difference between Float16 Model and OpenAI API
[Float16.Cloud](https://float16.cloud) is a platform providing open-source models and APIs for developers. It is similar to the OpenAI API.

There are, however, some differences between Float16 and the OpenAI API. Open-source models come in various sizes. For instance, the Llama2 model is available in 3 different sizes: 7b, 13b, and 70b. The larger the model, the better its performance. However, a larger model is generally more expensive to run. Hence, we provide a range of model sizes for developers to choose based on their needs.

## Prompt Engineering
To achieve better performance from smaller model sizes, we encourage using techniques such as prompt engineering. We plan to provide more examples of prompt engineering in the future.

Prompt engineering allows one to extract better performance from smaller model sizes. For instance, it's possible to achieve better performance with the 7b model than with the 13b or 70b models.

## FAQ
- **Which prompt engineer techniques are used in this project ?**
We have used the following prompt engineering techniques in this project:
  - Few-shot learning
  - Chain of Thought (CoT)
  - Tree of Thought (ToT)
  - Reason + Act (ReACT)

- **How do I use Float16?**
You can use Float16 by visiting [Float16.Cloud](https://float16.cloud). Register and get your API key. You can then use the API key to access the models.