# ai_agent
🎮 AI 3D PyGame Visualizer with DeepSeek R1

This Project demonstrates R1's code capabilities with a PyGame code generator and visualizer with browser use. The system uses DeepSeek for reasoning, OpenAI for code extraction, and browser automation agents to visualize the code on Trinket.io.

Features

Generates PyGame code from natural language descriptions
Uses DeepSeek Reasoner for code logic and explanation
Extracts clean code using OpenAI GPT-4o
Automates code visualization on Trinket.io using browser agents
Provides a streamlined Streamlit interface
Multi-agent system for handling different tasks (navigation, coding, execution, viewing)
How to get Started?

Clone the GitHub repository
git clone https://github.com/Shubhamsaboo/awesome-llm-apps.git
cd awesome-llm-apps/ai_agent_tutorials/ai_3dpygame_r1
Install the required dependencies:
pip install -r requirements.txt
Get your API Keys
Sign up for DeepSeek and obtain your API key
Sign up for OpenAI and obtain your API key
Run the AI PyGame Visualizer
streamlit run ai_3dpygame_r1.py
Browser use automatically opens your web browser and navigate to the URL provided in the console output to interact with the PyGame generator.
How it works?

Query Processing: User enters a natural language description of the desired PyGame visualization.
Code Generation:
DeepSeek Reasoner analyzes the query and provides detailed reasoning with code
OpenAI agent extracts clean, executable code from the reasoning
Visualization:
Browser agents automate the process of running code on Trinket.io
Multiple specialized agents handle different tasks:
Navigation to Trinket.io
Code input
Execution
Visualization viewing
User Interface: Streamlit provides an intuitive interface for entering queries, viewing code, and managing the visualization process.
