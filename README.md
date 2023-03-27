# api_final
### How to run a project:

Clone the repository and go to it on the command line:

```
git clone git@github.com:andreipcheli/api_final_yatube.git
```

```
cd api_final_yatube
```

Create and activate a virtual environment:

```
python3 -m venv env
```

```
source env/bin/activate
```

```
python3 -m pip install --upgrade pip
```

Install dependencies from the requirements.txt file:
```
pip install -r requirements.txt
```

Complete migrations:

```
python3 manage.py migrate
```

Run project:

```
python3 manage.py runserver
```
