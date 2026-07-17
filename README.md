# 📊 Expense Tracker (Personal Finance Manager)

A web application for managing personal finances, tracking income and expenses, generating charts, and performing budget analysis. 

## 🛠 Tech Stack
* **Backend:** Python, Django
* **Frontend:** HTML, CSS, Bootstrap 5
* **Tools:** Git (GitHub), Trello (Agile/Kanban)

## 👨‍💻 My Role in the Project
As a co-creator of this team project, my main responsibilities included:
* Designing and implementing a responsive User Interface (UI) using HTML, CSS, and Bootstrap 5.
* Creating and optimizing Django templates for key application views (Dashboard, Transaction History, Monthly Summary).
* Integrating frontend views with Python backend logic.
* Implementing bilingual application localization (i18n) - supporting Polish and English languages.
* Actively working with Git version control: branch management, resolving conflicts, and conducting code reviews.
* Performing manual testing (QA) of deployed features.

---

## 🚀 How to run locally
# All-in-one - Windows
```
git clone https://github.com/0Jan2137/projekt_aplikacja.git
python -m venv .venv
.venv\Scripts\Activate
python -m pip install -r requirements.txt
cd projekt_aplikacja\webapp
python manage.py migrate
python manage.py runserver
```

# All-in-one - Linux
```
git clone https://github.com/0Jan2137/projekt_aplikacja.git
python -m venv .venv
chmod +x .venv/bin/activate
. .venv/bin/activatepython -m pip install -r requirements.txt
cd projekt_aplikacja\webapp
python manage.py migrate
python manage.py runserver
```

# One-by-one
### Clone repo
```
git clone https://github.com/0Jan2137/projekt_aplikacja.git
```

### Set up a virtual environment:
```
python -m venv .venv
```

### Switch to a virtual environment in a terminal
Windows:
```
.venv\Scripts\Activate
```
Linux/WSL:
```
chmod +x .venv/bin/activate
. .venv/bin/activate
```

### Install all dependencies in an env
```
python -m pip install -r requirements.txt
```

### Run local server
```
cd projekt_aplikacja\webapp
python manage.py migrate
python manage.py runserver
```

### Credentials
`admin:admin`
