# 🧪 Selenium Python Pytest Automation Framework

A clean, scalable, and maintainable test automation framework using **Selenium WebDriver**, **Python**, and **Pytest** — designed to ensure reliable end-to-end testing for modern web applications.

---

## 🚀 Key Features

- 🔧 Built with **Selenium WebDriver** for cross-browser UI testing  
- 🧱 **Page Object Model (POM)** architecture for modular and reusable test code  
- ⚡️ Supports **parallel test execution** with `pytest-xdist`  
- 📊 **HTML reporting** via `pytest-html`  
- ☁️ CI-ready for **GitHub Actions**, **GitLab CI**, and **Jenkins**  
- 🧪 Custom **Pytest fixtures** for flexible setup/teardown  
- 🌐 Easily extendable for **API testing** or **cloud testing platforms** (e.g. BrowserStack)


## ⚙️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/selenium-pytest-framework.git
cd selenium-pytest-framework
```

### 2. Set up a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## ✅ Running Tests

### Basic run
```bash
pytest tests/
```

### With verbose output and HTML report
```bash
pytest -v --html=reports/report.html --self-contained-html
```

### Run tests in parallel
```bash
pytest -n auto tests/
```

### Run tests with a specific browser (via CLI argument)
```bash
pytest --browser=chrome
```

---

## 📦 Dependencies

- `selenium`
- 'pytest-selenium'
- `pytest`
- `pytest-html`
- `pytest-xdist`
- `python-dotenv` *(optional for env config)*

Install all via:
```bash
pip install -r requirements.txt
```

---

## 🧩 Integrations

- Compatible with **GitHub Actions**, **GitLab CI**, **Jenkins**
- Easily extendable to work with **BrowserStack**, **Sauce Labs**, or **LambdaTest**
- Add **API tests** using `requests` or `httpx`

---

## 🤝 Contributing

Have ideas or improvements?  
Feel free to fork the repo, create a branch, and open a pull request. Contributions are welcome!

---

## 📄 License

This project is licensed under the [MIT License](LICENSE)


