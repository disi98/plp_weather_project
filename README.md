# PLP WEATHER APP

## Project Structure

        src/
        ---core/
        ------migrations/
        ------templates/
        ---------core/base.html
        ---------core/index.html
        ------admin.py
        ------models.py
        ------tests.py
        ------urls.py
        ------views.py
        ---src/
        ------asgi.py
        ------wsgi.py
        ------settings.py
        ------db.sqlite3
        ---manage.py
        requirements.txt

Installations
---
- Python environment
    - <code> python -m venv venv </code> for linux terminal. Refer to official python resources for other distros.
- Django
    - Activate the python **env**.
        - e.g. <code> source venv/bin/activate</code> for linux.
    - Run <code> pip install -r requirements.txt</code> to install the latest django version.

Start Server
---
To run the server:
- <code>python src/manage.py runserver </code>