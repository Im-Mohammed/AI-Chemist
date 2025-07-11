# **AI Chemist App** 🧪

**AI Chemist** is a Streamlit-based web application that utilizes Google's Gemini Pro Vision API to analyze images of pharmaceutical tablets. The app provides detailed information about the tablets, including their uses, functionalities, and distinguishing features.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Setup Instructions](#setup-instructions)
5. [How to Use](#how-to-use)
6. [Environment Variables](#environment-variables)
7. [Dependencies](#dependencies)
8. [Contributing](#contributing)
9. [License](#license)

---

## **Overview**

The AI Chemist app:
- Accepts an image of pharmaceutical tablets.
- Analyzes the image using the Gemini Pro Vision API.
- Provides detailed information, including tablet uses, functionalities, and specifications.

This application is useful for pharmacists, chemists, and individuals who need to identify or understand various tablets quickly.

---

## **Features**

- Upload an image of tablets (`jpg`, `jpeg`, `png` formats supported).
- Real-time tablet analysis using the **Gemini Pro Vision API**.
- Clear and concise descriptions of tablet functionalities.
- Easy-to-use web interface powered by Streamlit.

---

## **Technologies Used**

- **Python**: Core programming language.
- **Streamlit**: Web framework for building the user interface.
- **Google Gemini Pro Vision API**: For analyzing the uploaded images.
- **Pillow (PIL)**: For image handling and processing.
- **dotenv**: For managing environment variables securely.

---

## **Setup Instructions**

Follow these steps to set up the project locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/Im-Mohammed/AI-Chemist.git
cd AI-Chemist/aichem
## **2.Create a virtual env
```bash
python -m venv venv
venv\Scripts\activate
# For Mac/Linux
python3 -m venv venv
source venv/bin/activate
Sure! Here is the markdown code for your project:

```markdown
# AI-Chemist

## Install dependencies:
```bash
pip install -r requirements.txt
```

## Set up the environment variables:
- Create a `.env` file in the `aichem` directory.
- Add your Google API key:
```plaintext
GOOGLE_API_KEY=your_google_api_key
```

## Run the application:
```bash
streamlit run app.py
```
- Open the app in your browser at [http://localhost:8501](http://localhost:8501).

## Directory Structure
```bash
AI-Chemist/
│
├── aichem/
│   ├── app.py            # Main application file
│   ├── .env              # Environment variables file
│   ├── requirements.txt  # Python dependencies
│   ├── .git/             # Git repository
│
├── README.md             # Documentation
```

## Key Technologies
- **Streamlit**: For building the user interface.
- **Google Gemini Vision API**: For AI-based tablet analysis.
- **Python**: Backend programming.

## Troubleshooting
### Common Issues
**API Key Error**:
- Ensure your `.env` file contains a valid `GOOGLE_API_KEY`.

**Streamlit App Not Starting**:
- Verify all dependencies are installed by running:
```bash
pip install -r requirements.txt
```

**Gemini Vision Deprecation**:
- Ensure you are using a supported Gemini API model like `gemini-1.5-flash`.

## Contribution
Contributions are welcome!

1. Fork the repository.
2. Create a new branch:
```bash
git checkout -b feature-name
```
3. Commit your changes:
```bash
git commit -m "Add new feature"
```
4. Push to the branch:
```bash
git push origin feature-name
```
5. Open a Pull Request.
## License
This project is licensed under the MIT License.

## Author
Developed by Mohammed.

- [GitHub](https://github.com/)
