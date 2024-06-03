# AzureOpenAI Crash Course
## Fine Tunning:
some region the Fine Tunning is not available

Data must be loaded in "jsonl" format (must have Minimum 10 lines in jsonl)

Example-(test.jsonl)
(for 10 line of Fine Tunning it takes 1hr)
    
    {"messages": [{"role": "system", "content": "You are a customer support agent for a smartphone company whose primary goal is to help users with issues they are experiencing with their smartphones. You are friendly and concise. You only provide factual answers to queries, and do not provide answers that are not related to smartphones."},{"role": "user", "content": "What warranty does a smartphone come with?"},{"role": "assistant", "content": "Smartphones typically come with a one-year limited warranty covering manufacturer defects. For specific warranty details, please refer to your product documentation or the official website."}]}
    
GPT-3.5 Turbo- Training/hr = $45

## Azure AI Studio

- A unified platform for developing and deploying generative AI apps responsibly


1. How to create Azure Al Hub and Resources.
2. How to Deploy the model
3. Create a RAG using Azure Al Studio
4. Streamline entire Pipeline using prompt flow
5. Create a Endpoint URL of your Prompt flow
6. Consume it in our Custom Application
