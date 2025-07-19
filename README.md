# **AI Chemist App** 🧪

**AI Chemist** is a Streamlit-based web application that utilizes Google's **Gemini Pro Vision API** to analyze images of pharmaceutical tablets. The app provides detailed information about the tablets, including their uses, functionalities, and distinguishing features.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [How to Use](#how-to-use)
6. [Environment Variables](#environment-variables)
7. [Dependencies](#dependencies)
8. [Directory Structure](#directory-structure)
9. [Troubleshooting](#troubleshooting)
10. [Contributing](#contributing)
11. [License](#license)
12. [Author](#author)
13. [Contact](#contact)

---

## **Overview**

The **AI Chemist** app:
- Accepts an image of pharmaceutical tablets.
- Analyzes the image using the **Gemini Pro Vision API**.
- Provides detailed information including uses, brand info, shape, and specifications.

This application is helpful for:
- Pharmacists and chemists 🧑‍⚕️  
- Researchers and students 🔬  
- Individuals trying to identify unknown tablets 💊

---

## **Features**

✅ Upload and analyze images of tablets (`.jpg`, `.jpeg`, `.png`)  
✅ Get detailed descriptions and use-cases of detected tablets  
✅ Gemini Vision API integration for image understanding  
✅ Minimal and clean UI built with Streamlit  
✅ Environment-secure via `.env` management  

---

## **Technologies Used**

- **Python** 🐍 – Core logic & backend
- **Streamlit** 📱 – For rapid web app development
- **Gemini Pro Vision API** 🔍 – For advanced image analysis
- **Pillow (PIL)** 🖼 – Image processing
- **dotenv** 🔐 – For managing API keys securely

---

## **Setup Instructions**

### 1. Clone the Repository
```bash
git clone https://github.com/Im-Mohammed/AI-Chemist.git
cd AI-Chemist/aichem
````

### 2. Create and Activate a Virtual Environment

#### For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

#### For Mac/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## **How to Use**

1. Add your Google API key in the `.env` file (see below).
2. Run the app:

```bash
streamlit run app.py
```

3. Upload an image of a tablet and get real-time insights.
4. Open your browser to [http://localhost:8501](http://localhost:8501).

---

## **Environment Variables**

Create a `.env` file in the `aichem/` directory and add your API key like this:

```plaintext
GOOGLE_API_KEY=your_google_api_key
```

---

## **Dependencies**

All dependencies are listed in `requirements.txt`. To install:

```bash
pip install -r requirements.txt
```

---

## **Directory Structure**

```
AI-Chemist/
│
├── aichem/
│   ├── app.py             # Main Streamlit application
│   ├── .env               # Environment variable config
│   ├── requirements.txt   # Python dependencies
│
├── README.md              # Project documentation
```

---

## **Troubleshooting**

### 🔑 API Key Error

* Ensure the `.env` file exists and has the correct `GOOGLE_API_KEY`.

### 🚫 Streamlit Not Running

* Double-check you’ve activated your virtual environment and installed all dependencies.

### ⚠️ Gemini Model Error

* Make sure you're using a supported Gemini model such as `gemini-1.5-flash` or newer.

---

## **Contributing**

Contributions are welcome!

1. Fork the repository.
2. Create a new branch:

```bash
git checkout -b feature-branch
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push to your branch:

```bash
git push origin feature-branch
```

5. Open a Pull Request.

---

## **License**

This project is licensed under the **MIT License**.

---

## **Author**

👨‍💻 Developed by **Mohammed Ali**

* [GitHub](https://github.com/Im-Mohammed)

---

## **Contact**

Have questions, feedback, or ideas?
🐙 GitHub Issues: [Submit here](https://github.com/Im-Mohammed/AI-Chemist/issues)

---
