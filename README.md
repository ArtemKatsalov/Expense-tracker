# 📊 Expense Tracker (Personal Finance Manager)

A web application for managing personal finances, tracking income and expenses, generating charts, and performing budget analysis. 

## 📸 Screenshots
<img width="1872" height="935" alt="image" src="https://github.com/user-attachments/assets/e8c1029a-20c4-429b-8061-7a87810d5680" />
<img width="1877" height="896" alt="image" src="https://github.com/user-attachments/assets/1876a5d4-dd9d-438c-8ddc-87651379ddb5" />
<img width="1873" height="898" alt="image" src="https://github.com/user-attachments/assets/4eebc821-8683-464a-bff9-cf8dd32bbe80" />



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
### All-in-one - Windows
```
git clone https://github.com/ArtemKatsalov/Expense-tracker.git
python -m venv .venv
.venv\Scripts\Activate
cd Expense-tracker
python -m pip install -r requirements.txt
cd webapp
python manage.py migrate
python manage.py runserver
```

### All-in-one - Linux
```
git clone https://github.com/ArtemKatsalov/Expense-tracker.git
python -m venv .venv
chmod +x .venv/bin/activate
cd Expense-tracker
. .venv/bin/activatepython -m pip install -r requirements.txt
cd webapp
python manage.py migrate
python manage.py runserver
```

### One-by-one
#### Clone repo
```
git clone https://github.com/ArtemKatsalov/Expense-tracker.git
```

#### Set up a virtual environment:
```
python -m venv .venv
```

#### Switch to a virtual environment in a terminal
Windows:
```
.venv\Scripts\Activate
```
Linux/WSL:
```
chmod +x .venv/bin/activate
. .venv/bin/activate
```

#### Install all dependencies in an env
```
python -m pip install -r requirements.txt
```

#### Run local server
```
cd Expense-tracker\webapp
python manage.py migrate
python manage.py runserver
```

#### Credentials
`admin:admin`
