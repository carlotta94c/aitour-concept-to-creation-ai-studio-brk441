## Workshop Description

When developing a generative AI application, selecting the right model is an essential first step. However, the true differentiator lies in how you utilize your input. In this workshop, you will discover how to maximize the potential of your model through advanced prompt engineering techniques, integrating your model with custom data sources, and enabling it to perform actionable tasks. Additionally, you will learn how to leverage Azure AI Studio as the ideal platform to start building custom AI solutions.

## Learning Outcomes

1. Make the best out of the powerful models offered by Azure AI Studio [Model Catalog](https://learn.microsoft.com/azure/ai-studio/how-to/model-catalog-overview?WT.mc_id=academic-145965-cacaste) by leveraging Prompt Engineering techniques and best practices. 
2. Discover how to build, test and evaluate custom and multimodal AI solutions safely in [Azure AI Studio](https://azure.microsoft.com/products/ai-studio/?WT.mc_id=academic-145965-cacaste), thanks to built-in data connectors, AI orchestration toolchain and tracing facilities.

## Technology Used

1. [Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/?WT.mc_id=academic-145965-cacaste)
2. [Azure OpenAI Service](https://learn.microsoft.com/azure/ai-services/openai/overview?WT.mc_id=academic-145965-cacaste)
3. [Azure AI Search Service](https://learn.microsoft.com/azure/search/search-what-is-azure-search?WT.mc_id=academic-145965-cacaste)
3. [Prompty](https://prompty.ai/)

## Additional Resources and Continued Learning

| Resources          | Links                             | Description        |
|:-------------------|:----------------------------------|:-------------------|
| OSS curriculum| [Generative AI for Beginners](https://aka.ms/genai-beginners?WT.mc_id=academic-145965-cacaste) | Deep dive into the world of Generative AI with an 18 lessons-curriculum |
| Microsoft Learn Training | [Create custom copilots with Azure AI Studio](https://learn.microsoft.com/training/paths/create-custom-copilots-ai-studio/?WT.mc_id=academic-145965-cacaste) | Learn more about Azure AI Studio |
| Workshop GitHub repo | [Interact with LLMs](https://github.com/microsoft/aitour-interact-with-llms/) | Master prompt engineering skills and learn about function calling with the workshop repo |
| Agent sample GitHub repo | [Contoso Creative Writer](https://github.com/Azure-Samples/contoso-creative-writer) | Explore an enterprise-ready agent sample built with Prompty and Azure AI  |

## Responsible AI 

Microsoft is committed to helping our customers use our AI products responsibly, sharing our learnings, and building trust-based partnerships through tools like Transparency Notes and Impact Assessments. Many of these resources can be found at [https://aka.ms/RAI](https://aka.ms/RAI).
Microsoft’s approach to responsible AI is grounded in our AI principles of fairness, reliability and safety, privacy and security, inclusiveness, transparency, and accountability.

Large-scale natural language, image, and speech models - like the ones used in this sample - can potentially behave in ways that are unfair, unreliable, or offensive, in turn causing harms. Please consult the [Azure OpenAI service Transparency note](https://learn.microsoft.com/legal/cognitive-services/openai/transparency-note?tabs=text) to be informed about risks and limitations.

The recommended approach to mitigating these risks is to include a safety system in your architecture that can detect and prevent harmful behavior. [Azure AI Content Safety](https://learn.microsoft.com/azure/ai-services/content-safety/overview) provides an independent layer of protection, able to detect harmful user-generated and AI-generated content in applications and services. Azure AI Content Safety includes text and image APIs that allow you to detect material that is harmful. We also have an interactive Content Safety Studio that allows you to view, explore and try out sample code for detecting harmful content across different modalities. The following [quickstart documentation](https://learn.microsoft.com/azure/ai-services/content-safety/quickstart-text?tabs=visual-studio%2Clinux&pivots=programming-language-rest) guides you through making requests to the service.

Another aspect to take into account is the overall application performance. With multi-modal and multi-models applications, we consider performance to mean that the system performs as you and your users expect, including not generating harmful outputs. It's important to assess the performance of your overall application using [generation quality and risk and safety metrics](https://learn.microsoft.com/azure/ai-studio/concepts/evaluation-metrics-built-in).

You can evaluate your AI application in your development environment using the [prompt flow SDK](https://microsoft.github.io/promptflow/index.html). Given either a test dataset or a target, your generative AI application generations are quantitatively measured with built-in evaluators or custom evaluators of your choice. To get started with the prompt flow sdk to evaluate your system, you can follow the [quickstart guide](https://learn.microsoft.com/azure/ai-studio/how-to/develop/flow-evaluate-sdk). Once you execute an evaluation run, you can [visualize the results in Azure AI Studio](https://learn.microsoft.com/azure/ai-studio/how-to/evaluate-flow-results). 

## Content Owners

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->

<table>
<tr>
    <td align="center"><a href="https://github.com/carlotta94c">
        <img src="https://github.com/carlotta94c.png" width="100px;" alt="Carlotta Castelluccio
"/><br />
        <sub><b>Carlotta Castelluccio
</b></sub></a><br />
            <a href="https://github.com/carlotta94c" title="talk">📢</a> 
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

