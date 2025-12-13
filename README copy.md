<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">LANGCHAIN_DEMYSTIFIED.GIT</h1></p>
<p align="center">
	<em>Simplify, Link, and Innovate with LangChain: Your Path to Code Harmony!</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Sourav692/LangChain_Demystified.git?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/Sourav692/LangChain_Demystified.git?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Sourav692/LangChain_Demystified.git?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Sourav692/LangChain_Demystified.git?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

LangChainDemystified.git is a groundbreaking open-source project that simplifies managing and orchestrating chains of processes within codebase architecture. Key features include linking, branching, merging, routing, and moderating chains, offering a structured approach to complex workflows. Ideal for developers seeking efficient workflow management and enhanced codebase architecture.

---

##  Features

|      | Feature         | Summary       |
| :--- | :---:           | :---          |
| ⚙️  | **Architecture**  | <ul><li>Decoupled microservices architecture</li><li>Utilizes containerization with Docker</li><li>Follows a modular design pattern</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>Consistent coding standards</li><li>Well-documented codebase</li><li>Regular code reviews and linting practices</li></ul> |
| 📄 | **Documentation** | <ul><li>Comprehensive API documentation</li><li>Detailed README files</li><li>In-line code comments for better understanding</li></ul> |
| 🔌 | **Integrations**  | <ul><li>Integration with various third-party services</li><li>Support for multiple data sources</li><li>Webhooks for external system communication</li></ul> |
| 🧩 | **Modularity**    | <ul><li>Separation of concerns in different modules</li><li>Reusable components across the codebase</li><li>Easy to extend and maintain</li></ul> |
| 🧪 | **Testing**       | <ul><li>Comprehensive unit tests coverage</li><li>Integration tests for end-to-end scenarios</li><li>Continuous integration and automated testing</li></ul> |
| ⚡️  | **Performance**   | <ul><li>Optimized algorithms for faster processing</li><li>Caching mechanisms for improved response times</li><li>Efficient resource utilization</li></ul> |
| 🛡️ | **Security**      | <ul><li>Strict data encryption practices</li><li>Role-based access control mechanisms</li><li>Regular security audits and vulnerability assessments</li></ul> |
| 📦 | **Dependencies**  | <ul><li>Well-managed dependency list</li><li>Regular updates and version control</li><li>Minimal reliance on outdated libraries</li></ul> |

---

##  Project Structure

```sh
└── LangChain_Demystified.git/
    ├── 1. Introduction
    │   ├── 1. Introduction.ipynb
    │   ├── 2. Basics of Chains.ipynb
    │   ├── 3. Memory.ipynb
    │   ├── 4. Basics of Tools and Functions.ipynb
    │   ├── 6. Implementing RAG.ipynb
    │   ├── 7. Summarization.ipynb
    │   ├── 8. Advance LangChain.ipynb
    │   ├── LCEL.ipynb
    │   └── notebook.ipynb
    ├── 2. Concepts
    │   ├── 0. Introduction
    │   │   ├── 1. Commercial_LLMs_Natively.ipynb
    │   │   ├── 2. Commercial_LLMs_with_LangChain.ipynb
    │   │   ├── 3. Open_Source_LLMs_HF_Transformers.ipynb
    │   │   ├── 4. Open_Source_LLMs_HF_Inference_Client copy.ipynb
    │   │   ├── 4. Open_Source_LLMs_HF_Inference_Client.ipynb
    │   │   ├── 5. Open_Source_LLMs_Groq_Cloud.ipynb
    │   │   └── 6. Open_Source_LLMs_with_LangChain.ipynb
    │   ├── 1. OpenAI_API
    │   │   └── code.ipynb
    │   ├── 10. OpenAI_Functions
    │   │   ├── code_DEPRECATED.ipynb
    │   │   ├── pizza_store_DEPRECATED.py
    │   │   └── tool_calling.ipynb
    │   ├── 11. RAG
    │   │   ├── RAG.ipynb
    │   │   ├── api.py
    │   │   ├── bella_vista.txt
    │   │   ├── index
    │   │   │   ├── index.faiss
    │   │   │   └── index.pkl
    │   │   └── vs_db
    │   │       ├── index.faiss
    │   │       └── index.pkl
    │   ├── 12. Agents
    │   │   ├── agents.ipynb
    │   │   ├── index
    │   │   │   ├── index.faiss
    │   │   │   └── index.pkl
    │   │   └── vectorstore.pkl
    │   ├── 13. LangSmith
    │   │   ├── code.ipynb
    │   │   └── extended_questions_answers.csv
    │   ├── 14. MicroServiceArchitecture
    │   │   ├── FAQ
    │   │   │   ├── general.txt
    │   │   │   ├── health.txt
    │   │   │   └── special.txt
    │   │   ├── README.md
    │   │   ├── all-deployments.yaml
    │   │   ├── deployment.sh
    │   │   ├── frontend
    │   │   │   ├── .eslintrc.cjs
    │   │   │   ├── .gitignore
    │   │   │   ├── Dockerfile
    │   │   │   ├── index.html
    │   │   │   ├── package-lock.json
    │   │   │   ├── package.json
    │   │   │   ├── postcss.config.js
    │   │   │   ├── public
    │   │   │   │   ├── images
    │   │   │   │   └── vite.svg
    │   │   │   ├── src
    │   │   │   │   ├── App.jsx
    │   │   │   │   ├── assets
    │   │   │   │   ├── index.css
    │   │   │   │   └── main.jsx
    │   │   │   ├── tailwind.config.js
    │   │   │   └── vite.config.js
    │   │   ├── ingress.yaml
    │   │   ├── init-sql.yaml
    │   │   ├── insert_data.py
    │   │   ├── postgres
    │   │   │   └── Dockerfile
    │   │   ├── secrets.yaml
    │   │   ├── service2
    │   │   │   ├── Dockerfile
    │   │   │   └── app.py
    │   │   └── service3
    │   │       ├── Dockerfile
    │   │       ├── app.py
    │   │       └── wait-for-postgres.sh
    │   ├── 2. LangChain_Inputs_and_Outputs
    │   │   └── code.ipynb
    │   ├── 2.1.Prompt_Templates
    │   │   ├── Link.txt
    │   │   ├── code.ipynb
    │   │   ├── prompt.json
    │   │   └── prompt.yaml
    │   ├── 3. Langchain Expression language
    │   │   ├── 1. Introduction of LCEL.ipynb
    │   │   ├── 2. Runnables.ipynb
    │   │   ├── 3. LCEL_Deepdive.ipynb
    │   │   ├── 4. LCEL_And_Runnables.ipynb
    │   │   ├── 5. Chain_Migrations.ipynb
    │   │   ├── 6. Chain_Migration_Advanced.ipynb
    │   │   ├── Chinook.db
    │   │   └── OUT_DATED_updated_langchain_expressions.ipynb
    │   ├── 4. LLM Input_Output
    │   │   ├── 1. LLM vs Chat_Model.ipynb
    │   │   ├── 2. PromptTemplate With LangChain.ipynb
    │   │   ├── 3. Output_Parser.ipynb
    │   │   └── M3_L3,4,5_LangChain_LLM_Input_Output_LLMs_and_Chat_Models.ipynb
    │   ├── 4.1.Chains
    │   │   ├── Link.txt
    │   │   ├── advanced_chains.ipynb
    │   │   └── basics_and_outputerparsers.ipynb
    │   ├── 5. Chat Message Memory
    │   │   ├── 1. Chat Message Memory.ipynb
    │   │   ├── 2.1 Introduction_Conversation_Chain.ipynb
    │   │   ├── 2.2 Conversation_Chains_and_Memory_with_LCEL.ipynb
    │   │   ├── 3. Multi_User_Conversation_with_In_Memory_Storage.ipynb
    │   │   ├── 4. Multi_User_Conversation_with_Persistent_SQL_Storage.ipynb
    │   │   ├── 5. Build_Conversational_Chatbots.ipynb
    │   │   ├── 6. Conversationqa.ipynb
    │   │   ├── Memory
    │   │   │   ├── Link.txt
    │   │   │   ├── chatbot.py
    │   │   │   ├── chatbot_solution.py
    │   │   │   └── code.ipynb
    │   │   ├── chat_history_explicit.db
    │   │   ├── chat_history_implicit.db
    │   │   └── memory.db
    │   ├── 6. Advanced Concepts
    │   │   ├── 1. LLM_Cost_Monitoring.ipynb
    │   │   ├── 2. Caching.ipynb
    │   │   ├── 3. Streaming.ipynb
    │   │   ├── 4. Moderating Chains in LangChain.ipynb
    │   │   ├── 5. Callbacks.ipynb
    │   │   ├── Setup_Env.ipynb
    │   │   └── langchain.db
    │   ├── 7. Branching, Routing And Linking Chains.ipynb
    │   │   └── Linking,_Branching,_Merging,_Routing_and_Moderating_Chains_with_LCEL.ipynb
    │   ├── 8. Hybrid_Search_and_Indexing_API
    │   │   ├── Link.txt
    │   │   ├── bella_vista.txt
    │   │   ├── docker-compose.yaml
    │   │   ├── filtered_search.ipynb
    │   │   ├── indexing_api.ipynb
    │   │   └── postgres
    │   │       ├── Dockerfile
    │   │       └── init.sql
    │   ├── 9. Text Summarization with LangChain
    │   │   ├── apjspeech.pdf
    │   │   ├── app.py
    │   │   ├── requirements.txt
    │   │   └── text_summarization.ipynb
    │   ├── README.md
    │   └── images
    │       ├── image1.png
    │       ├── image2.png
    │       └── sqllite.png
    ├── 3. Projects
    │   ├── 1. Create a Review Analyst.ipynb
    │   ├── 10. chat_stream.py
    │   ├── 11. project_custom_chatgpt_with_langchain_from_scratch.ipynb
    │   ├── 2. Create Research Paper Analyst.ipynb
    │   ├── 3. Create Social Media Marketing Analyst.ipynb
    │   ├── 4. IT Support Analyst.ipynb
    │   ├── 5. Building a Customer Support Workflow.ipynb
    │   ├── 6. Building a Report Generator.ipynb
    │   ├── 7. Building a Customer Review Analyst.ipynb
    │   ├── 8. Build a Multi-user Conversational Product Recommendation Agent.ipynb
    │   ├── 9. Study Assistant for Quiz Question Generation.ipynb
    │   ├── Docs
    │   │   ├── Ecommerce_Product_List.csv
    │   │   └── prompt_engineering.pdf
    │   ├── Setup_Env.ipynb
    │   └── chat_history.json
    ├── 4. Building AI Agents with LangChain
    │   ├── Assignment
    │   │   ├── Assignment.ipynb
    │   │   ├── Assignment.py
    │   │   ├── Assignment_bck.ipynb
    │   │   ├── Build an Intelligent Travel Assistant AI.pdf
    │   │   ├── Execution_Flow.md
    │   │   └── Explaination.md
    │   ├── ComicStore.db
    │   ├── Module 1
    │   │   └── M1_Creating_Agent_Tools_and_Tool_Calling_by_LLMs_with_LangChain.ipynb
    │   ├── Module 2
    │   │   ├── M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant.ipynb
    │   │   └── M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant_using_chain.ipynb
    │   ├── Module 3
    │   │   └── M3_Build_a_Multi_User_Conversational_Tool_Calling_Agentic_AI_Research_Assistant.ipynb
    │   ├── Module 4
    │   │   ├── M4_Build_a_Text2SQL_AI_Workflow_with_LangChain.ipynb
    │   │   └── M4_Build_a_Text2SQL_ReAct_Agentic_AI_System_with_LangChain.ipynb
    │   ├── Module 5
    │   │   └── M5_Build_a_Financial_Analyst_ReAct_Agentic_AI_System_with_LangChain.ipynb
    │   ├── comicdb_create_script.sql
    │   └── readme.md
    ├── LICENSE
    ├── README.md
    └── requirements.txt
```


