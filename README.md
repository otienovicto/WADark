# 🕵️‍♂️ WADark - WhatsApp Phishing Tool via OTP Code

WADark is a phishing tool designed to capture OTP codes from WhatsApp web sessions. This tool leverages Selenium for web automation, Flask for the web interface, and Tesseract for Optical Character Recognition (OCR) to extract OTP codes from the screenshots captured during the WhatsApp web login process.

> ⚠️ **Warning:** This tool is intended for educational purposes only. Unauthorized use of this tool to access someone's account without permission is illegal and unethical. Use responsibly.

```bash
Dev: LSDeep - v1.0.0

```
## ✨ Features

- 🛡️ **Phishing via OTP**: Capture OTP codes during the WhatsApp web login process.
- 🤖 **Web Automation**: Uses Selenium WebDriver for automating interactions with the WhatsApp web interface.
- 🔍 **OCR Integration**: Extracts text from images using Tesseract OCR for accurate OTP retrieval.
- 🌐 **Flask Web Interface**: Simple, intuitive web UI for user interaction.
- 📝 **Data Logging**: Captures user details including IP, User-Agent, and location information.

## 📋 Prerequisites

- 🐍 **Python 3.7+**: Ensure Python is installed on your machine.
- 🌐 **Ngrok**: Required to expose the Flask application to the internet.
- 🖥️ **ChromeDriver**: Compatible version of ChromeDriver to run Selenium WebDriver.
- 🔠 **Tesseract OCR**: Install Tesseract and update the path in the script. [Tesseract OCR Installation Guide](https://github.com/UB-Mannheim/tesseract/wiki)


## 🛠️ Setup & Installation

The application is provided preconfigured. However, the following prerequisites must be installed on your computer before running WADark:

- **Python** – Required to run the application.
- **Google Chrome** – Required for browser automation.
- **Tesseract OCR** – Required for image text recognition.
- **Ngrok** – Required for public tunnel connectivity, if not already bundled or configured.

1. Install Prerequisites

Install the following before running the application:

Python: https://www.python.org/downloads/

Google Chrome: https://www.google.com/chrome/

Tesseract OCR: https://github.com/UB-Mannheim/tesseract/wiki

Ngrok: https://ngrok.com/download

2. Create a Virtual Environment

Open Command Prompt (CMD) inside the WADark project folder.

Create the virtual environment:

python -m venv venv

3. Activate the Virtual Environment

Activate the environment:

venv\Scripts\activate

Once activated, your terminal should display (venv) at the beginning of the command line.

4. Install Dependencies

Install the required Python packages:

pip install -r requirements.txt

### 1. Install Tesseract OCR

Download and install Tesseract OCR for Windows:

https://github.com/UB-Mannheim/tesseract/wiki

Use the default installation location where possible:

`C:\Program Files\Tesseract-OCR\tesseract.exe`

### 2. Install Google Chrome

Download Google Chrome:

https://www.google.com/chrome/

### 3. Launch WADark

1. Open Command Prompt (CMD).
2. Navigate to the WADark application folder.
3. Run:

   ```cmd
   python WADark.py
   ```

The application will initialize and start its services.

## 🚀 Usage

Once the application is running, follow the application's on-screen instructions to proceed.

   ```

## 🛡️ How It Works

1. 📝 Phishing Page: Users are prompted to enter their phone number on the web page.
2. 🤖 WhatsApp Web Automation: The tool uses Selenium to navigate through the WhatsApp web interface.
3. 🔍 OTP Extraction: A screenshot of the OTP area is taken, and the OTP is extracted using Tesseract OCR.
4. 📊 Data Logging: User details, OTP code, and other information are logged to a text file for analysis.



