Sugarcoat - Powered by Flask & Azure Cognitive Services
Welcome to the Sugarcoat project! This web application allows users to translate text between languages using the power of Azure Cognitive Services and the simplicity of Flask.

Whether you're a beginner in AI or a developer looking to explore the possibilities of cloud-based translation, this project is perfect for you! 🎉🌍

🚀 Features
Real-time Translation: Translate text between multiple languages in real-time.
Simple & Interactive UI: Built with Flask, providing a seamless web experience.
Powered by Azure Cognitive Services: Utilizing the cutting-edge Azure Translator API for accurate and efficient translations.
🛠️ Tech Stack
Python: The programming language used for building the backend.
Flask: A lightweight web framework for Python to create the web application.
Azure Cognitive Services: Specifically the Translator API for real-time translations.
HTML/CSS: Front-end code for the user interface.
📋 Prerequisites
Before you can start using or developing the project, you'll need to set up the following:

Python 3.x (>= 3.8)

You can download it from the official Python website.
VS Code or any preferred IDE/Text Editor

For seamless development, we recommend using VS Code. You can get it from here.
Azure Student Account

If you don't have one yet, you can sign up for a free Azure student account here. You'll need it to access the Azure Translator API.
GitHub Account

Fork or clone the repository, and make sure you’re set up with Git to track your changes.
🔧 Getting Started
To set up this project on your local machine, follow these steps:

Clone the repository:

bash
Copy
git clone https://github.com/beingtechsavy/ai-web-translator.git
Install dependencies: Ensure you’re inside the project directory and install the required Python packages.

bash
Copy
cd ai-web-translator
pip install -r requirements.txt
Set up your Azure Translator API key:

Go to the Azure Portal and create a Translator resource.
Copy your API key and Endpoint.
Create a .env file in your project root and add:
ini
Copy
AZURE_TRANSLATOR_KEY=your_api_key_here
AZURE_TRANSLATOR_ENDPOINT=your_endpoint_here
Run the application: Start the Flask server to launch the app locally:

bash
Copy
python app.py
Now, visit http://127.0.0.1:5000/ in your browser to interact with your AI-powered translator!

✨ How It Works
The app allows users to input text and select the language they want to translate to.
Upon submission, the Azure Translator API processes the request and returns the translated text.
The app then displays the translation in real-time, giving the user immediate feedback.


🧑‍🤝‍🧑 Contributing
We welcome contributions to improve the project! Here’s how you can help:

Report Bugs: Open an issue for any bugs you encounter.
Submit a Pull Request: If you want to add a feature or improve the app, feel free to fork the repository and submit a PR.
Documentation: Help us enhance the README or add additional documentation for ease of use.



