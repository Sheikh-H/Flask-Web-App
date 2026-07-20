# 🖥️ Flask Web Application

<p align="center">
  <b>A full-stack Flask educational management platform built with Python, Jinja2, and MongoDB.</b><br>
  Designed to explore backend development, API integration, NoSQL databases, and dynamic web rendering.
</p>

---

<h2>📘 Project Overview</h2>

<p>
<b>Flask Web Application</b> is a full-stack web project developed using the Flask framework as part of the <b><a href="https://github.com/Asabeneh/30-Days-Of-Python" target="_blank">30 Days Of Python</a></b> learning journey by <b>Asabeneh Yetayeh</b>.
</p>

<p>
The application was created as a practical exploration of web development concepts using Python. The primary objective was to move beyond basic scripting and understand how backend systems communicate with databases, process user input, and dynamically generate web content.
</p>

<p>
The project simulates an educational institute management system where administrators can manage student information through a browser-based interface. Users can create, update, view, and delete student records stored inside a MongoDB NoSQL database.
</p>

<p>
Alongside database management, the application also includes additional learning-focused features such as text analysis tools, review collection, and dashboard visualisation. These features were implemented to gain practical experience with Flask routing, Jinja2 templates, form handling, and data processing.
</p>

<p>
This project represents a second iteration of the original website attempt. The previous version focused primarily on getting functionality working, whereas this rewrite placed greater emphasis on cleaner organisation, improved structure, and better separation between application logic and presentation layers.
</p>

---

<h2>🧠 Development Goals & Learning Objectives</h2>

<p>
The application was designed around several core learning objectives:
</p>

<ul>
  <li>
    <b>Backend Development:</b>
    Understanding Flask routing, request handling, and server-side application flow.
  </li>

  <li>
    <b>Database Integration:</b>
    Learning how Python applications communicate with NoSQL databases through MongoDB.
  </li>

  <li>
    <b>Template Rendering:</b>
    Using Jinja2 to dynamically generate HTML pages from Python data.
  </li>

  <li>
    <b>Application Structure:</b>
    Separating templates, static assets, and Python logic into organised project layers.
  </li>

  <li>
    <b>CRUD Operations:</b>
    Implementing create, read, update, and delete functionality for stored records.
  </li>
</ul>

---

<h2>⚡ Features</h2>

<ul>
  <li>Educational student management system.</li>
  <li>Add new student records to MongoDB.</li>
  <li>View stored student information.</li>
  <li>Modify existing student details.</li>
  <li>Delete student records.</li>
  <li>Text analysis tool for analysing written passages.</li>
  <li>Dynamic page rendering using Jinja2 templates.</li>
  <li>Review submission and dashboard functionality.</li>
  <li>Python-powered data processing.</li>
  <li>Responsive browser-based interface.</li>
</ul>

---

<h2>🏗️ Application Architecture</h2>

<p>
The application follows a traditional Flask structure where backend logic, templates, and static resources are separated.
</p>

<pre>
User Browser
      |
      ↓
Flask Routes
      |
      ↓
Python Application Logic
      |
      ↓
MongoDB Database
      |
      ↓
Dynamic Jinja2 Templates
</pre>

<p>
The workflow follows this pattern:
</p>

<ol>
  <li>User interacts with a web form.</li>
  <li>Flask receives the request.</li>
  <li>Python validates and processes the data.</li>
  <li>MongoDB stores or retrieves information.</li>
  <li>Jinja2 renders the updated page.</li>
</ol>

---

<h2>🧩 Folder Structure</h2>

<pre>
Flask-Web-Application/

│
├── app.py                         # Main Flask application
│
├── python_functions/
│   ├── __init__.py
│   ├── review_dashboard_function.py
│   └── text_analyser_functions.py
│
├── templates/
│   ├── layout.html                # Base HTML layout
│   │
│   ├── partials/
│   │   ├── footer.html
│   │   ├── main_nav.ico
│   │   └── database_nav.ico
│   │
│   └── pages/
│       ├── about.html
│       ├── add_new_student.html
│       ├── database_home.html
│       ├── home.html
│       ├── leave_a_review.html
│       ├── review_dashboard.html
│       ├── student_database_home.html
│       ├── testimonial_database_home.html
│       ├── text_analyser.html
│       └── update_student.html
│
├── static/
│   ├── img/
│   │   ├── favicon.ico
│   │   ├── female.png
│   │   ├── graph_chart.png
│   │   ├── male.png
│   │   ├── male2.png
│   │   ├── pie_chart.png
│   │   ├── preview.png
│   │   ├── student.png
│   │   └── Sheikh_Logo_3.png
│   │
│   └── css/
│       └── main.css
│
├── requirements.txt
├── README.md
└── LICENSE
</pre>

