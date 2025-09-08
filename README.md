# **AI Chemist** 🧪  
**Identify tablets instantly. Empower healthcare safely.**

[🌐 Live Demo](https://ai-chemist-odhv.onrender.com/) 

---

## **Overview**

**AI Chemist** is a web-based tool that uses **Gemini Pro Vision API** to analyze images of pharmaceutical tablets and provide instant, detailed insights. Whether you're a pharmacist verifying medication, a researcher cataloging compounds, or a curious individual trying to identify a pill—AI Chemist makes it effortless.

🧠 Powered by AI.  
📸 Just upload an image.  
💊 Get verified tablet info in seconds.

---

## **Key Features**

✨ **Tablet Recognition** – Upload `.jpg`, `.jpeg`, or `.png` images  
🔍 **Gemini Vision Integration** – Advanced image-to-text analysis  
📋 **Detailed Output** – Uses, brand, shape, and specifications  
🧪 **Secure & Scalable** – Environment-managed API keys  
🖥️ **Streamlit UI** – Clean, intuitive interface for all users

---

## **Who Is It For?**

- 🧑‍⚕️ **Pharmacists & Chemists** – Quick verification and lookup  
- 🔬 **Researchers & Students** – Educational and lab use  
- 💊 **General Users** – Identify unknown tablets safely  
- 🧠 **AI Enthusiasts** – Explore Gemini Vision in action

---

## **Live Demo**

Try it now:  
👉 [AI Chemist Web App](https://ai-chemist-odhv.onrender.com/)

> ⚠️ If the app shows “Streamlit Stop,” it may be sleeping due to inactivity. Just refresh or wait a few seconds.

---

## **Tech Stack**

| Tool                | Purpose                          |
|---------------------|----------------------------------|
| Python 🐍           | Core logic and backend           |
| Streamlit 📱        | Web interface                    |
| Gemini Pro Vision 🔍| Image analysis                   |
| Pillow (PIL) 🖼      | Image preprocessing              |
| dotenv 🔐           | Secure API key management        |

---

## **Setup Instructions**

```bash
# Clone the repo
git clone https://github.com/Im-Mohammed/AI-Chemist.git
cd AI-Chemist/aichem

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
```

---

## **Usage Guide**

1. Add your Google API key to `.env`:
   ```plaintext
   GOOGLE_API_KEY=your_google_api_key
   ```

2. Launch the app:
   ```bash
   streamlit run app.py
   ```

3. Open [http://localhost:8501](http://localhost:8501) in your browser  
4. Upload a tablet image and view results instantly

---

## **Project Structure**

```
AI-Chemist/
├── aichem/
│   ├── app.py             # Main app logic
│   ├── .env               # API key config
│   ├── requirements.txt   # Dependencies
├── README.md              # Documentation
```

---

## **Troubleshooting**

- 🔑 **API Key Error** – Check `.env` file and key format  
- 🚫 **Streamlit Not Running** – Ensure virtual environment is active  
- ⚠️ **Gemini Model Error** – Use supported models like `gemini-1.5-flash`

---

## **Contributing**

Pull requests are welcome!  
Fork → Branch → Commit → Push → PR

```bash
git checkout -b feature-branch
git commit -m "Add new feature"
git push origin feature-branch
```

---

## **License**

Licensed under the **MIT License** – free to use, modify, and distribute.

---

## **Author**

👨‍💻 Created by **Mohammed Ali**  
🔗 [GitHub Profile](https://github.com/Im-Mohammed)

---

## **Contact**

💬 Questions or feedback?  
Open an issue on [GitHub](https://github.com/Im-Mohammed/AI-Chemist/issues)
