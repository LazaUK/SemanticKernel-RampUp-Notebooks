# Semantic Kernel: Jupyter Notebooks for Ramp-Up Learning Process

Semantic Kernel (SK) is an open-source SDK that enables orchestration of your AI workflows. SK facilitates the development of AI agentic solutions capable of reasoning, planning and integrating with various external data sources and execution services.

This repo contains Jupyter notebooks to assist you with the ramp-up learning process. These notebooks cover topics and Python code based on the official Semantic Kernel documentation site [here](https://learn.microsoft.com/en-us/semantic-kernel/overview/).

> [!WARNING]
> To run these notebooks successfully, you will need an Azure OpenAI Service deployment. Please ensure you have the following environment variables set up in your system:
>
> | Environment Variable      | Description                                                    | Example Value                     |
> | :------------------------ | :------------------------------------------------------------- | :-------------------------------- |
> | `AZURE_OPENAI_API_DEPLOY` | The deployment name of your Azure OpenAI model.                | `gpt-41-mini`                    |
> | `AZURE_OPENAI_API_BASE`   | The endpoint URL of your Azure OpenAI service.                 | `https://YOUR_AOAI_SERVICE_NAME.openai.azure.com/` |
> | `AZURE_OPENAI_API_VERSION`| The API version to use.                                        | `2025-03-01-preview`              |
>
> You can set these environment variables in your operating system or within a `.env` file in the root of your project and load them using a library like `python-dotenv`.


## 📑 Table of Contents
- [Notebook 1: Quick Start](#notebook-1-quick-start)
- [Notebook 2: Essentials - AI Services](#notebook-2-essentials---ai-services)

---
## Notebook 1: Quick Start
This notebook provides a fundamental intro to Semantic Kernel, guiding you through the initial setup.

You'll learn how to configure your environment, add an Azure OpenAI-based AI model, enable logging and integrate your first custom plugin. The notebook also demonstrates how to perform basic AI function calls and observe the interaction between the kernel and your plugin.

## Notebook 2: Essentials - AI Services
This notebook intrduces management of AI services within Semantic Kernel.

You'll learn how to add AI services to the kernel, retrieve them using different methods (by type or service ID) and directly utilise chat completion services for both non-streaming and streaming responses. This notebook is essential for understanding how to connect SK to your chosen AI models.
