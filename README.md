# Demo's for AZ-2005

This repo contains a number of demo's that leverage Polyglot Notebooks extension in VSCode, and showcase a variety of techniques you can use to work with Semantic Kerenl. 

You can get the extension [here](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode). This extension brings support for multi-language (C#) notebooks to Visual Studio Code.

Make sure you also have Azure OpenAI resource created, and have deployed a gpt-4o model. Instructions can be found [here](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal).

Read the documentation for Semantic Kernel [here](https://learn.microsoft.com/en-us/semantic-kernel/).

Consider also following resource: https://learn.microsoft.com/en-us/semantic-kernel/get-started/detailed-samples?pivots=programming-language-csharp


## Demo's

- [Notebook 1](./demo_01.ipynb): General introduction to Semantic Kernel with some scenario's to test (plugins, chatbot, ....)
- [Notebook 2](./demo_02.ipynb): Demo of getting recent news and the ability to store data in a file.
- [Notebook 3](./demo_03.ipynb): This demo will showcase RAG patterns using Azure Cognitive Search (index custom data)
- [Notebook 4](./demo_04.ipynb): This demo will showcase RAG patterns using Azure Cognitive Search (index PDF document)
- [Notebook 5](./demo_05.ipynb): Running semantic kernel with local LLM's or SLM's