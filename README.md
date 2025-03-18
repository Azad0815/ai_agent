# 🎮 AI-Powered PyGame Code Generator

An interactive Streamlit web app that generates PyGame visualizations using AI models like DeepSeek R1 and OpenAI's GPT-4o. It also provides an option to run the generated code in Trinket.io.

## 🚀 Features
- **Natural Language to PyGame Code**: Enter a query describing your PyGame visualization, and AI will generate the corresponding Python code.
- **AI-Powered Code Generation**: Uses DeepSeek R1 for reasoning and GPT-4o for extracting clean PyGame code.
- **Trinket.io Integration**: Enables users to run the generated PyGame code directly in an online editor.
- **Secure API Key Handling**: Uses Streamlit’s session state to store and manage API keys securely.

## 🛠️ Installation
### 1. Clone the Repository
```sh
git clone https://github.com/your-username/pygame-code-generator.git
cd pygame-code-generator
```

### 2. Create a Virtual Environment (Optional but Recommended)
```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3. Install Dependencies
```sh
pip install -r requirements.txt
```

## 🏃‍♂️ Usage
### Run the Streamlit App
```sh
streamlit run app.py
```

### API Key Configuration
1. Enter your **DeepSeek API Key** and **OpenAI API Key** in the Streamlit sidebar.
2. Provide a PyGame-related query (e.g., "Create a bouncing ball simulation").
3. Click **Generate Code** to receive AI-generated PyGame code.
4. Click **Generate Visualization** to open Trinket.io and run the code.

## 📌 Example Queries
- "Create a simple platformer game with gravity and jumping mechanics."
- "Simulate a particle explosion effect when the user clicks the screen."
- "Generate a top-down 2D car racing game with keyboard controls."

## 🔧 Configuration
Modify `app.py` to tweak:
- **AI Model Settings** (e.g., token limits, model versions)
- **Code Extraction Process**
- **Browser Automation for Trinket.io**

## 🐛 Troubleshooting
- **Invalid API Key Errors**: Ensure your API keys are correct and have active subscriptions.
- **Code Not Generating**: Try using a more detailed query or restart the app.
- **Visualization Not Running**: Copy the generated code manually to Trinket.io if automation fails.

## 📜 License
This project is licensed under the MIT License. See `LICENSE` for details.

## 🤝 Contributing
Pull requests are welcome! If you’d like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## 📬 Contact
For questions or suggestions, feel free to open an issue or contact me at azad.yadav302@gmail.com


