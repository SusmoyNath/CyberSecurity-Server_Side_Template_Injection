# Server Side Template Injection 🛡️

A simple demonstration of **Server-Side Template Injection (SSTI)** using the Flask web framework.

## 🔍 What is Server-Side Template Injection?

**Server-Side Template Injection (SSTI)** is a web vulnerability where attackers can inject malicious input into server-side templates. These templates are rendered on the server before being sent to the user, and if improperly handled, they can allow attackers to execute arbitrary code — even enabling **Remote Code Execution (RCE)**.

This project emulates an SSTI scenario in a controlled environment to help developers understand and test this class of vulnerability.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/SusmoyNath/CyberSecurity-Server_Side_Template_Injection.git
cd CyberSecurity-Server_Side_Template_Injection
```

### 2. Set Up the Environment

Make sure Python 3 and pip are installed.

#### Install Flask and virtualenv

```bash
pip3 install Flask
pip3 install virtualenv
```

### 3. Create a Virtual Environment

#### On Linux/macOS:

```bash
mkdir SSTIProject
cd SSTIProject
python3 -m venv venv
source venv/bin/activate
```

#### On Windows:

```cmd
mkdir SSTIProject
cd SSTIProject
python -m venv venv
venv\Scripts\activate
```

### 4. Set the Flask App Environment Variable

#### On Linux/macOS:

```bash
export FLASK_APP=hello.py
```

#### On Windows:

```cmd
set FLASK_APP=hello.py
```

---

## ▶️ Run the App

```bash
flask run
```

Visit `http://127.0.0.1:5000/` in your browser to interact with the demo.

---

## ⚠️ Disclaimer

This project is **for educational purposes only**. Do **not** deploy this code in production. The goal is to **understand and prevent** such vulnerabilities, not exploit them.

---

## 📚 References

- [OWASP: Server-Side Template Injection](https://owasp.org/www-community/attacks/Server-Side_Template_Injection)
- [PayloadsAllTheThings - SSTI](https://github.com/swisskyrepo/PayloadsAllTheThings/tree/master/Server%20Side%20Template%20Injection)

---

## 🧠 Learn, Practice, Secure

If you're exploring web security or working in DevSecOps, understanding SSTI is crucial. Use this demo to test, learn, and level up your security awareness!