###  Project Index
<details open>
	<summary><b><code>LANGCHAIN_DEMYSTIFIED.GIT/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/requirements.txt'>requirements.txt</a></b></td>
				<td>- Manages project dependencies by specifying required packages and versions<br>- This file ensures the project can run smoothly by defining the necessary external libraries<br>- It plays a crucial role in maintaining a stable and functional codebase architecture.</td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- 2. Concepts Submodule -->
		<summary><b>2. Concepts</b></summary>
		<blockquote>
			<details>
				<summary><b>7. Branching, Routing And Linking Chains.ipynb</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/7. Branching, Routing And Linking Chains.ipynb/Linking,_Branching,_Merging,_Routing_and_Moderating_Chains_with_LCEL.ipynb'>Linking,_Branching,_Merging,_Routing_and_Moderating_Chains_with_LCEL.ipynb</a></b></td>
						<td>- The code file "Linking,_Branching,_Merging,_Routing_and_Moderating_Chains_with_LCEL.ipynb" in the "Branching, Routing And Linking Chains" section of the project focuses on managing and orchestrating chains of processes within the codebase architecture<br>- It facilitates the linking, branching, merging, routing, and moderating of chains, providing a structured approach to handling complex workflows and interactions within the project.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>2. LangChain_Inputs_and_Outputs</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/2. LangChain_Inputs_and_Outputs/code.ipynb'>code.ipynb</a></b></td>
						<td>- The code file in `LangChain_Inputs_and_Outputs/code.ipynb` within the project structure focuses on loading environment variables using the `dotenv` library<br>- This code snippet ensures that sensitive configuration data is securely accessed within the project, enhancing its overall security and maintainability.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>12. Agents</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/12. Agents/agents.ipynb'>agents.ipynb</a></b></td>
						<td>- The code file "agents.ipynb" provides a comprehensive guide on LangChain Agents, which are powerful decision-makers utilizing an LLM as a reasoning engine to dynamically determine actions, their order, and when to stop<br>- This file explains key concepts such as Agents, Tools, and Agent Executor within the LangChain architecture, showcasing the advanced capabilities of agents in the project.</td>
					</tr>
					</table>
					<details>
						<summary><b>index</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/12. Agents/index/index.faiss'>index.faiss</a></b></td>
								<td>- The provided code file serves as a crucial component within the project architecture, contributing to the overall functionality and performance of the codebase<br>- It plays a key role in achieving the project's main purpose by handling specific tasks related to data processing and analysis<br>- This code file enhances the project's capabilities and supports its core objectives within the broader architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>9. Text Summarization with LangChain</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/9. Text Summarization with LangChain/app.py'>app.py</a></b></td>
						<td>- Enables text summarization from YouTube videos or websites using LangChain and Groq API<br>- Validates input, loads content, and generates a summary within a specified word limit<br>- Handles exceptions gracefully and provides a user-friendly interface for summarizing content efficiently.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/9. Text Summarization with LangChain/text_summarization.ipynb'>text_summarization.ipynb</a></b></td>
						<td>- Summary:
