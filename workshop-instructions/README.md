# Workshop instructions

This folder contains the step-by-step instructions for this workshop.

It includes 5 sections:

- [**Set Up**](./00_set_up.md): set up your workspace in Azure AI Studio 
- [**Part 1 - Get Started with Azure AI Studio**](./01_get_started_with_Azure_AI_Studio.md): learn how to navigate the platform and explore the main features.
- [**Part 2 - Prompt Engineering Techniques in the Azure AI Studio Playground**](./02_prompt_eng_techniques_playground.md): test some basic and advanced prompt engineering techniques in the *Playground* of Azure AI Studio.
- [**Part 3 - Add your own data with Prompty**](./03_add_your_own_data.md): discover how to build your first LLM-based solution and connect it to your business data, leveraging *Retrieval Augmented Generation*(RAG).
- [**Part 4 - Evaluate your prototype**](./04_evaluate_your_prototype.md): once your first app is ready and connected to your data, go through this section to evaluate the performance of your solution.

## Folder structure

This folder contains the following files and folders:

- `README.md`: this file.
- `00_set_up.md`: step-by-step instructions to set up the development environment for the workshop using either the Azure Portal or the Azure CLI.
- `set_up.sh`: bash script to automatize Azure resources provisioning
- `.env.sample`: sample of the environment config file used to execute the app logic for part 3 
- `01-get-started.md`: step-by-step instructions to run part 1.
- `02-prompt-engineering.md`: step-by-step instructions to run part 2.
- `03-add-your-own-data.md`: step-by-step instructions to run part 3.
- `04-evaluate-your-prototype.md`: step-by-step instructions to run part 4.
- `media`: folder containing images used in the markdown files.
- `data`: folder containing the sample datasets used in part 3 and 4.
- `web_designer_app`: folder containing the source code files for part 3 and 4. 

## Scenario

All the demos are based on the following scenario.
You are a developer at **Contoso Outdoor Company**, a leading *e-commerce company that sells outdoor gear and equipment*. Your team is working on a new website design and you have been tasked with generating text content, and code snippets for the website. You have heard about the power of generative AI models and want to explore how you can leverage them to generate content for the website.