---

<h2>🚀 Installation & Setup</h2>

<ol>

<li>
Ensure <b>Python 3.13</b> is installed on your system.
</li>

<li>
Clone the repository:

<pre>
git clone https://github.com/Sheikh-H/Flask-Website.git
</pre>

</li>

<li>
Navigate into the project directory:

<pre>
cd Flask-Website
</pre>

</li>

<li>
Install required dependencies:

<pre>
pip install -r requirements.txt
</pre>

</li>

<li>
Run the Flask application:

<pre>
python app.py
</pre>

</li>

<li>
Open your browser:

<pre>
localhost:5000/
</pre>

</li>

</ol>

---

<h2>🌐 Live Deployment</h2>

<p>
The application can also be viewed through its deployed version:
</p>

<pre>
https://flask-website-xfss.onrender.com/
</pre>

---

<h2>📸 Application Preview</h2>

<p align="center">
<img src="/static/img/preview.png" alt="Application Preview" width="700">
</p>

---

<h2>⚙️ Core Application Components</h2>

<h3>🐍 Flask Backend</h3>

<p>
The Flask backend manages:
</p>

<ul>
  <li>Application routing.</li>
  <li>User requests.</li>
  <li>Form submissions.</li>
  <li>Database communication.</li>
  <li>Template rendering.</li>
</ul>

---

<h3>🗄️ MongoDB Database Integration</h3>

<p>
The application uses MongoDB as a NoSQL database for storing student information and user-generated content.
</p>

<p>
The database layer provides:
</p>

<ul>
<li>Student record storage.</li>
<li>Record retrieval.</li>
<li>Student updates.</li>
<li>Student deletion.</li>
</ul>

---

<h3>🖼️ Jinja2 Template System</h3>

<p>
Jinja2 is used to dynamically populate HTML templates with Python-generated data.
</p>

<p>
This allows the application to:
</p>

<ul>
<li>Generate dynamic pages.</li>
<li>Display database records.</li>
<li>Reuse common layouts.</li>
<li>Create interactive forms.</li>
</ul>

---

<h3>📝 Text Analysis System</h3>

<p>
The built-in text analyser processes user-provided passages and extracts useful information using Python logic.
</p>

Features include:

<ul>
<li>Text statistics.</li>
<li>Word analysis.</li>
<li>Character counting.</li>
<li>Basic content processing.</li>
</ul>

---

<h2>🧪 Current Limitations & Future Improvements</h2>

<p>
Although the application successfully demonstrates Flask and database integration, several improvements could be implemented in future versions.
</p>

<ul>
<li>User authentication and account management.</li>
<li>Improved database security.</li>
<li>Expanded student management features.</li>
<li>REST API integration.</li>
<li>Better frontend styling.</li>
<li>Production deployment configuration.</li>
<li>Automated testing.</li>
</ul>

---

<h2>🧰 Requirements & Dependencies</h2>

<ul>

<li>
<b>Python Runtime:</b> Python 3.13
</li>

<li>
<b>Framework:</b> Flask
</li>

<li>
<b>Database:</b> MongoDB
</li>

<li>
<b>Template Engine:</b> Jinja2
</li>

<li>
<b>Libraries:</b> Listed inside <code>requirements.txt</code>
</li>

</ul>

---

## 📄 Licence

<p>
  This project is licensed under the <b>MIT Licence</b> — see the <a href="./LICENCE">LICENCE</a> file for details.
</p>

<pre>
MIT Licence

Copyright (c) 2026 Sheikh Hussain

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</pre>

---

## Footnote

<div align="center" style="border: 1px solid green; padding: 10px; border-radius: 5px;">
  <p>🗣️ Feel free to follow, connect, and chat!</p>
  <a class="header-badge" target="_blank" href="https://github.com/Sheikh-H"><img src="https://img.shields.io/badge/GitHub-376e00?style=flat&logo=github&logoColor=white" alt="GitHub"></a>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/sheikh-hussain/"><img src="https://img.shields.io/badge/LinkedIn-376e00?style=flat&logo=LinkedIn&logoColor=white" alt="LinkedIn"></a>
  <a class="header-badge" target="_blank" href="mailto:sheikh.hussain1155@gmail.com"><img src="https://img.shields.io/badge/Gmail-376e00?style=flat&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a class="header-badge" target="_blank" href="https://sheikh-hussain.onrender.com/"><img src="https://img.shields.io/badge/Portfolio-376e00?style=flat&logo=github&logoColor=white" alt="Portfolio"></a>
</div>

<div align="center">
  <a href="https://sheikh-hussain.onrender.com/" target="_blank">By Sheikh Hussain 💚</a>
</div>

---

<h2 align="center">⭐ If you like this project, please give it a star on GitHub!</h2>
