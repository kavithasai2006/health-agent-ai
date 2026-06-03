 🏥 Healthcare AI Agent
 📖 Project Description
Healthcare AI Agent is an AI-powered healthcare assistance system developed using Flask and Google Gemini AI. The application helps users get basic health-related guidance by analyzing symptoms entered through a web interface.
The system generates possible health suggestions, preventive measures, and general wellness advice in real time using Artificial Intelligence.
---
🎯 Objectives
- Provide basic healthcare guidance using AI.
- Analyze user-entered symptoms.
- Generate instant health suggestions.
- Create an easy-to-use healthcare assistant.
---
🚀 Features
- AI-powered symptom analysis
- Healthcare recommendations
- User-friendly interface
- Real-time response generation
- Responsive design
- Secure API integration
---
🛠️ Technologies Used
Frontend
- HTML
- CSS
- JavaScript
- Bootstrap
 Backend
- Python
- Flask
 AI Model
- Google Gemini API
 Libraries
- Flask
- google-generativeai
- python-dotenv

---
📂 Project Structure
Healthcare-AI-Agent/
├── server.py
├── .env
├── requirements.txt
├── templates/
│ └── home.html,index.html
└── README.md
---
⚙️ Installation Steps
 Step 1: Create Virtual Environment

```bash
python -m venv venv
````
 Step 2: Activate Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac
```bash
source venv/bin/activate
```
### Step 3: Install Required Packages
```bash
pip install -r requirements.txt
```
### Step 4: Configure Gemini API Key
Create a `.env` file and add:
```env
GEMINI_API_KEY=YOUR_GEMINI_API_KEY
```
### Step 5: Run the Application
```bash
python app.py
```
---
## 🌐 Application URL
After running the Flask server, open the following URL in your browser:
```text
http://127.0.0.1:5000
```
---

## 💡 How to Use

1. Launch the application.
2. Open:

```text
http://127.0.0.1:5000
```

3. Enter your symptoms or health-related query.
4. Click the Submit button.
5. View AI-generated healthcare suggestions.

---
## 📝 Example Input
```text
I have fever, headache, and cough.
```
## 📝 Example Output

```text
Possible Conditions:
- Common Cold
- Viral Infection
- Flu
Suggestions:
- Drink plenty of fluids
- Get enough rest
- Monitor symptoms
- Consult a healthcare professional if symptoms persist
```
---
## 🔒 Security Features
* API key stored in environment variables.
* No sensitive user information is stored permanently.
* Secure communication between frontend and backend.
---
## 🔮 Future Enhancements
* Voice-based healthcare assistant
* Medical report analysis
* Doctor appointment booking
* Medicine reminder system
* Emergency alert feature
* Multi-language support
---
## ⚠️ Disclaimer
This Healthcare AI Agent provides AI-generated health information for educational purposes only. It does not replace professional medical diagnosis, treatment, or consultation. Always seek advice from qualified healthcare professionals.
---
## 👩‍💻 Developed By
Kavitha Narne
B.Tech Project
Healthcare AI Agent using Flask & Google Gemini AI
---
## 📜 License
This project is developed for educational and academic purposes.
```
