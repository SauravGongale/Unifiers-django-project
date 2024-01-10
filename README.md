#Django-CRM

To Run the Project

Create Virtual env
`python -m venv env`

Activate it
`.\env\Scripts\activate`

Install dependencies
`pip install -r requirements.txt`

Migrate Data to Sqlite
`python manage.py migrate`

Create SuperUser
`python manage.py createsuperuser`

Run App
`python manage.py runserver`

Create Agents with Admin Panel
`http://127.0.0.1:8000/admin/`

Add Leads/Data with leads page
`http://127.0.0.1:8000/leads/`
