What's included

Full Flask app with role-based auth (job seeker / employer / admin).

SQLite database (auto-created on first run).

Features: register/login, post jobs (employers), search/filter jobs, apply (job seekers), employer dashboard (view applications), admin dashboard.

Templates using Bootstrap (CDN) and a small CSS file.

Demo users created automatically on first run:

Admin: admin@example.com / adminpass

Employer: employer@example.com / employerpass

Jobseeker: seeker@example.com / seekerpass

How to get the project

Download the ZIP I generated: Download Job Portal (ZIP)

Quick start (run locally)

Unzip and enter folder:

unzip job_portal.zip
cd job_portal


Create & activate virtualenv:

python3 -m venv venv
source venv/bin/activate      # Windows: venv\\Scripts\\activate


Install dependencies:

pip install -r requirements.txt


Run the app:

python app.py


Open http://127.0.0.1:5000/ in your browser.

Files I created (high level)

app.py — main Flask app & routes

models.py — SQLAlchemy models (User, Job, Application)

forms.py — WTForms definitions

templates/*.html — Jinja2 templates (base, index, register, login, job detail, dashboards)

static/styles.css — small stylesheet

requirements.txt, README.md