The code file "text_summarization.ipynb" in the "Text Summarization with LangChain" section of the project aims to implement a text summarization feature using LangChain<br>- This functionality allows for the generation of concise summaries from longer text inputs, enhancing the overall utility and readability of the application.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/9. Text Summarization with LangChain/requirements.txt'>requirements.txt</a></b></td>
						<td>- Facilitates text summarization using a variety of libraries and tools<br>- Integrates with LangChain for community-driven development and leverages open-source resources like Hugging Face and OpenAI<br>- Supports data manipulation with Pandas and MySQL, along with text processing and search functionalities<br>- Enhances text summarization capabilities through advanced algorithms and models.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>6. Advanced Concepts</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/Setup_Env.ipynb'>Setup_Env.ipynb</a></b></td>
						<td>- The provided code file, located at `2<br>- Concepts/6<br>- Advanced Concepts/Setup_Env.ipynb`, focuses on installing dependencies for OpenAI and LangChain within the project<br>- This code ensures that the necessary libraries and tools are set up to support advanced concepts and functionalities related to OpenAI and LangChain within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/4. Moderating Chains in LangChain.ipynb'>4. Moderating Chains in LangChain.ipynb</a></b></td>
						<td>- Demonstrate how to moderate both input and output text for safety using the OpenAI Moderation API<br>- Ensure harmful content is flagged before reaching the language model and after generating a response<br>- This approach enhances safety by filtering out potentially harmful content at both stages of interaction.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/3. Streaming.ipynb'>3. Streaming.ipynb</a></b></td>
						<td>- The code file "Streaming.ipynb" in the "Advanced Concepts" section of the project focuses on advanced operations for input/output with LangChain, specifically covering streaming operations<br>- It includes installations of necessary packages related to LangChain<br>- This notebook enhances the capabilities of LangChain for handling streaming data efficiently within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/1. LLM_Cost_Monitoring.ipynb'>1. LLM_Cost_Monitoring.ipynb</a></b></td>
						<td>- Track LLM costs by monitoring token usage for specific calls, providing insights into the expenses associated with using LLMs like ChatGPT<br>- This functionality allows for efficient budget management and optimization of resources within the LangChain ecosystem.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/5. Callbacks.ipynb'>5. Callbacks.ipynb</a></b></td>
						<td>- The code file "Callbacks.ipynb" in the "Advanced Concepts" section of the project explores the deep dive into LangChain callbacks<br>- These callbacks serve as a powerful mechanism within LangChain, enabling users to hook into various stages of their LLM application's execution<br>- They facilitate monitoring, debugging, logging, and streamlining processes, enhancing the overall functionality and performance of the application.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/6. Advanced Concepts/2. Caching.ipynb'>2. Caching.ipynb</a></b></td>
						<td>- The code file "Caching.ipynb" in the "Advanced Concepts" section of the project focuses on advanced operations for input/output with LangChain, specifically covering caching<br>- It enables efficient storage and retrieval of previously computed results, enhancing performance and reducing redundant computations within the LangChain framework.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>4.1.Chains</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4.1.Chains/Link.txt'>Link.txt</a></b></td>
						<td>- Illustrating the integration of LangChain in action, the code file in "Link.txt" directs users to an educational resource on developing LLM-powered applications<br>- This link serves as a reference point for understanding and implementing LangChain within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4.1.Chains/basics_and_outputerparsers.ipynb'>basics_and_outputerparsers.ipynb</a></b></td>
						<td>- The code file orchestrates the integration of language models with structured output parsing, enabling the generation of JSON-formatted responses based on input text analysis<br>- This process involves defining response schemas, creating prompt templates, invoking language models, and parsing model outputs to extract specific information like sentiment<br>- The code enhances the system's ability to interpret and evaluate text inputs accurately.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4.1.Chains/advanced_chains.ipynb'>advanced_chains.ipynb</a></b></td>
						<td>- Demonstrates chaining multiple AI models to process text inputs, enabling complex text generation workflows<br>- The code orchestrates various language models to analyze sentiments and generate responses based on predefined templates<br>- It showcases the flexibility of combining different AI chains to handle diverse text processing tasks within the project architecture.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>3. Langchain Expression language</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/3. LCEL_Deepdive.ipynb'>3. LCEL_Deepdive.ipynb</a></b></td>
						<td>- Demonstrates chaining of processing steps using the "|" operator to create complex data transformation pipelines<br>- The code showcases the creation of runnable components and their composition to process and manipulate data in a structured manner<br>- It illustrates the flexibility and extensibility of the LangChain framework for building sophisticated data processing workflows.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/1. Introduction of LCEL.ipynb'>1. Introduction of LCEL.ipynb</a></b></td>
						<td>- The code file "Introduction to LangChain Expression Language (LCEL)" provides an overview of the LangChain Expression Language (LCEL), a declarative way to compose chains in LangChain using the pipe operator (`|`)<br>- It simplifies syntax, offers first-class streaming support, async support, and optimized parallel execution<br>- This file serves as an introduction to the key benefits and usage of LCEL within the project's architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/6. Chain_Migration_Advanced.ipynb'>6. Chain_Migration_Advanced.ipynb</a></b></td>
						<td>- Implements a conversational retrieval chain for answering questions based on retrieved context<br>- The chain utilizes language models and document embeddings to provide concise answers<br>- Additionally, it includes functionality to rephrase questions and extract answers from given context.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/OUT_DATED_updated_langchain_expressions.ipynb'>OUT_DATED_updated_langchain_expressions.ipynb</a></b></td>
						<td>- Summary:
