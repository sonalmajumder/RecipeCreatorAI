# RecipeCreatorAI
# 🍳 AI Recipe Creator

The **AI Recipe Creator** a Generative AI project that takes a list of ingredients and uses an AI model to generate a creative and complete recipe for you! It features a clean frontend, Flask-based backend, and runs directly on Google Colab using ngrok for public access.

---

## 🚀 Features

- 🧠 Uses HuggingFace Transformers (GPT-2) to generate recipes
- 📦 Flask backend hosted on Google Colab
- 🌐 Public access via ngrok
- 💻 Sleek glassmorphism-based HTML frontend
- 🔄 Real-time recipe generation on user input

---

## 📁 Project Structure
AI-Recipe-Creator/
├── recipe_generator.py    # AI model logic using Transformers
├── app.py                 # Flask server with API endpoint
├── templates/
│ └── index.html           # User Interface (glassmorphism style)
├── static/                # (Optional: for CSS/images)
├── requirements.txt       # Required libraries
└── README.md              # Project documentation

### 🟢 Step 1: Clone or upload files to Colab

Upload:
- `recipe_generator.py`
- `app.py`
- `templates/index.html`

### 🟢 Step 2: Install dependencies

```bash
!pip install flask flask-ngrok transformers
