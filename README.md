# PORTFOLIO-TASK-6
Create a personal portfolio website using Flask that showcases personal information, skills, projects, and includes a contact form.
# Portfolio Website with Flask

### Tools & Technologies
- Python
- Flask
- HTML
- CSS

### Deliverable
Complete Flask project folder.

---

## Project Structure

```
portfolio-flask/
│
├── app.py
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── README.md
```

---

## Features

- Flask-based web application
- Personal portfolio homepage
- About Me section
- Skills and Projects display
- Contact form
- Clean and responsive design

---

## Setup Instructions

### 1. Install Flask

```bash
pip install flask
```

### 2. Run the Application

```bash
python app.py
```

### 3. Open in Browser

```
http://127.0.0.1:5000/
```

---

## Flask Routing Example

```python
from flask import Flask, render_template

app = Flask(__name__)

@app.route('/')
def home():
    return render_template('index.html')

if __name__ == '__main__':
    app.run(debug=True)
```

---

## Contact Form

The website includes a simple contact form with:
- Name field
- Email field
- Message field
- Submit button

---

## Learning Outcomes

By completing this project, you will learn:

- Flask application setup
- Routing in Flask
- HTML template rendering
- CSS styling
- Building a basic web form
- Creating a real-world mini web application

---

## Expected Output

A personal portfolio website that displays:
- Personal information
- Skills
- Projects
- Contact form

The website should be accessible through a local Flask server and demonstrate the fundamentals of web development using Flask.

---

## Author

Your Name