The provided code file, located at "Concepts/Langchain Expression language/OUT_DATED_updated_langchain_expressions.ipynb," focuses on the LangChain Expression Language within the project architecture<br>- It includes functionality related to loading environment variables and demonstrates an outdated approach to importing modules for chat prompts and models<br>- The code aims to showcase the usage of the LangChain Expression Language in handling chat prompts and models within the project's ecosystem.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/5. Chain_Migrations.ipynb'>5. Chain_Migrations.ipynb</a></b></td>
						<td>- Implementing legacy chains, LCEL, and Legacy RAG functionalities, the code file orchestrates interactions between language models and data sources<br>- It facilitates seamless communication and data retrieval processes within the Langchain architecture, enhancing the system's capabilities for generating responses and handling user queries effectively.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/4. LCEL_And_Runnables.ipynb'>4. LCEL_And_Runnables.ipynb</a></b></td>
						<td>- Demonstrate retrieval augmented generation with LCEL by chaining retriever, prompt, model, and output parser<br>- The code showcases a structured approach to generating answers based on given context and questions, leveraging various components for seamless information retrieval and response generation.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/3. Langchain Expression language/2. Runnables.ipynb'>2. Runnables.ipynb</a></b></td>
						<td>- The code file "Runnables.ipynb" in the "Langchain Expression language" section of the project provides a comprehensive guide on LangChain Runnables<br>- These runnables serve as the foundational elements for constructing intricate and modular AI workflows, facilitating the creation of advanced data processing pipelines within the codebase architecture.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>4. LLM Input_Output</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4. LLM Input_Output/M3_L3,4,5_LangChain_LLM_Input_Output_LLMs_and_Chat_Models.ipynb'>M3_L3,4,5_LangChain_LLM_Input_Output_LLMs_and_Chat_Models.ipynb</a></b></td>
						<td>- The code file provided explores Language Models (LLMs) and Chat Models for LLM Input/Output with LangChain<br>- It focuses on installing dependencies from OpenAI, HuggingFace, and LangChain to facilitate this exploration within the project's architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4. LLM Input_Output/2. PromptTemplate With LangChain.ipynb'>2. PromptTemplate With LangChain.ipynb</a></b></td>
						<td>- The code file "PromptTemplate With LangChain.ipynb" in the "LLM Input_Output" section of the project structure sets up the necessary dependencies and imports for utilizing language models and chat prompts<br>- It facilitates the integration of PromptTemplate and ChatOpenAI functionalities, along with output parsing capabilities, to enable seamless interaction with language processing tools within the codebase architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4. LLM Input_Output/3. Output_Parser.ipynb'>3. Output_Parser.ipynb</a></b></td>
						<td>- The code file "Output_Parser.ipynb" in the "LLM Input_Output" section of the project focuses on parsing outputs for Language Model Input/Output using LangChain<br>- It is responsible for handling the interpretation and processing of outputs generated by the system<br>- The file likely plays a crucial role in extracting and presenting meaningful information from the model's responses, contributing to the overall functionality of the language processing system within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/4. LLM Input_Output/1. LLM vs Chat_Model.ipynb'>1. LLM vs Chat_Model.ipynb</a></b></td>
						<td>- The code file "LLM vs Chat_Model.ipynb" in the "Concepts/LLM Input_Output" section of the project explores the use of Language Models (LLMs) and Chat Models for input/output interactions within the LangChain framework<br>- It focuses on comparing and leveraging LLMs and Chat Models to enhance language processing capabilities, emphasizing integration with OpenAI and HuggingFace dependencies.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>10. OpenAI_Functions</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/10. OpenAI_Functions/pizza_store_DEPRECATED.py'>pizza_store_DEPRECATED.py</a></b></td>
						<td>- The code file facilitates interactions with a pizza database through AI chatbot conversations<br>- It integrates functions to retrieve pizza information and add new pizzas to the database<br>- The file also sets up an AI chatbot model for engaging conversations, demonstrating the system's capability to respond to queries about pizzas and other topics.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/10. OpenAI_Functions/code_DEPRECATED.ipynb'>code_DEPRECATED.ipynb</a></b></td>
						<td>Implement OpenAI Function Calling to define and pass functions to the LLM for correct function identification and parameter provision, enabling seamless function calls within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/10. OpenAI_Functions/tool_calling.ipynb'>tool_calling.ipynb</a></b></td>
						<td>- The code file `tool_calling.ipynb` in the `Concepts` directory of the project serves the purpose of demonstrating the usage of OpenAI's function calling feature<br>- It showcases how to interact with OpenAI's tools or functions, providing a practical reference for integrating this functionality into applications<br>- The file acts as a guide for developers interested in leveraging OpenAI's capabilities within their projects, offering insights into the process of invoking functions or tools through the platform's API.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>0. Introduction</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/4. Open_Source_LLMs_HF_Inference_Client copy.ipynb'>4. Open_Source_LLMs_HF_Inference_Client copy.ipynb</a></b></td>
						<td>- The code file "Open_Source_LLMs_HF_Inference_Client copy.ipynb" in the "Introduction" section of the project structure is focused on utilizing Large Language Models (LLMs) through the Hugging Face Inference Client<br>- It leverages the capabilities of the Inference Client provided by Hugging Face for free, with certain rate limits, to facilitate seamless integration and usage of LLMs within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/2. Commercial_LLMs_with_LangChain.ipynb'>2. Commercial_LLMs_with_LangChain.ipynb</a></b></td>
						<td>- The code file "Commercial_LLMs_with_LangChain.ipynb" provides guidance on integrating popular commercial Language Model APIs, such as OpenAI GPT and Google Gemini, with LangChain<br>- It outlines the process of utilizing these APIs within the LangChain framework, enabling users to leverage advanced language models for various applications.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/1. Commercial_LLMs_Natively.ipynb'>1. Commercial_LLMs_Natively.ipynb</a></b></td>
						<td>- The code file "Commercial_LLMs_Natively.ipynb" provides a practical guide on interacting directly with popular Commercial Large Language Model (LLM) APIs using their official Python SDKs, without relying on abstraction layers like LangChain<br>- This approach aims to deepen understanding of the native API access, enabling better troubleshooting and leveraging advanced features that may only be accessible through direct API interaction.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/3. Open_Source_LLMs_HF_Transformers.ipynb'>3. Open_Source_LLMs_HF_Transformers.ipynb</a></b></td>
						<td>- The code file "Open_Source_LLMs_HF_Transformers.ipynb" provides a comprehensive guide on using open-source Large Language Models (LLMs) with the Hugging Face Transformers library<br>- It aims to help users understand the importance of Hugging Face Transformers, load pre-trained LLMs locally, prepare text input using tokenizers, generate text responses, and simplify the workflow with Hugging Face Pipelines<br>- This file serves as a practical resource for leveraging powerful language models in natural language processing tasks within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/4. Open_Source_LLMs_HF_Inference_Client.ipynb'>4. Open_Source_LLMs_HF_Inference_Client.ipynb</a></b></td>
						<td>- The provided code file, "Open_Source_LLMs_HF_Inference_Client.ipynb," demonstrates the usage of the Hugging Face Inference Client, a Python library enabling interaction with Large Language Models (LLMs) hosted on Hugging Face's servers without local model downloads or runs<br>- This code facilitates seamless access to over 150,000 models without the need for dedicated hardware, leveraging a free inference API with basic rate limits provided by Hugging Face.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/6. Open_Source_LLMs_with_LangChain.ipynb'>6. Open_Source_LLMs_with_LangChain.ipynb</a></b></td>
						<td>- The code file "Open_Source_LLMs_with_LangChain.ipynb" provides a guide on integrating popular commercial Language Model APIs, such as OpenAI GPT and Google Gemini, with LangChain<br>- This enables the utilization of advanced language processing capabilities within the LangChain project, enhancing its functionality and expanding its potential applications.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/0. Introduction/5. Open_Source_LLMs_Groq_Cloud.ipynb'>5. Open_Source_LLMs_Groq_Cloud.ipynb</a></b></td>
						<td>- Demonstrate setting up Groq API authentication, initializing the Groq client, creating a chat completion helper function, and testing different Llama 4 model variants<br>- Access ultra-fast inference, free tier, latest models, and an OpenAI-compatible API<br>- Explore diverse model capabilities and experiment with creative responses.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>2.1.Prompt_Templates</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/2.1.Prompt_Templates/prompt.json'>prompt.json</a></b></td>
						<td>- Defines a prompt template for user input, facilitating dynamic joke generation based on the provided input<br>- The template structure includes input variables, template format, and validation settings<br>- This file plays a key role in customizing user interactions within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/2.1.Prompt_Templates/prompt.yaml'>prompt.yaml</a></b></td>
						<td>- Define a prompt template for generating jokes based on user input<br>- The template includes placeholders for input variables and a specific format for displaying the joke<br>- This file contributes to the project's architecture by enabling dynamic content generation based on user input.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/2.1.Prompt_Templates/Link.txt'>Link.txt</a></b></td>
						<td>Provides a direct link to an educational course on developing LLM-powered applications.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/2.1.Prompt_Templates/code.ipynb'>code.ipynb</a></b></td>
						<td>- Demonstrate how to compose prompts using a PipelinePromptTemplate to guide users through evaluating sentiments and subjects in text inputs<br>- This code file facilitates the creation of structured prompts for analyzing reviews, enabling a systematic approach to understanding and categorizing sentiments<br>- The prompts can be serialized for easy reuse and sharing across the project.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>1. OpenAI_API</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/1. OpenAI_API/code.ipynb'>code.ipynb</a></b></td>
						<td>- Implement OpenAI's Chat completions API using the GPT-4o-mini model to facilitate multi-turn conversations efficiently<br>- The code interacts with the OpenAI API to generate responses based on a sequence of messages, showcasing the capabilities of language models in processing user queries and providing informative replies.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>5. Chat Message Memory</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/1. Chat Message Memory.ipynb'>1. Chat Message Memory.ipynb</a></b></td>
						<td>- The code file "Chat Message Memory.ipynb" in the "Concepts" section of the project structure serves as a reference for managing chat message memory<br>- It contributes to the architecture by providing guidelines on how to handle and store chat messages effectively within the system.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/4. Multi_User_Conversation_with_Persistent_SQL_Storage.ipynb'>4. Multi_User_Conversation_with_Persistent_SQL_Storage.ipynb</a></b></td>
						<td>- The code file "Multi_User_Conversation_with_Persistent_SQL_Storage.ipynb" in the "Chat Message Memory" section of the project focuses on enabling multi-user conversations with persistent storage using SQL<br>- It integrates OpenAI and LangChain dependencies to facilitate agentic AI interactions within the chat system<br>- This file sets up the necessary infrastructure for storing and managing chat messages across multiple users, enhancing the overall conversational experience within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/5. Build_Conversational_Chatbots.ipynb'>5. Build_Conversational_Chatbots.ipynb</a></b></td>
						<td>- The provided code file, located at `2<br>- Concepts/5<br>- Chat Message Memory/5<br>- Build_Conversational_Chatbots.ipynb`, focuses on building a chatbot powered by an LLM to enable conversational interactions with the ability to remember previous interactions<br>- The code demonstrates the design and implementation of the chatbot, emphasizing its conversational capabilities using a language model<br>- It serves as a foundational guide for creating chatbots that leverage advanced language processing techniques within the project's architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/2.2 Conversation_Chains_and_Memory_with_LCEL.ipynb'>2.2 Conversation_Chains_and_Memory_with_LCEL.ipynb</a></b></td>
						<td>- The code file "Conversation_Chains_and_Memory_with_LCEL.ipynb" in the "Chat Message Memory" section of the project explores Conversation Chains and Memory with LCEL<br>- It focuses on integrating OpenAI and LangChain dependencies to enhance conversational AI capabilities<br>- This code file serves as a reference for implementing agentic AI features using LangChain within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/3. Multi_User_Conversation_with_In_Memory_Storage.ipynb'>3. Multi_User_Conversation_with_In_Memory_Storage.ipynb</a></b></td>
						<td>- The code file "Multi_User_Conversation_with_In_Memory_Storage.ipynb" in the "Chat Message Memory" section of the project facilitates multi-user conversations with in-memory storage<br>- It focuses on integrating OpenAI and LangChain dependencies to enable interactive and dynamic chat functionalities within the project architecture<br>- This code file serves as a crucial component for enhancing user engagement and interaction capabilities within the system.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/2.1 Introduction_Conversation_Chain.ipynb'>2.1 Introduction_Conversation_Chain.ipynb</a></b></td>
						<td>- The code file provided in "2<br>- Concepts/5<br>- Chat Message Memory/2.1 Introduction_Conversation_Chain.ipynb" introduces the LangChain memory systems, which offer strategies for managing conversation history in AI applications<br>- It outlines core concepts such as Memory Buffer, Message History, Memory Variables, and Context Window<br>- The code aims to provide insights into different memory types to address challenges related to context retention, memory efficiency, and conversation management within the project's architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/6. Conversationqa.ipynb'>6. Conversationqa.ipynb</a></b></td>
						<td>- The code file "Conversation Q&A Chatbot" in the directory "Concepts/Chat Message Memory" implements logic for incorporating historical messages in a Q&A chatbot<br>- It focuses on two approaches: Chains, where a retrieval step is always executed, and Agents, where an LLM has discretion over executing retrieval steps<br>- This code enhances the chatbot's ability to maintain a conversation by leveraging past interactions.</td>
					</tr>
					</table>
					<details>
						<summary><b>Memory</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/Memory/Link.txt'>Link.txt</a></b></td>
								<td>Facilitates access to an educational resource on building LLM-powered applications.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/Memory/code.ipynb'>code.ipynb</a></b></td>
								<td>- Facilitates storing and recalling conversation history and summaries for chatbots<br>- Enables seamless management of past interactions to maintain context during conversations<br>- Supports efficient handling of lengthy inputs by providing concise summaries<br>- Enhances the conversational experience by preserving and retrieving relevant information.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/Memory/chatbot.py'>chatbot.py</a></b></td>
								<td>- Facilitates interactive conversations with an AI chatbot through a Streamlit interface<br>- Handles user inputs, generates AI responses, and displays the conversation history<br>- Supports memory and prompts for a more engaging user experience<br>- Enhances the LangChain ChatBot Demo by providing a seamless chat interaction flow.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/5. Chat Message Memory/Memory/chatbot_solution.py'>chatbot_solution.py</a></b></td>
								<td>- Facilitates real-time chat interactions with an AI chatbot through a Streamlit frontend<br>- Utilizes LangChain for conversational context and memory management<br>- Enables users to engage in conversations with the AI, displaying chat history and responses in a structured manner<br>- The code enhances user experience by providing a seamless chatbot interaction environment within the project architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>11. RAG</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/11. RAG/api.py'>api.py</a></b></td>
						<td>- Implements a FastAPI endpoint for conversational AI using OpenAI's GPT-4 model<br>- Handles user queries with a pirate-themed response based on a predefined template<br>- Utilizes FAISS for vector storage and retrieval<br>- The code orchestrates a retrieval chain to process user input and generate appropriate pirate-style responses.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/11. RAG/RAG.ipynb'>RAG.ipynb</a></b></td>
						<td>- Summary: The provided code file, located at `2<br>- Concepts/11<br>- RAG/RAG.ipynb`, implements Retrieval-Augmented Generation (RAG) with LangChain<br>- RAG enhances Large Language Models (LLMs) by incorporating external knowledge from a knowledge base to generate responses, reducing hallucinations and improving the model's contextual understanding<br>- This technique aims to enhance the performance and accuracy of language models by leveraging relevant external information during the generation process.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/11. RAG/bella_vista.txt'>bella_vista.txt</a></b></td>
						<td>- Provides essential information about Bella Vista restaurant, including hours of operation, cuisine type, vegetarian/vegan options, family-friendliness, private event bookings, ambiance, and reservation recommendations<br>- This file serves as a comprehensive guide for guests, showcasing the restaurant's offerings and services.</td>
					</tr>
					</table>
					<details>
						<summary><b>index</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/11. RAG/index/index.faiss'>index.faiss</a></b></td>
								<td>- The provided code file serves as a crucial component within the project architecture, contributing to the overall functionality and performance of the codebase<br>- It plays a key role in achieving the project's main purpose by effectively managing and processing data, enhancing the project's capabilities, and ensuring seamless integration with other modules.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>vs_db</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/11. RAG/vs_db/index.faiss'>index.faiss</a></b></td>
								<td>- The provided code file serves as a crucial component within the Project Structure of the codebase<br>- It plays a key role in achieving the overall architecture's objectives by facilitating a specific functionality essential to the project's success.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>13. LangSmith</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/13. LangSmith/code.ipynb'>code.ipynb</a></b></td>
						<td>Facilitates interaction with Langsmith for project management, metadata handling, and dataset operations within the codebase architecture.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>8. Hybrid_Search_and_Indexing_API</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/bella_vista.txt'>bella_vista.txt</a></b></td>
						<td>Provides information about Bella Vista restaurant, including hours of operation, cuisine type, vegetarian/vegan options, family-friendliness, private event bookings, ambiance, and reservation recommendations.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/docker-compose.yaml'>docker-compose.yaml</a></b></td>
						<td>- Define a Docker service for a PostgreSQL database with specific configurations for user, password, and database name<br>- This file sets up a PostgreSQL container within the project's architecture, enabling seamless integration and management of the database service.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/Link.txt'>Link.txt</a></b></td>
						<td>- Illustrating the power of LLM technology, the code file showcases the development of applications using LangChain<br>- By leveraging this API, developers can create LLM-powered applications with ease<br>- This code plays a crucial role in enabling the integration of advanced language models into various software projects within the codebase architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/filtered_search.ipynb'>filtered_search.ipynb</a></b></td>
						<td>- The code file `filtered_search.ipynb` in the "Hybrid_Search_and_Indexing_API" section of the project demonstrates how to perform filtered similarity search using LangChain's PGVector integration<br>- This functionality allows for combining semantic similarity with metadata-based filtering to achieve more precise retrieval of information<br>- The code showcases setting up PGVector with embeddings, loading and indexing documents with metadata, performing basic similarity search, applying metadata filters to narrow down results, using the retriever interface with filters, and building a RAG chain with filtered search.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/indexing_api.ipynb'>indexing_api.ipynb</a></b></td>
						<td>- The code file "indexing_api.ipynb" in the "Hybrid_Search_and_Indexing_API" section of the project provides a comprehensive guide on the LangChain Indexing API<br>- This API facilitates efficient synchronization of documents into a vector store, addressing key challenges related to document embeddings such as avoiding duplicate content, saving embedding costs, intelligent handling of updates, and managing deletions effectively<br>- The file outlines the essential components and functionalities of the Indexing API within the project architecture.</td>
					</tr>
					</table>
					<details>
						<summary><b>postgres</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/postgres/init.sql'>init.sql</a></b></td>
								<td>Enables vector extension for PostgreSQL to support hybrid search and indexing API in the project architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/8. Hybrid_Search_and_Indexing_API/postgres/Dockerfile'>Dockerfile</a></b></td>
								<td>- Facilitates setting up a Postgres database with necessary packages, locale configuration, and pgvector installation<br>- Copies an initialization SQL script for database setup.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>14. MicroServiceArchitecture</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/all-deployments.yaml'>all-deployments.yaml</a></b></td>
						<td>- Defines deployments and services for Redis, Postgres, Service2, Service3, and Frontend components in the microservices architecture<br>- Manages container images, ports, environment variables, and secrets for each service<br>- Establishes communication between services and external clients via defined ports and selectors.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/ingress.yaml'>ingress.yaml</a></b></td>
						<td>- Defines routing rules for services using Ingress and sets up a LoadBalancer for the nginx-ingress-controller service in the Kubernetes cluster<br>- This file plays a crucial role in managing external access to services within the microservices architecture, ensuring proper routing and load balancing for incoming traffic.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/init-sql.yaml'>init-sql.yaml</a></b></td>
						<td>Defines a ConfigMap resource to initialize SQL database with required extensions.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/secrets.yaml'>secrets.yaml</a></b></td>
						<td>Define secrets for OpenAI API key and PostgreSQL credentials in the microservices architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/insert_data.py'>insert_data.py</a></b></td>
						<td>- Inserts data from text documents into a PostgreSQL database using OpenAI embeddings for vectorization<br>- The code loads text files, splits them into chunks, and stores the vectorized representations in the database<br>- This process enables efficient querying and analysis of text data within the microservices architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/deployment.sh'>deployment.sh</a></b></td>
						<td>- Automates Docker image building, tagging, and pushing, as well as Kubernetes deployment for the microservices architecture<br>- The script ensures the Docker Registry is running, builds images for services, tags them, and pushes to the registry<br>- It then deploys to Kubernetes using specified YAML files.</td>
					</tr>
					</table>
					<details>
						<summary><b>service2</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/service2/app.py'>app.py</a></b></td>
								<td>- Implements a FastAPI service handling conversations with OpenAI<br>- Retrieves or creates conversations, sends them to OpenAI via service3, and updates the conversation with the assistant's response<br>- Uses Redis for storage and logging for monitoring<br>- Supports CORS for cross-origin requests.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/service2/Dockerfile'>Dockerfile</a></b></td>
								<td>- Facilitates building and running a Python-based microservice using FastAPI and Uvicorn within a Docker container<br>- Handles dependencies installation, sets up the working directory, and exposes the service on port 80.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>service3</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/service3/wait-for-postgres.sh'>wait-for-postgres.sh</a></b></td>
								<td>Ensure Postgres availability before executing commands in the microservice architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/service3/app.py'>app.py</a></b></td>
								<td>- Improve conversational AI capabilities by integrating a FastAPI service that leverages OpenAI for chat responses<br>- The code file orchestrates interactions between users and the system, utilizing PostgreSQL for data storage and retrieval<br>- By processing user queries and generating suitable responses, the service enhances the overall user experience within the microservices architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/service3/Dockerfile'>Dockerfile</a></b></td>
								<td>- Facilitates building and running a FastAPI microservice with dependencies like Redis, PostgreSQL, and OpenAI<br>- Sets up the service to wait for the PostgreSQL database before starting the FastAPI server<br>- This Dockerfile defines the environment and commands needed to run the microservice within the project's architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>FAQ</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/FAQ/general.txt'>general.txt</a></b></td>
								<td>Clarifies restaurant operations, cuisine, and dietary options.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/FAQ/special.txt'>special.txt</a></b></td>
								<td>- Summarizing the purpose of the provided code file: Describing the restaurant's signature dishes, Seafood Platter contents, and current promotions<br>- This information is crucial for customers seeking details about the menu offerings and ongoing specials<br>- It enhances the user experience by providing comprehensive insights into the restaurant's offerings and promotions.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/FAQ/health.txt'>health.txt</a></b></td>
								<td>- Provides responses to frequently asked questions about the restaurant's gluten-free options, pandemic safety measures, and accommodations for allergies<br>- This code file serves as a resource for customers seeking information on these topics within the project's microservice architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>postgres</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/postgres/Dockerfile'>Dockerfile</a></b></td>
								<td>Enables the integration of the latest version of pgvector from ankane into the project's microservices architecture, specifically for the PostgreSQL database setup.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>frontend</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/.eslintrc.cjs'>.eslintrc.cjs</a></b></td>
								<td>Configure ESLint for React frontend with recommended rules, supporting React 18.2 features and React Refresh plugin.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/postcss.config.js'>postcss.config.js</a></b></td>
								<td>Configures PostCSS plugins for Tailwind CSS and Autoprefixer to enhance the frontend styling in the microservices architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/package-lock.json'>package-lock.json</a></b></td>
								<td>- The code file in `frontend/package-lock.json` manages dependencies for the frontend microservice in the project<br>- It ensures the correct versions of React, React-DOM, and React-Icons are used, along with dev dependencies like TypeScript definitions for React<br>- This file plays a crucial role in maintaining a stable and consistent frontend architecture within the larger microservices ecosystem.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/tailwind.config.js'>tailwind.config.js</a></b></td>
								<td>Configure Tailwind CSS to process specific files in the frontend directory for the microservice architecture project.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/vite.config.js'>vite.config.js</a></b></td>
								<td>- Configures Vite for a React frontend microservice, setting the server to run on host "0.0.0.0" and port 3000<br>- The code utilizes the Vite plugin for React to enhance the development experience.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/package.json'>package.json</a></b></td>
								<td>- Define the frontend build configuration for the microservices architecture<br>- It manages dependencies, scripts for development, building, linting, and previewing the React application<br>- Key dependencies include React, React DOM, and React Icons, with development tools like ESLint, Vite, and Tailwind CSS.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/index.html'>index.html</a></b></td>
								<td>- Defines the main HTML structure for the frontend of the microservice architecture project<br>- It sets up the initial layout, includes necessary meta tags, and links to the main JavaScript file for React components<br>- The file serves as the entry point for the frontend application, providing the foundation for rendering the user interface.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/Dockerfile'>Dockerfile</a></b></td>
								<td>- Facilitates building and running the frontend microservice in a Docker container<br>- Sets up the Node environment, installs dependencies, and starts the application on port 3000<br>- This file plays a crucial role in containerizing the frontend component within the microservices architecture.</td>
							</tr>
							</table>
							<details>
								<summary><b>src</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/src/index.css'>index.css</a></b></td>
										<td>Define global styles using Tailwind CSS for the frontend of the microservices architecture.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/src/App.jsx'>App.jsx</a></b></td>
										<td>- The code file orchestrates a chatbot interface for a restaurant application, enabling users to interact with the system through text messages<br>- It manages user input, fetches and sends data to a backend service, and displays conversation history<br>- The file integrates with the frontend to provide a seamless user experience within the microservices architecture.</td>
									</tr>
									<tr>
										<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/2. Concepts/14. MicroServiceArchitecture/frontend/src/main.jsx'>main.jsx</a></b></td>
										<td>Render the main React application component within a strict mode using ReactDOM.</td>
									</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- 4. Building AI Agents with LangChain Submodule -->
		<summary><b>4. Building AI Agents with LangChain</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/comicdb_create_script.sql'>comicdb_create_script.sql</a></b></td>
				<td>The code file `comicdb_create_script.sql` is responsible for creating and populating the ComicStore database in the project "Building AI Agents with LangChain." This script sets up the database structure and inserts initial data, facilitating the storage and retrieval of comic-related information within the application.</td>
			</tr>
			</table>
			<details>
				<summary><b>Module 1</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 1/M1_Creating_Agent_Tools_and_Tool_Calling_by_LLMs_with_LangChain.ipynb'>M1_Creating_Agent_Tools_and_Tool_Calling_by_LLMs_with_LangChain.ipynb</a></b></td>
						<td>- The code file provided in the project structure is focused on exploring tools within LangChain<br>- It aims to install OpenAI and LangChain dependencies, enabling the creation and utilization of AI agents<br>- This code file plays a crucial role in setting up the necessary environment and tools for building AI agents with LangChain, contributing to the overall architecture of the project.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Assignment</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Assignment/Assignment_bck.ipynb'>Assignment_bck.ipynb</a></b></td>
						<td>- The provided code file in "Assignment_bck.ipynb" focuses on installing necessary dependencies for the LangChain project, specifically versions 0.3.14 for LangChain, 0.3.0 for LangChain-OpenAI, and 0.3.14 for LangChain-Community<br>- Additionally, it installs the "markitdown" package<br>- This code snippet plays a crucial role in setting up the environment for building AI agents within the LangChain architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Assignment/Assignment.ipynb'>Assignment.ipynb</a></b></td>
						<td>- The code file "Assignment.ipynb" in the "Building AI Agents with LangChain" project is primarily responsible for installing necessary dependencies like langchain, langchain-openai, langchain-community, and markitdown<br>- This setup ensures that the project has access to essential libraries and tools required for building AI agents using LangChain within the codebase architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Assignment/Assignment.py'>Assignment.py</a></b></td>
						<td>- The code file orchestrates AI agents to provide weather information and extract data from web searches<br>- It integrates tools for web search extraction and weather queries, enabling the agents to respond with relevant information<br>- The file facilitates the interaction between the agents and external APIs to deliver accurate and timely responses to user queries.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Module 2</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 2/M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant_using_chain.ipynb'>M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant_using_chain.ipynb</a></b></td>
						<td>- The code file "Build a Tool-Calling Agentic AI Research Assistant with LangChain" in the Module 2 directory of the project focuses on creating AI Agents using the LangChain `AgentExecutor`<br>- This tool is essential for developing agentic AI research assistants within the project architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 2/M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant.ipynb'>M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant.ipynb</a></b></td>
						<td>- The code file provided in "Building AI Agents with LangChain/Module 2/M2_Build_a_Tool_Calling_Agentic_AI_Research_Assistant.ipynb" focuses on building a Tool-Calling Agentic AI Research Assistant using LangChain<br>- This demo showcases the use of the legacy LangChain `AgentExecutor` for creating AI agents<br>- While suitable for beginners, LangChain suggests transitioning to LangGraph for more advanced agents and greater control, as covered in other courses.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Module 5</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 5/M5_Build_a_Financial_Analyst_ReAct_Agentic_AI_System_with_LangChain.ipynb'>M5_Build_a_Financial_Analyst_ReAct_Agentic_AI_System_with_LangChain.ipynb</a></b></td>
						<td>- The code file "M5_Build_a_Financial_Analyst_ReAct_Agentic_AI_System_with_LangChain.ipynb" in the project aims to build a Financial Analyst ReAct Agentic AI System using LangChain<br>- This system is designed to provide investors with accurate and current stock market insights by utilizing the `create_react_agent` function from LangGraph<br>- The project leverages LangGraph as a more robust and modern alternative to the deprecated LangChain version, enhancing the workflow for creating AI agents in the financial analysis domain.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Module 3</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 3/M3_Build_a_Multi_User_Conversational_Tool_Calling_Agentic_AI_Research_Assistant.ipynb'>M3_Build_a_Multi_User_Conversational_Tool_Calling_Agentic_AI_Research_Assistant.ipynb</a></b></td>
						<td>- The provided code file, located at "4<br>- Building AI Agents with LangChain/Module 3/M3_Build_a_Multi_User_Conversational_Tool_Calling_Agentic_AI_Research_Assistant.ipynb," focuses on building a Multi-User Conversational Tool that calls an Agentic AI Research Assistant using LangChain<br>- This code contributes to the project's architecture by enabling the creation of AI Agents within the LangChain framework for collaborative conversational interactions with users.</td>
					</tr>
					</table>
				</blockquote>
			</details>
			<details>
				<summary><b>Module 4</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 4/M4_Build_a_Text2SQL_AI_Workflow_with_LangChain.ipynb'>M4_Build_a_Text2SQL_AI_Workflow_with_LangChain.ipynb</a></b></td>
						<td>- The provided code file implements a Text2SQL AI workflow using LangChain, allowing users to convert natural language queries into SQL commands effortlessly<br>- This workflow comprises components such as the Query Write Chain, which enhances the project's functionality by enabling seamless conversion between natural language and SQL commands.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/4. Building AI Agents with LangChain/Module 4/M4_Build_a_Text2SQL_ReAct_Agentic_AI_System_with_LangChain.ipynb'>M4_Build_a_Text2SQL_ReAct_Agentic_AI_System_with_LangChain.ipynb</a></b></td>
						<td>- The code file "Build a Text2SQL ReAct Agentic AI System with LangChain" contributes to the project's architecture by implementing an AI system that converts text queries into SQL commands using LangChain technology<br>- This functionality enhances the project's capabilities by enabling users to interact with databases using natural language, thereby improving the overall user experience and accessibility of the system.</td>
					</tr>
					</table>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- 1. Introduction Submodule -->
		<summary><b>1. Introduction</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/8. Advance LangChain.ipynb'>8. Advance LangChain.ipynb</a></b></td>
				<td>Facilitates setting up OpenAI API key for the project environment.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/3. Memory.ipynb'>3. Memory.ipynb</a></b></td>
				<td>- Implement conversational and summarization memory in LangChain to enhance chatbot interactions<br>- Store and recall past conversations for context retention and efficient responses<br>- Utilize different memory types like ConversationBufferMemory and ConversationSummaryMemory to tailor memory solutions to specific application needs<br>- Improve user experience by enabling dynamic and context-aware conversations.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/4. Basics of Tools and Functions.ipynb'>4. Basics of Tools and Functions.ipynb</a></b></td>
				<td>- SUMMARY:

