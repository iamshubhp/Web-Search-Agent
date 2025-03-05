# Web Search Agent

This is an AI-powered web search agent that utilizes Groq's AI models and DuckDuckGo search to fetch real-time information from the web. It is built using the Phidata framework and runs as a simple script in Python.

# Features

- Uses Groq's AI model for generating responses.

- Fetches real-time web search results using DuckDuckGo.

- Displays sources of information for transparency.

- Supports streaming responses for an interactive experience.

- Designed with debug mode for easier troubleshooting.

# Installation

- To set up this project, follow these steps:

1. Clone the Repository

git clone https://github.com/iamshubhp/Web-Search-Agent.git
cd Web-Search-Agent

2. Create a Virtual Environment (Optional but Recommended)

conda create -n YOURENVIRONMENTNAME python=3.12 -y

and than run activate the environment using 
conda activate YOURENVIRONMENTNAME

3. Install Dependencies

pip install -r requirements.txt

# API Key Setup

This project requires an API key for Groq Cloud. Since API keys are sensitive information, the .env file is included in .gitignore to prevent accidental exposure.

1. Create a .env file

Inside the project directory, create a new file named .env and add your Groq API key:

GROQ_API_KEY=your_groq_api_key_here

2. Obtain a Groq API Key

To get an API key, follow these steps:

Go to Groq Cloud.

Generate a new API key from the dashboard.

Copy the key and paste it into your .env file.

# Running the Web Search Agent

Once the setup is complete, you can run the agent using:

python main.py or python yourfilename.py

# Example Usage

The agent is designed to answer web search queries. For example:

web_search_agent.print_response("Who is the Prime Minister of Canada?", stream=True)

This will fetch the latest information and include sources in the response.

# Tutorial Video

A tutorial video is attached below to show how it works!



https://github.com/user-attachments/assets/d0141d8c-f429-45bc-a16a-0f0d83d0b608



