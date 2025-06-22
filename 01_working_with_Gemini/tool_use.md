


##  Function calling 
   + Allow a model to call one or more functions that you have written or imported.
   + Often described as the model calling functions, the model is not a runtime that can call the function itself.
   + The model requests that the function be called, and it provides the arguments that should be passed to the function.
   + Your system calls the function and returns the response back to the model for further steps
   + https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/function-calling#best-practices

![image](https://github.com/user-attachments/assets/9eda1513-91f6-4837-a908-0babc0941680)

### Reference links 
 + https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/function-calling#tool-config
 + https://googleapis.github.io/python-genai/genai.html#genai.types.ToolConfig
 + https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/function-calling#python-from-function
 + https://googleapis.github.io/python-genai/#function-calling

## Vertex AI uses a subset of the OpenAPI schema to structure inputs and responses for several features of Gemini
+ Function declarations for Gemini function calling.
+ Defining the output schema for controlled generation in which Gemini outputs structured JSON responses instead of plain text.
+ Extending Conversational Agents Playbooks with tools.
+ The rest of your system is then responsible for calling the function and returning the function’s results back to the model so it can generate a response
  
### Reference links
 + https://cloud.google.com/vertex-ai/docs/reference/rest/v1/projects.locations.cachedContents#Schema
 + https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/function-calling
 + https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/control-generated-output
 + https://cloud.google.com/dialogflow/cx/docs/concept/playbook/tool