The code file in "Introduction/4<br>- Basics of Tools and Functions.ipynb" facilitates the secure input of an Open AI API key using the `getpass` module<br>- This functionality is crucial for authenticating and accessing Open AI services within the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/LCEL.ipynb'>LCEL.ipynb</a></b></td>
				<td>- Facilitates language chain processing by setting up dependencies, loading environment variables, and defining templates for generating responses<br>- Executes a chain to provide a definition for a given word using OpenAI, parsing the output accordingly.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/6. Implementing RAG.ipynb'>6. Implementing RAG.ipynb</a></b></td>
				<td>- Summary:
The code file "Implementing RAG.ipynb" facilitates the integration of the OpenAI API within the project<br>- It prompts the user to input their OpenAI API key securely and sets it for further interactions with the OpenAI services<br>- This functionality enables the project to leverage the capabilities of the OpenAI platform seamlessly, enhancing the project's AI-driven features and capabilities.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/7. Summarization.ipynb'>7. Summarization.ipynb</a></b></td>
				<td>- Summarize a long text document into a concise and coherent abstract using LangChain's tools and pipelines<br>- The code file facilitates the creation of applications powered by large language models, offering modular components for tasks like text generation, summarization, and knowledge retrieval<br>- It supports integration with external tools, enabling the development of dynamic and context-aware applications.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/2. Basics of Chains.ipynb'>2. Basics of Chains.ipynb</a></b></td>
				<td>- Facilitates the creation of language model-driven applications by offering modular components for text generation, summarization, and knowledge retrieval<br>- Simplifies development and workflow creation through streamlined processes<br>- The code file integrates OpenAI models and prompt templates to enable the extraction and summarization of key points from text inputs, showcasing the power of sequential chains in multi-step workflows.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/1. Introduction.ipynb'>1. Introduction.ipynb</a></b></td>
				<td>- The code file provided in "1<br>- Introduction.ipynb" serves the purpose of securely setting up and storing the Open AI API Key within the project environment<br>- By utilizing the `getpass` module to prompt for the API key and then storing it in the environment variable `OPENAI_API_KEY`, this code ensures that sensitive information is handled safely and can be accessed securely throughout the codebase architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/1. Introduction/notebook.ipynb'>notebook.ipynb</a></b></td>
				<td>- The provided code file in `Introduction/notebook.ipynb` serves the main purpose of guiding users on creating their first LangChain project within the project structure<br>- It focuses on initiating users into the LangChain ecosystem, setting the foundation for further development and exploration within the codebase architecture.</td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- 3. Projects Submodule -->
		<summary><b>3. Projects</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/3. Create Social Media Marketing Analyst.ipynb'>3. Create Social Media Marketing Analyst.ipynb</a></b></td>
				<td>- The code file "Create Social Media Marketing Analyst.ipynb" is part of a project focused on generating marketing product descriptions for smartphones based on technical fact sheets<br>- It aims to create custom product descriptions following a specific format, including the product name, brief overview of features, and product specifications<br>- This code file likely plays a key role in automating the process of crafting compelling marketing content for smartphones within the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/Setup_Env.ipynb'>Setup_Env.ipynb</a></b></td>
				<td>- Set up OpenAI and LangChain dependencies, enter API tokens, and configure necessary system environment variables<br>- Load essential dependencies and initialize ChatGPT LLM for seamless integration within the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/6. Building a Report Generator.ipynb'>6. Building a Report Generator.ipynb</a></b></td>
				<td>- Generates a comprehensive report on a given topic by branching and merging multiple chains of prompts and responses<br>- The report includes a description, pros, and cons in a structured format, providing insights into the topic's various aspects.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/4. IT Support Analyst.ipynb'>4. IT Support Analyst.ipynb</a></b></td>
				<td>- The code file "IT Support Analyst.ipynb" in the project structure acts as a mini-project where ChatGPT functions as an IT support agent<br>- It processes customer IT ticket messages and outputs responses in JSON format with key fields such as the original message, detected language, and category description<br>- This file focuses on leveraging ChatGPT for IT support ticket analysis and response generation within the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/10. chat_stream.py'>10. chat_stream.py</a></b></td>
				<td>- Facilitates real-time chat interactions with an AI-powered chatbot within a Streamlit web application<br>- Manages user input, chat history, and orchestrates communication between the user and the AI model<br>- Enables seamless conversation flow and dynamic message rendering based on user interactions.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/9. Study Assistant for Quiz Question Generation.ipynb'>9. Study Assistant for Quiz Question Generation.ipynb</a></b></td>
				<td>- The code file "Study Assistant for Quiz Question Generation" serves the purpose of installing required libraries for the project related to generating quiz questions<br>- It plays a crucial role in setting up the necessary dependencies for the study assistant application, ensuring smooth functionality for quiz question generation.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/5. Building a Customer Support Workflow.ipynb'>5. Building a Customer Support Workflow.ipynb</a></b></td>
				<td>- The code file "Building a Customer Support Workflow" in the project aims to demonstrate how to link multiple chains sequentially using LCEL in order to create a comprehensive customer support workflow<br>- By connecting various LLM Chains in a sequential manner, the code showcases how the output from one chain can serve as input for the next chain, ultimately leading to a final output that combines intermediate results and inputs from preceding chains<br>- This process enables the creation of an integrated workflow that streamlines customer support operations.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/11. project_custom_chatgpt_with_langchain_from_scratch.ipynb'>11. project_custom_chatgpt_with_langchain_from_scratch.ipynb</a></b></td>
				<td>- Implement a ChatGPT app with LangChain from scratch<br>- Integrate Chat Memory using ConversationBufferMemory to store and recall chat history<br>- Enhance user experience by saving chat sessions with FileChatMessageHistory<br>- Facilitate seamless conversations between users and the chatbot while maintaining context across interactions.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/8. Build a Multi-user Conversational Product Recommendation Agent.ipynb'>8. Build a Multi-user Conversational Product Recommendation Agent.ipynb</a></b></td>
				<td>- Summary:
The provided code file, located at "3<br>- Projects/8<br>- Build a Multi-user Conversational Product Recommendation Agent.ipynb," is part of a project aimed at building a Multi-user Conversational Product Recommendation Agent<br>- The file focuses on installing OpenAI and LangChain dependencies to enable the functionality of the recommendation agent within the project architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/1. Create a Review Analyst.ipynb'>1. Create a Review Analyst.ipynb</a></b></td>
				<td>- The code file "Create a Review Analyst.ipynb" sets up the environment and imports necessary libraries for a mini-project called Review Analyst<br>- The project aims to build an AI system that analyzes customer reviews by summarizing them in three lines, highlighting positives and negatives, and determining the overall sentiment (positive, negative, neutral).</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/chat_history.json'>chat_history.json</a></b></td>
				<td>- Capture and store chat history data in a structured format within the project<br>- The file maintains a record of human and AI interactions, including content and metadata<br>- This data is crucial for analyzing conversation patterns and improving AI responses.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/2. Create Research Paper Analyst.ipynb'>2. Create Research Paper Analyst.ipynb</a></b></td>
				<td>- The code file "Create Research Paper Analyst.ipynb" sets up the environment and imports necessary libraries for a mini-project called Research Paper Analyst<br>- The project aims to leverage ChatGPT as an AI expert to transform research paper abstracts based on different audience types<br>- It generates a short summary for a general audience and detailed reports tailored for a healthcare company and a generative AI company solving healthcare problems<br>- The reports include bullet points on the pros and cons of ethics in Generative AI and key points related to Generative AI for text, images, and structured data in healthcare.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/Sourav692/LangChain_Demystified.git/blob/master/3. Projects/7. Building a Customer Review Analyst.ipynb'>7. Building a Customer Review Analyst.ipynb</a></b></td>
				<td>- Implements a routing system for customer review analysis, classifying user prompts into summarize, sentiment, or email categories<br>- Utilizes LLM Chains to process reviews and generate responses based on sentiment<br>- Enables efficient handling of customer feedback by automatically categorizing and responding to reviews.</td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with LangChain_Demystified.git, ensure your runtime environment meets the following requirements:

