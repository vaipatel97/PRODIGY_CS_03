# PRODIGY_CS_03
Password Complexity Checker
# Password Complexity Checker 🔐

A Flask-based web application that helps users assess the strength of their passwords and detect potential security risks. This tool ensures users create stronger, more secure passwords while alerting them to possible breaches.

## 🚀 Features

✅ **Instant Strength Analysis** – Evaluates length, character variety & overall complexity.

✅ **Breach Detection** – Leverages Have I Been Pwned API to identify compromised passwords.

✅ **Strong Password Generator** – Creates secure, random passwords instantly.

✅ **Interactive UI** – Provides real-time feedback with a dynamic progress bar.

✅ **Flask-Powered Backend** – Efficient processing & seamless API integration.

## 📂 Project Structure
```
password-complexity-checker/
│── templates/             # HTML templates
│── app.py                 # Python resource file and Flask application

```

## 🛠️ Technology Used 
-**Frontend:** HTML, CSS, JavaScript

-**Backend:** Python, Flask

-**API:** Have I Been Pwned API for breach detection

## ⚙️ Installation & Setup

### Prerequisites:
- Python 3.x (or higher)
- Flask
- Requests library (Python package for HTTP requests)
- Have I Been Pwned API key (optional for breach detection)

### Steps to Install & Run:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/vaipatel97/PRODIGY_CS_03.git
   cd password-complexity-checker
   ```
   
2. **Give path to the project directory**   
   ```bash
   cd PRODIGY_CS_03-main
   ```

   **Create a virtual environment (optional but recommended):** 
   ```
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. **Install required packages**
   ```bash
    pip install flask requests
   ```

4. **Run the Flask App**
   ```bash
   python app.py
   ```

5. **Open in Browser**
   - Navigate to `http://127.0.0.1:5000/` in your web browser.
  
## 🔗 API Integration ##
This project utilizes the **Have I Been Pwned API** to check if a password has been compromised. To enable this feature:
- Obtain an API key from [Have I Been Pwned](https://haveibeenpwned.com/API/v3)


## 🧑‍💻Usage ##

1. **Check Password Strength:**

    -Input or generate a password in the designated field.
    
     -The tool analyzes its strength, provides a score, suggests improvements, and checks for breaches.

2. **Create a Strong Password:**

    -Click on the "Generate Secure Password" button to instantly get a highly secure password.
    
    -The generated password is automatically assessed for strength and security.

3. **Live Feedback & Updates:**

    -You type or generate a password, the strength meter and recommendations update dynamically in real time.


## 📖How It Works ##
This application evaluates password complexity using regular expressions and secure API requests. It checks for:

🔹 **Length:** Ensures a minimum of 8 characters.

🔹 **Character Variety:** Verifies the presence of uppercase, lowercase, numbers, and special characters.

🔹 **Breach Check:** Converts the password into a SHA-1 hash and cross-checks it with Have I Been Pwned API for known breaches.

The backend processes this data and provides a detailed strength score along with personalized suggestions to improve password security.



## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.



## 🔗 Connect with Me
- **LinkedIn**: https://www.linkedin.com/in/vaibhavpatel25/
- **GitHub**: https://github.com/vaipatel97

---

Excited to keep learning and improving password security! 🚀
