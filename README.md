📂 Data-Retrieval-AI-Agent
An intelligent n8n workflow designed to retrieve specific data from .txt, .csv, or .json files based on user-defined queries. Built to enhance data accessibility through chatbot or webhook triggers, this agent delivers filtered and relevant results instantly.

🔍 Key Features
⚙️ Automated Query Processing: Extracts targeted information from uploaded files using natural language prompts.

📁 Multi-format Support: Works seamlessly with .txt, .csv, and .json file formats.

🤖 AI-Powered Understanding: Uses AI prompts to understand user queries and fetch accurate data.

🌐 Webhook & Chatbot Triggered: Activate data retrieval through chat interfaces or webhook requests.

🧠 Prompt Engineering: Crafted prompts to guide the AI agent for precise and context-aware data extraction.

🧰 Tech Stack
n8n – for workflow automation

OpenAI API – for natural language processing and query understanding

Webhook/HTTP Requests – to connect external interfaces

File Reader Nodes – to parse and process file data

JavaScript Function Nodes – for intermediate logic

🛠 Use Case
Perfect for:

Automating customer data lookups

Filtering product data on demand

Supporting internal teams with quick info access via chatbot

Enabling business teams to interact with structured/unstructured data using plain language

⚡ How It Works
A user sends a query along with a file (e.g., via chatbot or webhook).

The file is parsed and stored in memory.

The user’s question is passed to the AI agent, referencing the file content.

Relevant, filtered data is returned as the response.

👨‍💻 Developer Note
This project was independently designed and developed to demonstrate the integration of AI and automation for intelligent file querying. It reflects my experience in n8n, prompt engineering, and system automation.

🔗 Get Started
Clone this repository

Import the workflow into your n8n instance

Set up OpenAI credentials and file handling settings

Trigger the workflow via chatbot or webhook and test with sample queries

🤝 Feedback
I welcome ideas and suggestions to improve the workflow. Please feel free to fix this project, open issues, or connect if you find it helpful.