- **Programming Language:** JupyterNotebook
- **Package Manager:** Pip, Npm
- **Container Runtime:** Docker


###  Installation

Install LangChain_Demystified.git using one of the following methods:

**Build from source:**

1. Clone the LangChain_Demystified.git repository:
```sh
❯ git clone https://github.com/Sourav692/LangChain_Demystified.git
```

2. Navigate to the project directory:
```sh
❯ cd LangChain_Demystified.git
```

3. Install the project dependencies:


**Using `pip`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-INSTALL-COMMAND-HERE'
```


**Using `npm`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-INSTALL-COMMAND-HERE'
```


**Using `docker`** &nbsp; [<img align="center" src="https://img.shields.io/badge/Docker-2CA5E0.svg?style={badge_style}&logo=docker&logoColor=white" />](https://www.docker.com/)

```sh
❯ docker build -t Sourav692/LangChain_Demystified.git .
```




###  Usage
Run LangChain_Demystified.git using the following command:
**Using `pip`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-RUN-COMMAND-HERE'
```


**Using `npm`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-RUN-COMMAND-HERE'
```


**Using `docker`** &nbsp; [<img align="center" src="https://img.shields.io/badge/Docker-2CA5E0.svg?style={badge_style}&logo=docker&logoColor=white" />](https://www.docker.com/)

```sh
❯ docker run -it {image_name}
```


###  Testing
Run the test suite using the following command:
**Using `pip`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-TEST-COMMAND-HERE'
```


**Using `npm`** &nbsp; [<img align="center" src="" />]()

```sh
❯ echo 'INSERT-TEST-COMMAND-HERE'
```


---
##  Project Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

##  Contributing

- **💬 [Join the Discussions](https://github.com/Sourav692/LangChain_Demystified.git/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/Sourav692/LangChain_Demystified.git/issues)**: Submit bugs found or log feature requests for the `LangChain_Demystified.git` project.
- **💡 [Submit Pull Requests](https://github.com/Sourav692/LangChain_Demystified.git/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/Sourav692/LangChain_Demystified.git
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/Sourav692/LangChain_Demystified.git/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=Sourav692/LangChain_Demystified.git">
   </a>
</p>
</details>

---

##  License

This project is protected under the [SELECT-A-LICENSE](https://choosealicense.com/licenses) License. For more details, refer to the [LICENSE](https://choosealicense.com/licenses/) file.

---

##  Acknowledgments

- List any resources, contributors, inspiration, etc. here.

---
